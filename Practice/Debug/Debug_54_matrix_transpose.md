# Debug Session 54: Matrix Transpose

**Section E — Arrays and Searching/Sorting**

## Aim

Debug the program below. It is the solution to: *Write a program to find the transpose of a matrix.*

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
    int r, c, a[10][10];
    cout << "Enter rows and columns: ";
    cin >> r >> c
    cout << "Enter matrix:\n";
    for (int i = 0; i < r; i++) for (int j = 0; j < c; j++) cin >> a[i][j];
    cout << "Transpose:\n";
    for (int j = 0; j < c; j++) 
        for (int i = 0; i < r; i++) cout << a[i][j] << " ";
        cout << endl;
    }
    return 0;
}
```

**Input**

```text
2 3
1 2 3
4 5 6
```

## Expected Output

```text
Enter rows and columns: Enter matrix:
Transpose:
1 4 
2 5 
3 6 
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing brace (unbalanced)
2. Missing semicolon

</details>
