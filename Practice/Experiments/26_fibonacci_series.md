# Experiment 26: Fibonacci Series

**Section C — Loops and Number-Based Problems**

## Aim

Write a program to generate the Fibonacci series up to \\(N\\) terms.

## Concepts Used

Loop with two running variables

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n, a = 0, b = 1;
    cout << "Enter number of terms: ";
    cin >> n;
    for (int i = 1; i <= n; i++) {
        cout << a << " ";
        int next = a + b;
        a = b;
        b = next;
    }
    cout << endl;
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
Enter number of terms: 0 1 1 2 3 5 8 13 21 34 

```

## Result

The program was executed successfully and the output was verified.
