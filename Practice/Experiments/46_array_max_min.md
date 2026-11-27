# Experiment 46: Array Max Min

**Section E — Arrays and Searching/Sorting**

## Aim

Write a program to find the largest and smallest elements in an array.

## Concepts Used

Finding extremes

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
    int mx = a[0], mn = a[0];
    for (int i = 1; i < n; i++) {
        if (a[i] > mx) mx = a[i];
        if (a[i] < mn) mn = a[i];
    }
    cout << "Largest = " << mx << "\nSmallest = " << mn << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
5
23 7 41 15 9
```

**Output**

```text
Enter number of elements: Enter elements: Largest = 41
Smallest = 7

```

## Result

The program was executed successfully and the output was verified.
