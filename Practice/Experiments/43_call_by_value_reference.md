# Experiment 43: Call By Value Reference

**Section D — Functions and Recursion**

## Aim

Write a program to demonstrate the difference between call by value and call by reference.

## Concepts Used

Value vs reference parameters

## Program

```cpp
#include <iostream>
using namespace std;

void byValue(int x) { x = x + 10; }
void byRef(int &x) { x = x + 10; }

int main() {
    int a = 5;
    byValue(a);
    cout << "After call by value: " << a << endl;
    byRef(a);
    cout << "After call by reference: " << a << endl;
    return 0;
}
```

## Sample Run

**Output**

```text
After call by value: 5
After call by reference: 15

```

## Result

The program was executed successfully and the output was verified.
