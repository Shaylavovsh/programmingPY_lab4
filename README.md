# Laboratory Practice n. 3 — Python (Exercises 4–7)

Turin Polytechnic University in Tashkent — Course of Computer Science

## How to submit

1. Write your solution for each exercise in its own file:

   | Exercise | File |
   |----------|------|
   | 4 | `ex4.py` |
   | 5 | `ex5.py` |
   | 6 | `ex6.py` |
   | 7 | `ex7.py` |

2. Run each program and check it against the example in the exercise:

   ```bash
   python ex5.py
   ```

   In GitHub Codespaces, choose **Terminal > Run Task** and select the matching
   `Run exN.py` task to run an exercise in the integrated terminal.

3. Commit and push your work before the deadline:

   ```bash
   git add .
   git commit -m "Solve lab 3"
   git push
   ```

Only work that has been pushed to GitHub is graded. Do not rename the files.

Read input from the keyboard with `input()` and show results with `print()`.

---

## Exercise 4

Write a Python program that prints a table of the decimal ASCII codes for every letter of the English alphabet, both small and capital.

The table must have **26 rows and 4 columns**. Each row shows a small letter, its ASCII code, the matching capital letter, and its ASCII code.

Use an iterative statement (a loop) to solve this problem.

**Example** (first and last lines of the output):

```
'a' 97   'A' 65
'b' 98   'B' 66
'c' 99   'C' 67
'd' 100  'D' 68
...
'z' 122  'Z' 90
```

## Exercise 5

Write a Python program that:

- reads two positive integer numbers `x` and `y`;
- computes the greatest common divisor (gcd) of `x` and `y`;
- prints that value.

The gcd of `x` and `y` is the largest integer `v` that divides both `x` and `y` with a remainder of 0.

Use **Euclid's method**:

1. Given `x` and `y`, let `M` be the larger and `m` the smaller of the two.
2. Let `r` be the remainder of dividing `M` by `m`: `r = M % m`.
3. If `r` is 0, then `m` is the gcd.
4. If `r` is not 0, replace `M` with `m` and `m` with `r`, then go back to step 2.

**Example:** with `x = 15` and `y = 40`, the divisions are `40 % 15 = 10`, `15 % 10 = 5`, `10 % 5 = 0`. So the gcd of 15 and 40 is **5**.

## Exercise 6

Write a Python program that:

- reads a positive integer number `n`;
- reads `n` integer values, then:
  - prints `ascending sequence` if every number after the first is larger than the one before it;
  - prints `descending sequence` if every number after the first is smaller than the one before it;
  - prints `neither ascending nor descending sequence` if neither condition holds.

**Example:** with `n = 10` and the numbers `-2 5 7 13 18 24 40 56 90 137`, the program prints `ascending sequence`.

## Exercise 7

Write a Python program that:

- reads an integer number `n`, at least 2;
- reads `n` real values from the keyboard;
- finds the two largest values and prints them (in any order).

**Example:** with `n = 9` and the values `1.5 3.8 14.3 0.0 -2.1 78.1 -5.9 4.4 9.2`, the program prints **78.1** and **14.3**.
