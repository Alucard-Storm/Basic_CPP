# Experiment 32: Armstrong Number

**Section C — Loops and Number-Based Problems**

## Aim

Write a program to check whether a number is an Armstrong number.

## Concepts Used

`pow()`, digit counting

## Program

```cpp
#include <iostream>
#include <cmath>
using namespace std;

int main() {
    int n, temp, digits = 0, sum = 0;
    cout << "Enter a number: ";
    cin >> n;
    temp = n;
    while (temp > 0) { digits++; temp /= 10; }
    temp = n;
    while (temp > 0) {
        sum += pow(temp % 10, digits);
        temp /= 10;
    }
    if (sum == n)
        cout << n << " is an Armstrong number" << endl;
    else
        cout << n << " is not an Armstrong number" << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
153
```

**Output**

```text
Enter a number: 153 is an Armstrong number

```

## Result

The program was executed successfully and the output was verified.
