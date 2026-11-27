# Debug Session 60: String Concat Compare

**Section F — Strings**

## Aim

Debug the program below. It is the solution to: *Write a program to concatenate and compare two strings.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
#include <cstring>
using namespace std;

int main() {
    char a[100], b[50];
    cout << "Enter first string: ";
    cin >> a;
    cout << "Enter second string: ";
    cin >> b;
    if (strcmp(a, b) == 0
        cout << "Strings are equal" << endl;
    else
        cout << "Strings are not equal" << endl;
    strcat(a, b)
    cout << "Concatenated: " << a << endl;
    return 0;
}
```

**Input**

```text
Good
Morning
```

## Expected Output

```text
Enter first string: Enter second string: Strings are not equal
Concatenated: GoodMorning
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Missing parenthesis

</details>
