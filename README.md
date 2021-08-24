# Agenda 
     
  - [Basic](#basic)
    - [Intro](#intro)
    - [Comment](#comment)
















---

### basic


### intro
> What is java ?
```
Java is a programming language and computing platform first released by Sun Microsystems in 1995.
It is owned by Oracle, and more than 3 billion devices run Java.
```





> Why you should learn Java in 2021 ?
```
- Mobile applications (specially Android apps)
- Desktop applications
- Web applications
- Web servers and application servers
- Games
- Database connection
- Java works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc.)
- It is one of the most popular programming language in the world
- It is easy to learn and simple to use
- It is open-source and free
- It is secure, fast and powerful
- It has a huge community support (tens of millions of developers)
- Java is an object oriented language which gives a clear structure to programs and allows code to be reused, lowering development costs
- As Java is close to C++ and C#, it makes it easy for programmers to switch to Java or vice versa
- And much, much more!
```





> You should know it.
```
JDK = Java development kit
JVM = Java virtual machine
JRE = Java runtime environment
```









### comment
```
> Single-line comments start with two forward slashes (//).
ex: 
// This is a comment
System.out.println("Hello World");


> Multi-line comments start with /* and ends with */.
ex: 
/* The code below will print the words Hello World
to the screen, and it is amazing */
System.out.println("Hello World");
```









### variable
```
String - stores text, such as "Hello". String values are surrounded by double quotes
int - stores integers (whole numbers), without decimals, such as 123 or -123
float - stores floating point numbers, with decimals, such as 19.99 or -19.99
char - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
boolean - stores values with two states: true or false
```
```
> To create a variable, you must specify the type and assign it a value:
ex:
type variable = value;


> A demonstration of how to declare variables of other types:
ex:
int myNum = 5;
float myFloatNum = 5.99f;
char myLetter = 'D';
boolean myBool = true;
String myText = "Hello";


> Create a variable called name of type String and assign it the value "John":
ex:
String name = "John";
System.out.println(name);


> Create a variable called myNum of type int and assign it the value 15:
ex:
int myNum = 15;
System.out.println(myNum);


> You can also declare a variable without assigning the value, and assign the value later:
ex:
int myNum;
myNum = 15;
System.out.println(myNum);


> Note that if you assign a new value to an existing variable, it will overwrite the previous value:
ex:
int myNum = 15;
myNum = 20;  // myNum is now 20
System.out.println(myNum);


> However, you can add the final keyword if you don't want others (or yourself) to overwrite existing 
values (this will declare the variable as "final" or "constant", which means unchangeable and read-only):
ex:
final int myNum = 15;
myNum = 20;  // will generate an error: cannot assign a value to a final variable
```
























