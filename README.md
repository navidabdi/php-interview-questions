# PHP Interview Questions

This is a list of PHP interview questions and answers for PHP developers. I have tried to cover all possible interview questions from PHP. If you have any questions or suggestions, please feel free to create an issue or pull request.

## Beginner Level

### 1. What is PHP?

PHP is a server-side scripting language that is used to develop Static websites or Dynamic websites or Web applications. PHP stands for Hypertext Pre-processor, that earlier stood for Personal Home Pages. PHP scripts can only be interpreted on a server that has PHP installed.

### 2. What is the difference between static and dynamic websites?

Static Websites: Static websites can be described as simple websites. The content can be the same for all users. Static websites are written in HTML and CSS. They do not require any web programming or database design. They are easy to develop and host.

Dynamic Websites: Dynamic websites can be described as complex websites. The content can vary for different users. Dynamic websites are written in languages such as CGI, AJAX, ASP, ASP.NET, etc. They are comparatively difficult to develop and host.

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
