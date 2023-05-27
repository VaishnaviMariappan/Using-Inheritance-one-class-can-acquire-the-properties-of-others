# EXP8 Using Inheritance one class can acquire the properties of others.

## AIM:

To create a program using inheritance and aquire the properties into another class.

## PROCEDURE:
1. Create the class and declare the main method so that the JVM will identify the main program to run.

2. Create another class and use the keyword EXTENDS to use the concept of INHERITANCE.

3. Print a statement to check whether the inner class is accessable or not. 

4. If the extended class's statement is executed then,this program follows the concept of inheritance.

5. The program will be executed after the compilation and results are printed.

## PROGRAM:
```java
package q1;

public class Main {
    public static void main(String[] args) {
        Bird c=new Bird();
        c.fly();
        c.walk();
        c.sing();
    }
}
//CLASS FILE: BIRD
public class Bird extends Animal{
    public void fly(){
        System.out.println("I m flying");
    }
    public void sing(){
        System.out.println(" "+"I m singing");
    }
}
//CLASS FILE: ANIMAL
public class Animal {
    public void walk(){
        System.out.println("I m walking");
    }
}
```
## OUTPUT:
![image](https://github.com/VaishnaviMariappan/Using-Inheritance-one-class-can-acquire-the-properties-of-others/assets/94169913/21df7f69-089f-4aa6-9f57-b6af85adc277)

## RESULT:
Thus a program using inheritance is executed.
