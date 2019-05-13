# Entry 5: OOP - Inheritance, Composition, Encapsulation, Polymorphism

This week I learned some Object Oriented Programming Concepts or OOP concepts in Java. Java OOP concepts includes inheritance, composition, encapsulation, and polymorphism. 

## Inheritance
Inheritance is essentially an OOP concept in Java where an object inherits qualities of another object or that an object is based on another object. An example of inheritance would be a `Dog` class inheriting the `Animal` class, since dogs are animals and they have some characteristics that animals in general have. In the concept of inheritance the object that is getting inherited is called superclass and the object that inherits the superclass is called subclass. In the previous example, the `Dog` class would be the subclass and the `Animal` class would be the superclass. When inherit a class from another class we use the extend keyword. For example, the syntax of the inheritance class should look like this:

```java
class Dog entends Animal {
    //some code
}
```

[Click here to see a code example on repl.it](https://repl.it/@JohnsonWu/inheritance)

## Composition
The composition concept is very similar to the inheritance concept, thus people often get them confused. The difference between the inheritance concept and the composition concept is that the inheritance concept is the idea of an “is-a” relationship between objects, whereas the composition concept is the idea of a “has-a” relationship between objects. For example, when you have a `Dog` class that inherits the `Animal` class then that would be an inheritance or an “is-a” relationship because, a dog *is an* animal. However, if you have a `Monitor` class that extends to the `Computer` class then that would be a composition because a computer *has a* monitor. 

[Click here to see a code example on repl.it](https://repl.it/@JohnsonWu/Composition)

## Encapsulation
Encapsulation is a technique or mechanism in java that allows the programmer to restrict access to certain components in objects that they are creating. The purpose of the encapsulation is to protect members of a class from external access. In other words, encapsulation prevent classes or code outside of the class that you're working on, from accessing the inner workings of a class. Encapsulation in java is achieved by using access modifier keywords such as public private and protected.

## Polymorphism
Polymorphism is a mechanism in java that allows objects to behave differently in different situations. It is a very complicated concept. From my understanding of it right now, I believe that it is a mechanism that allows subclasses to override some components that it has inherited from the superclass. 

## Takeaway(s)
A takeaway that I have this week is that doing code alongs and coding challenges makes learning more fun. While just reading and watching videos to learn new ideas is actually very boring to me. I found excitement and enjoyment in doing code alongs and code challenges since it gives me a lot of freedom to test with the code and learn about what can be done and what can’t be done. Code alongs and coding challenges makes my process of learning entertaining, thus it fuels my interests and keeps me learning. 
