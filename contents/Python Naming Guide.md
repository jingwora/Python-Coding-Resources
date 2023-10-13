# Python Naming Guide

[<<Python-Coding-Resources](https://github.com/jingwora/Python-Coding-Resources/tree/main)

Proper naming conventions, outlined in PEP 8, are essential for code readability. While new Python assets should adhere to these guidelines, existing libraries with established styles should maintain their internal consistency. Furthermore, avoid overly generic names and ensure, as per PEP 3131, that identifiers in the standard library remain ASCII compatible. Below, we'll explore the recommended naming conventions for prevalent Python objects.

---

#### 1. Packages: `lowercase`

Packages in Python refer to directories that house multiple module files. The naming convention for packages is all lowercase.

*Example (Directory Structure)*:

```
mypackage/
├── __init__.py
└── module1.py
```

---

#### 2. Modules: `lowercase`

Modules in Python typically refer to individual `.py` files. The naming convention for modules is straightforward: use all lowercase letters, separating words with underscores if necessary.

*Example*:

```python
# filename: user_management.py
```

---

#### 3. Classes: `CapWords`

Classes in Python adopt the `CapWords` or CamelCase convention, capitalizing the first letter of each word.

*Example*:

```python
class UserProfile:
    pass
```

---

#### 4. Type Variables: `CapWords`

Type variables, used in type hinting and generics, follow the `CapWords` or CamelCase convention.

*Example*:

```python
from typing import TypeVar

UserType = TypeVar('UserType')
```

---

#### 5. Constants: `UPPERCASE`

Constants are values that remain unchanged throughout a program's execution. They are conventionally named using all uppercase letters, separating multiple words with underscores.

*Example*:

```python
MAX_RETRIES = 5
PI_VALUE = 3.14159
```

---

#### 6. Functions: `lowercase`

Functions stick to an all-lowercase naming scheme. Names composed of multiple words should be separated by underscores.

*Example*:

```python
def calculate_average(values):
    pass
```

---

#### 7. Methods: `lowercase`

Methods, which are functions defined within classes, follow the same naming convention as standalone functions: all lowercase with underscore-separated words.

*Example*:

```python
class User:
    def get_username(self):
        pass
```

---

#### 8. Parameters: `lowercase`

Parameters, which are the variables listed in a function definition, adhere to the all-lowercase convention, separating multiple words with underscores.

*Example*:

```python
def register_user(first_name, last_name):
    pass
```

---

Embracing these naming conventions ensures your Python code remains accessible, readable, and maintainable. These standards promote clarity, simplify the onboarding process for new contributors, and contribute to the cohesiveness of the Python community.
