## Hi there 👋

```java
import java.util.List;
import java.util.ArrayList;

class JoseCarlosGalvanKamey {
    public String name = "Jose Carlos Galvan Kamey";
    public String profession = "Software Developer";
    public List<String> technologies = new ArrayList<>();

    public JoseCarlosGalvanKamey() {
        technologies.add("Java");
        technologies.add("CPP");
    }

    public void introduction() {
        System.out.println("Hello, I'm " + name + " 👋");
        System.out.println("I'm a " + profession + " passionate about competitive programming.");
    }

    public static void main(String[] args) {
        JoseCarlosGalvanKamey dev = new JoseCarlosGalvanKamey();
        dev.introduction();
    }
}
```
