# Logic Debug 2: Initial Maximum Value for Negative Numbers

**Logic Bug Practice — Section E**

## Aim

This program compiles without errors, but prints `0` instead of the largest negative element in the array. Find and fix the logic bug.

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
    int n, a[50];
    cout << "Enter count: ";
    cin >> n;
    cout << "Enter elements: ";
    for (int i = 0; i < n; i++) cin >> a[i];
    int maxVal = 0;
    for (int i = 0; i < n; i++) {
        if (a[i] > maxVal) maxVal = a[i];
    }
    cout << "Max = " << maxVal << endl;
    return 0;
}
```

**Input**

```text
4
-12 -5 -30 -8
```

## Expected Output

```text
Enter count: Enter elements: Max = -5
```

## Answer Key

<details>
<summary>Show logic bug</summary>

1. `maxVal` is initialized to `0`, which is larger than all negative numbers in the array. Initialize `maxVal = a[0]` and loop from `i = 1`.

</details>
