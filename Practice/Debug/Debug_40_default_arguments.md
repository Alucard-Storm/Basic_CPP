# Debug Session 40: Default Arguments

**Section D — Functions and Recursion**

## Aim

Debug the program below. It is the solution to: *Write a program to demonstrate the use of default arguments in functions.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int power(int base = 2, int exp) {
    int result = 1
    for (int i = 0; i < exp; i++) result *= base;
    return result;
}

int main() {
    cout << "power(5) = " << power(5) << endl;
    cout << "power(2, 10) = " << power(2, 10) << endl;
    return 0;
}
```

## Expected Output

```text
power(5) = 25
power(2, 10) = 1024
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Default argument must be trailing
2. Missing semicolon

</details>
