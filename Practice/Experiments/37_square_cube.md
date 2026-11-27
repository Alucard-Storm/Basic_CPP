# Experiment 37: Square Cube

**Section D — Functions and Recursion**

## Aim

Write a program to calculate the square and cube of a number using functions.

## Concepts Used

Functions with parameters

## Program

```cpp
#include <iostream>
using namespace std;

int square(int n) { return n * n; }
int cube(int n) { return n * n * n; }

int main() {
    int n;
    cout << "Enter a number: ";
    cin >> n;
    cout << "Square = " << square(n) << endl;
    cout << "Cube = " << cube(n) << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
4
```

**Output**

```text
Enter a number: Square = 16
Cube = 64

```

## Result

The program was executed successfully and the output was verified.
