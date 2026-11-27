# Experiment 41: Factorial Recursion

**Section D — Functions and Recursion**

## Aim

Write a program to calculate factorial using recursion.

## Concepts Used

Recursion, base case

## Program

```cpp
#include <iostream>
using namespace std;

long long fact(int n) {
    if (n <= 1) return 1;
    return n * fact(n - 1);
}

int main() {
    int n;
    cout << "Enter a number: ";
    cin >> n;
    cout << n << "! = " << fact(n) << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
5
```

**Output**

```text
Enter a number: 5! = 120

```

## Result

The program was executed successfully and the output was verified.
