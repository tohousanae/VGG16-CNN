# VGG16-CNN
VGG16圖片分類器<br>
## 功能
採用cifar10數據集進行訓練，支援10種圖片的分類。
## 成效
圖像分類準確率已達到83%

## 遇到的困難
1.模型的泛化能力不佳，對未知圖片的辨識能力還需加強。<br>
2.資料集解析度太小，丟掉過多特徵造成辨識能力下降。<br>
3.VGG16訓練時間長，耗費大量硬體資源。

## 解決方法以及未來方向
1.數據增強。<br>
2.更換解析度較高的資料集圖片來增加圖像辨識的準確率。
