[slide]
# Infinite While Loops
Infinite loop = repeating a block of code an infinite number of times

Infinite while loops: use true as loop condition
```java
while (true) {
  // Commands
}
```
# Example: Bug
```java
String command = scanner.nextLine();
while (!command.equals("End")) {
   System.out.println("Executing: " + command);
```
# Example: Bug Fixed
```java
String command = scanner.nextLine()
while (!command.equals("End")) {
   System.out.println("Executing: " + command);
   command = scanner.nextLine();
}
```
# Example: Finite Loop with Break
```java
String command = scanner.nextLine()
while (!command.equals("End")) {
   System.out.println("Executing: " + command);
   command = scanner.nextLine();
}
```
# Example: Infinite Loop with Break
```java
while (true) {
  String command = scanner.nextLine();
  if (command.equals("End"))
    break;
  System.out.println("Executing: " + command);
}
```
[/slide]
