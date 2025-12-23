Hello! That is a very comprehensive list of requirements for a stock analysis prompt. To create the optimized prompt, I'll structure it clearly, specify the data requirements, and outline the analysis sections.

Since this analysis requires fetching and processing **real-time and historical financial data** for a specific stock (including prices, revenue, profit, dividends, and various financial multiples), and then conducting a detailed qualitative analysis (overview, industry, news, investment thesis, risks, opportunities, and analyst consensus), I will first need the name of the stock or the company you want to analyze.

I will formulate a high-quality prompt template that you can use. Note that the AI's ability to fulfill all data points (especially the full 10-year history for all items and the specific multiples table) will depend on the publicly available information it can access at that moment.

Here is the optimized prompt template:

---

## Optimized Stock Analysis Prompt Template

**INSTRUCTIONS:** Analyze the stock with the ticker **[INSERT STOCK TICKER HERE, e.g., AAPL or PETR4.SA]** using current and historical financial data. The final output must be structured, detailed, and address all the points listed below.

### 1. Financial Data and Key Metrics

Retrieve the following financial data and present it clearly:

| Metric                    | Required Data/Period                                                                                                        |
| :------------------------ | :-------------------------------------------------------------------------------------------------------------------------- |
| **Current Price**         | Real-time or latest available closing price.                                                                                |
| **Price Range**           | Minimum and maximum price over the last 52 weeks.                                                                           |
| **Historical Financials** | **Revenue, Profit, and Dividends Distributed** for the last 10 available fiscal years (or since IPO if less than 10 years). |

### 2. Multiples and Growth Table

Create a historical table (10 years, 5 years, and 3 years when applicable) and latest available values for the following multiples and metrics (use the English terms):

| Brazilian Portuguese Term                    | English Term                                                                      |
| :------------------------------------------- | :-------------------------------------------------------------------------------- |
| P/L                                          | Price-to-Earnings (P/E)                                                           |
| P/VP                                         | Price-to-Book (P/B)                                                               |
| DY                                           | Dividend Yield (DY)                                                               |
| Earning Yield                                | Earnings Yield (EY)                                                               |
| Preço de Graham                              | Graham Price (or Graham Number)                                                   |
| CAGR lucros últimos 10 anos, 5 anos e 3 anos | Compound Annual Growth Rate (CAGR) of **Profits** for the last 10, 5, and 3 years |
| Dívida/EBITDA                                | Net Debt/EBITDA                                                                   |
| Dívida/EV                                    | Net Debt/Enterprise Value (EV)                                                    |
| Lucro                                        | Profit (Latest TTM)                                                               |
| EV                                           | Enterprise Value (EV) (Latest)                                                    |
| Payout de Dividendos                         | Dividend Payout Ratio                                                             |
| Margem Líquida                               | Net Margin (Latest TTM)                                                           |
| Crescimento do Estoque                       | **Stock Price Growth** (1-year, 5-year, and 10-year return)                       |

**Classification:** Based on its **Market Capitalization** (or **Enterprise Value**), classify the company's size (e.g., small-cap, mid-cap, large-cap, blue chip).

### 3. Financial Analysis and Benchmarks

- Provide a **general overview analysis of the Multiples** based on industry or market benchmarks.
- **Identify** any multiple that appears significantly "bad" (e.g., extremely high P/E, negative Net Margin, high Debt/EBITDA).
- For each "bad" multiple, **bring potential reasons** or contextual factors that could explain its current value.

### 4. Qualitative and Strategic Analysis

- **Latest Relevant Facts:** Summarize the most recent and impactful news, M&A activity, earnings calls highlights, or regulatory changes affecting the company or stock.
- **Industry/Sector Analysis:** Analyze the company's industry or sector. Discuss its current stage (growth, mature, declining), competitive landscape, and key market drivers.

### 5. Investment Thesis and Risk/Opportunity

- **Investment Thesis (Why Invest):** A clear, concise statement on the primary arguments for investing in this stock. This should integrate the potential opportunities.
  - **Potential/Opportunities Analysis:** Detail what future industry or market trends, products, or strategic moves could significantly benefit the company.
- **Risk Analysis (Why NOT Invest):** A comprehensive breakdown of the key risks: financial risks (e.g., high debt), operational risks (e.g., supply chain), competitive risks, and regulatory risks.

### 6. Analyst Consensus

- **Top Analysts' Analysis:** Provide a summary of the consensus among top market analysts (e.g., S&P, Moody's, major investment banks). Include the **current analyst rating** (Buy, Hold, Sell) and any recent **price targets**.

---

### Example of Search Queries for Analysis

I'll now search for the data using the provided requirements. I will use a placeholder ticker, **TSLA**, to show the process, as the user did not provide a ticker. I will generate the tool code block with the necessary searches.

I need to search for:

1.  Current price and 52-week min/max.
2.  Historical financial statements (Revenue, Profit) for 10 years.
3.  Historical Multiples (P/E, P/B, Net Debt/EBITDA, etc.).
4.  Latest news/facts.
5.  Industry analysis (e.g., Electric Vehicle market).
6.  Analyst ratings/consensus.

Once the user provides the specific stock ticker, I will execute the relevant searches. Since the user has not provided a stock ticker, I cannot execute the tool code yet. I will provide the placeholder tool code to demonstrate the next step.

