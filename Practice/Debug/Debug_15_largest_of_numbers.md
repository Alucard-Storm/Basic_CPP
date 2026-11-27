# Debug Session 15: Largest Of Numbers

**Section B — Conditional Statements and Decision-Making**

## Aim

Debug the program below. It is the solution to: *Write a program to find the largest of two and three numbers.*

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
    int a, b, c;
    cout << "Enter three numbers: ";
    cin >> a >> b >> c;
    cout << "Largest of " << a << " and " << b << " is " << (a > b ? a b) << endl;
    if (a >= b & & a >= c)
        cout << "Largest of three: " << a << endl;
    else if (b >= a && b >= c)
        cout << "Largest of three: " << b << endl;
    else
        cout << "Largest of three: " << c << endl;
    return 0;
}
```

**Input**

```text
12 45 30
```

## Expected Output

```text
Enter three numbers: Largest of 12 and 45 is 45
Largest of three: 45
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Malformed ternary operator
2. Broken `&&` operator

</details>
