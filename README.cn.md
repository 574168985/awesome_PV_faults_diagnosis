[![en](https://img.shields.io/badge/lang-en-blue.svg)](https://github.com/574168985/awesome_PV_faults_diagnosis/edit/main/README.md)
[![pt-br](https://img.shields.io/badge/lang-fr-white.svg)](https://github.com/574168985/awesome_PV_faults_diagnosis/edit/main/README.fr.md)
[![es](https://img.shields.io/badge/lang-cn-red.svg)](https://github.com/574168985/awesome_PV_faults_diagnosis/edit/main/README.cn.md)
# 光伏组件故障监测
光伏组件故障监测文献综述，持续更新中，包括文献、数据集、代码

# 更新计划

在本文献综述中，我们关注:

- [ ] [基于图像的故障监测方法](#基于图像的故障监测方法)
- [ ] [基于多模态融合的方法](#基于多模态融合的方法)
- [ ] [基于图像方法的公开数据集](#基于图像方法的公开数据集)

# 基于图像的故障监测方法

图像类型, 图像的收集方法, 图像的处理方法, 故障类型及严重程度, 所应用的层次(cell, module, string, plant), 实验结果(仿真/实际实验), 准确率, 以及其他

# 基于多模态融合的方法

图像类型, 图像的收集方法, 图像的处理方法, 如何融合, 故障类型及严重程度, 所应用的层次(cell, module, string, plant), 实验结果(仿真/实际实验), 准确率, 以及其他

其他的相关的文献综述文章

# 基于图像方法的公开数据集 

待续

## 【2023】基于图像的故障监测方法

- [期刊|International Journal of Photoenergy，中科院4区] [图像类型|可见光图像] [图像的收集方法|无人机] [图像的处理方法|模糊、翻转、旋转、噪声、平移、缩放和扭曲] [故障类型及严重程度|正常板块、蜗牛痕迹、层裂、玻璃破裂、变色和烧伤] [所应用的层次|光伏阵列] [初始600，扩增到3150] [CNN+Classifier(不使用AI分类器)] [准确率|在自建数据集宣称上使用DenseNet-201+k-nearest达到100] [Enhancing Photovoltaic Module Fault Diagnosis with Unmanned Aerial Vehicles and Deep Learning-Based Image Analysis](https://www.hindawi.com/journals/ijp/2023/8665729/)

- [会议|Chinese Control and Decision Conference (CCDC)] [图像类型|红外图像] [图像的收集方法|无人机] [图像的处理方法|定位和提取，旋转水平化，去除透视畸变，聚类分割。显著性] [故障类型及严重程度|热点] [所应用的层次|光伏阵列] [拍摄图片135，从中提取了1020个光伏模块，有96个正样本，表示这些PV模块样本中存在热点。另外，有924个负样本，表示这些PV模块是正常的] [网格分割->聚类分割] [准确率|在自建数据集宣称达到99.71%] [Hotspot detection of photovoltaic modules in infrared thermal image based on saliency analysis]([https://www.hindawi.com/journals/ijp/2023/8665729/](https://ieeexplore.ieee.org/abstract/document/10033497)https://ieeexplore.ieee.org/abstract/document/10033497/)
