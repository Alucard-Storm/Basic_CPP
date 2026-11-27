# Debug Session 66: Pointer Arithmetic Array

**Section G — Pointers and References**

## Aim

Debug the program below. It is the solution to: *Write a program to traverse an array using pointer arithmetic.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int main() {
    int a[5] = {10, 20, 30, 40, 50}
    int *p == a;
    for (int i = 0; i < 5; i++) {
        cout << "Element " << i << " = " << *p << endl;
        p++;
    }
    return 0;
}
```

## Expected Output

```text
Element 0 = 10
Element 1 = 20
Element 2 = 30
Element 3 = 40
Element 4 = 50
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Wrong operator in declaration

</details>
