# Debug Session 21: Triangle Validity

**Section B — Conditional Statements and Decision-Making**

## Aim

Debug the program below. It is the solution to: *Write a program to check whether three sides can form a valid triangle and determine its type.*

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
    float a, b, c;
    cout << "Enter three sides: ";
    cin >> a >> b >> c;
    if (a + b > c && b + c > a && a + c > b) {
        if (a == b && b == c
            cout << "Equilateral triangle" << endl;
        else if (a == b || b == c || a == c)
            cout << "Isosceles triangle" << endl;
        else
            cout << "Scalene triangle" << endl;
    } else
        cout << "Not a valid triangle" << endl;
    }
    return 0;
}
```

**Input**

```text
5 5 8
```

## Expected Output

```text
Enter three sides: Isosceles triangle
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing opening brace after else
2. Missing parenthesis

</details>
