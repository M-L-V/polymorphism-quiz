# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?


Polymorphism is when you treat an instance of a class as though it were also an instance of another class, allowing it to be treated as multiple things and to reuse methods to do different things.


2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

There could be a parent class of a general type that has child classes. There would be an interface that references a simple method that returns a String. This interface would then be referenced in the parent class which would mean each child class would have a unique method that returned a different String depending on what child it was called on. The subclasses would then count as both children of the parent class AND examples of the interface class.

3. What can we use to implement polymorphism in Java?

Interfaces.


4. How many 'forms' can an object take when using polymorphism?

Two - its original and the interface version.


5. Give an example of when you could use polymorphism.

The example in number 2 is an example that shows reusing of a method as a use of polymorphism.


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

Classes are composed of other classes that implement the behaviour required in the first class. This means the first class can use these methods.

7. When would you use composition? Provide a simple example in Java.

A class called Staff could have use another class called Job which gives salary amount methods.

8. What is/are the advantage(s) of using composition?

It allows you to reuse code, allowing for cleaning abstraction and preventing code breaking.  


9. When an object is destroyed, what happens to all the objects it is composed of?

They are also destroyed.
