# Stream Lab 3

## Instructions

Create a method called the `divisorsSum` that has the following parameters:

- `start`: starting point of range.
- `end`: ending point of range (inclusive).
- `a`: first divisor.
- `b`: second divisor.

Your method should return the sum of the numbers in the range (`start` to `end`)
that are divisible by `a` or `b`. Here are a couple of example outputs:

```java
// sumOfDivisors(5, 15, 3, 5) -> 57
// sumOfDivisors(2, 8, 2, 3) -> 23
```

## Starter Code

```java
public class Main {
    public static int sumOfDivisors(int start, int end, int a, int b) {

    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int start = scanner.nextInt();
        int end = scanner.nextInt();
        int a = scanner.nextInt();
        int b = scanner.nextInt();

        System.out.println(sum(start, end, a, b));
    }
}
```
