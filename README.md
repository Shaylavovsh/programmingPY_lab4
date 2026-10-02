# Laboratory Practice n. 4 - Python (Exercises 1-4)

Turin Polytechnic University in Tashkent - Course of Computer Science

## Getting started in GitHub Codespaces

Each exercise has its own Python file. Open the file you are working on and use the **Run Python File** button in the top-right corner of the editor. The program runs in the terminal below the editor.

You can also run a file from the terminal:

```bash
python ex1.py
```

Replace `ex1.py` with the file you want to test. Do not rename the provided files.

Before the deadline, commit and push your work:

```bash
git add .
git commit -m "Solve lab 4"
git push
```

Only work pushed to GitHub is graded. Read input with `input()` and display output with `print()`.

---

## Exercise 1 - Number series

Write a program that displays the following two series of numbers, one after the other. Replace the dots with the appropriate numbers.

First series:

```
(0,0) (0,1) (0,2) (0,3) ... (0,9)
(1,0) (1,1) (1,2) (1,3) ... (1,9)
(2,0) (2,1) (2,2) (2,3) ... (2,9)
...
(9,0) (9,1) (9,2) (9,3) ... (9,9)
```

Second series:

```
0  1  2  3  ... 9
10 11 12 13 ... 19
20 21 22 23 ... 29
...
90 91 92 93 ... 99
```

Write the solution in `ex1.py`.

## Exercise 2 - Figures

Read a positive integer `n`. Write the programs to produce each figure below, using `n` as the side length.

Write all Exercise 2 solutions in `ex2.py`.

For `n = 4`, the figures are:

```text
****     ****     ****     *+++     *  *
***       ***     *  *     -*++      **
**         **     *  *     --*+      **
*           *     ****     ---*     *  *
```

For `n = 5`, the figures are:

```text
*****     *****     *****     *++++     *   *
****       ****     *   *     -*+++      * *
***         ***     *   *     --*++       *
**           **     *   *     ---*+      * *
*             *     *****     ----*     *   *
```

## Exercise 3 - Repeated asterisks

Write a program that repeatedly reads an integer `n`.

- If `n > 0`, display `n` asterisks on one row, then ask for another value.
- If `n <= 0`, stop the program.

Example:

```text
Input n: 5
*****
Input n: 13
*************
Input n: 2
**
Input n: -3
Execution terminated.
```

Write the solution in `ex3.py`.

## Exercise 4 - Floyd's triangle

Floyd's triangle is formed by consecutive integers arranged in rows:

```text
1
2  3
4  5  6
7  8  9  10
11 12 13 14 15
...
```

### Part 1 - First n rows

Read a strictly positive integer `n` and display the first `n` rows of Floyd's triangle. Write the solution in `ex4.py`.

For `n = 3`:

```text
1
2  3
4  5  6
```

For `n = 4`:

```text
1
2  3
4  5  6
7  8  9  10
```

### Part 2 - First n numbers

Write another program that reads a strictly positive integer `n` and prints only the first `n` numbers of Floyd's triangle. Write this second solution in `ex4.py`, below the first one.

For `n = 5`:

```text
1
2  3
4  5
```

For `n = 7`:

```text
1
2  3
4  5  6
7
```
