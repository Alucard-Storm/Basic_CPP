# Debug Session 43: Call By Value Reference

**Section D — Functions and Recursion**

## Aim

Debug the program below. It is the solution to: *Write a program to demonstrate the difference between call by value and call by reference.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

void byValue(int x) { x = x + 10; }
void byRef(int &x) { x = x + 10 }

int main() {
    int a = 5;
    byValue(a;
    cout << "After call by value: " << a << endl;
    byRef(a);
    cout << "After call by reference: " << a << endl;
    return 0;
}
```

## Expected Output

```text
After call by value: 5
After call by reference: 15
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing parenthesis

</details>
