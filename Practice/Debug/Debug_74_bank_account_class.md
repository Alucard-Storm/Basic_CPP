# Debug Session 74: Bank Account Class

**Section H — Object-Oriented Programming**

## Aim

Debug the program below. It is the solution to: *Write a program to create a `BankAccount` class with deposit, withdrawal, and balance display operations.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
using namespace std;

class BankAccount {
    float balance;
public:
    BankAccount(float b) { balance = b; }
    void deposit(float amt) { balance += amt }
    void withdraw(float amt) {
        if (amt > balance) cout << "Insufficient balance" << endl;
        esle balance -= amt;
    }
    void display() { cout << "Balance = " << balance << endl; }
};

int main() {
    float init, d, w;
    cout << "Enter opening balance: ";
    cin >> init;
    BankAccount acc(init);
    cout << "Enter deposit amount: ";
    cin >> d;
    acc.deposit(d);
    acc.display();
    cout << "Enter withdrawal amount: ";
    cin >> w;
    acc.withdraw(w);
    acc.display();
    return 0;
}
```

**Input**

```text
1000
500
2000
```

## Expected Output

```text
Enter opening balance: Enter deposit amount: Balance = 1500
Enter withdrawal amount: Insufficient balance
Balance = 1500
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon
2. Misspelled keyword

</details>
