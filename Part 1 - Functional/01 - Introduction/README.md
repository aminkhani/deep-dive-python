# Python Deep Dive

## Part 1

### This course is about

- The Python **language and built-in types**
- The **standard library**
- Becoming an **expert** Python developer
- **Idiomatic** Python

#### The Zen of Python

> Tim Peters [PEP 20](https://peps.python.org/pep-0020/)

```python
>>> import this
```

- [x] Beautiful is better than ugly.
- [x] Explicit is better than implicit.
- [x] Simple is better than complex.
- [x] Complex is better than complicated.
- [x] Flat is better than nested.
- [x] Sparse is better than dense.
- [x] Readability counts.
- [x] Special cases aren't special enough to break the rules.
- [x] Although practicality beats purity.
- [x] Errors should never pass silently.
- [x] Unless explicitly silenced.
- [x] In the face of ambiguity, refuse the temptation to guess.
- [x] There should be one-- and preferably only one --obvious way to do it.
- [x] Although that way may not be obvious at first unless you're Dutch.
- [x] Now is better than never.
- [x] Although never is often better than *right* now.
- [x] If the implementation is hard to explain, it's a bad idea.
- [x] If the implementation is easy to explain, it may be a good idea.
- [x] Namespaces are one honking great idea -- let's do more of those!

## What we learn?

### [Variables and Memory](./01-Variables-and-Memory/README.md)

- **What are variables?**
  - symbols for memory addresses
- **Memory**
- **Python memory management**
  - reference counting, garbage collection
- **Mutability**
  - function arguments, shared references
- **What is equality of two objects?**
- **Python memory optimizations**
  - interning, peephole

### [Numeric Types](./02-Numeric-Types/README.md)

- **Integers**
- **Rationals**
- **Floats**
  - binary representation
  - exactness
  - rounding
  - equality
  - measure of closeness
  - approximate equality
- **Decimals**
  - alternative to floats
  - exactness
  - precision
  - rounding
- **Complex Numbers**
  - **cmath** standard library

### [Numeric Types - Booleans](./03-Booleans/README.md)

- **Associated Truth values**
  - every object has one
- **Precedence and short-circuiting**
- **Boolean operators**
  - what they ***really*** do
  - using in context of associated truth values
- **Comparison operators**
  - identity
  - values equalities
  - ordering

### [Functions](./04-Functions/README.md)

- **Higher-order functions**
- **Docstrings and annotations**
- **Lambdas**
- **Introspection**
- **Functional programming**
  - map, filter, zip
  - reducing functions
  - partial functions

### [Functions - Arguments](./05-Functional-Arguments/README.md)

- **Positional arguments**
- **Positional arguments**
- **Default values**
  - caveats
- **Packing and unpacking**
- **Variable positional arguments**
- **Variable keyword-only arguments**

### [Functions - Scopes and Closures](./06-Scopes-and-Closures/README.md)

- **Global and local scopes**
- **Nested scopes**
- **Closures**
- **Nested closures**

### [Decorators](./07-Decorators/README.md)

- **Decorators**
- **Nested decorators**
- **Parameterized decorators**
- **Stacked decorators**
- **Class decorators**
- **Decorator classes**
- **Applications**
  - memoization, single dispatch, logging, timing

### [Tuples as Data Structures](./08-Tuples-as-Data-Structures/README.md)

- **Tuples are not just read-only lists**
- **Data structures**
- **Packing and unpacking**
- **Named tuples**
- **Augmenting named tuples**

### [Modules, Packages and Namespaces](./09-Modules-Packages-Namespaces/README.md)

- **What are modules?**
- **What are packages?**
- **How do the various imports work?**
- **How to manipulate namespaces using packages**
- **Zip archives**
- **__main__**

### [Extras](./10-Extras/README.md)

- **Will keep growing over time**
- **Important new features of Python 3.6 and later**
- **Best practices**
- **Random collection of interesting stuff**
- **Additional resources**
