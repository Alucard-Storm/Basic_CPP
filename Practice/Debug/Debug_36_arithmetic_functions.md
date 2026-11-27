# Debug Session 36: Arithmetic Functions

**Section D — Functions and Recursion**

## Aim

Debug the program below. It is the solution to: *Write a program to perform arithmetic operations using user-defined functions.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int add(int a, int b) { return a + b; }
int sub(int a, b) { return a - b; }
int mul(int a, int b) { return a * b }
float divide(int a, int b) { return (float)a / b; }

int main() {
    int x, y;
    cout << "Enter two numbers: ";
    cin >> x >> y;
    cout << "Add = " << add(x, y) << endl;
    cout << "Sub = " << sub(x, y) << endl;
    cout << "Mul = " << mul(x, y) << endl;
    cout << "Div = " << divide(x, y) << endl;
    return 0;
}
```

**Input**

```text
9 3
```

## Expected Output

```text
Enter two numbers: Add = 12
Sub = 6
Mul = 27
Div = 3
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing parameter type
2. Missing semicolon

</details>
