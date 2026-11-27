# Debug Session 20: Switch Calculator

**Section B — Conditional Statements and Decision-Making**

## Aim

Debug the program below. It is the solution to: *Write a menu-driven calculator using the `switch` statement.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

int main() {
    float a, b;
    char op;
    cout << "Enter two numbers and an operator (+ - * /): ";
    cin >> a >> b >> op;
    switch (op) 
        case '+': cout << a + b << endl; break;
        case '-'  cout << a - b << endl; break;
        case '*': cout << a * b << endl; break;
        case '/':
            if (b != 0) cout << a / b << endl;
            else cout << "Division by zero!" << endl;
            break;
        default: cout << "Invalid operator" << endl;
    }
    return 0;
}
```

**Input**

```text
8 2 /
```

## Expected Output

```text
Enter two numbers and an operator (+ - * /): 4
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing opening brace
2. Missing colon after case

</details>
