# Debug Session 19: Student Grade

**Section B — Conditional Statements and Decision-Making**

## Aim

Debug the program below. It is the solution to: *Write a program to calculate a student's grade based on marks.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int main() {
    int marks;
    cout << "Enter marks (0-100): ";
    cin >> marks;
    char grade
    if (marks >= 90) grade = 'A';
    else if (marks >= 75) grade = 'B'
    else if (marks >= 60) grade = 'C';
    else if (marks >= 40) grade = 'D';
    else grade = 'F';
    cout << "Grade: " << grade << endl;
    return 0;
}
```

**Input**

```text
82
```

## Expected Output

```text
Enter marks (0-100): Grade: B
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing semicolon

</details>
