# Debug Session 28: Digit Sum Product

**Section C — Loops and Number-Based Problems**

## Aim

Debug the program below. It is the solution to: *Write a program to calculate the sum and product of the digits of a number.*

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
    int n, sum = 0, prod = 1;
    cout << "Enter a number: ";
    cin >> n;
    while (n > 0) {
        int d = n % 10
        sum += ;
        prod *= d;
        n /= 10;
    }
    cout << "Sum of digits = " << sum << "\nProduct of digits = " << prod << endl;
    return 0;
}
```

**Input**

```text
234
```

## Expected Output

```text
Enter a number: Sum of digits = 9
Product of digits = 24
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing operand

</details>
