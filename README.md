# CN-Rail-DCF-Model
Built a full discounted cash flow (DCF) model and comparable companies analysis to value Canadian National Railway (TSX: CNR), one of North America's largest rail infrastructure operators.

Methodology

Sourced 5-year historical financials (2021–2025) directly from CN's SEC EDGAR filings (40-F)
Projected 5-year unlevered free cash flows using data-driven assumptions derived from historical trends
Calculated WACC of 7.53% using CAPM (β = 0.95, risk-free rate = 3.39%, ERP = 5.5%)
Applied Gordon Growth Model for terminal value assuming 2.0% long-run growth in line with North American GDP

Key Assumptions

Revenue growth: 2.0% (3-year avg ex-COVID ~1.4%, anchored to long-run GDP)
EBITDA margin: 49.3% (5-year avg excluding 2022 outlier)
Capex % of revenue: 19.0% (stabilizing at recent levels)
Tax rate: 27.0% (high end of observed range)

Findings

Implied share price: $104.18 vs market price of $139.75 (~25% premium to intrinsic value)
CN trades at 12.0x EV/EBITDA vs peer average of 14.7x — a discount on relative value
Sensitivity analysis shows fair value only achieved under WACC below 7.0% and terminal growth above 2.5%

Tools: Microsoft Excel, SEC EDGAR
