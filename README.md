
程式優化說明:
 1.利用GELU取代ReLU
 2.增加至4個卷積區塊(BLOCK1-BLOCK4),經過實驗,使用4個卷積區塊,相較於使用3個與5個performance都較佳
 3.卷積後增加nn.BatchNorm2d
 4.通道數逐層增加
 5.增加dropout,每層dropout逐層增加
 ,在Colab使用GPU模式下,最終共跑80個epoch,val_acc達到63%
