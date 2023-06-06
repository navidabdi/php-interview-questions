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

1. Integers: Integers are whole numbers, without a decimal point, like 4195.
2. Doubles: Doubles are floating-point numbers, like 3.14159 or 49.1.
3. Booleans: Booleans have only two possible values either true or false.
4. NULL: NULL is a special type that only has one value: NULL.
5. Strings: Strings are sequences of characters, like 'PHP supports string operations.'
6. Arrays: Arrays are named and indexed collections of other values.
7. Objects: Objects are instances of programmer-defined classes, which can package up both other kinds of values and functions that are specific to the class.
8. Resources: Resources are special variables that hold references to resources external to PHP (such as database connections).

### 10. What are the variable-name rules in PHP?

The rules for naming variables in PHP are:

1. A variable name must start with a letter or the underscore character.
2. A variable name cannot start with a number.
3. A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and \_ ).
4. Variable names are case-sensitive ($age and $AGE are two different variables).
5. Variable names should be short yet descriptive.
6. PHP variable names are not typed, that is, they do not need to be declared with any particular type, and can even change type after they have been set.
