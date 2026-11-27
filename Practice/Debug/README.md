# Practice Debug Exercises

This folder contains **88 debugging exercises** paired with the [Practice Bank](../README.md):

- **Syntax debugging (`Debug_01`–`Debug_84`):** Deliberate compile-time syntax errors paired one-to-one with `Practice/Experiments/` (`01`–`84`).
- **Logic debugging (`Logic_01`–`Logic_04`):** Programs that compile cleanly but produce incorrect output due to common beginner logic mistakes.

For structured syntax + logic debugging labs with separate `buggy.cpp` and `fixed.cpp` files, see [debugging/README.md](../../debugging/README.md).

## How to practise

1. Copy the **Buggy Code** into a `.cpp` file and compile with:
   ```bash
   g++ -std=c++17 -Wall -Wextra file.cpp -o file
   ```
2. Fix the compiler errors (or trace the wrong output for `Logic_*` exercises) before checking the **Answer Key**.
3. Browse the full index in [Practice/README.md](../README.md).
