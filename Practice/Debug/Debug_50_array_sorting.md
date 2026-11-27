# Debug Session 50: Array Sorting

**Section E — Arrays and Searching/Sorting**

## Aim

Debug the program below. It is the solution to: *Write a program to sort an array in ascending and descending order.*

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
    int n, a[50];
    cout << "Enter number of elements: ";
    cin >> n;
    cout << "Enter elements: ";
    for (int i = 0; i < n; i++) cin >> a[i];
    for (int i = 0; i < n - 1; i++)
        for (int j = 0; j < n - i - 1; j++
            if (a[j] > a[j + 1]) { int t = a[j] a[j] = a[j + 1]; a[j + 1] = t; }
    cout << "Ascending: ";
    for (int i = 0; i < n; i++) cout << a[i] << " ";
    cout << "\nDescending: ";
    for (int i = n - 1; i >= 0; i--) cout << a[i] << " ";
    cout << endl;
    return 0;
}
```

**Input**

```text
5
40 10 50 20 30
```

## Expected Output

```text
Enter number of elements: Enter elements: Ascending: 10 20 30 40 50 
Descending: 50 40 30 20 10 
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing parenthesis
2. Missing semicolon

</details>
