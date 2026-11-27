# Experiment 8: Temperature Conversion

**Section A — Basic Programming and Operators**

## Aim

Write a program to convert temperature between Celsius and Fahrenheit.

## Concepts Used

Formula conversion, menu choice

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int choice;
    float t;
    cout << "1. Celsius to Fahrenheit\n2. Fahrenheit to Celsius\nChoice: ";
    cin >> choice;
    cout << "Enter temperature: ";
    cin >> t;
    if (choice == 1)
        cout << "Fahrenheit = " << t * 9 / 5 + 32 << endl;
    else
        cout << "Celsius = " << (t - 32) * 5 / 9 << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
1
100
```

**Output**

```text
1. Celsius to Fahrenheit
2. Fahrenheit to Celsius
Choice: Enter temperature: Fahrenheit = 212

```

## Result

The program was executed successfully and the output was verified.
