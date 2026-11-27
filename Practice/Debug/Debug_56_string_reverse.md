# Debug Session 56: String Reverse

**Section F — Strings**

## Aim

Debug the program below. It is the solution to: *Write a program to reverse a string.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
#include <cstrng>
#include <iomanip>
using namespace std;

int main() {
    char s[100];
    cout << "Enter a string: ";
    cin >> setw(100) >> s;
    int n = strlen(s);
    for (int i = 0, j = n - 1; i < j; i++, j--) {
        char t = s[i]
        s[i] = s[j];
        s[j] = t;
    }
    cout << "Reversed: " << s << endl;
    return 0;
}
```

**Input**

```text
Hello
```

## Expected Output

```text
Enter a string: Reversed: olleH
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Wrong header name
2. Missing semicolon

</details>
