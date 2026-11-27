# Experiment 24: Sum Natural Numbers

**Section C — Loops and Number-Based Problems**

## Aim

Write a program to calculate the sum of the first \\(N\\) natural numbers.

## Concepts Used

Accumulator pattern

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n, sum = 0;
    cout << "Enter N: ";
    cin >> n;
    for (int i = 1; i <= n; i++)
        sum += i;
    cout << "Sum = " << sum << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
10
```

**Output**

```text
Enter N: Sum = 55

```

## Result

The program was executed successfully and the output was verified.
