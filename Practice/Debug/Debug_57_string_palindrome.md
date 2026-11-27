# Debug Session 57: String Palindrome

**Section F — Strings**

## Aim

Debug the program below. It is the solution to: *Write a program to check whether a string is a palindrome.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

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
    bool pal = true
    for (int i = 0; i < n / 2; i++)
        if (s[i] != s[n - 1 - i]) { pal = false; break; }
    cout << s << (pal ? " is a palindrome" " is not a palindrome") << endl;
    return 0;
}
```

**Input**

```text
madam
```

## Expected Output

```text
Enter a string: madam is a palindrome
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing `:` in ternary

</details>
