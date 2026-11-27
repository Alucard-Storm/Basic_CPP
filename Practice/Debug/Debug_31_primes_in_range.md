# Debug Session 31: Primes In Range

**Section C — Loops and Number-Based Problems**

## Aim

Debug the program below. It is the solution to: *Write a program to print all prime numbers within a given range.*

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
    int lo, hi;
    cout << "Enter range: ";
    cin >> lo >> hi;
    for (int n = lo; n <= hi; n++) {
        if (n < 2) continue;
        bool prime = true
        for (int i = 2; i * i <= n; i++)
            if (n % i == 0) { prime = false; break; }
        if (prime) cout << n << " "
    }
    cout << endl;
    return 0;
}
```

**Input**

```text
10 50
```

## Expected Output

```text
Enter range: 11 13 17 19 23 29 31 37 41 43 47 
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing semicolon

</details>
