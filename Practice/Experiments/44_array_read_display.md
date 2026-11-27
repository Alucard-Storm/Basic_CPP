# Experiment 44: Array Read Display

**Section E — Arrays and Searching/Sorting**

## Aim

Write a program to read and display elements of a one-dimensional array.

## Concepts Used

1-D arrays, loops

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n, a[50];
    cout << "Enter number of elements: ";
    cin >> n;
    cout << "Enter elements: ";
    for (int i = 0; i < n; i++) cin >> a[i];
    cout << "Array elements: ";
    for (int i = 0; i < n; i++) cout << a[i] << " ";
    cout << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
5
10 20 30 40 50
```

**Output**

```text
Enter number of elements: Enter elements: Array elements: 10 20 30 40 50 

```

## Result

The program was executed successfully and the output was verified.
