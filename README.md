# Titan Company Ltd: DCF Valuation Model

An Excel financial model of Titan Company Ltd (NSE: TITAN, BSE: 500114). It analyses ten years of financials, tests the company's financial health, and values it three ways: discounted cash flow, comparable companies, and market risk. The results come together in a football field chart.

The model covers FY17 to FY26 and forecasts FY27 to FY31. All figures are in ₹ crore unless stated otherwise.

> This project is for educational purposes only and is not investment advice.

## What the model contains

| Area | What it does |
|---|---|
| Historical financials | Ten years of income statement, balance sheet and cash flow, with common-size lines |
| Ratio analysis | 30+ growth, margin, return, turnover, working-capital and cash-flow ratios with trend sparklines, mean and median |
| DuPont analysis | ROE split into net margin, asset turnover and financial leverage, plus ROA, with a dashboard |
| Altman Z-score | Five-ratio financial stability test, FY20 to FY26, with a dashboard |
| Forecasting | Linear-trend forecasts of sales, EBITDA and EPS for FY27 to FY31 |
| WACC | Peer-based beta (unlevered, then relevered), CAPM cost of equity, cost of debt |
| Beta regression | Two years of weekly Titan and Nifty returns with regression output |
| Intrinsic growth | ROIC and reinvestment rate, used to derive the expected growth rate |
| DCF | FCFF forecast, mid-year discounting, terminal value, equity value per share and a sensitivity table |
| Relative valuation | Ten listed jewellery and watch peers on EV/Revenue, EV/EBITDA and P/E |
| Football field | Valuation ranges from comps, DCF scenarios and the 52-week price range on one chart |
| Value at Risk | One-day VaR by the historical method and by a 10,000-run Monte Carlo simulation |

## Sheet guide

| Sheet | Contents |
|---|---|
| `Executive Summary` | Company snapshot, brands, market data and projection period |
| `Assumptions` | Every key input in one place, each with its source or reasoning |
| `Historical_FS` | Income statement, balance sheet and cash flow, FY17 to FY26 |
| `Du Pont Analysis` | Dashboard charts plus ROE and ROA decomposition, FY20 to FY26 |
| `Altman Z score` | Dashboard charts plus the five Z-score ratios and final score |
| `Financials>` | Ratio analysis |
| `Forecasting` | Sales, EBITDA and EPS trend forecasts |
| `WACC` | Peer table, capital structure, cost of debt, cost of equity, WACC |
| `Beta-Regression` | Weekly return data and regression statistics |
| `Rm` | Nifty annual returns, 2000 to 2025, used for the market return |
| `Intrinsic Growth` | Invested capital, ROIC, reinvestment rate and growth |
| `DCF` | FCFF, terminal value, equity value per share, sensitivity table |
| `Relative_Valuation` | Comparable company multiples and implied value per share |
| `Football Field Analysis` | Chart data and the football field chart |
| `VaR` | Historical VaR on daily returns, January 2024 to October 2026 |
| `Mont_Carlo` | Monte Carlo VaR using 10,000 simulated daily returns |
| `Data Sheet`, `Data2`, `Raw Data`, `Cash Flow Data` | Source data. Do not edit `Data Sheet` directly |

## Key assumptions

| Assumption | Value | Basis |
|---|---|---|
| Valuation date | 31 March 2026 | Latest balance sheet |
| Tax rate | 25.17% | 22% base, 10% surcharge, 4% cess |
| Risk-free rate | 7.20% | India 10-year government bond yield |
| Market return | 16.45% | Average Nifty annual return 2000 to 2025, plus dividend yield |
| Equity risk premium | 9.25% | Market return minus risk-free rate |
| Beta | 1.20 | Median unlevered peer beta, relevered at target debt/equity |
| Cost of equity | 18.30% | CAPM |
| Post-tax cost of debt | 2.88% | Interest expense ÷ total debt, after tax |
| Capital structure | 91.5% equity, 8.5% debt | Peer median |
| **WACC** | **16.99%** | |
| Growth, FY27 to FY31 | 21.06% | Median intrinsic growth (reinvestment rate × ROIC) |
| Reinvestment rate | 75% | Share of NOPAT reinvested each year |
| Terminal growth | 5.75% | Long-run nominal growth of the Indian economy |
| Terminal ROIC | 16.99% | Set equal to WACC |
| Discounting | Mid-year convention | |

