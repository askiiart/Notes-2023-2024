# Methods

## Defining a method

```java
public static void myMethod() {
    // code
}
```

The keywords are very important!

Keyword 1: `public` or `private`

- `public` means that the method can be accessed from anywhere.
- `private` means that the method can only be accessed from within the class.

Keyword 2: `static` or nothing

- `static` means that the method can be accessed without an instance of the class. But it can only access static variables.

Keyword 3: `void` or any type

- `void` means that the method doesn't return anything.
- Any other type means that the method returns that type. For example, `int` means that the method returns an integer, and `ArrayList<String>` means that the method returns an ArrayList of Strings.

## Examples

### Ackermann function

```java
public static int ackermann(int m, int n) {
    if (m == 0) {
        return n + 1;
    } else if (n == 0) {
        return ackermann(m - 1, 1);
    } else {
        return ackermann(m - 1, ackermann(m, n - 1));
    }
}
```
