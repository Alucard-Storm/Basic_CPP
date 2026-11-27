# Debug Session 8: Temperature Conversion

**Section A — Basic Programming and Operators**

## Aim

Debug the program below. It is the solution to: *Write a program to convert temperature between Celsius and Fahrenheit.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int main() {
    int choice;
    float t
    cout << "1. Celsius to Fahrenheit\n2. Fahrenheit to Celsius\nChoice: ";
    cin >> choice;
    cout << "Enter temperature: ";
    cin >> t;
    if choice == 1)
        cout << "Fahrenheit = " << t * 9 / 5 + 32 << endl;
    else
        cout << "Celsius = " << (t - 32) * 5 / 9 << endl;
    return 0;
}
```

**Input**

```text
1
100
```

## Expected Output

```text
1. Celsius to Fahrenheit
2. Fahrenheit to Celsius
Choice: Enter temperature: Fahrenheit = 212
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing opening parenthesis
2. Missing semicolon

</details>
