# Debug Session 38: Largest Function

**Section D — Functions and Recursion**

## Aim

Debug the program below. It is the solution to: *Write a program to find the largest of three numbers using a function.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int largest(int a, int b, int c) {
    if (a >= b && a >= c) return a;
    if (b >= c return b;
    return c;
}

int main() {
    int a, b, c;
    cout << "Enter three numbers: ";
    cin >> a >> b >> c
    cout << "Largest = " << largest(a, b, c) << endl;
    return 0;
}
```

**Input**

```text
3 9 5
```

## Expected Output

```text
Enter three numbers: Largest = 9
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing parenthesis
2. Missing semicolon

</details>
