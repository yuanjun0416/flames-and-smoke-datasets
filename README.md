# flames-and-smoke-datasets

## 总结火灾数据集的论文
1. Video Fire Detection Methods Based on Deep Learning: Datasets, Methods, and Future Directions

## 火灾数据集
### 1. DFS
论文： A dataset for fire and smoke object detection \
下载网址：https://github.com/siyuanwu/DFS-FIRE-SMOKE-Dataset?tab=readme-ov-file \
数据集描述：火灾和烟雾检测数据集 (DFS) 包含从真实场景中收集的 9462 张火灾图像。图像根据火焰面积在图像中所占的比例进行分类，包括大火焰、中火焰和小火焰，分别有 3357 张、4722 张和 349 张图像。除了“火焰”和“烟雾”的注释外，DFS 还包含一个名为“其他”的新类别，用于标记车辆灯、路灯、阳光和金属灯等对象，总共包含 1034 张图像。包含此“其他”类别是为了减少因错误分类而导致的误报。\
个人评价：标注的质量不高，且火灾图像的质量也不是很高，DFS中包好大量的其它标注目标"other" 
图片展示(仅展示了火焰和烟雾标注，其余标注请看下载网址或数据集)
![images/DFS/1.jpg](images/DFS/1.jpg)
![images/DFS/2.jpg](images/DFS/2.jpg)

### 2. D-Fire dataset
论文：An automatic fire-detection system based on deep convolutional neural networks for low-power, resource-constrained devices \
官方下载网址：https://github.com/gaiasd/DFireDataset \
数据集描述： D-Fire 数据集是专为对象检测方法开发而设计的火灾和烟雾图像集合。考虑到烟雾和火焰的形态多样，该数据集整合了来自互联网、火灾模拟、监控摄像头和人工合成图像的数据，其中人工烟雾使用计算机软件与绿色景观背景合成。D-Fire 数据集包含 21,527 张带 YOLO 格式标签的图像，共计 26,557 个边界框。其中，1164 张图像描绘了火灾，5867 张图像仅描绘了烟雾，4658 张图像描绘了火灾和烟雾，9838 张图像作为反例。\
个人评价：大量重复图像，大量背景图像，且存在火焰和烟雾的背景很黑，也存在部分类似DFS介绍的图像。 \
图片展示(仅展示了火焰和烟雾标注，其余标注请看数据集)
![images/DFS/1.jpg](images/D-Fire/1.jpg)
![images/DFS/2.jpg](images/D-Fire/2.jpg)

### 3. FASDD
论文： An open flame and smoke detection dataset for deep learning in remote sensing based fire detection \
下载网址： https://github.com/openrsgis/FASDD?tab=readme-ov-file \
数据集描述：火焰烟雾检测数据集 (FASDD) 是一个包含 100,000 级火焰和烟雾图像的大型数据集，这些图像来自各种来源，包括监控摄像机、无人机、多源遥感卫星图像以及描绘火灾场景的计算机图形绘画。此外，FASDD 数据集包含大量小尺寸火焰和烟雾物体，对小物体检测的深度学习研究提出了挑战。它由两个子集组成：FASDD_CV，包括从监控摄像机、瞭望塔和无人机捕获的 95,314 个样本，以及 FASDD_RS，包括 5773 个遥感图像样本。此外，FASDD 提供了三种不同格式的注释文件。 \
个人评价: \
图片展示(仅展示了火焰和烟雾标注，其余标注请看数据集)

### 4. FLAME 
论文：Aerial imagery pile burn detection using deep learning: The FLAME dataset \
下载网址: https://ieee-dataport.org/open-access/flame-dataset-aerial-imagery-pile-burn-detection-using-drones-uavs \
数据集描述: 火光度空中机器学习评估 (FLAME) 提供使用两架无人机 (UAV) 收集的亚利桑那州北部森林中燃烧堆积碎石的航拍图像和视频。该数据集包括使用传统和热成像相机拍摄的四种摄影模式：正常、Fusion、WhiteHot 和 GreenHot。火灾识别任务包括 48,010 张 RGB 航拍图像，分为 30,155 张火灾图像和 17,855 张非火灾图像，专门为野火识别而精心挑选。该数据集包括 2003 个分割掩码，带有用于火灾分割任务的像素级注释。该数据集是火灾识别、分割方法和进一步开发基于视觉的火灾蔓延模型的宝贵资源
个人评价：分割火灾数据集，场景单一，重复图像多
图片展示: 直接在下载网址上可以观察

### 5. BoWFire
论文: Bowfire: Detection of fire in still images by integrating pixel color and texture analysis \
下载网址: https://www.kaggle.com/datasets/malligasenthil/bowfire?select=fire017.png \
数据集描述: BoWFire 数据集包含 226 张不同分辨率的图像，其中 119 张图像描绘火灾，107 张图像代表非火灾场景。火灾图像涵盖紧急火灾事件的不同场景，例如建筑火灾、工业火灾、事故和骚乱。非火灾图像包括红色或黄色色调的火状物体和日落场景。此外，还提供了一个由 240 张分辨率为 50 × 50 像素的图像组成的训练集，其中包括 80 张火灾图像和 160 张非火灾图像。 \
个人评价: 图像数量少

### 6. VisiFire
论文:  Available online: http://signal.ee.bilkent.edu.tr/VisiFire/  \
下载网址:  Available online: http://signal.ee.bilkent.edu.tr/VisiFire/  \
数据集描述: VisiFire 数据集是一个广泛使用的用于火灾和烟雾检测的公共视频数据集。它包含四类视频：火焰、烟雾、其他和森林烟雾。火灾组包含 13 个视频，烟雾组包含 21 个视频，森林烟雾组包含 21 个视频，其他视频组包含 2 个视频。Dharmawan 等人 [30] 从 VisiFire 数据集中选择了 12 个常用视频进行逐帧分割注释，最终得到 2684 个带注释的帧。 \
个人评价: 重复图像多

### 7. fire-smoke-detect-yolov4
下载网址: https://github.com/gengyanlei/fire-smoke-detect-yolov4/blob/master/readmes/README_ZN.md \
个人评价: 标注质量也不是特别好

### 8. Forest Fire
下载网址: https://www.kaggle.com/datasets/kutaykutlu/forest-fire?resource=download \
数据集描述: 未标注, train-smoke中合成烟雾, train_fire中为正常火灾图像 \
图像展示(train_fire):
![images/Forest-Fire/1.jpg](images/Forest-Fire/1.jpg)

### 9. Forest Fire
下载网址: https://www.kaggle.com/datasets/phylake1337/fire-dataset \
数据集描述: 未标注 \

## 双光谱火灾数据集
### 1. Flame 2
论文: FLAME 2: Fire detection and modeLing: Aerial Multi-spectral imagE dataset \
下载网址: https://ieee-dataport.org/open-access/flame-2-fire-detection-and-modeling-aerial-multi-spectral-image-dataset \
个人评价: 大量重复的图像、没有目标检测标注文件 
