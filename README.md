# Python101 - A Guide to Python 

---------------------------------------------------------------

## Table of Contents

- [Data Types](https://github.com/Ladydiana/Python101#data-types)
  - [Integer](https://github.com/Ladydiana/Python101#data-types)
  - [Floating Point](https://github.com/Ladydiana/Python101#data-types)
  - [Complex Numbers](https://github.com/Ladydiana/Python101#data-types)
  - [Strings](https://github.com/Ladydiana/Python101#data-types)
  - [Boolean](https://github.com/Ladydiana/Python101#data-types)
  - [Lists](https://github.com/Ladydiana/Python101#data-types)
  - [Dictionaries](https://github.com/Ladydiana/Python101#data-types)
  - [Tuples](https://github.com/Ladydiana/Python101#data-types)
  - [Sets](https://github.com/Ladydiana/Python101#data-types)
- [Naming Conventions](https://github.com/Ladydiana/Python101#naming-conventions)
- [Printing](https://github.com/Ladydiana/Python101#printing)
- [Assignment Operators](https://github.com/Ladydiana/Python101#assignment-operators)
- [Arithmetic Operators](https://github.com/Ladydiana/Python101#arithmetic-operators)
  -[Addition](https://github.com/Ladydiana/Python101#arithmetic-operators)		
  -[Subtraction](https://github.com/Ladydiana/Python101#arithmetic-operators)	
  -[Multiplication](https://github.com/Ladydiana/Python101#arithmetic-operators)
  -[Division](https://github.com/Ladydiana/Python101#arithmetic-operators) 		
  -[Mode](https://github.com/Ladydiana/Python101#arithmetic-operators)  		
  -[Floor Division](https://github.com/Ladydiana/Python101#arithmetic-operators)
  -[Exponent](https://github.com/Ladydiana/Python101#arithmetic-operators)
- [Bitwise Operators](https://github.com/Ladydiana/Python101#bitwise-operators)  
- [Comparison Operators](https://github.com/Ladydiana/Python101#comparison-operators)
- [Logical Operators](https://github.com/Ladydiana/Python101#logical-operators)
- [Conditional Operators](https://github.com/Ladydiana/Python101#conditional-operators)
- [Loops](https://github.com/Ladydiana/Python101#loops)

---------------------------------------------------------------

<p align="center"> ★★★ </p>  

---------------------------------------------------------------



## Data Types

| Data Types      			| 		Example								| Comments 			|
| ------------- 			|  ------------------------- 				| --------------------
|	Integer					|         ``` 1234567123 ```				| In Python 3 integers have no length limit |
|	Floating Point Numbers	|         ``` 2.5 ```, ``` .3e5 ```			| |
|	Complex Numbers			|         ``` 2 + 5j ```					| |
|	Strings					|         ``` "I am Groot." ```				| |
|   Boolean 				|         ``` True ```, ```False ```		| |
|   Lists  					|         ``` [1,2,3] ```					| |
|   Dictionaries  			|         ``` {'key1': 'value1', 'key2':'value2'} ```					| |
|   Tuples  				|         ``` (1,2,3) ```					| Tuples do not support value assignment |
|   Sets  					|         ``` {1,2,3} ```					| |


To determine the type of a variable or expression we use the ``` type()``` function.



## Naming conventions

```  joined_lower ```  for functions, methods, attributes, variables (also called Snake Case)

```  joined_lower or ALL_CAPS ```  for constants

```  StudlyCaps ```  for classes (also called Pascal Case)

```  camelCase ```  only to conform to pre-existing conventions

Variable names in Python cannot start with a number or special characters and cannot be a reserved word.



## Printing

TODO: -> print()

TODO: -> Escape Characters



## Assignment Operators

In Python, variables don't need a type to be assigned previously or during the declaration and dont need to be defined in advance.

``` n = 3 ```

Python allows chained assignments, so that assigning the same value to multiple variables is easier.

```a = b = c = 5 ```

Also, variables in Python are not typre restricted, so a variable which was previously an int can be reassigned as a string.

``` 
n = 12
print(n)
>>> 12
n = "This is Sparta!"
print(n)
>>> This is Sparta!
```



## Arithmetic Operators

| Operator      | Description   			| 			Example			| Result (a=4, b=2)		|
| ------------- | ------------------------ 	| ------------------------- | ---------------------	|
|		+		| Addition					|        ``` a+b ```		| 	```	6 ```		|
|		-		| Subtraction				|        ``` a-b ```		| 	```	2```  		|
|		*		| Multiplication 			|        ``` a*b ```		| 	```	8 ``` 		|
|		/		| Division 					|        ``` a/b ```		| 	```	2 ```	 	|
|      % 		| Mode  					|        ``` a%b ```		| 	```	0 ```		|
|      //  		| Floor Division  			|        ``` a//b ```		|	```	2 ```		|
|      **  		| Exponent  				|        ``` a**b ```		|	```	16 ```		|


## Bitwise Operators

TODO




## Comparison Operators

| Operator      | Description   			| 			Example			| Result (a=3, b=5)		|
| ------------- | ------------------------ 	| ------------------------- | ---------------------	|
|		>		| Greater than				|        ``` a>b ```		| 	```	False ```		|
|		<		| Less than					|        ``` a<b ```		| 	```	True ```  		|
|		>=		| Greater than or Equal to 	|        ``` a>=b ```		| 	```	False ``` 		|
|		<=		| Less than or Equal to 	|        ``` a<=b ```		| 	```	True ```	 	|
|      == 		| Equality Operator  		|        ``` a==b ```		| 	```	False ```		|
|      !=  		| Not Equal Operator  		|        ``` a!=b ```		|	```	True ```		|



## Logical Operators

TODO



## Conditional Operators

TODO



## Loops

TODO: for, while, do while

