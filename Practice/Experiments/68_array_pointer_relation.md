# Experiment 68: Array Pointer Relation

**Section G — Pointers and References**

## Aim

Write a program to demonstrate the relationship between arrays and pointers.

## Concepts Used

Array name as a pointer

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int a[4] = {1, 2, 3, 4};
    int *p = a;
    for (int i = 0; i < 4; i++) {
        cout << "a[" << i << "] = " << a[i] << ", *(a+" << i << ") = " << *(a + i)
             << ", p[" << i << "] = " << p[i] << endl;
    }
    return 0;
}
```

## Sample Run

**Output**

```text
a[0] = 1, *(a+0) = 1, p[0] = 1
a[1] = 2, *(a+1) = 2, p[1] = 2
a[2] = 3, *(a+2) = 3, p[2] = 3
a[3] = 4, *(a+3) = 4, p[3] = 4

```

## Result

The program was executed successfully and the output was verified.
