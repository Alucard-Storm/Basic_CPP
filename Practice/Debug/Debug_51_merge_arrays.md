# Debug Session 51: Merge Arrays

**Section E — Arrays and Searching/Sorting**

## Aim

Debug the program below. It is the solution to: *Write a program to merge two arrays into a third array.*

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
    int n1, n2, a[50], b[50], c[100]
    cout << "Size of first array: ";
    cin >> n1;
    for (int i = 0; i < n1; i++) cin >> a[i];
    cout << "Size of second array: ";
    cin >> n2;
    for (int i = 0; i < n2; i++) cin >> b[i];
    for (int i = 0; i < n1; i++) c[i] = a[i];
    for (int i = 0; i < n2; i++) c[n1 + i] = b[i;
    cout << "Merged array: ";
    for (int i = 0; i < n1 + n2; i++) cout << c[i] << " ";
    cout << endl;
    return 0;
}
```

**Input**

```text
3
1 3 5
3
2 4 6
```

## Expected Output

```text
Size of first array: Size of second array: Merged array: 1 3 5 2 4 6 
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing bracket

</details>
