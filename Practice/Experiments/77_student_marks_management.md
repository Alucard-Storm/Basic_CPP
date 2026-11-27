# Experiment 77: Student Marks Management

**Section I — Mini-Projects**

## Aim

Develop a student marks management application to calculate totals, averages, and grades.

## Concepts Used

Arrays of structs, grade logic

## Program

```cpp
#include <iostream>
#include <string>
using namespace std;

struct Student {
    string name;
    int m[3];
    int total;
    float avg;
    char grade;
};

char getGrade(float avg) {
    if (avg >= 75) return 'A';
    if (avg >= 60) return 'B';
    if (avg >= 40) return 'C';
    return 'F';
}

int main() {
    int n;
    Student s[20];
    cout << "Enter number of students: ";
    cin >> n;
    for (int i = 0; i < n; i++) {
        cout << "Enter name and marks in 3 subjects: ";
        cin >> s[i].name >> s[i].m[0] >> s[i].m[1] >> s[i].m[2];
        s[i].total = s[i].m[0] + s[i].m[1] + s[i].m[2];
        s[i].avg = s[i].total / 3.0;
        s[i].grade = getGrade(s[i].avg);
    }
    cout << "\nName\tTotal\tAverage\tGrade\n";
    for (int i = 0; i < n; i++)
        cout << s[i].name << "\t" << s[i].total << "\t" << s[i].avg << "\t" << s[i].grade << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
2
Asha
80 90 70
Rahul
55 45 60
```

**Output**

```text
Enter number of students: Enter name and marks in 3 subjects: Enter name and marks in 3 subjects: 
Name	Total	Average	Grade
Asha	240	80	A
Rahul	160	53.3333	C

```

## Result

The program was executed successfully and the output was verified.
