# EXP-1-Java-program-to-print-the-Arithmetic-operations

## AIM:
To write a java program to print the arithmetic operations.

## ALGORITHM: 
### Step 1:
Import the necessary packages
### Step 2: 
Get the two values from the user
### Step 3: 
Calculate the basic arithmetic operations using two variables
### Step 4:  
Print the result
### Step 5: 
End the program
## PROGRAM:

~~~
import java.util.*;
public class Main
{
    public static void main(String[] args) {
        Scanner s=new Scanner(System.in);
        int a=s.nextInt();
        int b=s.nextInt();
        int sum,mul,diff,div,mod;
        sum=a+b;
        diff=a-b;
        mul=a*b;
        div=a/b;
        mod=a%b;
        System.out.println("Sum = "+sum);
        System.out.println("Difference = "+diff);
        System.out.println("Product = "+mul);
        System.out.println("Division = "+div);
        System.out.println("Remainder = "+mod);
    }
}
~~~

## OUTPUT:
![1](https://github.com/abdulwasih2003/EXP-1-Java-program-to-print-the-Arithmetic-operations/assets/91781810/604c6f58-02f3-4027-ae3c-c03be9dc77b5)

## RESULT:
Thus the java program to print the arithmetic operations is successful.



