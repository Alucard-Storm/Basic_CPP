# Debug Session 5: Swap Without Temp

**Section A — Basic Programming and Operators**

## Aim

Debug the program below. It is the solution to: *Write a program to swap two numbers without using a temporary variable.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int main() 
    int a, b;
    cout << "Enter two numbers: ";
    cin >> a >> b;
    a = a + b:
    b = a - b;
    a = a - b;
    cout << "After swap: a = " << a << ", b = " << b << endl;
    return 0;
}
```

**Input**

```text
10 20
```

## Expected Output

```text
Enter two numbers: After swap: a = 20, b = 10
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Colon instead of semicolon
2. Missing opening brace

</details>
