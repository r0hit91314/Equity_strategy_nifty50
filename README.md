# Equity Strategy on NIFTY 50

This project implements and evaluates quantitative trading strategies on the NIFTY 50 stock universe. It explores long-only portfolio strategies, evaluates multiple signal-generation methods, applies market regime filters, and compares performance against the benchmark index.

The work is documented through Jupyter notebooks and a detailed strategy-building report.

## 📂 Repository Structure

├── Final_pivoted_strategy.ipynb           # Jupyter Notebook for market regime strategy <br>
├── Initial_long_only_strategy.ipynb     # Jupyter Notebook for long-only strategy <br>
├── Strategy Building Documentation.pdf  # Full methodology & analysis <br>
├── requirements.txt                # Python dependencies <br>

## ⚙️ Installation

git clone https://github.com/r0hit91314/Equity_strategy_nifty50.git <br>
cd Equity_strategy_nifty50 <br>
pip install -r requirements.txt <br>

## ▶️ Usage

Run the notebooks in sequence: <br>
Initial_long_only_strategy.ipynb → Long-only strategy backtests. <br>
Final_pivoted_strategy.ipynb → Incorporates regime filters for improved robustness. <br>
Refer to Strategy Building Documentation.pdf for a detailed explanation of methodology, pivots, and results. <br>

## 📌 Key Learnings  

- **Trial and Error Matters:** Strategies don’t work perfectly at first. Testing, rejecting, and improving ideas step by step made the system stronger.  
- **Be Realistic:** Backtests look good only if you account for real issues like costs, slippage, and survivorship bias.  
- **Work with Market Rules:** Since overnight shorts aren’t allowed in India, the strategy had to pivot to long-only. Designing within rules is key.  
- **Filter the Noise:** Using market regime filters helped avoid bad trades in sideways or down markets and improved consistency.  
- **Keep it Balanced:** Too many rules kill returns, while balanced approaches gave steady and reliable performance.  

