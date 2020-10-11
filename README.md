
# Chiasma-Systems-Coding-Workshop-2020
Chiasma Auckland's Coding Workshop 2020.
 Presented by Ayush and Kabilan.

## Hello there!

Welcome to Chiasma's Coding Workshop for 2020. It's great to see you here. 

Regardless of whether you've coded before or study a tech-related degree, this workshop is here to teach you the basics of programming through Python - a language that is useful for so many things including making games, artificial intelligence, websites and analytics. In this workshop, we will first teach you the basic syntax, then progress to making a Tic-Tac-Toe simulation that you can show off to your mates! Our aim is to at least get you comfortable with what programming entails.



### Print statements

Want to send a happy birthday message to a friend next to you? You've come to the right place.

Python's print statements allow you to write messages to your system console.

eg. For "Happy birthday!", this can be done using:
   

     print("Happy birthday!")

eg. To sing Adele's song, just do:

    print("Helloooo")

Et cetera...

### Variables 

Variables are a way to store any type of information or data. In Python luckily we dont have to declare the type of variable we have so creating a variable for your name is as easy as 123...

eg. 

    PersonOne = "Steve"; 
       
    Persontwo = "Johnny";
    
    AgeOne = 20;
 
    AgeTwo = 25;
    
As we can see from these examples we have two different datatypes, the names are stored in the variables as strings, and the ages are stored as integers (since they are numbers)

### Lists

A list is a special type of datatype that is able to store multiple entries into a single variable. Lists can store all types of variables including strings, integers and also other lists. 

eg. 

    fruits = ["apple", "banana", "cherry", "mango"]

    print(len(fruits))   # The length function in python is used to determine how many items are stored in a list
    
    print(fruits)
      
      
eg. 

    fruits = [ ["orange", "apple", "banana"], ["pineapple", "mango", "cherry"] ]
    
    print(len(fruits))	# prints "2"
    
    print(fruits[0][1])	# Prints "apple"
    
    print(fruits[1]) # Prints ["pineapple", "mango", "cherry"]
    
    print(len(fruits[0]) # Prints "3"

### Comparison statements
To compare different variables with each other (for example checking if two numbers are equal), you can use a condition


eg. 

    if PersonOne == Persontwo: 
        
        print("Same person!")
     
    else:
       
       print ("Different people")

eg. 

    if AgeOne > AgeTwo:
           
	    print(" Steve is older than Johnny")
        
    else:
       
       print(" Johnny is older than Steve")


### Loops
In Python there are basically two types of loops. **For loops** and **While Loops**. Loops are useful to use when we have a list or array that we want to look through for any reason. 

eg. 

    numbers = [0,1,2,3,4,5,6,7,8,9]
    
    for digit in number:
	    print(digit)
      
eg. 

    numbers = [0,1,2,3,4,5,6,7,8,9]
    
    for i in range(len(numbers)):
	    numbers[i] = numbers[i]+1
      
    print(numbers)
    
eg. 

    fruits = ["banana", "apple", "orange", "kiwi"]
    
    position = 0
    
    while position < len(fruits):
        print(fruits[position])
        position = position + 1
        
     print("reached end of list")
    
### Functions
A function is a block of code which will only run when it is called. In functions you can also pass data, known as parameters into a function and a function can also return data as a result. 

eg. 

    def my_function(name):
	    print("My name is" + name)
    
    my_function("Ayush")
    my_function("Kabilan")
    my_function("Viewers")

eg. 

    def my_function(x):
		return 5 * x
    
    print(my_function(3))
    print(my_function(5))
    print(my_function(9))

### Libraries
A Python library is a collection of functions and methods that have already been written by others and they allow you to perform many actions that otherwise would normally take too long to write or would be too difficult for an average person. 

eg. 

    import time
    import random
    
    randDecimal = random.random()   # From the random library, the random() function generates a random float number between 0.0 to 1.0 
    randNum = random.randint(1,100)   # The randint() function gives us an integer between the specified parameters

    print (randDecimal)
    print(randNum)

  
