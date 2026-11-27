# Debug Session 69: Student Class

**Section H — Object-Oriented Programming**

## Aim

Debug the program below. It is the solution to: *Write a program to create a `Student` class with data members and member functions.*

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

class Student {
public:
    string name;
    int roll;
    float marks

    void input() {
        cout << "Enter name, roll and marks: ";
        cin >> name >> roll >> marks;
    }
    void display() {
        cout << "Name: " << name << ", Roll: " << roll << ", Marks: " << marks << endl;
    }
}

int main() {
    Student s;
    s.input();
    s.display();
    return 0;
}
```

**Input**

```text
Ravi
12
91
```

## Expected Output

```text
Enter name, roll and marks: Name: Ravi, Roll: 12, Marks: 91
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing semicolon after class

</details>
