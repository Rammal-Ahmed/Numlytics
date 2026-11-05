# Numlytics

**Number Analysis & Statistics**

Numlytics is a small command-line program written in Python. You type in eight numbers, and it gives you back a neat results table with the smallest, largest, average, most repeated number, total, and how many of the numbers are even or odd.

I built it while learning Python and data analytics. It started as a simple "find the smallest number" exercise, and I kept adding to it until it became a proper little analysis tool.

## What it does

- Asks for eight whole numbers, one at a time (1st, 2nd, 3rd and so on)
- Finds the smallest and the largest number
- Calculates the average, rounded to two decimals
- Finds the most repeated number, or tells you when nothing repeats
- Adds up all the numbers
- Counts how many are even and how many are odd
- Prints everything in a results table that adjusts to its content

## Getting started

You need Python 3.8 or newer.

```bash
git clone https://github.com/your-username/numlytics.git
cd numlytics
python numlytics.py
```

## Example run

Input: `8, 69, 65, 12, 54, 65, 65, 6, 2`

```
=====================================================
                     NUMLYTICS
            Number Analysis & Statistics
=====================================================
+--------------------------------------+------------+
| RESULT                               |      VALUE |
+--------------------------------------+------------+
| Largest:                             |         69 |
| Smallest:                            |          2 |
| Average:                             |      38.44 |
| Most Repeated Number:                |         65 |
| Sum of these digits are:             |        346 |
| Total even numbers in these digits:  |          5 |
| Odd numbers spotted in these digits: |          4 |
+--------------------------------------+------------+
```

## How it works

1. The first number is stored as the starting "smallest" value and as the first item of a list.
2. A `for` loop asks for the remaining eight numbers, adds each one to the list, and updates the smallest whenever a lower number appears.
3. Once the list is complete, the program calculates the largest, average, sum, even/odd counts and the mode.
4. The width of the table is measured from the longest label and value, so the borders always line up.

## What I practised

- `input()` and `int()` for user input
- Lists and `append()`
- `for` loops with `range()`
- `if` / `else` conditions and the `%` operator
- `max()`, `sum()`, `len()` and `round()`
- Counting repeated values with `list.count()`
- A small helper function (turning 1, 2, 3 into 1st, 2nd, 3rd)
- Formatting output with f-strings

## Ideas for the next version

- Let the user choose how many numbers to enter
- Handle wrong input (letters or decimals) with `try` / `except`
- Add the median and the range
- Save the results to a text or CSV file

## About me

**Rammal Ahmed**

**AI & Data Science Enthusiast** | **Microsoft Dynamics 365 CRM Developer** | **Power Platform** | **UI/UX Designer** | **Graphic Designer & Illustrator**

[LinkedIn] www.linkedin.com/in/rammal-ahmed-58184b325 · [GitHub] https://github.com/Rammal-Ahmed


**I truly value your feedback and welcome any suggestions for improvement**

**Always open to fresh perspectives, constructive feedback, and new ideas**


## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**Project Status:** Completed
