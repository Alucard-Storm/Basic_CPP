# Debug Session 30: Prime Check

**Section C — Loops and Number-Based Problems**

## Aim

Debug the program below. It is the solution to: *Write a program to check whether a number is prime.*

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
    int n;
    bool prime = ture;
    cout << "Enter a number: ";
    cin >> n;
    if (n < 2) prime = false;
    for (int i = 2; i * i <= n; i++) {
        if (n % i == 0) {
            prime = false;
            brek;
        }
    }
    cout << n << (prime ? " is prime" : " is not prime") << endl;
    return 0;
}
```

**Input**

```text
29
```

## Expected Output

```text
Enter a number: 29 is prime
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Misspelled keyword (undeclared identifier)
2. Misspelled keyword

</details>
