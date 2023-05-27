# table
# EXP-5 -> CREATING TABLE TO STORE EMPLOYEE INFORMATION

## AIM:
TO Write a Java Program To Store a Details
java
Write a program that would print the information (name, year of joining, salary, address) of three employees 
by creating a class named 'Employee'. The output should be as follows:
Name           Year of joining                Address
 Robert              1994                  64C- WallsStreat
 Sam                 2000                  68D- WallsStreat
 John                1999                  26B- WallsStreat
 

## SOFTWARE REQUIRED :
IntelliJ IDEA COMMUNITY EDITION

## ALGORITHM:
1) Define a class named "Employee" with instance variables to store employee details such as name,year of joining,address
2) Create methods within the "Employee" class to get and set the values of these instance variables.
3) Instantiate an "Employee" object for each employee and set their details using the setter methods.
4) Create a collection (e.g., an ArrayList) to store the employee objects.
5) Prompt the user for input to gather the details of each employee.
6) Create a loop to repeat.After the loop ends, you can perform operations on the collection, such as searching for specific employees, displaying all employee details.

## PROGRAM:
```
java
class Employee
{
    String Name;
    int Year;
    String Address;
    Employee(String nam,int years, String addr)
    {
        Name=nam;
        Year=years;
        Address=addr;
    }
    void Sam()
    {
        System.out.println(Name+ " " +Year + " " +Address);
    }
    void Robert()
    {
        System.out.println(Name+ " " +Year + " " +Address);
    }
    void John()
    {
        System.out.println(Name+ " "+Year + " " +Address);
    }
}
class EmployeeDetails
{
    public static void main(String args[])
    {
        System.out.println("Name    " + "Year of Joining   " + "    Address" );
        Employee e=new Employee("Sam         ", 2000, "        68D-WallsStreet");
        e.Sam();
        Employee e1=new Employee("Robert      ", 1994, "        64C-WallsStreet");
        e1.Robert();
        Employee e2=new Employee("John        ", 2002, "        70F-WallsStreet");
        e2.Sam();
    }
}
```



## OUTPUT:

<img width="286" alt="image" src="https://github.com/Monisha-11/EXP-5--JAVA/assets/93427240/a42a07aa-736d-4c9a-951c-2399cd8b3d34">

## RESULT:

Thus The Output Is Verfied.
