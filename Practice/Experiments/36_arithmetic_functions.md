# Experiment 36: Arithmetic Functions

**Section D — Functions and Recursion**

## Aim

Write a program to perform arithmetic operations using user-defined functions.

## Concepts Used

User-defined functions, return values

## Program

```cpp
#include <iostream>
using namespace std;

int add(int a, int b) { return a + b; }
int sub(int a, int b) { return a - b; }
int mul(int a, int b) { return a * b; }
float divide(int a, int b) { return (float)a / b; }

int main() {
    int x, y;
    cout << "Enter two numbers: ";
    cin >> x >> y;
    cout << "Add = " << add(x, y) << endl;
    cout << "Sub = " << sub(x, y) << endl;
    cout << "Mul = " << mul(x, y) << endl;
    cout << "Div = " << divide(x, y) << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
9 3
```

**Output**

```text
Enter two numbers: Add = 12
Sub = 6
Mul = 27
Div = 3

```

## Result

The program was executed successfully and the output was verified.