---

## Next Step

**Please provide the stock ticker you wish to analyze.**
\*Example: **AAPL**, **GME**, or a Brazilian stock like **PETR4.SA\***.

For now, I will generate the search queries using a generic example, **TSLA**, to show the subsequent step of the process.

---

This is an excellent, comprehensive prompt for a deep-dive stock analysis. The structure effectively blends **quantitative historical data** with **qualitative forward-looking analysis**, which is the hallmark of a thorough equity research report.

The following is the **optimized, complete prompt template** that incorporates all your specified requirements, ensuring clarity and an analytical tone for the AI model.

---

## Optimized Comprehensive Stock Analysis Prompt Template

**Target Stock Ticker:** **[INSERT STOCK TICKER HERE, e.g., AAPL or PETR4.SA]**

**Objective:** Conduct a comprehensive fundamental analysis of the target company. The analysis must integrate historical quantitative data with forward-looking qualitative analysis, addressing all the specified metrics and strategic questions.

### 1. Key Stock and Historical Financial Data

Present the following data for the target stock. For historical metrics (Revenue, Profit, Dividends), aim for the last **10 available fiscal years** (or since IPO/listing if shorter).

| Metric Category           | Data Points Required                                                                                                                             |
| :------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------- |
| **Current Market Data**   | **Current Price** (latest available), **52-Week Minimum Price**, and **52-Week Maximum Price**.                                                  |
| **Historical Financials** | **Annual Revenue History** (10 years), **Annual Profit/Net Income History** (10 years), and **Annual Dividends Distributed History** (10 years). |
| **Company Size**          | **Market Capitalization** (or Enterprise Value) and **Classification** (e.g., small-cap, mid-cap, large-cap, blue chip).                         |

---

### 2. Multiples and Growth Metrics Table

Create a concise table with the **latest available figures (TTM/LTM)** for the following financial multiples and growth rates.

| English Multiple/Metric                                 | Brazilian Portuguese Equivalent       |
| :------------------------------------------------------ | :------------------------------------ |
| **Price-to-Earnings (P/E)**                             | _P/L_                                 |
| **Price-to-Book (P/B)**                                 | _P/VP_                                |
| **Dividend Yield (DY)**                                 | _DY_                                  |
| **Earnings Yield (EY)**                                 | _Earning Yield_                       |
| **Graham Price/Number**                                 | _Preço de Graham_                     |
| **CAGR of Profits (10-Year, 5-Year, and 3-Year)**       | _CAGR lucros últimos 10, 5, e 3 anos_ |
| **Net Debt/EBITDA**                                     | _Dívida/EBITDA_                       |
| **Net Debt/Enterprise Value (EV)**                      | _Dívida/EV_                           |
| **Enterprise Value (EV)**                               | _EV_                                  |
| **Dividend Payout Ratio**                               | _Dividend Payout_                     |
| **Net Margin**                                          | _Net Margin_                          |
| **Stock Price Growth** (1-Year, 5-Year, 10-Year Return) | _Crescimento do Estoque_              |

---

### 3. Financial Analysis and Multiples Overview

- **General Multiples Analysis:** Provide a high-level overview of the company's valuation, contrasting its primary multiples (P/E, P/B, EV/EBITDA, DY) against **relevant industry benchmarks** and its own **historical averages**.
- **Anomaly Identification:** Identify any multiple that appears significantly adverse (e.g., very high P/E, very low P/B, negative Net Margin, excessive Debt/EBITDA).
- **Contextual Explanation:** For each adverse multiple, provide a **detailed explanation of the context or reasons** why it may be at that level (e.g., high P/E due to expected high future growth, negative Net Margin due to temporary M&A expenses, high Debt/EBITDA due to recent capital-intensive expansion).

---

### 4. Strategic and Qualitative Analysis

- **Latest Relevant Facts:** Summarize the most **recent and impactful news, strategic announcements, M&A activity, or regulatory shifts** that are currently influencing investor sentiment and the stock price.
- **Industry/Sector Analysis:**
  - Analyze the company's **industry and sector**, discussing its current growth stage (e.g., rapid growth, mature, disruptive).
  - Describe the **competitive landscape** and the company's **moat/competitive advantage** (or lack thereof) within that sector.

---

### 5. Investment Thesis and Risk Assessment

- **Potential/Opportunities Analysis:** Detail the **specific trends, market shifts, product innovations, or strategic decisions** that the company or industry is positioned to capitalize on in the future. **Why Invest in it?**
- **Risk Analysis (Why NOT Invest):** Provide a comprehensive analysis of the major risks:
  - **Financial Risks** (e.g., liquidity, debt structure, interest rate exposure).
  - **Operational/Execution Risks** (e.g., supply chain, key person dependence, failed project launch).
  - **Competitive/Industry Risks** (e.g., disruption by new technology, intense price wars, regulatory changes).
- **Investment Thesis:** Synthesize the entire analysis into a **clear, concise Investment Thesis** that states the core argument for a **Buy, Hold, or Sell** recommendation, incorporating the opportunities and risks.

---

### 6. Top Analyst Consensus

- **Analyst Consensus Summary:**
- **Rating and Price Target:** Provide the **current consensus rating** (e.g., Strong Buy, Hold, Sell) and the **average or median consensus price target**.
