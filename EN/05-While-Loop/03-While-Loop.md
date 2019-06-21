[slide]
# Complex Loops
Loops with different steps
```java
for (int i = n; i >= 1; i--) …
```
```java
for (int j = 1; j <= n; j += 2) …
```
```java
for (int k = 1; k <= n; k *= 2) …
```
```java
for (int d = n; d > 0; d /= 2) …
```
[/slide]
[slide]
# Problem: Numbers from N down to 1
[code-task title="Numbers from N down to 1" executionStrategy="java-code" requiresInput]
[code-editor language=java]
```java
import java.util.Scanner;

public class Program {
   public static void main(String[] args) {
      // Write code here
    }
}
```
[/code-editor]
[task-description]

Write a program to print the numbers from N down to 1

* Read an integer number n

* Print the numbers from n down to 1
[/task-description]
[code-io /]
[/code-task]
## Sample Input and Output
|Input|Output|
|-----|------|
|10|10, 9, 8, 7, 6, 5, 4, 3, 2, 1|
[/slide]

[slide]
# Solution: Numbers from N down to 1
[code-task title="Numbers from N down to 1" executionStrategy="java-code" requiresInput]
[code-editor language=java]
```java
import java.util.Scanner;

public class Program {
   public static void main(String[] args) {
      int n = scanner.nextInt();
      for (int i = n; i >= 1; i--)  {
        if (i < n)
          System.out.print(", ");
       System.out.print(i);
      }
      System.out.println();
    }
}
```
[/code-editor]
[task-description]

Write a program to print the numbers from N down to 1

* Read an integer number n

* Print the numbers from n down to 1
[/task-description]
[code-io /]
[/code-task]
## Sample Input and Output
|Input|Output|
|-----|------|
|10|10, 9, 8, 7, 6, 5, 4, 3, 2, 1|
[/slide]

[slide]
# Problem: Numbers from 1 to N with Step 3
[code-task title="Numbers from 1 to N with Step 3" executionStrategy="java-code" requiresInput]
[code-editor language=java]
```java
import java.util.Scanner;

public class Program {
   public static void main(String[] args) {
      // Write code here
    }
}
```
[/code-editor]
[task-description]

Write a program to print the numbers from 1 to n with step 3:

* Read an integer number n

* Print the numbers from 1 to n with step 3
[/task-description]
[code-io /]
[/code-task]
## Sample Input and Output
|Input|Output|
|-----|------|
|10|1, 4, 7, 10|
|7|1, 4, 7|
[/slide]

[slide]
# Solution: Numbers from 1 to N with Step 3
[code-task title="Numbers from 1 to N with Step 3" executionStrategy="java-code" requiresInput]
[code-editor language=java]
```java
import java.util.Scanner;

public class Program {
   public static void main(String[] args) {
      int n = scanner.nextInt();
      for (int i = 1; i <= n; i += 3) {
        if (i > 1)
          System.out.print(", ");
        System.out.print(i);
      }
      System.out.println();
    }
}
```
[/code-editor]
[task-description]

Write a program to print the numbers from 1 to n with step 3:

* Read an integer number n

* Print the numbers from 1 to n with step 3
[/task-description]
[code-io /]
[/code-task]
## Sample Input and Output
|Input|Output|
|-----|------|
|10|1, 4, 7, 10|
|7|1, 4, 7|
[/slide]

[slide]
# Problem: Even Powers of 2
[code-task title="Even Powers of 2" executionStrategy="java-code" requiresInput]
[code-editor language=java]
```java
import java.util.Scanner;

public class Program {
   public static void main(String[] args) {
      // Write code here
    }
}
```
[/code-editor]
[task-description]
Write a program to print the even powers of 2:

* Read a number n

* Print the even powers of 2 up to 2n
[/task-description]
[code-io /]
[/code-task]
## Sample Input and Output
|Input|Output|
|-----|------|
|3|1, 4, 16|
[/slide]

[slide]
# Solution: Even Powers of 2
[code-task title="Even Powers of 2" executionStrategy="java-code" requiresInput]
[code-editor language=java]
```java
import java.util.Scanner;

public class Program {
   public static void main(String[] args) {
      int n = scanner.nextInt();
      int num = 1;
      for (int i = 0; i <= n; i += 2) {
        if (i > 0)
          System.out.print(", ");
        System.out.print(num);
        num = num * 2 * 2;
      }
      System.out.println();
   }
}
```
[/code-editor]
[task-description]
Write a program to print the even powers of 2:

* Read a number n

* Print the even powers of 2 up to 2n
[/task-description]
[code-io /]
[/code-task]
## Sample Input and Output
|Input|Output|
|-----|------|
|3|1, 4, 16|
[/slide]
[slide]
# Do...While Loops
The do … while (…) loop repeats a block of code until an exit condition is met

* The loop body is always executed at least once

while (…) loop uses exit condition at the start

do … while (…) loop uses exit condition at the end
```java
int i = 1;
do {
  System.out.println(i);
  i++;
} while (i <= 10);
```
[/slide]
