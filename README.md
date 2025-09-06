
程式說明:
 1.利用GELU取代ReLU
 2.增加至4個卷積區塊(BLOCK1-BLOCK4)
 3.卷積後增加nn.BatchNorm2d
 4.通道數逐層增加
 5.增加dropout,每層dropout逐層增加
