# Python 🐍
- Python  is an interactive , interpreted , object-oriented programming  language
- It is a high level programming language
- Initially designed by Sir Guido Van Rossum in 1991
## Careers in Python
- Software Engineer
- Python Developer
- Research Analyst
- Data Analyst
- Data Scientist
- Machine Learning Engineer
## Advantages and Disadvantages of Python
*Advantages*
- Presence of third party modules
- open source , easy to use , user friendly
- high language
- portable, interactive, highly efficient
- Dynamically typed language(No need to mention data types based on the value assigned, it takes data type.

*Disadvantages*
- Speed is slow because it is an interpreted language ,because of which code executed line by line.
- Python is an weak language for mobile development
- Python memory consumption is also too much high
## Compiler VS Interpreter
*compiler*
- The compiler scans the whole program in one go
- As it scans the code in one go, the errors are going to shown in the end
- the main advantage of compiler is it's execution time
- it converts source code into object code
- it is more efficient

*Interpreter*
- Translates the program one statement at a time
- errors are shown line by line not like compiler at end
- Due to interpreters being slow in executing the object code,it is preferred less
- It does not convert source code to object code
- It is less efficient
## IDLE (Integrated devlopment and Learning Environment)
- Python IDLE offers full-fledged file editor, which gives you the ability to write and execute python program from with in this program
- It allows programmers to easily write python code just like python shell, Idle can be used to cexecute a single statement and create , modify and execute python scripts
## IDE (Integrate Devlopment Environment)
- IDE Provides an Environment consolidated for the programmer to write a computer program
- Bascially IDE is an environment or combination of tools , jahan par aap code likhte ho apna
## REPL ( Read Evaluate Print Loop )
REPL is the interactive top level of programming language interpreter or command line shell. It offers the user a simple prompt , accepts expressions , evaluate them and print the result.
## Variables
Pyton variables can be only start with (A-Z/a-z) or underscore(_)
```python
Niharika=100
_lives='kanpur'
_lives
output='kanpur'
```
Python is an case-sensitive programming language , so python identifiers Name and name are two different things
```python
name='shradhha ji'
name
output='shradhha ji'
```
You can aslso assign multiple values to python varaibles in one statement.
```python
age,city=20,'kanpur'
print(age,city)
output=20 kanpur
```
We can also delete python variables using the keyword 'del'
```python
a='black'
dela
a
Name Error: name 'a' is not defined
```
# Python Datatype
- Datatype represent a type of data present inside a variable
Python Conatin following inbuilt data types :-
1) Int
2) Float
3) Complex
4) boal
5) str
6) bytes
7) bytearray
8) range
9) list
10) tuple
11) set
12) fozenset
13) dict
14) None

1) int : integer values
```python
a=10
type(a)
output=int
```
2) float: decimal values
```python
f=1.034
type(f)
output=float
```
3) complex: real + imaginary values
```python
a=3+5j
```
4)boal: for boolean values(true and false)
```python
a=kushara loves shradhha
b=shradhha loves kushagra
a=b
output: False 😭
```
5) str: koi bhi word or senetence in double or single quotes
```python
"kushagra loves shradhha ji"
"kushagra loves niharika ji"
'kushagra friend loves stuti ji'
```
6) list: group of values either int, float,str etc.. ( for storing duplicate values also)
```python
list=['ram','ghanshyam','radheshyam',1.5,True]
Print(list)
```
7) tuple: tuple is exactly same as list but it is only read version of list
```python
t(10,20,30,40)
type(t)
t[0]=100
type error:'tuple object does not support item assignment
```
8) dict: dictionary (storing data in the form of key value pairs)
```python
dict1 = { "name": "Kushagra", "age": 21, "girlfriends": 0 😭, "canCode": True, "canDraw": True }
```
etc..... 
aage aur bhi kai saare data type hai , lekin vo aap kahin se bhi padh skte ho vo bhutt simple hai .

