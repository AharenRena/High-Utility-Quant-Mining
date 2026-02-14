# High-Utility Pattern Mining for Financial Time Series Analysis

1. 研究動機 (Research Motivation)
本專案旨在結合 Utility-based Data Mining 技術與金融時序數據，識別市場中顯著的流動性異常（Significant Liquidity Anomalies）與市場微結構特徵。
本研究假設特定的市場微結構特徵（Market Microstructure Features）與市場流動性異常（Liquidity Anomalies），並非隨機雜訊，而是具備統計顯著性的高價值序列模式（High-Utility Sequential Patterns）。

2. 擬定技術架構 (Proposed Framework)
本計畫擬將量化交易中的「尋找高獲利型態」問題，轉化為資料探勘領域的「高效能序列探勘 (High-Utility Sequential Pattern Mining)」問題。
初步規劃分為三個工作面向：

2.1 資料前處理與特徵編碼 (Preprocessing & Feature Encoding)
目標：解決金融時序數據（Continuous Time-Series）無法直接應用於傳統探勘演算法的問題。

2.2 高效能模式探勘 (High-Utility Pattern Mining)
目標：解決傳統統計指標（如 MA, RSI）往往只能描述「市場常態」的限制。本計畫希望能從雜亂的市場數據中，過濾掉那些頻繁發生但無意義的雜訊（Noise），專注於找出那些雖然不常出現，但一旦出現往往伴隨著顯著單向價格波動的市場微結構。

2.3 回測與效用評估 (Backtesting & Utility Evaluation)
目標：驗證挖掘出的模式在樣本外期間 (Out-of-Sample Period) 的穩定，以免過擬合 (Overfitting) 。

3. 目前進度 (Current Status)
- [x] 基礎數據API獲取
- [x] 金融數據預處理流程
- [ ] 演算法整合 
