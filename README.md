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

### ✔ Pseudocode
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

### ✔ Flowchart
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

### ✔ Pseudocode
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

### ✔ Flowchart
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

### ✔ Pseudocode
```text
START
    INPUT number
    IF number > 0 THEN
        DISPLAY "Positive"
    ELSE IF number < 0 THEN
        DISPLAY "Negative"
    ELSE
        DISPLAY "Number is Zero"
    ENDIF
END
```
---

### ✔ Flowchart
```mermaid
flowchart TD
    A([Start]) --> B[Input number]
    B --> C{Is number > 0?}
    C -- Yes --> D[Display Positive]
    C -- No --> E{Is number < 0?}
    E -- Yes --> F[Display Negative]
    E -- No --> G[Display Number is Zero]
    D --> H([End])
    F --> H
    G --> H
```
---

## 5. Simple Interest Calculator

Create an algorithm and flowchart for a program that calculates simple
interest using the formula:
**SI = (P × R × T) / 100**

- **P = Principal** → original amount of money
- **R = Rate of Interest** → percentage per year
- **T = Time** → number of year

### ✔ Pseudocode
```text
START
    INPUT principal
    INPUT rate
    INPUT time
    SI = (principal * rate * time) / 100
    DISPLAY "Simple Interest: ", SI
END
```

### ✔ Flowchart
```mermaid
flowchart TD
    A([Start]) --> B[Input principal]
    B --> C[Input rate]
    C --> D[Input time]
    D --> E[Compute SI = principal * rate * time / 100]
    E --> F[Display Simple Interest]
    F --> G([End])
```
---

## 6. Average Temperature Calculation

Write the algorithm and draw the flowchart for a program that takes the
temperature of 7 days, finds the average temperature, and displays it.

```text
START
    INPUT  total temperature 
    INPUT number of days 
    Average Temperatures = total temperature / number of days
    Display "Average Temperature: "; average temperature
END

```
### ✔ Flowchart

```mermaid
flowchart TD
    A([Start]) --> B[Input  total temperature]
    B --> C[number of days]
    C --> D{Average Temperatures = total temperature/number of days}
    D --> E[Display Average Temperature]
    E --> F([End])
```
---

## 7. Calculate Area of a Rectangle

Create an algorithm and flowchart to input length and width, calculate
the area (**Area = Length × Width**), and display the result.

### ✔ Pseudocode
```test
    START
    INPUT length
    INPUT width
    Area = length × width
    Display "Area:, " area
END
```

```mermaid
flowchart TD
    A([Start]) --> B[INPUT length]
    B --> C[INPUT width]
    C --> D[compute area = length * width]
    D --> E[Display Area]
    E --> F([END])
```
---

## 8. Determine Pass or Fail

Write the algorithm and draw the flowchart for a program that takes a
student's average marks and displays **"Pass"** if average ≥ 50,
otherwise **"Fail"**.

### ✔ Pseudocode

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
