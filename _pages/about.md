---
permalink: /
title: "Jin Zhang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
**Research Interests**
* Computer vision and deep learning for industrial applications
* Industrial process sensing, monitoring, optimization, and control
* Laser-induced breakdown spectroscopy (LIBS) for in situ mineral composition analysis
* Autonomous inspection and intelligent sensing for industrial environments

**Education**
* Ph.D., School of Automation, Central South University, Changsha, China
* Visiting Scholar, Automatic Control and Complex Systems, University of Duisburg-Essen, Duisburg, Germany

Froth Flotation 
======
Froth flotation is one of the most widely used separation processes in mineral processing and handles a substantial fraction of the world's beneficiated ores. It separates valuable minerals from gangue by exploiting differences in their surface hydrophobicity. As illustrated below, flotation reagents are added to the slurry to selectively modify the surface properties of mineral particles. Air is introduced into the slurry through a rotating impeller, generating a large number of bubbles within the flotation cell. Hydrophobic mineral particles collide with and attach to these bubbles, forming mineralized bubbles that rise to the slurry surface and form a froth layer. The froth is subsequently removed and collected as concentrate, whereas strongly hydrophilic particles remain in the slurry and are eventually discharged as tailings.
![FlotationPlant](/images/FlotationPlant.jpg)

Effective process monitoring is essential for ensuring the stable, safe, and efficient operation of flotation plants. Modern flotation circuits often employ X-ray fluorescence (XRF) analyzers to measure key performance indicators, including concentrate grade, tailings grade, and intermediate stream grades. However, because XRF analyzers are expensive to acquire and maintain, a single analyzer is often shared among multiple sampling points. As a result, the sampling interval for an individual stream can be approximately 20 minutes, limiting the availability of timely feedback for process monitoring, control, and decision-making. Because froth surface appearance is closely related to flotation performance, considerable research has focused on computer vision-based froth analysis. By extracting visual information from froth images and establishing relationships between froth appearance and metallurgical performance, vision-based monitoring provides a promising approach to high-frequency and non-contact flotation process sensing.

Computer Vision-Based Flotation Process Monitoring
======
![Froth Image Acquisition System](/images/froth_machine_and_image.jpg)
Computer vision-based flotation process monitoring aims to extract informative characteristics from froth surface images and establish reliable relationships between froth appearance and metallurgical performance. Compared with conventional sampling-based analyzers, vision systems provide non-contact, low-cost, and high-frequency measurements, making them well suited for real-time industrial applications.

In a typical flotation monitoring framework, industrial cameras are installed above flotation cells to continuously acquire froth images. Image processing and machine learning techniques are then employed to characterize froth appearance from multiple perspectives, including texture, bubble size distribution, color, mobility, and structural patterns. These visual characteristics implicitly reflect underlying physical and chemical states of the flotation process, such as reagent dosage, airflow rate, pulp level, and mineral hydrophobicity.

With the rapid development of deep learning, representation learning methods have increasingly complemented or replaced conventional handcrafted features. By learning high-level visual representations directly from data, deep models can provide more robust and adaptive characterization of froth appearance under varying operating conditions. They are also better able to cope with complex backgrounds, illumination variations, and process disturbances commonly encountered in industrial flotation environments.

The extracted froth features and learned representations can be further used to:
* Estimate key performance indicators (KPIs), such as concentrate grade and tailings grade
* Detect abnormal operating conditions and process faults
* Support decision-making and advanced control strategies

Overall, computer vision-based flotation monitoring provides an effective pathway toward intelligent perception, soft sensing, and closed-loop control of flotation processes, contributing to improved process stability, product quality, and resource efficiency.

Laser-Induced Breakdown Spectroscopy (LIBS)-Based Slurry Analysis
======
Laser-induced breakdown spectroscopy (LIBS)-based slurry analysis aims to achieve rapid, in situ, and multielement characterization of mineral slurries under complex industrial conditions. By using high-energy laser pulses to generate plasma on or within the slurry, LIBS enables direct acquisition of elemental emission spectra with minimal sample preparation.

