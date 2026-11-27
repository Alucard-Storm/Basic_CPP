# Experiment 83: File Write and Read Numbers

**Section J — Structures and File Handling**

## Aim

Write a program to save integers to a text file (`numbers.txt`) and read them back to display their sum and average.

## Concepts Used

`<fstream>`, `ofstream`, `ifstream`, file error checking

## Program

```cpp
#include <iostream>
#include <fstream>
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
    cout << "Sum = " << sum << ", Average = " << static_cast<double>(sum) / count << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
4
10 20 30 40
```

**Output**

```text
How many numbers? Enter numbers: Saved to numbers.txt
Sum = 100, Average = 25

```

## Result

The program was executed successfully and the output was verified.
