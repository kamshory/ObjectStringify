# ObjectStringify

Sometimes the programmer wants to display the value of the properties of an object stored into a string either for debugging, logging, or serializing it into a database, file or sent to another application. In the JavaScript and PHP programming languages, this is very easy to do, but not for Java. In the Java programming language, programmers need to make it manually.
Actually in Java, there is already a toString method that can transform objects into strings. But the output of this method may not be expected.

Here is a method to override the toString method that can store the value of all properties of the object into a string.
