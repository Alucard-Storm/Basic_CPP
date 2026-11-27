# Experiment 2: Student Details

**Section A — Basic Programming and Operators**

## Aim

Write a program to read and display a student's name, roll number, and marks.

## Concepts Used

Variables, `cin`, `cout`, `string`

## Program

```cpp
#include <iostream>
#include <string>
using namespace std;

int main() {
    string name;
    int roll;
    float marks;
    cout << "Enter name: ";
    cin >> name;
    cout << "Enter roll number: ";
    cin >> roll;
    cout << "Enter marks: ";
    cin >> marks;
    cout << "Name: " << name << "\nRoll No: " << roll << "\nMarks: " << marks << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
Asha
101
87.5
```

**Output**

```text
Enter name: Enter roll number: Enter marks: Name: Asha
Roll No: 101
Marks: 87.5

```

## Result

The program was executed successfully and the output was verified.