## Key outputs

### DuPont analysis

| | FY23 | FY24 | FY25 | FY26 |
|---|---|---|---|---|
| Net profit margin | 8.01% | 6.84% | 5.52% | 5.79% |
| Asset turnover | 1.68x | 1.74x | 1.67x | 1.73x |
| Financial leverage | 2.28x | 2.76x | 3.43x | 3.70x |
| **Return on equity** | **30.7%** | **32.9%** | **31.8%** | **37.1%** |
| Return on assets | 13.5% | 11.9% | 9.2% | 10.0% |

ROE is at its highest in the period. The rise since FY23 comes from higher financial leverage, while net margin and return on assets have fallen.

### Altman Z-score

| | FY23 | FY24 | FY25 | FY26 |
|---|---|---|---|---|
| Working capital ÷ Total assets | 0.58 | 0.60 | 0.65 | 0.59 |
| Retained earnings ÷ Total assets | 0.44 | 0.29 | 0.28 | 0.26 |
| EBIT ÷ Total assets | 0.18 | 0.17 | 0.14 | 0.13 |
| Market cap ÷ Borrowings | 23.8 | 21.7 | 13.1 | 11.5 |
| Sales ÷ Total assets | 1.50 | 1.62 | 1.49 | 1.45 |
| **Z-score** | **17.8** | **16.5** | **11.1** | **10.0** |
| Financial stability | Strong | Strong | Strong | Strong |

A score above 3 indicates a financially strong company. Titan stays well above that level in every year, although the score has come down as borrowings have grown.

### DCF

| Item | ₹ crore |
|---|---|
| PV of FCFF, FY27 to FY31 | 8,958 |
| PV of terminal value | 47,705 |
| Value of operating assets | 56,663 |
| Add: cash | 1,917 |
| Less: debt | 27,448 |
| Value of equity | 31,132 |
| Shares outstanding (crore) | 88.78 |
| **Equity value per share** | **₹351** |
| Market price (1 October 2026) | ₹4,516 |

### Relative valuation

Peer median multiples applied to Titan:

| Multiple | Peer median | Titan | Implied value per share |
|---|---|---|---|
| EV/Revenue | 2.9x | 4.6x | ₹2,737 |
| EV/EBITDA | 24.5x | 42.1x | ₹2,436 |
| P/E | 40.8x | 68.1x | ₹2,645 |

### Value at Risk

One day, on a price of ₹4,406:

| Confidence | Historical | Monte Carlo |
|---|---|---|
| 95% | 2.1% (₹92) | about 2.4% (₹104) |
| 99% | 3.5% (₹156) | about 3.3% (₹145) |
| 99.5% | 5.5% (₹242) | about 3.6% (₹158) |

Monte Carlo figures use `RAND()` and change each time the workbook recalculates.

## How to use

1. Download `TITAN_COMPANY_DCF_MODEL.xlsx` and open it in Microsoft Excel 2016 or later. The model uses data tables, sparklines and a stock chart, which may not display correctly in Google Sheets or LibreOffice.
2. Start at `Executive Summary`, then `Assumptions`.
3. Change inputs in `WACC`, `Intrinsic Growth` and `DCF`. Most cells in `Assumptions` are linked to those sheets; the reinvestment rate is entered there directly.
4. Press F9 to recalculate the sensitivity table and the Monte Carlo simulation.

## Data sources

- Financial statements and peer data: [Screener.in](https://www.screener.in/)
- Share prices and Nifty index levels: NSE
- Risk-free rate: India 10-year government bond yield

## Disclaimer

This model was built for learning and portfolio purposes. It is not a recommendation to buy, sell or hold any security. Please check figures against company filings before using them.
