# Experiment 29: Palindrome Number

**Section C — Loops and Number-Based Problems**

## Aim

Write a program to check whether a number is a palindrome.

## Concepts Used

Reversing and comparing

## Program

```cpp
#include <iostream>
using namespace std;

int main() {
    int n, original, rev = 0;
    cout << "Enter a number: ";
    cin >> n;
    original = n;
    while (n > 0) {
        rev = rev * 10 + n % 10;
        n /= 10;
    }
    if (rev == original)
        cout << original << " is a palindrome" << endl;
    else
        cout << original << " is not a palindrome" << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
1221
```

**Output**

```text
Enter a number: 1221 is a palindrome

```

## Result

The program was executed successfully and the output was verified.
