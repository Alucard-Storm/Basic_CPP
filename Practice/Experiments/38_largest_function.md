# Experiment 38: Largest Function

**Section D — Functions and Recursion**

## Aim

Write a program to find the largest of three numbers using a function.

## Concepts Used

Function returning the max

## Program

```cpp
#include <iostream>
using namespace std;

int largest(int a, int b, int c) {
    if (a >= b && a >= c) return a;
    if (b >= c) return b;
    return c;
}

int main() {
    int a, b, c;
    cout << "Enter three numbers: ";
    cin >> a >> b >> c;
    cout << "Largest = " << largest(a, b, c) << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
3 9 5
```

**Output**

```text
Enter three numbers: Largest = 9

```

## Result

The program was executed successfully and the output was verified.
