# Debug Session 6: Circle Area Circumference

**Section A — Basic Programming and Operators**

## Aim

Debug the program below. It is the solution to: *Write a program to calculate the area and circumference of a circle.*

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
    const float PI = 3.14159
    float r;
    cout << "Enter radius: ";
    cin >> r;
    cout << "Area =  << PI * r * r << endl;
    cout << "Circumference = " << 2 * PI * r << endl;
    return 0;
}
```

**Input**

```text
5
```

## Expected Output

```text
Enter radius: Area = 78.5397
Circumference = 31.4159
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Unterminated string literal

</details>
