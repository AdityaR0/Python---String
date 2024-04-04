# Python---String Assignment Questions:

Q1) How can we store a single quote (‘) as a string in a variable?

Ans) string='Hello World'
     print(string)

Q2) Refer the below variable:
x = 'a'
Here, is x a character type or string type variable? Support your answer with an explanation.

Ans) String is a collection of alphabets, words or other characters. It is one of the primitive data structures and are the building blocks for data manipulation.
     Python has a built-in string class named str. 
     For example, "hello" is a string containing a sequence of characters 'h' , 'e' , 'l' , 'l' , and 'o'.

Q3) Apply the following functions on this variable: ‘Welcome to Python foundation course'.
(1)find()
(2)count()
(3)len()
(4)Concatenation

Ans) (1) txt = "Welcome to Python foundation course"
x = txt.find("welcome")
print(x)

(2) txt = 'Welcome to Python foundation course'
substring = 'o'
count = txt.count(substring)

(3) a = "Welcome to Python foundation course"
    len(a)
    
(4) var1 = "Welcome to Python foundation course"
var2 = "Hello PW"
var3 = var1 + var2
print(var3)

Q4) For the variable: word = "PanaJi@12256"
Calculate the following:
(a) Total number of alphabets in lowercase
(b) Total number of alphabets in uppercase
(c) Total number of numerical in string

Ans) Str="PanaJi@12256"
lower=0
upper=0
for i in Str:
      if(i.islower()):
            lower+=1
      else:
            upper+=1
(a) print("The number of lowercase characters is:",lower)
(b) print("The number of uppercase characters is:",upper)


(c) import re
string = "PanaJi@12256"
total_digits = len(re.findall('[0-9]',string))
print("Total digits found :-", total_digits)

Q5) Write a code to store a numerical value inside a variable then convert it into string.

Ans) num = 10
print("Type of variable before conversion : ", type(num)) 
converted_num = str(num)
print("Type After conversion : ",type(converted_num))
