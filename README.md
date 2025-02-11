# Java_Techincal_Interview_Questions

Core Java Concepts :

1. What is the difference between JDK and JRE?
   
-> JDk stands for Java Developement Kit, which is a software development environment for building Java applications. 
   JRE stands for Java Runtime Environment, which is required to run Java programs.

2. Why is Java platform independent languauge?
   
-> Java programming language and its associated APIs are first complied into bytecodes that can run on multiple platforms.

3. What is the difference between an abstract class and an interface?
   
-> * An abstract class is a class that cannot be instantiated and must be extended by derived classes,
     providing a combination of implemented and abstract methods.
   * Abstract classes can hold state(have fields or properties).
   * Abstract class supports single inheritence(can extend one class).
   * Less flexible in terms of class hierarchy due to single inheritance.
   * Abstract class can have abstract and concrete methods.

   * An interface is a contract that classes implement.
   * Interface cannot hold state.
   * Interface supports multiple implementations (can implement multiple interfaces).
   * More flexible, allows one class to implement multiple interfaces.
   * Interface can have abstract methods, default methods and static methods.
  
4. What is the difference between final, finally and finalize?
   
-> Final is used to make a variable or method constant and cannot be changed later and final class cannot be inherited.
   Finally is used in try-catch blocks to execute a block of code(task) regardless whether an exception is thrown or not.
   Finalise is a method that is called by the garbage collector when an object is no longer in use.

5. What is the difference between stack and heap memory?

-> Stack memory is used for storing local variables and function call. while heap memory is used for objects and their
   instance variables.     
      
