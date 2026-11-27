# Debug Session 82: Employee Records Array

**Section J — Structures and File Handling**

## Aim

Debug the program below. It is the solution to: *Write a program to read details of `n` employees using an array of structures and display the highest-paid employee.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
#include <string>
using namespace std;

struct Employee {
    string name;
    int id;
    double salary;
}

int main() {
    int n;
    Employee e[20];
    cout << "Enter number of employees: ";
    cin >> n;
    for (int i = 0; i < n; i++) {
        cout << "Enter name, ID and salary: ";
        cin >> e[i].name >> e[i].id >> e[i].salary;
    }
    int best = 0;
    for (int i = 1; i < n; i++)
        if (e[i].salary > e[best].salary) best = i;
    cout << "Highest paid: " << e[best].name
         << " (ID: " << e[best].id
         << ", Salary: " << e[best].salary << ")" << endl
    return 0;
}
```

**Input**

```text
3
Asha 101 45000
Ravi 102 62000
Neha 103 54000
```

## Expected Output

```text
Enter number of employees: Enter name, ID and salary: Enter name, ID and salary: Enter name, ID and salary: Highest paid: Ravi (ID: 102, Salary: 62000)
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon after struct
2. Missing semicolon

</details>
