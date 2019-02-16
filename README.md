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
- [Reserved Keywords](https://github.com/Ladydiana/Python101#reserved-keywords-in-python)
- [Printing](https://github.com/Ladydiana/Python101#printing)
- [Assignment Operators](https://github.com/Ladydiana/Python101#assignment-operators)
- [Arithmetic Operators](https://github.com/Ladydiana/Python101#arithmetic-operators)
  - [Addition](https://github.com/Ladydiana/Python101#arithmetic-operators)		
  - [Subtraction](https://github.com/Ladydiana/Python101#arithmetic-operators)	
  - [Multiplication](https://github.com/Ladydiana/Python101#arithmetic-operators)
  - [Division](https://github.com/Ladydiana/Python101#arithmetic-operators) 		
  - [Mode](https://github.com/Ladydiana/Python101#arithmetic-operators)  		
  - [Floor Division](https://github.com/Ladydiana/Python101#arithmetic-operators)
  - [Exponent](https://github.com/Ladydiana/Python101#arithmetic-operators)
- [Bitwise Operators](https://github.com/Ladydiana/Python101#bitwise-operators)
  - [Bitwise AND](https://github.com/Ladydiana/Python101#bitwise-operators)
  - [Bitwise OR](https://github.com/Ladydiana/Python101#bitwise-operators)
  - [XOR](https://github.com/Ladydiana/Python101#bitwise-operators)
  - [Bitwise NOT](https://github.com/Ladydiana/Python101#bitwise-operators)
  - [RIGHT SHIFT](https://github.com/Ladydiana/Python101#bitwise-operators)
  - [LEFT SHIFT](https://github.com/Ladydiana/Python101#bitwise-operators)
- [Comparison Operators](https://github.com/Ladydiana/Python101#comparison-operators)
- [Logical Operators](https://github.com/Ladydiana/Python101#logical-operators)
  - [AND](https://github.com/Ladydiana/Python101#logical-operators)
  - [OR](https://github.com/Ladydiana/Python101#logical-operators)
  - [NOT](https://github.com/Ladydiana/Python101#logical-operators)
- [Identity Operators](https://github.com/Ladydiana/Python101#identity-operators)
  - [is](https://github.com/Ladydiana/Python101#identity-operators)
  - [is not](https://github.com/Ladydiana/Python101#identity-operators)
- [Membership Operators](https://github.com/Ladydiana/Python101#membership-operators)
  - [in](https://github.com/Ladydiana/Python101#membership-operators)
  - [not in](https://github.com/Ladydiana/Python101#membership-operators)
- [Conditional Operators](https://github.com/Ladydiana/Python101#conditional-operators)
  - [if](https://github.com/Ladydiana/Python101#conditional-operators)
  - [elif](https://github.com/Ladydiana/Python101#conditional-operators)
  - [else](https://github.com/Ladydiana/Python101#conditional-operators)
- [Loops](https://github.com/Ladydiana/Python101#loops)

---------------------------------------------------------------

<p align="center"> ★★★ </p>  

---------------------------------------------------------------


<br/>

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


<br/>

## Naming conventions

```  joined_lower ```  for functions, methods, attributes, variables (also called Snake Case)

```  joined_lower or ALL_CAPS ```  for constants

```  StudlyCaps ```  for classes (also called Pascal Case)

```  camelCase ```  only to conform to pre-existing conventions

Variable names in Python cannot start with a number or special characters and cannot be a reserved word.


<br/>

## Reserved keywords in Python



|○       Keyword       ○|
| :---:	 	|
| and       |
| as        |
| assert    |
| break     |
| class     |
| continue  |
| def       |
| del       |
| elif      |
| else      |
| except    |
| False     |
| finally   |
| for       |
| from      |
| global    |
| if        |
| import    |
| in        |
| is        |
| lambda    |
| None      |
| nonlocal  |
| not       |
| or 	    |
| pass      |
| raise     |
| return    |
| True 		|
| try       |
| while     |
| with      |
| yield     |


<br/>

## Printing

There are a few printing methods in Python.

The first one is directly calling the varible.

```
 x = 'Hello World!'
 x
>>> 'Hello World!'
```

The downside to this method is that it also shows the quotes around a string.


The second method is by calling the ``` print() ``` function.

The print function accepts more than one argument to display.

``` 
print(x)
>>> Hello World!
``` 

TODO: -> Escape Characters


<br/>

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

Like other programming languages, in Python you can alse use **composed assignment operators**.
                                
| Operator      | Description   					| 			Example			| Equivalent to 		|	
| :---:			| :---:							 	| :---:						| :---:					|
|		+=		| Addition to operand				|        ``` a += 2 ```		| 	```	a= a+2 ```		|
|		-=		| Subtraction to operand			|        ``` a -= 2 ```		| 	```	a= a-2 ```  	|
|		*=		| Multiplication with operand 		|        ``` a *= 2 ```		| 	```	a= a*2 ``` 		|
|		/=		| Division with operand				|        ``` a /= 2 ```		| 	```	a= a/2 ```	 	|
|       %= 		| Mode to opearand 					|        ``` a %= 2 ```		| 	```	a= a%2 ```		|
|      //= 		| Floor Division to operand 		|        ``` a //= 5 ```	|	```	a= a//5 ```		|
|      **= 		| Exponent to operand 				|        ``` a **= 5 ```	|	```	a= a**5 ```		|
|      &=  		| Logical AND with operand 			|        ``` a &= b ```		|	```	a= a&b ```		|
|      \|=  	| Logical OR with operand 			|        ``` a \|= b ```	|	```	a= a\|b ```		|
|      ^=  		| Logical XOR with operand 			|        ``` a ^= b ```		|	```	a= a^b ```		|
|      >>=  	| Bitwise RIGHT SHIFT with operand 	|        ``` a >>= 2 ```	|	```	a= a>>2```		|
|      <<=  	| Bitwise LEFT SHIFT with operand 	|        ``` a <<= 2 ```	|	```	a= a<<2 ```		|



<br/>

## Arithmetic Operators

| Operator      | Description   			| 			Example			| Result (a=4, b=2)	|
| :---: 		| ------------------------ 	| :---:						| :---:				|
|		+		| Addition					|        ``` a+b ```		| 	```	6 ```		|
|		-		| Subtraction				|        ``` a-b ```		| 	```	2```  		|
|		*		| Multiplication 			|        ``` a*b ```		| 	```	8 ``` 		|
|		/		| Division 					|        ``` a/b ```		| 	```	2 ```	 	|
|      % 		| Mode  					|        ``` a%b ```		| 	```	0 ```		|
|      //  		| Floor Division  			|        ``` a//b ```		|	```	2 ```		|
|      **  		| Exponent  				|        ``` a**b ```		|	```	16 ```		|


<br/>

## Bitwise Operators

| Operator      | Description   			| 			Example			| Result (a=10 (binary 00001010), b=2 (binary 00000100))		|
| :---: 		| ------------------------ 	| :---:						| ----------------------------------------------------------	|
|		&		| Bitwise AND				|        ``` a & b ```		| 	```	0 ```  (binary 0000 0000)		|
|		\|		| Bitwise OR				|        ``` a \| b ```		| 	```	14 ```  (binary 0000 1110) 		|
|		^		| Bitwise XOR 				|        ``` a ^ b ```		| 	```	14 ```  (binary 0000 1110)		|
|		~		| Bitwise NOT 				|        ``` ~a ```			| 	```	-11 ```  (binary 1111 0101)	 	|
|       >>		| Bitwise RIGHT SHIFT  		|        ``` a >> 2 ```		| 	```	2 ```  (binary 0000 0010)		|
|       <<  	| Bitwise LEFT SHIFT 		|        ``` a << 2 ```		|	```	40 ```  (binary 0010 1000)		|


<br/>

## Comparison Operators

| Operator      | Description   			| 			Example			| Result (a=3, b=5)		|
| :---: 		| ------------------------ 	| :---: 					| :---:					|
|		>		| Greater than				|        ``` a>b ```		| 	```	False ```		|
|		<		| Less than					|        ``` a<b ```		| 	```	True ```  		|
|		>=		| Greater than or Equal to 	|        ``` a>=b ```		| 	```	False ``` 		|
|		<=		| Less than or Equal to 	|        ``` a<=b ```		| 	```	True ```	 	|
|      == 		| Equality Operator  		|        ``` a==b ```		| 	```	False ```		|
|      !=  		| Not Equal Operator  		|        ``` a!=b ```		|	```	True ```		|


<br/>

## Logical Operators

| Operator      | Description   						| 			Example			| 
| :---: 		| ------------------------ 				| :---:						| 
|		AND		| True is both operands are true		|        ``` a AND b ```	|	
|		OR		| True if at least one operand is true	|        ``` a OR b ```		| 
|		NOT		| Complement of the operand 			|        ``` NOT a ```		| 


<br/>

## Identity Operators

Used to check if two variables are in the same part of the memory.
```diff 
- !Attention! This does not imply equality.
``` 


| Operator      | Description   											| 			Example				|
| :---: 		| ------------------------ 									| :---:							|
|	is			| True if the operands refer to the same object				|        ``` x is True ```		| 
|	is not		| True if the operands do not refer to the same object		|        ``` x is not True ```	|


<br/>

## Membership Operators

Used to test a variable's membership to a certain structure.

| Operator      | Description   							| 			Example				|
| :---: 		| ------------------------ 					| :---:							| 
|	in			| True if variable is found in sequence		|        ``` 3 in x```			| 
|	not in		| True if variable is not found in sequence	|        ``` 3 not in x ```		|


<br/>

## Conditional Operators

Conditional Operators : **if, elif, else**.

After the if statement, a colon ':' is required.

Python does not require the condition/expression to be checked to be enclosed in paranthesis.

Python defines blocks by indentation (called the off-side rule), not by curly brackets. So, in order to execute more commands in an if block, they need to have the same indentation.

```
if <expression>:
	<statement>
	<statement>
	...
	<statement>
<other blocks>
```

An if block containts statements with the same indentation. If the next block has other indentation, it is not considered to be part of the if block.


```
if <expression>:
	<statement>
	<statement>
	...
	<statement>
elif <expression>:
	<statement>
	...
else:
	<statement>
	...
<other blocks>
```

In Python the *else if* statement is shertened as *elif*.


<br/>

## Loops

TODO: for, while, do while

