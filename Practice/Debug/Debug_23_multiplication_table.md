# Debug Session 23: Multiplication Table

**Section C — Loops and Number-Based Problems**

## Aim

Debug the program below. It is the solution to: *Write a program to print the multiplication table of a given number.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int main() {
    int n
    cout << "Enter a number: ";
    cin >> n;
    for (int i = 1, i <= 10; i++)
        cout << n << " x " << i << " = " << n * i << endl;
    return 0;
}
```

**Input**

```text
7
```

## Expected Output

```text
Enter a number: 7 x 1 = 7
7 x 2 = 14
7 x 3 = 21
7 x 4 = 28
7 x 5 = 35
7 x 6 = 42
7 x 7 = 49
7 x 8 = 56
7 x 9 = 63
7 x 10 = 70
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Comma instead of semicolon in `for`
2. Missing semicolon

</details>
