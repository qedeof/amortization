🧮 Universal Amortization Solver

A fully responsive, educational, and interactive web application designed to break down and solve the standard textbook amortization formula.

Unlike typical calculators that only find your monthly payment, this tool is a universal solver: enter any four variables, and the application will instantly calculate the fifth.

📐 The Amortization Formula

This solver is built around the exact mathematical formula used in modern finance textbooks:

$$A = P \left[ \frac{1 - \left(1 + \frac{r}{n}\right)^{-nt}}{\frac{r}{n}} \right]$$

Variable Guide

$A$ = Loan Amount (Present Value) — The starting principal borrowed.

$P$ = Payment per Period — The amount paid at each compounding interval.

$r$ = Annual Interest Rate — The yearly interest rate (expressed as a decimal in formulas, entered as a percentage in the UI).

$n$ = Payments per Year — Compounding/payment frequency (e.g., $12$ for monthly, $26$ for bi-weekly, $4$ for quarterly).

$t$ = Term in Years — The total life span of the loan.

✨ Features

Solve for Any Variable ($A$, $P$, $r$, $n$, $t$): Dynamically choose your target variable from a dropdown. The interface automatically adapts, locking the selected variable and marking it for auto-calculation.

Advanced Numerical Solving: Since variables like $r$ (Interest Rate) and $n$ (Payments per Year) cannot be isolated algebraically in the formula, the application implements a robust Bisection Algorithm (numerical method) to converge on mathematically precise solutions.

Dynamic Amortization Schedule: Generates a complete, highly optimized payment-by-payment schedule showing exactly how much of each payment goes toward the Principal vs. Interest, alongside a running total of interest paid and the remaining balance.

Visual Breakdown: Rendered using Chart.js, a premium-designed doughnut chart displays a breakdown of the total cost of your loan (Total Principal vs. Total Interest Paid).

Beautiful Mathematical Typesetting: Leverages the high-performance KaTeX library to render the textbook formula dynamically with native mathematical typesetting.

No Server/Zero Dependencies: Built entirely with vanilla JavaScript, HTML5, and Tailwind CSS. The app runs fully client-side inside a single index.html file.
