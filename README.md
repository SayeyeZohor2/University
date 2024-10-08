# LMS
سیستم جامع مدیریت یادگیری به زبان جاوا


![Lovely Programming Language => java](https://github.com/SayeyeZohor2/University/blob/main/picture/java-programming-language-script-code-260nw-1119262511.jpg?raw=true)

### لذت برنامه‌نویسی با جاوا!

در اینجا یک کد جالب با جاوا آورده شده که برخی از ویژگی‌های جذاب این زبان را به نمایش می‌گذارد:


```java
import java.util.Arrays;
import java.util.List;

public class JavaFun {
    public static void main(String[] args) {
        List<String> favoriteThings = Arrays.asList("Code", "Coffee", "Challenges");
        printFavoriteThings(favoriteThings);

        // ایجاد شیء از کلاس JavaFun و فراخوانی متد doSomethingCool
        JavaFun javaFunInstance = new JavaFun();
        javaFunInstance.doSomethingCool();
    }

    private static void printFavoriteThings(List<String> favoriteThings) {
        favoriteThings.stream()
            .map(String::toUpperCase)
            .forEach(thing -> System.out.println("I love " + thing + "!"));
    }

    private void doSomethingCool() {
        System.out.println("Let’s keep exploring the world of Java!");
    }
}
```

```java
I love CODE!
I love COFFEE!
I love CHALLENGES!
Let’s keep exploring the world of Java!
```



در کد جاوا فوق، از امکانات زیر استفاده شده است:

1. **کتابخانه‌های استاندارد جاوا**:
   - `import java.util.Arrays;`
   - `import java.util.List;`

2. **استفاده از کلاس `List` و متد `Arrays.asList`**:
   - برای ایجاد لیست از رشته‌ها: `List<String> favoriteThings = Arrays.asList("Code", "Coffee", "Challenges");`

3. **استفاده از `Stream API`**:
   - `favoriteThings.stream()` برای ایجاد (Stream) از لیست.
   - `map(String::toUpperCase)` برای تبدیل هر رشته به حروف بزرگ.
   - `forEach(thing -> System.out.println("I love " + thing + "!"))` برای اعمال عملی روی هر عنصر در جریان.

4. **تعریف متد `static`**:
   - `private static void printFavoriteThings(List<String> favoriteThings)` برای متدی که نیازی به وضعیت شیء ندارد و به طور مستقیم از متد `main` فراخوانی می‌شود.

5. **تعریف متد غیر `static`**:
   - `private void doSomethingCool()` برای متدی که به وضعیت شیء وابسته است و از شیء کلاس فراخوانی می‌شود.

6. **ایجاد و استفاده از شیء کلاس**:
   - `JavaFun javaFunInstance = new JavaFun();` برای ایجاد یک شیء از کلاس `JavaFun`.
   - `javaFunInstance.doSomethingCool();` برای فراخوانی متد غیر `static` از شیء ساخته شده.

# intellij Editor ...
![Lovely Programming Language => java](https://github.com/SayeyeZohor2/University/blob/main/picture/Screenshot%202024-08-14%20190202.png)
![Lovely Programming Language => java](https://github.com/SayeyeZohor2/University/blob/main/picture/Screenshot%202024-08-14%20190253.png)

![Lovely Programming Language => java](https://github.com/SayeyeZohor2/University/blob/main/picture/pexels-photo-4017430.webp)

