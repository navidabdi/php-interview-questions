# PHP Interview Questions and Answers

This is a list of PHP interview questions and answers for PHP developers. I have tried to cover all possible interview questions from PHP. If you have any questions or suggestions, please feel free to create an issue or pull request.

### 1. What is PHP?

PHP is a server-side scripting language that is used to develop Static websites or Dynamic websites or Web applications. PHP stands for Hypertext Pre-processor, that earlier stood for Personal Home Pages. PHP scripts can only be interpreted on a server that has PHP installed.

### 2. What is the difference between static and dynamic websites?

**Static Websites**: The content of static websites cannot be changed dynamically. Each page is coded in HTML and displays the same information to every visitor. Static websites are written in languages such as HTML, CSS, JavaScript, etc. They are easy to develop and host but difficult to maintain.

**Dynamic Websites**: The content of dynamic websites can be changed dynamically. Each page is generated based on the information stored in a database or external file. Dynamic websites are written in languages such as PHP, Python, Ruby, etc. They are difficult to develop and host but easy to maintain.

### 3. Is PHP a case sensitive language?

The answer to this is both Yes and No. PHP is a case sensitive language except for function names. Variables, constants, class names, and function arguments are case-sensitive. However, function names are not case-sensitive. But it is recommended to use the same case for function names as in the calling code.

### 4. What is the difference between echo and print?

Both `echo` and `print` are used to display output in PHP. The difference between `echo` and `print` is that `echo` has no return value while `print` has a return value of 1 so it can be used in expressions. `echo` can take multiple parameters while `print` can take one argument. `echo` is faster than `print`.

### 5. What is the meaning of PEAR in PHP?

PEAR stands for PHP Extension and Application Repository. It is a framework and distribution system for reusable PHP components. PEAR is a code repository containing all kinds of PHP code snippets and libraries. It also contains a command-line interface that can be used to automatically install "packages".

### 6. What is the difference between include and require?

Both `include` and `require` are used to include a file in PHP. The difference between `include` and `require` is that if the file is not found, `include` will only emit a warning while `require` will emit a fatal error. So require is recommended over include.

### 7. How is a PHP script executed?

A PHP script can be executed in three ways:

1. In a browser by typing the URL in the address bar.
2. From the command line. For example, `php script.php`.
3. Using an IDE such as Eclipse, NetBeans, etc.

### 8. What is the difference between GET and POST?

Both `GET` and `POST` are used to send data from the client to the server. The difference between `GET` and `POST` is that `GET` method sends data in the URL while `POST` method sends data in the HTTP request body. So `POST` method is more secure than `GET` method.

### 9. What are the types of variables present in PHP?

There are eight types of variables present in PHP:

1. **Integers**: Integers are whole numbers, without a decimal point, like 4195.
2. **Doubles**: Doubles are floating-point numbers, like 3.14159 or 49.1.
3. **Booleans**: Booleans have only two possible values either true or false.
4. **NULL**: NULL is a special type that only has one value: NULL.
5. **Strings**: Strings are sequences of characters, like 'PHP supports string operations.'
6. **Arrays**: Arrays are named and indexed collections of other values.
7. **Objects**: Objects are instances of programmer-defined classes, which can package up both other kinds of values and functions that are specific to the class.
8. **Resources**: Resources are special variables that hold references to resources external to PHP (such as database connections).

### 10. What are the variable-name rules in PHP?

The rules for naming variables in PHP are:

1. A variable name must start with a letter or the underscore character.
2. A variable name cannot start with a number.
3. A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and \_ ).
4. Variable names are case-sensitive ($age and $AGE are two different variables).
5. Variable names should be short yet descriptive.
6. PHP variable names are not typed, that is, they do not need to be declared with any particular type, and can even change type after they have been set.

### 11. What is `NULL` in PHP?

`NULL` is a special data type in PHP that can have only one value: NULL. A variable of data type NULL is a variable that has no value assigned to it. If a variable is created without a value, it is automatically assigned a value of NULL.

### 12. What is the difference between `==` and `===`?

`==` is used to compare two variables which **may or may not** have the same data type.

`===` is used to compare two variables which **must** have the same data type.

### 13. How a constant is defined in PHP?

A constant is a name or an identifier for a simple value. A constant name starts with a letter or underscore (no $ sign before the constant name). To define a constant, use the `define()` function. The syntax for defining a constant is:

```php
define(name, value, case-insensitive)
```

