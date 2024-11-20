# Big-Data-Analytics-for-Finance
## 作業區
### week2作業_金融市場概述與資料收集、預處理
說明 :
請嘗試用 Python 撰寫程式分別從證券交易所、Yahoo奇摩爬取股價資料，並進行可視化。

* 取台積電 2330, 追蹤半年

### week3作業_技術分析與K線圖
說明:
延用上週爬取的股價資料，完成本次作業要求：
1. 計算技術指標（SMA、RSI、MACD）
2. 可視化 K 線圖
3. 技術指標結合機器學習（線性回歸、決策樹、隨機森林）預測股價漲跌。使用技術指標作為特徵來預測第 n 天的股價

### week4作業_時間序列、量化交易策略
延用week3的股價資料，完成本次作業要求：
1. 使用Python建立ARIMA模型，預測股票價格，並進行可視化。
2. 使用Python設計一個量化交易策略，並使用歷史資料進行回測。

### week7作業-深度學習ANN、CNN
1. 使用 TensorFlow 或 PyTorch 實作類神經網路模型預測股票價格（TensorFlow 使用 Dense layer；PyTorch 使用 Linear layer）。
說明：使用收盤價或技術指標預測，預測N日後的股價。
2. 使用 TensorFlow 或 PyTorch 實作 CNN 捕捉 K 線趨勢，並預測股價漲跌（分類任務）。
說明：輸入一張 N 天的 K 線圖判斷未來價格可能漲或跌，label 方式可以使用技術指標輔助，例如：5日均線高於10日均線標註「漲」，5日均線低於10日均線標註「跌」。

### week9作業-時間序列 LSTM、Transformer
1. 使用 LSTM 模型預測股票未來價格，自訂窗口大小，並分析預測效果。
2. 使用 Transformer 模型預測股價漲跌，自訂窗口大小，並分析預測結果。

### week10作業- 
1. 使用 Hugging Face 框架建立 BERT 模型，針對金融領域文本進行情緒分析訓練。
2 .可使用以下提供的資料集，或選擇其他適合的金融文本資料集。
3. 資料集網址：https://huggingface.co/datasets/takala/financial_phrasebank
