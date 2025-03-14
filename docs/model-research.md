# AI Trading Insights Model Research

### **LLM Model Research & Decision: Gemini 2.0 Flash**

After evaluating the top language models for financial market analysis, we have selected **Gemini 2.0 Flash** for our AI Trading Insights Proof of Concept (POC). While **Gemini 2.0 Pro Experimental** demonstrates exceptional potential, its full benchmarking is not yet complete. Given the current need for a proven, cost-effective, and efficient solution, **Gemini 2.0 Flash** is the most practical choice, with the flexibility to pivot to **Gemini 2.0 Pro Experimental** once its performance metrics are fully validated.

---

## Research Methodology

### Leaderboard for LLM Evaluation

To identify the best LLM for our use case, we relied on the **Artificial Analysis AI Leaderboard**, which provides detailed, tested metrics for various models. The leaderboard evaluates LLMs across multiple dimensions, offering transparency into their capabilities and trade-offs. This allowed us to make an informed, data-driven decisions tailered to our use-case.

### **Key Metrics from the Leaderboard**

1. **Quality Index**:

   - Measures reasoning, factual accuracy, and mathematical proficiency.
   - Directly impacts the model's ability to process complex financial data with precision.

2. **Performance Benchmarks**:

   - Includes latency (Time to First Token), tokens processed per second, and end-to-end response time.
   - Crucial for ensuring real-time analysis and timely decision-making in fast-moving financial markets.

3. **Cost Analysis**:

   - Tracks input/output token costs and provides a blended price metric for easier comparison.
   - Ensures scalability without exceeding budget constraints.

4. **Context Window**:

   - Reflects the maximum number of tokens a model can process in one session.
   - A larger context window is essential for analyzing extensive financial datasets.

5. **Scenario-Specific Workloads**:
   - Models are tested on a variety of workloads (e.g., 100, 1,000, 10,000 tokens), offering insights into their efficiency at different scales.

### **How We Used These Metrics**

- **Initial Screening**:
  Models were shortlisted based on their **Quality Index** and **Performance Benchmarks**, ensuring they met the minimum requirements for financial analysis.

- **Cost vs. Scalability Trade-Offs**:
  We evaluated cost metrics alongside the **context window size**, identifying models that could handle large datasets without excessive costs.

- **Real-Time Suitability**:
  Latency and token throughput metrics were prioritized to ensure the selected model could deliver timely insights for decision-making.

- **Benchmark Validation**:
  Data from the leaderboard was cross-referenced with our POC requirements, ensuring the chosen model aligns with our scalability, accuracy, and cost objectives.

The leaderboard’s tested metrics gave us confidence in **Gemini 2.0 Flash** as the most cost-effective and reliable solution for our current needs. However, we will continue monitoring advancements in **Gemini 2.0 Pro Experimental**, which is anticipated to exceed other models in areas of value once fully benchmarked.

---

## **Model Comparison for Financial Data Analysis**

### **Evaluation Criteria**

We assessed the top **16 LLM models** based on the following metrics that are beneficial to our project's success and limited this down to 6 models:

- **Quality**: Reasoning, factual accuracy, and mathematical proficiency.
- **Cost**: Token pricing (input/output) and operational expense.
- **Context Window**: Maximum token capacity for handling large datasets.
- **Performance**: Latency, tokens processed per second, and suitability for real-time analysis.

---

### **Comparison Table**

| **Model**                         | **Quality Index** | **MATH-500** | **HumanEval** | **Blended Cost (USD/1M Tokens)** | **Context Window** | **Median Latency (s)** | **Tokens/s (Median)** | **Strengths**                                                                 |
| --------------------------------- | ----------------- | ------------ | ------------- | -------------------------------- | ------------------ | ---------------------- | --------------------- | ----------------------------------------------------------------------------- |
| **Gemini 2.0 Flash**              | 83                | 93%          | 90%           | $0.17                            | 1M                 | 0.30                   | 157.7                 | Cost-efficient, low latency, strong math benchmarks.                          |
| **Gemini 2.0 Pro Experimental**   | 85                |              |               | $0.00                            | 2M                 | 0.62                   | 129.8                 | Anticipated exceptional scalability and performance, pending full benchmarks. |
| **o1**                            | 90                | 95%          | 97%           | $26.25                           | 200k               | 28.63                  | 47.4                  | Highest quality, exceptional benchmarks, but very expensive.                  |
| **DeepSeek R1 Distill**           | 85                | 92%          | 97%           | $0.81                            | 128k               | 1.31                   | 1,191.3               | High-speed processing, strong benchmarks, but limited context window.         |
| **o3-mini**                       | 89                | 97%          |               | $1.93                            | 200k               | 10.74                  | 209.9                 | High quality, moderate cost, good for smaller-scale analyses.                 |
| **Gemini 2.0 Flash-Lite Preview** | 79                | 87%          | 90%           | $0.13                            | 1M                 | 0.26                   | 258.9                 | Low latency, excellent cost-efficiency for smaller data analysis.             |

