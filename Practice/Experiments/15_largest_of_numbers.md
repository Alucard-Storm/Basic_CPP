# Experiment 15: Largest Of Numbers

**Section B — Conditional Statements and Decision-Making**

## Aim

Write a program to find the largest of two and three numbers.

## Concepts Used

Nested conditions, logical operators

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int a, b, c;
    cout << "Enter three numbers: ";
    cin >> a >> b >> c;
    cout << "Largest of " << a << " and " << b << " is " << (a > b ? a : b) << endl;
    if (a >= b && a >= c)
        cout << "Largest of three: " << a << endl;
    else if (b >= a && b >= c)
        cout << "Largest of three: " << b << endl;
    else
        cout << "Largest of three: " << c << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
12 45 30
```

**Output**

```text
Enter three numbers: Largest of 12 and 45 is 45
Largest of three: 45

```

## Result

The program was executed successfully and the output was verified.
