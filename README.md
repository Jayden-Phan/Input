## Input
There are many different ways to get user input. We are going to use `Scanner` class. In order to get to use the class to get input, we must


1. `import java.util.Scanner;`
2. Create a Scanner Object
3. Output prompt to guide user


`Scanner user = new Scanner(System.in);`


### Input Types 
1. `nextInt()` reads integer value form user 
2. `nextFloat()` or `nextDouble()` reads a decimal vlaue from user 
3. `nextBoolean()` reads boolean value from user
4. `nextLine()` reads a String value 


## String 
A collection of characters. String are immutable, which means they cannot be changed.

Ex: `My name is Mr. Nick`

Ex: `I have 4 dogs`


## Constructing String Objects


We can create string objects similar to primitive data types.

`String name="Nick";`


### Concatentation of Strings

String can be added together using an operator called concatenetaion 



Example:

`String firstName = "Matt";`

`String lastName = "Jones";`

`String fullname = firstName + lastName;`


Example:

`String id = 5;`


### Comparing Strings 


In Java, you can compare strings using two different methods.

- `equals()` method
- `compareTo()` method

**For the equals() method**


`string1.equals(string2); `, this returns a boolean value, either true if the two strings are equal, or false otherwise.


Example:

`String dog = "Dog"`
`String cat = "Cat"`
 `System.out.print(dog.equals(cat));` result = false


 ## For the compareTo() method:

 `string1.compareTo(string2);`


 This method return:
- Return 0 if the 2 string are equal
- Returns a greater value than zero if the first string precedes the second string in the dictionary
- Returns value less than 0 if the second string precedes the first string in the dictionary.

** Method: substring()**

The substring() method has 2 different forms:
- string1.substring(5)
 - The first for takes a single integer input returns the characters of the string from the index of the input to the end



 Example:

 `String dinasour = "Triceratops";`

 `String half = dinasour.substring(5);`
 

 -`string1.substring(Integer,num1, Integer num2);` 
 - The second form takes 2 integer inputs and returns the characters of the string form the index of the first input to the character before the index of the second input.

 Example:

 `String dinasour = "Triceratops";`

 `String part = dinasour.substring(2, 6);`


 There are other string methods 

 String length:

 To find the length of a string, you can use the method length(). This method returns the length of the string as an integer.



 Example:

 `String name = "Nicholas";`

`int length = name.length();` returns the length of the string.


 









