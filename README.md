# Stock-Analysis
Project to explore indicators that help a modelling and reporting buy/sell signal with probability of success from both fundamental and technical analysis.

## Discounted Cash Flow model

Notebook: [DCF](https://github.com/StevenC623/CPSC4820---Stock-Analysis/blob/main/Fundamental%20Analysis%20-%20DCF.ipynb)

Cash is what the firm needs in order to be able to pay bills, taxes, salaries and also to pay back to the company capital providers.

The company reported cash flow statements splits company activities into three parts. Investment activities, financing activities and operating activities. For the discounted cash flow method, we will mainly focus on the operating cash flow. Operating cash flow reflects all cash in and outflows related to the production and sale of the company goods and services.

To calculate the free cash flow, we would need the following parameters of the company

Net income

(+) Depreciation

(-) Increase in accounts receivable

(-) Increase in inventory

(-) Increase in other assets

(+) Increase in accounts payable

(+) Increase in other liabilities

Operating cash flow

(-) Purchases of equipment or capital expenditures

## Weighted Average Cost of Capital

Notebook: [WACC](https://github.com/StevenC623/CPSC4820---Stock-Analysis/blob/main/Fundamental%20Analysis%20-%20WACC.ipynb)

The WACC is a firm cost of capital. Is the capital rate that a firm is expected to pay on average to all its security holders. WACC uses cost of debt, cost of equity, capital structure of a firm and tax rate. A company capital structure is important to compute WACC since it uses the blended cost of capital across all sources of capital (i.e. cost of debt and cost of equity).

WACC is commonly used as a discount rate to calculate the net present value of a company. For example, when valuing a company using the Discounted Cash Flow model, we should use WACC to discount future free cash flows.

WACC is calculated using the below formula:

WACC = Kd (1 -Tc) (D /D+E) + Ke * (E /D+E)

Where:

WACC = Weighted Average Cost of Capital

Kd = Cost of debt

Tc = Tax effective rate

Ke = Cost of equity

D / D + E = Proportion of debt in firm capital structure

## Technical Analysis

### EMA
Notebook: [EMA](https://github.com/StevenC623/CPSC4820---Stock-Analysis/blob/main/EMA.ipynb)

The elastic moving average method uses the moving average price and threshold to indicate the trading signals. When the moving average prices are crossed from below, and the general trend of the moving average prices is uprising, the possibility that the stock price is rising, and vice versa.

### RSI
Notebook: [RSI](https://github.com/StevenC623/CPSC4820---Stock-Analysis/blob/main/RSI.ipynb)

### Fibonacci
Notebook: [Fibonacci](https://github.com/StevenC623/CPSC4820---Stock-Analysis/blob/main/Fibonacci.ipynb)
