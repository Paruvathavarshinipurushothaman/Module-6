# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

## 💻 Program
```
from abc import ABC, abstractmethod

# Abstract Base Class
class educlass(ABC):
    def __init__(self, value):
        self.value = value

    # Abstract method
    @abstractmethod
    def course(self):
        pass

    # Normal method visible to user
    def print_value(self):
        print(f"The value is:  {self.value}")

# Subclass Demo
class Demo(educlass):
    def course(self):
        print("This is demo class")
        self.print_value()

# Subclass Learn
class Learn(educlass):
    def course(self):
        print("This is test class")
        self.print_value()

# Creating objects
t1 = Learn(500)
ex = Demo(850)

# Invoking course() method
t1.course()
ex.course()

# Checking instances
print(f"t1 is instance of educlass? ", isinstance(t1, educlass))
print(f"ex is instance of educlass? ", isinstance(ex, educlass))
```
## Output
<img width="796" height="275" alt="image" src="https://github.com/user-attachments/assets/9a080570-65da-4336-a387-02dfeac63669" />

## Result
Executed successfully.
