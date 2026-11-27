# Experiment 7: Rectangle Triangle

**Section A — Basic Programming and Operators**

## Aim

Write a program to calculate the area and perimeter of a rectangle and triangle.

## Concepts Used

Area and perimeter formulas

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    float l, b;
    cout << "Enter length and breadth of rectangle: ";
    cin >> l >> b;
    cout << "Rectangle area = " << l * b << ", perimeter = " << 2 * (l + b) << endl;
    float base, height, s1, s2;
    cout << "Enter base, height and the two other sides of triangle: ";
    cin >> base >> height >> s1 >> s2;
    cout << "Triangle area = " << 0.5 * base * height << ", perimeter = " << base + s1 + s2 << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
4 6
3 4 5 6
```

**Output**

```text
Enter length and breadth of rectangle: Rectangle area = 24, perimeter = 20
Enter base, height and the two other sides of triangle: Triangle area = 6, perimeter = 14

```

## Result

The program was executed successfully and the output was verified.
