# Experiment 65: Swap Using Pointers

**Section G — Pointers and References**

## Aim

Write a program to swap two numbers using pointers.

## Concepts Used

Pointer parameters

## Program

```cpp
#include <iostream>
using namespace std;

void swapNum(int *x, int *y) {
    int t = *x;
    *x = *y;
    *y = t;
}

int main() {
    int a, b;
    cout << "Enter two numbers: ";
    cin >> a >> b;
    swapNum(&a, &b);
    cout << "After swap: a = " << a << ", b = " << b << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
5 9
```

**Output**

```text
Enter two numbers: After swap: a = 9, b = 5

```

## Result

The program was executed successfully and the output was verified.
