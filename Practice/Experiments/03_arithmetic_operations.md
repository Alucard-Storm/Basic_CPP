# Experiment 3: Arithmetic Operations

**Section A — Basic Programming and Operators**

## Aim

Write a program to perform addition, subtraction, multiplication, division, and modulus operations.

## Concepts Used

Arithmetic operators `+ - * / %`

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int a, b;
    cout << "Enter two integers: ";
    cin >> a >> b;
    cout << "Sum = " << a + b << endl;
    cout << "Difference = " << a - b << endl;
    cout << "Product = " << a * b << endl;
    cout << "Quotient = " << a / b << endl;
    cout << "Modulus = " << a % b << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
17 5
```

**Output**

```text
Enter two integers: Sum = 22
Difference = 12
Product = 85
Quotient = 3
Modulus = 2

```

## Result

The program was executed successfully and the output was verified.
