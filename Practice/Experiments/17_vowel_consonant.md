# Experiment 17: Vowel Consonant

**Section B — Conditional Statements and Decision-Making**

## Aim

Write a program to check whether a character is a vowel or consonant.

## Concepts Used

`char`, `switch`/`if`

## Program

```cpp
#include <iostream>
#include <cctype>
using namespace std;

int main() {
    char ch;
    cout << "Enter an alphabet: ";
    cin >> ch;
    ch = tolower(ch);
    if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u')
        cout << "Vowel" << endl;
    else
        cout << "Consonant" << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
e
```

**Output**

```text
Enter an alphabet: Vowel

```

## Result

The program was executed successfully and the output was verified.
