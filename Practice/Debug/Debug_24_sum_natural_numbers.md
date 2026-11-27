# Debug Session 24: Sum Natural Numbers

**Section C — Loops and Number-Based Problems**

## Aim

Debug the program below. It is the solution to: *Write a program to calculate the sum of the first \\(N\\) natural numbers.*

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
    int n, sum = 0
    cout << "Enter N: ";
    cin >> n;
    for (int i = 1; i <= n; i++)
        sum =+ i
    cout << "Sum = " << sum << endl;
    return 0;
}
```

**Input**

```text
10
```

## Expected Output

```text
Enter N: Sum = 55
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon (and wrong operator)
2. Missing semicolon

</details>