### 14. What is the usecase of `constant()` function in PHP?

The `constant()` function is used to get the value of a constant. It accepts one parameter which is the name of the constant. The syntax for `constant()` function is:

```php
constant(name)
```

### 15. What are the magic constants in PHP?

Magic constants are the predefined constants in PHP that change based on their use. They start with two underscores (**) followed by the name of the constant and end with two underscores. For example, `**LINE\_\_` is a magic constant that returns the current line number of the file.

Some of the magic constants in PHP are:

1. `__LINE__`: Returns the current line number of the file.
2. `__FILE__`: Returns the full path and filename of the file.
3. `__DIR__`: Returns the directory of the file.
4. `__FUNCTION__`: Returns the function name.
5. `__CLASS__`: Returns the class name.
6. `__TRAIT__`: Returns the trait name.
7. `__METHOD__`: Returns the class method name.
8. `__NAMESPACE__`: Returns the namespace name.

### 16. What is the difference between variables and constants in PHP?

Here are the differences between variables and constants in PHP:

1. Variables can be redefined but constants cannot be redefine.
2. The default scope of a variable is local but the default scope of a constant is global.
3. The $ sign is used to declare a variable but constants are declared with the `define()` function.

### 17. What does the phrase "PHP escape" mean?

"PHP escape" is a mechanism to prevent special characters from being interpreted as part of the PHP code. It is used to prevent SQL injection, XSS, and other types of attacks. The PHP escape character is the backslash (\). It can be used before a single quote, double quote, backslash, and NUL (the NULL byte).

### 18. What is the difference between PHP4 and PHP5?

The difference between PHP4 and PHP5 are (comparison table):

| PHP4                                                 | PHP5                                         |
| ---------------------------------------------------- | -------------------------------------------- |
| PHP4 does not support OOP.                           | PHP5 supports OOP.                           |
| PHP4 does not support exceptions.                    | PHP5 supports exceptions.                    |
| PHP4 does not support interfaces.                    | PHP5 supports interfaces.                    |
| PHP4 does not support visibility.                    | PHP5 supports visibility.                    |
| PHP4 does not support static methods and properties. | PHP5 supports static methods and properties. |
| PHP4 does not support overloading.                   | PHP5 supports overloading.                   |
| PHP4 does not support type hinting.                  | PHP5 supports type hinting.                  |
| PHP4 does not support constructors and destructors.  | PHP5 supports constructors and destructors.  |
| PHP4 does not support cloning.                       | PHP5 supports cloning.                       |
| PHP4 does not support call-time pass-by-reference.   | PHP5 supports call-time pass-by-reference.   |
| PHP4 does not support the SimpleXML extension.       | PHP5 supports the SimpleXML extension.       |
| PHP4 does not support the DOM extension.             | PHP5 supports the DOM extension.             |
| PHP4 does not support the SQLite extension.          | PHP5 supports the SQLite extension.          |
| PHP4 does not support the MySQLi extension.          | PHP5 supports the MySQLi extension.          |
| PHP4 does not support the SOAP extension.            | PHP5 supports the SOAP extension.            |

### 19. How are two objects compared in PHP?

Two objects are compared in PHP using the `==` operator. If two objects are compared using the `==` operator, PHP will compare their attributes. If two objects are compared using the `===` operator, PHP will compare their references.

### 20. What is the meaning of `break` and `continue` statements in PHP?

The `break` statement is used to exit from a loop. The `continue` statement is used to skip the current iteration of a loop and continue with the next iteration.

### 21. What are some of the popular PHP frameworks?

Some of the popular PHP frameworks are (with their official websites):

1. Laravel: https://laravel.com/
2. Symfony: https://symfony.com/
3. CodeIgniter: https://codeigniter.com/
4. CakePHP: https://cakephp.org/
5. Zend Framework: https://framework.zend.com/
6. Yii Framework: https://www.yiiframework.com/
7. Phalcon: https://phalconphp.com/
8. FuelPHP: https://fuelphp.com/
9. Slim: https://www.slimframework.com/
10. PHPixie: https://phpixie.com/

### 22. What is the usecase of the `final` class and the `final` method in PHP?

The `final` keyword is used to prevent inheritance. If a class is marked as `final`, it cannot be extended. If a method is marked as `final`, it cannot be overridden.

### 23. How does JavaScript interact with PHP?

