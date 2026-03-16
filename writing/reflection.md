# CS101 Spring 2026 — Practice Midterm Reflection

Name: Muhammed Bello 
Date: March 16, 2026

After completing the practice test, please reflect on your experience by
answering the questions below. Replace each todo` with a thoughtful response
(a few sentences each). Your responses help you consolidate what you learned
and identify areas to review before the real midterm.

---

## 1. Self-Assessment

**Question:** How did you feel about your performance on the practice test?
Which topics felt most comfortable, and which ones felt most difficult?

**Your Answer:**

I felt confident while completing the practice test. Questions about loops, dictionaries, and conditionals felt comfortable to me. Some questions about slicing, lambda functions, and operator precedence were a little more difficult. Overall, the test helped me review important Python concepts and showed me which topics I should practice more before the midterm.

---

## 2. Tricky Questions

**Question:** Identify one question you got wrong (or were unsure about).
Explain the concept being tested and describe why the correct answer is right.

**Your Answer:**

One tricky question involved exponentiation order. In Python, the ** operator is evaluated from right to left. For example, 3 ** 2 ** 2 becomes 3 ** (2 ** 2). First Python calculates 2 ** 2 = 4, then it calculates 3 ** 4 = 81. Understanding operator precedence is important when reading mathematical expressions in Python.

---

## 3. Loops and Iteration

**Question:** In your own words, explain the difference between `range(a, b, step)`
with a positive step versus a negative step. Give one original example of each.

**Your Answer:**

One hard question involved exponentiation order. In Python, the ** operator is evaluated from right to left. For example, 3 ** 2 ** 2 becomes 3 ** (2 ** 2). First Python calculates 2 ** 2 = 4, then it calculates 3 ** 4 = 81. Understanding operator precedence is important when reading mathematical expressions in Python.

---

## 4. Data Structures

**Question:** Python has lists, tuples, dictionaries, and sets. Describe one key
difference between a list and a tuple, and one key difference between a
dictionary and a set. When would you choose each?

**Your Answer:**

A list is mutable, meaning its values can be changed, while a tuple is immutable and cannot be modified after creation. Lists are useful when data needs to change, while tuples are useful for fixed data. A dictionary stores data as key-value pairs, while a set stores unique values without duplicates.

---

## 5. Functions

**Question:** What is a default parameter in a Python function? Write a short
example function that uses a default parameter, and explain what happens when
the caller omits that argument.

**Your Answer:**

A default parameter is a value used when the caller does not provide an argument. For example:
     def greet(name="Guest"):
    print("Hello", name)


---

## 6. List Comprehensions

**Question:** List comprehensions can include an optional filter condition.
Rewrite the following traditional loop as a list comprehension:

```python
result = []
for n in range(1, 11):
    if n % 3 == 0:
        result.append(n * 2)
```

**Your Answer:**

result = [n * 2 for n in range(1, 11) if n % 3 == 0]

---

## 7. Operator Precedence

**Question:** Python evaluates `**` (exponentiation) right-to-left.
What is the value of `2 ** 2 ** 3`? Show your step-by-step reasoning.

**Your Answer:**

Python evaluates exponentiation from right to left.

Step 1: 2 ** 3 = 8
Step 2: 2 ** 8 = 256

So 2 ** 2 ** 3 = 256.

---

## 8. Classes 

**Question:** What are classes in Python programming? Explain why they are necessary in programming.

**Your Answer:**

Classes are blueprints used to create objects in Python. They group data and functions together. Classes help organize code and make programs easier to maintain. For example, a Book class might store a title and number of pages for each book object.

---

(Did you remember to add your name and date at the top of this document?)
