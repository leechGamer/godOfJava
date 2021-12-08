직접 해봅시다. 
1.
```
int age;
```

2.
```
str
```

3.
```
public class Profile {
  public void setAge(int val) {
    this.age = val;
  }
}
```

4.
```
import java.io.*;

public class Profile {
  public void printName(String name) {
    System.out.println(name);
  }
}
```

5.
```

import java.io.*;

public class Profile {
  public void printAge(int age) {
    System.out.println(age);
  }
}

6.
```
public static void main(String[] args) {
  Profile profile = new Profile();
}

7.
```
public static void main(String[] args) {
  Profile p = new Profile();
  p.setName("Min");
  p.setAge(20);
}
```
8.
```
public static void main(String[] args) {
  Profile p = new Profile();
  p.setName("Min");
  p.setAge(20);
  p.printName();
  p.printAge();
}
```