JavaScript is a client-side language and PHP is a server-side language. JavaScript can send and receive data from PHP using AJAX. AJAX stands for Asynchronous JavaScript and XML. It is a set of web development techniques using many web technologies on the client-side to create asynchronous web applications. In other words, it is the use of the XMLHttpRequest object to communicate with servers.

### 24. Does PHP intract whit HTML?

Yes! HTML and PHP intraction is the core of waht makes PHP so popular. PHP can be used to generate HTML code dynamically. PHP can be used to create, read, write, delete, and close files on the server. PHP can be used to send and receive cookies. PHP can be used to add, delete, modify data in your database.

### 25. What is the difference between `print_r()` and `var_dump()`?

`print_r()` displays information about a variable in a way that's readable by humans. `var_dump()` displays structured information about one or more expressions that includes its type and value. `var_dump()` is used for debugging purposes while `print_r()` is used for displaying information about a variable.

### 26. What are the types of arrays supported by PHP?

There are three types of arrays supported by PHP:

1. **Indexed arrays**: Arrays with a numeric index.
2. **Associative arrays**: Arrays with named keys.
3. **Multidimensional arrays**: Arrays containing one or more arrays.

### 27. How does the `foreach()` loop work in PHP?

The `foreach()` loop works only on arrays and objects. It is used to loop through each key/value pair in an array. The syntax for `foreach()` loop is:

```php
foreach ($array as $key => $value) {
  // code to be executed;
}
```

### 28. What is the difference between `array()` and `[]`?

`array()` is a language construct while `[]` is a language construct as well as a function. `array()` can be used to create an array while `[]` can be used to create an array as well as access an array element.

### 29. What is the difference between `require()` and `require_once()` functions?

Both `require()` and `require_once()` functions are used to include a file in PHP. The difference between `require()` and `require_once()` is that `require()` will emit a fatal error if the file is not found while `require_once()` will not emit a fatal error if the file is not found.

### 30. What are the data types supported by PHP?

| Scalar  | Compound | Special  |
| ------- | -------- | -------- |
| string  | array    | resource |
| integer | object   | NULL     |
| float   |          |          |
| boolean |          |          |

### 31. How can a text be printed in PHP?

A text can be printed in PHP using the `echo` or `print` statement. The syntax for `echo` statement is:

```php
echo "Hello World!";
```

The syntax for `print` statement is:

```php
print "Hello World!";
```

### 32. How can a text be printed without using `echo` or `print`?

A text can be printed without using `echo` or `print` by using the `<?= ?>` shorthand. The `<?= ?>` shorthand is equivalent to `<?php echo ?>`.

### 33. Is it possible to set infinite execution time for PHP script?

Yes! It is possible to set infinite execution time for PHP script. The `set_time_limit()` function is used to set the maximum execution time for a PHP script. The syntax for `set_time_limit()` function is:

```php
set_time_limit(seconds)
```

### 34. What is the usecase of the `__autoload()` function in PHP?

The `__autoload()` function is used to automatically load classes. It accepts one parameter which is the name of the class. The syntax for `__autoload()` function is:

```php
__autoload(classname)
```

### 35. What is the usecase of the `__construct()` function in PHP?

The `__construct()` function is used to initialize an object. It is called automatically when an object is created.

### 36. What is the usecase of the `__destruct()` function in PHP?

The `__destruct()` function is used to destroy an object. It is called automatically when an object is destroyed.

### 37. What are the popular Content Management Systems (CMS) written in PHP?

Some of the popular Content Management Systems (CMS) written in PHP are:

1. WordPress: https://wordpress.org/
2. Joomla: https://www.joomla.org/
3. Drupal: https://www.drupal.org/
4. Magento: https://magento.com/
5. MediaWiki: https://www.mediawiki.org/
6. PrestaShop: https://www.prestashop.com/
7. OpenCart: https://www.opencart.com/
8. Moodle: https://moodle.org/
9. phpBB: https://www.phpbb.com/
10. Typo3: https://typo3.org/

### 38. What are the differnet types of comments in PHP?

There are three types of comments in PHP:

1. Single-line comments: Single-line comments start with `//` and end with a newline character.
2. Multi-line comments: Multi-line comments start with `/*` and end with `*/`.
3. Doc comments: Doc comments start with `/**` and end with `*/`. They are used to document the code.

### 39. Differentiate between an indexed array and an associative array with examples.

An indexed array is an array with a numeric index. The index starts from 0. The values are stored and accessed in linear fashion. An associative array is an array with named keys. The keys can be strings or numbers. The values are stored and accessed by using the keys.

