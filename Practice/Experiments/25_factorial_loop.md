# Experiment 25: Factorial Loop

**Section C — Loops and Number-Based Problems**

## Aim

Write a program to calculate the factorial of a number using a loop.

## Concepts Used

`long long`, loops

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    long long fact = 1;
    cout << "Enter a number: ";
    cin >> n;
    for (int i = 2; i <= n; i++)
        fact *= i;
    cout << "Factorial = " << fact << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
6
```

**Output**

```text
Enter a number: Factorial = 720

```

## Result

The program was executed successfully and the output was verified.
