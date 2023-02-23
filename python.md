# Python Fact Finding Exercise
### 1)Define a list and tuple inPython.Providesomeexamples?
  ## List: 
         * Lists are used to store multiple items in a single variable
         * Lists are created using square brackets.
         * List items are ordered, changeable, and allow duplicate values.
         * List items are indexed, the first item has index [0], the second item has index [1] etc.
         ex: thislist = ["apple", "banana", "cherry"]
        Ordered:
           When we say that lists are ordered, it means that the items have a defined order, and that order will not change.
        Changeable:
          The list is changeable, meaning that we can change, add, and remove items in a list after it has been created.
          If you add new items to a list, the new items will be placed at the end of the list.
        Allow Duplicates:
          Since lists are indexed, lists can have items with the same value:
          thislist = ["apple", "banana", "cherry", "apple", "cherry"]
 ## Tuple:   
       * Tuples are used to store multiple items in a single variable.
       * Tuples are used to store multiple items in a single variable.
       * Tuples are written with round brackets.
         Ex: thistuple = ("apple", "banana", "cherry")
      Ordered:
        When we say that tuples are ordered, it means that the items have a defined order, and that order will not change.
      Unchangeable:
        Tuples are unchangeable, meaning that we cannot change, add or remove items after the tuple has been created.  
      Allow Duplicates: 
        Since tuples are indexed, they can have items with the same value
        ex:thistuple = ("apple", "banana", "cherry", "apple", "cherry")


## 2)What is a namespace in Python?
    
    A namespace in Python is a mapping from names to objects. It is used to avoid naming conflicts and to organize code into logical groups. Namespaces provide a way to isolate names from different parts of a program so that they do not interfere with each other.
    In Python, there are four types of namespaces:
    Built-in Namespace - It contains the built-in functions and types provided by Python.
    Global Namespace - It contains the names defined at the module level. These names are available throughout the module.
    Local Namespace - It contains the names defined inside a function. These names are available only within the function.
    Enclosing Namespace - It contains the names defined in the local scope of enclosing functions. These names are available to nested functions.
    Python uses a hierarchical namespace lookup system to resolve names in a program. When a name is used, Python searches for it in the local namespace first, then in the enclosing namespace(s), then in the global namespace, and finally in the built-in namespace. If the name is not found, a NameError is raised.

    In summary, a namespace is a way to organize and manage names in a Python program. It helps to avoid naming conflicts and provides a mechanism for resolving names during runtime.


## 3)What is the difference between a localvariable and a globalvariable?
    Local Variables:
       * Local variables are created when the function starts its execution and are lost when the function ends.
       * local variables are declared within the functions.
         
    Global Variable:
       * Global variables are declared outside the functions
       * Global variables, on the other hand, are created as the execution of the program begins and are lost when the program is ended
             

## 4)What is an IDE? Mention some common IDEs that could be used with Python?
     IDE stands for Integrated Development Environment. It is a software application that provides comprehensive tools and features for developing and testing software. An IDE typically includes a code editor, a compiler or interpreter, a debugger, and other tools that simplify the software development process.
     Here are some popular IDEs that can be used with Python:

       PyCharm - Developed by JetBrains, PyCharm is a powerful and feature-rich IDE that offers intelligent code completion, debugging, testing, and other productivity features.
       Spyder - Spyder is an open-source IDE that is specifically designed for scientific computing and data analysis. It includes features like variable explorer, profiler, and IPython console.
       IDLE - IDLE is a lightweight IDE that comes bundled with Python. It includes basic features like syntax highlighting, code completion, and a debugger.
       Visual Studio Code - Visual Studio Code is a lightweight, cross-platform IDE that offers a range of features for Python development, including syntax highlighting, debugging, and extensions for linting, testing, and code formatting.
       Jupyter Notebook - Jupyter Notebook is a web-based interactive development environment that is widely used for data analysis and scientific computing. It allows users to create and share documents that combine live code, equations, visualizations, and narrative text.
       These are just a few examples of the many IDEs that are available for Python. The choice of IDE will depend on the specific needs and preferences of the developer.
    

## 5)What are modules in Python? Providesomeexamples?
    In Python, a module is a file containing Python code that can be imported into another Python program. Modules are used to organize code into reusable units, making it easier to manage and maintain large codebases. Modules provide a way to reuse code across multiple projects and to share code with other developers.

    Here are some examples of modules in Python:

      1.math - The math module provides a range of mathematical functions and constants, such as sqrt(), sin(), cos(), and pi.
      2.datetime - The datetime module provides classes for working with dates and times, such as date(), time(), datetime(), timedel  (), and timezone().
      3.random - The random module provides functions for generating random numbers, such as randint(), random(), and choice().

## 6)What is the difference between an array and a list?
     List:
       * List cannot manage arithmetic operations
       * List consists of elements that belong to the different data types. 
       * the list is perfect as it allows easy modification of data.
      Array:
        *  array can manage arithmetic operations.
        * Array consists of elements that belong to the same data type.
        * the array is not suitable as it does not allow easy modification of data.
       
        
## 7)What are operators? Providesomeexamples?
     In Python, operators are special symbols that designate that some sort of computation should be performed. The values that an operator acts on are called operands.In Python, operators are symbols or keywords that perform operations on values or variables. Python has several types of operators, including arithmetic operators, comparison operators, logical operators, bitwise operators, and assignment operators.

     Here are some examples of operators in Python:

     Arithmetic operators:
       x = 10
       y = 3
       print(x + y)  # Output: 13
       print(x - y)  # Output: 7
    Comparison operators:
       x = 10
       y = 3
       print(x == y)  # Output: False
       print(x != y)  # Output: True
    Logical operators:
       x = True
       y = False
       print(x and y) # Output: False
       print(x or y)  # Output: True
    operator= %
      Example= a % b
      Meaning= Modulo
      Results= Remainder when a is divided by b
    Operator= /    
       Example= a / b    Division
       Meaning= Quotient when a is divided by b.
       Results= The result always has type float.  
    