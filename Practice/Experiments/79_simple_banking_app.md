# Experiment 79: Simple Banking App

**Section I — Mini-Projects**

## Aim

Develop a simple banking application using classes and objects.

## Concepts Used

Classes, objects, menu loop

## Program

```cpp
#include <iostream>
using namespace std;

class Bank {
    float balance;
public:
    Bank() { balance = 0; }
    void deposit(float a) { balance += a; cout << "Deposited " << a << endl; }
    void withdraw(float a) {
        if (a > balance) cout << "Insufficient funds" << endl;
        else { balance -= a; cout << "Withdrawn " << a << endl; }
    }
    void show() { cout << "Current balance = " << balance << endl; }
};

int main() {
    Bank acc;
    int ch;
    float amt;
    do {
        cout << "\n1. Deposit\n2. Withdraw\n3. Balance\n4. Exit\nChoice: ";
        cin >> ch;
        switch (ch) {
            case 1: cout << "Amount: "; cin >> amt; acc.deposit(amt); break;
            case 2: cout << "Amount: "; cin >> amt; acc.withdraw(amt); break;
            case 3: acc.show(); break;
            case 4: cout << "Thank you!" << endl; break;
            default: cout << "Invalid choice" << endl;
        }
    } while (ch != 4);
    return 0;
}
```

## Sample Run

**Input**

```text
1
500
2
200
3
4
```

**Output**

```text

1. Deposit
2. Withdraw
3. Balance
4. Exit
Choice: Amount: Deposited 500

1. Deposit
2. Withdraw
3. Balance
4. Exit
Choice: Amount: Withdrawn 200

1. Deposit
2. Withdraw
3. Balance
4. Exit
Choice: Current balance = 300

1. Deposit
2. Withdraw
3. Balance
4. Exit
Choice: Thank you!

```

## Result

The program was executed successfully and the output was verified.
