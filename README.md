# Donchian-Channel-Backtesting
[Quantitative Research] Donchian Channel Trend Following Strategy for TAIFEX. Features backtesting, risk metrics (Sharpe/MDD), and parameter sensitivity analysis.
# Donchian Channel 趨勢追蹤策略 (台指期)
## Strategy Development & Backtesting Project

### 專案摘要 (Project Summary)
本專案為 TMBA 第 26 屆程式交易部 之研究成果。針對台股指數期貨（TAIFEX）開發 Donchian Channel 趨勢追蹤策略，並透過 Python 進行量化實證。

### 核心邏輯與回測架構 (Core Logic & Framework)
策略邏輯：利用 Donchian Channel 進行突破判斷，建立趨勢跟隨模型。
回測環境：使用 Python (Pandas/NumPy) 建立含交易成本與滑價假設之流程。
優化重點：經Mentor審核修正進出場邏輯，並進行參數敏感度比較（如通道天數、停損停利）。

### 績效指標 (Key Performance Metrics)
* 年化報酬率 (Annualized Return)
* 夏普值 (Sharpe Ratio)
* 最大回撤 (Max Drawdown, MDD)
* 勝率 (Win Rate)
