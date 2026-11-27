# Debug Session 16: Leap Year

**Section B — Conditional Statements and Decision-Making**

## Aim

Debug the program below. It is the solution to: *Write a program to check whether a given year is a leap year.*

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
    int y
    cout << "Enter year: ";
    cin >> y;
    if ((y % 4 == 0 && y % 100 != 0) | y % 400 == 0))
        cout << y << " is a leap year" << endl;
    else
        cout << y << " is not a leap year" << endl;
    return 0;
}
```

**Input**

```text
2024
```

## Expected Output

```text
Enter year: 2024 is a leap year
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Extra parenthesis

</details>
