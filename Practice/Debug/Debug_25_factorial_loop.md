# Debug Session 25: Factorial Loop

**Section C — Loops and Number-Based Problems**

## Aim

Debug the program below. It is the solution to: *Write a program to calculate the factorial of a number using a loop.*

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
    int n;
    long long fact = 1
    cout << "Enter a number: ";
    cin >> n;
    for (int i = 2; i <= n; i++)
        fact * = i;
    cout << "Factorial = " << fact << endl;
    return 0;
}
```

**Input**

```text
6
```

## Expected Output

```text
Enter a number: Factorial = 720
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Broken compound operator

</details>
