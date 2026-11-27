# Debug Session 52: Matrix Add Subtract

**Section E — Arrays and Searching/Sorting**

## Aim

Debug the program below. It is the solution to: *Write a program to perform matrix addition and subtraction.*

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
    int r, c, a[10][10], b[10,10];
    cout << "Enter rows and columns: ";
    cin >> r >> c;
    cout << "Enter first matrix:\n";
    for (int i = 0; i < r; i++) for (int j = 0; j < c; j++) cin >> a[i][j];
    cout << "Enter second matrix:\n";
    for (int i = 0; i < r; i++) for (int j = 0; j < c; j++) cin >> b[i][j];
    cout << "Sum:\n;
    for (int i = 0; i < r; i++) {
        for (int j = 0; j < c; j++) cout << a[i][j] + b[i][j] << " ";
        cout << endl;
    }
    cout << "Difference:\n";
    for (int i = 0; i < r; i++) {
        for (int j = 0; j < c; j++) cout << a[i][j] - b[i][j] << " ";
        cout << endl;
    }
    return 0;
}
```

**Input**

```text
2 2
1 2
3 4
5 6
7 8
```

## Expected Output

```text
Enter rows and columns: Enter first matrix:
Enter second matrix:
Sum:
6 8 
10 12 
Difference:
-4 -4 
-4 -4 
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Wrong 2-D array syntax
2. Unterminated string

</details>
