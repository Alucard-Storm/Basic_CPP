# Debug Session 58: String Char Count

**Section F — Strings**

## Aim

Debug the program below. It is the solution to: *Write a program to count vowels, consonants, digits, and spaces in a string.*

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
    int v = 0, c = 0, d = 0, sp = 0;
    cout << "Enter a string: ";
    getline(cin s);
    for (char ch : s {
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

**Input**

```text
Hello World 123
```

## Expected Output

```text
Enter a string: Vowels: 3, Consonants: 7, Digits: 3, Spaces: 2
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing parenthesis
2. Missing comma

</details>
