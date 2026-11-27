# Experiment 51: Merge Arrays

**Section E — Arrays and Searching/Sorting**

## Aim

Write a program to merge two arrays into a third array.

## Concepts Used

Combining arrays

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n1, n2, a[50], b[50], c[100];
    cout << "Size of first array: ";
    cin >> n1;
    for (int i = 0; i < n1; i++) cin >> a[i];
    cout << "Size of second array: ";
    cin >> n2;
    for (int i = 0; i < n2; i++) cin >> b[i];
    for (int i = 0; i < n1; i++) c[i] = a[i];
    for (int i = 0; i < n2; i++) c[n1 + i] = b[i];
    cout << "Merged array: ";
    for (int i = 0; i < n1 + n2; i++) cout << c[i] << " ";
    cout << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
3
1 3 5
3
2 4 6
```

**Output**

```text
Size of first array: Size of second array: Merged array: 1 3 5 2 4 6 

```

## Result

The program was executed successfully and the output was verified.
