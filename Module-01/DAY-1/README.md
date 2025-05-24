# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Sakthi Navaneetha M.R
RegisterNumber:  212222040138
*/
```

## Sourcecode.java:
class Student
{
    String name;
    String address;
}
public class Main
{
    public static void main(String[] args)
   {
        Student obj= new Student();        
        obj.name="John";
        obj.address="Chennai";
        System.out.println(obj.name+" "+obj.address);
    }
}






## OUTPUT:

https://private-user-images.githubusercontent.com/118344049/438633115-4eeffebe-7759-467e-bf87-ccd21a978cdf.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDgwNTY3NzYsIm5iZiI6MTc0ODA1NjQ3NiwicGF0aCI6Ii8xMTgzNDQwNDkvNDM4NjMzMTE1LTRlZWZmZWJlLTc3NTktNDY3ZS1iZjg3LWNjZDIxYTk3OGNkZi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTI0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUyNFQwMzE0MzZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00OTQzMGY5YTAzZTEyYWZmMzJiYjQ1ZGIzMzM0MjU1ZTNkYjQ2OTRhYTUwMmE5ZjMxZTFkNmVkNjczMzcyYjgyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.2Y8uT5JWTpx8eqMbZhc-qrQoZmjNKrxhMgG5XyHJTTg

## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
