# Debug Session 17: Vowel Consonant

**Section B — Conditional Statements and Decision-Making**

## Aim

Debug the program below. It is the solution to: *Write a program to check whether a character is a vowel or consonant.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
#include <cctype>
using namespace std;

int main() {
    chr ch;
    cout << "Enter an alphabet: ";
    cin >> ch;
    ch = tolower(ch);
    if (ch == 'a' || ch == "e' || ch == 'i' || ch == 'o' || ch == 'u')
        cout << "Vowel" << endl;
    else
        cout << "Consonant" << endl;
    return 0;
}
```

**Input**

```text
e
```

## Expected Output

```text
Enter an alphabet: Vowel
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Mismatched quote
2. Misspelled data type

</details>
