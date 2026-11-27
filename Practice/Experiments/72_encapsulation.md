# Experiment 72: Encapsulation

**Section H — Object-Oriented Programming**

## Aim

Write a program to demonstrate encapsulation using private data members and public methods.

## Concepts Used

`private` data, `public` getters/setters

## Program

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
    int getBalance() { return balance; }
};

int main() {
    Account a;
    int v;
    cout << "Enter balance: ";
    cin >> v;
    a.setBalance(v);
    cout << "Balance = " << a.getBalance() << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
75
```

**Output**

```text
Enter balance: Balance = 75

```

## Result

The program was executed successfully and the output was verified.
