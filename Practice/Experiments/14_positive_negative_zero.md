# Experiment 14: Positive Negative Zero

**Section B — Conditional Statements and Decision-Making**

## Aim

Write a program to check whether a number is positive, negative, or zero.

## Concepts Used

`if - else if - else`

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter a number: ";
    cin >> n;
    if (n > 0)
        cout << "Positive" << endl;
    else if (n < 0)
        cout << "Negative" << endl;
    else
        cout << "Zero" << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
-4
```

**Output**

```text
Enter a number: Negative

```

## Result

The program was executed successfully and the output was verified.