```php
// Indexed array
$colors = array("Red", "Green", "Blue");

// Associative array
$colors = array("R" => "Red", "G" => "Green", "B" => "Blue");
```

### 40. What is the usecase of the `compact()` function in PHP?

The `compact()` function is used to create an array from variables and their values. It accepts one or more parameters which are the names of the variables. The syntax for `compact()` function is:

```php
compact(var1, var2, ...)
```

### 41. What is the difference between ASP.NET and PHP?

| ASP.NET                                     | PHP                                |
| ------------------------------------------- | ---------------------------------- |
| A programming framework                     | A Scripting language               |
| Developed by Microsoft                      | Developed by Rasmus Lerdorf        |
| Supports languages such as C#, VB.NET, etc. | Supports only PHP                  |
| Runs on Windows only                        | Runs on Windows, Linux, Unix, etc. |
| Proprietary                                 | Open-source                        |
| Compiled                                    | Interpreted                        |

### 42. What is a session in PHP?

A session is a way to store information (in variables) to be used across multiple pages. Unlike a cookie, the information is not stored on the user's computer. A session is started using the `session_start()` function. The syntax for `session_start()` function is:

```php
session_start()
```

### 43. What is a cookie in PHP?

A cookie is a small file that the server embeds on the user's computer. Each time the same computer requests a page with a browser, it will send the cookie too. With PHP, you can both create and retrieve cookie values. A cookie is created using the `setcookie()` function. The syntax for `setcookie()` function is:

```php
setcookie(name, value, expire, path, domain, secure, httponly)
```

### 44. What is the difference between `session` and `cookie` in PHP?

| Session                                                                                  | Cookie                                                                  |
| ---------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| A session is a way to store information (in variables) to be used across multiple pages. | A cookie is a small file that the server embeds on the user's computer. |
| The information is not stored on the user's computer.                                    | The information is stored on the user's computer.                       |
| A session is started using the `session_start()` function.                               | A cookie is created using the `setcookie()` function.                   |
| A session is deleted when the user closes the browser.                                   | A cookie is deleted based on the lifetime of the cookie.                |

### 45. Is typecasting supported in PHP?

Yes! Typecasting is supported in PHP. Typecasting is the process of converting one data type into another. There are two types of typecasting in PHP:

1. **Implicit typecasting**: Implicit typecasting is done automatically by PHP. For example, converting a string to an integer.
2. **Explicit typecasting**: Explicit typecasting is done manually by the programmer. For example, converting a string to an integer using the `intval()` function.

### 46. Can a form be submitted without using a submit button in PHP?

Yes! A form can be submitted without using a submit button in PHP. The `submit()` method is used to submit a form using JavaScript. The syntax for `submit()` method is:

```php
form.submit()
```

### 47. What is the usecase of the `htmlspecialchars()` function in PHP?

The `htmlspecialchars()` function is used to convert some predefined characters to HTML entities. It accepts one parameter which is the string to be converted. The syntax for `htmlspecialchars()` function is:

```php
htmlspecialchars(string)
```

### 48. Does PHP support variable length argument functions?

Yes! PHP supports variable length argument functions. This simply means that you can pass any number of arguments to a function. The syntax simply involves using three dots (...) before the parameter name. For example:

```php
function sum(...$numbers) {
  $sum = 0;
  foreach ($numbers as $n) {
    $sum += $n;
  }
  return $sum;
}

echo sum(1, 2, 3, 4, 5);

// Output: 15
```

### 49. What is the usecase of `session_start()` and `session_destroy()` functions in PHP?

The `session_start()` function is used to start a session. The `session_destroy()` function is used to destroy a session. The syntax for `session_start()` function is:

```php
session_start()
```

The syntax for `session_destroy()` function is:

```php
session_destroy()
```

### 50. What is the usecase of the `header()` function in PHP?

The `header()` function is used to send a raw HTTP header to a client. It accepts one parameter which is the header to be sent. The syntax for `header()` function is:

```php
header(header)
```

### 51. How can you open a file in PHP?

A file can be opened in PHP using the `fopen()` function. It accepts two parameters which are the name of the file and the mode in which to open the file. The syntax for `fopen()` function is:

```php
fopen(filename, mode)
```

### 52. What are the different types of errors in PHP?

There are four different types of errors in PHP:

1. **Parse error**: A parse error occurs when the PHP parser is unable to understand the code. For example, missing semicolon, missing parenthesis, etc.
2. **Fatal error**: A fatal error occurs when the PHP parser understands the code but is unable to execute it. For example, calling an undefined function, accessing a private method, etc.
3. **Warning error**: A warning error occurs when the PHP parser understands and executes the code but encounters a problem. For example, using a deprecated function, using an undefined variable, etc.
4. **Notice error**: A notice error occurs when the PHP parser understands and executes the code but encounters a problem. For example, using a variable that has not been initialized, using an undefined index, etc.

### 53. How can you get the IP address of the client in PHP?

The IP address of the client can be obtained using the `$_SERVER['REMOTE_ADDR']` variable.

### 54. What is the usecase of $message and $$message in PHP?

Both `$message` and `$$message` are variables in PHP. The difference between `$message` and `$$message` is that `$message` is a simple variable while `$$message` is a variable variable. A variable variable takes the value of a variable and treats that as the name of a variable.

Consider the following example:

```php
$message = "Hello World";
$$message = "Hello PHP";

echo $message; // Output: Hello World
echo $$message; // Output: Hello PHP
echo $Hello World; // Output: Hello PHP
```

### 55. Differentiate between GET and POST methods in PHP.

| GET Method                                                                     | POST Method                                                                                |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| GET method is used to send a small amount of data.                             | POST method is used to send a large amount of data.                                        |
| GET method is not secure because data sent is part of the URL.                 | POST method is secure because data sent is not part of the URL.                            |
| GET method is less robust because data sent is limited by the URL length.      | POST method is more robust because data sent is not limited by the URL length.             |
| GET method is less secure because data sent is visible to everyone in the URL. | POST method is more secure because data sent is not visible to everyone in the URL.        |
| GET method is not suitable for sending sensitive information.                  | POST method is suitable for sending sensitive information.                                 |
| The $\_GET variable is used to collect values in a form with method="get".     | The $\_POST variable is used to collect values in a form with method="post".               |
| QUERY_STRING is used to collect values in a form with method="get".            | The HTTP protocol and the headers are used to collect values in a form with method="post". |
| GET does not support binary data.                                              | POST supports binary data as well as ASCII data.                                           |
| The GET method can only send a maximum of 1024 bytes.                          | The POST method has no restriction on data size to be sent.                                |

### 56. What is the usecase of the `$_SERVER` variable in PHP?

The `$_SERVER` variable is a superglobal variable in PHP. It is used to collect information about the server, headers, paths, and script locations. The `$_SERVER` variable is an array containing information such as headers, paths, and script locations. The entries in this array are created by the web server. There is no guarantee that every web server will provide any of these.

### 57. What is the usecase of "lambda functions" in PHP?

A lambda function is an anonymous function. It is a function that is defined without a name. It is used to create a function that can be used without naming it. The lambda function is used to first store the data in a variable and then to pass it as an argument to another function or method.

consider the following example:

```php
$add = function($a, $b) {
  return $a + $b;
};

echo $add(1, 2); // Output: 3
```

### 58. What is the difference between compile-time and run-time exceptions in PHP?

- **Compile-time exceptions**: Compile-time exceptions are the exceptions that are thrown at compile-time. For example, syntax errors, parse errors, etc.
- **Run-time exceptions**: Run-time exceptions are the exceptions that are thrown at run-time. For example, division by zero, calling an undefined function, etc.

### 59. What is the meaning of type hinting in PHP?

Type hinting is a feature introduced in PHP 5. It is used to specify the data type of a parameter in a function declaration. This ensures that the function will be called with the correct data type for the parameter. If the function is called with an incorrect data type for the parameter, a fatal error will be thrown.

### 60. How is a URL connected to a PHP script?

- Any URL can be connected to PHP easily by making use of the library called cURL.
- The cURL library is used to connect to a URL and make requests to the server.
- This comes as a default library in PHP.
- The term `cURL` stands for client-side URL, allowing users to connect to a server and make requests in order to get the data they need.

### 61. What are the steps to create a new database using PHP and MySQL?

- The first step is to connect to the MySQL server by using the `mysql_connect()` function.
- The second step is to create a new database by using the `mysql_create_db()` function.
- The third step is to select the database by using the `mysql_select_db()` function.
- The fourth step is to create a table by using the `mysql_query()` function.

### 62. How does string concatenation work in PHP?

String concatenation is the process of joining two or more strings together. In PHP, string concatenation is done using the `.` operator. For example:

