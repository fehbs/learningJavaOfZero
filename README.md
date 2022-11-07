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

  
    
    
    
    






