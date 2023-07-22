# Array #

## What is Array ##

- Arrays in Python are Data Structures that can hold multiple values of the same type.
- Python does not have built-in support for Arrays, but Python Lists can be used instead.
- There is a key difference between array and list i.e. array store multiple values of same data type where as a list can store value of  different data types.

## Creating, Accessing and Modifying Arrays/Lists ##

- Elements are specified under '[]' bracket.
- Eg :-
  - Create an array containing car names:
    - cars = ["Ford", "Volvo", "BMW"]
  - Create empty list.
    - names =[]
- An array or list can hold many values under a single name, and you can access the values by referring to an index number.
- Eg :-
  - Accessing list element using index.
    - x = cars[0]
  - Modifying list element using index.
    - cars[0]="Ferrari"

<sub>Note: Indexing starts from 0 to n-1 for list/array of 'n' length.</sub>

## Array Methods ##

![array methods](https://img.brainkart.com/imagebk36/dEGqTpG.jpg)
![array methods](https://img.brainkart.com/imagebk36/8wh8alZ.jpg)

# String #

## What is a string ##

- A string is a sequence of characters.
- For example, "hello" is a string containing a sequence of characters 'h' , 'e' , 'l' , 'l' , and 'o' .
- We use single quotes or double quotes to represent a string in Python.

## Creating, Accessing and Modifying String ##

- Strings can be created by assigning string value ( inside '' or "" ) to a variable.
- Eg :-
  - string1 = "Python programming" or
    string1 = 'Python programming'
- We can also create a multiline string using triple double quotes """ or triple single quotes '''.
- Eg :-
  - message = """
    Never gonna give you up
    Never gonna let you down
    """
  - print(message)
    #output :-
    Never gonna give you up
    Never gonna let you down
- We can access the characters in a string in three ways.
  - Indexing: One way is to treat strings as a list and use index values.
    - greet = 'hello'
      print(greet[1])  # o/p -> "e"

      <sub> ( Note: Indexing starts from 0. )</sub>

  - Negative Indexing: Similar to a list, Python allows negative indexing for its strings.
    - greet = 'hello'
      print(greet[-4]) # o/p -> "e"
  - Slicing: Access a range of characters in a string by using the slicing operator colon ':'.
    - greet = 'Hello'
      print(greet[1:4])  # o/p -> "ell"
- In Python, strings are immutable. That means the characters of a string cannot be changed.
- Eg :-
  - greet[0]='F'  --> Gives Error.
  - However, we can assign a new string value to that variable.

## String Methods ##

![string methods](https://img.brainkart.com/imagebk36/LRhIMx8.jpg)
![string methods](https://img.brainkart.com/imagebk36/uO4rIlR.jpg)

# Objected Oriented Programming #

## What is Object-Oriented Programming? ##

- Object-Oriented Programming (OOP) is a programming paradigm in computer science that relies on the concept of classes and objects.
- It is used to structure a software program into simple, reusable pieces of code blueprints (usually called classes), which are used to create individual instances of objects.

## Building blocks of OOP ##

- Classes
- Objects
- Methods
- Attributes

### Class ###

- Classes are where we create a blueprint for the structure of methods and attributes. Individual objects are instantiated from this blueprint.
- Classes contain fields for attributes and methods for behaviors.

### Object ###

- Objects are instances of a class created with specific data.
- Objects have states and behaviors.
- The state of an object is defined by data: things like names, birthdates, and other information you’d want to store about a dog.
- Behaviors are methods the object can undertake.

### Attributes ###

- Attributes are the information that is stored.
- Attributes are defined in the Class template.
- When objects are instantiated, individual objects contain data stored in the Attributes field.

### Methods ###

- Methods represent behaviors.
- Methods perform actions; methods might return information about an object or update an object’s data.
- The method’s code is defined in the class definition.
- When individual objects are instantiated, these objects can call the methods defined in the class.

Example Program :

![example program](https://miro.medium.com/v2/resize:fit:1400/1*9t7pbZoGPgYnsiP6_lmwgw.png)
