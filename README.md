# functional_programming
Project to learn java functional programming

### Function

It is a functional interface that takes a single argument and returns a value.

- Example:
```java
Function<String, Integer> length = x -> x.length();
```

### BiFunction

It is similar to Function, but it takes two arguments and returns a value.

- Example:
```java
BiFunction<Integer, Integer, Integer> sum = (x, y) -> x + y
```