<div  align="center">
<img height="87%" width="87%" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original-wordmark.svg" />
          
##

# Learning Java of Zero on the Android
 🤘 🎃 ☕ 🔥🔥
##
#### 🖖😎 I like to take my notes!
##

</div>

<div>

public class HelloJava {
    
public static void main(String[] args){

    System.out.println("I'm learning Java!");

     }

}

</div>

##
##

<div  align="center">

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

</div>

# Methods

public class GbMethod {

 public static void message() {

     System.out.printf("George Boolean is the father of logic!\n");

 }
 
 public static void main(String[] args) {

     System.out.printf("George Boolean is cool!\n");

     message();
 
    System.out.printf("George Boolean inspired me!\n");

    for(int count=1; count <= 3;count++) {

        message();
        
       }

    }

}

##

import java.util.Scanner;

public class menu {
    
    public static void menu() {

        System.out.println("\tClients register: ");
        
        System.out.println("0. End");

        System.out.println("1. Include");

        System.out.println("2. Update");

        System.out.println("3. Remove");

        System.out.println("4. Query");

        System.out.println("Option: ");
    }
    
    public static void include(){

        System.out.println("Include");
    }

    public static void update(){

        System.out.println("Update");
    }

    public static void remove(){

        System.out.println("Remove");
    }

    public static void query(){

        System.out.println("Query");

    }

    public static void main(String[] args){

        int option;

        Scanner input = new Scanner(System.in);
        
        do{
            menu();

            option = input.nextInt();

            switch(option){

                case 1:

                include();

                break;
                
                case 2:

                update();

                break;
                
                case 3:

                remove();

                break;
                
                case 4:

                query();

                break;
                
                default:

                System.out.println("Invalid option.");
            }

        }while(option!=0);
    }
        
}

##
##

# Object-Oriented Java

* Java object's state and behavior


public class Person {

// state of an object

 int age;

 String name;
    
* behavior of an object

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

* Java instance


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
    
* Java dot notation

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


* Constructor Method in Java

public class Maths {

 public Maths() {

  System.out.println("I am contructor");

 }
 
 public static void main(String [] args) 

 {

 System.out.println("I am main");

 Maths obj1 = new Maths();

    }

}

* Creating a new Class instance in Java

public class Person {

 int age;

 // Constructor:

 public Person(int a) {

  age = a;

 }
 
 public static void main(String [] args) 

 {

 // Here, we create a new instance of the person class:

 Person p = new Person(20);
 
 System.out.println("Age is " + p.age); 

    }
 
}


* Reference Data Types

public class Cat {

 public Cat() {

// instructions for creating a Cat instance

 }
 
 public static void main(String[] args) 

 {

// tom is declared with reference data type `Cat` 

 Cat tom = new Cat();

 System.out.println(tom);

     }

}


* Contructor Signatures

// The signatute is `Cat(String furLength, boolean hasClows)`.

public class Cat {

 String furType;

 boolean containsClows;
 
 public Cat(String furLength, boolean hasClows) 

 {

  furType = furLength;

  containsClows = hasClows;
     
 }
 
 public static void main(String [] args) 

  Cat tom = new Cat("Long-hair",true); 

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

import java.util.Scanner;

public class ForforArray{

    public static void main(String[] args){

        int[]number = new int[5];

        int sum = 0;

        Scanner input = new Scanner(System.in);
        
        for(int cont=0; cont<number.length; cont++){

            System.out.print("Enter a number: " + (cont+1) + " : ");

            number[cont] = input.nextInt();

        }

        for(int cont : number){

            sum += cont;
        }

        System.out.println("Result: " + sum);
        
       }
    
}

##
##

# Exceptions and Exception Handling in Java

* Try-Catch Block:

public class Main {

 public static void main(String[] args) {

  int n1, n2;

  try {

    n1 = 0;

    n2 = 10 / n1;

    System.out.println(n2);

    System.out.println("This is the end of try block");

  }

  catch (ArithmeticException e) {

    System.out.println("You can't divide a number by zero");  
  }

  catch (Exception e) {

    System.out.println("Exception ocurred here");

  }
  
  System.out.println(" Exit from try-catch block");

    }

}

##

* Nested Try-Catch Block:

public class Main {

 public static void main(String[] args) {

   try {

     try {
         
       System.out.println("Going to divide");

       int b = 39 / 0;

     }
     
       catch (ArithmeticException e) {

         System.out.println(e);

       }
       
       try {

         int a[] = new int [5];

         a[5] = 4;

       }
         catch(ArrayIndexOutOfBoundsException e) {

           System.out.println(e);
           
         }
         
           System.out.println("Other statement");

         }
         
           catch (Exception e) {

             System.out.println("Handled");

           }
           
           System.out.println("Normal flow...");
    }

}



##
##

# Practicing

### Programa Java estruturado para calcular média escolar.

//importamos a classe Scanner para 
ler os dados(import java.util.Scanner)

import java.util.Scanner;

public class Media {

    public static void main(String args[]) 

