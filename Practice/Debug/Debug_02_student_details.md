# Debug Session 2: Student Details

**Section A — Basic Programming and Operators**

## Aim

Debug the program below. It is the solution to: *Write a program to read and display a student's name, roll number, and marks.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
#include <string>
using namespace std;

int main() {
    string name;
    int roll;
    flaot marks;
    cout << "Enter name: ";
    cin >> name;
    cout << "Enter roll number: ";
    cin << roll;
    cout << "Enter marks: ";
    cin >> marks;
    cout << "Name: " << name << "\nRoll No: " << roll << "\nMarks: " << marks << endl;
    return 0;
}
```

**Input**

```text
Asha
101
87.5
```

## Expected Output

```text
Enter name: Enter roll number: Enter marks: Name: Asha
Roll No: 101
Marks: 87.5
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Wrong stream operator
2. Misspelled data type

</details>
