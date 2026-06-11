# Loan Amortization Visualizer

A single-file browser tool that takes a loan amount, an annual interest rate, a term in years, and an optional extra monthly payment, and shows the monthly payment, the total interest, the total paid, and how the balance falls over the term. If you add an extra payment, it shows how much sooner the loan is paid off and how much interest that saves.

**Live demo:** https://0xelitesystem.github.io/loan-amortization-visualizer/

It runs entirely in the browser. Nothing is uploaded, stored, or tracked.

## What it shows

- Monthly payment for the loan as entered
- Total interest and total paid over the life of the loan
- A chart of the remaining balance over time, with the running interest paid alongside it
- With an extra payment: the time and interest saved against paying the minimum

## How to use

Open `index.html` in any browser, or visit the GitHub Pages URL. Enter the amount, rate, term, and optionally an extra monthly payment. Everything recalculates as you type. If the payment does not cover the monthly interest, the tool says so rather than drawing a balance that never falls.

## Not financial advice

This is a planning calculator, not financial advice and not a loan offer. It assumes a fixed rate and the same payment every month, which real loans rarely hold exactly. Confirm any real loan's terms with the lender.

## License

MIT. Copyright (c) 2026 0xelitesystem.
