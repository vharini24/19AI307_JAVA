# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is equal to 0:
a.	If true, print "Given number is Zero"
b.	If false, print 'num' followed by " is Non-Zero"
6.	End





## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: V.HARINI 
RegisterNumber: 212225040113 
*/
```

## Sourcecode.java:
```

import java.util.Scanner;

class Demo
{
    public static void main(String args[])
    {
        int num;
        Scanner sc = new Scanner(System.in);

        num = sc.nextInt();

        if(num == 0)
            System.out.println("Given number is Zero");
        else
            System.out.println(num + " is Non-Zero");

        sc.close();
    }
}


```



## OUTPUT:
<img width="425" height="162" alt="Screenshot 2026-06-05 135208" src="https://github.com/user-attachments/assets/87a61729-1dc8-4c21-9f35-381d68542a8d" />

<img width="486" height="173" alt="Screenshot 2026-06-05 135245" src="https://github.com/user-attachments/assets/b62480c6-bcad-4869-8572-264cff53a978" />






## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

