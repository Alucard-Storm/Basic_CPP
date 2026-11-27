# Experiment 5: Swap Without Temp

**Section A — Basic Programming and Operators**

## Aim

Write a program to swap two numbers without using a temporary variable.

## Concepts Used

Swapping using arithmetic

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int a, b;
    cout << "Enter two numbers: ";
    cin >> a >> b;
    a = a + b;
    b = a - b;
    a = a - b;
    cout << "After swap: a = " << a << ", b = " << b << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
10 20
```

**Output**

```text
Enter two numbers: After swap: a = 20, b = 10

```

## Result

The program was executed successfully and the output was verified.
