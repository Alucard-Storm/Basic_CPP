# Experiment 60: String Concat Compare

**Section F — Strings**

## Aim

Write a program to concatenate and compare two strings.

## Concepts Used

`strcat`, `strcmp`

## Program

```cpp
#include <iostream>
#include <cstring>
#include <iomanip>
using namespace std;

int main() {
    char a[100], b[50];
    cout << "Enter first string: ";
    cin >> setw(50) >> a;
    cout << "Enter second string: ";
    cin >> setw(50) >> b;
    if (strcmp(a, b) == 0)
        cout << "Strings are equal" << endl;
    else
        cout << "Strings are not equal" << endl;
    strcat(a, b);
    cout << "Concatenated: " << a << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
Good
Morning
```

**Output**

```text
Enter first string: Enter second string: Strings are not equal
Concatenated: GoodMorning

```

## Result

The program was executed successfully and the output was verified.
