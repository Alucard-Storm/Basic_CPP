# Experiment 45: Array Sum Average

**Section E — Arrays and Searching/Sorting**

## Aim

Write a program to calculate the sum and average of array elements.

## Concepts Used

Accumulating over an array

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n, a[50], sum = 0;
    cout << "Enter number of elements: ";
    cin >> n;
    cout << "Enter elements: ";
    for (int i = 0; i < n; i++) {
        cin >> a[i];
        sum += a[i];
    }
    cout << "Sum = " << sum << endl;
    cout << "Average = " << (float)sum / n << endl;
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
Enter number of elements: Enter elements: Sum = 150
Average = 30

```

## Result

The program was executed successfully and the output was verified.
