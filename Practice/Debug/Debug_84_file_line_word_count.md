# Debug Session 84: File Line and Word Count

**Section J — Structures and File Handling**

## Aim

Debug the program below. It is the solution to: *Write a program to write lines of text to `notes.txt`, read the file back line by line, and count the total lines and words.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

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
        getline(cin line);
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
    cout << "Lines = " << lines << ", Words = " << words << endl
    return 0;
}
```

**Input**

```text
2
C++ is fun
Practice every day
```

## Expected Output

```text
How many lines? Enter lines:
Lines = 2, Words = 6
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing comma in `getline`
2. Missing semicolon

</details>
