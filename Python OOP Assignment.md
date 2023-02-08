## Python OOP Assignment
Q1. What is the purpose of Python's OOP?
    Purpose of oops is to bring and manage real world entities into programming.
    It also brings encapsulation and data binding to improve modularity and security in the code.

Q2. Where does an inheritance search look for an attribute?
    First in the object, then in its class and then in a parent class of the existing onject's class.    

Q3. How do you distinguish between a class object and an instance object?
    Class object is a blueprint of how the object will look while the instance object is a real place in memory where an object of a certain class exists.

Q4. What makes the first argument in a class's method function special?
    The first object of a class's method function is the object itself which calls the function. It is refrenced by the 'self' keyword.

Q5. What is the purpose of the init method?
    init method initializes the object for a class alaong with its attributes. It is used to build a constructor of a class.

Q6. What is the process for creating a class instance?
    to create a class instance we can do the following:-

    x = <ClassName>(pram1, param2,...)

    calling the __init__ menthod using the class name and providing the arguments for it.

Q7. What is the process for creating a class?
    We can create it using 'class' keyword

    eg:- class ABC:
            a=5

Q8. How would you define the superclasses of a class?
    The parent class through which a class inherits its properties is called as a superclass.

Q9. What is the relationship between classes and modules?
    A module is a package of code which can contain multiple or a single class/classes. It can be imported and the classes inside it can be used.

Q10. How do you make instances and classes?
    Class can be made using 'class' keyword and its instances can be made by calling the __init__ menthod using the class name and providing the arguments for it.

Q11. Where and how should be class attributes created?
     Class attributes are the attributes which are shared by all the objects/instances of the class. They are created when we need some value which is indipendent of the objects and still need to be tagged with the class

Q12. Where and how are instance attributes created?
    Instance attributes are made in the __init__ method and have diffrent values and addresses for diffrent objects of the class.

Q13. What does the term "self" in a Python class mean?
    'self' is a reference to the current object/instance of the class.

Q14. How does a Python class handle operator overloading?
    In Python, overloading is done by overriding the method which is specifically for an operator, in the user-defined class.

Q15. When do you consider allowing operator overloading of your classes?
    It is used when we want to use with the user-defined data type with diffrent operators in python.

Q16. What is the most popular form of operator overloading?
    '+' operator is overloaded to concatinate strings by operator overloading.

Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code?
    inheritence and polymorphism 

Q18. Describe three applications for exception processing.
    Exception processing is done to -
    1. respond to unwanted or unexpected events when program runs
    2. Avoids the program or system to crash
    3. Give better user experience if program malfunctions

Q19. What happens if you don't do something extra to treat an exception?
    The program will focefully get terminated without a concerete and proper message to the user for the termination.

Q20. What are your options for recovering from an exception in your script?
    We can provide try brock to catch these exceptions and process them in a way which we see fit for the code.

Q21. Describe two methods for triggering exceptions in your script.
    Raise 

Q22. Identify two methods for specifying actions to be executed at termination time, regardless of  
whether or not an exception exists.
    Finally 

Q23. What is the purpose of the try statement?
    It is used to check a block of code for exceptions when it is in runtime.

Q24. What are the two most popular try statement variations?
    try-except and try-else.
    After try:
    except is executed when a error is thrown by the code in try block
    else is executed when try code does not have any exception

Q25. What is the purpose of the raise statement?
    It is used to define an exception to be expicityly raised and message to be shown for it.

Q26. What does the assert statement do, and what other statement is it like?
    It is used to debug the code. It is used to test if a condition is true for the code. If it is false AssertionError is thrown.

Q27. What is the purpose of the with/as argument, and what other statement is it like?
    With is commonly used for exception handling in file streams in place of try and catch. 
    As Keyword is used to give alias in python

Q28. What are *args, **kwargs?
    *args is used to pass number of Non-Keyword Arguments in a function.
    *kwargs is used to pass a keyworded, variable-length argument list

Q29. How can I pass optional or keyword parameters from one function to another?
    It can be done using keyword arguments.

Q30. What are Lambda Functions?
    lambda is a keyword used for defining the anonymous function

Q31. Explain Inheritance in Python with an example?
    Inheritace is used to perovide 'is a' relationship between classes in python.
    Example SUV inherits CAR 

Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of 
class C, which version gets invoked?
    Version of class A will get invoked as it is written first in the code 'C(A,B)'

Q33. Which methods/functions do we use to determine the type of instance and inheritance?
    isinstance()

Q34.Explain the use of the 'nonlocal' keyword in Python.
    it is used when a variable in a function cannot be used in a nested fucntion

Q35. What is the global keyword?
    It is used when we need to manipulate a variable outside of its scope.