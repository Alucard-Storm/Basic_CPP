# Experiment 10: Days To Years Weeks

**Section A — Basic Programming and Operators**

## Aim

Write a program to convert a given number of days into years, weeks, and days.

## Concepts Used

Integer division and modulus

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int days;
    cout << "Enter number of days: ";
    cin >> days;
    int years = days / 365;
    int rem = days % 365;
    int weeks = rem / 7;
    int d = rem % 7;
    cout << years << " years, " << weeks << " weeks, " << d << " days" << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
800
```

**Output**

```text
Enter number of days: 2 years, 10 weeks, 0 days

```

## Result

The program was executed successfully and the output was verified.
