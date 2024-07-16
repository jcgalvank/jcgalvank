## Hi there 👋

```java
import java.util.List;
import java.util.ArrayList;

class JoseCarlosGalvanKamey {
    public String name = "Jose Carlos Galvan Kamey";
    public String profession = "Software Developer";
    public List<String> technologies = new ArrayList<>();

    // Constructor to initialize technologies list
    public JoseCarlosGalvanKamey() {
        technologies.add("Java");
    }

    public void introduction() {
        System.out.println("Hello, I'm " + name + " 👋");
        System.out.println("I'm a " + profession + " passionate about continuous learning and competitive programming.");
    }

    public static void main(String[] args) {
        JoseCarlosGalvanKamey dev = new JoseCarlosGalvanKamey();
        dev.introduction();
    }
}
```
