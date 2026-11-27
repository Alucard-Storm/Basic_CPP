# Experiment 52: Matrix Add Subtract

**Section E — Arrays and Searching/Sorting**

## Aim

Write a program to perform matrix addition and subtraction.

## Concepts Used

2-D arrays

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int r, c, a[10][10], b[10][10];
    cout << "Enter rows and columns: ";
    cin >> r >> c;
    cout << "Enter first matrix:\n";
    for (int i = 0; i < r; i++) for (int j = 0; j < c; j++) cin >> a[i][j];
    cout << "Enter second matrix:\n";
    for (int i = 0; i < r; i++) for (int j = 0; j < c; j++) cin >> b[i][j];
    cout << "Sum:\n";
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

## Sample Run

**Input**

```text
2 2
1 2
3 4
5 6
7 8
```

**Output**

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

## Result

The program was executed successfully and the output was verified.
