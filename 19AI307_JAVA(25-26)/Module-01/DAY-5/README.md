# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a Java program to calculate the power of a given number.

## AIM:
To write a Java program to calculate the power of a given number.

## ALGORITHM :
```
1.Start the program.
2.Import the necessary package 'java.util'
3.Read the base number.
4.Read the exponent value.
5.Initialize a variable power = 1.
6.Repeat a loop from 1 to exponent:
   ->Multiply power = power * base.
7.After the loop ends, print the value of power.
8.Stop the program.
```

## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: Mythili D
RegisterNumber: 212222040104
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

public class PowerOfNumber {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        double base = sc.nextDouble();
        double exponent = sc.nextDouble();
        double result = Math.pow(base, exponent);
        System.out.println(base + " raised to the power of " + exponent + " is: " + result);

    }
}
```





## OUTPUT:
<img width="1283" height="324" alt="image" src="https://github.com/user-attachments/assets/d9904226-7403-4a8b-bbf6-669fcd2fedb7" />



## RESULT:
The program successfully calculates and displays the power of a given number using a loop in Java.

