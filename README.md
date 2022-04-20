# BUAA-UESD33
这是BUAA-UESD33数据集的原始图片，共有10000张。包含33颗卫星，5种特征部件的标注图片
数据集可以在这里下载


Satellite Models
===
### 
卫星模型中为论文中使用的33颗卫星模型的几何文件，及其对应的结构图。可以在这里下载
The satellite models and their equipments diagrams in our paper could be downloaded here
[baidu disk]：https://pan.baidu.com/s/15iQRhna1JqZQ2r8gI-O4GA  提取码：BUAA
[buaa disk] :https://bhpan.buaa.edu.cn:443/link/C1F1E003D3AF6B173DFF8B30132DDB9E



### Benchmark
| Method | BG | Panel | Antenna | Instrument | Thruster | Optical Payload | mIoU | mIoU(no bg) |
| :---: | :---: | :---: | :---: | :---: | :---: |:---: | :---: | :---: |
| Danet| 99.6 | 85.69 | 77.65 | 54.24 | 46.16 | 64.64 | 71.33 | 65.68 |
| Deeplabv3+| 99.83 | 88.67 | 84.98 | 66.53 | 62.25 | 76.99 | 76.99 | 75.88 |
| Ocrnet| 99.69 | 89.03| 83.33 | 63.3 | 56.21 | 73.9 | 77.58 | 73.15 |
| Sfnet| 99.74 | 89.51 | 86.6 | 68.77 | 67.66 | 78.42 | 81.78 | 78.19 |
| VAN-B| 99.77 | 90.97 | 84.99 | 71.24 | 66.65 | 78.36 | 82.0 | 78.44 |
| ConvNext-B| 99.83 | 93.85 | 89.66 | 72.98 | 72.92 | 83.87 | 85.52 | 82.66 |
| Our method | 99.85 | 94.18 | 89.85 | 77.06 | 76.19 | 85.71 | 87.14 | 84.60 |  
