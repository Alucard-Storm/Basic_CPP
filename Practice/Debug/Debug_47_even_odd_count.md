# Debug Session 47: Even Odd Count

**Section E — Arrays and Searching/Sorting**

## Aim

Debug the program below. It is the solution to: *Write a program to count even and odd elements in an array.*

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
    int n, a[50], even = 0, odd = 0
    cout << "Enter number of elements: ";
    cin >> n;
    cout << "Enter elements: ";
    for (int i = 0; i < n; i++) {
        cin >> a[i];
        if (a[i] % 2 == 0) even++
        else odd++;
    }
    cout << "Even = " << even << ", Odd = " << odd << endl;
    return 0;
}
```

**Input**

```text
6
1 2 3 4 5 6
```

## Expected Output

```text
Enter number of elements: Enter elements: Even = 3, Odd = 3
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon before `else`
2. Missing semicolon

</details>