In a typical LIBS-based slurry analysis framework, a pulsed laser is directed onto the slurry surface or through an optical window to induce plasma formation. The light emitted by the plasma is collected and spectrally resolved to identify and quantify elemental compositions. Compared with conventional laboratory assays and many online analyzers, LIBS offers several advantages, including rapid response, low consumable cost, and simultaneous multielement detection, making it particularly attractive for real-time process monitoring.

However, direct LIBS analysis of mineral slurries remains challenging because of surface fluctuations, matrix effects, particle size variations, and spectral signal instability. To address these issues, advanced signal processing and machine learning methods can be employed to improve spectral robustness and quantitative accuracy. Data-driven modeling further enables the extraction of informative spectral representations and the establishment of reliable relationships between LIBS spectra and target mineral compositions.

LIBS-based slurry analysis can be applied to:
* In situ mineral composition and grade analysis
* Real-time monitoring of process streams and material balance
* Rapid feedback for process control and optimization

Overall, LIBS-based slurry analysis provides a promising approach to online elemental sensing and intelligent decision support in mineral processing. It also complements vision-based monitoring by providing direct compositional information, thereby contributing to the development of integrated intelligent flotation systems.

LIBS-V Lab
======
The LIBS-V Lab focuses on integrating laser-induced breakdown spectroscopy (LIBS) and machine vision for flotation process monitoring, optimization, and control. By combining elemental sensing with visual perception, the laboratory aims to provide multimodal information for understanding flotation dynamics and improving process performance.

The laboratory is equipped with a dual-pulse LIBS slurry analysis platform consisting of two high-energy pulsed lasers (200 mJ each), fiber-optic spectrometers, timing and synchronization units, scientific cameras, and a dedicated slurry sample chamber. The platform enables in situ acquisition of mineral slurry spectra with high temporal resolution and supports quantitative analysis of mineral composition under process-relevant conditions.

To support experimental studies of flotation processes, the laboratory maintains a comprehensive set of mineral processing equipment, including flotation machines, agitators, and grinding and granulation systems. A dedicated froth image acquisition system, consisting of industrial cameras and controlled illumination modules, is used for continuous monitoring of froth surface appearance. The resulting image data reproduce key visual characteristics and operating conditions encountered in industrial flotation processes.

The raw ores used in laboratory experiments are supplied by collaborating mineral processing enterprises, ensuring that their properties closely resemble those encountered in industrial flotation plants. This experimental setup enables systematic investigation of the relationships among ore characteristics, LIBS spectral responses, froth appearance, and flotation performance, thereby helping bridge the gap between laboratory research and industrial practice.

Overall, the LIBS-V Lab provides an integrated experimental platform for multisensor data acquisition, data-driven modeling, process monitoring, and intelligent control. It supports both fundamental research and application-oriented studies aimed at advancing intelligent mineral processing and flotation technologies.

研究生招生 
======
欢迎对**智能矿物加工、工业过程感知与控制、计算机视觉、深度学习以及激光诱导击穿光谱（LIBS）**等方向感兴趣的同学加入课题组。

目前主要面向复杂工业过程中的智能感知、建模、优化与控制开展研究，重点包括浮选过程机器视觉监测、矿浆成分在线分析、LIBS 光谱智能解析、无人车巡检、多源异构信息融合、数据驱动软测量以及智能优化控制等。相关研究兼具人工智能、自动化、矿物加工、光谱分析与工业过程控制等多学科交叉特点，并具有较强的工程应用背景。

实验室已搭建较为完善的**浮选实验平台、机器视觉采集系统和 LIBS 矿浆分析平台**，可支持算法开发、实验验证和过程机理研究。同时，我们与相关矿山及选矿企业保持合作，可为学生提供接触真实工业问题、开展现场数据分析与工程验证的机会。

我们欢迎具有自动化、人工智能、计算机、控制科学、矿物加工、光学、仪器科学等相关专业背景的同学加入课题组，也欢迎对上述研究方向感兴趣的本科生参与科研项目和毕业设计。**相比已有研究经验，我们更看重扎实的基础、主动学习的能力，以及对科研问题的兴趣与持续投入**。如果你希望将机器学习、智能感知等方法应用于真实工业过程，或希望开展具有工程背景的多学科交叉研究，欢迎联系交流。
