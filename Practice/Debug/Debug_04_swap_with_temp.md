# Debug Session 4: Swap With Temp

**Section A — Basic Programming and Operators**

## Aim

Debug the program below. It is the solution to: *Write a program to swap two numbers using a temporary variable.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int main() {
    int a, b temp;
    cout << "Enter two numbers: ";
    cin >> a >> b;
    temp = a;
    a = b;
    b = tmp;
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

1. Comma missing in declaration
2. Undeclared variable

</details>
