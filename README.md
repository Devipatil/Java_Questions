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

6. What is thedifference between method overloading and method overriding?

-> Method overloading is creating multiple methods in a class with same name but different parameters, while method overriding 
   is creating a method in a subclass with modified method body in subclass, same name and parameters as a method in its superclass.  

7. What is the difference between private and protected modifier?

-> A private modifier makes a member accessible only within the same class, while a protected  modifier makes a member accessible 
   within the same class and its subclasses.  

8. What is constructor overloading in java?

->  A class can have multiple constructor with different parameter lists. Each constructor provides a different way to 
    initialise objects of the class.   

9. What is the use of super keyword in java?

-> Super keyword is used to call the parent class's method when it has been overridden in a child class, to access the constructor 
   of the parent class, and to access fields of the parent class if they are shadowed or hidden by subclasses.  

10. What is the difference between static methods, static variables and static classes?

-> Static methods and static variables belong to the class of the java program, not to the object of the class. There 
   memory allocated when the class is loaded and can directly be called with the class name. A class in the java program 
   cannot be static except if it is the inner class. If it is an inner static class, then it exactly works like other 
   static members of the class.

11. What exactly is system.out.println in java?

->  System.out.println() is a method to print a message on the console. System - It is a class present in java.lang package.
    Out - is the static variable of type PrintStream class present in the System class. println() is the method present in 
    the PrintStream class.  

12. What part of memory - stack or heap - is cleaned in the garbage collection process?
   
->  Garbage collection is done on heap memory to free the memory used by objects that don't have any refernce. Any object 
    created in the heap space has global access and can be referenced from anywhere in the application.
