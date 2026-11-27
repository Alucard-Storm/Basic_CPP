# Experiment 66: Pointer Arithmetic Array

**Section G — Pointers and References**

## Aim

Write a program to traverse an array using pointer arithmetic.

## Concepts Used

Pointer increment over an array

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int a[5] = {10, 20, 30, 40, 50};
    int *p = a;
    for (int i = 0; i < 5; i++) {
        cout << "Element " << i << " = " << *p << endl;
        p++;
    }
    return 0;
}
```

## Sample Run

**Output**

```text
Element 0 = 10
Element 1 = 20
Element 2 = 30
Element 3 = 40
Element 4 = 50

```

## Result

The program was executed successfully and the output was verified.
