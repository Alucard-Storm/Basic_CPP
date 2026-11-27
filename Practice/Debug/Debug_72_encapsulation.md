# Debug Session 72: Encapsulation

**Section H — Object-Oriented Programming**

## Aim

Debug the program below. It is the solution to: *Write a program to demonstrate encapsulation using private data members and public methods.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

class Account {
private:
    int balance;
public:
    void setBalance(int b) {
        if (b >= 0) balance = b;
    }
    int getBalance() { return balance }
};

int main() {
    Account a;
    int v;
    cout << "Enter balance: ";
    cin >> v;
    a.balance = v;
    cout << "Balance = " << a.getBalance() << endl;
    return 0;
}
```

**Input**

```text
75
```

## Expected Output

```text
Enter balance: Balance = 75
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Accessing a private member

</details>
