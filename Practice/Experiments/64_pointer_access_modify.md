# Experiment 64: Pointer Access Modify

**Section G — Pointers and References**

## Aim

Write a program to access and modify a variable using a pointer.

## Concepts Used

Pointer declaration, dereferencing

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int a = 10;
    int *p = &a;
    cout << "a = " << a << ", *p = " << *p << endl;
    *p = 25;
    cout << "After modification through pointer, a = " << a << endl;
    return 0;
}
```

## Sample Run

**Output**

```text
a = 10, *p = 10
After modification through pointer, a = 25

```

## Result

The program was executed successfully and the output was verified.
