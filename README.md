# dart-basics
Basics of Dart programming language for beginners.

## what is Dart and why do we use it ?
Dart is a programming language developed by Google. It is used to build web, mobile, and desktop applications, and can also be used for server-side development. Dart is designed to be easy to learn and use, with a syntax similar to that of other popular languages such as Java and JavaScript. It also includes features such as garbage collection, type inference, and a built-in package manager. Dart is used in the development of the Flutter framework for building cross-platform mobile apps.

## requirements
- Install Dart Sdk from [here](https://dart.dev/get-dart/archive).
- Install VS Code from [here](https://code.visualstudio.com/download).
- Install `Dart` and `Dart (Syntax Highlighting Only)` extensions in VS Code.

## setup steps
- Checkout [this](https://github.com/rahulrajpandey/dart-basics.git) repository. 
```
git clone https://github.com/rahulrajpandey/dart-basics.git
```

## running code
- Open the cloned repository folder in VS Code in your local machine.
- Test with HelloWorld program first:
  - Open Terminal in VS Code.
  - Type: ``` dart TheHelloWorldDart.dart ``` and hit Enter.
  - If it gives the following result, you are done with the setup.
  ![Output](./TheHelloWorldDartOutputImg.png)
  - Now, try running rest of the code files one by one to learn Dart basics and essentials.

## learning the concepts
- Open the folders and files in their order of numbering.
- Each file contains the topic, its concepts and examples.
  - Read the concept section first.
  - Then glance over the given examples for better understanding.
  - Run the file and check the output.
- Once you understood the topic, create a new file for your practice with the name of the topic.
  - Try writing few more examples or re-write the example from repository file, and then try to run.
  - It will solidify your understanding on the topic.

Connect with me on [LinkedIn](https://www.linkedin.com/in/rahulrajpandey/) [Twitter](https://twitter.com/rrprahulraj).

Happy Dart Learning :smiling_face_with_three_hearts:

Thanks :handshake:

---

## Comments in Dart Programming Language

An example of comments in Dart programming language can be found in TheHelloWorldDart.dart code file.

So, What is comment in Dart and what are its significance ?  
A comment is a piece of text in a program file that is ignored by the compiler/interpreter 
and does not affect the execution of the code. 
Its purpose is to provide explanations and documentation for the code to make it 
easier for others to understand and maintain.

Significance:
1. Improves readability of code
2. Provides context and explanation
3. Helps in debugging and maintenance
4. Facilitates team collaboration
5. Improves code documentation.

In Dart, there are two types of comments:

1. Single-line comments: start with two forward slashes (//) and continue until the end of the line.
Example: 
```
void main() {
  // Its a single line comment.
  int i = 42;
  print("Value: $i"); // Value: 42
  // Single line comments are the preferred way of commenting in Dart.
}
```

2. Multi-line comments: start with /* and end with */. Everything between the symbols is ignored.
Example:
```
void main() {
  /*
    Its a multi-line comment as 
    It goes over multiple lines.
  */
  int i = 42;
  print("Value: $i"); // Value: 42
}
```

---

## Dart Programming Language Frequently Asked Questions with detailed Answer:

**Q1.** What is Dart, and what is it used for ?  
**Ans:** Dart is a programming language developed by Google. 
It is used to build web, mobile, and desktop applications and can also be used for server-side development. 
Dart is designed to be easy to learn and use with a syntax similar to that of other popular languages such as Java and JavaScript. 
It also includes features such as garbage collection, type inference, and a built-in package manager. 
Dart is used in the development of the Flutter framework for building cross-platform mobile apps.

**Q2.** What is the extension of Dart program files ?  
**Ans:** .dart is used as the file extension for Dart code files.

**Q3.** Is Dart an interpreted language ?  
**Ans:** No, Dart is not an interpreted language. Dart is a statically-typed, object-oriented programming language developed by Google. Dart code is compiled to JavaScript, which can then be executed by a browser or run on a server using Node.js. This means that Dart code is transformed into machine code that can be executed directly, making it faster than interpreted languages.

**Q4.** What are the features on Dart programming language ?  
**Ans:** Following are the features of Dart programming: 
1. Strong typing: Dart supports type annotations, which help catch type-related errors at compile-time.
2. Object-oriented: Dart supports classes, objects, inheritance, and other OOP features.
3. Easy to learn: Dart has a syntax that is familiar to developers who have experience with Java, JavaScript, or C-style languages.
4. Fast and Scalable: Dart provides fast and scalable apps, especially for large-scale projects.
5. Interoperable with JavaScript: Dart code can be easily translated into JavaScript, making it possible to use Dart on the web and in existing JavaScript environments.
6. Built-in support for asynchronous programming: Dart has built-in support for asynchronous programming, making it easy to build responsive and scalable apps.
7. Concise and Expressive Syntax: Dart's syntax is concise and expressive, making it easier to write and understand code.
8. Suitable for both client- and server-side development: Dart can be used for both client- and server-side development, making it a versatile choice for building full-stack web applications.
9. Rich Standard Library: Dart comes with a rich standard library that includes common data structures, utilities, and APIs.
10. Cross-platform development: Dart can be used to develop applications for multiple platforms, including web, mobile, desktop, and more.

**Q5.** What are the data types available in Dart programming language ?  
**Ans:** Dart has the following built-in data types:
1. num: A numeric type that can represent both integers (int) and floating-point numbers (double).
2. int: An integer type that can represent a whole number.
3. double: A floating-point type that can represent a real number with a fractional part.
4. String: A sequence of Unicode characters.
5. bool: A type that can only represent the values true or false.
6. List: An ordered collection of elements of any type.
7. Map: A collection of key-value pairs where the keys are unique.
8. Dynamic: A type that can hold values of any type.
9. Function: A type that represents a function or method.
10. Object: The base type of all objects in Dart.

**Q6.** Is Dart a fully object-oriented language ?  
**Ans:** Yes, that's correct. Everything in Dart is an object, including numbers, strings, functions, and even null. In Dart, even basic data types such as numbers and strings are instances of classes, which means that they can be manipulated like any other object. 
This makes Dart a fully object-oriented language, where everything is treated as an object, making it easier to write and understand code.

**Q7.** What is type-checking in Dart? What is the difference between compile-time type checking and runtime type checking in Dart?   
**Ans:** 
Type checking in Dart is the process of testing and enforcing the constraints of types at either compile-time (i.e. statically) or runtime (i.e. dynamically).

Compile-time type checking in Dart refers to the process of checking the type of an expression or variable before the code is executed. This is done by the Dart compiler to ensure that the code is valid and to catch type-related errors before the code is run.

Dart supports type annotations, which allow developers to specify the expected type of a variable or function parameter. The Dart compiler uses these annotations to perform compile-time type checking and to ensure that the code is type-safe.

For example, if a variable is declared as "int" and an attempt is made to assign a string value to it, the Dart compiler will generate an error:

```
int i = "String"; // Compile-time error: 
// A value of type 'String' can't be assigned to a variable of type 'int'.
```

Compile-time type checking is an important feature of Dart, as it helps catch type-related errors early in the development process, making it easier to write and maintain code. This can result in faster development times and fewer bugs, making Dart a great choice for building large-scale, complex applications.

Runtime type checking in Dart refers to the process of checking the type of an object during the execution of the program. Unlike compile-time type checking, which is performed by the Dart compiler, runtime type checking is done at runtime by the program itself.

The Dart runtime provides a number of methods and operators that can be used to check the type of an object at runtime. 
For example, the "is" operator can be used to check if an object is of a specific type:
```
void main() {
  int i = 42;
  if (i is int) {
    print("its an int"); // its an int
  }
}
```

Similarly, the "as" operator can be used to cast an object to a specific type:

```
void main() {
  var x = 42;
  var y = x as String; // throws a CastError if the cast is invalid
  // type 'int' is not a subtype of type 'String' in type cast
}
```

Runtime type checking is an important feature of Dart, as it allows developers to write code that can adapt to changing conditions and handle different types of data at runtime. By checking the types of objects at runtime, developers can write code that is more flexible and robust, making it easier to write and maintain code.

**Q8.** What are the benefits of using Dart over JavaScript?  
**Ans:** Some of the benefits of using Dart over JavaScript include:  
- Better performance and faster load times.
- Strong type checking, making it easier to catch bugs and prevent errors.
- A rich set of libraries and tools, making it easier to build complex applications.
- Interoperability with JavaScript, allowing you to use existing JavaScript code in your Dart applications.

**Q9.** What are typedefs in Dart and how are they used?  
**Ans:** A typedef in Dart is a type alias that gives a new name to an existing type. It allows you to define a new type based on a pre-existing type, such as a function type.

A typedef is declared using the typedef keyword, followed by a new name for the type, and a function signature enclosed in parentheses. For example:

```
typedef IntToString = String Function(int);
```

The above typedef creates a new type named IntToString that represents a function that takes an int parameter and returns a String result.

Typedefs are particularly useful when dealing with complex function types, as they allow you to give a clear and descriptive name to the type. For example, instead of using a complex function type in a function signature, you can use a typedef instead:

```
void processData(IntToString conversionFunction) {
  // data processing logic
}
```

In this example, the processData function takes a parameter of type IntToString, which makes the function signature much easier to understand.

Typedefs can also be used to define a new type based on a class or a mixin, making it possible to create reusable, composable types that can be used throughout your code.

