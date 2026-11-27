# Debug Session 59: Word Count

**Section F — Strings**

## Aim

Debug the program below. It is the solution to: *Write a program to count the number of words in a sentence.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
#include <string>
using namespace std;

int main() {
    string s;
    cout << "Enter a sentence: ";
    getline(cin, s);
    int words = 0
    bool inWord = false;
    for (char ch : s) {
        if (ch != ' ' && !inWord) { inWord = true; words++; 
        else if (ch == ' ') inWord = false;
    }
    cout << "Number of words = " << words << endl;
    return 0;
}
```

**Input**

```text
I love C++ programming
```

## Expected Output

```text
Enter a sentence: Number of words = 4
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing closing brace

</details>
