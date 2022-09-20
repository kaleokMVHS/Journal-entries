# 9/13/2022 OOP and Turtle

* Input and output- Ways to interact and communicate with the user. Can be done by printing to console, displaying or drawing an image, triggering physical machines (output), or receiving text input, mouse movement, external sensors, etc (input).

* print function - prints the given string to console

    ```python
      print("hello") # -> hello
    ```

* Data types- dufferent forms data can take in a program. Ex: integers, floats, strings, lists, dicts, etc.

* substrings - a section of an existing string

* commenting in python - makes a line of code just visual, not interpreted.

```python
  # print("hellow world") -> this will not run
```

* objects in OOP- objects are instances of a class "blueprint". They are representations of a physical or abstract object, and you can interact with them in all the ways defined by the class. You do this by sending it messages, or calling its methods, like ``.method(1, 2)`` to call the object's `method` method with args `(1, 2)`

## Conclusion questions

1. What is the difference between the input and output of a program, and how can one affect the other? Give an example using Python code.

Input is how a person can interact with the program. The examples given in this lesson are primarily via text. For example

```python
    print(input("What is your name")) # prompts for input via the command line, then prints it back.
```

Output is how the program communicates back to the user, via text, displaying something to the screen, etc. 

2. Is there only one way to solve a problem? Explain and give an example using Python turtle.

Of course not, there is almost always many ways to approach a problem. For example, there is many ways a
person could draw a square with turtle:

```python
import turtle as trtl

painter = trtl.Turtle()

painter.forward(25)
painter.right(90)
painter.forward(25)
painter.right(90)
painter.forward(25)
painter.right(90)
painter.forward(25)

for i in range(4):
  painter.forward(25)
  painter.right(90)

painter.circle(12.5, 360, 4)

# All three will make a square, but each accomplishes it slightly differently, in a different number of lines.
```

