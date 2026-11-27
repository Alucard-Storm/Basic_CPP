# Logic Debug 1: Integer Division in Temperature Conversion

**Logic Bug Practice — Section A**

## Aim

This program compiles without errors, but prints the wrong Fahrenheit temperature. Find and fix the logic bug.

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
    double c;
    cout << "Enter Celsius: ";
    cin >> c;
    double f = (9 / 5) * c + 32;
    cout << "Fahrenheit = " << f << endl;
    return 0;
}
```

**Input**

```text
25
```

## Expected Output

```text
Enter Celsius: Fahrenheit = 77
```

## Answer Key

<details>
<summary>Show logic bug</summary>

1. `9 / 5` performs integer division and evaluates to `1` instead of `1.8`. Change it to `9.0 / 5.0`.

</details>
