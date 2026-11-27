# Experiment 80: Inventory Management

**Section I — Mini-Projects**

## Aim

Develop a basic inventory management application to maintain item names, quantities, and prices.

## Concepts Used

Vector of structs, menu loop

## Program

```cpp
#include <iostream>
#include <string>
#include <vector>
using namespace std;

struct Item {
    string name;
    int qty;
    float price;
};

int main() {
    vector<Item> inv;
    int ch;
    do {
        cout << "\n1. Add item\n2. Display items\n3. Exit\nChoice: ";
        cin >> ch;
        if (ch == 1) {
            Item it;
            cout << "Enter name, quantity and price: ";
            cin >> it.name >> it.qty >> it.price;
            inv.push_back(it);
        } else if (ch == 2) {
            float total = 0;
            for (const Item &it : inv) {
                cout << it.name << " | " << it.qty << " | " << it.price << endl;
                total += it.qty * it.price;
            }
            cout << "Total inventory value = " << total << endl;
        }
    } while (ch != 3);
    return 0;
}
```

## Sample Run

**Input**

```text
1
Pen
50
5.5
1
Book
20
40
2
3
```

**Output**

```text

1. Add item
2. Display items
3. Exit
Choice: Enter name, quantity and price: 
1. Add item
2. Display items
3. Exit
Choice: Enter name, quantity and price: 
1. Add item
2. Display items
3. Exit
Choice: Pen | 50 | 5.5
Book | 20 | 40
Total inventory value = 1075

1. Add item
2. Display items
3. Exit
Choice: 
```

## Result

The program was executed successfully and the output was verified.
