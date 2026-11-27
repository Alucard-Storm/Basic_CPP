# Experiment 53: Matrix Multiplication

**Section E — Arrays and Searching/Sorting**

## Aim

Write a program to perform matrix multiplication.

## Concepts Used

Triple nested loops

## Program

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
            for (int k = 0; k < c; k++)
                m[i][j] += a[i][k] * b[k][j];
    cout << "Product:\n";
    for (int i = 0; i < r; i++) {
        for (int j = 0; j < c; j++) cout << m[i][j] << " ";
        cout << endl;
    }
    return 0;
}
```

## Sample Run

**Input**

```text
2 2
1 2
3 4
2 0
1 2
```

**Output**

```text
Enter order of square matrices: Enter first matrix:
Enter second matrix:
Product:
4 4 
10 8 

```

## Result

The program was executed successfully and the output was verified.
