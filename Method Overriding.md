# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM:
```
class ECE:
    def __init__(self, value):
        self.value = value

    # Overloading * operator to multiply values
    def __mul__(self, other):
        return self.value * other.value


# Creating objects
obj1 = ECE(4)
obj2 = ECE(3)

# Multiplying objects
result = obj1 * obj2
print(result)

# Printing "parrot" exactly 3 times
print("parrot" * 3)
```
## OUTPUT
<img width="558" height="193" alt="image" src="https://github.com/user-attachments/assets/f199c10b-f18b-49c6-9f13-10f787f87557" />

## RESULT
Executed successfully.
