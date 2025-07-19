# 📊 Portfolio Optimization using Modern Portfolio Theory (MPT)

## 🔍 Project Summary

This project applies Modern Portfolio Theory (MPT) to build an optimized stock portfolio by maximizing the Sharpe Ratio using historical financial data. It identifies the most efficient allocation among selected technology stocks to achieve the best possible return for a given level of risk.

---

## 🎯 Objective

To simulate and optimize portfolio performance using Python by:
- Minimizing risk while targeting higher returns
- Calculating and comparing the Sharpe Ratio across randomly generated portfolios
- Identifying the optimal portfolio allocation from a risk-return perspective

---

## 🧰 Tools & Libraries
- Python (NumPy, Pandas, Matplotlib, SciPy)
- Jupyter Notebook
- yfinance (for fetching historical stock data)

---

## 📌 Methodology

1. **Stock Selection**  
   Selected five technology stocks: `AAPL`, `MSFT`, `GOOG`, `AMZN`, `META`

2. **Data Collection**  
   Fetched adjusted closing prices from Yahoo Finance for the period **2018–2023**

3. **Return & Risk Analysis**  
   - Calculated daily and annualized returns  
   - Derived the covariance matrix to assess risk relationships

4. **Portfolio Simulation**  
   Simulated **10,000+ random portfolios**, each with unique asset weights

5. **Optimization**  
   - Maximized the Sharpe Ratio using constrained optimization  
   - Ensured total allocation = 100%, no short selling

6. **Visualization**  
   Plotted the **Efficient Frontier**, with risk on the x-axis and return on the y-axis

---

## 📈 Results

**Optimal Portfolio Allocation:**
- AAPL: **48.49%**
- MSFT: 0.00%
- GOOG: 0.00%
- AMZN: 0.00%
- META: **51.51%**

**Performance Metrics:**
- 📈 Expected Annual Return: **27.63%**
- 📉 Annual Volatility (Risk): **30.34%**
- 📊 Sharpe Ratio: **0.91**

---

## 📷 Visualization

<img width="530" height="302" alt="image" src="https://github.com/user-attachments/assets/a438e132-d3c0-458b-9e03-e37087b3423c" />



> The optimal portfolio is marked with a red star.

---

## 🚀 Key Takeaways

- Demonstrated ability to apply mathematical optimization to investment problems
- Learned practical use of MPT using real stock market data
- Gained hands-on experience with financial data analysis and visualization

---

## 📁 How to Run

1. Clone the repository  
2. Install required libraries using  
   `pip install yfinance pandas numpy matplotlib scipy`  
3. Run the notebook `Portfolio_Optimization_MPT.ipynb` in Jupyter

---

## 📌 References
- Investopedia: [Modern Portfolio Theory](https://www.investopedia.com/terms/m/modernportfoliotheory.asp)

---

## 📬 Contacts 

**Gaurav Mishra**  
📧 Email:7mishragaurav@gmail.com
🌐 LinkedIn: (www.linkedin.com/in/gaurav-mishra-3788ba271)
🐙 GitHub: (https://github.com/mishragaurav7)

---
