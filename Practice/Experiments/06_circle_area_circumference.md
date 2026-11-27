# Experiment 6: Circle Area Circumference

**Section A — Basic Programming and Operators**

## Aim

Write a program to calculate the area and circumference of a circle.

## Concepts Used

Constants, floating-point arithmetic

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    const float PI = 3.14159;
    float r;
    cout << "Enter radius: ";
    cin >> r;
    cout << "Area = " << PI * r * r << endl;
    cout << "Circumference = " << 2 * PI * r << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
5
```

**Output**

```text
Enter radius: Area = 78.5397
Circumference = 31.4159

```

## Result

The program was executed successfully and the output was verified.
