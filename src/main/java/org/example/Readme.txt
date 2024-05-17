Explanation:
Creating a List:

List<String> fruits = new ArrayList<>(); creates an ArrayList to store strings.
Adding Elements to the List:

fruits.add("Apple");, fruits.add("Banana");, fruits.add("Cherry"); add elements to the list.
forEach Loop:

fruits.forEach(fruit -> System.out.println(fruit)); iterates over each element in the list (fruits) and prints it using a lambda expression.
fruit -> System.out.println(fruit) is a lambda expression that specifies the action to be performed for each element. In this case, it prints each fruit.
Benefits of forEach Loop:
Concise Syntax: The forEach loop provides a more concise syntax compared to traditional loops, making the code cleaner and easier to read.

Lambda Expressions: It can be used with lambda expressions, allowing for more functional-style programming in Java.

Iterating Collections: It's specifically designed for iterating over collections, such as lists, sets, and maps.

Internal Iteration: The iteration process is handled internally by the Java runtime, which can lead to optimized performance in certain scenarios, especially when used with parallel streams.

The forEach loop is a handy tool for iterating over collections and performing operations on each element, contributing to the expressive and functional programming capabilities of Java.