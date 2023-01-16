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

Q26. What is a string? How can we declare string in Python?

    String represents a  sequence of characters. Once a string is created its immutable, meaning its value cannot be manipulated.
    name="Kaustubh"

Q27. How can we access the string using its index?
    using square brackets
    name="Kaustubh"
    print(name[0])


Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```
string = "Big Data iNeuron"
x = string.split(" ")
print(x[2])



Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"
```
string = "Big Data iNeuron"
x= string.split(" ")
print(x[2][::-1])


Q30. Resverse the string given in the above question.

string = "Big Data iNeuron"
print(string[::-1])

Q31. How can you delete entire string at once?
    Using del keyword
    name="Kaustubh"
    del name


Q32. What is escape sequence?
    It is a particular series of characters inside a string which is used to represent some other series of characters.
    eg \n for next line or new line

Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
print('iNeuron\'s Big Data Course')

Q34. What is a list in Python?
    Lists are sequentical data type in python. They are used to store multiple values in a single variable. 
    They are mutable and can increase or decrease their size.


Q35. How can you create a list in Python?
    Using []
    syntax:-
    my_list= [0, 1, [a,b,c], "kaustubh"]

Q36. How can we access the elements in a list?
    List elements can be accessed my index. 
    Name of the list followed by index no. in square brackets [].

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
``` 
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
print(lst[4][2])


Q38. Take a list as an input from the user and find the length of the list.
    mylist=list(input("Enter elements:").split(" "))
    print(len(mylist)) 


Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
```
lst = ["Welcome", "to", "Data", "course"]
lst.insert(3, "Big")
print(lst)

Q40. What is a tuple? How is it different from list?
    Tuple is sequential data type in python but unlike list it cannot be changed after being created, in other words its immutable.


Q41. How can you create a tuple in Python?
    using ()
    mytuple=(1,2."abcd",[x,y,z])

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
    its not possible as tuples are immutable. Code throws the following error:-
    TypeError: 'tuple' object does not support item assignment
    This can be done by using list() function to convert this into a list and then manipulate it.

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
     We can do it using concatination.
    a=('x','y','z')
    b=(1,2,3)
    c=a+b 
    print(c)
    

Q44. Take a tuple as an input and print the count of elements in it.

    mytuple=tuple(input("Enter numbers:").split(" "))
    print(len(mytuple))

Q45. What are sets in Python?
    set is a datatype in python which does not allow duplicate elements. It stores elements in unordered format but it is mutable and we can iterate throgh it.

Q46. How can you create a set?
     using {}
     myset={1,2,3}

Q47. Create a set and add "iNeuron" in your set.
    myset={1,2,3}
    myset.add("iNeuron")
    print(myset)

Q48. Try to add multiple values using add() function.
    myset={1,2,3}
    myset.add("x")
    myset.add("y")
    myset.add("z")
    print(myset)

Q49. How is update() different from add()?
    add() can add only one element to the set but update() can be used to add multiple elements.   

Q50. What is clear() in sets?
    it removes all the elements from the set

Q51. What is frozen set?
    it is a type of set which is immutable.

Q52. How is frozen set different from set?
    it can be used as key set in dictionaries and it is immutable.

Q53. What is union() in sets? Explain via code.
    this funtion creates a set with elements of multiple given sets.
    x = {"a", "b", "c"}
    y = {"f", "d", "a"}
    z = {"c", "d", "e"}
    l= {"q", "d", "e"}
    myset = x.union(y, z, l)
    print(myset)

Q54. What is intersection() in sets? Explain via code.
    this funtion creates a set with elements which are common in all the multiple given sets.
    x = {"a", "b", "c"}
    y = {"f", "c", "a"}
    z = {"c", "d", "c"}
    l= {"q", "c", "e"}
    result = x.intersection(y, z, l)    
    print(result)

Q55. What is dictionary in Python?
    Dictonary is a dataype which is used to store key value pairs in a single variable. it does not allow duplicate values.

Q56. How is dictionary different from all other data structures.
    it can store key value pairs while other cannot store keys.

Q57. How can we delare a dictionary in Python?
    using {}
    mydict={}

Q58. What will the output of the following?
```
var = {}
print(type(var))
```
dict

Q59. How can we add an element in a dictionary?
var = {}
var['name']='Kaustubh'
print(var)

Q60. Create a dictionary and access all the values in that dictionary.
mydict={'a':1, 'b':2, 'c':3}
for i, j in mydict.items():
    print(i,j)


Q61. Create a nested dictionary and access all the element in the inner dictionary.
mydict = {"Marks": {"English":10, "Math":20}}
for i, j in mydict["Marks"].items():
  print(i,j)

Q62. What is the use of get() function?
    it returns the value for the key given in the argument

Q63. What is the use of items() function?
    it retruns a list of all the key value pairs in the dictionary

Q64. What is the use of pop() function?
    Its used to delete a key value pair for the given key fron the dictionary

Q65. What is the use of popitems() function?
    it delets the last inserted key value pair from the dictionary

Q66. What is the use of keys() function?
    returns the list of all the keys in the dictionary

Q67. What is the use of values() function?
    returns the list of all the values in the dictionary

Q68. What are loops in Python?
    loops are used to run a block of codes repeatedly for a number of times

Q69. How many type of loop are there in Python?
    2. for and while

Q70. What is the difference between for and while loops?
    when no. of iterations is known we can use for loop. while runs until a certain condition is met.

