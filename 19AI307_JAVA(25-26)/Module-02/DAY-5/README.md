# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:
Create a class Employee with method display(). Inside display(), return the current object using this. Create another method that calls display().printName()

## AIM:
To create a class Employee with a method display() that returns the current object using this, and another method that calls display().printName().

## ALGORITHM :
```
1.Start the program.
2.Import the necessary package 'java.util'
3.Create a class named Employee.
4.Declare a variable to store employee name.
5.Create a method display() that:
   ->Prints the name.
   ->Returns the current object using this.
6.Create a method printName() to print a message.
7.In another method (say callMethods()), call:
display().printName()
8.In main() method create an object and call callMethods().
9.End the program.
```




## PROGRAM:
 ```
/*
Program to implement a Access Modifiers using Java
Developed by: Mythili D
RegisterNumber: 212222040104
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

class Employee {
    String name;

    void setName(String name) {
        this.name = name; 
    }

    Employee display() {
        return this; 
    }

    void printName() {
        System.out.println("Employee Name: " + name);
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String empName = sc.nextLine();

        Employee emp = new Employee();
        emp.setName(empName);
        emp.display().printName(); // chain call
    }
}
```

## OUTPUT:

<img width="1207" height="296" alt="image" src="https://github.com/user-attachments/assets/04e080f8-92e0-4b1e-a789-6079d572d2af" />



## RESULT:
The program successfully demonstrates returning the current object using this and chaining method calls using display().printName() in Java.
