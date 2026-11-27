# Experiment 11: Operators Demo

**Section A — Basic Programming and Operators**

## Aim

Write a program to demonstrate increment, decrement, relational, and logical operators.

## Concepts Used

`++`, `--`, relational and logical operators

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int a = 5, b = 10;
    cout << "a++ = " << a++;
    cout << ", now a = " << a << endl;
    cout << "--b = " << --b << endl;
    cout << "a == b : " << (a == b) << endl;
    cout << "a < b : " << (a < b) << endl;
    cout << "a > 3 && b > 3 : " << (a > 3 && b > 3) << endl;
    cout << "a > 10 || b > 3 : " << (a > 10 || b > 3) << endl;
    cout << "!(a > b) : " << !(a > b) << endl;
    return 0;
}
```

## Sample Run

**Output**

```text
a++ = 5, now a = 6
--b = 9
a == b : 0
a < b : 1
a > 3 && b > 3 : 1
a > 10 || b > 3 : 1
!(a > b) : 1

```

## Result

The program was executed successfully and the output was verified.