Q71. What is the use of continue statement?
    in a loop, continue skips the code after it until the next iteration

Q72. What is the use of break statement?
    it stops a loop as soon as its executed

Q73. What is the use of pass statement?
    it is used to skip the line of code

Q74. What is the use of range() function?
    it returns a squence of numbers in a range which can be used in looping

Q75. How can you loop over a dictionary?
    using for loop
    mydict={'a':1,'b':2,'c':3}
    for i in mydict:
        print(i)


### Coding problems
Q76. Write a Python program to find the factorial of a given number.
num=0
fact=1
if(num==0 or num==1):
    print("1")
else:
    for i in range (1, num+1):
        fact=fact*i
    print(fact)

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100

p,r,t= input("enter principle amount, rate, time").split(" ")
p=int(p)
r=int(r)
t=int(t)
si=p*r*t/100
print("Intrest =", si)

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

p,r,t= input("enter principle amount, rate, time").split(" ")
p=int(p)
r=int(r)
t=int(t)
amt=p*(1+r/100)**t
ci=amt-p
print("Intrest =", ci)

Q79. Write a Python program to check if a number is prime or not.

num=18
flag=0
for i in range(2, (num//2)):
    if(num%i==0):
        print("Not Prime")
        flag=1
        break
if(flag==0):
    print("Prime")

Q80. Write a Python program to check Armstrong Number.

num=153
sum=0
temp=num
while(temp!=0):
    sum=sum+( pow(temp%10,3) ) 
    temp=temp//10
if(sum==num):
    print("Armstrong")
else:
    print("Not Armstrong")

Q81. Write a Python program to find the n-th Fibonacci Number.

num=7

def fn(num):
    if(num==0 or num==1):
        return num
    return fn(num-1) + fn(num -2)

print(fn(num))

Q82. Write a Python program to interchange the first and last element in a list.

nums=[1,2,3,4,5]
temp=nums[-1]
nums[-1]=nums[0]
nums[0]=temp
print(nums)


Q83. Write a Python program to swap two elements in a list.

nums=[1,2,3,4,5]
index_1= 2
index_2=3
temp=nums[index_1]
nums[index_1]=nums[index_2]
nums[index_2]=temp
print(nums)


Q84. Write a Python program to find N largest element from a list.

nums=[1,2,3,4,5]
n=2
nums.sort()
print(nums[n-1])

Q85. Write a Python program to find cumulative sum of a list.

nums=[1,2,3,4,5,6]
result=[]
sum=0
for i in range(0,len(nums)):
    sum=0
    for j in range(0,i+1):
        sum=sum+nums[j]
    result.append(sum)
print(result)

Q86. Write a Python program to check if a string is palindrome or not.

x="AABBCCBBAA"
rev=x[::-1]
if(x==rev):
    print("Palindrome")
else:
    print("Not a Palindrome")

Q87. Write a Python program to remove i'th element from a string.

x="0123456789"
n=2
result=""
for i in range(0,len(x)):
    if(i==n):
        continue
    result=result+x[i]
print(result)

Q88. Write a Python program to check if a substring is present in a given string.

  x="0123456789"
n="234"
if(x.count(n)>=1):
    print("Present")
else:
    print("not present")

Q89. Write a Python program to find words which are greater than given length k.

str="My Name is Kaustubh"
k=2
l=str.split(" ")
for i in l:
    if(len(i)>k):
        print(i)

Q90. Write a Python program to extract unquire dictionary values.

mydict={'a':1,'b':2,'c':3, 'd':1}
myset={list(mydict.values())[0]}
for i in mydict.values():
    myset.add(i)
print(myset)

Q91. Write a Python program to merge two dictionary.

dict1={1:1,2:2,3:3,4:4}
dict2={5:1,6:2,7:3,8:4}
dict1.update(dict2)
print(dict1)




Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```
Input = [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
result=dict(Input)
print(result)

Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```
input = [9, 5, 6]
output=[]
for i in input:
    temp=[]
    temp.append(i)
    temp.append(pow(i,3))
    temp=tuple(temp)
    output.append(temp)
print(output)

Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
```
test_tuple1 = (7, 2) 
test_tuple2 = (7, 8)

result1=[(i,j) for i in test_tuple1 for j in test_tuple2 ]
result2=[(i,j) for i in test_tuple2 for j in test_tuple1 ]

print(result1+result2)

Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
```

input =[('for', 24), ('Geeks', 8), ('Geeks', 30)]
     
lst = len(input)
for i in range(0, lst):
         
    for j in range(0, lst-i-1):
        if (input[j][1] > input[j + 1][1]):
            temp = input[j]
            input[j]= input[j + 1]
            input[j + 1]= temp
print(input)

Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```
for i in range (0,6):
    for j in range (0,i):
        print("*", end=" ")
    print()

Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```
n=6
for i in range(1,n):
    for j in range(n-i):
        print(" ",end="")
    for k in range(i):
        print("*",end="")
    print("\n")

Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```
n=5
x = n - 1

for i in range(0, n):
	for j in range(0, x):
		print(end=" ")
	x-=1
	for j in range(0, i+1):
		print("* ", end="")
	print("\n")


Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```
n=5
for i in range(n+1):
    for j in range(i):
        print(j+1,end="")
    print("\n")

Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```

n=5
for i in range(n+1):
    for j in range(i):
        print(chr(64+i)+" ",end="")
    print("\n")