# OOPs-with-JAVA
## How to Download & Install Java JDK in Windows

Following are steps to install Java in Windows
* Go to link. Click on Download JDK. For java latest version.
* [Open Link] (https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
* According to your system, configuration (64 bit/32 bit) /Operating System (Windows/Linux), download  JDK. 
* For installation - Double click on exe file -> click next -> next ->………->Finish.
* Finally, we have completed the installation of jdk. 

Write, save,compile and run my First Java program: 
 
* Open Notepad/Notepad++ , type the following program. 
* Save it as First.java in any drive or folder.  
* Please recheck the extension of saved program, it should be .java 

Open Command Prompt: 
* Launch the command prompt via All Programs -> Accessories -> Command Prompt. 
* My program location is    F:\Java Code 2020 
* Check java/javac version: 
* Compile the program: Javac is the name of Java Compiler. 
* OR  
After compilation command, either control go on next line or it can show the following error on screen:   
Problem:  'OS is not able to recognize the .java file.' 
 
```Solution 1:  Setting Temporary Path :
Copy the path of jdk/bin directory where java located    
(C:\Program Files\Java\jdk1.8.0_131\bin)  
```

Write in the command prompt:  
  

Note: In LINUX 
 
>export PATH=$PATH:/home/jdk1.6.01/bin/ 

---
 
Command for checking the values of  PATH variable 
  >echo %path% 
 
Again, compile the program: 
 
* After proper compilation, compiler will generate one intermediate code/byte code or .class file. 
* Execute the program: Java is the name java Interpreter. 

----
Solution 2:  Setting Permanent Path: 
''' 
Go to My Computer properties  advanced tab  environment variables -> new tab of user/system variable -> write path in variable name -> write path of bin folder in variable value ->ok -> ok -> ok 
'''

 ### Some Important terms of java :

``` class First 
      {
         public static void main(String args[])
           {
              System.out.print("Hello users in JAVA Programming language");
           }
      }
```

* _public_: main is called by operating system in C++ but by JVM in java, JVM can call main only when the public mode is given before main
* _static_: Since JVM is calling main which is in class, so if we want to call main, an object of class is required to call main by JVM. So JVM escape from the burden of creating an object for the purpose of calling main(). 
* _void_: indicate main(),won’t return anything to JVM. 
* _String args[]_: Known as command line arguments, String is a built in class in java,String have every facility as for making and working on char. 

## Introduction to Java 
* Java is a computer programming language. It enables programmers to write computer instructions using English based commands, instead of having to write in numeric codes. 
* It’s known as a “high-level” language because it can be read and written easily by humans. Like English, Java has a set of rules that determine how the instructions are written. These rules are known as its “syntax”. Once a program has been written, the high-level instructions are translated into numeric codes that computers can understand and execute.  
* Java is an object-oriented programming language.  


Many java versions have been released till now. The current stable release of Java is Java SE 10. 
*	JDK Alpha and Beta (1995) 
*	JDK 1.0 (23rd Jan 1996) 
*	JDK 1.1 (19th Feb 1997) 
*	J2SE 1.2 (8th Dec 1998) 
*	J2SE 1.3 (8th May 2000) 
*	J2SE 1.4 (6th Feb 2002) 
*	J2SE 5.0 (30th Sep 2004) 
*	Java SE 6 (11th Dec 2006) 
*	Java SE 7 (28th July 2011) 
*	Java SE 8 (18th March 2014) 
*	Java SE 9 (21st Sep 2017) 
*	Java SE 10 (20th March 2018) 
*	Java SE 11 (September 2018) 
*	Java SE 12 ( March 2019) 
*	Java SE 13 (September 2019) 
*	Java SE 14 (March 2020) 


Types of Java Applications  :
There are mainly four types of applications that can be created using java programming: 
* _Desktop Application_ : 
It is also known as desktop application or window-based application. An application that we need to install on every machine such as media player, antivirus etc. AWT and Swing are used in java for creating standalone applications. 
* _Web Application_  : 
An application that runs on the server side and creates dynamic page, is called web application. 
Currently, servlet, jsp, struts, jsf etc. technologies are used for creating web applications in java. 
* _Enterprise Application_  :
An application that is distributed in nature, such as banking applications etc. It has the advantage of high level security, load balancing and clustering. In java, EJB is used for creating enterprise applications. 
* _Mobile Application_ : 
An application that is created for mobile devices. Currently Android and Java ME are used for creating mobile applications. 


Java Editions/Platforms :
There are 4 platforms or editions of Java:  
* _Java Standard Edition (JSE)_: The Java Standard Edition (Java SE) is for building desktop applications and applets. These applications typically serve only a small number of users at one time. It is a Java programming platform. It includes Java programming APIs such as java.lang, java.io, java.net, java.util, java.sql, java.math etc. It includes core topics like OOPs, String, Regex, Exception, Inner classes, Multithreading, I/O Stream, Networking, AWT, Swing, Reflection, Collection, etc. 
* _Java Enterprise Edition (JEE)_: It is an enterprise platform, which is mainly used to develop web and enterprise applications. It is built on the top of the Java SE platform. It includes topics like Servlet, JSP, Web Services, EJB, JPA, etc.  
* _Java Micro Edition (JME)_: The Java Micro Edition is for applications used on mobile (e.g., cell phone, PDA) and embedded devices (e.g., TV tuner box, printers). 
* _JAVA Card_: used in SIM Cards, ATM Cards, Credit Cards, SMART Card reader programming. 

Java Virtual Machine (JVM)

JVM (Java Virtual Machine) is an abstract machine. It is called a virtual machine because it doesn't physically exist. 
It is a  specification provides runtime environment in which java bytecode can be executed.  
JVMs are available for many hardware and software platforms.  
JVM, JRE and JDK are platform dependent because configuration of each OS differs. But, Java is platform independent. 


The JVM performs following main tasks: 
*	Loads code 
*	Verifies code 
*	Executes code 
*	Provides runtime environment 

Java Runtime Environment (JRE): 


JRE is an acronym for Java Runtime Environment. It is also written as Java RTE. The Java Runtime Environment is a set of software tools, which are used for developing Java applications. It is used to provide the runtime environment. It is the implementation of JVM. It physically exists. It contains a set of libraries + other files that JVM uses at runtime. 
The implementation of JVM is also actively released by other companies besides Sun Micro Systems. 
 
```JDK=JRE + Development Tools (JAVAC, JAVA)``` 

Java Development Kit (JDK):  


JDK is an acronym for Java Development Kit. The Java Development Kit (JDK) is a software development environment, which is used to develop Java applications and applets. It physically exists. 
It contains JRE + development tools. 
JDK is an implementation of any one of the below given Java Platforms released by Oracle Corporation: 
* Standard Edition Java Platform 
* Enterprise Edition Java Platform 
* Micro Edition Java Platform 


The JDK contains a private Java Virtual Machine (JVM) and a few other resources such as an interpreter/loader (java), a compiler (javac), an archiver (jar), a documentation generator (Javadoc), etc. to complete the development of a Java Application. 


Example: 
JDK 1.5,JDK 1.6 ,JDk 1.8 


Note: The JRE is contained within the JDK (i.e., if you just download the JDK you will be able to create and run java programs.).  
## Identifiers in Java 

A name in Java Program is called identifier, which can be used for identification purpose. It can be method name, class name, variable name, label name. 
 
 
How many identifiers are present in the following program?  
```
class Student 
  {  
      public static void main(String args[]) 
         { 
            int x=10; 
         } 
  } 
```
Answer:  5 (Student,main,String ,args,x)

### Rules for Defining Java Identifiers:  

Following are the allowed characters for identifiers in java:
* A to Z   a to z 0 to 9 
* $ 
* _ (underscore) 
 
By mistake if you are using any other character, you will get compile time error. 
 
* even_number  : :       valid 
* even#        : :       invalid 
* even2        : :       valid 
* 2even        : :       invalid-  identifiers cannot start with digits. 
 
_Note_: 
* Java identifiers are case sensitive.
* Java language itself is treated as case sensitive programming language. 

```
class Demo 
{ 
  public static void main(String args[]) 
  { 
    int number =10;   //Valid
    int Number =10;  // Valid
    int NUMBER =10; //Valid
    int number=20;  //Invalid 
  } 
} 
```
 
Note: We can differentiate with respect to case. 

_How many characters are allowed in java for identifiers?_ 
* 32 
* 64 
* 128 
* 256 
* 512 
* No limit  
 
 ```
 class Demo 
{ 
     public static void main(String args[]) 
        {        
           int _x=5;  	
           int x_=6; 
           int $=3;  	
           int 123x=30;   
           int #=5; 
           int num=20; 
           int Num=30; 
           int NUM=40;  
           int num=50;  
            int x=10; 
            int xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx=20; 
            System.out.println(xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx); 
       }
} 
```
 
Note : There is no length limit for java identifiers, Even you can take  100000000000000000000 length or any length, but it is not recommended to take too lengthy identifiers.  

Can we use reserve word for java identifiers  ???? 
 
 ```
class ReserveW 
{ 
   public static void main(String args[]) 
     { 
         int for =10; 
         int if =20; 
         int class =50; 
         int cat =70; 
     }
} 
``` 

>Note: We cannot use reserve words as identifiers. 
 
Can you tell what is output, we are going to get??? 

``` 
class Demo1 
{ 
     public static void main(String args[]) 
    { 
 	   int String =100; 
       int Runnable=200; 
       System.out.println(String); 
       System.out.println(Runnable); 
     }
}  
```
output:  100 
         200 
         
         
Question : Valid or not???? 
 
Answer : 100%  valid 
These are the predefined class or Interface of Java. 
 
 
_Note_:  
All predefined java class names and interface names, we can use as java identifiers. 
Even though it is valid but it is not a good programming practice. 
It reduces readability and creates confusion. 
 
 
Which are following valid/invalid  java Identifiers; 
 
* total_num  : : valid 
* total#     : : inv 
* 123total   : : inv 
* total123   : : valid 
* ca$h       : : valid  
* Integer    : : valid 
* int        : : inv
* Int        : : valid 
* _$_$_$     : :  valid 
* all@       : : inv 
* Upes2020iot  : :  valid 
 	  
Reserved Word:


In any language-normal language or programming language, some words are reserve word  like English apple students run sleep—crores of word. 
 
In java some words are reserve words to present some meaning or functionality, such type or words are called reserve words. 
How many reserve word are there in java 
* 40 
* 45 
* 50 
* 53 
* 55 
* 63 
 
Answer: 53 
	 
 
50  (keyword)+ 3(reserve literals)  true,false and null 
 
50 keyword= used keyword 48(if else…..)+unused keyword 2(goto,const) 
 
 Keywords for data types: 8 
1.	byte  
2.	short 3. int 
4.	long  
5.	float 
6.	double 
7.	boolean 
8.	char 
 
Keywords for flow control: 11 
9.	if  
10.	else 
11.	switch 
12.	case  
13.	default 
14.	while 
15.	do  
16.	break 
17.	continue 
18.	return 
19.	for 
20.	enum 
 
Keywords for modifiers: 11  default (already included) 
 
21.	public 
22.	private 
23.	protected 
24.	static 
25.	final 
26.	abstract 
27.	synchronized 
28.	native 
29.	strictfp-    1.2 version  
30.	transient 
31.	volatile 
 
Keywords for exception handling  6 
32.	try 
33.	catch 
34.	finally 
35.	throw 
36.	throws 
37.	assert      1.4 version 
 
 
Class related keywords: 6 
38.	class 
39.	interface 
40.	extends 
41.	implements 
42.	package 
43.	import 
 
Object related keywords: 4 
44.	new 
45.	instanceof 
46.	super 
47.	this 

Return type keyword:1 

48.	void  (default return type in java- void, default return type in c language-int) Unused keyword:2 
49.	goto-    uses of goto created several problems in old languages, hence SUN people banned this keyword in java. 
50.	const- use final instead of const 
 
Note: goto and const are unused keyword and if you are trying to use we will get compile time error. 
 
Reserved word -literals:3 
51.	true: value for Boolean data type 
52.	false : value for Boolean data type 
53.	null   default value of object reference 
 
 
Note: 
* All 53-reserve words in java contains only lower case alphabet symbols. 
* In java we have only new keyword, and there is no delete keyword because destruction of useless objects is the responsibility of garbage collector. 
 
enum :1 –keeps a wording in which version this one came.?? 1.5 version when we  should go  enum: if you want to define group of named constant  
 
 ```
enum Month 
{ 
  JAN,FEB…..DEC; 
} 
```
 
Which are the following list contains java reserve words: 
* new, ~~delete~~ goto , 
* ~~constant~~ break,
* continue,
* return,
* exit final,finally,
* ~~finalize~~-method throw,
* throws,~~thrown~~ 
* notify, notifyall
* implements, 
* extends, ~~imports~~ ~~sizeof~~, 
* instanceof-not in java istanceif,
* ~~strictFp~~ byte,short,
* ~~Int~~ ~~none of these~~-
* ~~true~~ 
 
 
 
class Reserveword 
 
Automatically they are come in blue color. 


