# python

* [ List and Tuple](#a)
* [What is dictionary in Python](#b)
* [What is the difference between tuple and dictionary?](#c)
* [What is the difference between NumPy and SciPy?](#d)
* [Difference between generators and iterators?](#e)
* [What is __init__?](#f)
* [What is break, continue and pass in Python?](#g)
* [What is the difference between Python Arrays and lists?](#h)
* [What is docstring in Python?](#i)
* [ What is the difference between xrange and range in Python?](#j)
* [What is pickling and unpickling?](#k)
* [Explain split() and join() functions in Python?](#l)
* [What does *args and **kwargs mean?](#m)
* [What is pep 8?](#n)
* [What are python namespaces?](#o)
* [What are the common built-in data types in Python?](#p)
* [ Is python case sensitive?](#r)
* [ What is the lambda function in Python?](#s)
* [What are docstrings in Python?](#z)
* [ What is the usage of help() and dir() function in Python? ](#x)
* [What are mutable and immutable data types?](#y)
* [Explain the difference between an array and a linked list.](#1b)

x = "Hello World"	str	

x =  20	int	

x =  20.5	float	

x =  1j	complex	

x =  ["apple", "banana", "cherry"]	list	

x =  ("apple", "banana", "cherry")	tuple	

x =  range(6)	range	

x =  {"name" : "John", "age" : 36}	dict	

x =  {"apple", "banana", "cherry"}	set	

x =  frozenset({"apple", "banana", "cherry"})	frozenset	

x =  True	bool	

x =  b"Hello"	bytes	

x =  bytearray(5)	bytearray	

x =  memoryview(bytes(5))	memoryview	




## List and Tuple <a name="a"></br>

- Lists and Tuples are both sequence data types that can store a collection of objects in Python. The objects stored in both sequences can have different data types. Lists   are represented with square brackets ['sara', 6, 0.19], while tuples are represented with parantheses ('ansh', 5, 0.97).

## What is dictionary in Python? Give an example. <a name="b"></br>
A Python dictionary is a collection of items in no particular order. Python dictionaries are written in curly brackets with keys and values. Dictionaries are optimised to retrieve value for known keys.

## What is the difference between tuple and dictionary? <a name="c"></br>
One major difference between a tuple and a dictionary is that dictionary is mutable while a tuple is not. Meaning the content of a dictionary can be changed without changing it’s identity, but in tuple that’s not possible.

## What is the difference between NumPy and SciPy?  <a name="d"></br>
NumPy stands for Numerical Python while SciPy stands for Scientific Python. NumPy is the basic library for defining arrays and simple mathematica problems, while SciPy is used for more complex problems like numerical integration and optimization and machine learning and so on.

## Difference between generators and iterators?  <a name="e"></br>
In Python, iterators are used to iterate over a group of elements (in a list, for example). The way of implementing these iterators is known as generators. It yields an expression in the function, but otherwise behaves like a normal function.

## What is __init__?  <a name="f"></br>
- __init__ is a contructor method in Python and is automatically called to allocate memory when a new object/instance is created. All classes have a __init__ method       associated with them. It helps in distinguishing methods and attributes of a class from local variables.


## What is break, continue and pass in Python?  <a name="g"></br>
  Break	The break statement terminates the loop immediately and the control flows to the statement after the body of the loop.
  Continue	The continue statement terminates the current iteration of the statement, skips the rest of the code in the current iteration and the control flows to the     next iteration of the loop.
  Pass	As explained above, the pass keyword in Python is generally used to fill up empty blocks and is similar to an empty statement represented by a semi-colon in       languages such as Java, C++, Javascript, etc.
  
 
   
## What is the difference between Python Arrays and lists?   <a name="h"></br>
  Arrays in python can only contain elements of same data types i.e., data type of array should be homogeneous. It is a thin wrapper around C language arrays and           consumes far less memory than lists.
 Lists in python can contain elements of different data types i.e., data type of lists can be heterogeneous. It has the disadvantage of consuming large memory.
 
 
## What are decorators in Python?  <a name="i"></br>
  Decorators in Python are essentially functions that add functionality to an existing function in Python without changing the structure of the function itself. They are   represented the @decorator_name in Python and are called in a bottom-up fashion. 
  
## What is the difference between xrange and range in Python?  <a name="j"></br>
  xrange() and range() are quite similar in terms of functionality. They both generate a sequence of integers, with the only difference that range() returns a Python       list, whereas, xrange() returns an xrange object.
  
  
 ## What is pickling and unpickling?  <a name="k"></br>
  Python library offers a feature - serialization out of the box. Serializing an object refers to transforming it into a format that can be stored, so as to be able to     deserialize it, later on, to obtain the original object. Here, the pickle module comes into play.

  Pickling:

  Pickling is the name of the serialization process in Python. Any object in Python can be serialized into a byte stream and dumped as a file in the memory. The process   of pickling is compact but pickle objects can be compressed further. Moreover, pickle keeps track of the objects it has serialized and the serialization is portable     across versions.
 The function used for the above process is pickle.dump().
 
Unpickling:

Unpickling is the complete inverse of pickling. It deserializes the byte stream to recreate the objects stored in the file and loads the object to memory.
The function used for the above process is pickle.load().

## Explain split() and join() functions in Python?  <a name="l"></br>
You can use split() function to split a string based on a delimiter to a list of strings.
You can use join() function to join a list of strings based on a delimiter to give a single string.

## What does *args and **kwargs mean?  <a name="m"></br>
*args

*args is a special syntax used in the function definition to pass variable-length arguments.
“*” means variable length and “args” is the name used by convention
**kwargs

*kwargs is a special syntax used in the function definition to pass variable-length keyworded arguments.
Here, also, “kwargs” is used just by convention. You can use any other name.
Keyworded argument means a variable that has a name when passed to a function.
It is actually a dictionary of the variable names and its value.
  
 
 
## What is pep 8? <a name="n"></br>
   PEP in Python stands for Python Enhancement Proposal.It is a set of rules that specify how to write and design Python code for maximum readability.  
  
## What are python namespaces? <a name="o"></br>
A Python namespace ensures that object names in a program are unique and can be used without any conflict. Python implements these namespaces as dictionaries with ‘name as key’ mapped to its respective ‘object as value’.

Let’s explore some examples of namespaces:

Local Namespace consists of local names inside a function. It is temporarily created for a function call and gets cleared once the function returns.
Global Namespace consists of names from various imported modules/packages that are being used in the ongoing project. It is created once the package is imported into the script and survives till the execution of the script.
Built-in Namespace consists of built-in functions of core Python and dedicated built-in names for various types of exceptions.

## What are the common built-in data types in Python? <a name="p"></br>
Python supports the below-mentioned built-in data types:

Immutable data types:

Number
String
Tuple
Mutable data types:

List
Dictionary
set
  
  
## Is python case sensitive?  <a name="r"></br>
Yes,Python is a case sensitive language.This means that Function and function both are different in python alike SQL and Pascal.  


## What is the lambda function in Python?  <a name="s"></br>
A lambda function is an anonymous function (a function that does not have a name) in Python. To define anonymous functions, we use the ‘lambda’ keyword instead of the ‘def’ keyword, hence the name ‘lambda function’. Lambda functions can have any number of arguments but only one statement.
  
## What are docstrings in Python?  <a name="z"></br>
Docstrings are not actually comments, but, they are documentation strings. These docstrings are within triple quotes. They are not assigned to any variable and therefore, at times, serve the purpose of comments as well.  

## What is the usage of help() and dir() function in Python?  <a name="x"></br>
Help() and dir() both functions are accessible from the Python interpreter and used for viewing a consolidated dump of built-in functions. 

Help() function: The help() function is used to display the documentation string and also facilitates you to see the help related to modules, keywords, attributes, etc.
Dir() function: The dir() function is used to display the defined symbols.
  
## what are mutable and immutable data types? <a name="y"></br>
 Mutable data types can be changed after creating them. Some of the mutable objects in Python are list, set, dict.

 Immutable data types can’t be changed after creating them. Some of the immutable objects in Python are str, tuple.  
 

 ## Explain the difference between an array and a linked list.<a name="1b"></br>
An array is a collection of elements of a similar data type. A linked list is a collection of objects known as a node where node consists of two parts, i.e., data and address. Array elements store in a contiguous memory location. Linked list elements can be stored anywhere in the memory or randomly stored. 
  
  
  
  
  
  
  
  
  
  
  
  
  
  
