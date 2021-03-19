# Online Reading: 03 - Maps, primitives, File I/O

## [Primitives vs. Objects](https://www.baeldung.com/java-primitives-vs-objects) 

**Java Type System**
* Java has a two-fold type system consisting of primitives and reference type. Primitives correspond to a reference type.Every object contains a single value of the corresponding primitive type. 
  - Examples of primative: int, boolean
  - Examples of reference: Integer, Boolean
* Autoboxing - process of converting a primitive type to a reference type 
* Unboxing - opposite process of autoboxing
* Primitive type variables live in the stack and can be accessed fast. They have the following impact on the memory:
  - boolean – 1 bit
  - byte – 8 bits
  - short, char – 16 bits
  - int, float – 32 bits
  - long, double – 64 bits
* Reference types are objects that live in the heap and slow to access.
* Default values of the primitive types are 0 for numeric types, false for the boolean type, \u0000 for the char type, and null for the wrapper classes. 
  - Primitive types may acquire values only from their domains.
  - Reference types might acquire a value that doesn't belong to their domains.  

## [Exceptions in Java (read the first three sections on the left: What is an Exception, The Catch or Specify Requirement, Catching and Handling Exceptions)](https://docs.oracle.com/javase/tutorial/essential/exceptions/index.html)


## [Using Scanner to read in a file in Java](https://docs.oracle.com/javase/tutorial/essential/io/scanning.html)