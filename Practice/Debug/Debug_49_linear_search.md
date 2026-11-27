# Debug Session 49: Linear Search

**Section E — Arrays and Searching/Sorting**

## Aim

Debug the program below. It is the solution to: *Write a program to search for an element using linear search.*

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
    int n, a[50], key, pos = -1;
    cout << "Enter number of elements: ";
    cin >> n;
    cout << "Enter elements: ";
    for (int i = 0; i < n; i++) cin >> a[i];
    cout << "Enter element to search: ";
    cin >> kye;
    for (int i = 0; i < n; i++) {
        if (a[i] == key) { pos = i; break; 
    }
    if (pos != -1)
        cout << "Found at position " << pos + 1 << endl;
    else
        cout << "Not found" << endl;
    return 0;
}
```

**Input**

```text
5
10 20 30 40 50
30
```

## Expected Output

```text
Enter number of elements: Enter elements: Enter element to search: Found at position 3
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing closing brace
2. Undeclared variable (typo)

</details>
