# Investment Portfolio Optimization with Technical Trading Strategies

## 📊 Project Overview
This project involved constructing and optimizing an investment portfolio using historical price data and technical analysis. By applying strategies such as Moving Average Crossover and Bollinger Bands, we identified optimal combinations of assets across equities, fixed income, commodities, and currencies. The goal was to achieve a Sharpe ratio above 1.0, maximizing returns relative to risk.

---

## 🎯 Objectives
- **Portfolio Construction**: Select a diversified set of assets across different classes to achieve balanced risk and return.
- **Technical Strategy Application**: Apply Moving Average Crossover and Bollinger Bands to enhance portfolio performance.
- **Sharpe Ratio Optimization**: Optimize the portfolio to exceed a Sharpe ratio of 1.0, outperforming individual asset strategies.
- **Risk Management**: Analyze correlation and beta to minimize risk exposure and enhance diversification.

---

## 🔍 Key Insights

### 1. **Asset Selection & Strategy Application**
   - Selected 8 assets, including 5 equities, 1 fixed income, 1 commodity, and 1 currency. Applied uniform parameter settings for Moving Average Crossover (fast and slow windows) and Bollinger Bands (window and standard deviation band) to maintain consistency.

### 2. **Performance Optimization**
   - **Equal Weighted Portfolio**: Calculated the Sharpe ratio of an equal-weighted portfolio to establish a baseline for performance.
   - **Mean-Variance Optimization (MVO)**: Conducted a 5,000-step Monte Carlo simulation to identify optimal weights for both minimum volatility and maximum Sharpe ratio portfolios.

### 3. **Risk/Return Analysis**
   - **Sharpe Ratio Comparison**: The optimized maximum Sharpe portfolio achieved a higher Sharpe ratio compared to the equal-weighted portfolio and individual asset strategies.
   - **Correlation and Diversification**: Analyzed the correlation structure among assets to enhance diversification. Identified low-correlation asset combinations that contributed to improved portfolio stability.

### 4. **Beta Analysis**
   - Calculated the portfolio beta relative to the S&P 500, providing insights into the portfolio's sensitivity to market movements.

---

## 🛠️ Tools & Technologies
- **Data Processing & Analysis**: Python (Pandas, Numpy)
- **Optimization**: Monte Carlo Simulation, Mean-Variance Optimization
- **Technical Analysis**: Moving Average Crossover, Bollinger Bands
- **Visualization**: Matplotlib, Seaborn

---

## 📈 Methodology

- **Technical Strategy Implementation**: Created functions for Moving Average Crossover and Bollinger Bands, enabling insights into price trends and volatility.
- **Portfolio Optimization**: Applied MVO using Monte Carlo simulations to construct efficient portfolios. Generated scatter plots of risk/return profiles to identify minimum volatility and maximum Sharpe ratio portfolios.
- **Risk and Correlation Analysis**: Calculated and visualized the correlation matrix to inform asset weightings and diversification strategies.

📌 Conclusion
Through this project, we constructed a robust investment portfolio that balances returns with risk. By combining technical strategies and optimization techniques, we achieved:

High Sharpe Ratio: Optimized asset weights yielded a Sharpe ratio above 1.0, outperforming individual strategies.
Enhanced Diversification: Analyzed asset correlations to select low-correlation assets, reducing overall portfolio volatility.
Market Sensitivity Management: Beta analysis provided insights into the portfolio’s responsiveness to broader market changes.
The project highlights how technical analysis and portfolio optimization can yield superior risk-adjusted returns, making it a valuable framework for investment strategy.


---

## 📂 Project Structure
```plaintext
📦 investment-portfolio-optimization
├── 📁 data                 # Raw and processed datasets
├── 📁 notebooks            # Jupyter notebooks with analysis and optimization code
├── 📁 visualizations       # Graphs and scatter plots of portfolio metrics
└── 📁 reports              # Project report and presentation materials


Thank you for exploring the Investment Portfolio Optimization Project! This project demonstrates the power of data-driven strategies in achieving financial performance.
