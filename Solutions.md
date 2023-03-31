## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

A.Python is called high-level programming language because it can be used to easily write by humans and easy to understand and it has a great versatility because python can be used in many domains like data sciences,data engineering,machine learning and many other

Q2. Why is Python called a dynamically typed language?

A.Python is called Dynamically typed language because we can declare the variable on go in runtime and easy for type casting.
Q3. List some pros and cons of Python programming language?

A.Pros:

1.Python is Easy to Learn and Use Programming Language

2.Python has a reach library support 

3.Python has a great versatility

Cons:

1.Python is Dynamically typed 

2.Perfomance of Python is Slow

2.Python has a reach library support

3.Python has a great versatility 

Cons:

 1.Python is Dynamically typed 
 
 2.Perfomance of Python is Slow

Q4. In what all domains can we use Python?

A.In Data Sciences,Data Analytics,Data Sciences,Data Engineering,Artificial Intelligence,Machine Learning And Many Other 

Q5. What are variable and how can we declare them?

A.Variable is location in memory that stores value,we can declare a variable directly equating it to some value.

Q6. How can we take an input from the user in Python?

A.by using input() function


Q7. What is the default datatype of the value that has been taken as an input using input() function?

A.String is the default datatype of the value that has been taken as input in input() function.

Q8. What is type casting?

A.Type Casting is converting data type of variable from one type to another datatype.


Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

A.Yes, by using loop functions such as for,while. 

Q10. What are keywords?

A.keywords are words in python which have a specific functionality and cannot be used as variable.

Q11. Can we use keywords as a variable? Support your answer with reason.

A.we cannot use keyword as variable as they have specific functionality to perform.

Q12. What is indentation? What's the use of indentaion in Python?

A.Indentation is Space given between the code after using this sign ":"

Q13. How can we throw some output in Python?

A.By Using print() function

Q14. What are operators in Python?

A.operators in python are used to perform operation on values stored in variables they are used for various tasks like comparing the variables ,assigning values and performing arthimetic operations 


Q15. What is difference between / and // operators?

A."/" operator gives float value as output "//" gives int value as output.

Q16. Write a code that gives following as an output.

iNeuroniNeuroniNeuroniNeuron
A..word="iNeuron"
print(word*3)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

number=int(input())
if number%2==0:
    print("number is Even")
else:
    print("number is Odd")

Q18. What are boolean operator?

A.Boolean operators in python are AND,OR,NOT and they are called Boolean Operators because they produce output whether true or false.

Q19. What will the output of the following?
```
1 or 0
1
0 and 0
0
True and False and True
False
1 or 0 or 0
1

Q20. What are conditional statements in Python?

A..Conditional Statemnts in Python are used to compile the code in condition of the code. 

Q21. What is use of 'if', 'elif' and 'else' keywords?

A.if,elif and else are the conditional keywords 

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
age = int(input())
if age>=18:
    print("I can vote")
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]

even_sum=0
for i in numbers:
    if i%2==0:
        even_sum+=i
    else:
        even_sum=even_sum
print(even_sum)

    
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

numbers_list=[]
for i in range(3):
    numbers=int(input())
    numbers_list.append(numbers)
print(max(numbers_list))



Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five
numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if i%5==0:
        print(i)
- If the number is greater than 150, then skip it and move to the next number
numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if i>=150:
        continue 
    else:
        print(i)
- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
for i in numbers:
    if i>500:
        print(i)
```

Q26. What is a string? How can we declare string in Python?

A.string is a combination of characters we can declare a string in python by palcing the characters in double or single quotations or by using string() fuinction


Q27. How can we access the string using its index?

A.we can access the string by by string slicing the String like this

String_word = StringName[0:len(StringName)] 

Q28. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "iNeuron"
```
string = "Big Data iNeuron"
String_split = string.split(" ")
desired_output = String_split[2]
print("desired_output = "+ desired_output)

Q29. Write a code to get the desired output of the following
```
string = "Big Data iNeuron"
desired_output = "norueNi"
String_split = string.split(" ")
desired_output = String_split[2]
print("desired_output = "+desired_output[::-1])

Q30. Resverse the string given in the above question.
string = "Big Data iNeuron"
reversed_string=string[::-1]
print(reversed_string)

Q31. How can you delete entire string at once?

A.you cannot delete a string because string are immutable objects , hiwever you can delete a string variable using "del" keyword.

