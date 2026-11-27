# Experiment 54: Matrix Transpose

**Section E — Arrays and Searching/Sorting**

## Aim

Write a program to find the transpose of a matrix.

## Concepts Used

Swapping row/column indices

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int r, c, a[10][10];
    cout << "Enter rows and columns: ";
    cin >> r >> c;
    cout << "Enter matrix:\n";
    for (int i = 0; i < r; i++) for (int j = 0; j < c; j++) cin >> a[i][j];
    cout << "Transpose:\n";
    for (int j = 0; j < c; j++) {
        for (int i = 0; i < r; i++) cout << a[i][j] << " ";
        cout << endl;
    }
    return 0;
}
```

## Sample Run

**Input**

```text
2 3
1 2 3
4 5 6
```

**Output**

```text
Enter rows and columns: Enter matrix:
Transpose:
1 4 
2 5 
3 6 

```

## Result

The program was executed successfully and the output was verified.
