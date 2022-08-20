# FizzBuzz

This is a classic. And a good starting point.

## Prequirements

* Write a programm that prints the numbers from 1 to 100.

```java
    public static void main(String[] args) {
        for (int i = 1; i <= 100 ; i++) {
            System.out.println(i);
        }
    }
```

* Now replace the "println" statement with a fizzbuzz-function:

```java
    public static void main(String[] args) {
        for (int i = 1; i <= 100 ; i++) {
            fizzbuzz(i);
        }
    }
```

## What should it do?

* For multiples of 3 it returns "Fizz" instead of the number
* For multiples of 5 it returns "Buzz" instead of the number
* For multiples of both 3 and 5 (like 15) it returns "FizzBuzz" instead of the number

**Remember to start with baby steps and a failing test before adding any real code!**

