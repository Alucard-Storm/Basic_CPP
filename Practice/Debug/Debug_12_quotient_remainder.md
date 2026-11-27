# Debug Session 12: Quotient Remainder

**Section A — Basic Programming and Operators**

## Aim

Debug the program below. It is the solution to: *Write a program to calculate the quotient and remainder of two integers.*

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
    int a, b
    cout << "Enter dividend and divisor: ";
    cin >> a >> b;
    cout << a / b << endl
    cout << "Quotient = " << a / b << endl;
    cout << "Remainder = " << a % b << endl;
    return 0;
}
```

**Input**

```text
47 5
```

## Expected Output

```text
Enter dividend and divisor: Quotient = 9
Remainder = 2
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing semicolon (extra statement)

</details>
