# Experiment 13: Even Odd

**Section B — Conditional Statements and Decision-Making**

## Aim

Write a program to check whether a number is even or odd.

## Concepts Used

`if-else`, modulus

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter a number: ";
    cin >> n;
    if (n % 2 == 0)
        cout << n << " is even" << endl;
    else
        cout << n << " is odd" << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
7
```

**Output**

```text
Enter a number: 7 is odd

```

## Result

The program was executed successfully and the output was verified.
