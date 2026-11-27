# Experiment 55: String Length

**Section F — Strings**

## Aim

Write a program to find the length of a string without using a built-in length function.

## Concepts Used

`char` arrays, null terminator

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    char s[100];
    int len = 0;
    cout << "Enter a string: ";
    cin >> s;
    while (s[len] != '\0') len++;
    cout << "Length = " << len << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
Programming
```

**Output**

```text
Enter a string: Length = 11

```

## Result

The program was executed successfully and the output was verified.
