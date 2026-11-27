# Experiment 69: Student Class

**Section H — Object-Oriented Programming**

## Aim

Write a program to create a `Student` class with data members and member functions.

## Concepts Used

Classes, objects, member functions

## Program

```cpp
#include <iostream>
#include <string>
using namespace std;

class Student {
public:
    string name;
    int roll;
    float marks;

    void input() {
        cout << "Enter name, roll and marks: ";
        cin >> name >> roll >> marks;
    }
    void display() {
        cout << "Name: " << name << ", Roll: " << roll << ", Marks: " << marks << endl;
    }
};

int main() {
    Student s;
    s.input();
    s.display();
    return 0;
}
```

## Sample Run

**Input**

```text
Ravi
12
91
```

**Output**

```text
Enter name, roll and marks: Name: Ravi, Roll: 12, Marks: 91

```

## Result

The program was executed successfully and the output was verified.
