# OOP in PHP
---------------------------------------

PHP is a server-side scripting language, mainly used for web development but also used as a general-purpose programming language. Object-Oriented Programming (PHP OOP), is a type of programming language principle added to php5, that helps in building complex, reusable web applications.

## Concepts used
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-`Class`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-`Object`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-`Inheritance`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-`Polymorphism`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-`Overloading`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-`Data Abstraction`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-`Constructor`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-`Destructor`<br>
&nbsp;Object-oriented programming has several advantages over procedural programming:<br> 

&nbsp;&nbsp;-OOP is faster and easier to execute<br>
&nbsp;&nbsp;-OOP provides a clear structure for the programs<br>
&nbsp;&nbsp;-OOP helps to keep the PHP code DRY "Don't Repeat Yourself", and makes the code easier to maintain, modify and debug<br>
&nbsp;&nbsp;-OOP makes it possible to create full reusable applications with less code and shorter development time<br>

## Class and Objects
`Objects have states and behaviors`. <br>
Example: A dog has states - color, name, breed as well as behaviors – wagging the tail, barking, eating. An object is an instance of a class.<br>

`A class can be defined as a template/blueprint that describes the behavior/state that the object of its type support.`<br>

Example code :<br>
&nbsp;&nbsp;`<?php`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`class Person{`<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`public function name(){`<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`echo "John";`<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`}`<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`public function age(){`<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`echo "20";`<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`}`<br>
`}`<br>
//To create php object we have to use a  new operator. Here php object is the object of the Person Class.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`$obj = new Person();`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`$obj->name();`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`$obj->age();`<br>
`?>`

## PHP OOP - Constructor and Destructor
`Rules and Example`:- ***[Constructor Destructor](https://www.php.net/manual/en/language.oop5.decon.php)***

## PHP OOP - Inheritance
Inheritance allows us to write the code only once in the parent, and then use the code in both the parent and the child classes.

It is done using the keyword : `extends`.  `--->`&nbsp;&nbsp; [Inheritance](https://www.studytonight.com/php/php-inheritance)

## PHP OOP - Abstract Classes
An abstract class is a class that has at least one abstract method. Abstract methods can only have names and arguments, and no other code. Thus, we cannot create objects out of abstract classes. Instead, we need to create child classes that add the code into the bodies of the methods, and use these child classes to create objects.

It is done using the keyword : `abstract`.  `--->`&nbsp;&nbsp; [Abstract](https://www.php.net/manual/en/language.oop5.abstract.php)

## PHP OOP - Static Methods
In certain cases, it is very handy to access methods and properties in terms of a class rather than an object. This can be done with the help of static keyword. Any method declared as static is accessible without the creation of an object. Static functions are associated with the class, not an instance of the class. 

[Static Methods](https://tutorials.supunkavinda.blog/php/oop-static-methods-properties)

## 	Polymorphism in PHP
Polymorphism is derived from two Greek words. Poly (meaning many) and morph (meaning forms). Polymorphism is one of the PHP Object Oriented Programming (OOP) features.  In general, polymorphism means the ability to have many forms. If we say it in other words, "Polymorphism describes a pattern in Object Oriented Programming in which a class has varying functionality while sharing a common interfaces.". 

[Polymorphism](https://www.tutorialspoint.com/explain-polymorphism-in-php)

## Overloading in PHP
Function overloading in PHP is used to dynamically create properties and methods. These dynamic entities are processed by magic methods which can be used in a class for various action types. Function overloading contains same function name and that function preforms different task according to number of arguments. For example, find the area of certain shapes where radius are given then it should return area of circle if height and width are given then it should give area of rectangle and others. Like other OOP languages function overloading can not be done by native approach. In PHP function overloading is done with the help of magic function __call(). This function takes function name and arguments.

[Overloading](https://www.geeksforgeeks.org/overloading-in-php/)

## Video Tutorials
-`Object Oriented PHP Tutorials`: ***[Dani Krossing](https://www.youtube.com/playlist?list=PL0eyrZgxdwhypQiZnYXM7z7-OTkcMgGPh)***

## Extra References :
`PHP`: ***[Official Website](https://www.php.net/)***<br>
`W3Schools` :  ***[W3Schools](https://www.w3schools.com/php/default.asp)***<br>

#### Popular Book
-`Object-Oriented PHP by Peter Lavin`<br>
-`PHP Objects, Patterns, and Practice, Second Edition by Matt Zandstra`<br>
-`Modern PHP: New Features and Good Practices`<br>