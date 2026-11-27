# Experiment 50: Array Sorting

**Section E — Arrays and Searching/Sorting**

## Aim

Write a program to sort an array in ascending and descending order.

## Concepts Used

Bubble sort

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
    for (int i = 0; i < n - 1; i++)
        for (int j = 0; j < n - i - 1; j++)
            if (a[j] > a[j + 1]) { int t = a[j]; a[j] = a[j + 1]; a[j + 1] = t; }
    cout << "Ascending: ";
    for (int i = 0; i < n; i++) cout << a[i] << " ";
    cout << "\nDescending: ";
    for (int i = n - 1; i >= 0; i--) cout << a[i] << " ";
    cout << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
5
40 10 50 20 30
```

**Output**

```text
Enter number of elements: Enter elements: Ascending: 10 20 30 40 50 
Descending: 50 40 30 20 10 

```

## Result

The program was executed successfully and the output was verified.
