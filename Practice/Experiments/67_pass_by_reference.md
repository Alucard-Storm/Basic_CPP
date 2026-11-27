# Experiment 67: Pass By Reference

**Section G — Pointers and References**

## Aim

Write a program to pass arguments to a function using references.

## Concepts Used

Reference parameters

## Program

```cpp
#include <iostream>
using namespace std;

void update(int &a, int &b) {
    a += 5;
    b *= 2;
}

int main() {
    int x, y;
    cout << "Enter two numbers: ";
    cin >> x >> y;
    update(x, y);
    cout << "x = " << x << ", y = " << y << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
5 9
```

**Output**

```text
Enter two numbers: x = 10, y = 18

```

## Result

The program was executed successfully and the output was verified.
