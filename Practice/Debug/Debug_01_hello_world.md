# Debug Session 1: Hello World

**Section A — Basic Programming and Operators**

## Aim

Debug the program below. It is the solution to: *Write a C++ program to display “Hello, World!” and demonstrate the basic structure of a program.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace sdt;

int main() {
    cout << "Hello, World!" << endl
    return 0;
}
```

## Expected Output

```text
Hello, World!
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Misspelled namespace

</details>
