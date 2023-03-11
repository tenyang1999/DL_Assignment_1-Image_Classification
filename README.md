# DL_Assignment_1-Image_Classification

- 深度學習作業一：使用各種特徵萃取方法將影像轉化為特徵向量，再透過分類器將影像做分類，最終驗證正確率。
- 使用image的資料集進行預測
- 使用sklearn中SGD classifier、Perceptron classifier、NB Multinomial classifier進行Incremental learning，測試不同的trianing example對於模型預測的準確率的影響。
- 使用Ensemble learning的Xgboost、Random Forest再加上NB Multinomial classifier針對不同的特徵萃取方式進行模型的訓練與預測，判斷不同的方式對於準確率的影響。
- 最終透過Accuracy去評分，比較模型效能

## 功能

- 了解不同特徵萃取方式對預測的影響。
- 測試不同trianing example對於模型預測的準確率的影響。

## 安裝
- 本次執行上會需要用到的package

```python
pip install sklearn
pip install opencv-python
pip install xgboost

```

## 使用方法
- Incremental learning的各種方法寫在Image_Classification_firststage.ipynb中，只需要將Image.zip解壓縮至相同資料夾後，直接執行即可
- 將後續的不同特徵萃取方法的實驗放置在Image_Classification_secondstage.ipynb中，直接執行即可將所有的實驗結果存入output.txt中。
