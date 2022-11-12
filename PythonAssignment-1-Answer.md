## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
    Python is an object-oriented, high-level programming language. Object-oriented means this language is based around objects (such as data) rather than functions, and high-level means it's easy for humans to understand.


Q2. Why is Python called a dynamically typed language?
    Python is called as dynamicallly typed language because the type of variable is determined only during the runtime.

Q3. List some pros and cons of Python programming language?
    There are many pros and cons of Python Programming language
    Pros:
    1.Python is easy to learn and read
    2.Python enhances productivity
    3.Python has a vast collection of libraries
    4.Python is an interpreted language
    Cons:
    1.Python has speed limitations
    2.Python can have runtime errors
    3.Python consumes a lot of memory space



Q4. In what all domains can we use Python?
    Python is used in different domains. Web Development domain plays a vital role. It is also used in Data Science, Data Analyst, Data Engineer, Game Development,
    Testing, Automation, Networks etc..

Q5. What are variable and how can we declare them?
    Variable is name that is referened to the object and it is declared as
    small_num=0

Q6. How can we take an input from the user in Python?
    In Python we can take input using the below format
    a=input()
    

Q7. What is the default datatype of the value that has been taken as an input using input() function?
    The default datatype of the value that has been taken as an input using input() function is string(str).


Q8. What is type casting?
    Type casting is method which is used to convert a variable data type to certain data type.
    For example: a=int(9.89), b=float(8)


Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
    Yes we can take using single input() along with split() method.
    For example: 
    a, b = input("Enter two of your lucky number: ").split() 
    print(a) 
    print(b) 



Q10. What are keywords?
    Python keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.
    No keywords cannot be used as the variable because keywords has predefined meaning

Q12. What is indentation? What's the use of indentaion in Python?
     Indentation refers to the spaces at the beginning of a code line. In Python indentation plays an important role.Other languages uses indentation for 
     readability purposes ony

Q13. How can we throw some output in Python?
    print() statement is used to get the output.

Q14. What are operators in Python?
     In Python, operators are special symbols that designate that some sort of computation should be performed. The values that an operator acts on are called operands.


Q15. What is difference between / and // operators?
    '/' is the divison which returns the quotient of the number with the decimal places
    '//' is the floor division which return the quotient to the round to the nearest whole number.

Q16. Write a code that gives following as an output.

```
iNeuroniNeuroniNeuroniNeuron

```
a='iNeuron'
print(a*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

n=int(input())
if n%2==0:
  print("It is Even Number")
else:
  print("It is Odd Number")


Q18. What are boolean operator?
     A boolean expression is an expression that yields just the two outcomes: true or false. When we work with multiple boolean expressions or perform some action on them, we make use of the boolean operators.Since the boolean expression reveals true or false, the operations on these expressions also result in either "true" or "false".
     Boolean Operators are AND,OR and NOT

Q19. What will the output of the following?
```
1 or 0--> 1

0 and 0-->0

True and False and True-->False

1 or 0 or 0--> 1
```

Q20. What are conditional statements in Python?
     Conditional Statement in Python perform different computations or actions depending on whether a specific Boolean constraint evaluates to true or false. Conditional statements are handled by IF, ELIF and SWITCH statements in Python.

Q21. What is use of 'if', 'elif' and 'else' keywords?
    if, elif and else are conditional statements that provide you with the decision making that is required when you want to execute code based on a particular condition.


Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Age=int(input())
if Age>=18:
  print("I can vote ")
else:
  print("I can't vote")



Q23. Write a code that displays the sum of all the even numbers from the given list.
```

numbers = [12, 75, 150, 180, 145, 525, 50]
sum=0
for i in range(len(numbers)):
  if numbers[i]%2==0:
    sum=sum+numbers[i]
print(sum)

```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

a=int(input())
b=int(input())
c=int(input())
if a>b and a>c:
  print(a,"is the greatest number")
elif b>a and b>c:
  print(b,"is the greatest number")
else:
  print(c,"is the greatest number")

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
for i in range(len(numbers)):
  if numbers[i]%5==0 and numbers[i]<150:
    print(numbers[i])
  elif numbers[i]>500:
    break