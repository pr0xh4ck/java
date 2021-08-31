```pr0h4ck © 2021```


# Agenda 
     
  - [Basic](#basic)
    - [Intro](#intro)
    - [First code](#first-code)
    - [Comment](#comment)
    - [Variable](#variable)
    - [Data types](#data-types)

 - [Advanced](#advanced)
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
> Write your first code using Notepad
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








> Compile your code using CMD
```
C\:> javac FirstCode.java
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



> JDK
```
Its use for code compiling, debugging & developing java program.
```


> JRE
```
It has java class library to execute java code.
```


> JVM
```
Basically it's a interpreter convert byte code to machine code. So JVM convert the code first then execute code.
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










### data-types


Data Type	       | Size	  | Descriptio
---------------- | ------- | -----------------------
byte	| 1 byte	| Stores whole numbers from -128 to 127
short |	2 bytes	| Stores whole numbers from -32,768 to 32,767
int	| 4 bytes	| Stores whole numbers from -2,147,483,648 to 2,147,483,647
long  |	8 bytes	| Stores whole numbers from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807
float |	4 bytes	| Stores fractional numbers. Sufficient for storing 6 to 7 decimal digits
double |	8 bytes	| Stores fractional numbers. Sufficient for storing 15 decimal digits
boolean |	1 bit	| Stores true or false values
char	| 2 bytes   | 	Stores a single character/letter or ASCII values





> Check storage capability, Now go to your terminal
```
C:\\java>javap java.lang.Integer 

C:\\java>javap java.lang.Float

C:\\java>javap java.lang.Double

C:\\java>javap java.lang.Boolean
```


> Now pick this 
```
MIN_VALUE

MAX_VALUE

BYTES
```


> Now write your code for testing
```
import java.lang.*;

public class First{
 
public static void main(String arg[]){
  
    System.out.println("Min value:" + Integer.MIN_VALUE);
    System.out.println("Max value: " + Integer.MAX_VALUE);
    System.out.println("Bytes: " + Integer.BYTES);
    
  }
}
```






































### advanced

### networking

> Java Networking intro.
```
Java Networking is a concept of connecting two or more computing devices together so that we can share resources.
Java socket programming provides facility to share data between different computing devices.
```


> Advantage
```
- Sharing resources
- Centralize software management
```


> The java.net support 2 trotocols
```
- TCP: Transmission Control Protocol provides reliable communication between the sender and receiver. 
       TCP is used along with the Internet Protocol referred as TCP/IP
       
- UDP: User Datagram Protocol provides a connection-less protocol service by allowing packet of data to be 
       transferred along two or more nodes.The User Datagram Protocol, or UDP, is a communication protocol
       used across the Internet for especially time-sensitive transmissions such as video playback or DNS lookups. 
       It speeds up communications by not formally establishing a connection before data is transferred. 
       This allows data to be transferred very quickly,    
```


> Network terminology
```
- IP Address
- Protocol
- Port Number
- MAC Address
- Connection-oriented and connection-less protocol
- Socket
```


> IP address
```
- IP address is a unique number assigned to a node of a network e.g. 192.168.0.1 . 
- It is composed of octets that range from 0 to 255.
- It is a logical address that can be changed.
```


> Protocol
```
A protocol is a set of rules followed for communication.
ex:

- HTTP
- TCP
- FTP
- Telnet
- SMTP
- POP 
```


> Port number
```
- The port number is used to uniquely identify different applications. 
- It acts as a communication endpoint between applications.
- The port number is associated with the IP address for communication between two applications.
- There are 65,535 possible port numbers.
```


> MAC address
```
- MAC (Media Access Control) address is a unique identifier of NIC (Network Interface Controller).
- A network node can have multiple NIC but each with unique MAC address.
- For example, an ethernet card may have a MAC address of 00:0d:83::b1:c0:8e.
```


> Connection-oriented and connection-less protocol
```
- In connection-oriented protocol, acknowledgement is sent by the receiver. 
  So it is reliable but slow. The example of connection-oriented protocol is TCP.

- But, in connection-less protocol, acknowledgement is not sent by the receiver. 
  So it is not reliable but fast. The example of connection-less protocol is UDP.
```


> Socket
```
- A socket is an endpoint between two way communications.
- WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.
```

