# Experiment 33: Gcd Lcm

**Section C — Loops and Number-Based Problems**

## Aim

Write a program to find the GCD and LCM of two integers.

## Concepts Used

Euclid's algorithm

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int a, b;
    cout << "Enter two numbers: ";
    cin >> a >> b;
    int x = a, y = b;
    while (y != 0) {
        int t = y;
        y = x % y;
        x = t;
    }
    cout << "GCD = " << x << endl;
    cout << "LCM = " << (a * b) / x << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
12 18
```

**Output**

```text
Enter two numbers: GCD = 6
LCM = 36

```

## Result

The program was executed successfully and the output was verified.
