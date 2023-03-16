```java
import java.util.ArrayList;
import java.util.HashMap;
import java.util.Map;

public class YupData {
    public static void main(String[] args) {
        Map<String, Object> YupData = new HashMap<>();
        YupData.put("name", "Yup");
        YupData.put("age", "x");

        ArrayList<String> skills = new ArrayList<>();

        skills.add("None");
        skills.add("Developer Discord Bots");
        skills.add("Professional Sleeper");
        skills.add("Açaí Lover");
        YupData.put("skills", skills);

        Map<String, Object> missions = new HashMap<>();
        missions.put("Make a Discord Bot", true);
        missions.put("Travel Around the World", "loading()");
        YupData.put("missions", missions);

        ArrayList<String> loves = new ArrayList<>();

        loves.add("Açaí");
        loves.add("International Music");
        loves.add("Code");
        YupData.put("loves", loves);

        System.out.println(YupData);
    }
}
```
