## Assignment Part-1

Q1. Why do we call Python as a general purpose and high-level programming language?
 Because its a human readable, writable  language and its converted to machine level using interpreter. Its has wide range of use so called general purpose.

Q2. Why is Python called a dynamically typed language?
 Because you dont need to specify data type during declaration of variable and the data type is decided on the go on the basis of value assigned to the variable.

Q3. List some pros and cons of Python programming language?
 Pros - Easy to read/write, not statiscally typed (dynamic), wide range of libraries available, great open source support
 Cons - Its slow compared to c++, java as its not compiled and interpreted line by line on the go. 

Q4. In what all domains can we use Python?
 data science, data analytics, big data, data engineering, software development, web development

Q5. What are variable and how can we declare them?
 variables are placeholders for changing values. In python its the name given to a memory location to which it points or refers to in memory. For eg: a = 5, a is variable name pointing to a memory loc where 5 (int data type) is stored. 

Q6. How can we take an input from the user in Python?
 Using the input function. And type casting is required to get input in desired data type for any successful operations as input function by default returns string data type. 
 a = input('Enter name:')

Q7. What is the default datatype of the value that has been taken as an input using input() function?
 string

Q8. What is type casting?
 converting data type to another type. For eg : str to int

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
 

Q10. What are keywords?
 keywords are reserved words in python having specific purpose which cannot be used to define variable names. Eg: list, tuple, or, and, False, True etc.

Q11. Can we use keywords as a variable? Support your answer with reason.
 no we cannot use keyword as a variable name. It can create a conflict when calling a variable as its reserved. 

Q12. What is indentation? What's the use of indentaion in Python?
 Indention is the space we give to create code blocks 

Q13. How can we throw some output in Python?

Q14. What are operators in Python?

Q15. What is difference between / and // operators?

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Q18. What are boolean operator?

Q19. What will the output of the following?
```
1 or 0 

Output : True

0 and 0

Output : False

True and False and True

Output : False

1 or 0 or 0

Output : True
```

Q20. What are conditional statements in Python?

Q21. What is use of 'if', 'elif' and 'else' keywords?

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Q23. Write a code that displays the sum of all the even numbers from the given list.


numbers = [12, 75, 150, 180, 145, 525, 50]

sum = 0
for i in numbers:
    if i % 2 == 0:
        sum = sum + i
print('sum of even numbers: ', sum)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
 
 a, b, c = int(input('Enter 1st no. : ')), int(input('Enter 2nd no. : ')), int(input('Enter 3rd no. : '))
if a > b and a > c:
    print('Greatest no. : ', a)
elif b > a and b > c:
    print('Greatest no. : ', b)
else:
    print('Greatest no. : ', c)


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]

for i in numbers:
    if i % 5 ==0:
        if i > 150 and i <= 500: 
            continue
        elif i > 500:
            break
        else:
            print(i)
        

        hello this is local edit



        