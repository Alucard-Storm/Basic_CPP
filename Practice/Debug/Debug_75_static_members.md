# Debug Session 75: Static Members

**Section H — Object-Oriented Programming**

## Aim

Debug the program below. It is the solution to: *Write a program to demonstrate static data members and static member functions.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

class Counter {
    static int count;
public:
    Counter() { count++; }
    static int getCount() { return count; }
};

int Counter::count = 0

int main() {
    Counter a, b, c;
    cout << "Objects created: " << Counter:getCount() << endl;
    return 0;
}
```

## Expected Output

```text
Objects created: 3
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Single colon instead of scope operator

</details>
