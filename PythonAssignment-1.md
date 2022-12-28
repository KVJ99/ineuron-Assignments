## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
    Because python can be used in a variety of ways. Both top down and bottom up approach can be followed. It isn't specialized for any specific problems.

Q2. Why is Python called a dynamically typed language?
    In python there is no declaration of datatype of variabe just assignment in the code.  It doesn’t know about the type of the variable until the code is run. So declaration is of no use. 

Q3. List some pros and cons of Python programming language?
    Pros: Number of libraries for diffrent purposes
          It can run the same source code across operating systems.
          Syntax is very simple and hence gives faster and efficient building process for program.
    Cons: Lacks Multithreading 
          has more memory consumption than other languages
          Slower than Java and C/C++

Q4. In what all domains can we use Python?
    Artificial intelligence, Big Data, data scince, machine learning and deep learning

Q5. What are variable and how can we declare them?
    Variables are containers for storing data values. A variable is created the moment you first assign a value to it.
    Ex:- x=5
         name='Kaustubh'

Q6. How can we take an input from the user in Python?
    We can do it using the input() method. 
    Ex: name = input("Enter your name:")


Q7. What is the default datatype of the value that has been taken as an input using input() function?
    String

Q8. What is type casting?
    it is a way to convert the variable data type into another data type. There can be two types of Type Casting in Python:- 
    Implicit Type Casting
    Explicit Type Casting

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
    We can do it using split() function. t breaks the given input by the specified separator. 
    x, y = input("Enter two values: ").split() 

Q10. What are keywords?
     keywords are words that have specific meanings and purposes and can't be used for anything but those specific purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.
     No, because keywords are used for a specific purpose and python does not allow using them as variable names.

Q12. What is indentation? What's the use of indentaion in Python?
     It is space given before a line of code. Python uses indentation to indicate a block of code.
     

Q13. How can we throw some output in Python?
     We can do it using Print() or retrun() funation

Q14. What are operators in Python?
     Operators are used to perform operations on variables and values. They are denoted using some symbols. 

Q15. What is difference between / and // operators?
    / is the dibision operator and // is floor division operation. // gives float output only if one os the operands is float. / always gives float output.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
    x="iNeuroniNeuroniNeuroniNeuron"
    print(x)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

x= int(input("Enter a number"))
if (x%2==0):
    print("Even")
else:
    print("Odd")

Q18. What are boolean operator?
    Logican operatiors which operate on Boolean datatype and give output as boolean are beelean opertors.

Q19. What will the output of the following?
```
1 or 0 = 1

0 and 0 = 0

True and False and True = False

1 or 0 or 0 = 1
```

Q20. What are conditional statements in Python?
    Conditional statements are used for decision making in python, they are used to handle conditions in the code
    Ex: if, elif, else

Q21. What is use of 'if', 'elif' and 'else' keywords?
     These are conditional statements used for decision making in python. They help automate that decision making process.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

x= int(input("Enter age"))
if (x>=18):
    print("I can vote")
else:
    print("I can't vote")
     

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
numbers = [12, 75, 150, 180, 145, 525, 50]
sum=0
for i in numbers:
    if (i%2==0):
        sum=sum+i
print(sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

x = int(input("Enter first number: "))
y = int(input("Enter second number: "))
z = int(input("Enter third number: "))
ans=0

if (x >= y) and (x >= z):
   ans = x
elif (x >= y) and (x >= z):
   ans = y
else:
   ans = z

print("The largest number is", ans)


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if(i>500):
        break
    elif(i>150):
        continue
    elif(i%5==0):
        print(i)