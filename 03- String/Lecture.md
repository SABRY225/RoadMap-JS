# JavaScript String

### Escape Character
```
\'	'	Single quote
\"	"	Double quote
\\	\	Backslash

\b	Backspace
\f	Form Feed
\n	New Line
\r	Carriage Return
\t	Horizontal Tabulator
\v	Vertical Tabulator
```

### Strings as Objects
```
let y = new String("John");

```
### String Methods

```
1- String length:
The `length` property of a string returns the number of characters in the string.

2- String slice(startIndex, endIndex): 
The `slice()` method extracts a portion of a string and returns a new string. It takes two parameters: the starting index (inclusive) and the ending index (exclusive) of the desired slice.

3- String substring(startIndex, endIndex): 
The `substring()` method is similar to `slice()` but it doesn't accept negative indices. 
It extracts a portion of a string and returns a new string. It takes two parameters: the starting index (inclusive) and the ending index (exclusive) of the desired substring.

4- String substr(startIndex, length): 
The `substr()` method extracts a specified number of characters from a string, starting at a specified index, and returns a new string. It takes two parameters: the starting index (inclusive) and the length of the substring.

5- String replace(oldValue, newValue): 
The `replace()` method searches for a specified value in a string and replaces it with a new value. It takes two parameters: the old value to be replaced and the new value.

6- String replaceAll(regexp, newValue): 
The `replaceAll()` method replaces all occurrences of a specified pattern (regular expression) in a string with a new value. It takes two parameters: the regular expression pattern and the new value.

7- String toUpperCase(): 
The `toUpperCase()` method converts all the characters in a string to uppercase and returns a new string.

8- String toLowerCase(): 
The `toLowerCase()` method converts all the characters in a string to lowercase and returns a new string.

9- String concat(string2): 
The `concat()` method concatenates two or more strings and returns a new concatenated string. It takes one or more strings as parameters.

10- String trim(): 
The `trim()` method removes whitespace from both ends of a string and returns a new string.

11- String trimStart(): 
The `trimStart()` method removes whitespace from the beginning of a string and returns a new string.

12- String trimEnd(): 
The `trimEnd()` method removes whitespace from the end of a string and returns a new string.

13- String padStart(targetLength, padString): 
The `padStart()` method pads the current string with another string until it reaches the specified target length. It takes two parameters: the target length and the string to pad with.

14- String padEnd(targetLength, padString): 
The `padEnd()` method pads the current string with another string until it reaches the specified target length. It takes two parameters: the target length and the string to pad with.

15- String charAt(index): 
The `charAt()` method returns the character at the specified index in a string.

16- String charCodeAt(index): 
The `charCodeAt()` method returns the Unicode value of the character at the specified index in a string.

17- String split(separator): 
The `split()` method divides a string into an array of substrings based on a specified separator and returns the new array. It takes one parameter: the separator string or regular expression pattern to split the string.

```
### Search Methods
```
1- String indexOf(searchValue, startIndex): 
The indexOf() method returns the index of the first occurrence of a specified search value within a string, starting from the specified startIndex. If the search value is not found, it returns -1.

2- String lastIndexOf(searchValue, startIndex): 
The lastIndexOf() method returns the index of the last occurrence of a specified search value within a string, searching backward from the specified startIndex. If the search value is not found, it returns -1.

3- String search(regexp): 
The search() method searches a string for a specified pattern (regular expression) and returns the index of the first match. If no match is found, it returns -1.

4- String match(regexp): 
The match() method retrieves the matches when matching a string against a specified pattern (regular expression). It returns an array containing the matches or null if no match is found.

5- String matchAll(regexp): 
The matchAll() method returns an iterator of all the matches of a string against a specified pattern (regular expression). It returns a MatchAllArray object.

6- String includes(searchValue, startIndex): 
The includes() method determines whether a string contains a specified substring. It returns true if the string contains the substring, and false otherwise. The startIndex parameter is optional and specifies the position within the string to start the search.

7- String startsWith(searchValue, startIndex): 
The startsWith() method determines whether a string starts with a specified substring. It returns true if the string starts with the substring, and false otherwise. The startIndex parameter is optional and specifies the position within the string to start the search.

8- String endsWith(searchValue, endIndex): 
The endsWith() method determines whether a string ends with a specified substring. It returns true if the string ends with the substring, and false otherwise. The endIndex parameter is optional and specifies the position within the string to end the search.
```
### Template literals

Here's an example demonstrating the usage of template literals:

```
const name = 'John';
const age = 30;

// Using template literals
const message = `My name is ${name} and I'm ${age} years old.`;

console.log(message);
// Output: My name is John and I'm 30 years old.

```
Template literals also support multi-line strings without the need for escape characters. You can simply write the string across multiple lines:

```
const multiLine = `
  This is a 
  multi-line
  string.
`;

console.log(multiLine);
/*
Output:
  This is a
  multi-line
  string.
*/
```