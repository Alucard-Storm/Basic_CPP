# Experiment 31: Primes In Range

**Section C — Loops and Number-Based Problems**

## Aim

Write a program to print all prime numbers within a given range.

## Concepts Used

Nested loops

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int lo, hi;
    cout << "Enter range: ";
    cin >> lo >> hi;
    for (int n = lo; n <= hi; n++) {
        if (n < 2) continue;
        bool prime = true;
        for (int i = 2; i * i <= n; i++)
            if (n % i == 0) { prime = false; break; }
        if (prime) cout << n << " ";
    }
    cout << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
10 50
```

**Output**

```text
Enter range: 11 13 17 19 23 29 31 37 41 43 47 

```

## Result

The program was executed successfully and the output was verified.
