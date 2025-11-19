# Workshop: Algorithm and Flowchart

For each question in this workshop, you must complete **two** things:

1.  **Write the pseudocode**
2.  **Draw the flowchart** using either
    - **Option 1:** Draw.io (recommended) → export image → upload to
      your repository → link it in this file
    - **Option 2 (optional):** Write a Mermaid flowchart directly in
      Markdown
    - **Option 3 (optional):** Any other valid method

👉 **IMPORTANT:** At the **bottom of each question**, add the
following sections:

### ✔ Pseudocode

### ✔ Flowchart

---

## 1. Check Even or Odd Number

Design an algorithm and flowchart that take a number as input and
determine whether it is even or odd.

### ✔ Pseudocode

```text
START
    INPUT number
    IF number % 2 == 0 THEN
        PRINT Even
    ELSE
        PRINT Odd
    ENDIF
END
```
---
### ✔ Flowchart

```mermaid
flowchart TD
    A([Start]) --> I[/Get input N/]
    I --> B{N % 2 == 0 ?}
    B -->|Yes| C[/Print Even/]
    B -->|No| D[/Print Odd/]
    C --> E([End])
    D --> E([End])
```

---

## 2. Calculate Total and Average Marks

Write the algorithm and draw the flowchart for a program that inputs
marks for 3 subjects, calculates the total and average, and displays
both.

```text
START
    INPUT mark1
    INPUT mark2
    INPUT mark3
    total = mark1 + mark2 + mark3
    average = total / 3
    DISPLAY "Total:", total
    DISPLAY "Average:", average
END
```

```mermaid
flowchart TD
    A([Start]) --> B[Input mark1, mark2, mark3]
    B --> C[total = mark1 + mark2 + mark3]
    C --> D[average = total/3]
    D --> E[DISPLAY Total and Average]
    E --> F([End])
```
---

## 3. Display Multiplication Table

Create an algorithm and flowchart that input a number and display its
multiplication table from 1 to 10 using a loop.

```text
START
    INPUT number
    SET i = 1
    WHILE i <= 10
    DISPLAY number, "*", i, "=", product
    i = i + 1
    ENDWHILE
END
```
```mermaid
flowchart TD
    A([Start]) --> B[Input number]
    B --> C[SET i = 1]
    C --> D{Is i ≤ 10?}
    D -- Yes --> E[product = number * i]
    E --> F[Display number * i = product]
    F --> G[i = i + 1]
    G --> D
    D -- No --> H([End])
  

```

---

## 4. Positive, Negative, or Zero Check

Write the algorithm and flowchart to input a number and display whether
it is positive, negative, or zero.

---

## 5. Simple Interest Calculator

Create an algorithm and flowchart for a program that calculates simple
interest using the formula:

**SI = (P × R × T) / 100**

- **P = Principal** → original amount of money
- **R = Rate of Interest** → percentage per year
- **T = Time** → number of years

---

## 6. Average Temperature Calculation

Write the algorithm and draw the flowchart for a program that takes the
temperature of 7 days, finds the average temperature, and displays it.

---

## 7. Calculate Area of a Rectangle

Create an algorithm and flowchart to input length and width, calculate
the area (**Area = Length × Width**), and display the result.

---

## 8. Determine Pass or Fail

Write the algorithm and draw the flowchart for a program that takes a
student's average marks and displays **"Pass"** if average ≥ 50,
otherwise **"Fail"**.

---

## 9. Calculate Factorial of a Number

Write the algorithm and draw the flowchart that input a number and
calculate its factorial using a loop.

---

## 10. Calculate Discount on Purchase

Write the algorithm and draw the flowchart for a program that inputs the
purchase amount and gives a **10% discount** if the amount is greater
than 1000.

---
