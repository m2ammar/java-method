# Java Methods – Lab Tasks

A collection of beginner Java programs written as lab exercises, demonstrating the use of methods, user input handling, and basic logic.

---

## Files

### `Labtask1pf.java`
A simple interactive program that collects user information via the console — name, age, favorite color, the day, temperature, city, and country — and prints formatted responses for each input.

**Concepts:** `Scanner`, `nextLine()`, `nextInt()`, string concatenation

---

### `Multimethods.java`
Demonstrates the use of multiple static methods in a single class.

| Method | What it does |
|---|---|
| `calculateSum(int a, int b)` | Returns the sum of two integers |
| `findArea(double length, double width)` | Returns the area of a rectangle |
| `findSquare(int num)` | Returns the square of a number |
| `calculateInterest(float p, float r, float t)` | Returns simple interest using `(P × R × T) / 100` |
| `findAverage(int num1, int num2, int num3)` | Returns the average of three integers |

**Concepts:** Static methods, return types, `float`, `double`, `int`

---

### `MultiRToP.java`
A car rental simulation that uses four static methods to handle different parts of the rental process.

| Method | What it does |
|---|---|
| `retRent(double rent, int days)` | Calculates and returns total rental cost |
| `carAvail(String name)` | Checks if a car name exists in a predefined list |
| `discount(double amount)` | Applies a tiered discount (10%, 20%, or 50%) based on the amount |
| `receipt(String name, int days, double total)` | Prints a formatted rental receipt |

**Concepts:** Static methods, arrays, `for-each` loop, `equalsIgnoreCase()`, conditional logic

---

## How to Run

1. Open the project in **IntelliJ IDEA**
2. Navigate to `src/`
3. Run the desired `.java` file
4. Follow the prompts in the console

> Requires **Java 8** or higher

---

## Author

**Muhammad Ammar Saleem** – [@m2ammar](https://github.com/m2ammar)  
BSCS Data Science Student
