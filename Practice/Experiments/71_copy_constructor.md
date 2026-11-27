# Experiment 71: Copy Constructor

**Section H — Object-Oriented Programming**

## Aim

Write a program to demonstrate a copy constructor.

## Concepts Used

Copying objects

## Program

```cpp
#include <iostream>
using namespace std;

class Point {
    int x, y;
public:
    Point(int a, int b) { x = a; y = b; }
    Point(const Point &p) {
        x = p.x;
        y = p.y;
        cout << "Copy constructor called" << endl;
    }
    void show() { cout << "(" << x << ", " << y << ")" << endl; }
};

int main() {
    Point p1(3, 4);
    Point p2 = p1;
    p1.show();
    p2.show();
    return 0;
}
```

## Sample Run

**Output**

```text
Copy constructor called
(3, 4)
(3, 4)

```

## Result

The program was executed successfully and the output was verified.
