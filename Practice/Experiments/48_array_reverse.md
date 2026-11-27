# Experiment 48: Array Reverse

**Section E — Arrays and Searching/Sorting**

## Aim

Write a program to reverse the elements of an array.

## Concepts Used

Two-index swapping

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
    for (int i = 0, j = n - 1; i < j; i++, j--) {
        int t = a[i];
        a[i] = a[j];
        a[j] = t;
    }
    cout << "Reversed: ";
    for (int i = 0; i < n; i++) cout << a[i] << " ";
    cout << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
5
1 2 3 4 5
```

**Output**

```text
Enter number of elements: Enter elements: Reversed: 5 4 3 2 1 

```

## Result

The program was executed successfully and the output was verified.
