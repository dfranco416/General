``` java
import java.util.*;
import java.time.LocalDate;

class Main {
  public static void main(String[] args) {
  Scanner scan = new Scanner(System.in);
    System.out.println("Your name: ");
    String name = scan.nextLine();

    System.out.println("Email: ");
    String email = scan.nextLine();

    LocalDate today = LocalDate.now();

    System.out.println("Your Name is " + name);
    System.out.println("Your Email is" + email);
    System.out.println("Today's Date: "+ today);
  }
}
```
