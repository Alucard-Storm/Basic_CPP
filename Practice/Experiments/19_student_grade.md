# Experiment 19: Student Grade

**Section B — Conditional Statements and Decision-Making**

## Aim

Write a program to calculate a student's grade based on marks.

## Concepts Used

`if-else if` ladder

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int marks;
    cout << "Enter marks (0-100): ";
    cin >> marks;
    char grade;
    if (marks >= 90) grade = 'A';
    else if (marks >= 75) grade = 'B';
    else if (marks >= 60) grade = 'C';
    else if (marks >= 40) grade = 'D';
    else grade = 'F';
    cout << "Grade: " << grade << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
82
```

**Output**

```text
Enter marks (0-100): Grade: B

```

## Result

The program was executed successfully and the output was verified.
