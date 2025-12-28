# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Robot:
    def __init__(self):
        self.__version = 22  # Private member

    # Getter method
    def get_version(self):
        return self.__version

    # Setter method
    def set_version(self, version):
        self.__version = version


# Creating object
r = Robot()

# Display initial version
print(r.get_version())

# Change version using setter
r.set_version(23)

# Display updated version
print(r.get_version())
```
## Output
<img width="322" height="180" alt="image" src="https://github.com/user-attachments/assets/b6346b79-a0aa-4f41-90c4-afa88b85b995" />

## Result
Executed successfully.
