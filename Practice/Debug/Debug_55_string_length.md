# Debug Session 55: String Length

**Section F — Strings**

## Aim

Debug the program below. It is the solution to: *Write a program to find the length of a string without using a built-in length function.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
#include <iomanip>
using namespace std;

int main() {
    char s[100]
    int len = 0;
    cout << "Enter a string: ";
    cin >> setw(100) >> s;
    while (s[len] != '\0' len++;
    cout << "Length = " << len << endl;
    return 0;
}
```

**Input**

```text
Programming
```

## Expected Output

```text
Enter a string: Length = 11
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing parenthesis
2. Missing semicolon

</details>
