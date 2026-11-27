# Debug Session 45: Array Sum Average

**Section E — Arrays and Searching/Sorting**

## Aim

Debug the program below. It is the solution to: *Write a program to calculate the sum and average of array elements.*

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
    int n, a[50], sum = 0;
    cout << "Enter number of elements: ";
    cin >> n;
    cout << "Enter elements: ";
    for (int i = 0; i < n; i++) {
        cin >> a[i];
        sum += a[i]
    }
    cout << "Sum = " << sum << endl;
    cout << "Average = " << (float sum / n << endl;
    return 0;
}
```

**Input**

```text
5
10 20 30 40 50
```

## Expected Output

```text
Enter number of elements: Enter elements: Sum = 150
Average = 30
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing parenthesis in cast

</details>
