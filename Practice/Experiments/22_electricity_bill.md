# Experiment 22: Electricity Bill

**Section B — Conditional Statements and Decision-Making**

## Aim

Write a program to calculate an electricity bill using slab-based charges.

## Concepts Used

Slab-based calculation

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int units;
    float bill;
    cout << "Enter units consumed: ";
    cin >> units;
    if (units <= 100)
        bill = units * 1.5;
    else if (units <= 200)
        bill = 100 * 1.5 + (units - 100) * 2.5;
    else
        bill = 100 * 1.5 + 100 * 2.5 + (units - 200) * 4;
    cout << "Electricity bill = Rs. " << bill << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
250
```

**Output**

```text
Enter units consumed: Electricity bill = Rs. 600

```

## Result

The program was executed successfully and the output was verified.
