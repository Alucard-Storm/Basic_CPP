# Experiment 47: Even Odd Count

**Section E — Arrays and Searching/Sorting**

## Aim

Write a program to count even and odd elements in an array.

## Concepts Used

Counting with conditions

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n, a[50], even = 0, odd = 0;
    cout << "Enter number of elements: ";
    cin >> n;
    cout << "Enter elements: ";
    for (int i = 0; i < n; i++) {
        cin >> a[i];
        if (a[i] % 2 == 0) even++;
        else odd++;
    }
    cout << "Even = " << even << ", Odd = " << odd << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
6
1 2 3 4 5 6
```

**Output**

```text
Enter number of elements: Enter elements: Even = 3, Odd = 3

```

## Result

The program was executed successfully and the output was verified.
