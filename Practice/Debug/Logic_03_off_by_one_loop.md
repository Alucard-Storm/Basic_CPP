# Logic Debug 3: Off-by-One Loop Bound

**Logic Bug Practice — Section C**

## Aim

This program compiles without errors, but calculates the wrong sum of the first `n` natural numbers. Find and fix the logic bug.

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Run the program with the sample input and notice why the output differs from the expected output.
3. Fix all the logic bugs (there is **1** deliberate error).
4. Recompile and verify the output matches the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int main() {
    int n, sum = 0;
    cout << "Enter n: ";
    cin >> n;
    for (int i = 1; i < n; i++) {
        sum += i;
    }
    cout << "Sum = " << sum << endl;
    return 0;
}
```

**Input**

```text
5
```

## Expected Output

```text
Enter n: Sum = 15
```

## Answer Key

<details>
<summary>Show logic bug</summary>

1. The loop condition `i < n` stops at `n - 1` and excludes `n`. Change it to `i <= n`.

</details>
