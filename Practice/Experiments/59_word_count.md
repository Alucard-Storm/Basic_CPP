# Experiment 59: Word Count

**Section F — Strings**

## Aim

Write a program to count the number of words in a sentence.

## Concepts Used

Counting word boundaries

## Program

```cpp
#include <iostream>
#include <string>
using namespace std;

int main() {
    string s;
    cout << "Enter a sentence: ";
    getline(cin, s);
    int words = 0;
    bool inWord = false;
    for (char ch : s) {
        if (ch != ' ' && !inWord) { inWord = true; words++; }
        else if (ch == ' ') inWord = false;
    }
    cout << "Number of words = " << words << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
I love C++ programming
```

**Output**

```text
Enter a sentence: Number of words = 4

```

## Result

The program was executed successfully and the output was verified.
