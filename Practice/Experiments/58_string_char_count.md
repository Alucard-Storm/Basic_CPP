# Experiment 58: String Char Count

**Section F — Strings**

## Aim

Write a program to count vowels, consonants, digits, and spaces in a string.

## Concepts Used

`getline`, character tests

## Program

```cpp
#include <iostream>
#include <string>
#include <cctype>
using namespace std;

int main() {
    string s;
    int v = 0, c = 0, d = 0, sp = 0;
    cout << "Enter a string: ";
    getline(cin, s);
    for (char ch : s) {
        char l = tolower(ch);
        if (l == 'a' || l == 'e' || l == 'i' || l == 'o' || l == 'u') v++;
        else if (l >= 'a' && l <= 'z') c++;
        else if (ch >= '0' && ch <= '9') d++;
        else if (ch == ' ') sp++;
    }
    cout << "Vowels: " << v << ", Consonants: " << c << ", Digits: " << d << ", Spaces: " << sp << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
Hello World 123
```

**Output**

```text
Enter a string: Vowels: 3, Consonants: 7, Digits: 3, Spaces: 2

```

## Result

The program was executed successfully and the output was verified.
