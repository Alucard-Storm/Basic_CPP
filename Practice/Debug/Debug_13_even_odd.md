# Debug Session 13: Even Odd

**Section B — Conditional Statements and Decision-Making**

## Aim

Debug the program below. It is the solution to: *Write a program to check whether a number is even or odd.*

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
    int n;
    cout << "Enter a number: ";
    cin >> n;
    if (n % 2 = 0)
        cout << n << " is even" << endl;
    esle
        cout << n << " is odd" << endl;
    return 0;
}
```

**Input**

```text
7
```

## Expected Output

```text
Enter a number: 7 is odd
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Assignment instead of comparison (lvalue error)
2. Misspelled keyword

</details>