Q32. What is escape sequence?

A.Escape sequence are some characters which are used in double quotes but are not printed after usig priont function and they perform string manipulations such as printing the string in a seperate line , representing a tab character etc..]
"/n" represents a new line,"/t" represent a tab character 

Q33. How can you print the below string?
```
'iNeuron's Big Data Course'
```
print("'iNeuron's Big Data Course'")

Q34. What is a list in Python?

A.list is a collection of items in an order and mutable. 

Q35. How can you create a list in Python?

A.we can create a list by enclosing the items in a bracket "[]" or by using list() function.

Q36. How can we access the elements in a list?

A.we can access the elements in a string by list indexing

Q37. Write a code to access the word "iNeuron" from the given list.
```
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
desired_word=lst[4][2]
print(desired_word)
``` 

Q38. Take a list as an input from the user and find the length of the List.
lst = ["Welcome", "to", "Data", "course"]
length_of_list = len(lst)
print(length_of_list)

Q39. Add the word "Big" in the 3rd index of the given list.
```
lst = ["Welcome", "to", "Data", "course"]
lst.insert(2,"Big")
print(lst)
```
Q40. What is a tuple? How is it different from list?

A.Tuple is an ordered collection of items and it is a immutable object.Lists are mutable and tuples are immutable means we can change the items in list but not a tuple and we cannot add new items to a existing tuple.

Q41. How can you create a tuple in Python?

A.We can create a tuple in python using tuple() function.

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.

A. No, We Cannot Add a new item top the tuple because it is immutable

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?

A.Yes two tuples can be Appended.
  tuple_1=(1,2,3)
  tuple_2=(3,4,5)
  tuple=tuple_1+tuple_2
  print(tuple)
  output:(1,2,3,3,4,5)
Q44. Take a tuple as an input and print the count of elements in it.

A.tuple_1=(1,2,3)
count_of_elements_Tuple=len(tuple_1)
print(count_of_elements_Tuple)

Q45. What are sets in Python?

A.Sets are  unordered collection of unique items enclosed in flower brackets "{}"

Q46. How can you create a set?

A.we can create a set by using set() function or "{}"

Q47. Create a set and add "iNeuron" in your set.

A.
new_set=set()
new_set.add("iNeuron")
print(new_set)

Q48. Try to add multiple values using add() function.

A.
new_set=set()
word_List=["iNeuron","PWSkills","Big Data"]
for word in word_List:
    new_set.add(word)
print(new_set)

Q49. How is update() different from add()?

A.update() function adds multiple values while add() adds a single value
 
Q50. What is clear() in sets?

A.clear() function removes all the elements from a set

Q51. What is frozen set?

A.frozen set converts a normal set to a Immutable Object

Q52. How is frozen set different from set?

A.A Normal Set is Mutable but a frozen set is Immutable

Q53. What is union() in sets? Explain via code.

A.union() between two sets give the combination of unique elements and common elements as a new set.

Q54. What is intersection() in sets? Explain via code.

A.intersection() between two sets gives the common elements in both sets.

Q55. What is dictionary in Python?

A.A Dictionary is a mutable collection of items in a key-pair format.

Q56. How is dictionary different from all other data structures.

A. Dictionaries Stores the Elements in Key-Value pairs,they are mutable and unordered , have flexible key and value types which is very useful for some programming Tasks

Q57. How can we delare a dictionary in Python?

A.we can declare a dictionary in python by using dict() function

Q58. What will the output of the following?
```
var = {}
print(type(var))
```
output:<class 'dict'>

Q59. How can we add an element in a dictionary?

