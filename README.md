# ECG arrhythmia classification using a 2-D convolutional neural network.

這是"使用卷積神經網路(CNN)對2D心電圖訊號影像進行心律不整疾病類型分類"的程式.

此模型需透過MIT-BIH心律不整訊號資料集進行訓練。  
可以透過此網址下載模型的權重: https://drive.google.com/open?id=1WaenBnWYyhiumkvfaqEcDzti4S9aEuhS

此模型可以檢測6種類型的心律不整: 
1. Atrial premature contraction beat (APC)
2. Left bundle branch block beat (LBB)
3. Paced beat (PAB)
4. Premature ventricular contraction beat (PVC)
5. Right bundle branch block beat (RBB)
6. Ventricular escape beat (VEB)

此模型也可以預測心電圖是否正常。因此，此模型總共可以預測7個類別。
# 使用模型
可以從上面提到的權重連結下載模型。執行main.py並放入所需的訓練資料。訓練資料可以提供心電圖的csv檔或經過分段的心電圖節拍的影像作為輸入。
