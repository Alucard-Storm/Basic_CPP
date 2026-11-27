# Experiment 76: Class Function Overloading

**Section H — Object-Oriented Programming**

## Aim

Write a program to demonstrate function overloading through class member functions.

## Concepts Used

Overloaded member functions

## Program

```cpp
#include <iostream>
using namespace std;

class Printer {
public:
    void print(int x) { cout << "Integer: " << x << endl; }
    void print(float x) { cout << "Float: " << x << endl; }
    void print(char x) { cout << "Char: " << x << endl; }
};

int main() {
    Printer p;
    p.print(10);
    p.print(2.5f);
    p.print('A');
    return 0;
}
```

## Sample Run

**Output**

```text
Integer: 10
Float: 2.5
Char: A

```

## Result

The program was executed successfully and the output was verified.
