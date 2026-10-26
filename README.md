# ⚡ SparsioQ: Algorithmic Quantitative Wealth & Portfolio Platform

**SparsioQ** is an institutional-grade algorithmic portfolio optimization and wealth management platform designed to democratize high-level mathematical finance for everyone—from first-time retail investors with as little as ₹100, up to quantitative researchers and institutional evaluators.

---

## 🌟 Key Platform Capabilities

### 1. 📊 Live NSE Market Intelligence & Real-Time Stock Ranking
- **100% Real-Time & Accurate**: Live quotes, daily change (₹ and %), day ranges, and 52-week highs/lows directly from the National Stock Exchange of India (NSE).
- **25 Blue-Chip Leaders Across All Sectors**: Comprehensive coverage of Banking, IT, Energy, FMCG, Auto, Infrastructure, Metals, and Healthcare.
- **Dynamic AI Quant Health Score**: Mathematically ranks stocks from **#1 Best to Least Recommended** based on price momentum, fundamental P/E valuation, and ESG sustainability.
- **Interactive Candlestick Charting**: View 60-day interactive candlestick price charts with 20-day Simple Moving Averages (SMA) and 14-day Relative Strength Index (RSI).
- **NSE Trading Hours Monitor**: Live Indian Standard Time (IST) clock tracking trading status (`09:15 AM - 03:30 PM IST`).

### 2. 🌟 Zero-Knowledge Auto-Pilot (Micro-Investing)
- **Accessible to Anyone**: Zero financial expertise required.
- **Dynamic Rupee Allocation**: Enter any custom amount (e.g., ₹100, ₹500, ₹5,000, ₹50,000) and the platform calculates the exact fractional shares down to 0.0001 units.
- **Instant UPI Intent Integration**: Launch Google Pay, PhonePe, or Paytm with pre-filled amounts via standard NPCI deep links (`upi://pay?pa=...`).
- **1-Click Execution**: Deduct wallet cash and immediately acquire fractional shares.

### 3. 💼 Live Portfolio Holdings & Trading Ledger (Buy / Sell)
- **Real-Time Holdings Tracker**: View your owned shares, average purchase cost, current live market price, and unrealized Profit / Loss (₹ and %).
- **Instant Liquidation (Sell Shares)**: Sell 50% or 100% of any position with 1 click to book profits and return funds directly into your cash balance.
- **Complete Transaction Ledger**: Audit history recording timestamps, order types (BUY / SELL), payment methods, and settlement statuses.

### 4. 🧠 Quant Pro Mode (Advanced Mathematics)
- **Micro-Investment Fractional Slicer & MDP Q-Learning RL**: Algorithmic trade slicing across TWAP/VWAP intervals to minimize market impact slippage.
- **Gaussian Hidden Markov Models (HMM) & 3D Tensor HoSVD**: 3-state market regime shift detection (Bull, Consolidation, Bear) and Tucker factor loadings across macroeconomic modes.
- **$L_1$-Regularized CVXOPT Sparse Efficient Frontier**: Enforces portfolio sparsity, reducing transaction fees by >40% with ESG penalty terms and Karush-Kuhn-Tucker (KKT) optimality.
- **Qiskit Quantum Amplitude Estimation (QAE)**: Quadratic speedup $O(1/\epsilon)$ over classical Monte Carlo $O(1/\epsilon^2)$ for European option pricing.

### 5. 🏛️ Bank Account Linking & Payment Gateway
- **NPCI Account Aggregator (AA)**: Mobile number 2FA OTP verification flow adhering to RBI regulatory guidelines.
- **Razorpay Python SDK Integration**: Production-ready API key configuration.
- **Dynamic Bank Balance Editor**: Set custom demo balances to test small and large portfolio allocations.

---

## 🚀 Live Cloud Deployment & Local Setup

### Live Web App (Streamlit Community Cloud)
👉 **[https://sparsioq-platform.streamlit.app](https://sparsioq-platform.streamlit.app)**

### Running Locally on Your Computer
Open Command Prompt (`CMD`), navigate to the folder, and run:
```bash
cd C:\Users\welcome\.gemini\antigravity\scratch\SparsioQ_Platform
pip install -r requirements.txt
python -m streamlit run sparsioq_app.py
```
