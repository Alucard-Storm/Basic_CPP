# Practice Bank

Alongside the 32 main [experiments](../experiments/README.md) and 11 [debugging labs](../debugging/README.md), this folder provides **80 extra practice experiments** ([`Experiments/`](Experiments/)) paired one-to-one with **80 syntax-debugging exercises** ([`Debug/`](Debug/)).

## How to use these exercises

1. **Practice experiments (`Experiments/`):** Read the **Aim** and **Concepts Used**, design your own solution, and test it before looking at the reference **Program**.
2. **Debug exercises (`Debug/`):** Copy the **Buggy Code** into a `.cpp` file, compile it with warnings enabled, read the compiler errors, and fix the deliberate syntax errors before checking the **Answer Key**.

Compile any solution with:

```bash
g++ -std=c++17 -Wall -Wextra -pedantic -o prog file.cpp
./prog
```

## Sections overview

| Section | Topic | Experiments | Count | Related notes |
|---|---|---:|---:|---|
| A | Basic Programming and Operators | 01–12 | 12 | [Unit 01](../units/01-introduction/README.md), [Unit 02](../units/02-variables-and-types/README.md), [Unit 03](../units/03-operators-and-io/README.md) |
| B | Conditional Statements and Decision-Making | 13–22 | 10 | [Unit 04](../units/04-decisions/README.md) |
| C | Loops and Number-Based Problems | 23–35 | 13 | [Unit 05](../units/05-loops/README.md) |
| D | Functions and Recursion | 36–43 | 8 | [Unit 06](../units/06-functions/README.md) |
| E | Arrays and Searching/Sorting | 44–54 | 11 | [Unit 07](../units/07-arrays/README.md) |
| F | Strings | 55–62 | 8 | [Unit 08](../units/08-strings/README.md) |
| G | Pointers and References | 63–68 | 6 | [Unit 09](../units/09-pointers-and-references/README.md) |
| H | Object-Oriented Programming | 69–76 | 8 | [Unit 11](../units/11-classes/README.md) |
| I | Mini-Projects | 77–80 | 4 | [Unit 10](../units/10-structs/README.md), [Unit 11](../units/11-classes/README.md), [Unit 12](../units/12-files-and-vectors/README.md) |

## Section A — Basic Programming and Operators

| No. | Experiment | Concepts Used | Debug Exercise |
|---:|---|---|---|
| 01 | [Hello World](Experiments/01_hello_world.md) | Program structure, `#include`, `main()`, `cout` | [Debug 01](Debug/Debug_01_hello_world.md) |
| 02 | [Student Details](Experiments/02_student_details.md) | Variables, `cin`, `cout`, `string` | [Debug 02](Debug/Debug_02_student_details.md) |
| 03 | [Arithmetic Operations](Experiments/03_arithmetic_operations.md) | Arithmetic operators `+ - * / %` | [Debug 03](Debug/Debug_03_arithmetic_operations.md) |
| 04 | [Swap With Temp](Experiments/04_swap_with_temp.md) | Swapping with a temporary variable | [Debug 04](Debug/Debug_04_swap_with_temp.md) |
| 05 | [Swap Without Temp](Experiments/05_swap_without_temp.md) | Swapping using arithmetic | [Debug 05](Debug/Debug_05_swap_without_temp.md) |
| 06 | [Circle Area Circumference](Experiments/06_circle_area_circumference.md) | Constants, floating-point arithmetic | [Debug 06](Debug/Debug_06_circle_area_circumference.md) |
| 07 | [Rectangle Triangle](Experiments/07_rectangle_triangle.md) | Area and perimeter formulas | [Debug 07](Debug/Debug_07_rectangle_triangle.md) |
| 08 | [Temperature Conversion](Experiments/08_temperature_conversion.md) | Formula conversion, menu choice | [Debug 08](Debug/Debug_08_temperature_conversion.md) |
| 09 | [Simple Compound Interest](Experiments/09_simple_compound_interest.md) | `pow()`, `<cmath>` | [Debug 09](Debug/Debug_09_simple_compound_interest.md) |
| 10 | [Days To Years Weeks](Experiments/10_days_to_years_weeks.md) | Integer division and modulus | [Debug 10](Debug/Debug_10_days_to_years_weeks.md) |
| 11 | [Operators Demo](Experiments/11_operators_demo.md) | `++`, `--`, relational and logical operators | [Debug 11](Debug/Debug_11_operators_demo.md) |
| 12 | [Quotient Remainder](Experiments/12_quotient_remainder.md) | `/` and `%` on integers | [Debug 12](Debug/Debug_12_quotient_remainder.md) |

