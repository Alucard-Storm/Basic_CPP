# Debug Session 46: Array Max Min

**Section E — Arrays and Searching/Sorting**

## Aim

Debug the program below. It is the solution to: *Write a program to find the largest and smallest elements in an array.*

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
    int n, a[50];
    cout << "Enter number of elements: ";
    cin >> n;
    cout << "Enter elements: ";
    for (int i = 0; i < n; i++) cin >> a[i];
    int mx = a[0], mn = a[0]
    for (int i = 1; i < n; i++) {
        if (a[i] > mx) mx = a[i];
        if (a[i] < mn) mn = a[i];
    }
    }
    }
    cout << "Largest = " << mx << "\nSmallest = " << mn << endl;
    return 0;
}
```

**Input**

```text
5
23 7 41 15 9
```

## Expected Output

```text
Enter number of elements: Enter elements: Largest = 41
Smallest = 7
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Extra closing braces

</details>
