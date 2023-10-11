# 真假新聞辨識專題
運用 NLP 領域中的特徵提取與分類模型，建立真假新聞判斷系統。

### 指導教授 & 學生
- 指導教授: 葉向原
- 學生: 巨資四 A 黃奕鈞、巨資四 B 李冠暶

## 簡介
面對即將來臨的2020總統大選，如何分辨真假新聞成為一大挑戰。本研究運用自然語言處理技術進行真假新聞的預測。

## 方法
- 資料集: LIAR
- 特徵提取: CountVectorizer, TFIDF_N-Gram, Doc2Vec
- 分類模型: Naive bayes, Logistic Regression, SVM, SGD, Random Forest

## 結果
最佳組合: TFIDF_N-gram 與 Random Forest (F1-Score: 0.613)

## 結論
提供一套簡易的真假新聞辨識系統，助選民於大選中做出明智選擇。

## 資源
- [Github 代碼](https://github.com/KungJun1107/-)
