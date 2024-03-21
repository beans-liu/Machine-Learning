* 已經完成的部分
1. 利用data augmentation增加資料的多樣性，即便起初有較少的valid data，可以透過水平翻轉等方式增加一倍的資料量
2. semi-supervised learning，利用未被標註的資料集，當model的準確率到達一定程度時，就可以標註新的資料當作新的Valid dataset
3. 加深model 

* 目前結果
過 medium baseline : 52.807 %

* 未來可以做
1. 用ResNet-18(pretrain= False)
2. learning rate衰減機制
----------------------------------------------------------------------------------------------------------------------
* Version 2
1. 利用ResNet34 (pretrained = False)當作基礎模型
2. 導入learning rate衰減機制
