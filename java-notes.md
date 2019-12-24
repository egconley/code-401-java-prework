[learnjavaonline.org](https://www.learnjavaonline.org/en/Welcome)

> Java is an object oriented language (OOP). 
Java objects are part of so-called "Java classes".

> In Java, every line of code that can actually run needs to be inside a class. 

`public` - *any other class can access it*

> when we declare a public class, we must declare it inside a file with the same name (Main.java for `public class Main {`), 
otherwise we'll get an error when compiling.

`public static void main(String[] args) {` 
 > This is the entry point of our Java program. 
 The main method has to have this exact signature in order to be able to run our program.
 - `public` - any other class can access it
 - `static` - means you can run this method without creating an instance of `Main`
 - `void` - means that this method doesn't return any value
 - `main` is the name of the method
 
 `System.out.println("This will be printed");`
 - `System` - a pre-defined class that Java provides us and it holds some useful methods and variables
 - `out` - static variable within System that represents the output of your program (stdout)
 - `println` - method of out that can be used to print a line
 
 
 
