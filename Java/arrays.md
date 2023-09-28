# Arrays

## Declaring and initializing arrays

Declaring:

```java
int[] myArray;
```

Initializing:

```java
int[] myArray = new int[5];
```

Hardcoding the values of an array:

```java
int[] myArray = {1, 2, 3, 4, 5};
```

## Variables

| Variable | Type | Description             |
| -------- | ---- | ----------------------- |
| length   | int  | The length of the array |

## For-each loop

```java
for (int item : myArray) {
    System.out.println(item);
}
```

## Accessing and modifying elements

Note that arrays start at zero (except in Lua for some reason).

### Accessing

```java
for (int i = 0; i < myArray.length; i++) {
    System.out.println(i + ": " + myArray[i]);
}
```

### Modifying

```java
myArray[0] = 1;
myArray[1] = 2;
myArray[2] = 3;
```
