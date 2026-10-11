# Equity-Research-and-DCF-Valuation
# Paradeep Phosphates (NSE: PARADEEP): DCF Valuation and Equity Research Note

A five-year discounted cash flow model and one-page investment note on Paradeep Phosphates Ltd, an Indian phosphatic fertilizer manufacturer. Built in Excel from public financial data (Screener.in, consolidated).

## Conclusion
The DCF does not support the current price. The base case values the stock at **₹66 per share against ₹146.75**, and even the bull case (₹118) sits below the market. A peer EV/EBITDA cross-check gives ₹85. The market is paying for margins and growth above what a conservative model supports.

| Method | Value per share (₹) | vs price ₹146.75 |
|---|---|---|
| DCF: Bear | 22 | -85% |
| **DCF: Base** | **66** | **-55%** |
| DCF: Bull | 118 | -20% |
| Peer median EV/EBITDA (6.7x) | 85 | -42% |

The market values the company at about 9.5x trailing EBITDA, against 5.8x implied by the base DCF and a 6.7x median for four fertilizer peers.

## Thesis
- **Strong profit growth:** FY2026 revenue ₹21,826 cr (+28.7%), EBITDA margin 10.1% (FY22-26 average 8.0%), net profit ₹996 cr (+50%). Q1 FY2027 EBITDA margin was 11.8%, which supports the bull case.
- **Weak cash conversion:** working capital rose to 23.7% of sales in FY2026 and operating cash flow was -₹1,012 cr. It was negative in four of the last eight years.
- **Leverage:** net debt ₹6,490 cr (2.9x FY2026 EBITDA), interest ₹528 cr (EBITDA covers interest 4.2x).
- **Valuation:** the stock trades above three of the four peers on EV/EBITDA, and no combination of WACC and terminal growth in the sensitivity grid reaches the current price (maximum ₹137).

## Model (base case)
| Assumption | FY27E | FY28E | FY29E | FY30E | FY31E |
|---|---|---|---|---|---|
| Revenue growth | 12% | 9% | 8% | 7% | 6% |
| EBITDA margin | 9.5% | 9.0% | 8.75% | 8.5% | 8.5% |
| Capex % of sales | 3.0% | 3.0% | 2.75% | 2.5% | 2.5% |
| Net working capital % of sales | 22% | 21% | 20% | 19% | 18% |

Depreciation 1.9% of sales, tax 25%, terminal growth 4%. **WACC 11.6%**: risk-free 6.7%, equity risk premium 5.5%, beta 1.3, pre-tax cost of debt 8.8%, debt weight 31% at market values. Free cash flow to firm is discounted at year end from the 31 March 2026 balance sheet. Terminal value is 71% of enterprise value.

**Sensitivity (base case):** value per share ranges from ₹35 to ₹137 across WACC of 9.6% to 13.6% and terminal growth of 3% to 5%.

## Peer cross-check (EV/EBITDA)
Chambal Fertilisers 5.3x, Coromandel International 14.6x, Rashtriya Chemicals & Fertilizers 8.1x, GSFC 5.1x. Median 6.7x applied to trailing EBITDA of ₹2,292 cr gives an enterprise value of ₹15,274 cr and ₹85 per share.

## Key risks
- Government subsidy and policy changes, which drive fertilizer revenue and margins.
- Input price and currency swings on imported raw materials.
- Working capital and debt, which can absorb cash even when profits rise.
- Upside risk: margins holding at recent quarterly levels (11.8%) for longer than assumed.

## Limitations
- Forecast assumptions are judgement-based and the valuation is sensitive to them.
- Net working capital is a proxy (receivables + inventory - other liabilities).
- Risk-free rate and beta are inputs to be refreshed; end-of-year discounting is a simplification.
- Educational analysis, not investment advice.

## Files
`Paradeep_Phosphates_DCF.xlsx`: Guide, Historical (Screener data and ratios with a reconciliation check), WACC, DCF (bear/base/bull selector), Sensitivity, Cross-Check.

## Tools
Excel (financial modelling, scenario analysis, sensitivity tables), Screener.in data

## Author
Satyam Arora | [LinkedIn Profile](https://www.linkedin.com/in/satyam-arora-b83a3648)
