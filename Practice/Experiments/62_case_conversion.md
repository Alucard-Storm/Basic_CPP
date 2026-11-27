# Experiment 62: Case Conversion

**Section F — Strings**

## Aim

Write a program to convert a string to uppercase and lowercase.

## Concepts Used

`toupper`, `tolower`

## Program

```cpp
#include <iostream>
#include <string>
#include <cctype>
using namespace std;

int main() {
    string s;
    cout << "Enter a string: ";
    getline(cin, s);
    string up = s, low = s;
    for (size_t i = 0; i < s.length(); i++) {
        up[i] = toupper(s[i]);
        low[i] = tolower(s[i]);
    }
    cout << "Uppercase: " << up << "\nLowercase: " << low << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
Hello World
```

**Output**

```text
Enter a string: Uppercase: HELLO WORLD
Lowercase: hello world

```

## Result

The program was executed successfully and the output was verified.
