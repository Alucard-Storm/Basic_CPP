# Experiment 84: File Line and Word Count

**Section J — Structures and File Handling**

## Aim

Write a program to write lines of text to `notes.txt`, read the file back line by line, and count the total lines and words.

## Concepts Used

`<fstream>`, `<sstream>`, `getline`, `istringstream`

## Program

```cpp
#include <iostream>
#include <fstream>
#include <sstream>
#include <string>
using namespace std;

int main() {
    int n;
    cout << "How many lines? ";
    cin >> n;
    cin.ignore();

    ofstream out("notes.txt");
    if (!out) {
        cout << "Could not create notes.txt" << endl;
        return 1;
    }
    cout << "Enter lines:\n";
    string line;
    for (int i = 0; i < n; i++) {
        getline(cin, line);
        out << line << "\n";
    }
    out.close();

    ifstream in("notes.txt");
    if (!in) {
        cout << "Could not read notes.txt" << endl;
        return 1;
    }
    int lines = 0, words = 0;
    while (getline(in, line)) {
        lines++;
        istringstream iss(line);
        string word;
        while (iss >> word) words++;
    }
    cout << "Lines = " << lines << ", Words = " << words << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
2
C++ is fun
Practice every day
```

**Output**

```text
How many lines? Enter lines:
Lines = 2, Words = 6

```

## Result

The program was executed successfully and the output was verified.
