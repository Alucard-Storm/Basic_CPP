# Debug Session 64: Pointer Access Modify

**Section G — Pointers and References**

## Aim

Debug the program below. It is the solution to: *Write a program to access and modify a variable using a pointer.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int main() {
    int a = 10;
    int *p = a;
    cout << "a = " << a << ", *p = " << *p << endl;
    *p = 25
    cout << "After modification through pointer, a = " << a << endl;
    return 0;
}
```

## Expected Output

```text
a = 10, *p = 10
After modification through pointer, a = 25
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Assigning int to pointer (type error)
2. Missing semicolon

</details>
