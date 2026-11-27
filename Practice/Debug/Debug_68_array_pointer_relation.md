# Debug Session 68: Array Pointer Relation

**Section G — Pointers and References**

## Aim

Debug the program below. It is the solution to: *Write a program to demonstrate the relationship between arrays and pointers.*

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
    int a[4] = {1, 2, 3, 4};
    int *p = a
    for (int i = 0; i < 4; i++) {
        cout << "a[" << i << "] = " << a[i] << ", *(a+" << i << ") = " << *(a + i
             << ", p[" << i << "] = " << p[i] << endl;
    }
    return 0;
}
```

## Expected Output

```text
a[0] = 1, *(a+0) = 1, p[0] = 1
a[1] = 2, *(a+1) = 2, p[1] = 2
a[2] = 3, *(a+2) = 3, p[2] = 3
a[3] = 4, *(a+3) = 4, p[3] = 4
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing parenthesis

</details>
