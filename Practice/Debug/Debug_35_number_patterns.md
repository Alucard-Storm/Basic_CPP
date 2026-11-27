# Debug Session 35: Number Patterns

**Section C — Loops and Number-Based Problems**

## Aim

Debug the program below. It is the solution to: *Write a program to print number patterns using nested loops.*

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
    cout << "Enter rows: ";
    cin >> n;
    for (int i = 1; i <= n; i++) {
        for (int j = 1; j <= i; j++) cout << j << " "
        cout << endl;
    }
    for (int i = 1; i <= n; i++) 
        for (int j = 1; j <= i; j++) cout << i << " ";
        cout << endl;
    }
    return 0;
}
```

**Input**

```text
5
```

## Expected Output

```text
Enter rows: 1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5 
1 
2 2 
3 3 3 
4 4 4 4 
5 5 5 5 5 
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing brace causes unbalanced braces

</details>
