[slide]
# The break Operator
Used for prematurely exiting the loop

Can only be executed from the loop's body

When break is executed, the code inside the loop's body after it is skipped (does not execute)
```java
while (true) {
  // Some code …
  if (…) break;
  // More code …
}
```
# Example
Sum numbers until 0 is entered
```java
long sum = 0;
while (true) {
  int nextNum = scanner.nextInt();
  if (nextNum == 0) {
      // The last number was reached
      break;
  }
  sum += nextNum;
  System.out.println("Sum: " + sum);
}
```
[/slide]
