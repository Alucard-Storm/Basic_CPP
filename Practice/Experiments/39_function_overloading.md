# Experiment 39: Function Overloading

**Section D — Functions and Recursion**

## Aim

Write a program to demonstrate function overloading.

## Concepts Used

Same name, different parameters

## Program

```cpp
#include <iostream>
using namespace std;

int area(int side) { return side * side; }
int area(int l, int b) { return l * b; }
float area(float r) { return 3.14159f * r * r; }

int main() {
    cout << "Square area = " << area(4) << endl;
    cout << "Rectangle area = " << area(4, 5) << endl;
    cout << "Circle area = " << area(2.0f) << endl;
    return 0;
}
```

## Sample Run

**Output**

```text
Square area = 16
Rectangle area = 20
Circle area = 12.5664

```

## Result

The program was executed successfully and the output was verified.
