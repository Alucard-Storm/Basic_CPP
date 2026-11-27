# Experiment 9: Simple Compound Interest

**Section A — Basic Programming and Operators**

## Aim

Write a program to calculate simple interest and compound interest.

## Concepts Used

`pow()`, `<cmath>`

## Program

```cpp
#include <iostream>
#include <cmath>
using namespace std;

int main() {
    float p, r, t;
    cout << "Enter principal, rate and time: ";
    cin >> p >> r >> t;
    float si = (p * r * t) / 100;
    float ci = p * pow(1 + r / 100, t) - p;
    cout << "Simple Interest = " << si << endl;
    cout << "Compound Interest = " << ci << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
1000 5 2
```

**Output**

```text
Enter principal, rate and time: Simple Interest = 100
Compound Interest = 102.5

```

## Result

The program was executed successfully and the output was verified.
