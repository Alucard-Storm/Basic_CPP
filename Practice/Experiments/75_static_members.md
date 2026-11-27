# Experiment 75: Static Members

**Section H — Object-Oriented Programming**

## Aim

Write a program to demonstrate static data members and static member functions.

## Concepts Used

`static` data and functions

## Program

```cpp
#include <iostream>
using namespace std;

class Counter {
    static int count;
public:
    Counter() { count++; }
    static int getCount() { return count; }
};

int Counter::count = 0;

int main() {
    Counter a, b, c;
    cout << "Objects created: " << Counter::getCount() << endl;
    return 0;
}
```

## Sample Run

**Output**

```text
Objects created: 3

```

## Result

The program was executed successfully and the output was verified.
