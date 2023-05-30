# GLAB-370.3.4-Object-Oriented-Mastery

## Welcome to the "Object-Oriented Mastery: Unleashing the Power of OOP in Python" Guided Lab! 🚀

In this 30-minute guided lab, we'll embark on an exciting coding adventure that focuses on **Object-Oriented Programming (OOP)** in Python. Get ready to dive into the world of classes, objects, and inheritance, and unlock the true potential of OOP!

### Prerequisites

Before we begin, make sure you have the following:

- Basic knowledge of Python syntax.
- A Python interpreter or an integrated development environment (IDE) installed on your machine.

### Table of Contents

- [Step 1: Introduction](#step-1-introduction)
- [Step 2: Creating Classes and Objects](#step-2-creating-classes-and-objects)
- [Step 3: Class Attributes and Methods](#step-3-class-attributes-and-methods)
- [Step 4: Inheritance](#step-4-inheritance)
- [Step 5: Challenge](#step-5-challenge)
- [Step 6: Conclusion](#step-6-conclusion)

### Step 1: Introduction

Let's begin our adventure into the world of **Object-Oriented Programming (OOP)**. OOP is a powerful programming paradigm that allows us to organize code into reusable and modular components called **classes**. In this lab, we'll explore how to create classes, objects, and inheritance in Python.

### Step 2: Creating Classes and Objects

To start our journey, we'll learn how to create **classes** and **objects** in Python. Classes serve as blueprints for creating objects, while objects are instances of classes. We'll define attributes and methods within classes to encapsulate data and functionality.

```python
# Example:
class Car:
    def __init__(self, make, model, year):
        self.make = make
        self.model = model
        self.year = year

# Creating an object of the Car class
my_car = Car("Tesla", "Model 3", 2022)
```

### Step 3: Class Attributes and Methods

Next, let's explore class **attributes** and **methods**. Attributes are variables that store data, while methods are functions that define the behavior of objects. We'll define both instance attributes and class attributes, as well as instance methods and class methods.

```python
# Example:
class Car:
    # Class attribute
    category = "Electric"

    def __init__(self, make, model, year):
        # Instance attributes
        self.make = make
        self.model = model
        self.year = year

    def start_engine(self):
        # Instance method
        print("Engine started.")

    @classmethod
    def get_category(cls):
        # Class method
        return cls.category

# Creating an object of the Car class
my_car = Car("Tesla", "Model 3", 2022)
my_car.start_engine()

# Accessing class attribute and class method
print(Car.get_category())
```

### Step 4: Inheritance

Inheritance is a fundamental concept in OOP that allows us to create **child classes** (subclasses) that inherit attributes and methods from **parent classes** (superclasses). It promotes code reuse and enables hierarchical relationships between classes.

```python
# Example:
class ElectricCar(Car):  # ElectricCar inherits from Car
    def __init__(self, make, model, year, battery_capacity):
        super().__init__(make, model, year)
        self.battery_capacity = battery_capacity

# Creating an object of the ElectricCar class
my_electric_car = ElectricCar("Tesla", "

Model S", 2022, "100 kWh")
my_electric_car.start_engine()

# Accessing attributes from the parent class
print(my_electric_car.make)
```

### Step 5: Challenge

Now it's time for an exciting challenge! Create a class hierarchy with a parent class and multiple child classes. Define attributes and methods specific to each class, and demonstrate how inheritance allows child classes to inherit and extend the functionality of the parent class.

### Step 6: Conclusion

Congratulations on completing the "Object-Oriented Mastery: Unleashing the Power of OOP in Python" Guided Lab! You've learned the foundations of OOP in Python and unlocked the true potential of classes, objects, and inheritance.

Remember to keep exploring and practicing OOP concepts in your projects. Object-Oriented Programming offers a powerful way to structure your code, promote reusability, and enhance modularity.

Feel free to reach out if you have any questions. Happy coding, and may your OOP adventures continue! 🎉
