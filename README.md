# 🧮 Universal Amortization Solver

A powerful, single-page web application that not only calculates loan payments but can universally solve for *any* missing variable in the amortization formula. Designed as both a practical financial tool and an educational resource.

## ✨ Features

* **Universal Variable Solving:** Don't just calculate payments. Enter any 4 variables and let the app solve for the 5th—whether it's the Principal (A), Payment (P), Annual Rate (r), Payments per Year (n), or Loan Term (t).
* **Advanced Numerical Methods:** Uses a custom Bisection Algorithm to accurately solve for complex variables like Interest Rate and Compounding Frequency.
* **Dynamic Amortization Schedule:** Automatically generates a comprehensive, row-by-row breakdown of every payment, detailing principal, interest, and remaining balance.
* **Visual Breakdown:** Integrates `Chart.js` for an interactive doughnut chart showing the true cost of the loan (Principal vs. Total Interest).
* **Educational Display:** Renders the complex textbook amortization formula beautifully using `KaTeX`, helping students understand the math behind their loans.
* **Zero Dependencies:** A purely front-end application contained within a single `index.html` file. No build steps, no Node modules, no server required.