    {
        java.util.Scanner nota = new Scanner(System.in);

        float n1, n2, n3, n4, mf;

        System.out.print("Nota 1 : ");

        n1 = nota.nextFloat();

        System.out.print("Nota 2 : ");

        n2 = nota.nextFloat();

        System.out.print("Nota 3 : ");

        n3 = nota.nextFloat();

        System.out.print("Nota 4 : ");

        n4 = nota.nextFloat();

        mf = (n1+n2+n3+n4)/4;

        if(mf >= 7)

        {
            System.out.print("APROVADO!, com ");
        }

        else

        {
            System.out.print("REPROVADO!,  com ");
        }

        System.out.print("media final: " +  mf + " .");
    }

}

##

### Conversor de Temperaturas.

Celsius convertido em:

Kelvin(K), Réaumur(Re), 

Rankine(Ra), Fahrenhert(F).

Fórmulas: 

F = C * 1.8 + 32;

K = C + 273.15;

Re = C * 0.8;

Ra = C * 1.8 + 32 + 459.67 .



public class Temperatura {

 public static void main(String[] args) {

  double C, K, F, Re, Ra;

  C = 2.43;
  
  F = C * 1.8 + 32;

  K = C + 273.15;

  Ra = C * 1.8 + 32 + 459.67;

  Re = C * 0.8;
  
  System.out.println("Fahrenheit: " + F);

  System.out.println("Kelvin: " + K);

  System.out.println("Reaumur: " + Ra);

  System.out.println("Rankine: " + Re);

    }

}

##

### JavaImc 

Menos do que 18,5 Abaixo do peso

Entre 18,5 e 24,9 Peso normal

Entre 25 e 29,9 Sobrepeso

Entre 30 e 34,9 Obesidade grau 1

Entre 35 e 39,9 Obesidade grau 2

Mais do que 40 Obesidade grau 3
##


public class JavaImc {

 public static void main(String[]args) {

    double p, a, i;
    
    p = 68.5;

    a = 18.5;
    
    i = p / (a * a);
    
    if(i <= 18.5) 

    {
        System.out.println("Abaixo do peso: " );

    } else if(i > 18.5 && i <= 24.9) 

    {
        System.out.println("Peso normal: ");

    } else if(i > 25 && i <= 29.9) 

    {
        System.out.println("Sobrepeso: ");

    } else if(i > 30 && i <= 34.9) 

    {
        System.out.println("Obesidade grau 1: ");

    } else if(i > 35 && i <= 39.9)

    {
        System.out.println("Obesidade grau 2: ");

    } else 

    {
        System.out.println("Obesidade grau 3: ");
    }
    
    System.out.println("IMC: " + i);

      }

}

##

## JavaDeathStar

import java.util.Scanner;

public class JavaDeathStar {

 public static void main(String[] args) {

  boolean go = true;

  char option;

  Scanner input = new Scanner(System.in);
  
  while(go) {

   System.out.println("You are on the Java Death Star! ");
   
   System.out.println("Choose one side to exit: ");
   
   option = input.next().charAt(0);
   
   if(option == 'd') {

       go = false;

       System.out.println("Congratulations, you out of the Death Star");
   }

   else {

       System.out.println("Not authorized.");
   
        }
      }
    }
 }

##
##

public class breakTest {

 public static void main(String[] args) {

   long i = System.currentTimeMillis();

   boolean print = true;
   
   for(int count=1; count <=100000; count++) {

     if((count % 17 == 0) && (count % 19 == 0))

        if(print) {

           System.out.println("RESULT: " + count);

           break;

           //print = false;
         }
      }
   
   System.out.println(" Time of execution in milliseconds: "+ (System.currentTimeMillis() -i));

    }

}

##

public class continueTest {

 public static void main(String[] args) {

   long i = System.currentTimeMillis();
   
   for(int count = 1; count <= 1000000; count++) {

     if(count % 2 == 0) {

        continue;
     }

     if((count % 17 == 0) && (count % 19 == 0)) {

        System.out.println(count);

        break;
      }
    }
 
 System.out.println("Time of execution in milliseconds: " + (System.currentTimeMillis() -i));

   
    }

}

##
##

public class Increment {

 public static void main(String[] args) {

   int a,

     b = 1;
     
    System.out.println("b= " + b);

    System.out.println("a= b++");

    a = b++;

    System.out.println("Then: a =" + a);

    System.out.println();
    
    System.out.println("b =" + b);

    System.out.println("a = ++ b");

    a = ++ b;

    System.out.print("Then: a =" +a);

    }

}

##
##

import java.util.Scanner;

public class variablesParams {
    
  public static float average(float... values) {

    float average = 0;
    
    for(float value: values) {

      average += value;

    }
    
    return average/values.length;
  }
  
  public static float majorNote(float n1, float n2, float n3) {

    if(n1 >= n2) {
       if(n1 >= n3)
          return n1;
    }else{
       if(n2 >= n3)
          return n2;
    }
    return n3;
    
  }
  
