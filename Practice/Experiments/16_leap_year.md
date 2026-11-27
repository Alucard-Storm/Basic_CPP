# Experiment 16: Leap Year

**Section B — Conditional Statements and Decision-Making**

## Aim

Write a program to check whether a given year is a leap year.

## Concepts Used

Compound conditions

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int y;
    cout << "Enter year: ";
    cin >> y;
    if ((y % 4 == 0 && y % 100 != 0) || y % 400 == 0)
        cout << y << " is a leap year" << endl;
    else
        cout << y << " is not a leap year" << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
2024
```

**Output**

```text
Enter year: 2024 is a leap year

```

## Result

The program was executed successfully and the output was verified.
