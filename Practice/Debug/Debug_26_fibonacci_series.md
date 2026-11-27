# Debug Session 26: Fibonacci Series

**Section C — Loops and Number-Based Problems**

## Aim

Debug the program below. It is the solution to: *Write a program to generate the Fibonacci series up to \\(N\\) terms.*

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
    int n, a = 0, b = 1;
    cout << "Enter number of terms: ";
    cin >> n;
    for (int i = 1; i <= n; i++) {
        cout << a << " ";
        int next = a + b
        a = b;
        b = next;
    }
    cout << endl;
    }
    return 0;
}
```

**Input**

```text
10
```

## Expected Output

```text
Enter number of terms: 0 1 1 2 3 5 8 13 21 34 
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Extra closing brace

</details>
