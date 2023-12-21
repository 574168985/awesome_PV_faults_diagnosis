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

图像类型![图像类型](https://img.shields.io/badge/图像类型-2b83e2), 图像的收集方法![收集方法](https://img.shields.io/badge/收集方法-e28a2b), 图像的处理方法![处理方法](https://img.shields.io/badge/处理方法-83e22b), 故障类型及严重程度![故障类型](https://img.shields.io/badge/故障类型-ff0000), 所应用的层次![应用层次](https://img.shields.io/badge/应用层次-009999)(cell, module, string, plant), 实验结果![实验结果](https://img.shields.io/badge/实验结果-330033)(仿真/实际实验), 准确率![准确率](https://img.shields.io/badge/准确率-660066), 以及其他

加一个纵轴数据量 横轴准确率的方图

# 基于多模态融合的方法

图像类型, 图像的收集方法, 图像的处理方法, 如何融合, 故障类型及严重程度, 所应用的层次(cell, module, string, plant), 实验结果(仿真/实际实验), 准确率, 以及其他

其他的相关的文献综述文章

# 基于图像方法的公开数据集 

待续

## 【2023】基于图像的故障监测方法

- [![文献类型](https://img.shields.io/badge/期刊-8A2BE2)|International Journal of Photoenergy，中科院4区] [![图像类型](https://img.shields.io/badge/图像类型-2b83e2)|可见光图像] [![收集方法](https://img.shields.io/badge/收集方法-e28a2b)|无人机] [![处理方法](https://img.shields.io/badge/处理方法-83e22b)|模糊、翻转、旋转、噪声、平移、缩放和扭曲] [![故障类型](https://img.shields.io/badge/故障类型-ff0000)|正常板块、蜗牛痕迹、层裂、玻璃破裂、变色和烧伤] [![应用层次](https://img.shields.io/badge/应用层次-009999)|光伏阵列] [![数据规模](https://img.shields.io/badge/数据规模-990066)|初始600，扩增到3150] [![方法设计](https://img.shields.io/badge/方法设计-6666cc)|CNN+Classifier(不使用AI分类器)] [![准确率](https://img.shields.io/badge/准确率-660066)|宣称在自建数据集上使用DenseNet-201+k-nearest达到100] [Enhancing Photovoltaic Module Fault Diagnosis with Unmanned Aerial Vehicles and Deep Learning-Based Image Analysis](https://www.hindawi.com/journals/ijp/2023/8665729/) **[报告|多分类任务中，非全连接分类器中k-nearest最优]**

## 【2022】基于图像的故障监测方法

- [![文献类型](https://img.shields.io/badge/会议-8A2BE2)|Chinese Control and Decision Conference (CCDC)] [![图像类型](https://img.shields.io/badge/图像类型-2b83e2)|红外图像] [![收集方法](https://img.shields.io/badge/收集方法-e28a2b)|无人机] [![处理方法](https://img.shields.io/badge/处理方法-83e22b)|定位和提取，旋转水平化，去除透视畸变，聚类分割。显著性] [![故障类型](https://img.shields.io/badge/故障类型-ff0000)|热点] [![应用层次](https://img.shields.io/badge/应用层次-009999)|光伏阵列] [![数据规模](https://img.shields.io/badge/数据规模-990066)|拍摄图片135，从中提取了1020个光伏模块，有96个正样本，表示这些PV模块样本中存在热点。另外，有924个负样本，表示这些PV模块是正常的] [![方法设计](https://img.shields.io/badge/方法设计-6666cc)|网格分割->聚类分割] [![准确率](https://img.shields.io/badge/准确率-660066)|宣称在自建数据集达到99.71%] [Hotspot detection of photovoltaic modules in infrared thermal image based on saliency analysis](https://ieeexplore.ieee.org/abstract/document/10033497) **[报告|二分类任务中，聚类分割>网格分割]**

- [![文献类型](https://img.shields.io/badge/会议-8A2BE2)|ICESEP-2022] [![图像类型](https://img.shields.io/badge/图像类型-2b83e2)|红外图像] [![收集方法](https://img.shields.io/badge/收集方法-e28a2b)|无人机] [![处理方法](https://img.shields.io/badge/处理方法-83e22b)|改变热点的位置和大小，裁剪出带热点的部分后对齐大小。报告旋转和翻转无用] [![故障类型](https://img.shields.io/badge/故障类型-ff0000)|热点] [![应用层次](https://img.shields.io/badge/应用层次-009999)|光伏阵列] [![数据规模](https://img.shields.io/badge/数据规模-990066)|初始39张带有热点的图像和235张没有热点的图像，扩增到292张带有热点的图像和292张没有热点的图像] [![方法设计](https://img.shields.io/badge/方法设计-6666cc)|CNN+Classifier(全连接分类器)] [![准确率](https://img.shields.io/badge/准确率-660066)|宣称在自建数据集达到96.58 ] [Hot Spot Detection of Photovoltaic Module Infrared Near-field Image based on Convolutional Neural Network](https://iopscience.iop.org/article/10.1088/1742-6596/2310/1/012076/meta) **[报告|二分类任务中，全连接分类器>朴素贝叶斯分类器]**

- [![文献类型](https://img.shields.io/badge/期刊-8A2BE2)|IEEE Journal of Photovoltaics，中科院3区] [图像类型|电致发光] [![收集方法](https://img.shields.io/badge/收集方法-e28a2b)|激光线扫描] [![处理方法](https://img.shields.io/badge/处理方法-83e22b)|图像堆栈->分类为背景、电致发光或激光像素->重建无接触传统电致发光,强调缺陷电致发光->校准] [![故障类型](https://img.shields.io/badge/故障类型-ff0000)|?] [![应用层次](https://img.shields.io/badge/应用层次-009999)|光伏阵列] [![数据规模](https://img.shields.io/badge/数据规模-990066)|?] [![方法设计](https://img.shields.io/badge/方法设计-6666cc)|?] [![准确率](https://img.shields.io/badge/准确率-660066)|?] [Reconstruction and Calibration of Contactless Electroluminescence Images From Laser Line Scanning of Photovoltaic Modules](https://ieeexplore.ieee.org/abstract/document/9736329) **[报告|?]**

- [![文献类型](https://img.shields.io/badge/期刊-8A2BE2)|Sustainable Energy Grids & Networks，中科院3区] [![图像类型](https://img.shields.io/badge/图像类型-2b83e2)|电致发光] [![收集方法](https://img.shields.io/badge/收集方法-e28a2b)|暗室] [![处理方法](https://img.shields.io/badge/处理方法-83e22b)|？] [![故障类型](https://img.shields.io/badge/故障类型-ff0000)|有缺陷的(功率损失超过初始功率输出的3%被视为有缺陷的电池)，开裂，腐蚀] [![应用层次](https://img.shields.io/badge/应用层次-009999)|光伏阵列] [![数据规模](https://img.shields.io/badge/数据规模-990066)|制备了两个数据集，2624/1028] [![方法设计](https://img.shields.io/badge/方法设计-6666cc)|CNN+Classifier(SVM)] [![准确率](https://img.shields.io/badge/准确率-660066)|宣称在自建数据集上达到99.49] [A combined convolutional neural network model and support vector machine technique for fault detection and classification based on electroluminescence images of photovoltaic modules](https://www.sciencedirect.com/science/article/pii/S2352467722001916) **[报告|？]**

- [![文献类型](https://img.shields.io/badge/期刊-8A2BE2)|IEEE Transactions on Industrial Informatics，中科院1区] [![图像类型](https://img.shields.io/badge/图像类型-2b83e2)|电致发光] [![收集方法](https://img.shields.io/badge/收集方法-e28a2b)|生产制造] [![处理方法](https://img.shields.io/badge/处理方法-83e22b)|？] [![故障类型](https://img.shields.io/badge/故障类型-ff0000)|10] [![应用层次](https://img.shields.io/badge/应用层次-009999)|光伏电池] [![数据规模](https://img.shields.io/badge/数据规模-990066)|36,543] [![方法设计](https://img.shields.io/badge/方法设计-6666cc)|CNN+Classifier(SVM)] [![准确率](https://img.shields.io/badge/准确率-660066)|宣称在自建数据集上达到99.49] [PVEL-AD: A Large-Scale Open-World Dataset for Photovoltaic Cell Anomaly Detection](https://ieeexplore.ieee.org/abstract/document/9744494/algorithms?tabFilter=dataset#algorithms) **[报告|提供公开数据集。第一个为光伏太阳能电池异常检测提供框架真值的公共数据集（目标检测任务）]** 重点

- [![文献类型](https://img.shields.io/badge/期刊-8A2BE2)|mdpi data，中科院未收录] [![图像类型](https://img.shields.io/badge/图像类型-2b83e2)|可见光图像] [![收集方法](https://img.shields.io/badge/收集方法-e28a2b)|生产制造] [![处理方法](https://img.shields.io/badge/处理方法-83e22b)|？] [![故障类型](https://img.shields.io/badge/故障类型-ff0000)|10] [![应用层次](https://img.shields.io/badge/应用层次-009999)|光伏电池] [![数据规模](https://img.shields.io/badge/数据规模-990066)|36,543] [![方法设计](https://img.shields.io/badge/方法设计-6666cc)|CNN+Classifier(SVM)] [![准确率](https://img.shields.io/badge/准确率-660066)|宣称在自建数据集上达到99.49] [Dataset for Detecting the Electrical Behavior of Photovoltaic Panels from RGB Images](https://www.mdpi.com/2306-5729/7/6/82) **[报告|提供公开数据集]**

- [![文献类型](https://img.shields.io/badge/会议-8A2BE2)|Chinese Automation Congress (CAC)] [![图像类型](https://img.shields.io/badge/图像类型-2b83e2)|电致发光] [![收集方法](https://img.shields.io/badge/收集方法-e28a2b)|生产制造] [![处理方法](https://img.shields.io/badge/处理方法-83e22b)|？] [![故障类型](https://img.shields.io/badge/故障类型-ff0000)|10] [![应用层次](https://img.shields.io/badge/应用层次-009999)|光伏电池] [![数据规模](https://img.shields.io/badge/数据规模-990066)|36,543] [![方法设计](https://img.shields.io/badge/方法设计-6666cc)|CNN+Classifier(SVM)] [![准确率](https://img.shields.io/badge/准确率-660066)|宣称在自建数据集上达到99.49] [Defect detection for PV Modules based on the improved YOLOv5s](https://ieeexplore.ieee.org/abstract/document/10055183) **[报告|提供公开数据集]**

