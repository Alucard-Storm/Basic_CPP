# Debug Session 11: Operators Demo

**Section A — Basic Programming and Operators**

## Aim

Debug the program below. It is the solution to: *Write a program to demonstrate increment, decrement, relational, and logical operators.*

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
    int a = 5, b = 10
    cout << "a++ = " << a++;
    cout << ", now a = " << a << endl;
    cout << "--b = " << --b << endl;
    cout << "a == b : " << (a == b) << endl;
    cout << "a < b : " <<<  << (a < b) << endl;
    cout << "a > 3 && b > 3 : " << (a > 3 && b > 3) << endl;
    cout << "a > 10 || b > 3 : " << (a > 10 || b > 3) << endl;
    cout << "!(a > b) : " << !(a > b) << endl;
    return 0;
}
```

## Expected Output

```text
a++ = 5, now a = 6
--b = 9
a == b : 0
a < b : 1
a > 3 && b > 3 : 1
a > 10 || b > 3 : 1
!(a > b) : 1
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Invalid operator `<<<`

</details>
