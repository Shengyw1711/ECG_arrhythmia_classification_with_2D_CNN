# ECG arrhythmia classification using a 2-D convolutional neural network.

這是"使用卷積神經網路(CNN)對2D心電圖訊號影像進行心律不整疾病類型分類"的程式.

模型需透過MIT-BIH心律不整訊號資料集進行訓練。  
This is the link to the model's weights: https://drive.google.com/open?id=1WaenBnWYyhiumkvfaqEcDzti4S9aEuhS

The model can detect arrythmias of 6 types, namely: 
1. Atrial premature contraction beat (APC)
2. Left bundle branch block beat (LBB)
3. Paced beat (PAB)
4. Premature ventricular contraction beat (PVC)
5. Right bundle branch block beat (RBB)
6. Ventricular escape beat (VEB)

The model can also predict whether an ECG is normal or not. So, there are 7 classes the model can predict.
# Using the model
You can download the model from the link mentioned above. Run main.py and provide the required directories. You can give a csv ecg file or images of segmented ecg beats as your input. Mostly you will have a csv file of an ecg signal. 

