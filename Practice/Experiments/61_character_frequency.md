# Experiment 61: Character Frequency

**Section F — Strings**

## Aim

Write a program to count the frequency of each character in a string.

## Concepts Used

Frequency array

## Program

```cpp
#include <iostream>
#include <string>
using namespace std;

int main() {
    string s;
    int freq[256] = {0};
    cout << "Enter a string: ";
    cin >> s;
    for (char ch : s) freq[(unsigned char)ch]++;
    for (int i = 0; i < 256; i++)
        if (freq[i] > 0)
            cout << (char)i << " : " << freq[i] << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
banana
```

**Output**

```text
Enter a string: a : 3
b : 1
n : 2

```

## Result

The program was executed successfully and the output was verified.
