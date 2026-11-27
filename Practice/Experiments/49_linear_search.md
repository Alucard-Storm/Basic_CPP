# Experiment 49: Linear Search

**Section E — Arrays and Searching/Sorting**

## Aim

Write a program to search for an element using linear search.

## Concepts Used

Searching with a flag

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n, a[50], key, pos = -1;
    cout << "Enter number of elements: ";
    cin >> n;
    cout << "Enter elements: ";
    for (int i = 0; i < n; i++) cin >> a[i];
    cout << "Enter element to search: ";
    cin >> key;
    for (int i = 0; i < n; i++) {
        if (a[i] == key) { pos = i; break; }
    }
    if (pos != -1)
        cout << "Found at position " << pos + 1 << endl;
    else
        cout << "Not found" << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
5
10 20 30 40 50
30
```

**Output**

```text
Enter number of elements: Enter elements: Enter element to search: Found at position 3

```

## Result

The program was executed successfully and the output was verified.
