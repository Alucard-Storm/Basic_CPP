# Debug Session 71: Copy Constructor

**Section H — Object-Oriented Programming**

## Aim

Debug the program below. It is the solution to: *Write a program to demonstrate a copy constructor.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

class Point {
    int x, y;
public:
    Point(int a, int b) { x = a; y = b; }
    Point(const Point &p {
        x = p.x;
        y = p.y
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

## Expected Output

```text
Copy constructor called
(3, 4)
(3, 4)
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing parenthesis
2. Missing semicolon

</details>
