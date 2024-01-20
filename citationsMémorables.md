- [Deep Learning-Based Fault Diagnosis of Photovoltaic Systems: A Comprehensive Review and Enhancement Prospects](https://ieeexplore.ieee.org/abstract/document/9530686)
Faults can be divided into two types depending on their evolution: significant faults and minor faults. The design of a multi-level diagnosis framework in the deep network model will help achieving the real-time monitoring of significant faults and effectively improve the diagnosis of random faults. In addition, significant faults affect the system performance differently, and small faults are also very likely to cause considerable damage.
**Thus, it is important to develop DL-based algorithms that consider the fusion of faults from different manufacturing environments with different characteristics.**
Moreover, classical DL algorithms are generally utilized to model the dynamic nature of multivariable PV systems in both the offline training and online updating phases using the updated measurements. Instead, using online extensions of DL models for diagnosis in the first place may reduce the training and update time. In addition, complex PV systems often have problems such as uncertainty, multiple fault occurrence, and fault levels changing with time. If only a single FDD technology is used, the accuracy and generalization will be low. Thus, combining multivariate statistical analysis (such as: PCA [15]–​[17], kernel PCA [18]–​[20]), signal processing (such as: Fourier transform, multiscale representation [13], [21], interval-valued data representation [22], [23]), and other tools with DL models could improve the performance of the FDD and more specifically decision-making accuracy. It could also reduce the impact of noise, outliers [24], and uncertainties and estimate the severity of the fault location.

*The accuracy and generalization of non-fusion methods (simple methods) are low, and they exhibit poor robustness. Therefore, it is necessary to combine different variables for analysis.*

*非融合方法（简单方法）的准确率和泛化性低，鲁棒性差，所以有必要组合不同变量进行分析。*

- [Faults and infrared thermographic diagnosis in operating c-Si photovoltaic modules: A review of research and future challenges](https://www.sciencedirect.com/science/article/pii/S1364032116301629#f0060)https://www.sciencedirect.com/science/article/pii/S1364032116301629#f0060
**Photovoltaic (PV) solar energy recorded an exponential growth, in worldwide scale, over the last decade. Inevitably, mature PV markets are becoming highly competitive, boosting the need for research and development (R&D) on efficiency and reliability optimization, maintenance and fault diagnosis of key components, such as the PV modules.**
The power generation of PV plants and the consequent payback time of investments on PV installations, are significantly dependent on the operational lifetime of PV modules and their electrical performance.
Apart from the obvious merit of such long warranty, PV modules technology can become even more attractive for consumers and investors if the energy production cost is further minimized, while at the same time, reliability and durability are kept at top level during operation [11].
However, long-term performance of PV modules and their overall reliability, can be drastically affected by faults occurring mainly under real (field) operation conditions but also during the post-manufacturing stages of transportation and installation [12], [13]. Such faults result in specific abnormal operation, principally characterized by reduced electrical power output, abnormal temperature profiles on the surface of modules, excessive thermal/mechanical stresses or even safety risk for the installation [3], [14].
Considering zero-failure PV production as the ultimate objective for future investors, the strong need to reduce, isolate and, if possible, remove any source of occurring or potential faults, is becoming more than evident [15]. Today, on-line detection and effective diagnosis of any possible fault of PV modules under operation in the field, remains a technical and economic challenge, especially when dealing with large-scale PV plants consisting of hundreds or thousands of PV modules [13].

*After the expansion phase, competition in the photovoltaic market shifts from capacity to optimization of efficiency and reliability, as well as maintenance and fault diagnosis.*

*在扩张阶段之后，光伏市场的竞争不再是产能而是效率和可靠性优化、维护和故障诊断。*

- [Faults and infrared thermographic diagnosis in operating c-Si photovoltaic modules: A review of research and future challenges](https://www-sciencedirect-com.ezproxy.universite-paris-saclay.fr/science/article/pii/S1364032116301629)
However, up today, such research, published in the form of reports, technical papers or even books, remains mostly dispersed and unclassified.

*然而，时至今日，此类以报告、技术论文甚至书籍形式发表的研究仍然大多是分散且未分类的。*

As a result, although PV modules are characterized by limited electrical efficiency, they comprise the most robust part of a PV system, typically featuring warranty periods of up to 25 or 30 years.

*因此，尽管光伏组件的电力效率有限，但它们构成了光伏系统中最坚固的部分，通常具有长达 25 或 30 年的保修期。->服役期*

Conventional inspection of PV modules, by means of electrical performance measurements, is a well-established method which, however, presents limited fault detection ability. Indeed, an abnormal I–V characteristic or a reduced power output of a PV plant or a PV array, can be indicative of an occurring fault. However, the “source” or physical location of this fault can be identified only by performing further, individual electrical measurements to each module. It is evident that such a costly and time-consuming practice, cannot be practically feasible or acceptable by PV plant operators in the competitive PV market. Nevertheless, I–V characterization may still play an auxiliary but important role, providing valuable information on the electrical “signature” of each detected fault and validating its impact on the power output losses of the affected module.通过电气性能测量对光伏组件进行常规检查是一种行之有效的方法，但其故障检测能力有限。事实上，异常的I - V特性或光伏电站或光伏阵列的功率输出降低可能表明发生了故障。然而，只能通过对每个模块进行进一步的单独电气测量来识别该故障的“源”或物理位置。显然，这种成本高昂且耗时的做法在竞争激烈的光伏市场中实际上是不可行或不被光伏电站运营商接受的。尽管如此，I - V表征仍可能发挥辅助但重要的作用，提供有关每个检测到的故障的电气“特征”的有价值的信息，并验证其对受影响模块的功率输出损耗的影响。

*电气信息对于健康监测的作用*

On the other hand, with the advent of digital cameras, charge-coupled device (CCD) and uncooled focal plane array (UFPA) detectors of affordable cost, advanced inspection, based on optical methods, becomes increasingly popular. Specifically, electroluminescence (EL) and IRT imaging comprise effective and powerful tools for qualitative characterization of PV modules; not only to witness the presence of faults within a PV plant, but also to detect their exact location, with high accuracy.
另一方面，随着成本低廉的数码相机、电荷耦合器件（CCD）和非制冷焦平面阵列（UFPA）探测器的出现，基于光学方法的先进检测变得越来越流行。具体而言，电致发光 (EL) 和 IRT 成像构成了光伏组件定性表征的有效且强大的工具；不仅可以见证光伏电站内是否存在故障，还可以高精度检测故障的确切位置。

*光学信息对于健康监测的作用*

EL imaging is a non-invasive technique developed to detect the radiative recombinations of charge carriers excited under forward bias [16]. In more simple words, in a typical EL image, the resultant light intensity is proportional to the voltage; thus, any electrically inactive parts, within a module or cell, are depicted as dark areas [17]. In principle, EL inspection of PV modules can indicate the presence and location of cell cracks and shunts, potential induced degradation (PID) and inactive submodules/strings (due to shunted bypass diodes or open-circuits), with great accuracy [3]. However, in several cases of optical degradation and failure, such as delamination or glass (front-cover) breakage, EL-based diagnosis is very limited or even inefficient. Besides, EL appears techno-economically effective and, thus, competitive, for small-scale indoor characterization rather than for large-scale outdoor diagnosis, due to the following practical limitations:
•
Inspections are not performed under realistic, maximum power-point (MPP) conditions; only during nighttime or after interrupting the PV plant׳s operation.

•
In the case of large-scale PV installations, EL testing protocol involves the use of very large power supply; the experimental set-up inevitably becomes complex and energy/cost- and time-consuming.

•
EL imaging gives no information on the thermal impact of a potential fault and, thus, no estimation on the resultant power output loss can be done for the impacted PV module; purely qualitative rather than quantitative diagnosis.


Only recently, advances in photoluminescence (PL) and EL imaging equipment, involving InGaAs uncooled detectors and InSb cooled ones, comprise the first steps for reliable outdoor measurements and fault diagnosis of installed PV plants, even under real-sun conditions [18], [19]. The output PL/EL images from such state-of-the-art detectors, provide fast, reliable and on-site diagnosis of faults (e.g. interrupted interconnects or cell cracks) with remarkable details, even on cell scale. Research in this field is still in early stages, however with promising prospects.
EL 成像是一种非侵入性技术，旨在检测正向偏压下激发的电荷载流子的辐射复合[16]。更简单地说，在典型的 EL 图像中，合成的光强度与电压成正比；因此，模块或电池内的任何电不活跃部分都被描述为暗区[17]。原则上，光伏模块的 EL 检查可以非常准确地指示电池裂纹和分流、电势诱导退化(PID) 和不活动子模块/串（由于分流旁路二极管或开路）的存在和位置[3]。然而，在一些光学退化和故障的情况下，例如分层或玻璃（前盖）破裂，基于 EL 的诊断非常有限，甚至效率低下。此外，由于以下实际限制，EL 似乎在技术经济上有效，因此对于小规模室内表征而不是大规模室外诊断具有竞争力：•检查不是在实际的最大功率点 (MPP) 条件下进行的；仅在夜间或中断光伏电站运行后。•在大型光伏装置的情况下，EL测试协议涉及使用非常大的电源；实验装置不可避免地变得复杂并且耗费能源/成本和时间。•EL 成像无法提供有关潜在故障的热影响的信息，因此无法对受影响的光伏模块产生的功率输出损失进行估计；纯粹定性而非定量诊断。
直到最近，光致发光 (PL) 和 EL 成像设备（包括InGaAs非制冷探测器和 InSb 制冷探测器）的进步，构成了对已安装光伏电站进行可靠户外测量和故障诊断的第一步，即使在真实的阳光条件下也是如此[18]，[ 19]。这些最先进的探测器输出的 PL/EL 图像可以提供快速、可靠的现场故障诊断（例如互连中断或电池裂纹），并且具有非凡的细节，即使是在电池规模上也是如此。该领域的研究仍处于早期阶段，但前景广阔。

*光学信息中的EL和PL信息对于健康监测的作用*

IRT-based diagnosis, on the other hand, appears likely more suitable to provide this missing quantitative information and to overcome, at the same time, the aforementioned limitations. In principle, IRT or thermal imaging refers to the nondestructive detection and measurement of infrared radiation, which is intrinsically emitted by the surface of any body, and its depiction, by means of appropriate imagers (thermal cameras), in the form of two- or three-dimensional pseudocolor images of temperature distribution (i.e. thermal images) [20]. In the case of PV applications, field IRT measurements of PV modules are performed outdoors, under steady-state illumination (i.e. clear-sky or, in the worst case, maximum 2 okta non-cumulus cloud coverage, is preferred) and MPP conditions. Under such conditions, heat and electricity are generated by the incident irradiance which, in the case of a “healthy” PV module, is expected to cause homogeneous temperature distribution on its surface. Since the majority of occurring faults have a significant impact on the thermal behavior of the PV module, they are detected as inhomogeneities of its surface temperature distribution, as depicted on the thermal image of the defective module. In other words, IRT can provide information about the thermal signature and the exact physical location of an occurring fault, indicating the defective cell, group of cells or module (qualitative diagnosis). In turn, such thermal signature can be used for quantitative diagnosis, by identifying the electrical power output losses of the impacted module, in the form of dissipated heat. What makes IRT even more “appealing” for fault diagnosis of PV modules, is the fact that the thermal images can be obtained in a fast way, with minimal instrumentations, without the involvement of any sensor and without interrupting the operation of the PV system in the field [3], [13]. For the above reasons, as we will see in Section 3, IRT has already provided several promising results, reported in the recent literature, in the research field of fault diagnosis of PV modules.
另一方面，基于 IRT 的诊断似乎更适合提供缺失的定量信息，同时克服上述限制。原则上，IRT或热成像是指对任何物体表面本质上发射的红外辐射进行无损检测和测量，并通过适当的成像仪（热像仪）以两个或多个图像的形式对其进行描绘。温度分布的三维伪彩色图像（即热图像）[20]。在光伏应用的情况下，光伏模块的现场IRT测量在室外、稳态照明（即晴空，或者在最坏的情况下，最大2okta非积云覆盖是首选）和MPP条件下进行。在这种情况下，入射辐照度会产生热量和电力，在“健康”光伏组件的情况下，预计会在其表面产生均匀的温度分布。由于大多数发生的故障对光伏模块的热行为都有重大影响，因此它们被检测为表面温度分布的不均匀性，如缺陷模块的热图像所示。换句话说，IRT 可以提供有关热特征和发生故障的确切物理位置的信息，指示有缺陷的电池、电池组或模块（定性诊断）。反过来，这种热特征可以通过识别受影响模块的耗散热量形式的电力输出损耗来用于定量诊断。IRT 对于光伏组件故障诊断更具“吸引力”，因为它可以快速获取热图像，使用最少的仪器，无需任何传感器的参与，也无需中断光伏系统的运行。字段[3]、[13]。由于上述原因，正如我们将在第 3 节中看到的，IRT 已经在光伏组件故障诊断研究领域提供了一些有希望的成果，这些成果在最近的文献中报道。

*光学信息中的IR信息对于健康监测的作用*

**融合方法在第三节的分类的表达方法:**

提出了一个统一的定位框架来阐明大多数 FBIP 作品的范式。然后，基于这个框架，我们将在第三节、第四节和第五节分别从源空间、算法空间和权重空间讨论FBIP的工作。

提出了一个统一的融合定位框架，以便于比较 FBIP 中的最先进作品，如图3所示；统一融合定位框架由源空间、算法空间、权重空间三部分组成。从数学上来说，我们可以得到最终的位置估计

本次调查将回答 FBIP 中的以下两个问题：融合什么、如何融合？

融合什么？融合源之间的互补性是决定实现改进融合结果潜力的主要因素。换句话说，只有互补性好的融合源才能在定位精度和鲁棒性方面带来更好的增强[30]。本文总结了不同网络框架中常用的融合源。

怎么融合？考虑到上述融合源，如何将它们集中有效地融合是提高基于融合的系统性能的关键[80]。我们首先从以下几个方面回顾融合定位中使用的主要方法：传统方法 机器学习方法 状态估计方法

*不同点：任务目标单一，都是室内定位；而健康监测面对多种故障*

*可以利用的点：都是说一个对于融合类方法的综述的行文逻辑，分类方法*
