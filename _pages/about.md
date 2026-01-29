---
permalink: /
title: "Academic Pages"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
**Research Interests**
* Industrial process sensing, monitoring, and control.
* Computer vision & deep learning
* LIBS in-situ mineral content analysis

**Education**
* Ph.D. in School of Automation, Central South University, Changsha, China
* Visiting Scholar in Automatic Control and Complex Systems, University of Duisburg-Essen, Duisburg, Germany

Froth Flotation 
======
Froth flotation is the largest tonnage separation in mineral processing by which valuable mineral is separated from gangue in an aerated pulp utilizing differences in their hydrophobicity. It utilizes the hydrophobicity of liberated minerals to separate them from hydrophilic gangue. As shown in Fig. 1 (a), flotation reagents are added into the slurry to change the hydrophobicity of mineral surface. Air is introduced into the slurry via a rotating impeller and produce a substantial quantity of air bubbles in the flotation bank. Hydrophobic particles contact and collide with these air bubbles, resulting in the formation of mineralized bubbles that ascend to the slurry's surface, forming a froth layer. The froth is subsequently scraped off and collected as concentrate, while mineral particles exhibiting strong hydrophilic properties persist within the slurry and are discharged as tailings.
![FlotationPlant](/images/FlotationPlant.jpg)

Effective monitoring is an essential prerequisite to ensure the reliability and safety of this complicated industrial process. Modern flotation plants often employ X-ray fluorescence (XRF) analyzers to detect key performance indices such as concentrate grade, tailing grade, and other pulp grades in typical flotation banks. However, due to the high cost of acquisition and maintenance, a single XRF analyzer needs to sequentially test multiple detection points, which causes the sample time for each pulp grade is about 20min. This makes it challenging to provide timely feedback for the control and decision of the flotation process. Because froth surface appearance is closely related to the flotation performance, increasing efforts have been devoted to develop computer vision-based froth appearance analysis, and monitor the flotation performance by establishing relationship models between appearance features and performance indicators

Computer Vision-Based Flotation Process Monitoring
======
![FlotationPlant](/images/froth_machine_and_image.jpg)
Computer vision–based flotation process monitoring aims to extract meaningful information from froth surface images and establish a reliable link between froth appearance and metallurgical performance. Compared with traditional sampling-based analyzers, vision systems provide non-contact, low-cost, and high-frequency measurements, making them well suited for real-time industrial applications.

In a typical flotation monitoring framework, industrial cameras are installed above flotation cells to continuously acquire froth images. Image processing and machine learning techniques are then employed to characterize froth appearance from multiple perspectives, including froth texture, bubble size distribution, color, mobility, and structural patterns. These visual features implicitly reflect underlying physical and chemical states such as reagent dosage, air flow rate, pulp level, and mineral hydrophobicity.

With the development of deep learning, representation learning methods have increasingly replaced handcrafted features, enabling more robust and adaptive froth characterization under varying operating conditions. By learning high-level visual representations directly from data, deep models can better cope with complex backgrounds, illumination changes, and process disturbances commonly encountered in industrial flotation environments.

The extracted froth features or learned representations are further used to:
* Estimate key performance indicators (KPIs), such as concentrate grade and tailings grade
* Detect abnormal operating conditions and process faults
* Support decision-making and advanced control strategies
Overall, computer vision–based flotation monitoring provides an effective pathway toward intelligent perception, soft sensing, and closed-loop control of flotation processes, contributing to improved process stability, product quality, and resource efficiency.

Laser-Induced Breakdown Spectroscopy (LIBS)-Based Slurry Analysis
======
Laser-induced breakdown spectroscopy (LIBS)–based slurry analysis focuses on achieving rapid, in-situ, and multi-element characterization of mineral slurries in complex industrial environments. By utilizing high-energy laser pulses to generate plasma on or within the slurry, LIBS enables direct acquisition of elemental emission spectra without the need for extensive sample preparation.

In a typical LIBS-based slurry analysis framework, a pulsed laser is directed onto the slurry surface or through an optical window to induce plasma formation. The emitted light from the plasma is collected and spectrally resolved to identify and quantify elemental compositions. Compared with conventional laboratory assays or on-line analyzers, LIBS offers advantages in fast response, low consumable cost, and simultaneous multi-element detection, making it particularly suitable for real-time process monitoring.

However, slurry environments introduce significant challenges, including surface fluctuations, matrix effects, particle size variability, and signal instability. To address these issues, advanced signal processing and machine learning techniques are employed to enhance spectral robustness and improve quantitative accuracy. Data-driven modeling methods enable the extraction of informative spectral representations and the establishment of reliable relationships between LIBS spectra and target mineral contents.

LIBS-based slurry analysis can be applied to:
* In-situ mineral content and grade analysis
* Real-time monitoring of process streams and material balance
* Rapid feedback for process control and optimization
Overall, LIBS-based slurry analysis provides a promising solution for on-line elemental sensing and intelligent decision support in mineral processing, complementing vision-based monitoring approaches and contributing to the development of fully integrated intelligent flotation systems.

LIBS-V Lab
======
The LIBS-V Lab focuses on the integration of laser-induced breakdown spectroscopy (LIBS) and machine vision for flotation process monitoring, optimization, and control. By combining elemental sensing and visual perception, the laboratory aims to provide multi-modal information for understanding flotation dynamics and improving process performance.

The laboratory is equipped with a dual-pulse LIBS slurry analysis platform, including two high-energy pulsed lasers (200 mJ each), fiber-optic spectrometers, timing synchronization units, scientific cameras, and a dedicated slurry sample chamber. This platform enables in-situ and high-temporal-resolution acquisition of spectral signals from mineral slurries, supporting quantitative analysis of mineral composition under realistic process conditions.

To support experimental flotation studies, the lab maintains a complete set of mineral processing equipment, including flotation machines, agitators, and grinding–granulation systems. A dedicated froth image acquisition system, consisting of industrial cameras and controlled illumination modules, is used for continuous froth surface monitoring. The collected image data are consistent with industrial flotation scenarios in terms of visual characteristics and operating conditions.

Raw ores used in the laboratory experiments are supplied by collaborating mineral processing enterprises, ensuring that the ore properties closely match those encountered in industrial flotation plants. This setup allows systematic investigation of the relationships among ore characteristics, LIBS spectral responses, froth appearance, and flotation performance, bridging laboratory research and industrial practice.

Overall, the LIBS-V Lab provides an integrated experimental platform for multi-sensor data acquisition, data-driven modeling, and intelligent control of flotation processes, supporting both fundamental research and application-oriented studies in mineral processing.
