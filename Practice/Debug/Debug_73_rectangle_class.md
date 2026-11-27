# Debug Session 73: Rectangle Class

**Section H — Object-Oriented Programming**

## Aim

Debug the program below. It is the solution to: *Write a program to create a `Rectangle` class to calculate area and perimeter.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

class Rectangle {
    float l, b;
public:
    void setData(float x, float y) { l = x; b = y; }
    float area() { return l * b; }
    float perimeter() { return 2 * (l + b; }
};

int main() {
    Rectangle r;
    float x, y;
    cout << "Enter length and breadth: ";
    cin >> x >> y;
    r.setDta(x, y);
    cout << "Area = " << r.area() << endl;
    cout << "Perimeter = " << r.perimeter() << endl;
    return 0;
}
```

**Input**

```text
5 3
```

## Expected Output

```text
Enter length and breadth: Area = 15
Perimeter = 16
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing parenthesis
2. Undefined member function (typo)

</details>
