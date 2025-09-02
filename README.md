# Equity Strategy on NIFTY 50

This project implements and evaluates quantitative trading strategies on the NIFTY 50 stock universe. It explores long-only portfolio strategies, evaluates multiple signal-generation methods, applies market regime filters, and compares performance against the benchmark index.

The work is documented through Jupyter notebooks and a detailed strategy-building report.

## 📂 Repository Structure

├── Market_regime_2.ipynb           # Jupyter Notebook for market regime strategy <br>
├── QI_STRAT_Long_Final_2.ipynb     # Jupyter Notebook for long-only strategy <br>
├── Strategy Building Documentation.pdf  # Full methodology & analysis <br>
├── requirements.txt                # Python dependencies <br>

## ⚙️ Installation

git clone https://github.com/r0hit91314/Equity_strategy_nifty50.git <br>
cd Equity_strategy_nifty50 <br>
pip install -r requirements.txt <br>

## ▶️ Usage

Run the notebooks in sequence: <br>
QI_STRAT_Long_Final_2.ipynb → Long-only strategy backtests. <br>
Market_regime_2.ipynb → Incorporates regime filters for improved robustness. <br>
Refer to Strategy Building Documentation.pdf for a detailed explanation of methodology, pivots, and results. <br>

## 📌 Key Learnings

- Strategy design is an iterative process of hypothesis, testing, rejection, and refinement.

- Market constraints (like no overnight shorts in India) , Survivorship bias, costs, and execution assumptions must be corrected for realistic performance.

- Market regime filtering greatly improves consistency.


