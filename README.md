# kugyu_audio-style-transfer/釘宮理惠變聲器
![image](https://github.com/TaiChunYen/kugyu_audio-style-transfer/blob/master/figure/kugimiya4moe.jpeg)
## 使用工具
* Pytorch  

## 訓練模型
* Generator:CycleGAN-VC2(reduce one upsample layer and one downsample layer)  
* Discriminator:CycleGAN-VC  
* loss function:CycleGAN-VC
* Pytorch implement:https://github.com/TaiChunYen/Pytorch-CycleGAN-VC2/blob/master/model_m.py  
## 訓練資料
* 轉換:釘宮理惠dataset(kugimiya/) 200個  
* 被轉換:JSUT (Japanese speech corpus of Saruwatari-lab., University of Tokyo) 1000個  
download:https://sites.google.com/site/shinnosuketakamichi/publication/jsut  

## 訓練參數
batch size:1  
epoch:100  

## 訓練過程
![image](https://github.com/TaiChunYen/kugyu_audio-style-transfer/blob/master/figure/g_loss.png)
![image](https://github.com/TaiChunYen/kugyu_audio-style-transfer/blob/master/figure/d_loss.png)
## 訓練結果
In convert/history/  



