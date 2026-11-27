# Experiment 34: Star Patterns

**Section C — Loops and Number-Based Problems**

## Aim

Write a program to print star patterns, including triangles and pyramids.

## Concepts Used

Nested loops

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter rows: ";
    cin >> n;
    cout << "Right triangle:" << endl;
    for (int i = 1; i <= n; i++) {
        for (int j = 1; j <= i; j++) cout << "* ";
        cout << endl;
    }
    cout << "Pyramid:" << endl;
    for (int i = 1; i <= n; i++) {
        for (int s = 1; s <= n - i; s++) cout << " ";
        for (int j = 1; j <= 2 * i - 1; j++) cout << "*";
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
Enter rows: Right triangle:
* 
* * 
* * * 
* * * * 
* * * * * 
Pyramid:
    *
   ***
  *****
 *******
*********

```

## Result

The program was executed successfully and the output was verified.