  public static float minorNote(float n1, float n2, float n3) {
      
    if(n1 <= n2) {
      if(n1 <= n3)
          return n1;
    }else{
      if(n2 <= n3)
         return n2;
    }
    return n3;
  
}

public static void main(String[] args) {

    float n1, n2, n3;

    Scanner input = new Scanner(System.in);
    
    System.out.print("Enter a value 1: ");

    n1 = input.nextFloat();

    System.out.print("Enter a value 2: ");

    n2 = input.nextFloat();

    System.out.print("Enter a value 3: ");

    n3 = input.nextFloat();
    
    System.out.println("Major note was: " + majorNote(n1, n2, n3));

    System.out.println("Minor note was: " + minorNote(n1, n2, n3));

    System.out.println("Average with three notes: " + average(n1, n2, n3));

    System.out.println("Average without a minor note: " + (n1+n2+n3 - minorNote(n1, n2, n3)) / 2);

    }
   
}

##
##

## DarkScanner

import java.util.Scanner;

public class DarkScanner {

 public static void main(String[] args) {

  Scanner read = new Scanner(System.in);
  
  int age;

  String name;
  
  System.out.printf("Enter your age:\n");

  age = read.nextInt();
  
  read.nextLine();
  
  System.out.printf("\nEnter your name:\n");

  name = read.nextLine();
  
  System.out.printf("\nResult:\n");

  System.out.printf(" %s have %d years.\n", name, age);

    }
 
}

##
##

* Java Secret Number

import java.util.Random;

import java.util.Scanner;

public class SecretNumber{
    
    public static void tip(int shot, int snumber, int attempts ) {

      if(shot == snumber) {

          System.out.println("Congratulations! The secret number is " + snumber);

          System.out.println("You tried " + attempts+ "x");

      }else {

          if(shot > snumber) {

              System.out.println("Your shot it's greater than secret number.");
              
          }else {

              System.out.println("Your shot it's less than secret number.");
          }
      
    }
}

public static void main(String[] args) {

    int shot = 0,

    drawm,

    attempts = 0;
    
    Scanner input = new Scanner(System.in);
    
    Random randomGenerator = new Random();

    drawm = randomGenerator.nextInt(10) + 1;
    
    System.out.println("Enter a number between 1 and 10 drawn");
    
    do {

        System.out.printf("\n\n\n\n**********\n");
        
        System.out.println("Number of attempts: " + attempts);
        
        System.out.print("Enter your shot: ");

        shot = input.nextInt();
        
        attempts++;
        
        tip(shot, drawm, attempts);

    }while(shot!=drawm);

     } 

}

##
##

public class ForEachResidentEvil

{

    public static void main(String[] arg)

    {
        {
            int[] score = {101, 102, 95, 106, 160 };

            int h_score = maximum(score);

            System.out.println("The better score is: " + h_score);
        }
    }

    public static int maximum(int[] numbers)

    {
        int maxScore = numbers[0];

        for (int num : numbers)
        
        {
            if (num > maxScore)

            {
                maxScore = num;
            }
        }

        return maxScore;

    }
}

##
##

public class HellraiserLoop 

{

    public static void main(String[] args) {

        xx:

        for(int i = 1; i <= 3; i++)

        {

        yy:

        for(int j = 1; j <= 3; j++)

        {

        if(i == 2 && j == 2){

            break xx;
        }

        System.out.println(i + " " + j);

        }

      }

     }

}

##   
##

import java.util.List;

import java.util.ArrayList;

public class SomeMovies

{
    public static void main(String[] args)

    {
        String movie1 = "Resident Evil";

        String movie2 = "Allien";
        
        String movie3 = "Terminator";
        
        ArrayList<String> movies = new ArrayList<>();
        
        movies.add(movie1);
        
        movies.add(movie2);
        
        movies.add(movie3);
        
        System.out.println(movies);
         
        movies.remove(0);

        System.out.println(movies);
        
    }
 
}

##
##

import java.util.List;

import java.util.ArrayList;

import java.util.Collections;

public class SomeSeries

 {

    public static void main(String[] args)

 {

        String serie1 = "Better call Saul";

        String serie2 = "Walking Dead";

        String serie3 = "Stranger Things";

        String serie4 = "The Crown";

        ArrayList<String> series = new ArrayList<>();

        series.add(serie1);

        series.add(serie2);

        series.add(serie3);

        series.add(serie4);
        
        System.out.println(series);
        
        Collections.sort(series);
        
        System.out.println(series);

        //After orderly
        
    }
}
 
##
##

    

import java.util.ArrayList;

public class SomeGames 

{

    public static void main(String[] args) 

    {
        ArrayList<String> games = new ArrayList<String>();

        System.out.println(games);
        
        games.add("Resident Evil");

        games.add("Blackthorne");

        games.add("Zelda - The link of the past");

        games.add("Donkey Kong");

        games.add("Super Metroid");
        
        //games.clear(); 

        // removing arraylyst with the method .clear()
        
        //System.out.println(games.get(3)); 

        // access index with the method .get()
        
        System.out.println("Games add: " + games);

     }
}

##
##


   


    
    
    
    






