# Experiment 4: Swap With Temp

**Section A — Basic Programming and Operators**

## Aim

Write a program to swap two numbers using a temporary variable.

## Concepts Used

Swapping with a temporary variable

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int a, b, temp;
    cout << "Enter two numbers: ";
    cin >> a >> b;
    temp = a;
    a = b;
    b = temp;
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
