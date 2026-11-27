# Experiment 56: String Reverse

**Section F — Strings**

## Aim

Write a program to reverse a string.

## Concepts Used

Reversing a string

## Program

```cpp
#include <iostream>
#include <cstring>
#include <iomanip>
using namespace std;

int main() {
    char s[100];
    cout << "Enter a string: ";
    cin >> setw(100) >> s;
    int n = strlen(s);
    for (int i = 0, j = n - 1; i < j; i++, j--) {
        char t = s[i];
        s[i] = s[j];
        s[j] = t;
    }
    cout << "Reversed: " << s << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
Hello
```

**Output**

```text
Enter a string: Reversed: olleH

```

## Result

The program was executed successfully and the output was verified.
