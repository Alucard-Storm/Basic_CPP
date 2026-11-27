# Debug Session 10: Days To Years Weeks

**Section A — Basic Programming and Operators**

## Aim

Debug the program below. It is the solution to: *Write a program to convert a given number of days into years, weeks, and days.*

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
    int days;
    cout << "Enter number of days: ";
    cin >> days;
    int years = days / 365;
    int rem = days % 365;
    int weeks = rem / 7
    int 2d = rem % 7;
    cout << years << " years, " << weeks << " weeks, " << d << " days" << endl;
    return 0;
}
```

**Input**

```text
800
```

## Expected Output

```text
Enter number of days: 2 years, 10 weeks, 0 days
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Invalid identifier name

</details>
