# Debug Session 83: File Write and Read Numbers

**Section J — Structures and File Handling**

## Aim

Debug the program below. It is the solution to: *Write a program to save integers to a text file (`numbers.txt`) and read them back to display their sum and average.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
#include <fstram>
using namespace std;

int main() {
    int n, x;
    cout << "How many numbers? ";
    cin >> n;

    ofstream out("numbers.txt");
    if (!out) {
        cout << "Could not open numbers.txt for writing" << endl;
        return 1;
    }
    cout << "Enter numbers: ";
    for (int i = 0; i < n; i++) {
        cin >> x;
        out << x << "\n";
    }
    out.close();
    cout << "Saved to numbers.txt" << endl;

    ifstream in("numbers.txt");
    if (!in) {
        cout << "Could not open numbers.txt for reading" << endl;
        return 1;
    }
    int sum = 0, count = 0;
    while (in >> x) {
        sum += x;
        count++;
    }
    cout << "Sum = " << sum << ", Average = " << static_cast<double>(sum) / count << endl
    return 0;
}
```

**Input**

```text
4
10 20 30 40
```

## Expected Output

```text
How many numbers? Enter numbers: Saved to numbers.txt
Sum = 100, Average = 25
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Wrong header name
2. Missing semicolon

</details>
