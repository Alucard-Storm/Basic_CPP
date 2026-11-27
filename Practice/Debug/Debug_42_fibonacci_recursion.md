# Debug Session 42: Fibonacci Recursion

**Section D — Functions and Recursion**

## Aim

Debug the program below. It is the solution to: *Write a program to generate the Fibonacci series using recursion.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int fib(int n) {
    if (n == 0) return 0;
    if (n = = 1) return 1;
    return fib(n - 1) + fib(n - 2;
}

int main() {
    int n;
    cout << "Enter number of terms: ";
    cin >> n;
    for (int i = 0; i < n; i++)
        cout << fib(i) << " ";
    cout << endl;
    return 0;
}
```

**Input**

```text
8
```

## Expected Output

```text
Enter number of terms: 0 1 1 2 3 5 8 13 
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing parenthesis
2. Broken operator

</details>