---

## **Extended Functionality of Gemini 2.0 Flash**

### **1. Grounding for Accuracy**

- **Description**: Integrates real-time external data sources for factually accurate responses.
- **Benefit**: Ensures outputs align with up-to-date market conditions and events, reducing reliance on static or outdated knowledge.

---

### **2. Real-Time Insights**

- **Description**: Provides dynamic, event-driven financial insights by connecting to APIs or live databases.
- **Benefit**: Generates actionable recommendations based on earnings reports, geopolitical developments, or market shifts, improving decision-making.

---

### **3. Search Integration**

- **Description**: Incorporates live search results for enhanced relevance and context.
- **Benefit**: Delivers traders direct access to the latest articles, reports, or analyses without needing to switch platforms.

---

### **4. Dynamic Recommendations and Alerts**

- **Description**: Tracks patterns (e.g., RSI, MACD) and issues alerts or strategy recommendations based on preset conditions.
- **Benefit**: Supports proactive decision-making by notifying users about significant trends or deviations.

---

### **5. Fine-Tuning for Proprietary Data**

- **Description**: Tailors outputs using proprietary datasets like historical trading data or internal financial reports.
- **Benefit**: Produces highly customized insights optimized for specific trading strategies or niche requirements.

---

### **6. Multimodal Integration**

- **Description**: Analyzes text, numerical data, and visual inputs like candlestick charts or financial graphs.
- **Benefit**: Offers a holistic view of market dynamics, combining numerical and visual data for better insights.

---

### **7. Scenario-Based Simulations**

- **Description**: Simulates “what-if” scenarios to assess the impact of potential market events.
- **Benefit**: Enables traders to evaluate the effects of interest rate changes, regulatory updates, or earnings surprises for informed decision-making.

---

## **Why Gemini 2.0 Flash Stands Out**

**Gemini 2.0 Flash** offers an excellent balance of **cost efficiency**, **performance**, and **proven benchmarks**, making it the ideal choice for our POC. Its standout features include **strong mathematical capabilities** (MATH-500: 93%), **low latency** (0.30 seconds), and an **extremely competitive cost** of $0.17 per 1M tokens. These attributes ensure that **Gemini 2.0 Flash** meets the high standards required for financial market analysis, where accuracy, real-time insights, and affordability are critical.

With a **1M token context window**, **Gemini 2.0 Flash** allows for effective analysis of moderately sized datasets, making it well-suited for the majority of our current use cases. Its **robust output speed** (157.7 tokens per second) ensures timely and reliable results, facilitating fast decision-making in dynamic trading environments. Additionally, its proven benchmarks across reasoning and factual accuracy ensure confidence in its ability to handle complex financial queries with precision.

While **Gemini 2.0 Flash** is currently the optimal choice for our POC, **Gemini 2.0 Pro Experimental** offers significant potential as a contingency model. With its unmatched **2M token context window**, anticipated scalability, and **cost-free experimental phase**, it holds the promise of greater efficiency in processing extensive datasets and handling more advanced use cases. Once fully benchmarked, **Gemini 2.0 Pro Experimental** could provide even greater value, particularly for large-scale, data-intensive applications where its scalability and potential cost-efficiency would excel.

For now, **Gemini 2.0 Flash** provides a **practical, low-risk solution** that delivers consistent, reliable performance at an attractive cost. This strategic decision allows us to proceed confidently with the POC, while retaining the flexibility to pivot to **Gemini 2.0 Pro Experimental** if its benchmarks demonstrate a clear performance advantage in the future.

---

## **Testing**

I manually tested several LLMs (including **ChatGPT 4o**, **ChatGPT o1**, **DeepSeek R1**, **Gemini 2.0 Flash**, and **Gemini 2.0 Pro**) using the same prompt to identify various **trend indicators** (e.g., _Simple Moving Average (SMA), Exponential Moving Average (EMA), Pivot Points (Standard/Fibonacci)_) and **momentum indicators** (e.g., _Relative Strength Index (RSI), Moving Average Convergence Divergence (MACD), Commodity Channel Index (CCI)_).

All models were able to extract this information and provide acceptable analyses. However, in my tests, **Gemini 2.0 Flash** consistently returned more detailed and accurate results, including key support and resistance levels, which I verified independently.

## **Conclusion**

**Gemini 2.0 Flash** has been chosen as the primary LLM for our financial market analysis POC due to its proven cost-efficiency, scalability, and consistent performance metrics. It offers the precision and speed required to deliver actionable insights for financial trading, making it the most suitable choice for our immediate use cases.

