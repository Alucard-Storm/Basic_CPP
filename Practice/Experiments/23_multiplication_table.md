# Experiment 23: Multiplication Table

**Section C — Loops and Number-Based Problems**

## Aim

Write a program to print the multiplication table of a given number.

## Concepts Used

`for` loop

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter a number: ";
    cin >> n;
    for (int i = 1; i <= 10; i++)
        cout << n << " x " << i << " = " << n * i << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
7
```

**Output**

```text
Enter a number: 7 x 1 = 7
7 x 2 = 14
7 x 3 = 21
7 x 4 = 28
7 x 5 = 35
7 x 6 = 42
7 x 7 = 49
7 x 8 = 56
7 x 9 = 63
7 x 10 = 70

```

## Result

The program was executed successfully and the output was verified.
