# JavaScript Star Pattern Art Generator

## Overview

This project demonstrates advanced pattern printing in JavaScript using nested loops and mathematical conditions.

The program generates a unique star (`*`) design by combining:

* Borders
* Horizontal lines
* Vertical lines
* Diagonal lines
* Center lines
* Symmetrical pattern logic

The output creates an artistic geometric structure using only characters and console output.

---

## Features

* Pattern generation using nested loops
* Symmetrical star design
* Mathematical coordinate calculations
* Border creation
* Diagonal pattern drawing
* Center row and column highlighting
* Console-based visualization

---

## Technologies Used

* JavaScript (ES6)
* Nested Loops
* Conditional Statements
* Console Output

---

## Project Structure

```text
project/
│
├── main.js
└── README.md
```

---

## How It Works

The program:

1. Creates an 11 × 11 grid.
2. Iterates through rows and columns.
3. Uses mathematical conditions to determine star positions.
4. Prints `*` for matching coordinates.
5. Prints spaces elsewhere.
6. Displays a complete geometric pattern.

### Grid Size

```javascript
let n = 11;
```

---

## Core Concepts Used

### Border Conditions

```javascript
i == 0 || i == n - 1
j == 0 || j == n - 1
```

### Center Line Conditions

```javascript
i == Math.floor(n / 2)
j == Math.floor(n / 2)
```

### Main Diagonal

```javascript
i == j
```

### Secondary Diagonal

```javascript
i + j == n - 1
```

### Additional Diagonal Logic

```javascript
i + j == Math.floor(n / 2)
i - j == Math.floor(n / 2)
```

These conditions combine to create the final design.

---

## Sample Output

```text
* * * * * * * * * * *
* *     * * *     * *
*   * *   *   * *   *
*   * *   *   * *   *
* *     * * *     * *
* * * * * * * * * * *
* *     * * *     * *
*   * *   *   * *   *
*   * *   *   * *   *
* *     * * *     * *
* * * * * * * * * * *
```

---

## Learning Outcomes

This project helps in understanding:

* Nested Loops
* Coordinate-Based Pattern Printing
* Symmetry in Programming
* Mathematical Pattern Design
* JavaScript Logic Building
* Console Rendering Techniques

---

## Time Complexity

```text
O(n²)
```

The program checks every row and column position once.

---

## Space Complexity

```text
O(1)
```

Only a few variables are used.

---

## How to Run

### Using Node.js

```bash
node main.js
```

### Online Compiler

Copy and paste the code into:

* Programiz
* OneCompiler
* Replit
* JSFiddle

and run it.

---

## Possible Enhancements

* User-defined pattern size
* Hollow pattern variations
* Colored console output
* HTML Canvas visualization
* Interactive web version
* Pattern export feature

---

## Author

Supraja Shetty

---

## License

This project is open-source and intended for educational and learning purposes.
