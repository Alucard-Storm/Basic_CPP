# Debug Session 70: Constructors

**Section H — Object-Oriented Programming**

## Aim

Debug the program below. It is the solution to: *Write a program to demonstrate default and parameterized constructors.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

class Box {
    int l, b;
public:
    Box() { l = 1; b = 1 }
    Box(int x, int y) { l = x; b = y; }
    void show() { cout << "Length = " << l << ", Breadth = " << b << endl; }
};

int main() {
    Box b1;
    Box b2(4, 7)
    b1.show();
    b2.show();
    return 0;
}
```

## Expected Output

```text
Length = 1, Breadth = 1
Length = 4, Breadth = 7
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing semicolon

</details>
