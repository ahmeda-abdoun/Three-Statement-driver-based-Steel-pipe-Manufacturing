
# Driver-Based Three-Statement Financial Model — Steel Pipe Manufacturing

**Tool:** Excel | **Type:** FP&A / Financial Modeling | **Period:** 2022A–2026F

---

## What This Model Does

A fully integrated three-statement financial model for a multi-product steel pipe manufacturer (MidEast Pipes Co.), built the way it would be built in a real FP&A team — driver-based, forecast-ready, and structured so any change in a business assumption flows automatically through the full P&L, Balance Sheet, and Cash Flow Statement.

---

## Model Structure

### Assumptions Tab
The single source of truth for all inputs. Separated by product and cost type:

- **Three products:** Standard Pipe, Fancy Burn Pipes, Fittings
- **Per-product drivers:** Volume, Price
- **COGS drivers per product:** Raw Material, Direct Labor, Overhead
- **SG&A drivers:** Admin, S&M, R&A, Other Opex
- **Balance sheet drivers:** A/R days, Inventory days, A/P days
- **Fixed asset schedule:** Capex, depreciation, useful life
- **Debt schedule:** Loan amount, interest rate, annual repayment
- **Tax rate**

### Income Statement
Builds from product-level revenue through to Net Income across 3 historical periods (2022A–2024A) and 2 forecast years (2025F–2026F). Includes full COGS breakdown, Gross Profit, EBITDA, EBIT, and interest/tax calculations.

### Balance Sheet
Full asset and liability structure with working capital modeled from the assumption drivers. Includes a balance check to confirm Assets = Liabilities + Equity across all periods.

### Cash Flow Statement
Indirect method — reconciles from Net Income through operating, investing, and financing activities. Working capital movements flow directly from the balance sheet build.

---

## Key Design Decisions

**Driver-based, not hardcoded.** Every revenue and cost line is derived from a unit assumption. Change one volume or price input and the full model updates — this is how professional FP&A models are built for fast scenario testing.

**Historical + Forecast in one model.** Three actuals periods anchor the model in real performance before the forecast extends it — same structure used in investment banking and corporate finance.

**Working capital modeled properly.** A/R, Inventory, and A/P are calculated from days outstanding assumptions, not entered as plug numbers. This means cash flow responds correctly when the business grows.

---

## How to Use It

1. Open the **Assumptions** tab — all inputs live here
2. Change any volume, price, or cost driver
3. Watch the P&L, Balance Sheet, and Cash Flow update automatically
4. Use the forecast columns (2025F, 2026F) to test different business scenarios

---

## What This Demonstrates

- Three-statement modeling with full linkage
- Driver-based forecasting structure
- Working capital and cash flow mechanics
- Multi-product revenue and COGS build
- FP&A-standard model layout and assumption separation
