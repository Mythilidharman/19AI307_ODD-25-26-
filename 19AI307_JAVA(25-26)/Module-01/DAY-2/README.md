# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
A pirate ship has a code lock that only opens if:

->The input code is even, and

   -If it is less than 100, say "Weak Code".

   -If it is between 100 and 999, say "Strong Code".

->If the code is odd, deny access -"Access Denied".
## AIM:

To write a Java program to check if the pirate ship lock code is valid based on conditions and display the required message.
## ALGORITHM :
```
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read a number (code) from the user.
4.Check if the number is even.
5.If it is even and less than 100, print "Weak Code".
6.If it is even and between 100 and 999, print "Strong Code".
7.If the number is odd, print "Access Denied".
8.Stop the program.
```


## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: Mythili D
RegisterNumber: 212222040104
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

public class PirateCodeLock {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int code = sc.nextInt(); 

        if (code % 2 == 0) 
        { 
            if (code < 100)
            {
                System.out.println("Weak Code");
            } 
            else if (code >= 100 && code <= 999)
            {
                System.out.println("Strong Code");
            }
            else 
            {
                System.out.println("Access Denied");
            }
        }
        else 
        {
            System.out.println("Access Denied");
        }

        sc.close();
    }
}
```


## OUTPUT:
<img width="1329" height="398" alt="Screenshot (21)" src="https://github.com/user-attachments/assets/e369f567-133e-4ab0-b3c0-135ec76cba10" />



## RESULT:
The program correctly checks the pirate lock code and displays whether it is a Weak Code, Strong Code, or Access Denied based on the given conditions.
