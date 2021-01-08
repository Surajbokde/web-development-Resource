# PHP Connectivity with MySQLi
---------------------------------------
Coonecting PHP with mysql is one of the required topics in php web development. For here let us use [`phpmyadmin`](https://www.phpmyadmin.net/) for the mysql interface. 
MySQL works very well in combination of various programming languages like PERL, C, C++, JAVA and PHP. Out of these languages, PHP is the most popular one because of its web application development capabilities.

## PHP mysqli connect() Function
The connect() / mysqli_connect() function opens a new connection to the MySQL server.
Example :<br>
`<?php`<br>
`$con = mysqli_connect("localhost","root","password_here","database_name_here");`<br>
`// Check connection`<br>
`if (mysqli_connect_errno()) {`<br>
  `echo "Failed to connect to MySQL: " . mysqli_connect_error();`<br>
 ` exit();`
`}`<br>
`?>`<br>

---------------------------> [`mysqli_connect`](https://www.php.net/manual/en/function.mysqli-connect.php)

## Video Tutorials
-`PHP MySQLi Connect to Database`: ***[Helpfolder](https://www.youtube.com/watch?v=oBxlfSDF7A4)***<br>
-`PHP Tutorials in Hindi`: ***[CodeWithHarry](https://www.youtube.com/playlist?list=PLu0W_9lII9aikXkRE0WxDt1vozo3hnmtR)***<br>
-`CRUD Operation in PHP MySQLi In Hindi | Select Insert Update Delete in PHP MySQLi`: ***[Thapa Technical](https://www.youtube.com/watch?v=y5mBHPtEO5w)<br>***

## Extra References :
`PHP`: ***[Official Website](https://www.php.net/)***<br>
`W3Schools` :  ***[W3Schools](https://www.w3schools.com/php/default.asp)***<br>
<br>