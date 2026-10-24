# Interest Calculator

A free, single-page calculator for Indian savings accounts, fixed deposits (FD) and recurring deposits (RD). It shows interest earned, TDS and the income tax you owe under both the old and new tax regimes.

**Live page:** `https://rustybinary.github.io/interest-calculator/`

## What it does

- **Savings:** slab-wise interest on the daily closing balance. Add, remove and edit slabs and rates. Choose when interest is credited or paid out.
- **Fixed deposit:** quarterly compounding or monthly and quarterly payouts, with rates picked from an editable rate card by tenure and age.
- **Recurring deposit:** monthly instalments with the same editable rate card.
- **TDS and income tax:** bank TDS thresholds for FD and RD (₹50,000, or ₹1,00,000 for senior citizens), the PAN rate, and Form 121 guidance. A step-by-step statement shows income, deductions, slab-wise tax, rebate, cess and the extra tax caused by the interest, for each financial year and each regime.

## Privacy

Everything runs in your browser. Nothing you enter is sent anywhere.

## Run it locally

Open `index.html` in a browser. There is no build step and no dependencies. It loads fonts from Google Fonts.

## Update rates or tax rules

Rate cards are editable on the page. Default rates and tax slabs are written in `index.html`. Edit them and commit the file to update the live page.

## Accuracy

The calculator's FD and RD results were compared with a bank's published calculator for a few cases (day count, quarterly compounding, rounding). Other banks differ in credit dates, rounding and slab rules. Tax rules shown are for FY 2026-27 and come from third-party sources. This is an estimate, not tax or financial advice. Check final figures with your bank statement and a tax adviser.

## Licence

MIT. See `LICENSE`.
