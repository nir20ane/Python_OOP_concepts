Python OOP Concepts

# Classes
* A class in Python is a blueprint for creating objects.
* Object: An instance of a class.
* Attributes: Properties or variables belonging to an object that define its characteristics.
* Methods: Functions defined within a class that describe behaviors of an object.
* self: Refers to the specific instance of the class.
* __init__: A special method in Python known as the constructor, used to initialize attributes of an object when it's created.



# Encapsulation
* Encapsulation refers to restricting direct access to an object's attributes and methods.
  # Public Attributes and Methods
    * Can be freely accessed and modified from outside the class.
    * By default, all attributes and methods in Python are public.

  # Protected attributes and methods
    * protected attributes and methods are class members that should not be accessed directly from outside the class
    * However, they can be accessed within the class and in child classes 
    * Protected attributes are denoted by prefixing the attribute/method name with a _
    * Note: Python does not enforce access control strictly. Protected attributes and methods are a convention to signal that external code should avoid accessing them directly.
