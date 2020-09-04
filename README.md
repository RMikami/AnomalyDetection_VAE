# AnomalyDetection_VAE
以下の記事を参考にヘーゼルナッツの画像を使って、従来手法と提案手法で異常部分の可視化及び数値的比較を行いました。

[Variational Autoencoderを使った画像の異常検知　前編](https://qiita.com/shinmura0/items/811d01384e20bfd1e035)

[Variational Autoencoderを使った画像の異常検知　後編](https://qiita.com/shinmura0/items/6572d782ad21b15b004e)

# Result
## ヒートマップによる異常個所の可視化
### crack
![old_2](https://user-images.githubusercontent.com/70367328/92232405-7111bd00-eee9-11ea-912f-e97b963bc42c.png)
![new_2](https://user-images.githubusercontent.com/70367328/92232411-753dda80-eee9-11ea-9351-19a57e100ba5.png)

### cut
![old_](https://user-images.githubusercontent.com/70367328/92232740-01e89880-eeea-11ea-9b67-aa2a94979d1d.png)
![new_](https://user-images.githubusercontent.com/70367328/92232751-057c1f80-eeea-11ea-88d5-cbc696e9fe0a.png)

### hole
![old_7](https://user-images.githubusercontent.com/70367328/92233632-97385c80-eeeb-11ea-888e-0bffcfa96d0a.png)
![new_7](https://user-images.githubusercontent.com/70367328/92233634-9a334d00-eeeb-11ea-926f-9119f39190f8.png)

### print
![old_6](https://user-images.githubusercontent.com/70367328/92233814-ed0d0480-eeeb-11ea-92cc-db153d282b68.png)
![new_6](https://user-images.githubusercontent.com/70367328/92233826-f1392200-eeeb-11ea-9612-46cae03ab14a.png)

## ROC曲線の描画
