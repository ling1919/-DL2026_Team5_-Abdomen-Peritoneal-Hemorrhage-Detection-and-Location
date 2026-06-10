# 腹部出血偵測 (Gastrointestinal Bleeding Detection)

## 1. 專案目標
本專案利用深度學習 CNN 模型（ResNet-18, DenseNet-121, EfficientNet-B0），針對腸胃道內視鏡影像進行「出血病灶 (Lesion)」與「正常 (Normal)」的二元分類，目標為最大化出血召回率 (Recall)，以輔助臨床診斷。

## 2. 檔案說明
* `DenseNet_121.ipynb`：DenseNet-121 訓練與測試程式碼。
* `ResNet18_GastrointestinalBleeding.ipynb`：ResNet-18 訓練與測試程式碼。
* `深度學習_Final_EfficientNet_B0.ipynb`：EfficientNet-B0 訓練與測試程式碼。

## 3. 資料集說明
因版權與容量考量，本專案不直接提供圖片檔案。
* 資料來源：Kaggle 公開資料集
* 取得連結：[Gastrointestinal Bleeding Images Dataset](https://www.kaggle.com/datasets/aryashah2k/gastrointestinal-bleeding-images-dataset)

## 4. 使用方法
1. 將本專案 Clone 至本機，或下載 `.ipynb` 檔案至 Google Colab 開啟。
2. 確保環境已安裝 `torch`, `torchvision`, `scikit-learn` 等套件。
3. 透過上述 Kaggle 連結下載資料集，並放置於指定的 `raw_data` 資料夾內。
4. 依序執行 Jupyter Notebook 中的儲存格，即可重現訓練與測試結果。# -DL2026_Team5_-Abdomen-Peritoneal-Hemorrhage-Detection-and-Location
