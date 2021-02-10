# Object-Oriented Programming and its Concepts
Object-oriented programming is a methodology or paradigm to design a program using **classes** & **objects**. 
- Objects:- Objects States that it has Real-world entities that have their own properties and behaviour.
- Classes:- Blueprint from which the properties and behaviour of an object are decided.

The main aim of OOP is to bind together the data and the functions that operate on them so that no other part of the code can access this data except that *function*.
## IMPORTANCE OF  OOPs
OOPs, play a very vital role in a programming language. OOPs provides good design patterns which are basically a figurative model of the design of an object; called class. It gives references for the user to create new objects and is very user friendly. It also gives us the option of sharing the code, which is called inheritance where the old methods can be reused into a new class. By giving prior error handling method, it gives the user to recheck the code and compile the run-time errors with the use of exception handling.
## OOPs TERMINOLOGY
- **INHERITANCE**:- Inheritance is the property of an object to acquire all the properties and behavior of its parent object. Inheritance represents the IS-A relationship which is also known as a parent-child relationship.
     - Important points.
         1. **Super Class:** The class whose features are inherited is known as superclass(or a base class or a parent class).
         2. **Sub Class:**  The class that inherits the other class is known as a subclass(or a derived class, extended class, or child class). The subclass can add its own fields and methods in addition to the superclass fields and methods.
         3. **Re-usability:** Inheritance supports the concept of “reusability”, i.e. when we want to create a new class and there is already a class that includes some of the code that we want, we can derive our new class from the existing class. By doing this, we are reusing the fields and methods of the existing class.

- **POLYMORPHISM**:- Polymorphism is the property of an object which allows it to take multiple forms. Polymorphism makes a function get implemented in different ways in classes and subclasses and get different forms Polymorphism creates a common interface for different implementation of a function for the programmer which operates differently for different objects. Polymorphism means “one class, some functions with different structures.
     - Types of Polymorphism:
       1. Compile-Time:- Compile time polymorphism or static polymorphism is resolved during compiler time.
       ```- Overloading is an example of compile-time polymorphism.```
       2. Run-Time:- Runtime polymorphism or dynamic polymorphism is resolved during runtime.
       ```- Overriding is an example of run-time polymorphism```

- **ENCAPSULATION**:- is a *Process of wrapping code and data together into a single unit*, ``` for example, a capsule which is mixed of several medicines```. It is the mechanism that binds together code and the data it manipulates. Another way to think about encapsulation is, it is a protective shield that prevents the data from being accessed by the code outside this shield.
     - Technically in encapsulation, the variables or data of a class are hidden from any other class and can be accessed only through any member function of own class in which they are declared.
    -   As in encapsulation, the data in a class is hidden from other classes using the data hiding concept which is achieved by making the members or methods of a class private, and the class is exposed to the end-user or the world without providing any details behind implementation using the abstraction concept, so it is also known as  **combination of data-hiding and abstraction.**.
   -   Encapsulation can be achieved by Declaring all the variables in the class as private and writing public methods in the class to set and get the values of variables.

- **ABSTRACTION**:-Abstraction is one of the  Key-Concept of object-oriented programming (OOP) languages. Its main goal is to handle complexity by hiding unnecessary details from the user. That enables the user to implement more complex logic on top of the provided abstraction without understanding or even thinking about all the hidden complexity.
   - That’s a very generic concept that’s not limited to object-oriented programming. You can find it everywhere in the real world.
   - Objects in an OOP language provide an abstraction that hides the internal implementation details. ```Similar to the coffee machine in your kitchen, you just need to know which methods of the object are available to call and which input parameters are needed to trigger a specific operation.``` But you don’t need to understand how this method is implemented and which kinds of actions it has to perform to create the expected result.
  
## ADVANTAGES OF OOPs
- **Re-usability**:-  Objects can be reused in different programs
- **Data Redundancy**:- Inheritance is a good feature for data redundancy if you need the same functionality in multiple classes you can write a common class for the same functionality and inherit that class to subclass.
- **Easy Maintenance**:- It is easy to maintain and modify existing code as new objects can be created with small differences to existing ones.
- **Data hiding**:- Implementation details are hidden from other modules and other modules have a clearly defined interface.
- **Security**:- Using data hiding and abstraction we are providing necessary data only it means we are maintaining security.

## CONCLUSION

Software engineering is the robust representation to measure the real-world entities with the help of object-oriented software. Object-oriented programming has shown a very drastic change in the nature of programming by the advent of the Object-Oriented Approach. The elements of OOP play a very important role in the development of the language and give broad options to the users while developing in the programming environment. With the feature like objects, encapsulations, polymorphism, inheritance, information hiding, and abstraction it can be seen that production of software is better by using these capabilities.

## References
- [Google](https://www.google.com/search?client=ubuntu&hs=4f7&sxsrf=ALeKk02U2Zv1cvnkrB-kNi_VGVyGeupGPg%3A1612940211205&ei=s4MjYMWJDNa7rQGn84WQDg&q=oops&oq=oops&gs_lcp=CgZwc3ktYWIQAzIECCMQJzIECCMQJzIECCMQJzIHCAAQsQMQQzIFCAAQkQIyCggAELEDEBQQhwIyBAgAEEMyBQgAELEDMgUIABCxAzICCAA6BwgjELADECc6BwgAEEcQsANQl5ZGWJeWRmCAmEZoAXACeACAAbcBiAG-ApIBAzAuMpgBAKABAaoBB2d3cy13aXrIAQnAAQE&sclient=psy-ab&ved=0ahUKEwiFr9TC3t7uAhXWXSsKHad5AeIQ4dUDCA0&uact=5)
- [geeksforgeeks](https://www.geeksforgeeks.org/object-oriented-programming-oops-concept-in-java/)
- [Stackify](https://stackify.com/oop-concept-abstraction/#:~:text=Abstraction%20is%20one%20of%20the,unnecessary%20details%20from%20the%20user.&text=That's%20a%20very%20generic%20concept,everywhere%20in%20the%20real%20world.)
- [Educba](https://www.educba.com/advantages-of-oop/)
- [Programming with mosh](https://www.youtube.com/watch?v=PFmuCDHHpwk)
- [Research Paper on Object-Oriented Software Engineering By- 1Iqbaldeep Kaur, 2Navneet Kaur, 3Amandeep Ummat, 4Jaspreet Kaur, 5Navjot Kaur](http://www.ijcst.com/vol74/1/8-iqbaldeep-kaur.pdf)

- [Object-Oriented Programming and its Concepts Asha Rani M1 Kavana M D2 Parvathy S J3 Shreelakshmi C M4](https://www.academia.edu/35629816/Object_Oriented_Programming_and_its_Concepts)
- [Object-Oriented Programming and its Concepts by Ashwin Urdhwareshe](http://www.ijcst.com/vol74/1/8-iqbaldeep-kaur.pdf)




