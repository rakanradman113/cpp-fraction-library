# Fraction Arithmetic Library

### Overview
A C++ class that supports arithmetic and comparison operations on fractions using **operator overloading**.  
Includes input/output stream support, normalization, and validation.

---

### Features
- Overloaded operators: `+`, `-`, `*`, `/`, `==`, `!=`, `<`, `>`  
- Stream operators (`<<`, `>>`) for easy I/O  
- Automatic simplification using GCD  
- Handles negative and zero denominators safely  

---

### Example
```cpp
Fraction a(1, 2);
Fraction b(3, 4);

Fraction c = a + b;
cout << c << endl; // Output: 5/4
