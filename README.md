# python-oops

# Datatypes:

Python has many native datatypes. Here are the important ones:

Booleans are either True or False.
Numbers can be integers (1 and 2), floats (1.1 and 1.2), fractions (1/2 and 2/3), or even complex numbers.
Strings are sequences of Unicode characters, e.g. an html document.
Bytes and byte arrays, e.g. a jpeg image file.
Lists are ordered sequences of values.
Tuples are ordered, immutable sequences of values.
Sets are unordered bags of values.
Dictionaries are unordered bags of key-value pairs.

a_list = ['a', 'b', 'new', 'mpilgrim', 'new']

a_list[1]

del a_list[1]

a_list.remove('new')

a_list.pop() //Last item

Calling the pop() list method without an argument is like the pop() function in Perl. It removes the last item from the list and returns the value of the removed item. Perl has another function, shift(), which removes the first item and returns its value; in Python, this is equivalent to a_list.pop(0).


A tuple is an immutable list. A tuple can not be changed in any way once it is created.
- A tuple is defined in the same way as a list, except that the whole set of elements is enclosed in parentheses instead of square brackets.
- The elements of a tuple have a defined order, just like a list. Tuple indices are zero-based, just like a list, so the first element of a non-empty tuple is always a_tuple[0].
- Negative indices count from the end of the tuple, just like a list.
- Slicing works too, just like a list. When you slice a list, you get a new list; when you slice a tuple, you get a new tuple.
- In practical terms, they have no methods that would allow you to change them. Lists have methods like append(), extend(), insert(), remove(), and pop(). Tuples have none of these methods. You can slice a tuple (because that creates a new tuple), and you can check whether a tuple contains a particular value (because that doesn’t change the tuple), and… that’s about it.

Assigning multiple values:
v = ('a', 2, True)

#Dictionaries

A dictionary is an unordered set of key-value pairs. When you add a key to a dictionary, you must also add a value for that key. (You can always change the value later.) Python dictionaries are optimized for retrieving the value when you know the key, but not the other way around.

a_dict = {'server': 'db.diveintopython3.org', 'database': 'mysql'}

a_dict['database'] = 'blog'

#### __init__ is a special method in Python classes, it is the constructor method for a class. ... You can see the first argument to the method is self. It is a special variable which points to the current object

## Encapsulation
Using OOP in Python, we can restrict access to methods and variables. This prevent data from direct modification which is called encapsulation. In Python, we denote private attribute using underscore as prefix i.e single “ _ “ or double “ __ “.

## Polymorphism
In the the program, we defined two classes Parrot and Penguin. Each of them have common method fly() method. However, their functions are different. To allow polymorphism, we created common interface i.e flying_test() function that can take any object. Then, we passed the objects blu and peggy in the flying_test() function, it ran effectively.

Ref: https://www.programiz.com/python-programming/object-oriented-programming
