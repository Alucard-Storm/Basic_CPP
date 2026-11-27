# Debug Session 32: Armstrong Number

**Section C — Loops and Number-Based Problems**

## Aim

Debug the program below. It is the solution to: *Write a program to check whether a number is an Armstrong number.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
#include <cmath>
using namespace std;

int main() {
    int n, temp, digits = 0, sum = 0;
    cout << "Enter a number: ";
    cin >> n;
    temp = n;
    while (temp > 0) { digits++; temp /= 10; }
    temp = n;
    while temp > 0) {
        sum += pow(temp % 10 digits);
        temp /= 10;
    }
    if (sum == n)
        cout << n << " is an Armstrong number" << endl;
    else
        cout << n << " is not an Armstrong number" << endl;
    return 0;
}
```

**Input**

```text
153
```

## Expected Output

```text
Enter a number: 153 is an Armstrong number
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing parenthesis
2. Missing comma in function call

</details>
