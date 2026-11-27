# Debug Session 61: Character Frequency

**Section F — Strings**

## Aim

Debug the program below. It is the solution to: *Write a program to count the frequency of each character in a string.*

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
    int freq[256] = {0}
    cout << "Enter a string: ";
    cin >> s;
    for (char ch : s) freq[(unsigned char)ch]++;
    for (int i = 0; i < 256; i++)
        if (freq[i] > 0)
            cout << (char)i << " :  << freq[i] << endl;
    return 0;
}
```

**Input**

```text
banana
```

## Expected Output

```text
Enter a string: a : 3
b : 1
n : 2
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Unterminated string

</details>
