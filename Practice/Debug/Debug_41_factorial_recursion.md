# Debug Session 41: Factorial Recursion

**Section D — Functions and Recursion**

## Aim

Debug the program below. It is the solution to: *Write a program to calculate factorial using recursion.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

long long fact(int n) 
    if (n <= 1) return 1;
    return n * fact(n - 1)
}

int main() {
    int n;
    cout << "Enter a number: ";
    cin >> n;
    cout << n << "! = " << fact(n) << endl;
    return 0;
}
```

**Input**

```text
5
```

## Expected Output

```text
Enter a number: 5! = 120
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing opening brace

</details>
