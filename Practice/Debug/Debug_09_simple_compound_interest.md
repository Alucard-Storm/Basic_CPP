# Debug Session 9: Simple Compound Interest

**Section A — Basic Programming and Operators**

## Aim

Debug the program below. It is the solution to: *Write a program to calculate simple interest and compound interest.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
#include <cmth>
using namespace std;

int main() {
    float p, r, t;
    cout << "Enter principal, rate and time: ";
    cin >> p >> r >> t;
    float si = (p * r * t) / 100
    float ci = p * pow(1 + r / 100, t) - p;
    cout << "Simple Interest = " << si << endl;
    cout << "Compound Interest = " << ci << endl;
    return 0;
}
```

**Input**

```text
1000 5 2
```

## Expected Output

```text
Enter principal, rate and time: Simple Interest = 100
Compound Interest = 102.5
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Wrong header name
2. Missing semicolon

</details>
