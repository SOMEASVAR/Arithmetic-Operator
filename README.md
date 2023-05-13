# Experiment-1

# Arithmetic Operations

# Aim:
  To write a Java program to perform arithmetic operations on the given numbers.
  
# Algorithm:

Step 1 :Open Intelli J application or any other code editor.

Step 2 : Create a class and name it ArithmeticOperations.

Step 3 : Using Scanner, we can input numbers from the user.

Step 4 : Write the logic for the program using arithmetic operations.

Step 5 : Display the operations done the input numbers in the terminal.

## Program:
```
Program developed by: SOMEASVAR.R
Register No: 212221230103;
```
```
import java.util.Scanner;
public class arithmetic_operator
{
    public static void main(String[] args)
    {
        Scanner br= new Scanner(System.in);
        System.out.println("Enter the value of first number:");
        int a=br.nextInt();
        System.out.println("Enter the value of second number");
        int b=br.nextInt();
        int add=a+b;
        int sub=a-b;
        int mul=a*b;
        int div=a/b;
        int mol=a%b;
        System.out.println("Arithmetic operators are as follows:");
        System.out.println(" ");
        System.out.println("Addition of given two numbers: "+add);
        System.out.println("Subtraction of given two numbers: "+sub);
        System.out.println("Multiplication of given two numbers: "+mul);
        System.out.println("Division of given two numbers: "+div);
        System.out.println("Modulus of given two numbers: "+mol);
    }
}
```
## Output:
![image](https://github.com/SOMEASVAR/Arithmetic-Operator/assets/93434149/f634459a-57e0-466c-aa63-42feb5c7304c)
## Result :
  We have successfully created a Java program to display the arithmetic operations on numbers.
