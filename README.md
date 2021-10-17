# Review of OOP using Java

The purpose of this repository is to review and 
practice key concepts that are crucial in understanding
object-oriented programming. These concepts include:

- Encapsulation
- Accessor methods
- Mutator methods
- Local vs Instance Variables
- Inheritance
- Polymorphism

These concepts will be explored by creating few
simple projects.

## Additional Notes

### Private vs Public:
In Java, these keywords in front of variables, classes,
etc. determine which parts of your code have access to
other parts of your code. Doing so helps us "encapsulate" 
our code into nice little bundles of logic, and helps
the programmer segment our code and potentially prevent
unwanted changes from occurring.

### Accessor (getter) & Mutator (setter):
The instance variables of a class is often set to be 
private, but we can still edit & read them by creating 
getter and setter method.

### Constructor Parameter Naming Convention:
Oftentimes, we may see constructors have parameters
with the same name as the instance variable.
```java
public Person(String name){
    this.name = name;
}
```
This can be read as - "set `this` `Person`‘s instance 
variable name equal to the variable passed into the 
constructor."

Sometimes other people may use different name for the 
argument, to prevent confusion.

```java
public Person(String inputName){
    this.name = inputName;
}
```

Like in JavaScript, `this` keyword is a reference 
to the current object.