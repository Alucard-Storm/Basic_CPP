# Experiment 27: Reverse Number

**Section C — Loops and Number-Based Problems**

## Aim

Write a program to reverse the digits of an integer.

## Concepts Used

`while` loop, digit extraction

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n, rev = 0;
    cout << "Enter a number: ";
    cin >> n;
    while (n > 0) {
        rev = rev * 10 + n % 10;
        n /= 10;
    }
    cout << "Reversed = " << rev << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
12345
```

**Output**

```text
Enter a number: Reversed = 54321

```

## Result

The program was executed successfully and the output was verified.
