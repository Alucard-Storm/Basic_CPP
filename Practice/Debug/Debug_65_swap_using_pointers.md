# Debug Session 65: Swap Using Pointers

**Section G — Pointers and References**

## Aim

Debug the program below. It is the solution to: *Write a program to swap two numbers using pointers.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

void swapNum(int *x, int *y) {
    int t = *x
    *x = *y;
    *y = t;
}

int main() {
    int a, b;
    cout << "Enter two numbers: ";
    cin >> a >> b;
    swapNum(a, b);
    cout << "After swap: a = " << a << ", b = " << b << endl;
    return 0;
}
```

**Input**

```text
5 9
```

## Expected Output

```text
Enter two numbers: After swap: a = 9, b = 5
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Passing int where pointer is expected
2. Missing semicolon

</details>
