# Experiment 20: Switch Calculator

**Section B — Conditional Statements and Decision-Making**

## Aim

Write a menu-driven calculator using the `switch` statement.

## Concepts Used

`switch`, `case`, `break`, `default`

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    float a, b;
    char op;
    cout << "Enter two numbers and an operator (+ - * /): ";
    cin >> a >> b >> op;
    switch (op) {
        case '+': cout << a + b << endl; break;
        case '-': cout << a - b << endl; break;
        case '*': cout << a * b << endl; break;
        case '/':
            if (b != 0) cout << a / b << endl;
            else cout << "Division by zero!" << endl;
            break;
        default: cout << "Invalid operator" << endl;
    }
    return 0;
}
```

## Sample Run

**Input**

```text
8 2 /
```

**Output**

```text
Enter two numbers and an operator (+ - * /): 4

```

## Result

The program was executed successfully and the output was verified.
