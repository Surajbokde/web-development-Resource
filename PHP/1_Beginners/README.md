# PHP Resources

# PHP Introduction

### What is PHP ?
---------------------------------------
PHP is an acronym for "PHP: Hypertext Preprocessor". It is a widely-used, open source scripting language.

<div align="center">
	<code><img height="250" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/php/php.png"></code>
</div>
<div align="start">
	
## Contents

- [Tutorials](#beginer-tutorials)<br/> 

- [ Youtubetutorials](#beginer-tutorials)<br/> 

- [Top  Online Courses](#beginer-tutorials)<br/> 

- [Books](#beginer-tutorials)<br/> 



## Comments in PHP
- `Single line comment` : // or #
- `Multiple line comment` : /* .... */


## General Structure

`<?php`
    <br> 
       &nbsp;&nbsp;&nbsp;&nbsp; ***//.....Code here.....***
    <br>
`?>`

## Variable Declaration

In php a variable name is started with `$` sign  as follows:<br>
`<?php` <br>
&nbsp;&nbsp;`$name = "Welcome to PHP";`<br>
&nbsp;&nbsp;`$num = 77.5;`<br>
`?>`

`Rules for naming convention`: ***Reference: [Click here for further info](https://www.roseindia.net/tutorial/php/phpbeginners/PHPvariable.html)***

## Printing statement in PHP

In php there are two methods to do so : <br>
`1) Echo statement` : <br>
&nbsp;&nbsp; Eg: <br>
&nbsp;&nbsp;&nbsp;&nbsp;`<?php`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `echo "Hello Learner"`    
&nbsp;&nbsp;&nbsp;&nbsp;`?>`<br>
`2) Print statement` : <br>
&nbsp;&nbsp; Eg: <br>
&nbsp;&nbsp;&nbsp;&nbsp;`<?php`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `print "Hello Learner"`    
&nbsp;&nbsp;&nbsp;&nbsp;`?>`
<br><br>
Common Example :

&nbsp;&nbsp; `<?php`<br>
&nbsp;&nbsp;&nbsp;&nbsp; `$name = "Joe";`<br>
&nbsp;&nbsp;&nbsp;&nbsp; `$title = "Denly";`<br>
&nbsp;&nbsp;&nbsp;&nbsp; `$age = 5;`<br>
&nbsp;&nbsp;&nbsp;&nbsp; `print "<h2>My name is " . $name . " " .$title. "</h2>";`<br>
&nbsp;&nbsp;&nbsp;&nbsp; `echo "My age is  " . $age . "<br>";`<br>
&nbsp;&nbsp; `?>`<br>

## Data Types in PHP
-PHP supports the following data types:
&nbsp;&nbsp;- String <br>
&nbsp;&nbsp;- Integer <br>
&nbsp;&nbsp;- Float/Double <br>
&nbsp;&nbsp;- Boolean <br>
&nbsp;&nbsp;- Array <br>
&nbsp;&nbsp;- Object <br>
&nbsp;&nbsp;- NULL <br>
&nbsp;&nbsp;- Resource <br>
&nbsp;&nbsp;- callable <br>
&nbsp;&nbsp;- iterable <br>

`The types of the data types are detailed here`: ***Reference: [Click here for further info](https://www.php.net/manual/en/language.types.intro.php)***

## Popular mathematical functions
There are many popular mathematical functions used such as pi(), max(), min(),abs() and so on.
`The functions are elaborated here `: ***Reference: [Click here for further info](https://www.php.net/manual/en/ref.math.php)***

## Popular mathematical functions

Operators are used to perform operations on variables and values.<br>
PHP divides the operators in the following groups:
&nbsp;&nbsp;- Operator Precedence <br>
&nbsp;&nbsp;- Arithmetic Operators <br>
&nbsp;&nbsp;- Assignment Operators <br>
&nbsp;&nbsp;- Bitwise Operators <br>
&nbsp;&nbsp;- Comparison Operators <br>
&nbsp;&nbsp;- Error Control Operators <br>
&nbsp;&nbsp;- Execution Operators <br>
&nbsp;&nbsp;- Incrementing/Decrementing Operators <br>
&nbsp;&nbsp;- Logical Operators <br>
&nbsp;&nbsp;- String Operators <br>
&nbsp;&nbsp;- Array Operators <br>
&nbsp;&nbsp;- Type Operators <br>
`The Operators `: ***Reference: [Click here for further info](https://www.php.net/manual/en/language.operators.php)***

## PHP Conditional Statements
 As normal languages php also uses two types of conditional statements:
 - `if_ _elseif_ _else`
 - `switch`
 
#### if _ elseif _ else
##### Syntax for normal `if` statement :
if (condition) { <br>
 &nbsp;&nbsp; &nbsp;&nbsp;  // code here <br>
} <br>

##### Syntax for normal `if _ else` statement :
if (condition) { <br>
  &nbsp;&nbsp; &nbsp;&nbsp;  // code here if condition is true; <br>
} else { <br>
  &nbsp;&nbsp; &nbsp;&nbsp;  // code here if condition is false; <br>
} <br>

##### Syntax for normal `if _ elseif _ else` statement :
if (condition) { <br>
  &nbsp;&nbsp; &nbsp;&nbsp;  // code here if condition is true; <br>
}  elseif (condition) { <br>
  &nbsp;&nbsp; &nbsp;&nbsp;  // code here if first condition is false and this condition is true; <br>
} else { <br>
  &nbsp;&nbsp; &nbsp;&nbsp;  // code here if condition is false; <br>
} <br>

`Examples `: ***[Example of if else](https://www.w3schools.com/php/php_if_else.asp)***

#### switch
switch (num) { <br>
  &nbsp;&nbsp; case label1: <br>
   &nbsp;&nbsp;&nbsp;&nbsp; //code to be executed if num = label1; <br>
   &nbsp;&nbsp;&nbsp;&nbsp; break; <br>
 &nbsp;&nbsp; case label2: <br>
   &nbsp;&nbsp;&nbsp;&nbsp; //code to be executed if num = label2; <br>
   &nbsp;&nbsp;&nbsp;&nbsp; break; <br>
 &nbsp;&nbsp; case label3: <br>
   &nbsp;&nbsp;&nbsp;&nbsp; //code to be executed if num = label3; <br>
   &nbsp;&nbsp;&nbsp;&nbsp; break; <br>
  &nbsp;&nbsp;  ... <br>
 &nbsp;&nbsp; default: <br>
   &nbsp;&nbsp;&nbsp;&nbsp; //code to be executed if num is different from all labels; <br>
} <br>

## PHP Loops
There are 4 types of loop used in php namely :
- `for`
- `while`
- `do while`
- `for each`

Each one is clearly explained in the given links.
-`1`: ***[for loop](https://www.php.net/manual/en/control-structures.for.php)*** <br>
-`2`: ***[while loop](https://www.php.net/manual/en/control-structures.while.php)*** <br>
-`3`: ***[do while loop](https://www.php.net/manual/en/control-structures.do.while.php)*** <br>
-`4`: ***[for each loop](https://www.php.net/manual/en/control-structures.foreach.php)*** <br>


## Extra References :
`PHP`: ***[Official Website](https://www.php.net/)*** <br>
`W3Schools` :  ***[W3Schools](https://www.w3schools.com/php/default.asp)*** <br>
`javatpoint` : ***[javatpoint](https://www.javatpoint.com/php-tutorial)*** <br>
`tutorialspoint` : ***[tutorialspoint](https://www.tutorialspoint.com/php/index.htm)*** <br>
`geeksforgeeks` : ***[geeksforgeeks](https://www.geeksforgeeks.org/php/)*** <br>

## Youtubetutorials
-  ***[freecodecamp](https://www.youtube.com/watch?v=OK_JCtrrv-c)*** 
-  ***[CodeWithHarry](https://www.youtube.com/playlist?list=PLu0W_9lII9aikXkRE0WxDt1vozo3hnmtR)***
-  ***[ProgrammingKnowledge](https://www.youtube.com/playlist?list=PLS1QulWo1RIZc4GM_E04HCPEd_xpcaQgg)***
- ***[TheNetNinja](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gksOX3Kd9KPo-O68ncT05o)***
- ***[Geeky Shows](https://www.youtube.com/playlist?list=PLbGui_ZYuhigFdLdbSI2EM2MrJB7I0j-B)***

#### Popular Book
-`Learning PHP, MySQL, JavaScript, CSS & HTML5: A Step-by-Step Guide to Creating Dynamic Websites` <br>
-`Head First PHP & MySQL` <br>
-`Modern PHP: New Features and Good Practices` <br>

## Projects
-  ***[Project1](https://www.youtube.com/watch?v=1SnPKhCdlsU&t=7104s)***
-  ***[Project2](https://www.youtube.com/playlist?list=PLxefhmF0pcPkatGBnqCSa7ZrU4axKrm6p)***

## 5 PHP Top projects ideas
- ***[5 PHP Top projects ideas](https://www.youtube.com/watch?v=wMVARHHPIz4)***