Additionally, the flexibility to pivot to **Gemini 2.0 Pro Experimental** ensures that we can adapt to the best-performing model as the project evolves. This adaptability maximizes cost-effectiveness and analytical value, while providing opportunities to leverage **Gemini 2.0 Pro Experimental’s larger 2M token context window** as a potential cost-saving and performance-enhancing avenue for processing extensive datasets. By starting with **Gemini 2.0 Flash**, we can maintain a balance between performance, cost, and scalability, ensuring the success of the POC while preparing for future advancements or the possibily of generative AI agent imntegration.

---

# Live Data Testing

Below are results from **Gemini 2.0 Flash** and **Gemini 2.0 Pro Experimental** when analyzing live 4-hour OHLC data on **Minswap**, Cardano’s largest DEX by volume. Each section covers the specific pair, timeframe, and the model’s technical assessment.

---

## SNEK/ADA (4H Timeframe on Minswap) with Gemini 2.0 Flash

To validate **Gemini 2.0 Flash** under real-world conditions, I tested it on **SNEK/ADA** data (4-hour OHLC) from Minswap, including volume. The model analyzed:

- **Trend Indicators**: SMA/EMA, Ichimoku, ADX, Parabolic SAR, Pivot Points
- **Momentum Indicators**: RSI, MACD, Williams %R, CCI
- **Volatility Metrics**: Bollinger Bands, ATR, Keltner Channels
- **Volume-Based Indicators**: OBV, VWAP, CMF

### Observations

- **Trend**: Predominantly neutral signals
- **Volatility**: Contracting Bollinger Bands, suggesting reduced price swings
- **Volume**: Lower volume, consistent with OBV trending downward
- **Support & Resistance**: \$0.0059 (support), \$0.0064 (resistance)

### Conclusion

Overall, the model indicated a **Neutral** bias and recommended waiting for a **breakout** before taking a position.

> **Executed On:** 26 February 2025, 10:45 UTC

---

## SNEK/ADA (4H Timeframe on Minswap) with Gemini 2.0 Pro Experimental

For additional validation, **Gemini 2.0 Pro Experimental** was tested on **SNEK/ADA** using 4-hour OHLC data from Minswap (including volume). This analysis delivered more precise support/resistance targets, reflecting a **Bearish** environment:

- **Trend & Momentum**:

  - SMA/EMA, Ichimoku, Parabolic SAR: All bearish
  - RSI, MACD, Williams %R, CCI: Oversold/downward momentum

- **Volatility**:

  - Bollinger Bands: Expanding
  - ATR: Increasing volatility
  - Keltner Channels: Breakout scenario

- **Volume-Based Indicators**:

  - OBV: Declining
  - VWAP: Below price
  - CMF: Negative (Selling pressure)

- **Support & Resistance**:
  - Resistance: \$0.0061
  - Support: \$0.0057

### Conclusion

**Gemini 2.0 Pro Experimental** concluded a **Bearish** bias and suggested a short position, albeit cautiously due to oversold signals.

> **Executed On:** 26 February 2025, 11:00 UTC

---

## IAG/ADA (4H Timeframe on Minswap) with Gemini 2.0 Flash

Using **Gemini 2.0 Flash** to analyze **IAG/ADA** 4-hour data from Minswap revealed a notably **Bearish** setup:

- **Trend & Momentum**:

  - SMA/EMA, Ichimoku Cloud, Parabolic SAR: Downward trend
  - ADX: Weak trend reading
  - RSI, Williams %R, CCI: Oversold
  - MACD: Bearish

- **Volatility**:

  - Bollinger Bands: Expanding (higher price swings)
  - ATR: Increasing volatility
  - Keltner Channels: No immediate breakout, but volatility is rising

- **Volume-Based Indicators**:

  - OBV: Falling
  - VWAP: Below price
  - CMF: Negative (Selling pressure)

- **Support & Resistance**:
  - Resistance: \$0.405
  - Support: \$0.370
  - Model Note: A break above \$0.340 invalidates the short thesis

### Conclusion

**Gemini 2.0 Flash** recommends a short position but advises close monitoring due to oversold conditions and elevated volatility, where sudden reversals remain possible. Risk management is essential in this context.

> **Executed On:** 26 February 2025, 11:32 UTC

During testing, the model’s grounding capabilities—especially its ability to reference live Google searches—returned **inaccurate news events** and **invalid links**. These issues should improve once the model transitions out of its **experimental phase**, at which point more **reliable real-time data integration** can be seamlessly incorporated.

## Model Configuration Insights

In my testing, **lowering the model’s temperature** setting—thereby reducing its randomness—resulted in **more reliable and accurate results** upon repeated analysis of OHLC data. Additionally, configuring a **seed** for deterministic outputs proved useful, ensuring consistent responses across multiple runs and facilitating direct comparisons or debugging. Together, these configuration choices help maintain predictability and precision, which is especially beneficial for financial data analysis and record-keeping.

## **References**

- Artificial Analysis AI Leaderboard: [https://artificialanalysis.ai/leaderboards/models](https://artificialanalysis.ai/leaderboards/models)
