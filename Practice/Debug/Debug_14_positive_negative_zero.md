# Debug Session 14: Positive Negative Zero

**Section B — Conditional Statements and Decision-Making**

## Aim

Debug the program below. It is the solution to: *Write a program to check whether a number is positive, negative, or zero.*

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
    if (n > 0)
        cout << "Positive" << endl;
    else if n < 0)
        cout << "Negative" << endl;
    else
        cout << "Zero << endl;
    return 0;
}
```

**Input**

```text
-4
```

## Expected Output

```text
Enter a number: Negative
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing parenthesis
2. Missing closing quote

</details>
