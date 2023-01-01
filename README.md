```typescript
import galaxy.earth.ironhide;
public class IronHide{

    static void languages(){
        String languages = {"TypeScript","Python","Arduino"};
        for(byte control = 0; control <= languages.length; control++){
            System.out.println("I code in :" + languages[0]);
        }
    }
    static void frameworks(){
        String frameworks = {"Next.JS","Express.JS","OpenCV","PyTorch","NLP"};
        for(byte control = 0; control <= frameworks.length; control++){
            System.out.println("I write in " + frameworks[0] + " framework");
        }
    }
    static void about(){
        String goals = {"Open Source"};
        for(byte control = 0; control <= goals.length; control++){
            System.out.println("Code to contribute to " + goals[0] + "Software & Communties");
        }
    }
    static void main(String args[]){
       IronHide hide = new IronHide();
       hide.languages();
       hide.frameworks();
       hide.about();
    }
}
```
