# Debug Session 29: Palindrome Number

**Section C — Loops and Number-Based Problems**

## Aim

Debug the program below. It is the solution to: *Write a program to check whether a number is a palindrome.*

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
    int n, original, rev = 0;
    cout << "Enter a number: ";
    cin >> n;
    orignal = n;
    while (n > 0) {
        rev = rev * 10 + n % 10;
        n /= 10;
    }
    if (rev == original
        cout << original << " is a palindrome" << endl;
    else
        cout << original << " is not a palindrome" << endl;
    return 0;
}
```

**Input**

```text
1221
```

## Expected Output

```text
Enter a number: 1221 is a palindrome
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Undeclared variable (typo)
2. Missing parenthesis

</details>
