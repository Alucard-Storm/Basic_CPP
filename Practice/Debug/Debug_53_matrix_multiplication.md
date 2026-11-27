# Debug Session 53: Matrix Multiplication

**Section E — Arrays and Searching/Sorting**

## Aim

Debug the program below. It is the solution to: *Write a program to perform matrix multiplication.*

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
    int r, c, a[10][10], b[10][10], m[10][10] = {0};
    cout << "Enter order of square matrices: ";
    cin >> r >> c;
    cout << "Enter first matrix:\n";
    for (int i = 0; i < r; i++) for (int j = 0; j < c; j++) cin >> a[i][j];
    cout << "Enter second matrix:\n";
    for (int i = 0; i < r; i++) for (int j = 0; j < c; j++) cin >> b[i][j];
    for (int i = 0; i < r; i++)
        for (int j = 0; j < c; j++)
            for (int k = 0; k < c; k++
                m[i][j] += a[i][k] * b[k][j]
    cout << "Product:\n";
    for (int i = 0; i < r; i++) {
        for (int j = 0; j < c; j++) cout << m[i][j] << " ";
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
2 0
1 2
```

## Expected Output

```text
Enter order of square matrices: Enter first matrix:
Enter second matrix:
Product:
4 4 
10 8 
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing parenthesis

</details>
