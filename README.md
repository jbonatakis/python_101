## Python 101

### Setup

1. Go to https://repl.it/
2. Click “+ new repl” in top right corner
	* Select “bash” 
	* “Create repl”

### About Python

Python is a high-level general purpose programming language. That means it is relatively easy to read and write, and can be used for a multitude of different purposes. 

### The Basics

#### Data Types

Python has all of the basic data types that you might expect to find in a programming language. An incomplete list of the most frequently encountered data types is below:

* Integer
* Float
* String
* Boolean

#### Data Structures

Python has a variety of data structures which are important to understand before undertaking a more advanced project.

* Tuple
* List
* Dictionary
* Set


#### Core Functions/Commands

`import` - Used to import Python packages and module, which allow for funtionality beyong what is offered by standard Python. Imports are traditionally handled at the beginning of a Python file.
	Example: `import os` 

`print` - Prints text to the console
	Example: `print("Hello, world!")`

#### Loops

***For Loop***

A for loop repeats an action for every item in a set. For example, a for loop may print the value of each object in a list, no matter the length of the list.

```
example_list = ['d', 'a', 's', '4', 2, 'done!']

for item in example_list:
	print(item)
```
Result:
 ```
d
a
s
4
2
done!
 ```


***While Loop***

A while loop continues to perform an action while a defined condition is true.

```
i = 0

while i < 5:
	print(i)
	i = i + 1
```

Result:
```
0
1
2
3
4
```