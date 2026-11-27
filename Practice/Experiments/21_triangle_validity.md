# Experiment 21: Triangle Validity

**Section B — Conditional Statements and Decision-Making**

## Aim

Write a program to check whether three sides can form a valid triangle and determine its type.

## Concepts Used

Validity condition, triangle types

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    float a, b, c;
    cout << "Enter three sides: ";
    cin >> a >> b >> c;
    if (a + b > c && b + c > a && a + c > b) {
        if (a == b && b == c)
            cout << "Equilateral triangle" << endl;
        else if (a == b || b == c || a == c)
            cout << "Isosceles triangle" << endl;
        else
            cout << "Scalene triangle" << endl;
    } else {
        cout << "Not a valid triangle" << endl;
    }
    return 0;
}
```

## Sample Run

**Input**

```text
5 5 8
```

**Output**

```text
Enter three sides: Isosceles triangle

```

## Result

The program was executed successfully and the output was verified.
