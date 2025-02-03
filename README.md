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
