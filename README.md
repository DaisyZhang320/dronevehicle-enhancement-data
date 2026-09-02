DroneVehicle Enhancement Data
DroneVehicle可见光图像增强测试配对数据

#数据组成
共200组一一对应的测试配对：
- Heavy Haze：100组
- Heavy Dark + Noise：100组
每组数据包含：
- GT：白天干净图像
- INPUT：对应的重度退化图像
GT与INPUT采用完全相同的文件名，可直接用于配对测试。

#数据结构
- haze/GT
- haze/INPUT
- dark_noise/GT
- dark_noise/INPUT
- manifests/test_pairs.csv

#下载
请在右侧Releases中下载v1.0.0版本的数据压缩包。
