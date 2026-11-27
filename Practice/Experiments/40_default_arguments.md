# Experiment 40: Default Arguments

**Section D — Functions and Recursion**

## Aim

Write a program to demonstrate the use of default arguments in functions.

## Concepts Used

Default parameter values

## Program

```cpp
#include <iostream>
using namespace std;

int power(int base, int exp = 2) {
    int result = 1;
    for (int i = 0; i < exp; i++) result *= base;
    return result;
}

int main() {
    cout << "power(5) = " << power(5) << endl;
    cout << "power(2, 10) = " << power(2, 10) << endl;
    return 0;
}
```

## Sample Run

**Output**

```text
power(5) = 25
power(2, 10) = 1024

```

## Result

The program was executed successfully and the output was verified.
