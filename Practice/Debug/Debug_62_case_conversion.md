# Debug Session 62: Case Conversion

**Section F — Strings**

## Aim

Debug the program below. It is the solution to: *Write a program to convert a string to uppercase and lowercase.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
#include <string>
#include <cctype>
using namespace std;

int main() {
    string s;
    cout << "Enter a string: ";
    getline(cin, s);
    string up = s, low = s
    for (size_t i = 0; i < s.length(); i++) {
        up[i] = toupper(s[i];
        low[i] = tolower(s[i]);
    }
    cout << "Uppercase: " << up << "\nLowercase: " << low << endl;
    return 0;
}
```

**Input**

```text
Hello World
```

## Expected Output

```text
Enter a string: Uppercase: HELLO WORLD
Lowercase: hello world
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing parenthesis

</details>