```php
echo "Hello" . " " . "World"; // Output: Hello World
```

### 63. How to check if defined variable is NULL in PHP?

The `isset()` function is used to check if a variable is set and is not NULL. The syntax for `isset()` function is:

```php
isset(variable)
```

### 64. Is multiple inheritance supported in PHP?

No! Multiple inheritance is not supported in PHP. Multiple inheritance is the process of deriving a class from more than one base class. PHP only supports single inheritance.

### 65. What is the use of `func_num_args()` function in PHP?

The `func_num_args()` function is used to get the number of arguments passed to a function.

### 66. Name some common applications of PHP.

Some common applications of PHP are:

1. System functions
2. Form handling
3. CRUD tasks (Create, Read, Update, Delete)
4. Accessing cookies variables and setting cookies
5. Data encryption

### 67. How to connect to a database using PHP?

A database can be connected using PHP by using the `mysqli_connect()` function. The syntax for `mysqli_connect()` function is:

```php
$servername = "localhost";
$username = "username";
$password = "password";

// Create connection
$conn = mysqli_connect($servername, $username, $password);

// Check connection
if (!$conn) {
  die("Connection failed: " . mysqli_connect_error());
}
echo "Connected successfully";
```

### 68. What does final class and final method mean in PHP?

Example of final class:

```php
final class BaseClass {
  public function test() {
    echo "BaseClass::test() called";
  }

  // Here it doesn't matter if you specify the function as final or not
  final public function moreTesting() {
    echo "BaseClass::moreTesting() called";
  }
}

class ChildClass extends BaseClass {
  public function moreTesting() {
    echo "ChildClass::moreTesting() called";
  }
}

// Results in Fatal error: Cannot override final method BaseClass::moreTesting()
```

Example of final method:

```php
class BaseClass {
  public function test() {
    echo "BaseClass::test() called";
  }

  final public function moreTesting() {
    echo "BaseClass::moreTesting() called";
  }
}

class ChildClass extends BaseClass {
  public function moreTesting() {
    echo "ChildClass::moreTesting() called";
  }
}

// Results in Fatal error: Cannot override final method BaseClass::moreTesting()
```

### 69. How does Exepction handling work in PHP?

Exception handling is used to change the normal flow of the code execution if a specified error (exceptional) condition occurs. This condition is called an exception. PHP has an exception model similar to that of other programming languages. An exception can be thrown, and caught ("catched") within PHP. Code may be surrounded in a try block, to facilitate the catching of potential exceptions. Each try must have at least one corresponding catch block. Multiple catch blocks can be used to catch different classes of exceptions. Normal execution (when no exception is thrown within the try block, or when a catch matching the thrown exception's class is not present) will continue after that last catch block defined in sequence. Exceptions can be thrown (or re-thrown) within a catch block.

Consider the following example:

```php
function inverse($x) {
  if (!$x) {
    throw new Exception('Division by zero.');
  }
  else return 1/$x;
}

try {
  echo inverse(5) . "\n";
  echo inverse(0) . "\n";
} catch (Exception $e) {
  echo 'Caught exception: ',  $e->getMessage(), "\n";
}

// Output:
// 0.2
// Caught exception: Division by zero.
```

### 70. How to call a function by reference in PHP?

A function can be called by reference in PHP by using the `&` operator. The syntax for calling a function by reference is:

```php
function add(&$num) {
  $num++;
}

$num = 1;
add($num);
echo $num; // Output: 2
```

### 71. Create a singleton class in PHP.

A singleton class is a class that can have only one instance. It is used to control the object creation by keeping a private constructor. The singleton class is used to create a single object that can be shared across multiple classes. The singleton class is used to create a single object that can be shared across multiple classes.

Consider the following example:

```php
class Singleton {
  private static $instance;

  private function __construct() {}

  public static function getInstance() {
    if (!self::$instance) {
      self::$instance = new self();
    }
    return self::$instance;
  }
}

$singleton = Singleton::getInstance();
```

### 72. How to encrypt a password using PHP?

A password can be encrypted using PHP by using the `password_hash()` function. The syntax for `password_hash()` function is:

```php
$password_string = "password$123";
$password_hash = password_hash($password_string, PASSWORD_DEFAULT);
```

### 73. What is the output of the following code?

```php
$a = '1';
$b = &$a;
$b = "2$b";
echo $a.", ".$b;

// The output of the above code is:
// 21, 21
```
