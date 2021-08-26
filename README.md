# Agenda 
     
  - [Basic](#basic)
    - [Intro](#intro)
    - [First code](#first-code)
    - [Comment](#comment)
    - [Variable](#variable)

  - [Networking](#networking)














---

### basic


### intro
> What is java ?
```
Java is a programming language and computing platform first released by Sun Microsystems in 1995.
It is owned by Oracle, and more than 3 billion devices run Java.
```





> Path
```
CMD:
set path=C:\Program Files\Java\jdk-16.0.2\bin;%path%;
```






### first-code
> Write your first code using notepad
```
import java.lang.*;

class FistCode
{

 public static void main(String arg[])
 {
 System.out.println("Hello World !");
 }

}
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










### networking
```
> Java Networking intro.

Java Networking is a concept of connecting two or more computing devices together so that we can share resources.
Java socket programming provides facility to share data between different computing devices.


> Advantage

- Sharing resources
- Centralize software management


> The java.net support 2 trotocols

- TCP: Transmission Control Protocol provides reliable communication between the sender and receiver. 
       TCP is used along with the Internet Protocol referred as TCP/IP
       
- UDP: User Datagram Protocol provides a connection-less protocol service by allowing packet of data to be 
       transferred along two or more nodes.The User Datagram Protocol, or UDP, is a communication protocol
       used across the Internet for especially time-sensitive transmissions such as video playback or DNS lookups. 
       It speeds up communications by not formally establishing a connection before data is transferred. 
       This allows data to be transferred very quickly, but it can also cause packets to become lost in transit — 
       and create opportunities for exploitation in the form of DDoS attacks.       
```




