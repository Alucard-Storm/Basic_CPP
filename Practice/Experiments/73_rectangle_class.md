# Experiment 73: Rectangle Class

**Section H — Object-Oriented Programming**

## Aim

Write a program to create a `Rectangle` class to calculate area and perimeter.

## Concepts Used

Class with area and perimeter

## Program

```cpp
#include <iostream>
using namespace std;

class Rectangle {
    float l, b;
public:
    void setData(float x, float y) { l = x; b = y; }
    float area() { return l * b; }
    float perimeter() { return 2 * (l + b); }
};

int main() {
    Rectangle r;
    float x, y;
    cout << "Enter length and breadth: ";
    cin >> x >> y;
    r.setData(x, y);
    cout << "Area = " << r.area() << endl;
    cout << "Perimeter = " << r.perimeter() << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
5 3
```

**Output**

```text
Enter length and breadth: Area = 15
Perimeter = 16

```

## Result

The program was executed successfully and the output was verified.
