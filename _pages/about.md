---
permalink: /
title: "Academic Pages"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
**Research Interests**
* Computer vision and deep learning for industrial applications
* Industrial process sensing, monitoring, and control
* Laser-induced breakdown spectroscopy (LIBS) for in situ mineral composition analysis

**Education**
* Ph.D., School of Automation, Central South University, Changsha, China
* Visiting Scholar, Automatic Control and Complex Systems, University of Duisburg-Essen, Duisburg, Germany

Froth Flotation 
======
Froth flotation is one of the most widely used separation processes in mineral processing and handles a substantial fraction of the world's beneficiated ores. It separates valuable minerals from gangue by exploiting differences in their surface hydrophobicity. As illustrated in Fig. 1(a), flotation reagents are added to the slurry to selectively modify the surface properties of mineral particles. Air is introduced into the slurry through a rotating impeller, generating a large number of bubbles within the flotation cell. Hydrophobic mineral particles collide with and attach to these bubbles, forming mineralized bubbles that rise to the slurry surface and form a froth layer. The froth is subsequently removed and collected as concentrate, whereas strongly hydrophilic particles remain in the slurry and are eventually discharged as tailings.
![FlotationPlant](/images/FlotationPlant.jpg)

Effective process monitoring is essential for ensuring the stable, safe, and efficient operation of flotation plants. Modern flotation circuits often employ X-ray fluorescence (XRF) analyzers to measure key performance indicators, including concentrate grade, tailings grade, and intermediate stream grades. However, because XRF analyzers are expensive to acquire and maintain, a single analyzer is often shared among multiple sampling points. As a result, the sampling interval for an individual stream can be approximately 20 minutes, limiting the availability of timely feedback for process monitoring, control, and decision-making. Because froth surface appearance is closely related to flotation performance, considerable research has focused on computer vision-based froth analysis. By extracting visual information from froth images and establishing relationships between froth appearance and metallurgical performance, vision-based monitoring provides a promising approach to high-frequency and non-contact flotation process sensing.

Computer Vision-Based Flotation Process Monitoring
======
![FlotationPlant](/images/froth_machine_and_image.jpg)
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
* In-situ mineral content and grade analysis
* Real-time monitoring of process streams and material balance
* Rapid feedback for process control and optimization
Overall, LIBS-based slurry analysis provides a promising approach to online elemental sensing and intelligent decision support in mineral processing. It also complements vision-based monitoring by providing direct compositional information, thereby contributing to the development of integrated intelligent flotation systems.

LIBS-V Lab
======
The LIBS-V Lab focuses on integrating laser-induced breakdown spectroscopy (LIBS) and machine vision for flotation process monitoring, optimization, and control. By combining elemental sensing with visual perception, the laboratory aims to provide multimodal information for understanding flotation dynamics and improving process performance.

The laboratory is equipped with a dual-pulse LIBS slurry analysis platform consisting of two high-energy pulsed lasers (200 mJ each), fiber-optic spectrometers, timing and synchronization units, scientific cameras, and a dedicated slurry sample chamber. The platform enables in situ acquisition of mineral slurry spectra with high temporal resolution and supports quantitative analysis of mineral composition under process-relevant conditions.To support experimental studies of flotation processes, the laboratory maintains a comprehensive set of mineral processing equipment, including flotation machines, agitators, and grinding and granulation systems. A dedicated froth image acquisition system, consisting of industrial cameras and controlled illumination modules, is used for continuous monitoring of froth surface appearance. The resulting image data reproduce key visual characteristics and operating conditions encountered in industrial flotation processes.

The raw ores used in laboratory experiments are supplied by collaborating mineral processing enterprises, ensuring that their properties closely resemble those encountered in industrial flotation plants. This experimental setup enables systematic investigation of the relationships among ore characteristics, LIBS spectral responses, froth appearance, and flotation performance, thereby helping bridge the gap between laboratory research and industrial practice.

Overall, the LIBS-V Lab provides an integrated experimental platform for multisensor data acquisition, data-driven modeling, process monitoring, and intelligent control. It supports both fundamental research and application-oriented studies aimed at advancing intelligent mineral processing and flotation technologies.
