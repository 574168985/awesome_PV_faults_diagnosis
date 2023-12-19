[![en](https://img.shields.io/badge/lang-en-blue.svg)](https://github.com/574168985/awesome_PV_faults_diagnosis/edit/main/README.md)
[![fr](https://img.shields.io/badge/lang-fr-white.svg)](https://github.com/574168985/awesome_PV_faults_diagnosis/edit/main/README.fr.md)
[![cn](https://img.shields.io/badge/lang-cn-red.svg)](https://github.com/574168985/awesome_PV_faults_diagnosis/edit/main/README.cn.md)
# 光伏组件故障监测
光伏组件故障监测文献综述，持续更新中，包括文献、数据集、代码

# 更新计划

在本文献综述中，我们关注:

- [ ] [基于图像的故障监测方法](#基于图像的故障监测方法)
- [ ] [基于多模态融合的方法](#基于多模态融合的方法)
- [ ] [基于图像方法的公开数据集](#基于图像方法的公开数据集)

# 基于图像的故障监测方法

图像类型, 图像的收集方法, 图像的处理方法, 故障类型及严重程度, 所应用的层次(cell, module, string, plant), 实验结果(仿真/实际实验), 准确率, 以及其他

[![图像类型](https://img.shields.io/badge/图像类型-图像类型-blue.svg)]

# 基于多模态融合的方法

图像类型, 图像的收集方法, 图像的处理方法, 如何融合, 故障类型及严重程度, 所应用的层次(cell, module, string, plant), 实验结果(仿真/实际实验), 准确率, 以及其他

其他的相关的文献综述文章

# 基于图像方法的公开数据集 

待续

## 【2023】基于图像的故障监测方法

- [期刊|International Journal of Photoenergy，中科院4区] [图像类型|可见光图像] [图像的收集方法|无人机] [图像的处理方法|模糊、翻转、旋转、噪声、平移、缩放和扭曲] [故障类型及严重程度|正常板块、蜗牛痕迹、层裂、玻璃破裂、变色和烧伤] [所应用的层次|光伏阵列] [初始600，扩增到3150] [CNN+Classifier(不使用AI分类器)] [准确率|宣称在自建数据集上使用DenseNet-201+k-nearest达到100] [Enhancing Photovoltaic Module Fault Diagnosis with Unmanned Aerial Vehicles and Deep Learning-Based Image Analysis](https://www.hindawi.com/journals/ijp/2023/8665729/) **[报告|多分类任务中，非全连接分类器中k-nearest最优]**

- [会议|Chinese Control and Decision Conference (CCDC)] [图像类型|红外图像] [图像的收集方法|无人机] [图像的处理方法|定位和提取，旋转水平化，去除透视畸变，聚类分割。显著性] [故障类型及严重程度|热点] [所应用的层次|光伏阵列] [拍摄图片135，从中提取了1020个光伏模块，有96个正样本，表示这些PV模块样本中存在热点。另外，有924个负样本，表示这些PV模块是正常的] [网格分割->聚类分割] [准确率|宣称在自建数据集达到99.71%] [Hotspot detection of photovoltaic modules in infrared thermal image based on saliency analysis](https://ieeexplore.ieee.org/abstract/document/10033497) **[报告|二分类任务中，聚类分割>网格分割]**

- [会议|ICESEP-2022] [图像类型|红外图像] [图像的收集方法|无人机] [图像的处理方法|改变热点的位置和大小，裁剪出带热点的部分后对齐大小。报告旋转和翻转无用] [故障类型及严重程度|热点] [所应用的层次|光伏阵列] [初始39张带有热点的图像和235张没有热点的图像，扩增到292张带有热点的图像和292张没有热点的图像] [CNN+Classifier(全连接分类器)] [准确率|宣称在自建数据集达到96.58 ] [Hot Spot Detection of Photovoltaic Module Infrared Near-field Image based on Convolutional Neural Network](https://iopscience.iop.org/article/10.1088/1742-6596/2310/1/012076/meta) **[报告|二分类任务中，全连接分类器>朴素贝叶斯分类器]**

- [期刊|IEEE Journal of Photovoltaics，中科院3区] [图像类型|电致发光] [图像的收集方法|激光线扫描] [图像的处理方法|模糊、翻转、旋转、噪声、平移、缩放和扭曲] [故障类型及严重程度|正常板块、蜗牛痕迹、层裂、玻璃破裂、变色和烧伤] [所应用的层次|光伏阵列] [初始600，扩增到3150] [CNN+Classifier(不使用AI分类器)] [准确率|宣称在自建数据集上使用DenseNet-201+k-nearest达到100] [Reconstruction and Calibration of Contactless Electroluminescence Images From Laser Line Scanning of Photovoltaic Modules](https://ieeexplore.ieee.org/abstract/document/9736329) **[报告|多分类任务中，非全连接分类器中k-nearest最优]**