main data type : 
```python
Integer: a=1
Boolean: b = False
String: c = "Shradhha ji"
NoneType: d = None
```
---
## Type Casting
Conerting from one data type to another

functions:-

- *int()*

- *float()*

- *complex()*

- *boal()*

- *str()*

## Types of type casting
- Explicit Conversion: Done manually by the developer.
- Implicit Conversion: Automatically performed by Python.

example:-

```python
int(123.456) # typecasting float value to integer
output-123

int("12") # typecasting string to integer
output-12
```
## Operators
Aise symbols jo kuch task perform karte hai.(+,-,x,%,/...etc)

*+* : Addition

*-* : Subtraction

*x(*)* : Multiplication

*/* : Division

*%* : Modulus

*//* : Floor Divsion

*xx(**)* : exponention

## String Handling
koi bhi word or senetence in double or single quotes (sequence of textual data)
- **String Indexing** : har string mein ek index number hota hai , uss string ke index ke zariya hmlog uss string ke characters ko access kar skte hai easily.
example : `name= Shradhha ka Aashiq`
```python
print(name[0])
output= S
```
> Note : In python , indexing start from 0
- **String Slicing** : Har string ko hmlog small small slices mein access kar skte hai (matlab chothe chothe part bhi string ka access karna easy hai )

![WhatsApp Image 2025-02-03 at 19 14 29_4f113bdd](https://github.com/user-attachments/assets/f0396cee-91b6-4f27-b20c-7d36b40d74b2)

```python
n="singh"
n[-1]
output=h

s[1:40]
output=ingh

s[:4]
output=sing
```
## Some methods of string
- `lower()` : Convert string to lowercase( bade ko chotha )
- `upper()` : convert string to uppercase( chothe ko bada)
```python
love='kushagra likes shradhha ji'
print(love.upper())
output= KUSHAGRA LIKES SHRADHHA JI

love2='KUSHAGRA LIKES NIH JI'
print(love2.lower())
output= kushagra likes nih ji
```
- `strip()` : removes whitespaces after and before the string.
```python
name='   kushagra is great at coding  '
print(name.strip())
output= 'kushagra is great at coding'
```
- `split()` : ye method split karta hai ek string ko in different-different strings.
```python
name='Hrithik Roshan'
print(name.split())
output=['Hrithik','roshan']
```
- `capitalize()` : Capitalizes the first character of the string.
- `count()` : Returns the number of occurrences of a value within the string.
```python
str='i like u i love u i miss u'
print(str.count('i'))
outpput=5
```
- `find()` : kisi string ke part ko find karta hai ye method , whether string is a part of that word or not ?
```python
str = "He's name is kushagra and he is enough goood"
print(str.find("is"))
print(str.find("Daniel"))
output=6
output=-1
```
These are the main string methods ☝️.

---
## Flow Control
Describes the order in which code will going to executed .
## Conditional Statements
- if
![WhatsApp Image 2025-02-04 at 09 56 51_ecf802c9](https://github.com/user-attachments/assets/c8fc408c-94e4-431b-a474-4d4c568c8d8c)

- if-else

*Example* :
```PYTHON
BaliTripPrice=2,00000
budget=1000
if budget < BaliTripPrice:
    print("Aur paise kama bsdk")
else:
   print("chla jaa bhai trip pe")
```
- if-else-elif
*example* :
```python
num = 0
if num < 0:
    print("number is negative")
elif num == 0:
    print("number is zero")
else:
    print("number is positive")
```
## Iterative Statements (loops overall)
- `for`
- `while`

## For Loops
A for loop is used for iterating over a sequence(that is either a list, a tuple, a dictionary, a set, or a string).
*example* :
```python
fruits = ["amrud(guava)", "banana(kela)", "mango(aam)"]
for x in fruits:
  print(x)
```
## While Loop
A while loop repeatedly executes a block of code as long as a condition is True.
```python
count = 5
while count > 0:
    print(count)
    count -= 1
else:
    print("I am inside else")
```

## Transfer Statements
*break* : Exits the loop immediately.

With the break statement we can stop the loop before it has looped through all the items
```python
fruits = ["amrud(guava)", "banana(kela)", "mango(aam)"]
for x in fruits:
  print(x)
  if x == "banana":
    break
```
*continnue* : Skips the rest of the code inside the current iteration of the loop.

With the continue statement we can stop the current iteration of the loop, and continue with the next
```python
fruits = ["amrud(guava)", "banana(kela)", "mango(aam)"]
for x in fruits:
  if x == "banana":
    continue
  print(x)
```
## Python Functions ( simply,aise statements jinko ham baar baar call kar ske aur use kar ske with few lines of code)

```python
def my_function():
  print("Hello from a Kushagra")

my_function()
```

If a group of statements is repeatedly required then it is not recoomended to write these statements every time . We just have to define the statements as a single unit and we can call them any no of times..

Main advanatage is code reusability
>Note: In other languages functions are methods,procedures etc.

Python support 2 types of functions
1) Built in functions
2) User defined functions

Built in functions: Jo pehle se hi bane hue hai by python team , jaise:
`min()`, `max()`, `len()`, `sum()`, `type()`, `tuple()`, `list()`, `set()`, `print()`, `range()`, `dict()`

User-defined Functions: Aise functions jo user ke zariye banaye gye hai , for certain tasks.
```python
def desire:
      desire='shradhha ji meri hojaaye 😤'
# joke tha don't take it seriously
```
Real Example of functions :
```python
def wish(name):
         print('hello',name,'good morning')
    wish('shradhha ji')
    wish('niharika ji')
output=hello shradhha ji good morning
output=hello niharika ji good morning
```
## Arguments
Information can be passed into functions as arguments.

Arguments are specified after the function name, inside the parentheses. You can add as many arguments as you want, just separate them with a comma.
```python
def my_function(fname):
  print(fname + "😘")

my_function("Niharika ji")
my_function("Shradhha ji")
```
## Parameters or Arguments?
The terms parameter and argument can be used for the same thing: information that are passed into a function.

- **Arbitrary arguments** (*args)
If you do not know how many arguments that will be passed into your function, add a * before the parameter name in the function definition.
```python
def my_function(*girls):
  print("The girl kushagra like is " + girls[1])

my_function("Shradhha ji", "Niharika ji", "Gwen Stacy")
```
- **Keyword Arguments**
Provide values in a key-value format, allowing you to skip the order of arguments.
```python
def greet(fname, mname, lname):
    print("Hello", fname, mname, lname)

greet(mname="Peter", lname="parker", fname="Gwen")
```
## List 
List in python is a data type that is a collection of items. it is also known as dynamic array in other programming languages
It is also mutable data type , it means that you can change the value of the list items.
*Example* :
```python
l=[1,2,3,45,6]
l2=['kushagra',21,'BTECH']
l3=['Shradhha ji','age doesn't matter']
```
> We can use `in` keyword in list.
```python
me=['today', 'after' ,'a', 'long' ,'time', 'i' ,'saw' ,'my', 'crush']
if "crush" in me:
    print("crush is present")
```
## Accesing list items
```python
names=['kushagra','niharika','shradhha']
print(names[0])
print(names[-1])
print(namess[:6])
print(names[::2])
print(namess[1:3])
```
## List Methods
- `list.copy()`: Returns a copy of the list.
```python
copy_me=clock.copy()
```
- `list.append()`:  Appends an item to the end of the list.
```python
crush_list=['shradhha ji','niharika ji']
crush_list.append('no one')
```
- `list.insert()`: Inserts an item at a specified index.
```python
mood=['happy','sad']
mood.insert(1,'bkchodi')
```
- `list.extend()`: Adds elements from another list or collection to the end of the list.
```python
my_crush=['niharika ji','shradhha ji']
animesh_crush=['infinite girls']
my_crush.extend(animesh_crush)
```
- `list.sort()`: Sorts the list in ascending order or in descending order
```python
names=['kushagra','niharika','shradhha']
names.sort()
#for descending order
names.sort(reverse=True)
```
- `list.reverse()`: Reverses the list.
```python
names.reverse()
```
- `list.index()`: Returns the index of the first occurrence of a specified item.
```python
names.index('shradhha')
```
- `list.count()`: Returns the count of items with a specified value.
```python
names.count('niharika')
```
## Tuple 
Tuple is exactly same as list except that it is immutable,once  we create tuple object. We cannot perform any change in that object , Hence tuple is read only version of list
```python
t=10,20,30,40
print(t)
print(type(t))
```
> check for item in tuple using in keyword:
```python
country = ("India", "Italy", "Spain")
if "India" in country:
   print("india present")
```
## Tuple Methods
- `count()`: Returns the number of occurrences of a specified value.
```python
tup1 = (1, 2, 3, 3, 3)
print(tup1.count(3)) 
```
- `index(): Returns the index of the first occurrence of a specified value.
```python
tupp = (1, 2, 3, 4)
print(tup1.index(2))
```
## Set 
- If we want to represent a group of unique values as a single entity then we should go for a set
- Duplicates are not allowed
- Insertion order are not preserved . But we can sort the elements
- We use curly braces {}
- Indexing and slicing are not allowed for the set
```python
s={10,20,30,40}
print(s)
print(type(s))
```
```python
s=set(range(5))
print(s)
```
# Operations
Operations: `add`, `union`, `difference`, `intersection`, `update`
- `union()`:Prints all items present in two sets.
- `update()`:adds items from another set into the existing set.
- `intersection()`:Prints all items that are similar in both sets.
*example* :
```python
my_crush = {'shradhha ji','niharika ji'}
animesh_crush= {'muskan','kirti','anushka','rimjhim'}
merge = my_crush.union(animesh_crush)
print(merge)
my_crush.update(animesh_crush)
print(merge)
my_crush.intersection(animesh_crush)
```
## Set methods
`isdisjoint()` , `add()`, `update()`,`remove()`,`pop()`,`del()`,`clear()`....
There are various sets methods which you can learn by yourself 👨‍💻.

## Dictionaries
- If we want to represent a group of objects as key-value pairs then we should go for dictionary
- Duplicate keys are not allowed but vakues can be duplicated.
- Dictionaries are mutable.
- indexing aur slicing concepts are not applicable.
```python
info = {"name": "kushagra", "age": 21, "language": "python"}
```
```python
info['name']
info.get('language')
```
# Dictionary methods:
```python
ep1 = {122: 45, 123: 89, 567: 69, 670: 69}
ep2 = {222: 67, 566: 90}
ep1.update(ep2) 
ep1.clear() 
ep1.pop(122)
ep1.popitem()
del ep1[122] 
```
## Exception handling
- The `try` block lets you test a block of code for errors.
- The `except` block lets you handle the error.
- We can use the `else` keyword to define a block of code to be executed if no errors were raised:
- The `finally` block, if specified, will be executed regardless if the try block raises an error or not.
When an error occurs, or exception as we call it, Python will normally stop and generate an error message.
*example* :
```python
try:
  print(x)
except:
  print("An exception occurred")
```
*another example* :
```python
try:
  print("Hello")
except:
  print("Something went wrong")
else:
  print("Nothing went wrong")
```
*ek aur example* :
```python
try:
  print(x)
except:
  print("Something went wrong")
finally:
  print("The 'try except' is finished")
```
## Classes and Objects
- Python is an object oriented programming language.
- Almost everything in Python is an object, with its properties and methods.
- A Class is like an object constructor, or a "blueprint" for creating objects.

`creating a class` :
```python
class MyClass:
  x = 5
```
`creating a object`:
```python
p1 = MyClass()
print(p1.x)
```
---
Agar achha laga ho to , please drop a 🌟. 
> mere aur meri crush ke liye hi kardo :)

![WhatsApp Image 2025-02-04 at 22 30 44_90c403d9](https://github.com/user-attachments/assets/836e2f32-557b-48ea-89f4-02f332b8c655)

