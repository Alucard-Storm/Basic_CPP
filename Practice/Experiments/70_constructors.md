# Experiment 70: Constructors

**Section H — Object-Oriented Programming**

## Aim

Write a program to demonstrate default and parameterized constructors.

## Concepts Used

Default and parameterized constructors

## Program

```cpp
#include <iostream>
using namespace std;

class Box {
    int l, b;
public:
    Box() { l = 1; b = 1; }
    Box(int x, int y) { l = x; b = y; }
    void show() { cout << "Length = " << l << ", Breadth = " << b << endl; }
};

int main() {
    Box b1;
    Box b2(4, 7);
    b1.show();
    b2.show();
    return 0;
}
```

## Sample Run

**Output**

```text
Length = 1, Breadth = 1
Length = 4, Breadth = 7

```

## Result

The program was executed successfully and the output was verified.
