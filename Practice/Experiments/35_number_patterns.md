# Experiment 35: Number Patterns

**Section C — Loops and Number-Based Problems**

## Aim

Write a program to print number patterns using nested loops.

## Concepts Used

Nested loops with numbers

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter rows: ";
    cin >> n;
    for (int i = 1; i <= n; i++) {
        for (int j = 1; j <= i; j++) cout << j << " ";
        cout << endl;
    }
    for (int i = 1; i <= n; i++) {
        for (int j = 1; j <= i; j++) cout << i << " ";
        cout << endl;
    }
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
Enter rows: 1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5 
1 
2 2 
3 3 3 
4 4 4 4 
5 5 5 5 5 

```

## Result

The program was executed successfully and the output was verified.