## Section B — Conditional Statements and Decision-Making

| No. | Experiment | Concepts Used | Debug Exercise |
|---:|---|---|---|
| 13 | [Even Odd](Experiments/13_even_odd.md) | `if-else`, modulus | [Debug 13](Debug/Debug_13_even_odd.md) |
| 14 | [Positive Negative Zero](Experiments/14_positive_negative_zero.md) | `if - else if - else` | [Debug 14](Debug/Debug_14_positive_negative_zero.md) |
| 15 | [Largest Of Numbers](Experiments/15_largest_of_numbers.md) | Nested conditions, logical operators | [Debug 15](Debug/Debug_15_largest_of_numbers.md) |
| 16 | [Leap Year](Experiments/16_leap_year.md) | Compound conditions | [Debug 16](Debug/Debug_16_leap_year.md) |
| 17 | [Vowel Consonant](Experiments/17_vowel_consonant.md) | `char`, `switch`/`if` | [Debug 17](Debug/Debug_17_vowel_consonant.md) |
| 18 | [Character Type](Experiments/18_character_type.md) | Character classification using ASCII ranges | [Debug 18](Debug/Debug_18_character_type.md) |
| 19 | [Student Grade](Experiments/19_student_grade.md) | `if-else if` ladder | [Debug 19](Debug/Debug_19_student_grade.md) |
| 20 | [Switch Calculator](Experiments/20_switch_calculator.md) | `switch`, `case`, `break`, `default` | [Debug 20](Debug/Debug_20_switch_calculator.md) |
| 21 | [Triangle Validity](Experiments/21_triangle_validity.md) | Validity condition, triangle types | [Debug 21](Debug/Debug_21_triangle_validity.md) |
| 22 | [Electricity Bill](Experiments/22_electricity_bill.md) | Slab-based calculation | [Debug 22](Debug/Debug_22_electricity_bill.md) |

## Section C — Loops and Number-Based Problems

| No. | Experiment | Concepts Used | Debug Exercise |
|---:|---|---|---|
| 23 | [Multiplication Table](Experiments/23_multiplication_table.md) | `for` loop | [Debug 23](Debug/Debug_23_multiplication_table.md) |
| 24 | [Sum Natural Numbers](Experiments/24_sum_natural_numbers.md) | Accumulator pattern | [Debug 24](Debug/Debug_24_sum_natural_numbers.md) |
| 25 | [Factorial Loop](Experiments/25_factorial_loop.md) | `long long`, loops | [Debug 25](Debug/Debug_25_factorial_loop.md) |
| 26 | [Fibonacci Series](Experiments/26_fibonacci_series.md) | Loop with two running variables | [Debug 26](Debug/Debug_26_fibonacci_series.md) |
| 27 | [Reverse Number](Experiments/27_reverse_number.md) | `while` loop, digit extraction | [Debug 27](Debug/Debug_27_reverse_number.md) |
| 28 | [Digit Sum Product](Experiments/28_digit_sum_product.md) | Digit extraction | [Debug 28](Debug/Debug_28_digit_sum_product.md) |
| 29 | [Palindrome Number](Experiments/29_palindrome_number.md) | Reversing and comparing | [Debug 29](Debug/Debug_29_palindrome_number.md) |
| 30 | [Prime Check](Experiments/30_prime_check.md) | Loop with `break` and flag | [Debug 30](Debug/Debug_30_prime_check.md) |
| 31 | [Primes In Range](Experiments/31_primes_in_range.md) | Nested loops | [Debug 31](Debug/Debug_31_primes_in_range.md) |
| 32 | [Armstrong Number](Experiments/32_armstrong_number.md) | `pow()`, digit counting | [Debug 32](Debug/Debug_32_armstrong_number.md) |
| 33 | [Gcd Lcm](Experiments/33_gcd_lcm.md) | Euclid's algorithm | [Debug 33](Debug/Debug_33_gcd_lcm.md) |
| 34 | [Star Patterns](Experiments/34_star_patterns.md) | Nested loops | [Debug 34](Debug/Debug_34_star_patterns.md) |
| 35 | [Number Patterns](Experiments/35_number_patterns.md) | Nested loops with numbers | [Debug 35](Debug/Debug_35_number_patterns.md) |

