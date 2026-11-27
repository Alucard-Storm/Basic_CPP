# Debug Session 39: Function Overloading

**Section D — Functions and Recursion**

## Aim

Debug the program below. It is the solution to: *Write a program to demonstrate function overloading.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int area(int side) { return side * side; }
int area(int l, int b { return l * b; }
float area(float r) { return 3.14159f * r * r; }

int main() {
    cout << "Square area = " << area(4) << endl
    cout << "Rectangle area = " << area(4, 5) << endl;
    cout << "Circle area = " << area(2.0f) << endl;
    return 0;
}
```

## Expected Output

```text
Square area = 16
Rectangle area = 20
Circle area = 12.5664
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing parenthesis in redefinition
2. Missing semicolon

</details>
