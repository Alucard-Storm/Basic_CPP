# Debug Session 67: Pass By Reference

**Section G — Pointers and References**

## Aim

Debug the program below. It is the solution to: *Write a program to pass arguments to a function using references.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

void update(int &a, &b) {
    a += 5;
    b *= 2
}

int main() {
    int x, y;
    cout << "Enter two numbers: ";
    cin >> x >> y;
    update(x, y);
    cout << "x = " << x << ", y = " << y << endl;
    return 0;
}
```

**Input**

```text
5 9
```

## Expected Output

```text
Enter two numbers: x = 10, y = 18
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing type for second parameter

</details>
