## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans: - python can be used in wide variety of sw task right from automating till developing application, no specific area limit for the language
     it got elegant syntax and easy learning
	 - python has huge veriety of data type/structures, inbuild modules and libraries with them almost all sw industry needed things can be implemented

Q2. Why is Python called a dynamically typed language?
Ans: - Before using any variable to store the values no need of variable declaration and intilization with it's data type,
       as execution goes the value type can be keep varied there is no need to stick to specific data-type for each variable like other programming languages

Q3. List some pros and cons of Python programming language?
Ans: -Pros:
		* no too many rules to write the code, it's like english like language 
		* open source, multiple platform language
		* high level language has big data structures and can implemented precise data-algorithms
		* no need compilation , interpreter language got quick run
		* can be use for automation, scripting , web developemnt, game apps, desktop aps, data , AI, many more can fit almost everywhere
		
	-cons:
		* run time errors, no compilation (dynamically typed) one serious issue that code execution may stop at any point if there are bugs 
		  not advisable for machine and life crictical applications
		* interpreter executes the code line by line
		* weak in mobile computing and browsing (not well fit for mobile apps)
		
		
Q4. In what all domains can we use Python?
Ans: web dev, test automation and embedded scripting, data engineering, machine learning, mobile app 

Q5. What are variable and how can we declare them?
Ans: variables are entities used to store data, they can be declared with two components i.e. data-type and name of variable

Q6. How can we take an input from the user in Python?
Ans: data=input("Please enter the input: ")  [python : 3]	

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans: with python 3.0 onwards its default string type

Q8. What is type casting?
Ans: way in which converting variable value data type from one to other required type

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans: it reads only one time input from the user, one time execution 
	 a,b = input("enter values: ").split()
	 print("first value ",a)
	 print("second value ",b)

Q10. What are keywords?
Ans: built in names/words in language, each one has it's own purpose i.e. can't be use for userdefined variables or objects

Q11. Can we use keywords as a variable? Support your answer with reason.
Ans: No, can't violate the keyword purpose or standards 

Q12. What is indentation? What's the use of indentaion in Python?
Ans: main coding rule python got 4 spaces at every lines of code , idea is to create coding structure and organise the code

Q13. How can we throw some output in Python?
Ans: print() -> with print statement or with debug ,log functions 

Q14. What are operators in Python?
Ans: entities has various compuations, evaluations which are being carried out with python operators on data structures are called operators

Q15. What is difference between / and // operators?
Ans: '/' -> devision operator which gives quotient value in floating point
	 '//' -> floor division gives quotient without decimal point only integer part

Q16. Write a code that gives following as an output.
Ans: print("```\niNeuroniNeuroniNeuroniNeuron\n```")
```
iNeuroniNeuroniNeuroniNeuron
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans: number=int(input("The number is: "))
     if ((number%2)==0):
		print("it is even number")
	 else:
		print("it is odd number ")
		
		
Q18. What are boolean operator?
Ans: operators they represent truth testing from conditional statements give results in true or flase logical 0 or 1


Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
Ans: 1,0,False,1

Q20. What are conditional statements in Python?
Ans: statements evaluate expressions along with conditional keywords and opertaors gives end result 

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans: these are conditional keywords used to evaluate expressions results based on truth testing execution falls at different if, elif or else blocks
     

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans: age=int(input())
     if age>=18:
		print("I can vote")
	 elif (age<18):
		print("I can't vote")
		

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans: even_list=[i for i in numbers if i%2==0]
     print(sum(even_list))


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans: data=input("enter numbers: ").split()
	 values=list(map(int(),data))
	 greater=values[0]
	 for i in values:
		if (i>greater):
			greater=i
	 print("Greater number is: ",greater)
		

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans: for i in numbers:
		if (i%5==0):
			if (i>500):
				break
			elif(i>150):
				continue
			
			print(i)
			
