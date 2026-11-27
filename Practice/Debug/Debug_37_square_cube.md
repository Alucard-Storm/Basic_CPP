# Debug Session 37: Square Cube

**Section D — Functions and Recursion**

## Aim

Debug the program below. It is the solution to: *Write a program to calculate the square and cube of a number using functions.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int square(int n) { return n * n; }
int cube(int n) { return n * n * n; 

int main() {
    int n;
    cout << "Enter a number: ";
    cin >> n;
    cout << "Square = " << squar(n) << endl;
    cout << "Cube = " << cube(n) << endl;
    return 0;
}
```

**Input**

```text
4
```

## Expected Output

```text
Enter a number: Square = 16
Cube = 64
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing closing brace
2. Undeclared function (typo)

</details>
