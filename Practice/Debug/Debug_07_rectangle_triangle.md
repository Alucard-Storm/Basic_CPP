# Debug Session 7: Rectangle Triangle

**Section A — Basic Programming and Operators**

## Aim

Debug the program below. It is the solution to: *Write a program to calculate the area and perimeter of a rectangle and triangle.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int main() {
    float l, b;
    cout << "Enter length and breadth of rectangle: ";
    cin >> l >> b
    cout << "Rectangle area = " << l * b << ", perimeter = " << 2 * (l + b) << endl;
    float base, height, s1, s2
    cout << "Enter base, height and the two other sides of triangle: ";
    cin >> base >> height >> s1 >> s2;
    cout << "Triangle area = " << 0.5 * base * height << ", perimeter = " << base + s1 + s2 << endl;
    return 0;
}
```

**Input**

```text
4 6
3 4 5 6
```

## Expected Output

```text
Enter length and breadth of rectangle: Rectangle area = 24, perimeter = 20
Enter base, height and the two other sides of triangle: Triangle area = 6, perimeter = 14
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing semicolon

</details>
