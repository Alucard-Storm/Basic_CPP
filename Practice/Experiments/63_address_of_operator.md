# Experiment 63: Address Of Operator

**Section G — Pointers and References**

## Aim

Write a program to display the address of a variable using the address-of operator.

## Concepts Used

`&` operator

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int a = 10;
    float f = 3.5;
    cout << "Value of a = " << a << ", address = " << &a << endl;
    cout << "Value of f = " << f << ", address = " << &f << endl;
    return 0;
}
```

## Sample Run

**Output**

```text
Value of a = 10, address = 0x7ffd9444d0ec
Value of f = 3.5, address = 0x7ffd9444d0e8

```

> The printed addresses will differ on every run.

## Result

The program was executed successfully and the output was verified.
