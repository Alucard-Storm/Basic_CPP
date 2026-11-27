# Experiment 81: Book Record Using Struct

**Section J — Structures and File Handling**

## Aim

Write a program to store and display a book's title, author, and price using a `struct`.

## Concepts Used

`struct`, member access (`.`)

## Program

```cpp
#include <iostream>
#include <string>
using namespace std;

struct Book {
    string title;
    string author;
    double price;
};

int main() {
    Book b;
    cout << "Enter title, author and price: ";
    cin >> b.title >> b.author >> b.price;
    cout << "Title: " << b.title << ", Author: " << b.author << ", Price: " << b.price << endl;
    return 0;
}
```

## Sample Run

**Input**

```text
CleanCode
Martin
499.5
```

**Output**

```text
Enter title, author and price: Title: CleanCode, Author: Martin, Price: 499.5

```

## Result

The program was executed successfully and the output was verified.
