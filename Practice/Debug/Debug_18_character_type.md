# Debug Session 18: Character Type

**Section B — Conditional Statements and Decision-Making**

## Aim

Debug the program below. It is the solution to: *Write a program to check whether a character is an uppercase letter, lowercase letter, digit, or special character.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int main() {
    char ch;
    cout << "Enter a character: ";
    cin >> ch;
    if (ch >= 'A' && ch <= 'Z')
        cout << "Uppercase letter" << endl;
    else if (ch >= 'a' && ch <= 'z'
        cout << "Lowercase letter" << endl;
    else if (ch >= '0' && ch <= '9')
        cout << "Digit" << endl
    else
        cout << "Special character" << endl;
    return 0;
}
```

**Input**

```text
$
```

## Expected Output

```text
Enter a character: Special character
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing closing parenthesis
2. Missing semicolon

</details>
