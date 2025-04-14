
## ✅ Day 11 - 30 Days of Coding Challenge: To-Do

### 🔁 Typecasting
- [ ] Understand converting one data type into another.
- [ ] Try converting string to int, float to int, etc.
- [ ] Practice with this example:
  ```python
  x = "10"
  y = int(x)
  print(y + 5)  # Output: 15
  ```
- 💡 **Fun Fact:** In Python, everything is an object—even numbers and functions! Typecasting just changes the object’s interface, not its underlying nature.

---

### 🔃 Recursion
- [ ] Understand how a function can call itself.
- [ ] Write a recursive function (e.g., factorial, Fibonacci).
- [ ] Practice with this example:
  ```python
  def factorial(n):
      if n == 1:
          return 1
      return n * factorial(n - 1)

  print(factorial(5))  # Output: 120
  ```
- 🧠 **Fun Fact:** Recursion is used in many real-world systems like file system traversal, search algorithms, and even the Tower of Hanoi puzzle.

---

### 🏷️ Class Attributes
- [ ] Learn the difference between class and instance attributes.
- [ ] Create a class and define both types of attributes.
- [ ] Practice with this example:
  ```python
  class Dog:
      species = "Canis familiaris"

      def __init__(self, name):
          self.name = name

  dog1 = Dog("Buddy")
  dog2 = Dog("Max")

  print(dog1.species)  # Output: Canis familiaris
  print(dog2.name)     # Output: Max
  ```
- 🐶 **Fun Fact:** Class attributes are shared across all instances, which is perfect for constants like species, version info, or defaults!

---

Want mini-challenges or exercises for these topics?
