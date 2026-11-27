# Debug Session 76: Class Function Overloading

**Section H — Object-Oriented Programming**

## Aim

Debug the program below. It is the solution to: *Write a program to demonstrate function overloading through class member functions.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

class Printer {
public:
    void print(int x) { cout << "Integer: " << x << endl; }
    void print(float x) { cout << "Float: " << x << endl; 
    void print(char x) { cout << "Char: " << x << endl; }
};

int main() {
    Printer p;
    p.print(10);
    p.print(2.5f);
    p.print('A);
    return 0;
}
```

## Expected Output

```text
Integer: 10
Float: 2.5
Char: A
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing closing brace
2. Unterminated char literal

</details>
