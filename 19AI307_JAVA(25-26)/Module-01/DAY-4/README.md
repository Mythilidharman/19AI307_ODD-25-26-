# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java Program to count Even and Odd Numbers in an Array.

## AIM:
To write a Java program to count the number of even and odd elements present in an array.

## ALGORITHM :
```
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the size of the array.
4.Read the array elements from the user.
5.Initialize two counters: even = 0, odd = 0.
6.Traverse the array using a loop.
7.For each element:
  ->If the element is divisible by 2, increment even.
  ->Else increment odd.
8.Display the total count of even and odd numbers.
9.Stop the program.
```



## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: Mythili D
RegisterNumber: 212222040104
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

public class CountEvenOdd {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        int n = sc.nextInt();
        int[] arr = new int[n];

        int evenCount = 0, oddCount = 0;
        for (int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
            if (arr[i] % 2 == 0) {
                evenCount++;
            } else {
                oddCount++;
            }
        }

        System.out.println("Number of even elements: " + evenCount);
        System.out.println("Number of odd elements: " + oddCount);
    }
}
```

## OUTPUT:
<img width="1272" height="704" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/2e1e034b-3d1c-492b-ac2b-223b0cdb855b" />



## RESULT:
The program successfully counts and prints the total number of even and odd elements present in an array.
