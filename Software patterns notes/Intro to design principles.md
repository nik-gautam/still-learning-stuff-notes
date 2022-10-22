# Intro to design principles

> 1. Identify the aspects of your application that vary and separate them from what stays the same

For all software the only constant is change. 

So, we take take what varies and "encapsulate" it so it wont affect the rest of the code. This saves the code from unintended changes in the code changes and more flexibility in your systems.

This concept remains the same for all design patterns.

> 2. Program to an interface, not an implementation.

When we direct program to an implementation, say extend a class, it resists further extention and introduces inflexbility in code. We are locked into using that specific implementation.

If we extend to an implemented class, the only way to change behaviour is by overridding methods; in both case  

> 3.  Favor composition over inheritance

Composition is more flexible than inheritance. Not only when can encapsulate a family of algorithms into their own sets of classes, but with composition we change switch between these  **_Strategies_** in runtime.

> **The Strategy Pattern** defines a family of algorithms, encapsulates each one, and makes them interchangeable. Strategy lets the algorithm vary independently fromt the client that use it.

