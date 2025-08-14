# M&A Accretion/Dilution Analysis – Excel Model

## Overview
This project models the EPS impact of a merger or acquisition to determine whether the transaction is **accretive** (increases EPS) or **dilutive** (decreases EPS) for the acquiring company.  
The model supports different deal structures, synergies, and financing mixes, allowing sensitivity testing on key assumptions.

---

## Features
- Buyer & Seller standalone inputs (share price, EPS, shares outstanding, P/E)
- Deal structure assumptions (cash %, stock %, synergies, tax rate, cost of debt)
- Pro forma net income and EPS calculation
- Accretion/Dilution status output
- Sensitivity tables for:
  - Synergies vs EPS impact
  - Deal structure mix (cash vs stock)

---

## Project Structure
- **Assumptions Tab** – Key inputs for buyer, seller, and deal parameters.
- **Pro Forma Combination Tab** – Merges financials, applies synergies, adjusts for financing.
- **Sensitivity Tab** – Two-way data tables to test assumption changes.
- **README Tab (Excel)** – In-model guide for usage.

---

## Methodology

1. **Inputs**  
   - Buyer and seller EPS, share price, shares outstanding, and P/E ratio.
   - Deal consideration split (% cash vs % stock).
   - Synergy estimates and tax rate.
   - Buyer’s cost of debt (only used if cash portion is debt-funded).

2. **Pro Forma Combination**  
   - Combine net income from buyer and seller.
   - Add after-tax synergies.
   - Deduct interest expense if debt-financed.
   - Calculate pro forma shares outstanding.
   - Compute pro forma EPS.

3. **Accretion/Dilution Analysis**  
   - Compare pro forma EPS to buyer’s standalone EPS.
   - Positive change → Accretion, Negative change → Dilution.

4. **Sensitivity Analysis**  
   - Table 1: Synergies vs EPS impact (holding deal mix constant).
   - Table 2: Deal mix (cash % vs stock %) vs EPS impact (holding synergies constant).

---

## How to Use
1. Download the Excel file from this repository.
2. Open the **Assumptions** tab and update inputs with your deal scenario.
3. View the **Pro Forma Combination** tab to see EPS changes.
4. Check the **Sensitivity** tab to see how results vary under different assumptions.

---

## Key Learnings
- How different deal structures affect post-merger EPS.
- How synergies influence accretion/dilution.
- The trade-off between cash financing and equity issuance.

---

**Note:** This model is simplified for educational purposes and omits complexities such as integration costs, changes in working capital, and advanced tax structuring.
