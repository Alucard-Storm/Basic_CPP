# Experiment 82: Employee Records Array

**Section J — Structures and File Handling**

## Aim

Write a program to read details of `n` employees using an array of structures and display the highest-paid employee.

## Concepts Used

Array of `struct`, finding maximum record

## Program

```cpp
#include <iostream>
#include <string>
using namespace std;

struct Employee {
    string name;
    int id;
    double salary;
};

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
         << ", Salary: " << e[best].salary << ")" << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
3
Asha 101 45000
Ravi 102 62000
Neha 103 54000
```

**Output**

```text
Enter number of employees: Enter name, ID and salary: Enter name, ID and salary: Enter name, ID and salary: Highest paid: Ravi (ID: 102, Salary: 62000)

```

## Result

The program was executed successfully and the output was verified.