## Section D — Functions and Recursion

| No. | Experiment | Concepts Used | Debug Exercise |
|---:|---|---|---|
| 36 | [Arithmetic Functions](Experiments/36_arithmetic_functions.md) | User-defined functions, return values | [Debug 36](Debug/Debug_36_arithmetic_functions.md) |
| 37 | [Square Cube](Experiments/37_square_cube.md) | Functions with parameters | [Debug 37](Debug/Debug_37_square_cube.md) |
| 38 | [Largest Function](Experiments/38_largest_function.md) | Function returning the max | [Debug 38](Debug/Debug_38_largest_function.md) |
| 39 | [Function Overloading](Experiments/39_function_overloading.md) | Same name, different parameters | [Debug 39](Debug/Debug_39_function_overloading.md) |
| 40 | [Default Arguments](Experiments/40_default_arguments.md) | Default parameter values | [Debug 40](Debug/Debug_40_default_arguments.md) |
| 41 | [Factorial Recursion](Experiments/41_factorial_recursion.md) | Recursion, base case | [Debug 41](Debug/Debug_41_factorial_recursion.md) |
| 42 | [Fibonacci Recursion](Experiments/42_fibonacci_recursion.md) | Recursive calls | [Debug 42](Debug/Debug_42_fibonacci_recursion.md) |
| 43 | [Call By Value Reference](Experiments/43_call_by_value_reference.md) | Value vs reference parameters | [Debug 43](Debug/Debug_43_call_by_value_reference.md) |

## Section E — Arrays and Searching/Sorting

| No. | Experiment | Concepts Used | Debug Exercise |
|---:|---|---|---|
| 44 | [Array Read Display](Experiments/44_array_read_display.md) | 1-D arrays, loops | [Debug 44](Debug/Debug_44_array_read_display.md) |
| 45 | [Array Sum Average](Experiments/45_array_sum_average.md) | Accumulating over an array | [Debug 45](Debug/Debug_45_array_sum_average.md) |
| 46 | [Array Max Min](Experiments/46_array_max_min.md) | Finding extremes | [Debug 46](Debug/Debug_46_array_max_min.md) |
| 47 | [Even Odd Count](Experiments/47_even_odd_count.md) | Counting with conditions | [Debug 47](Debug/Debug_47_even_odd_count.md) |
| 48 | [Array Reverse](Experiments/48_array_reverse.md) | Two-index swapping | [Debug 48](Debug/Debug_48_array_reverse.md) |
| 49 | [Linear Search](Experiments/49_linear_search.md) | Searching with a flag | [Debug 49](Debug/Debug_49_linear_search.md) |
| 50 | [Array Sorting](Experiments/50_array_sorting.md) | Bubble sort | [Debug 50](Debug/Debug_50_array_sorting.md) |
| 51 | [Merge Arrays](Experiments/51_merge_arrays.md) | Combining arrays | [Debug 51](Debug/Debug_51_merge_arrays.md) |
| 52 | [Matrix Add Subtract](Experiments/52_matrix_add_subtract.md) | 2-D arrays | [Debug 52](Debug/Debug_52_matrix_add_subtract.md) |
| 53 | [Matrix Multiplication](Experiments/53_matrix_multiplication.md) | Triple nested loops | [Debug 53](Debug/Debug_53_matrix_multiplication.md) |
| 54 | [Matrix Transpose](Experiments/54_matrix_transpose.md) | Swapping row/column indices | [Debug 54](Debug/Debug_54_matrix_transpose.md) |

## Section F — Strings

