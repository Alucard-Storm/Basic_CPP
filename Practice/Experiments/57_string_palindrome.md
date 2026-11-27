# Experiment 57: String Palindrome

**Section F — Strings**

## Aim

Write a program to check whether a string is a palindrome.

## Concepts Used

Comparing ends of a string

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
    bool pal = true;
    for (int i = 0; i < n / 2; i++)
        if (s[i] != s[n - 1 - i]) { pal = false; break; }
    cout << s << (pal ? " is a palindrome" : " is not a palindrome") << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
madam
```

**Output**

```text
Enter a string: madam is a palindrome

```

## Result

The program was executed successfully and the output was verified.
