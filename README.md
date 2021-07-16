# javainterviewQuestions
Java and hibernate
============Basics
Different ways to create objects in Java
1) Using new Keyword 
2) Using New Instance 
3) Using clone() method:
4) Using deserialization
5) Using newInstance() method of Constructor class

What is the difference between Stack and Heap in Java?
what is JVM and Class loaders?
1)Bootstrap ClassLoader/Extension ClassLoader/System/Application ClassLoader
what is serialVersionId and if dont write what ll happen?
===========Strings
why string are Immutable? How to create an Immutable object in Java?
String s1 = "abc", String s2 = new String("abc") how many objects created?
String s = "madhumita"; How many times repeated char count?

============Design patters
How to prevent Singleton Pattern from Reflection, Serialization and Cloning?

what are design patters you know and builder and factory DP
===========Threads
can we implement Runnable and Extends Thread at same time?

Why must you override the run() method in your thread class?

What happens if a thread throws an Exception inside synchronized block?

What are the main differences between notify and notifyAll in Java?
===============Java 8
java 8 freatures: interface has two methods, i want to implement m1 method through lambda exp is that possible?
diff b/w map and flatmap
============== Oops
class Animal has m1 and m2, sub class Cat has m2 and m3 if i create object Animal a = new Cat();  
output?
=============Collections
Hashmap internal implementation? balanced Tree
Generics Where you ll use other than Collections in ur Project?

============Hibernate
Hibernate uses then jdbc?
criterias where u ll use?
Stored Procedures how i ll write code?
onetomany mapping?

============Spring
How u ll check bean is singlton or not?
rest flow in application?
Springboot uses? diff @restcontroller and @controller?


=============Java for 3 below
oops concepts override/overload(polimer)
abstraction
encapsulation
inheritance
why multiple inheritance not supported? why multilevel
==========Strings
why strings are immtable?
String s1 = "abc";
		String s2 = new String("abc");
		s1 = s1+"xyz";
		s2 = s1.concat("cdf");
		System.out.println("s1- "+s1);
		System.out.println("s2- "+s2);
== and .equals diff why?
String intern()
============Collections
diff arrays/ collections
diff list and set/ hashmap and hashtable
How to print list?
what is use of concurrent collections?
=============DP
singleton DP and factory DP
=====
why generics introduced?
========Java 8
features? functional
Streams uses
optional use?
=========Threads
How many ways can create threads?
internal thread communication?
thread life cycle?
Synchronized key word?
join(),sleep(), yeild()?
deamon thread?
