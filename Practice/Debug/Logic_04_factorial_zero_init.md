# Logic Debug 4: Accumulator Initialized to Zero in Factorial

**Logic Bug Practice — Section C**

## Aim

This program compiles without errors, but always prints `Factorial = 0`. Find and fix the logic bug.

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
    int n;
    long long fact = 0;
    cout << "Enter n: ";
    cin >> n;
    for (int i = 1; i <= n; i++) {
        fact *= i;
    }
    cout << "Factorial = " << fact << endl;
    return 0;
}
```

**Input**

```text
5
```

## Expected Output

```text
Enter n: Factorial = 120
```

## Answer Key

<details>
<summary>Show logic bug</summary>

1. `fact` is initialized to `0`, so every multiplication `fact *= i` stays `0`. Initialize `fact = 1`.

</details>
