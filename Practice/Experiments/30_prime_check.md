# Experiment 30: Prime Check

**Section C — Loops and Number-Based Problems**

## Aim

Write a program to check whether a number is prime.

## Concepts Used

Loop with `break` and flag

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    bool prime = true;
    cout << "Enter a number: ";
    cin >> n;
    if (n < 2) prime = false;
    for (int i = 2; i * i <= n; i++) {
        if (n % i == 0) {
            prime = false;
            break;
        }
    }
    cout << n << (prime ? " is prime" : " is not prime") << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
29
```

**Output**

```text
Enter a number: 29 is prime

```

## Result

The program was executed successfully and the output was verified.
