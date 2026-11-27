# Debug Session 22: Electricity Bill

**Section B — Conditional Statements and Decision-Making**

## Aim

Debug the program below. It is the solution to: *Write a program to calculate an electricity bill using slab-based charges.*

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
    int units;
    float bill;
    cout << "Enter units consumed: ";
    cin >> units;
    if (units <= 100)
        bill = units * 1.5
    else if (units <= 200
        bill = 100 * 1.5 + (units - 100) * 2.5;
    else
        bill = 100 * 1.5 + 100 * 2.5 + (units - 200) * 4;
    cout << "Electricity bill = Rs. " << bill << endl;
    return 0;
}
```

**Input**

```text
250
```

## Expected Output

```text
Enter units consumed: Electricity bill = Rs. 600
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing parenthesis

</details>
