[slide]
# While Loop
Control flow statement

* Executes code repeatedly while a condition is true

```java
while (condition) {
   // Body of the loop
}
```
# Example: While Loop
Print the numbers from 1 to 5
```java
int i = 1;
while (i <= 5) {
   System.out.println(i);
   i++;
}
```
[/slide]
[slide]
# While or For?
***while*** and ***for*** loops **repeat** blocks of **code**

Use ***for*** when you know in advance the **number of repetitions**

* For example, repeat exactly 10 times

Use ***while*** when you don't know when the **exit condition** will be met

* For example, repeat until 0 is reached
[/slide]
[sldie]
# The "break" Operator
Used for prematurely exiting the loop

Can only be executed from the body, during an iteration of the loop

break immediately exits from the loop

* The rest of the loop body is skipped
```java
int i = 1;
while (true) {
  if (i > 10) break;
  i++;
}
```
[/slide]
