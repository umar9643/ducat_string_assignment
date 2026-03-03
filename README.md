# ducat_string_assignment

# 🐍 Python String Methods – Complete Guide

> A beginner-friendly and interview-ready reference for all important Python string methods.
> This repository is designed to help learners understand string manipulation clearly with definitions and examples.

---

## 📌 About This Repository

This repository contains:

* 🔤 Case conversion methods
* 🔎 Searching methods
* ✂️ Strip & cleaning methods
* 🔁 Replace & modify methods
* 🔗 Split & join methods
* 📏 Alignment & formatting methods
* ✅ Boolean checking methods

Each method includes:

* Clear definition
* Syntax
* Simple example
* Real-world use case

---

# 🔠 1. Case Conversion Methods

These methods change the letter casing of strings.

### `upper()`

Converts all characters to uppercase.

```python
text = "hello"
print(text.upper())
```

### `lower()`

Converts all characters to lowercase.

```python
text = "HELLO"
print(text.lower())
```

### `title()`

Capitalizes the first letter of each word.

```python
text = "hi my name is umar"
print(text.title())
```

### `capitalize()`

Capitalizes only the first character of the string.

```python
text = "hello world"
print(text.capitalize())
```

### `swapcase()`

Swaps uppercase to lowercase and vice versa.

```python
text = "Hello UMAR"
print(text.swapcase())
```

---

# 🔍 2. Searching Methods

Used to find substrings inside a string.

### `find()`

Returns index of substring. Returns -1 if not found.

```python
text = "hello world"
print(text.find("world"))
```

### `index()`

Same as find() but raises error if not found.

```python
text = "hello world"
print(text.index("world"))
```

### `count()`

Counts occurrences of substring.

```python
text = "apple apple mango"
print(text.count("apple"))
```

---

# ✂️ 3. Strip & Cleaning Methods

Used to remove unwanted characters.

### `strip()`

Removes characters from both ends.

```python
text = "  hello  "
print(text.strip())
```

### `lstrip()`

Removes characters from left side.

### `rstrip()`

Removes characters from right side.

---

# 🔁 4. Replace & Modify Methods

### `replace()`

Replaces one substring with another.

```python
text = "hi umar"
print(text.replace("umar", "ali"))
```

### `translate()` + `maketrans()`

Used for multiple character replacements.

---

# 🔗 5. Split & Join Methods

### `split()`

Splits string into a list.

```python
text = "hi my name"
print(text.split())
```

### `rsplit()`

Splits from right side.

### `splitlines()`

Splits on newline (`\n`).

### `join()`

Joins iterable into a string.

```python
words = ["hi", "umar"]
print(" ".join(words))
```

---

# 📏 6. Alignment & Formatting

### `center()`

Centers text within given width.

### `ljust()` / `rjust()`

Left and right alignment.

### `zfill()`

Pads string with zeros on the left.

```python
num = "25"
print(num.zfill(5))
```

### `format()`

Formats string dynamically.

---

# ✅ 7. Boolean Checking Methods

These return True or False.

* `isalnum()`
* `isalpha()`
* `isdigit()`
* `islower()`
* `isupper()`
* `isspace()`
* `isidentifier()`
* `istitle()`

Example:

```python
print("hello".islower())
```

---

# 🎯 Why This Matters

String manipulation is heavily used in:

* Data Cleaning
* Data Analysis
* Machine Learning Preprocessing
* Web Development
* Automation Scripts
* Interview Coding Questions

Mastering these methods makes your Python foundation very strong.

---

👨‍💻 Author

**Umar Alam**
Aspiring Data Analyst | Python & ML Learner

📬 **Contact**  
For feedback, suggestions, or collaboration, feel free to reach out via:  

**GitHub**: [umar9643](https://github.com/umar9643)  
**LinkedIn**: [Umar Alam's Profile](https://www.linkedin.com/in/umar-alam-a1b2c3)  
**Email**: [alamumar258455@gmail.com](mailto:alamumar258455@gmail.com)


