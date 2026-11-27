# Experiment 78: Number Utility Menu

**Section I — Mini-Projects**

## Aim

Develop a menu-driven number utility application with prime checking, factorial, palindrome, and digit-sum operations.

## Concepts Used

Menu-driven program with `do-while` and `switch`

## Program

```cpp
#include <iostream>
using namespace std;

bool isPrime(int n) {
    if (n < 2) return false;
    for (int i = 2; i * i <= n; i++)
        if (n % i == 0) return false;
    return true;
}

long long factorial(int n) {
    long long f = 1;
    for (int i = 2; i <= n; i++) f *= i;
    return f;
}

bool isPalindrome(int n) {
    int r = 0, t = n;
    while (t > 0) { r = r * 10 + t % 10; t /= 10; }
    return r == n;
}

int digitSum(int n) {
    int s = 0;
    while (n > 0) { s += n % 10; n /= 10; }
    return s;
}

int main() {
    int choice, n;
    do {
        cout << "\n1. Prime check\n2. Factorial\n3. Palindrome check\n4. Digit sum\n5. Exit\nChoice: ";
        cin >> choice;
        if (choice >= 1 && choice <= 4) {
            cout << "Enter a number: ";
            cin >> n;
        }
        switch (choice) {
            case 1: cout << (isPrime(n) ? "Prime" : "Not prime") << endl; break;
            case 2: cout << "Factorial = " << factorial(n) << endl; break;
            case 3: cout << (isPalindrome(n) ? "Palindrome" : "Not a palindrome") << endl; break;
            case 4: cout << "Digit sum = " << digitSum(n) << endl; break;
            case 5: cout << "Goodbye!" << endl; break;
            default: cout << "Invalid choice" << endl;
        }
    } while (choice != 5);
    return 0;
}
```

## Sample Run

**Input**

```text
1
17
2
5
3
121
4
123
5
```

**Output**

```text

1. Prime check
2. Factorial
3. Palindrome check
4. Digit sum
5. Exit
Choice: Enter a number: Prime

1. Prime check
2. Factorial
3. Palindrome check
4. Digit sum
5. Exit
Choice: Enter a number: Factorial = 120

1. Prime check
2. Factorial
3. Palindrome check
4. Digit sum
5. Exit
Choice: Enter a number: Palindrome

1. Prime check
2. Factorial
3. Palindrome check
4. Digit sum
5. Exit
Choice: Enter a number: Digit sum = 6

1. Prime check
2. Factorial
3. Palindrome check
4. Digit sum
5. Exit
Choice: Goodbye!

```

## Result

The program was executed successfully and the output was verified.
