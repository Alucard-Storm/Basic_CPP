# Debug Session 48: Array Reverse

**Section E — Arrays and Searching/Sorting**

## Aim

Debug the program below. It is the solution to: *Write a program to reverse the elements of an array.*

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
    for (int i = 0, j = n - 1; i < j; i++, j--) 
        int t = a[i]
        a[i] = a[j];
        a[j] = t;
    }
    cout << "Reversed: ";
    for (int i = 0; i < n; i++) cout << a[i] << " ";
    cout << endl;
    return 0;
}
```

**Input**

```text
5
1 2 3 4 5
```

## Expected Output

```text
Enter number of elements: Enter elements: Reversed: 5 4 3 2 1 
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing opening brace
2. Missing semicolon

</details>
