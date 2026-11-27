# Experiment 28: Digit Sum Product

**Section C — Loops and Number-Based Problems**

## Aim

Write a program to calculate the sum and product of the digits of a number.

## Concepts Used

Digit extraction

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n, sum = 0, prod = 1;
    cout << "Enter a number: ";
    cin >> n;
    while (n > 0) {
        int d = n % 10;
        sum += d;
        prod *= d;
        n /= 10;
    }
    cout << "Sum of digits = " << sum << "\nProduct of digits = " << prod << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
234
```

**Output**

```text
Enter a number: Sum of digits = 9
Product of digits = 24

```

## Result

The program was executed successfully and the output was verified.
