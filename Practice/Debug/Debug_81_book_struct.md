# Debug Session 81: Book Record Using Struct

**Section J — Structures and File Handling**

## Aim

Debug the program below. It is the solution to: *Write a program to store and display a book's title, author, and price using a `struct`.*

## Instructions

1. Copy the code into a `.cpp` file and compile it with `g++ -std=c++17 -Wall -Wextra file.cpp -o file`.
2. Read each compiler error message and locate the faulty line.
3. Fix all the syntax errors (there are **2** deliberate error(s)).
4. Run the program and compare its output with the expected output below.

## Buggy Code

```cpp
#include <iostream>
#include <string>
using namespace std;

struct Book {
    string title;
    string author;
    double price;
}

int main() {
    Book b;
    cout << "Enter title, author and price: ";
    cin >> b.title >> b.author >> b.price
    cout << "Title: " << b.title << ", Author: " << b.author << ", Price: " << b.price << endl;
    return 0;
}
```

**Input**

```text
CleanCode
Martin
499.5
```

## Expected Output

```text
Enter title, author and price: Title: CleanCode, Author: Martin, Price: 499.5
```

## Answer Key

<details>
<summary>Show errors</summary>

1. Missing semicolon after struct
2. Missing semicolon

</details>
