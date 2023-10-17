# JavaScript Operators

## Types of JavaScript Operators

There are different types of JavaScript operators:

#### Arithmetic Operators
```
+	Addition
-	Subtraction
*	Multiplication
**	Exponentiation (ES2016)
/	Division
%	Modulus (Division Remainder)
++	Increment
--	Decrement
```

#### Assignment Operators
```
=	x = y	x = y
+=	x += y	x = x + y
-=	x -= y	x = x - y
*=	x *= y	x = x * y
/=	x /= y	x = x / y
%=	x %= y	x = x % y
**=	x **= y	x = x ** y
```
####  Comparison Operators
```
==	equal to
===	equal value and equal type
!=	not equal
!==	not equal value or not equal type
>	greater than
<	less than
>=	greater than or equal to
<=	less than or equal to
?	ternary operator
```
#### String Operators
```
String Comparison

 EX:-
 let text1 = "A";
 let text2 = "B";
 let result = text1 < text2; // true

String Addition

 EX:-
 let text1 = "John";
 let text2 = "Doe";
 let text3 = text1 + " " + text2; // John Doe

Adding Strings and Numbers

 EX:-
 let x = 5 + 5;
 let y = "5" + 5;
 let z = "Hello" + 5;
```
#### Logical Operators
```
&&	logical and
||	logical or
!	logical not
```
#### Bitwise Operators
```
&	AND	5 & 1	0101 & 0001	0001	 1
|	OR	5 | 1	0101 | 0001	0101	 5
~	NOT	~ 5	 ~0101	1010	 10
^	XOR	5 ^ 1	0101 ^ 0001	0100	 4
<<	left shift	5 << 1	0101 << 1	1010	 10
>>	right shift	5 >> 1	0101 >> 1	0010	  2
>>>	unsigned right shift	5 >>> 1	0101 >>> 1	0010	  2
```

#### Conditional (ternary) operator
```
Syntx :
condition ? exprIfTrue : exprIfFalse
```

#### Type Operators
```
typeof	    Returns the type of a variable
instanceof	Returns true if an object is an instance of an object type
```