| No. | Experiment | Concepts Used | Debug Exercise |
|---:|---|---|---|
| 55 | [String Length](Experiments/55_string_length.md) | `char` arrays, null terminator | [Debug 55](Debug/Debug_55_string_length.md) |
| 56 | [String Reverse](Experiments/56_string_reverse.md) | Reversing a string | [Debug 56](Debug/Debug_56_string_reverse.md) |
| 57 | [String Palindrome](Experiments/57_string_palindrome.md) | Comparing ends of a string | [Debug 57](Debug/Debug_57_string_palindrome.md) |
| 58 | [String Char Count](Experiments/58_string_char_count.md) | `getline`, character tests | [Debug 58](Debug/Debug_58_string_char_count.md) |
| 59 | [Word Count](Experiments/59_word_count.md) | Counting word boundaries | [Debug 59](Debug/Debug_59_word_count.md) |
| 60 | [String Concat Compare](Experiments/60_string_concat_compare.md) | `strcat`, `strcmp` | [Debug 60](Debug/Debug_60_string_concat_compare.md) |
| 61 | [Character Frequency](Experiments/61_character_frequency.md) | Frequency array | [Debug 61](Debug/Debug_61_character_frequency.md) |
| 62 | [Case Conversion](Experiments/62_case_conversion.md) | `toupper`, `tolower` | [Debug 62](Debug/Debug_62_case_conversion.md) |

## Section G — Pointers and References

| No. | Experiment | Concepts Used | Debug Exercise |
|---:|---|---|---|
| 63 | [Address Of Operator](Experiments/63_address_of_operator.md) | `&` operator | [Debug 63](Debug/Debug_63_address_of_operator.md) |
| 64 | [Pointer Access Modify](Experiments/64_pointer_access_modify.md) | Pointer declaration, dereferencing | [Debug 64](Debug/Debug_64_pointer_access_modify.md) |
| 65 | [Swap Using Pointers](Experiments/65_swap_using_pointers.md) | Pointer parameters | [Debug 65](Debug/Debug_65_swap_using_pointers.md) |
| 66 | [Pointer Arithmetic Array](Experiments/66_pointer_arithmetic_array.md) | Pointer increment over an array | [Debug 66](Debug/Debug_66_pointer_arithmetic_array.md) |
| 67 | [Pass By Reference](Experiments/67_pass_by_reference.md) | Reference parameters | [Debug 67](Debug/Debug_67_pass_by_reference.md) |
| 68 | [Array Pointer Relation](Experiments/68_array_pointer_relation.md) | Array name as a pointer | [Debug 68](Debug/Debug_68_array_pointer_relation.md) |

## Section H — Object-Oriented Programming

| No. | Experiment | Concepts Used | Debug Exercise |
|---:|---|---|---|
| 69 | [Student Class](Experiments/69_student_class.md) | Classes, objects, member functions | [Debug 69](Debug/Debug_69_student_class.md) |
| 70 | [Constructors](Experiments/70_constructors.md) | Default and parameterized constructors | [Debug 70](Debug/Debug_70_constructors.md) |
| 71 | [Copy Constructor](Experiments/71_copy_constructor.md) | Copying objects | [Debug 71](Debug/Debug_71_copy_constructor.md) |
| 72 | [Encapsulation](Experiments/72_encapsulation.md) | `private` data, `public` getters/setters | [Debug 72](Debug/Debug_72_encapsulation.md) |
| 73 | [Rectangle Class](Experiments/73_rectangle_class.md) | Class with area and perimeter | [Debug 73](Debug/Debug_73_rectangle_class.md) |
| 74 | [Bank Account Class](Experiments/74_bank_account_class.md) | Methods that modify state | [Debug 74](Debug/Debug_74_bank_account_class.md) |
| 75 | [Static Members](Experiments/75_static_members.md) | `static` data and functions | [Debug 75](Debug/Debug_75_static_members.md) |
| 76 | [Class Function Overloading](Experiments/76_class_function_overloading.md) | Overloaded member functions | [Debug 76](Debug/Debug_76_class_function_overloading.md) |

## Section I — Mini-Projects

| No. | Experiment | Concepts Used | Debug Exercise |
|---:|---|---|---|
| 77 | [Student Marks Management](Experiments/77_student_marks_management.md) | Arrays of structs, grade logic | [Debug 77](Debug/Debug_77_student_marks_management.md) |
| 78 | [Number Utility Menu](Experiments/78_number_utility_menu.md) | Menu-driven program with `do-while` and `switch` | [Debug 78](Debug/Debug_78_number_utility_menu.md) |
| 79 | [Simple Banking App](Experiments/79_simple_banking_app.md) | Classes, objects, menu loop | [Debug 79](Debug/Debug_79_simple_banking_app.md) |
| 80 | [Inventory Management](Experiments/80_inventory_management.md) | Vector of structs, menu loop | [Debug 80](Debug/Debug_80_inventory_management.md) |
