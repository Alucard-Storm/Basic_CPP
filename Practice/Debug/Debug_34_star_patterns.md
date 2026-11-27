# Debug Session 34: Star Patterns

**Section C — Loops and Number-Based Problems**

## Aim

Debug the program below. It is the solution to: *Write a program to print star patterns, including triangles and pyramids.*

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
    cout << "Right triangle:" << endl;
    for (int i = 1; i <= n; i++) {
        for (int j = 1; j <= i; j++) cout << "* ;
        cout << endl;
    }
    cout << "Pyramid:" << endl;
    for (int i = 1; i <= n; i++) {
        for (int s = 1; s <= n - i; s++ cout << " ";
        for (int j = 1; j <= 2 * i - 1; j++) cout << "*";
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
Enter rows: Right triangle:
* 
* * 
* * * 
* * * * 
* * * * * 
Pyramid:
    *
   ***
  *****
 *******
*********
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Unterminated string
2. Missing parenthesis

</details>
