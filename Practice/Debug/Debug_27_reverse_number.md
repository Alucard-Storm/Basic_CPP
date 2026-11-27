# Debug Session 27: Reverse Number

**Section C — Loops and Number-Based Problems**

## Aim

Debug the program below. It is the solution to: *Write a program to reverse the digits of an integer.*

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
    int n, rev = 0;
    cout << "Enter a number: ";
    cin >> n;
    while (n > 0 {
        rev = rev * 10 + n % 10;
        n /= 10
    }
    cout << "Reversed = " << rev << endl;
    return 0;
}
```

**Input**

```text
12345
```

## Expected Output

```text
Enter a number: Reversed = 54321
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing parenthesis
2. Missing semicolon

</details>
