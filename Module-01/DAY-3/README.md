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
Developed by: PRAVEENA D
RegisterNumber:  212224040248
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
public class Demo {
public void check(int num){
    num=num*num;
    System.out.println(num);
}
public static void main(String[] args) 
    {
        Scanner in = new Scanner(System.in);
        int num=in.nextInt();
    Demo s=new Demo();
    s.check(num);   
    }
}
``` 






## OUTPUT:
<img width="611" height="171" alt="image" src="https://github.com/user-attachments/assets/a19d7978-78fa-4d32-aed0-83fb1f649493" />



## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

