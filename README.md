# Java Core

### `4 OOP concepts in Java`
1. **Abstraction**
- Abstraction aims to `hide complexity` from users and show them `only relevant information`. For example, if you’re driving a car, you don’t need to know about its internal workings.
 
2. **Encapsulation**
- The practice of keeping fields within a `class private`, then providing access to those fields via `public methods`. Encapsulation is a protective barrier that keeps the data and code safe within the class itself.

3. **Inheritance**
- Inheritance lets programmers create new classes that share some of the attributes of existing classes using keyword `extends`.

4. **Polymorphism**
- Polymorphism refers to the ability to perform a certain action in different ways
- In Java, polymorphism can take two forms: method `overloading` and method `overriding`.

### `Abtract class vs Interface`
| Abstract class | Interface |
| --- | --- |
| Can have any kind of instance or static variables, mutable or immutable. | Can only have final static variables. An interface can never change its own state. | 
| Abstract class `doesn't suppor`t multiple inheritance. | Interface `supports` multiple inheritance. |
| An abstract class can `extend` another Java class and `implement` multiple Java interfaces. | An interface can `extend` another Java interface only |
| Abstract class can have final, non-final, static and non-static variables. | Interface has only static and final variables. |

**Important Reasons For Using Interface**:
  - It is better to use interface when various implementations `share only method signature`.
  - Allows you to separate the definition of a method from the inheritance hierarchy.
  - It helps you to achieve loose coupling.
  - Designed to support dynamic method resolution at run time. 
  
**Important Reasons For Using Abstract Class**:
  - It should be used when various implementations of the same kind `share a common behavior`.
  - Abstract classes offer default functionality for the subclasses.
  - Provides a template for future specific classes.
  - Helps you to define a common interface for its subclasses.

### `StringBuffer vs StringBuilder`
| StringBuffer | StringBuilder |
| --- | --- |
| StringBuffer operations are `thread-safe` and `synchronized` | StringBuilder operations are not `thread-safe` and `not-synchronized`. | 
| StringBuffer is to used when `multiple threads` are working on the same String  | StringBuilder is used in a `single-threaded` environment |
| StringBuffer performance is `slower` | StringBuilder performance is `faster` |

# SQL
The `INNER JOIN` keyword selects records that have matching values in both tables.
The `LEFT JOIN` keyword returns all records from the `first` table, and the matching records from the second table.

# Spring Security 
https://www.javainuse.com/webseries/spring-security-jwt/chap3 

![Security_Flow](https://www.javainuse.com/series-2-2-min.jpg)

