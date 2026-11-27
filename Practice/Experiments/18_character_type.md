# Experiment 18: Character Type

**Section B — Conditional Statements and Decision-Making**

## Aim

Write a program to check whether a character is an uppercase letter, lowercase letter, digit, or special character.

## Concepts Used

Character classification using ASCII ranges

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    char ch;
    cout << "Enter a character: ";
    cin >> ch;
    if (ch >= 'A' && ch <= 'Z')
        cout << "Uppercase letter" << endl;
    else if (ch >= 'a' && ch <= 'z')
        cout << "Lowercase letter" << endl;
    else if (ch >= '0' && ch <= '9')
        cout << "Digit" << endl;
    else
        cout << "Special character" << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
$
```

**Output**

```text
Enter a character: Special character

```

## Result

The program was executed successfully and the output was verified.
