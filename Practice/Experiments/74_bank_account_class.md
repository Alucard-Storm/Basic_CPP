# Experiment 74: Bank Account Class

**Section H — Object-Oriented Programming**

## Aim

Write a program to create a `BankAccount` class with deposit, withdrawal, and balance display operations.

## Concepts Used

Methods that modify state

## Program

```cpp
#include <iostream>
using namespace std;

class BankAccount {
    float balance;
public:
    BankAccount(float b) { balance = b; }
    void deposit(float amt) { balance += amt; }
    void withdraw(float amt) {
        if (amt > balance) cout << "Insufficient balance" << endl;
        else balance -= amt;
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

## Sample Run

**Input**

```text
1000
500
2000
```

**Output**

```text
Enter opening balance: Enter deposit amount: Balance = 1500
Enter withdrawal amount: Insufficient balance
Balance = 1500

```

## Result

The program was executed successfully and the output was verified.
