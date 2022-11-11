## Assignment Part-1

Q1. Why do we call Python as a general purpose and high-level programming language?
<b style='color:green; display:block'> Ans : </b>

```
Python is used in multiple domains like for web developemnt, operating system, Hardware devices etc.And python is very easy to understand So it is known as general purpose and high-level programming language.
```

Q2. Why is Python called a dynamically typed language?
<b style='color:green; display:block'> Ans : </b>

```
But Python is a dynamically typed language. It doesn’t know about the type of the variable until the code is run. So declaration is of no use. What it does is, It stores that value at some memory location and then binds that variable name to that memory container. And makes the contents of the container accessible through that variable name.
```

Q3. List some pros and cons of Python programming language?
<b style='color:green; display:block'> Ans : </b>

```
Pros:
Beginner-friendly
Flexible and Extensible
Highly Scalable
Portable
Embeddable
Extensive Libraries

Cons:
Issues with design
Slower than compiled languages
High memory consumption
Complex multithreading
```

Q4. In what all domains can we use Python?
<b style='color:green; display:block'> Ans : </b>

```
Python is easy to utilize, powerful, and versatile, making it a great for beginners and experts. Python’s readability makes it a great first programming language — it sanctions you to think like a programmer and not waste time with confusing syntax. Python is great for backend web development, data analysis, artificial intelligence, and scientific computing.
```

Q5. What are variable and how can we declare them?
<b style='color:green; display:block'> Ans : </b>

```
Variable is containers which store values. Python is not “statically typed”. We do not need to declare variables before using them or declare their type. A variable is created the moment we first assign a value to it. A Python variable is a name given to a memory location.
```

Q6. How can we take an input from the user in Python?
<b style='color:green; display:block'> Ans : </b>

```
input() is used for taking input from user. This function first takes the input from the user and converts it into a string.
```

Q7. What is the default datatype of the value that has been taken as an input using input() function?
<b style='color:green; display:block'> Ans : </b>

```
input() function takes the input from the user and converts it into a string. The type of the returned object always will be <type ‘str’>.
```

Q8. What is type casting?
<b style='color:green; display:block'> Ans : </b>

```
Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users.
```

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
<b style='color:green; display:block'> Ans : </b>

```
Yes, we can take multiple values or inputs in one line by using split() method.
x, y = input("Enter two values:").split()
print("Enter value of x:", x)
print("Enter value of y:", y)
print()
```

Q10. What are keywords?
<b style='color:green; display:block'> Ans : </b>

```
Keywords are some predefined and reserved words in python that have special meanings. Keywords are used to define the syntax of the coding. The keyword cannot be used as an identifier, function, and variable name.
```

Q11. Can we use keywords as a variable? Support your answer with reason.
<b style='color:green; display:block'> Ans : </b>

```
No, we can not use keyword as a variable. Because keywords are reserved word and has some specific meaning which can not be overridden by other meaning.
```

Q12. What is indentation? What's the use of indentaion in Python?
<b style='color:green; display:block'> Ans : </b>

```
Indentation refers to the spaces at the beginning of a code line. Python uses indentation to indicate a block of code.
```

Q13. How can we throw some output in Python?
<b style='color:green; display:block'> Ans : </b>

```
There is a "print()" function in python that is used to give output.
```

Q14. What are operators in Python?
<b style='color:green; display:block'> Ans : </b>

```
In python, operators are special symbols that designate that some sort of computation should be performed.
```

Q15. What is difference between / and // operators?
<b style='color:green; display:block'> Ans : </b>

```
'/' is the division operator. '//' is the floor division operator.
eg:
x = 10 / 3 ## 3.33333333
y = 10 // 3 ## 3
```

Q16. Write a code that gives following as an output.

```
iNeuroniNeuroniNeuroniNeuron
```

<b style='color:green; display:block'> Ans : </b>

```
print("iNeuroniNeuroniNeuroniNeuron")
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
<b style='color:green; display:block'> Ans : </b>

```
int_num = int(input("Enter a number"))
if int_num % 2 == 0:
    print("It is a even number.")
else:
    print("It is a odd number.")
```

Q18. What are boolean operator?
<b style='color:green; display:block'> Ans : </b>

```
'and' , 'or', 'not' are boolean operator in python.
```

Q19. What will the output of the following?

```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

<b style='color:green; display:block'> Ans : </b>

```
1. "1"
2. "0"
3. False
4. "1"
```

Q20. What are conditional statements in Python?
<b style='color:green; display:block'> Ans : </b>

```
There are three conditional statement in python.
i.e if, else and elif.
```

Q21. What is use of 'if', 'elif' and 'else' keywords?
<b style='color:green; display:block'> Ans : </b>

```
- if statement is used with a condition. Execution enters to "if" block when condition is true.

- When condition is false, Execution happens in "else" block.

- When above condition is false, we use another condition using "elif". By which we create nested if-else.
```

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
<b style='color:green; display:block'> Ans : </b>

```
age = int(input("Enter age of person"))

if(age >= 18):
    print("I can vote")
else:
    print("I can't vote")
```

Q23. Write a code that displays the sum of all the even numbers from the given list.

```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

<b style='color:green; display:block'> Ans : </b>

```
numbers = [12, 75, 150, 180, 145, 525, 50]
sum = 0

for i in numbers:
    if(i % 2 == 0):
        sum += i

print(sum)
```

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
<b style='color:green; display:block'> Ans : </b>

```
a = input("Enter 1st number")
b = input("Enter 2nd number")
c = input("Enter 3rd number")

print("Greatest Number :",max(a, b, c))
```

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop

```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

<b style='color:green; display:block'> Ans : </b>

```
numbers = [12, 75, 150, 180, 145, 525, 50]

for i in numbers:
    if(i < 150 and i % 5 == 0):
        print(i)
    if(i > 500):
        break
```
