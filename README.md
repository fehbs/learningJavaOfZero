# Learning Java of Zero on the Android
 🤘 🎃 ☕ 🔥🔥
##
#### 🖖😎 I like to take my notes!
##

public class HelloJava {
    
public static void main(String[] args){

    System.out.println("I'm learning Java!");

    }

}
##
##
# Variables


int age = 28;

char grade = 'A';

boolean late = true;

byte = 20;

long num = 1234567;

short no = 10;

float k = (float)12.5;

double pi = 3.14;*/


int i = 10; // type int

char ch = 'a'; // type is char

j = 20; // won't compile, no type is given

char name = "Lill"; // won't compile, data type


// Value cannot be changed:

final double PI = 3.14;

double PI = 3.14;

double price = 5.75;

* Math Operations

 (+) addition

 (-) subtraction

 (*) multiplication

 (/) division

 (%) modulo (yelds the remainder)

int a = 20;

int b = 10;

int result;

result = a + b; // 30

result = a - b; // 10

result = a * b; // 200

result = a / b; // 2

result a % b; // 0

 * Comparison Operators

( > greater than )

( < less than )

( >= greater than or equal to )

( <= less than or equal to )

( == equal to )

( != not equal to )

int a = 5;

int b = 3;

boolean result = a > b;

//result now holds the boolean value true

Compound Assignment Operators inclue:

+=, -=, *=, /=, and %= .

int number = 5;

number += 3; // Value is now 8

number -= 4; // Value is now 4

number *= 6; // Value is now 24

number /= 2; // Value is now 12

number %= 7; // Value is now 5

Increment and Decrement Operators

int numApples = 5;

numApples++; // Value is now 6

int numOranges = 5;

numOranges--; // Value is now 4

##
##
# Object-Oriented Java

// Java object's state and behavior


public class Person {

// state of an object

 int age;

 String name;
    
// behavior of an object

public void set_value() {

 age = 20;

 name = "Dracula";

    }
public void get_value() {

 System.out.println("Age is"+age);

 System.out.println("Name is"+name);

}

    // main method

public static void mai(String[]args) {

// creates a new person object

 Person p = new Person();

// changes state through behavior

 p.set_value();

    }


}

// Java instance


public class Person {

 int age;

 String name;
    
// Constructor method

 public Person(int age, String name) {

  this.age = age;

  this.name = name;

  }
    
public static void main(String[] args) {

 Person Martin = new Person(25,"Martin");

 Person Doc = new Person(49,"Doc"); 

     }

}
    
// Java dot notation

public class Person {

 int age;
 
public static void mai(String[]args) {

 Person p = new Person();
 
 // here we use notation to set age

 p.age = 20;
 
// here we use dot notation to access
 age and print

System.out.println("Age is"+p.age);

// Output: Age is 20

    }

 
}

##
##
# Condicionals and Control Flow

* else Statement

boolean condition1 = false;

if(condition1) {

    System.out.println("condition1 is true");
}

else {

    System.out.println("condition1 is not true");

}

// Prints: condition is not true

* else if Statements

int testScore = 76;

char grade;


if(testScore >= 90) {

    grade = 'A';

} else if (testScore >= 80) {

    grade = 'B';

} else if (testScore >= 70) {

    grade = 'C';

} else if (testScore >= 60) {

    grade = 'D';

} else {

    grade =  'F';

}

System.out.println("Grade:"+grade);

// Prints: C 

if Statement

if(true) {

    System.out.println("This code executes");
}

//Prints: This code executes

if(false) {

    System.out.println("This code does not execute");
}

// There is not output for the above statement

  
##
##

#   Arrays and ArraysLists

* Index

int[] marks = {50, 55, 60, 70, 80};

System.out.println(marks[0]);

// Output: 50

System.out.println(marks[4]);

// Output: 80

* Arrays

// Create an array of 5 int elements

int[] marks = {10, 20, 30, 40, 50};

Array creation in Java

int[] age = {20, 21, 30};

int[] marks = new int[3];

marks[0] = 50;

marks[1] = 70;

marks[2] = 93;

Changing an Element Value

int[] nums = {1, 2, 0, 4};

// Change value at index 2

nums[2] = 3;

* Java ArrayList

// import the ArrayList package

import java.util.ArrayList;

// create an ArrayList called students

ArrayList<String> students = new ArrayList<String>();

Modifying ArrayLists in Java

public class Studentd {

 public static void main(String[] args) {
     
// create an ArrayList called studentList, wich initialy holds []

       ArrayList<String>studentList = new ArrayList<String>();
       
 // add students to the ArrayList
 
 studentList.add("Dracula");

 studentList.add("Poe");

 studentList.add("LoveCraft");

 studentList.add("MaryShelley");
 
 // remove Dracula from thr ArrayList, then Mina
 
 studentList.remove(0);

 studenttList.remove("Mina");
 
 // studentList now holds [LoveCraft, MaryShelley]
 
System.out.println(studentList);
 
    }
 
}

##
##
# For-each statement in Java

// array of numbers

 int[] numbers = {1, 2, 3, 4, 5};

// for-each loop that prints each number in numbers

// int num is the handle while numbers is the source array

 for (int num : numbers) {

     System.out.println(num);

}

##
##

    
    
    






