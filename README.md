# High-Utility Pattern Mining for Financial Time Series Analysis

## 1. 研究動機 (Research Motivation)
本專案旨在結合 Utility-based Data Mining 技術與金融時序數據，識別市場中顯著的流動性異常（Significant Liquidity Anomalies）與市場微結構特徵。
本研究假設特定的市場微結構特徵（Market Microstructure Features）與市場流動性異常（Liquidity Anomalies），並非隨機雜訊，而是具備統計顯著性的高價值序列模式（High-Utility Sequential Patterns）。

2. 擬定技術架構 (Proposed Framework)
本計畫擬將量化交易中的「尋找高獲利型態」問題，轉化為資料探勘領域的**「高效能序列探勘 (High-Utility Sequential Pattern Mining)」**問題。初步規劃分為三個核心模組：

2.1 資料前處理與特徵編碼 (Preprocessing & Feature Encoding)
目標：解決金融時序數據（Continuous Time-Series）無法直接應用於傳統探勘演算法的問題。

2.2 高效能模式探勘 (High-Utility Pattern Mining)
目標：從海量歷史數據中，識別出稀有但具備高獲利期望值的交易訊號。

2.3 回測與效用評估 (Backtesting & Utility Evaluation)
目標：驗證挖掘出的模式在樣本外期間 (Out-of-Sample Period) 的穩健性，以避免過度擬合 (Overfitting) 。

## 3. 目前進度 (Current Status)
- [x] 基礎數據API獲取
- [x] 金融數據預處理流程
- [ ] 演算法整合 