A.we add an element in a dictionary by entering a new key pair like
```
dict_1=dict()
dict_1["Name"]="Javed"
print(dict_1)

Q60. Create a dictionary and access all the values in that dictionary.

dict_1=dict()
dict_1["Name"]="Javed"
dict_1["Age"]=23
dict_1["Job"]="Data Engineer"
for values in dict_1.values():
    print(values)

Q61. Create a nested dictionary and access all the element in the inner dictionary.

student_data = {
  "John": {
    "age": 21,
    "major": "Computer Science",
    
  },
  "Emily": {
    "age": 19,
    "major": "Engineering",

  }
}
for key in student_data.keys():
    print("=====================outer_keys===============================================================")
    print(key)
for value in student_data.values():
    print("=====================outer_values==============================================================")
    print(value)
    for inner_key in value.keys():
        print("=====================inner_keys===============================================================")
        print(inner_key)
    for inner_value in value.values():
        print("=====================inner_values===============================================================")
        print(inner_value)


Q62. What is the use of get() function?

A.get() function is used to get values from keys in dictionary like
  dict.get("key") = "values"

Q63. What is the use of items() function?

A.get() function converts the key-value pair to tuple
 
Q64. What is the use of pop() function?

A.pop() function is used to delete the  key-value pair in the dictionary.

Q65. What is the use of popitems() function?

A.popitems() function is used to delete the last key-value pair in the dictionary.

Q66. What is the use of keys() function?

A.keys() function is used to retreive all the keys of a dictionary.  

Q67. What is the use of values() function?

A.values() function is used to retreive all the values of a dictionary

Q68. What are loops in Python?

A.loops are used to repeat a block of code until it satisfies a specific condition

Q69. How many type of loop are there in Python?

A.There are two types of for,while loops

Q70. What is the difference between for and while loops?

A. for loop is use when you want to iterate over a sequence of elements on the other hand while loop is used to run under certain condition is true or false

Q71. What is the use of continue statement?

A.continue statement is used to continue the loop when  condition is satisfied without executing it.

Q72. What is the use of break statement?

A.break statement is used to break the loop when the condition is satisfied.

Q73. What is the use of pass statement?

A.pass statement is used to run the code without writing block of code

Q74. What is the use of range() function?

A.range() function is used to iterate over numbers from 0 to the number less mention in the range() argument.

Q75. How can you loop over a dictionary?

A.my_dict = {"apple": 3, "banana": 5, "orange": 2}
for i in my_dict.keys():
    print(i)
for j in my_dict.values():
    print(j)


### Coding problems
Q76. Write a Python program to find the factorial of a given number.

A.def factorial_of_number(input_number):
    factorial=1
    for i in range(input_number):
        if input_number==0 or input_number==1:
            return 1
        else:
           return input_number*factorial_of_number(input_number-1)
        
input_number=int(input())
factorial_of_given_number=factorial_of_number(input_number)
print(factorial_of_given_number)

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (P*R*T)/100

p=int(input())
t=int(input())
r=int(input())
Simple_interest=p*t*r/100
print(Simple_interest)
Q78. Write a Python program to calculate the compound interest. Formula of compound interest is CI = P(1+R/100)^T

p=int(input())
t=int(input())
r=int(input())
compound_interest = p*((1+(r/100))**t)
print(compound_interest)

Q79. Write a Python program to check if a number is prime or not.

num=int(input())
counter=0
for i in range(num):
    if num%(i+1)==0:
        counter+=1
if num==0 or num==1:
    print("The Given Number is Neither Prime Nor Composite")
elif counter==2:
    print("The Given Number is Prime")
else:
    print("The Given Number is Composite")

Q80. Write a Python program to check Armstrong Number.

input_number=input()
length_input_number=len(input_number)
arm_criteria=0
for i in range(length_input_number):
    arm_criteria+=int(input_number[i])**length_input_number
if arm_criteria==int(input_number):
    print("The Given Number is An Armstrong Number")
else:
    print("The Given Number is Not An Armstrong Number")

Q81. Write a Python program to find the n-th Fibonacci Number.

def fibonacci_series_func(num):
    if num==1:
        return 0
    elif num==2:
        return 1
    else:
        return fibonacci_series_func(num-2)+fibonacci_series_func(num-1)
Number=int(input())
Nth_Fibonacci_Number=fibonacci_series_func(Number)
print(Nth_Fibonacci_Number)
Q82. Write a Python program to interchange the first and last element in a list.

lst = ["Welcome","to","Big","Data","Course"]
position1=0
position2=len(lst)-1
lst[position1],lst[position2]=lst[position2],lst[position1]
print(lst)

Q83. Write a Python program to swap two elements in a list.

lst = ["Welcome","to","Big","Data","Course"]
position1=3
position2=1
lst[position1],lst[position2]=lst[position2],lst[position1]
print(lst)

Q84. Write a Python program to find N largest element from a list.

Nth_Element=int(input())
numList = [10, 25, 30, 15, 40, 20]
max_List=[]
for i in numList:
    max_List+=[max(numList)]
    numList.remove(max(numList))
Nth_Largest_Element=max_List[Nth_Element-1]
print(Nth_Largest_Element)

Q85. Write a Python program to find cumulative sum of a list.

numList = [1, 2, 3, 4, 5]
Cummulative_Sum=0
Cummulative_Sum_list=[]
for i in range(len(numList)):
    Cummulative_Sum+=numList[i]
    Cummulative_Sum_list.append(Cummulative_Sum)
print(Cummulative_Sum_list)

Q86. Write a Python program to check if a string is palindrome or not.

Input_String = input()
if Input_String==Input_String[::-1]:
    print("It is a Palindrome")
else:
    print("It is Not a Palindrome")

Q87. Write a Python program to remove i'th element from a string.

ith_element=int(input())
input_string=input()
ith_element_removed_string=input_string[:ith_element-1]+input_string[ith_element:]
print(ith_element_removed_string)


Q88. Write a Python program to check if a substring is present in a given string.

input_string=input()
input_sub_string=input()
if input_sub_string in input_string:
    print("Sub String is Present")
else:
    print("Sub String is Absent")

Q89. Write a Python program to find words which are greater than given length k.

lst = input()
k=int(input())
for i in lst:
    if k<len(i):
        print(i)

Q90. Write a Python program to extract unquire dictionary values.
```
dictionary={'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
dict_keys=dictionary.keys()
print(dict_keys)

Q91. Write a Python program to merge two dictionary.
```
dictionary={'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
dictionary_1={'Sach': 13, 'MSF': 27, 'SDF': 48, 'Lohit': 53}
dictionary.update(dictionary_1)
print(dictionary)
Q92. Write a Python program to convert a list of tuples into dictionary.
```
Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
```
given_Input= [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
dictionary_of_players=dict()
for i in given_Input:
    (name,age)=i
    dictionary_of_players[name]=age
print(dictionary_of_players)

Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
```
Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
```
list = [9, 5, 6]
tuples_list=[]
for i in list:
    cube_pair_tuple=(i,i**3)
    tuples_list+=[cube_pair_tuple]
print(tuples_list)    

Q94. Write a Python program to get all combinations of 2 tuples.
```
Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
def combination_of_tuples(test_tuple):
    combination_tuple_list=[]
    for i in test_tuple:
        for j in test_tuple:
            combination_of_tuples=(i,j)
            combination_tuple_list+=[combination_of_tuples]
    return combination_tuple_list


test_tuple1 = (7, 2)
test_tuple2 = (7, 8)
List_of_combination_of_Tuples=[]
combination_of_tuples_output_1 = combination_of_tuples(test_tuple1)
combination_of_tuples_output_2=combination_of_tuples(test_tuple2)
combination_of_tuples_output = combination_of_tuples_output_1+combination_of_tuples_output_2
sorted_combination_of_tuples_output = sorted(combination_of_tuples_output,key=lambda x:x[0])
print(sorted_combination_of_tuples_output)

Q95. Write a Python program to sort a list of tuples by second item.
```
Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
list_of_tuples = [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
sorted_list_of_tuples=sorted(list_of_tuples,key = (lambda x:x[1]))
print(sorted_list_of_tuples)

Q96. Write a python program to print below pattern.
```
* 
* * 
* * * 
* * * * 
* * * * * 
```
n=5
for i in range(n):
    print("* "*(i+1))


      

Q97. Write a python program to print below pattern.
```
    *
   **
  ***
 ****
*****
```
n=5
for i in range(n):
    print(" "*(n-i-1)+"*"*(i+1))
    

Q98. Write a python program to print below pattern.
```
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
```
n=5
for i in range(n):
    print(" "*(n-i-1)+"* "*(i+1))

Q99. Write a python program to print below pattern.
```
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
```
numbers_List = ["1 ","2 ","3 ","4 ","5 "]
for i in numbers_List:
    for j in range(len(Alphabets_List)):
        if Alphabets_List[j]==i:
            print(i*(j+1))
        else:continue
Q100. Write a python program to print below pattern.
```
A 
B B 
C C C 
D D D D 
E E E E E 
```
Alphabets_List = ["A ","B ","C ","D ","E "]
for i in Alphabets_List:
    for j in range(len(Alphabets_List)):
        if Alphabets_List[j]==i:
            print(i*(j+1))
        else:continue