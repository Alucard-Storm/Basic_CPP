# Experiment 42: Fibonacci Recursion

**Section D — Functions and Recursion**

## Aim

Write a program to generate the Fibonacci series using recursion.

## Concepts Used

Recursive calls

## Program

```cpp
#include <iostream>
using namespace std;

int fib(int n) {
    if (n == 0) return 0;
    if (n == 1) return 1;
    return fib(n - 1) + fib(n - 2);
}

int main() {
    int n;
    cout << "Enter number of terms: ";
    cin >> n;
    for (int i = 0; i < n; i++)
        cout << fib(i) << " ";
    cout << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
8
```

**Output**

```text
Enter number of terms: 0 1 1 2 3 5 8 13 

```

## Result

The program was executed successfully and the output was verified.
