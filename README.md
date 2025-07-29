# Awesome-Robotics-Manipulation

## ✨ About

This repo contains a curated list of **Robot Manipulation** papers at the intersection of robotics and deep learning..

This repository will be continuously updated, and we warmly welcome contributions from the community. If you have papers, projects, or resources that are not yet included, please feel free to submit them via a pull request, open an issue for discussion or [email](baishuanghao@stu.xjtu.edu.cn) us to add papers! 

## 📢 News

Our comprehensive survey is in progress—stay tuned for updates!

- **[2025/07]** Expanded coverage of *Dexterous*, *Soft Robotic*, *Mobile*, *Quadrupedal*, and *Humanoid Manipulation*; refined the categorization and content for *Awesome Simulators, Benchmarks, and Datasets*，added non-learning-based control methods.  
- **[2025/06]** Introduced new sections on *Grasping in Cluttered Scenes*, *Quadrupedal and Humanoid Manipulation*, and *Learning from Human Demonstrations*. Also improved the classification of the *Applications* section and added a subsection on *Embodied QA Datasets*.  
- **[2025/02]** Added a new section on *Bimanual Grasping*.  
- **[2024/12]** Introduced coverage of *Dexterous Grasping*.  
- **[2024/10]** Repository is now public!



<!-- ******* 0 - Content Table ******* -->
## 🏠 Table of Contents
- [📝 Awesome Papers](#-awesome-papers)
  - [📄 Survey](#-survey)
  - [🦾 Grasp](#-grasp)
    - [Non-learning Grasp](#non-learning-grasp)
    - [Rectangle-based Grasp](#rectangle-based-grasp)
    - [6-DoF Grasp](#6-dof-grasp)
    - [Grasp with 3D Techniques](#grasp-with-3d-techniques)
    - [Language-Driven Grasp](#language-driven-grasp)
    - [Grasp for Transparent Objects](#grasp-for-transparent-objects)
    - [Dexterous Grasp](#dexterous-grasp)
    - [Bimanual Grasp](#bimanual-grasp)
  - [🤖 Manipulation](#-manipulation)
    - [Representation Learning with Auxiliary Tasks](#representation-learning-with-auxiliary-tasks)
    - [Visual Imitation Learning](#visual-imitation-learning)
    - [Learning from Demonstrations](#learning-from-demonstrations)
    - [Latent Action Learning](#latent-action-learning)
    - [World Model](#world-model)
    - [Asynchronous Action Learning](#asynchronous-action-learning)
    - [Diffusion Policy Learning](#diffusion-policy-learning)
    - [Other Policies](#other-policies)
    - [Vision Language Action Models](#vision-language-action-models)
    - [Tactile-based Action Models](#tactile-based-action-models)
    - [Reinforcement Learning](#reinforcement-learning)
    - [Motion, Tranjectory and Flow](#motion-tranjectory-and-flow)
    - [Data Collection, Selection and Augmentation](#data-collection-selection-and-augmentation)
    - [Affordance Learning](#affordance-learning)
    - [3D Representation for Manipulation](#3d-representation-for-manipulation)
    - [3D Representation Policy Learning](#3d-representation-policy-learning)
    - [High-level Planner](#high-level-planner)
    - [Generalization](#generalization)
    - [Generalist](#generalist)
    - [Human-Robot Interaction and Collaboration](#human-robot-interaction-and-collaboration)
    - [Dexterous Manipulation](#dexterous-manipulation)
    - [Soft Robotic Manipulation](#soft-robotic-manipulation)
    - [Deformable Object Manipulation](#deformable-object-manipulation)
    - [Mobile Manipulation](#mobile-manipulation)
    - [Quadrupedal Manipulation](#quadrupedal-manipulation)
    - [Humanoid Manipulation](#humanoid-manipulation)
    - [Other Applications](#other-applications)
- [📊 Awesome Simulators, Benchmarks and Datasets](#-awesome-simulators-benchmarks-and-dataset)
  - [Grasp Datasets](#grasp-datasets)
  - [Single-Embodiment Manipulation Simulators and Benchmarks](#single-embodiment-manipulation-simulators-and-benchmarks)
  - [Cross-Embodiment Simulators and Benchmarks](#cross-embodiment-simulators-and-benchmarks)
  - [Other Simulators and Benchmarks](#other-simulators-and-benchmarks)
  - [Trajectory Datasets](#trajectory-datasets)
  - [Embodied QA and Affordance Datasets](#embodied-qa-and-affordance-datasets)
- [🛠️ Awesome Techniques](#-awesome-techniques)



<!-- ******* 1 - Papers ******* -->
## 📝 Awesome Papers

<!-- ******* 1.1 - Survey ******* -->
## 📄 Survey
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| _VLA Models_ |
| [**Vision Language Action Models in Robotic Manipulation: A Systematic Review**](https://arxiv.org/abs/2507.10672) | arXiv | 2025-07-14 | - | VLA Models |
| [**A Survey on Vision-Language-Action Models: An Action Tokenization Perspective**](https://arxiv.org/abs/2507.01925) | arXiv | 2025-07-02 | - | VLA Models |
| [**Parallels Between VLA Model Post-Training and Human Motor Learning: Progress, Challenges, and Trends**](https://arxiv.org/abs/2506.20966) | arXiv | 2025-05-26 | ![Star](https://img.shields.io/github/stars/AoqunJin/Awesome-VLA-Post-Training?style=social&label=Star) [Github](https://github.com/AoqunJin/Awesome-VLA-Post-Training) | VLA Models |
| [**Vision-Language-Action Models: Concepts, Progress, Applications and Challenges**](https://arxiv.org/abs/2505.04769) | arXiv | 2025-05-07 | - | VLA Models |
| [**A Survey on Vision-Language-Action Models for Embodied AI**](https://arxiv.org/abs/2405.14093) | arXiv | 2024-05-23 | - | VLA Models |
| _Dexterous Manipulation_ |
| [**The Developments and Challenges towards Dexterous and Embodied Robotic Manipulation: A Survey**](https://arxiv.org/abs/2507.11840) | arXiv | 2025-07-16 | - | Dexterous Manipulation |
| [**Interactive Imitation Learning for Dexterous Robotic Manipulation: Challenges and Perspectives -- A Survey**](https://arxiv.org/abs/2506.00098) | arXiv | 2025-06-30 | - | Dexterous Manipulation |
| [**Dexterous Manipulation through Imitation Learning: A Survey**](https://arxiv.org/abs/2504.03515) | arXiv | 2025-04-04 | - | Dexterous Manipulation |
| _Deformable Object Manipulation (DOM)_ |
| [**T-DOM: A Taxonomy for Robotic Manipulation of Deformable Objects**](https://arxiv.org/abs/2412.20998) | arXiv | 2024-12-30 | [Project](https://sites.google.com/view/t-dom) | DOM |
| [**A Survey on Robotic Manipulation of Deformable Objects: Recent Advances, Open Challenges and New Frontiers**](https://arxiv.org/abs/2312.10419) | arXiv | 2023-12-16 | - | DOM |
| [**Robotic manipulation and sensing of deformable objects in domestic and industrial applications: a survey**](https://uca.hal.science/hal-01816189/document) | IJRR 2018 | 2018-06-13 | - | DOM |
| _Humanoid Manipulation_ |
| [**Humanoid Locomotion and Manipulation: Current Progress and Challenges in Control, Planning, and Learning**](https://arxiv.org/abs/2501.02116) | arXiv | 2025-01-03 | - | Humanoid Manipulation |
| [**Teleoperation of Humanoid Robots: A Survey**](https://arxiv.org/abs/2301.04317) | T-RO 2024 | 2023-01-11 | [Project](https://humanoid-teleoperation.github.io/) | Humanoid |
| _Others_ |
| [**A Survey of Robotic Navigation and Manipulation with Physics Simulators in the Era of Embodied AI**](https://arxiv.org/abs/2505.01458) | arXiv | 2025-05-01 | - | Navigation and Manipulation |
| [**Diffusion Models for Robotic Manipulation: A Survey**](https://arxiv.org/abs/2504.08438) | arXiv | 2025-04-11 | - | Manipulation + DP |
| [**Multimodal Fusion and Vision-Language Models: A Survey for Robot Vision**](https://arxiv.org/abs/2504.02477) | arXiv | 2025-04-03 | ![Star](https://img.shields.io/github/stars/Xiaofeng-Han-Res/MF-RV?style=social&label=Star) [Github](https://github.com/Xiaofeng-Han-Res/MF-RV) | Robot Vision |
| [**Generative Artificial Intelligence in Robotic Manipulation: A Survey**](https://arxiv.org/abs/2503.03464) | arXiv | 2025-03-05 | ![Star](https://img.shields.io/github/stars/GAI4Manipulation/AwesomeGAIManipulation?style=social&label=Star) [Github](https://github.com/GAI4Manipulation/AwesomeGAIManipulation) | Manipulation |
| [**A Survey of Embodied Learning for Object-Centric Robotic Manipulation**](https://arxiv.org/abs/2408.11537) | arXiv | 2024-08-21 | ![Star](https://img.shields.io/github/stars/RayYoh/OCRM_survey?style=social&label=Star) [Github](https://github.com/RayYoh/OCRM_survey) | Manipulation |
| [**Aligning Cyber Space with Physical World: A Comprehensive Survey on Embodied AI**](https://arxiv.org/abs/2407.06886) | arXiv | 2024-07-09 | ![Star](https://img.shields.io/github/stars/HCPLab-SYSU/Embodied_AI_Paper_List?style=social&label=Star) [Github](https://github.com/HCPLab-SYSU/Embodied_AI_Paper_List) | Embodied Agent |
| [**Survey of Learning-based Approaches for Robotic In-Hand Manipulation**](https://arxiv.org/abs/2401.07915) | arXiv | 2024-01-15 | - | In-hand Manipulation |
| [**Language-conditioned Learning for Robotic Manipulation: A Survey**](https://arxiv.org/abs/2312.10807) | arXiv | 2023-12-17 | ![Star](https://img.shields.io/github/stars/hk-zh/language-conditioned-robot-manipulation-models?style=social&label=Star) [Github](https://github.com/hk-zh/language-conditioned-robot-manipulation-models) | Manipulation |
| [**Deep Learning Approaches to Grasp Synthesis: A Review**](https://arxiv.org/abs/2207.02556) | T-RO 2023 | 2023-07-06 | [Project](https://rhys-newbury.github.io/projects/6dof/) | Grasp |
| [**A Survey of Wheeled Mobile Manipulation: A Decision Making Perspective**](https://par.nsf.gov/servlets/purl/10393722) | J. Mech. Robot. 2023 | 2023-04 | - | Mobile Manipulation |
| [**A Review of Soft Manipulator Research, Applications, and Opportunities**](https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.22051) | J Field Robot. 2023 | 2023-04 | - | Soft Manipulator |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>



<!-- ******* 1.2 - Grasp ******* -->
## 🦾 Grasp

<!-- ******* 1.2.1 - 2D Grasp Detection ******* -->
### Non-learning Grasp
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Behavior-Grounded Representation of Tool Affordances**](https://ieeexplore.ieee.org/document/1570580) | ICRA 2005 | 2006-04 | - | |
| [**Graspit! a Versatile Simulator for Robotic Grasping**](https://ieeexplore.ieee.org/document/1371616) | RAM 2004 | 2004-12 | [Project](https://graspit-simulator.github.io/) | |
| [**A fast and robust grasp planner for arbitrary 3D objects**](https://ieeexplore.ieee.org/abstract/document/770384/) | ICRA 1999 | 1999-05 | - | |
| [**Planning Two-fingered Grasps for Pick-and-Place Operations on Polyhedra**](https://ieeexplore.ieee.org/document/126063) | ICRA 1990 | 1990-05 | - | |

<!-- ******* 1.2.2 - Rectangle-based Grasp ******* -->
### Rectangle-based Grasp
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**RoboGrasp: A Universal Grasping Policy for Robust Robotic Control**](https://arxiv.org/abs/2502.03072) | arXiv | 2025-02-05 | - | |
| [**HMT-Grasp: A Hybrid Mamba-Transformer Approach for Robot Grasping in Cluttered Environments**](https://arxiv.org/abs/2410.03522) | arXiv | 2024-10-04 | - | |
| [LLGD: **Lightweight Language-driven Grasp Detection using Conditional Consistency Model**](https://arxiv.org/abs/2407.17967) | IROS 2024 | 2024-07-25 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/Lightweight-Language-driven-Grasp-Detection?style=social&label=Star) [Github](https://github.com/Fsoft-AIC/Lightweight-Language-driven-Grasp-Detection) | |
| [TF-Grasp: **When Transformer Meets Robotic Grasping: Exploits Context for Efficient Grasp Detection**](https://arxiv.org/abs/2107.05287) | RA-L 2022 | 2022-02-24 | ![Star](https://img.shields.io/github/stars/WangShaoSUN/grasp-transformer?style=social&label=Star) [Github](https://github.com/WangShaoSUN/grasp-transformer) |  |
| [grasp_det_seg_cnn: **End-to-end Trainable Deep Neural Network for Robotic Grasp Detection and Semantic Segmentation from RGB**](https://arxiv.org/abs/2107.05287) | ICRA 2021 | 2021-07-12 | ![Star](https://img.shields.io/github/stars/stefan-ainetter/grasp_det_seg_cnn?style=social&label=Star) [Github](https://github.com/stefan-ainetter/grasp_det_seg_cnn) |  |
| [GR-ConvNet: **Antipodal Robotic Grasping using Generative Residual Convolutional Neural Network**](https://arxiv.org/abs/1909.04810) | IROS 2020 | 2019-09-11 | ![Star](https://img.shields.io/github/stars/skumra/robotic-grasping?style=social&label=Star)  [Github](https://github.com/skumra/robotic-grasping) |  |
| [**Closing the Loop for Robotic Grasping: A Real-time, Generative Grasp Synthesis Approach**](https://arxiv.org/abs/1804.05172) | RSS 2018 | 2018-04-14 | ![Star](https://img.shields.io/github/stars/dougsm/ggcnn?style=social&label=Star)  [Github](https://github.com/dougsm/ggcnn) |  |
| [**Robotic Grasp Detection using Deep Convolutional Neural Networks**](https://arxiv.org/abs/1611.08036) | IROS 2017 | 2016-11-24 | ![Star](https://img.shields.io/github/stars/tnikolla/robot-grasp-detection?style=social&label=Star)  [Github](https://github.com/tnikolla/robot-grasp-detection) |  |
| [**Real-Time Grasp Detection Using Convolutional Neural Networks**](https://arxiv.org/abs/1412.3128) | ICRA 2015 | 2014-12-09 | - |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.3 - 6-DoF Grasp ******* -->
### 6-DoF Grasp
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Grasp in Cluttered Scenes_ |
| [**MISCGrasp: Leveraging Multiple Integrated Scales and Contrastive Learning for Enhanced Volumetric Grasping**](https://arxiv.org/abs/2507.02672) | arXiv | 2025-07-02 | [Project](https://miscgrasp.github.io/) |  |
| [**ClutterDexGrasp: A Sim-to-Real System for General Dexterous Grasping in Cluttered Scenes**](https://arxiv.org/abs/2506.14317) | arXiv | 2025-06-17 | [Project](https://clutterdexgrasp.github.io/) | |
| [**Grasp the Graph (GtG) 2.0: Ensemble of GNNs for High-Precision Grasp Pose Detection in Clutter**](https://arxiv.org/abs/2505.02664) | arXiv | 2025-05-05 | ![Star](https://img.shields.io/github/stars/Ali-Rashidi/GtG2?style=social&label=Star) [Github](https://github.com/Ali-Rashidi/GtG2) |  |
| [**PCF-Grasp: Converting Point Completion to Geometry Feature to Enhance 6-DoF Grasp**](https://arxiv.org/abs/2504.16320) | arXiv | 2025-04-22 | ![Star](https://img.shields.io/github/stars/ChengYaofeng/PCF-Grasp?style=social&label=Star) [Github](https://github.com/ChengYaofeng/PCF-Grasp) |  |
| [**MISCGrasp: Leveraging Multiple Integrated Scales and Contrastive Learning for Enhanced Volumetric Grasping**](https://arxiv.org/abs/2507.02672) | IROS 2025 | 2025-07-03 | [Project](https://miscgrasp.github.io/) |  |
| [**Exploiting Radiance Fields for Grasp Generation on Novel Synthetic Views**](https://arxiv.org/abs/2505.11467) | RSSW 2025 | 2025-05-16 | ![Star](https://img.shields.io/github/stars/Ali-Rashidi/GtG2?style=social&label=Star) [Github](https://github.com/Ali-Rashidi/GtG2) |  |
| [**ZeroGrasp: Zero-Shot Shape Reconstruction Enabled Robotic Grasping**](https://arxiv.org/abs/2504.10857) | CVPR 2025 | 2025-04-15 | ![Star](https://img.shields.io/github/stars/sh8/ZeroGrasp?style=social&label=Star) [Github](https://github.com/sh8/ZeroGrasp) |  |
| [**Real-to-Sim Grasp: Rethinking the Gap between Simulation and Real World in Grasp Detection**](https://arxiv.org/abs/2410.06521) | CoRL 2024 | 2024-10-09 | [Project](https://isee-laboratory.github.io/R2SGrasp/) | Real2Sim |
| [**OrbitGrasp: SE(3)-Equivariant Grasp Learning**](https://arxiv.org/abs/2407.03531) | CoRL 2024 | 2024-07-03 | [Project](https://orbitgrasp.github.io/) | Equivariance |
| [EconomicGrasp: **An Economic Framework for 6-DoF Grasp Detection**](https://arxiv.org/abs/2407.08366) | ECCV 2024 | 2024-07-11 | ![Star](https://img.shields.io/github/stars/iSEE-Laboratory/EconomicGrasp?style=social&label=Star) [Github](https://github.com/iSEE-Laboratory/EconomicGrasp) | Scene-level |
| [**Generalizing 6-DoF Grasp Detection via Domain Prior Knowledge**](https://arxiv.org/abs/2404.01727) | CVPR 2024 | 2024-04-02 | ![Star](https://img.shields.io/github/stars/mahaoxiang822/Generalizing-Grasp?style=social&label=Star) [Github](https://github.com/mahaoxiang822/Generalizing-Grasp) | Generalization |
| [HGGD: **Efficient Heatmap-Guided 6-Dof Grasp Detection in Cluttered Scenes**](https://arxiv.org/abs/2403.18546) | RA-L 2023 | 2024-03-27 | ![Star](https://img.shields.io/github/stars/THU-VCLab/HGGD?style=social&label=Star) [Github](https://github.com/THU-VCLab/HGGD) | Scene-level |
| [**Contact-GraspNet: Efficient 6-DoF Grasp Generation in Cluttered Scenes**](https://arxiv.org/abs/2103.14127) | ICRA 2021 | 2021-03-25 | ![Star](https://img.shields.io/github/stars/NVlabs/contact_graspnet?style=social&label=Star) [Github](https://github.com/NVlabs/contact_graspnet) | |
| [**GraspNet-1Billion: A Large-Scale Benchmark for General Object Grasping**](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_GraspNet-1Billion_A_Large-Scale_Benchmark_for_General_Object_Grasping_CVPR_2020_paper.pdf) | CVPR 2020 | 2020-08-05 | ![Star](https://img.shields.io/github/stars/graspnet/graspnet-baseline?style=social&label=Star) [Github](https://github.com/graspnet/graspnet-baseline) | Scene-level |
| [**6-DOF Grasping for Target-driven Object Manipulation in Clutter**](https://arxiv.org/abs/1912.03628) | ICRA 2020 | 2019-12-08 | - | |
| _Grasp in Uncluttered Scenes_ |
| [**EquiGraspFlow: SE(3)-Equivariant 6-DoF Grasp Pose Generative Flows**](https://openreview.net/pdf?id=5lSkn5v4LK) | CoRL 2024 | 2024-09-06 | ![Star](https://img.shields.io/github/stars/bdlim99/EquiGraspFlow?style=social&label=Star) [Github](https://github.com/bdlim99/EquiGraspFlow) | Equivariance |
| [FlexLoG: **Rethinking 6-Dof Grasp Detection: A Flexible Framework for High-Quality Grasping**](https://arxiv.org/abs/2403.15054) | PR 2025 | 2024-03-22 | - | Target-oriented |
| [**AnyGrasp: Robust and Efficient Grasp Perception in Spatial and Temporal Domains**](https://arxiv.org/abs/2212.08333) | T-RO 2023 | 2022-12-16 | ![Star](https://img.shields.io/github/stars/graspnet/anygrasp_sdk?style=social&label=Star) [Github](https://github.com/graspnet/anygrasp_sdk) | |
| [**MonoGraspNet: 6-DoF Grasping with a Single RGB Image**](https://arxiv.org/abs/2209.13036) | ICRA 2023 | 2022-09-26 | - | |
| [**6-DOF GraspNet: Variational Grasp Generation for Object Manipulation**](https://arxiv.org/abs/1905.10520) | ICCV 2019 | 2019-05-25 | ![Star](https://img.shields.io/github/stars/NVlabs/6dof-graspnet?style=social&label=Star) [Github](https://github.com/NVlabs/6dof-graspnet) | VAE |
| [**Learning 6-DOF Grasping Interaction via Deep Geometry-aware 3D Representations**](https://arxiv.org/abs/1708.07303) | ICRA 2018 | 2017-08-24 | [Project](https://xcyan.github.io/geoaware_grasping/) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.4 - Grasp with 3D Techniques ******* -->
### Grasp with 3D Techniques
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _SDF_|
| [IGD: **Implicit Grasp Diffusion: Bridging the Gap between Dense Prediction and Sampling-based Grasping**](https://openreview.net/pdf?id=VUhlMfEekm) | CoRL 2024 | 2024-09-05 | ![Star](https://img.shields.io/github/stars/mousecpn/Implicit-Grasp-Diffusion?style=social&label=Star) [Github](https://github.com/mousecpn/Implicit-Grasp-Diffusion) |  |
| [NeuGraspNet: **Learning Any-View 6DoF Robotic Grasping in Cluttered Scenes via Neural Surface Rendering**](https://arxiv.org/abs/2306.07392) | RSS 2024 | 2023-06-12 | - | |
| [**Volumetric Grasping Network: Real-time 6 DOF Grasp Detection in Clutter**](https://arxiv.org/abs/2101.01132) | CoRL 2020 | 2021-01-04 | ![Star](https://img.shields.io/github/stars/ethz-asl/vgn?style=social&label=Star) [Github](https://github.com/ethz-asl/vgn) |  |
| _NeRF_ |
| [LERF-TOGO: **Language Embedded Radiance Fields for Zero-Shot Task-Oriented Grasping**](https://arxiv.org/abs/2309.07970) | CoRL 2023 | 2023-09-14 | ![Star](https://img.shields.io/github/stars/lerftogo/lerftogo?style=social&label=Star) [Github](https://github.com/lerftogo/lerftogo) | LERF |
| [**GraspNeRF: Multiview-based 6-DoF Grasp Detection for Transparent and Specular Objects Using Generalizable NeRF**](https://arxiv.org/abs/2210.06575) | ICRA 2023 | 2022-10-12 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/GraspNeRF?style=social&label=Star) [Github](https://github.com/PKU-EPIC/GraspNeRF) | |
| _3D Gaussian Splatting (3DGS)_ |
| [**SparseGrasp: Robotic Grasping via 3D Semantic Gaussian Splatting from Sparse Multi-View RGB Images**](https://arxiv.org/abs/2412.02140) | arXiv | 2024-12-03 | - | |
| [**GraspSplats: Efficient Manipulation with 3D Feature Splatting**](https://arxiv.org/abs/2409.02084) | CoRL 2024 | 2024-09-03 | ![Star](https://img.shields.io/github/stars/jimazeyu/GraspSplats?style=social&label=Star) [Github](https://github.com/jimazeyu/GraspSplats) | |
| [**GaussianGrasper: 3D Language Gaussian Splatting for Open-vocabulary Robotic Grasping**](https://arxiv.org/abs/2403.09637) | RA-L 2024 | 2024-03-14 | ![Star](https://img.shields.io/github/stars/MrSecant/GaussianGrasper?style=social&label=Star) [Github](https://github.com/MrSecant/GaussianGrasper) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.5 - Language-Driven Grasp ******* -->
### Language-Driven Grasp
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**FineGrasp: Towards Robust Grasping for Delicate Objects**](https://arxiv.org/abs/2507.05978) | arXiv | 2025-07-08 | ![Star](https://img.shields.io/github/stars/HorizonRobotics/robo_orchard_lab?style=social&label=Star) [Github](https://github.com/HorizonRobotics/robo_orchard_lab/tree/master/projects/finegrasp_graspnet1b) | |
| [**MapleGrasp: Mask-guided Feature Pooling for Language-driven Efficient Robotic Grasping**](https://arxiv.org/abs/2506.06535) | arXiv | 2025-06-06 | - | |
| [**GraspMolmo: Generalizable Task-Oriented Grasping via Large-Scale Synthetic Data Generation**](https://arxiv.org/abs/2505.13441) | arXiv | 2025-05-19 |  ![Star](https://img.shields.io/github/stars/abhaybd/GraspMolmo?style=social&label=Star) [Github](https://github.com/abhaybd/GraspMolmo) | |
| [**GraspCorrect: Robotic Grasp Correction via Vision-Language Model-Guided Feedback***](https://arxiv.org/abs/2503.15035) | arXiv | 2025-03-19 | - | |
| [**Free-form language-based robotic reasoning and grasping**](https://arxiv.org/abs/2503.13082) | arXiv | 2025-03-17 | [Project](https://tev-fbk.github.io/FreeGrasp/) | |
| [**AffordGrasp: In-Context Affordance Reasoning for Open-Vocabulary Task-Oriented Grasping in Clutter**](https://arxiv.org/abs/2503.00778) | arXiv | 2025-03-02 | [Project](https://eqcy.github.io/affordgrasp/) | |
| [**RoboReflect: Robotic Reflective Reasoning for Grasping Ambiguous-Condition Objects**](https://arxiv.org/abs/2501.09307) | arXiv | 2025-01-16 | - | |
| [**Attribute-Based Robotic Grasping with Data-Efficient Adaptation**](https://arxiv.org/abs/2501.02149) | T-RO 2024 | 2024-12-12 | [Project](https://sites.google.com/umn.edu/attributes-grasping) | |
| [**RTAGrasp: Learning Task-Oriented Grasping from Human Videos via Retrieval, Transfer, and Alignment**](https://arxiv.org/abs/2409.16033) | ICRA 2025 | 2024-09-24 | [Project](https://sites.google.com/view/rtagrasp/home) | LfD |
| [LGrasp6D: **Language-Driven 6-DoF Grasp Detection Using Negative Prompt Guidance**](https://arxiv.org/abs/2407.13842) | ECCV 2024 | 2024-07-18 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance?style=social&label=Star) [Github](https://github.com/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance) | |
| [Reasoning Grasping: **Reasoning Grasping via Multimodal Large Language Model**](https://arxiv.org/abs/2402.06798) | CoRL 2024 | 2024-02-09 | [Project](https://reasoning-grasping.github.io/) | LLMs |
| [**ThinkGrasp: A Vision-Language System for Strategic Part Grasping in Clutter**](https://arxiv.org/abs/2407.11298) | CoRL 2024 | 2024-07-16 | ![Star](https://img.shields.io/github/stars/H-Freax/ThinkGrasp?style=social&label=Star) [Github](https://github.com/H-Freax/ThinkGrasp) | MLLMs |
| [OWG: **Towards Open-World Grasping with Large Vision-Language Models**](https://arxiv.org/abs/2406.18722) | CoRL 2024 | 2024-06-26 | [Project](https://gtziafas.github.io/OWG_project/) | MLLMs |
| [**RT-Grasp: Reasoning Tuning Robotic Grasping via Multi-modal Large Language Model**](https://arxiv.org/abs/2411.05212) | IROS 2024 | 2024-11-07 | [Project](https://sites.google.com/view/rt-grasp) | Tunning MLLMs |
| [**VL-Grasp: a 6-Dof Interactive Grasp Policy for Language-Oriented Objects in Cluttered Indoor Scenes**](https://arxiv.org/abs/2308.00640) | IROS 2023 | 2023-08-01 | ![Star](https://img.shields.io/github/stars/luyh20/VL-Grasp?style=social&label=Star) [Github](https://github.com/luyh20/VL-Grasp) | |
| [**GraspGPT: Leveraging Semantic Knowledge from a Large Language Model for Task-Oriented Grasping**](https://arxiv.org/abs/2307.13204) | RA-L 2023 | 2023-07-25 | ![Star](https://img.shields.io/github/stars/mkt1412/GraspGPT_public?style=social&label=Star) [Github](https://github.com/mkt1412/GraspGPT_public) | |
| [**A Joint Modeling of Vision-Language-Action for Target-oriented Grasping in Clutter**](https://arxiv.org/abs/2302.12610) | ICRA 2023 | 2023-02-24 | ![Star](https://img.shields.io/github/stars/xukechun/Vision-Language-Grasping?style=social&label=Star) [Github](https://github.com/xukechun/Vision-Language-Grasping) | |
| [**Learning 6-DoF Fine-grained Grasp Detection Based on Part Affordance Grounding**](https://arxiv.org/pdf/2301.11564) | TASE 2025 | 2023-01-27 | ![Star](https://img.shields.io/github/stars/aaronhd/LangPartGPD?style=social&label=Star) [Github](https://github.com/aaronhd/LangPartGPD) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.6 - Grasp for Transparent Objects ******* -->
### Grasp for Transparent Objects
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**DCIRNet: Depth Completion with Iterative Refinement for Dexterous Grasping of Transparent and Reflective Objects**](https://arxiv.org/abs/2506.09491) | arXiv | 2025-06-11 | - | |
| [**SR3D: Unleashing Single-view 3D Reconstruction for Transparent and Specular Object Grasping**](https://arxiv.org/abs/2505.24305) | arXiv | 2025-05-30 | [Project](https://sites.google.com/view/sr3dtech/) | |
| [**FuseGrasp: Radar-Camera Fusion for Robotic Grasping of Transparent Objects**](https://arxiv.org/abs/2502.20037) | arXiv | 2025-02-27 | - | |
| [**TranSplat: Surface Embedding-guided 3D Gaussian Splatting for Transparent Object Manipulation**](https://arxiv.org/abs/2502.07840) | arXiv | 2025-02-11 | - | |
| [**T<sup>2</sup>SQNet: A Recognition Model for Manipulating Partially Observed Transparent Tableware Objects**](https://openreview.net/pdf?id=M0JtsLuhEE) | CoRL 2024 | 2024-09-06 | ![Star](https://img.shields.io/github/stars/seungyeon-k/T2SQNet-public?style=social&label=Star) [Github](https://github.com/seungyeon-k/T2SQNet-public) | |
| [**Residual-NeRF: Learning Residual NeRFs for Transparent Object Manipulation**](https://arxiv.org/abs/2405.06181) | ICRA 2024 | 2024-05-10 | ![Star](https://img.shields.io/github/stars/momentum-robotics-lab/residual-nerf?style=social&label=Star) [Github](https://github.com/momentum-robotics-lab/residual-nerf) | |
| [**ASGrasp: Generalizable Transparent Object Reconstruction and Grasping from RGB-D Active Stereo Camera**](https://arxiv.org/abs/2405.05648) | ICRA 2024 | 2024-05-09 | ![Star](https://img.shields.io/github/stars/jun7-shi/ASGrasp?style=social&label=Star) [Github](https://github.com/jun7-shi/ASGrasp) | |
| [**Dex-NeRF: Using a Neural Radiance Field to Grasp Transparent Objects**](https://arxiv.org/abs/2110.14217) | CoRL 2021 | 2021-10-27 | ![Star](https://img.shields.io/github/stars/BerkeleyAutomation/dex-nerf-datasets?style=social&label=Star) [Github](https://github.com/BerkeleyAutomation/dex-nerf-datasets) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.7 - Dexterous Grasp ******* -->
### Dexterous Grasp
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**You Only Estimate Once: Unified, One-stage, Real-Time Category-level Articulated Object 6D Pose Estimation for Robotic Grasping**](https://arxiv.org/abs/2506.05719) | ICRA 2025 | 2025-06-06 | [Project](https://shanehuanghz.github.io/YOEO/) |  |
| [**Grasp What You Want: Embodied Dexterous Grasping System Driven by Your Voice**](https://arxiv.org/abs/2412.10694) | arXiv | 2024-12-14 | [Project](https://isee-laboratory.github.io/R2SGrasp/) | Real2Sim |
| [**UniGraspTransformer: Simplified Policy Distillation for Scalable Dexterous Robotic Grasping**](https://arxiv.org/abs/2412.02699) | arXiv | 2024-12-03 | ![Star](https://img.shields.io/github/stars/microsoft/UniGraspTransformer?style=social&label=Star) [Github](https://github.com/microsoft/UniGraspTransformer) | |
| [**Grasp as You Say: Language-guided Dexterous Grasp Generation**](https://arxiv.org/abs/2405.19291) | NeurIPS 2024 | 2024-05-29 | ![Star](https://img.shields.io/github/stars/iSEE-Laboratory/Grasp-as-You-Say?style=social&label=Star) [Github](https://github.com/iSEE-Laboratory/Grasp-as-You-Say) |
| [**D(R, O) Grasp: A Unified Representation of Robot and Object Interaction for Cross-Embodiment Dexterous Grasping**](https://arxiv.org/abs/2410.01702) | CoRLW 2024 | 2024-10-02 | ![Star](https://img.shields.io/github/stars/zhenyuwei2003/DRO-Grasp?style=social&label=Star) [Github](https://github.com/zhenyuwei2003/DRO-Grasp) |
| [**Dexterous Grasp Transformer**](https://arxiv.org/abs/2404.18135) | CVPR 2024 | 2024-04-28 | ![Star](https://img.shields.io/github/stars/iSEE-Laboratory/DGTR?style=social&label=Star) [Github](https://github.com/iSEE-Laboratory/DGTR) |
| [**DexDiffuser: Generating Dexterous Grasps with Diffusion Models**](https://arxiv.org/abs/2402.02989) | RA-L 2024 | 2024-02-05 | ![Star](https://img.shields.io/github/stars/YuLiHN/DexDiffuser?style=social&label=Star) [Github](https://github.com/YuLiHN/DexDiffuser) |
| [**GenDexGrasp: Generalizable Dexterous Grasping**](https://arxiv.org/abs/2210.00722) | ICRA 2023  | 2022-10-03 | ![Star](https://img.shields.io/github/stars/tengyu-liu/GenDexGrasp?style=social&label=Star) [Github](https://github.com/tengyu-liu/GenDexGrasp) |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.8 - Bimanual Grasp ******* -->
### Bimanual Grasp
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**COMBO-Grasp: Learning Constraint-Based Manipulation for Bimanual Occluded Grasping**](https://arxiv.org/abs/2502.08054) | arXiv | 2025-02-12 | [Project](https://combo-grasp.github.io/) | |
| [**Learning Ambidextrous Robot Grasping Policies**](https://www.science.org/doi/10.1126/scirobotics.aau4984?ijkey=IogH9u4mOL70s&keytype=ref&siteid=robotics) | SR 2019 | 2029-01-30 | - | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>



<!-- ******* 1.3 - Manipulation ******* -->
## 🤖 Manipulation

<!-- ******* 1.3.1 - Representation Learning with Auxiliary Tasks ******* -->
### Representation Learning with Auxiliary Tasks
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Contrastive Learning (Alignment)_ |
| [Σ-agent: **Contrastive Imitation Learning for Language-guided Multi-Task Robotic Manipulation**](https://arxiv.org/abs/2406.09738) | CoRL 2024 | 2024-06-14 | [Project](https://teleema.github.io/projects/Sigma_Agent/) | IL, RepL, Poliy Head, Alignment |
| [**Vid2Robot: End-to-end Video-conditioned Policy Learning with Cross-Attention Transformers**](https://arxiv.org/abs/2403.12943) | RSS 2024 | 2024-03-19 | [Project](https://vid2robot.github.io/) | IL, RepL, LfD, E-D, Poliy Head, Language Goal, Alignment |
| [**R3M: A Universal Visual Representation for Robot Manipulation**](https://arxiv.org/abs/2203.12601) | CoRL 2022 | 2022-03-23 | ![Star](https://img.shields.io/github/stars/facebookresearch/r3m?style=social&label=Star) [Github](https://github.com/facebookresearch/r3m) | IL, RepL, LfD, Alignment, Language Goal, Poliy Head |
| [HULC: **What Matters in Language Conditioned Robotic Imitation Learning over Unstructured Data**](https://arxiv.org/abs/2204.06252) | RA-L 2022 | 2022-04-13 | ![Star](https://img.shields.io/github/stars/lukashermann/hulc?style=social&label=Star) [Github](https://github.com/lukashermann/hulc) | IL, RepL, Alignment, Language Goal, Poliy Head |
| [**BC-Z: Zero-Shot Task Generalization with Robotic Imitation Learning**](https://arxiv.org/abs/2202.02005) | CoRL 2021 | 2022-02-04 | ![Star](https://img.shields.io/github/stars/google-research/tensor2robot?style=social&label=Star) [Github](https://github.com/google-research/tensor2robot/tree/master/research/bcz) | IL, RepL, Language Goal, Alignment, Poliy Head |
| _Masked Reconstruction_ |
| [STP: **Spatiotemporal Predictive Pre-training for Robotic Motor Control**](https://arxiv.org/abs/2403.05304) | arXiv | 2024-03-08 | - | IL, RepL, Masked Construction, Image Prediction, Poliy Head  |
| [**MUTEX: Learning Unified Policies from Multimodal Task Specifications**](https://arxiv.org/abs/2309.14320) | CoRL 2023 | 2023-09-25 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/mutex?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/mutex) | IL, RepL, Multimodal, E-D, Masked Construction, TP |
| [**Robot Learning with Sensorimotor Pre-training**](https://arxiv.org/abs/2306.10007) | CoRL 2023 | 2023-06-16 | [Project](https://robotic-pretrained-transformer.github.io/) | |
| [Voltron: **Language-Driven Representation Learning for Robotics**](https://arxiv.org/abs/2302.12766) | RSS 2023 | 2023-02-24 | ![Star](https://img.shields.io/github/stars/siddk/voltron-robotics?style=social&label=Star) [Github](https://github.com/siddk/voltron-robotics) | IL, RepL, Masked Construction, Both Goals, Poliy Head |
| [MVP: **Real-World Robot Learning with Masked Visual Pre-training**](https://arxiv.org/abs/2210.03109) | CoRL 2022 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/ir413/mvp?style=social&label=Star) [Github](https://github.com/ir413/mvp) | IL, RepL, Masked Construction, Image Goal, Poliy Head |
| _Text Goal Generation_ |
| [**Gondola: Grounded Vision Language Planning for Generalizable Robotic Manipulation**](https://arxiv.org/abs/2506.11261) | arXiv | 2025-06-12 | [Project](https://cshizhe.github.io/projects/robot_gondola.html) | |
| [**RACER: Rich Language-Guided Failure Recovery Policies for Imitation Learning**](https://arxiv.org/abs/2409.14674) | ICRA 2025 | 2024-09-23 | ![Star](https://img.shields.io/github/stars/sled-group/RACER?style=social&label=Star) [Github](https://github.com/sled-group/RACER) | IL, RepL, Human Intervention Generation, Poliy Head, Language Goal |
| [**EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought**](https://arxiv.org/abs/2305.15021) | NeurIPS 2023 | 2023-05-24 | ![Star](https://img.shields.io/github/stars/EmbodiedGPT/EmbodiedGPT_Pytorch?style=social&label=Star) [Github](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch) |  |
| [COTPC: **Chain-of-Thought Predictive Control**](https://arxiv.org/abs/2304.00776) | ICML 2024 | 2023-04-03 | ![Star](https://img.shields.io/github/stars/SeanJia/CoTPC?style=social&label=Star) [Github](https://github.com/SeanJia/CoTPC) | IL, RepL, CoT  |
| _Visual Goal Generation_ |
| [**VIRT: Vision Instructed Transformer for Robotic Manipulation**](https://arxiv.org/abs/2410.07169) | arXiv | 2024-10-09 | ![Star](https://img.shields.io/github/stars/Lizhuoling/VIRT?style=social&label=Star) [Github](https://github.com/Lizhuoling/VIRT) |  |
| [**KOI: Accelerating Online Imitation Learning via Hybrid Key-state Guidance**](https://www.arxiv.org/abs/2408.02912) | CoRL 2024 | 2024-08-06 | ![Star](https://img.shields.io/github/stars/GeWu-Lab/Keystate_Online_Imitation?style=social&label=Star) [Github](https://github.com/GeWu-Lab/Keystate_Online_Imitation) | Online IL, Motion Key States |
| [GENIMA: **Generative Image as Action Models**](https://arxiv.org/abs/2407.07875) | CoRL 2024 | 2024-07-10 | ![Star](https://img.shields.io/github/stars/MohitShridhar/genima?style=social&label=Star)  [Github](https://github.com/MohitShridhar/genima) | diffusion, draw joint-actions |
| [ATM: **Any-point Trajectory Modeling for Policy Learning**](https://arxiv.org/abs/2401.00025) | RSS 2024 | 2023-12-28 | ![Star](https://img.shields.io/github/stars/Large-Trajectory-Model/any-point-trajectory-modeling?style=social&label=Star) [Github](https://github.com/Large-Trajectory-Model/any-point-trajectory-modeling) | IL, RepL, Point Trajectories Generation |
| [MPI: **Learning Manipulation by Predicting Interaction**](https://www.arxiv.org/abs/2406.00439) | RSS 2024 | 2024-06-01 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/MPI?style=social&label=Star) [Github](https://github.com/OpenDriveLab/MPI) | IL, RepL, Interaction-oriented Prediction, Both Goals, Poliy Head |
| [OCI: **Object-Centric Instruction Augmentation for Robotic Manipulation**](https://arxiv.org/abs/2401.02814) | ICRA 2024 | 2024-01-05 | [Project](https://oci-robotics.github.io/) |  IL, RepL, Object-Centric Information Generation, Poliy Head, Language Goal |
| [HOPMan: **Towards Generalizable Zero-Shot Manipulation via Translating Human Interaction Plans**](https://arxiv.org/abs/2312.00775) | ICRA 2024 | 2023-12-01 | [Project](https://homangab.github.io/hopman/) | IL, RepL, LfD, Image Goal, E-D, TP, Human-Plan Generation |
| [**CALAMARI: Contact-Aware and Language conditioned spatial Action MApping for contact-RIch manipulation**](https://openreview.net/pdf?id=Nii0_rRJwN) | CoRL 2023 | 2023-08-30 | [Project](https://www.mmintlab.com/research/calamari/) | RepL, Language Goal, Contact Goal Generation |
| _Image / Video Prediction_ |
| [**ERMV: Editing 4D Robotic Multi-view images to enhance embodied agentss**](https://arxiv.org/abs/2507.17462) | arXiv | 2025-07-23 | ![Star](https://img.shields.io/github/stars/IRMVLab/ERMV?style=social&label=Star) [Github](https://github.com/IRMVLab/ERMV) |  |
| [**Generalist Bimanual Manipulation via Foundation Video Diffusion Models**](https://arxiv.org/abs/2507.12898) | arXiv | 2025-07-17 | - |  |
| [**RwoR: Generating Robot Demonstrations from Human Hand Collection for Policy Learning without Robot**](https://arxiv.org/abs/2507.03930) | arXiv | 2025-07-05 | - |  |
| [**RoboEnvision: A Long-Horizon Video Generation Model for Multi-Task Robot Manipulation**](https://arxiv.org/abs/2506.22007) | arXiv | 2025-06-27 | [Project](https://rwor.github.io/) |  |
| [**Self-Adapting Improvement Loops for Robotic Learning**](https://arxiv.org/abs/2506.06658) | arXiv | 2025-06-07 | [Project](https://diffusion-supervision.github.io/sail/) |  |
| [**ORV: 4D Occupancy-centric Robot Video Generation**](https://arxiv.org/abs/2506.03079) | arXiv | 2025-06-03 | ![Star](https://img.shields.io/github/stars/OrangeSodahub/ORV?style=social&label=Star) [Github](https://github.com/OrangeSodahub/ORV) |  |
| [**Learning Video Generation for Robotic Manipulation with Collaborative Trajectory Control**](https://arxiv.org/abs/2506.01943) | arXiv | 2025-06-02 | ![Star](https://img.shields.io/github/stars/KwaiVGI/RoboMaster?style=social&label=Star) [Github](https://github.com/KwaiVGI/RoboMaster) |  |
| [**GEVRM: Goal-Expressive Video Generation Model For Robust Visual Manipulation**](https://arxiv.org/abs/2502.09268) | ICLR 2025 | 2025-02-13 | - |  |
| [Seer: **Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation**](https://arxiv.org/abs/2412.15109) | ICLR 2025 | 2024-12-19 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/Seer?style=social&label=Star) [Github](https://github.com/OpenRobotLab/Seer/) |  |
| [**Video Prediction Policy: A Generalist Robot Policy with Predictive Visual Representations**](https://arxiv.org/abs/2412.14803) | ICML 2025 | 2024-12-19 | [Project](https://video-prediction-policy.github.io/) |  |
| [**GHIL-Glue: Hierarchical Control with Filtered Subgoal Images**](https://arxiv.org/abs/2410.20018) | arXiv | 2024-10-26 | [Project](https://ghil-glue.github.io/) |  |
| [**FoAM: Foresight-Augmented Multi-Task Imitation Policy for Robotic Manipulation**](https://arxiv.org/abs/2409.19528) | arXiv | 2024-09-29 | [Project](https://projfoam.github.io/) |  |
| [**VideoAgent: Self-Improving Video Generation**](https://arxiv.org/abs/2410.10076) | arXiv | 2024-10-14 | ![Star](https://img.shields.io/github/stars/video-as-agent/videoagent?style=social&label=Star) [Github](https://github.com/video-as-agent/videoagent) |  |
| [**GR-MG: Leveraging Partially Annotated Data via Multi-Modal Goal Conditioned Policy**](https://arxiv.org/abs/2408.14368) | RA-L 2025 | 2024-08-26 | ![Star](https://img.shields.io/github/stars/bytedance/GR-MG?style=social&label=Star) [Github](https://github.com/bytedance/GR-MG) | IL, RepL, Image Prediction, Text State Prediction, Partially labeled data, TP |
| [**GR-2: A Generative Video-Language-Action Model with Web-Scale Knowledge for Robot Manipulation**](https://arxiv.org/abs/2410.06158) | arXiv | 2024-10-08 | [Project](https://gr2-manipulation.github.io/) | IL, RepL, Image Prediction, TP |
| [**VLMPC: Vision-Language Model Predictive Control for Robotic Manipulation**](https://arxiv.org/abs/2407.09829) | RSS 2024 | 2024-07-13 | ![Star](https://img.shields.io/github/stars/PPjmchen/VLMPC?style=social&label=Star) [Github](https://github.com/PPjmchen/VLMPC) | IL, RepL, Video Prediction, MPC |
| [GR-1: **Unleashing Large-Scale Video Generative Pre-training for Visual Robot Manipulation**](https://arxiv.org/abs/2312.13139) | ICLR 2024 | 2023-12-20 | ![Star](https://img.shields.io/github/stars/bytedance/GR-1?style=social&label=Star) [Github](https://github.com/bytedance/GR-1) | IL, RepL, Image Prediction, TP |
| [SuSIE: **Zero-Shot Robotic Manipulation with Pretrained Image-Editing Diffusion Models**](https://arxiv.org/abs/2310.10639) | ICLR 2024 | 2023-10-16 | ![Star](https://img.shields.io/github/stars/kvablack/susie?style=social&label=Star) [Github](https://github.com/kvablack/susie) |  |
| [VLP: **Video Language Planning**](https://arxiv.org/abs/2310.10625) | ICLR 2024 | 2023-10-16 | [Github](https://github.com/video-language-planning/vlp_code) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.2 - Visual Imitation Learning ******* -->
### Visual Imitation Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Look, Focus, Act: Efficient and Robust Robot Learning via Human Gaze and Foveated Vision Transformers**](https://arxiv.org/abs/2507.15833) | arXiv | 2025-07-21 | ![Star](https://img.shields.io/github/stars/ian-chuang/gaze-av-aloha?style=social&label=Star) [Github](https://github.com/ian-chuang/gaze-av-aloha) |  |
| [**Behavioral Exploration: Learning to Explore via In-Context Adaptation**](https://arxiv.org/abs/2507.09041) | arXiv | 2025-07-11 | - |  |
| [**Is an object-centric representation beneficial for robotic manipulation ?**](https://arxiv.org/abs/2506.19408) | arXiv | 2025-06-24 | - |  |
| [**Robust Instant Policy: Leveraging Student's t-Regression Model for Robust In-context Imitation Learning of Robot Manipulation**](https://arxiv.org/abs/2506.15157) | arXiv | 2025-06-18 | [Project](https://sites.google.com/view/robustinstantpolicy) |  |
| [**SAIL: Faster-than-Demonstration Execution of Imitation Learning Policies**](https://arxiv.org/abs/2506.11948) | arXiv | 2025-06-13 | [Project](https://demospeedup.github.io/) |  |
| [**DemoSpeedup: Accelerating Visuomotor Policies via Entropy-Guided Demonstration Acceleration**](https://arxiv.org/abs/2506.05064) | arXiv | 2025-06-05 | [Project](https://demospeedup.github.io/) |  |
| [**SEM: Enhancing Spatial Understanding for Robust Robot Manipulation**](https://arxiv.org/abs/2505.16196) | arXiv | 2025-05-22 | - |  |
| [**H2R: A Human-to-Robot Data Augmentation for Robot Pre-training from Videos**](https://arxiv.org/abs/2505.11920) | arXiv | 2025-05-17 | - |  |
| [**L2D2: Robot Learning from 2D Drawings**](https://arxiv.org/abs/2505.12072) | arXiv | 2025-05-17 | [Project](https://collab.me.vt.edu/L2D2/) |  |
| [**Exploring Pose-Guided Imitation Learning for Robotic Precise Insertion**](https://arxiv.org/abs/2505.09424) | arXiv | 2025-05-14 | ![Star](https://img.shields.io/github/stars/sunhan1997/PoseInsert?style=social&label=Star) [Github](https://github.com/sunhan1997/PoseInsert) |  |
| [**Augmented Reality for RObots (ARRO): Pointing Visuomotor Policies Towards Visual Robustness**](https://arxiv.org/abs/2505.08627) | arXiv | 2025-05-13 | [Project](https://augmented-reality-for-robots.github.io/) |  |
| [**RoboGround: Robotic Manipulation with Grounded Vision-Language Priors**](https://arxiv.org/abs/2504.21530) | CVPR 2025 | 2025-04-30 | ![Star](https://img.shields.io/github/stars/ZzZZCHS/RoboGround?style=social&label=Star) [Github](https://github.com/ZzZZCHS/RoboGround) |  |
| [**CIVIL: Causal and Intuitive Visual Imitation Learning**](https://arxiv.org/abs/2504.17959) | arXiv | 2025-04-22 | [Project](https://civil2025.github.io/) |  |
| [**SPECI: Skill Prompts based Hierarchical Continual Imitation Learning for Robot Manipulation**](https://arxiv.org/abs/2504.15561) | arXiv | 2025-04-22 | - |  |
| [**Bi-LAT: Bilateral Control-Based Imitation Learning via Natural Language and Action Chunking with Transformers**](https://arxiv.org/abs/2504.01301) | arXiv | 2025-04-02 | [Project](https://mertcookimg.github.io/bi-lat/) |  |
| [**X-IL: Exploring the Design Space of Imitation Learning Policies**](https://arxiv.org/abs/2502.12330) | arXiv | 2025-02-17 | ![Star](https://img.shields.io/github/stars/ALRhub/X_IL?style=social&label=Star) [Github](https://github.com/ALRhub/X_IL) |  |
| [**Imit Diff: Semantics Guided Diffusion Transformer with Dual Resolution Fusion for Imitation Learning**](https://arxiv.org/abs/2502.09649) | arXiv | 2025-02-11 | - |  |
| [**Rethinking Latent Redundancy in Behavior Cloning: An Information Bottleneck Approach for Robot Manipulation**](https://arxiv.org/abs/2502.02853) | ICML 2025 | 2025-02-05 | ![Star](https://img.shields.io/github/stars/BaiShuanghao/BC-IB?style=social&label=Star) [Github](https://github.com/BaiShuanghao/BC-IB) |  |
| [CLOVER: **Closed-Loop Visuomotor Control with Generative Expectation for Robotic Manipulation**](https://arxiv.org/abs/2409.09016) | NeurIPS 2024 | 2024-09-13 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/CLOVER?style=social&label=Star) [Github](https://github.com/OpenDriveLab/CLOVER) | |
| [MS-Bot: **Play to the Score: Stage-Guided Dynamic Multi-Sensory Fusion for Robotic Manipulation**](https://arxiv.org/abs/2408.01366) | CoRL 2024 | 2024-08-02 | ![Star](https://img.shields.io/github/stars/GeWu-Lab/MS-Bot?style=social&label=Star) [Github](https://github.com/GeWu-Lab/MS-Bot) | IL, RepL, Multimodal, Poliy Head |
| [**Theia: Distilling Diverse Vision Foundation Models for Robot Learning**](https://arxiv.org/abs/2407.20179) | CoRL 2024 | 2024-07-29 | ![Star](https://img.shields.io/github/stars/bdaiinstitute/theia?style=social&label=Star) [Github](https://github.com/bdaiinstitute/theia) | IL, RepL, KD in VLMs, Poliy Head |
| [**BAKU: An Efficient Transformer for Multi-Task Policy Learning**](https://arxiv.org/abs/2406.07539) | NeurIPS 2024 | 2024-06-11 | ![Star](https://img.shields.io/github/stars/siddhanthaldar/BAKU?style=social&label=Star) [Github](https://github.com/siddhanthaldar/BAKU) |  |
| [**MUTEX: Learning Unified Policies from Multimodal Task Specifications**](https://arxiv.org/abs/2309.14320) | CoRL 2023 | 2023-09-25 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/mutex?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/mutex) | IL, RepL, Multimodal, E-D, Masked Construction, TP |
| [**LIV: Language-Image Representations and Rewards for Robotic Control**](https://arxiv.org/abs/2306.00958) | ICML 2023 | 2023-06-01 | ![Star](https://img.shields.io/github/stars/penn-pal-lab/LIV?style=social&label=Star) [Github](https://github.com/penn-pal-lab/LIV) | RepL, LfD, Both Goals, Alignment |
| [**VIMA: General Robot Manipulation with Multimodal Prompts**](https://arxiv.org/abs/2210.03094) | ICML 2023 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/vimalabs/VIMA?style=social&label=Star) [Github](https://github.com/vimalabs/VIMA) | Benchmark, E-D, TP, Multimodal Prompt |
| [ACT: **Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware**](https://arxiv.org/abs/2304.13705) | RSS 2023 | 2023-04-23 | ![Star](https://img.shields.io/github/stars/tonyzhaozh/aloha?style=social&label=Star) [Github](https://github.com/tonyzhaozh/aloha) | IL, RepL, E-D, TP |
| [ZeST: **Can Foundation Models Perform Zero-Shot Task Specification For Robot Manipulation?**](https://arxiv.org/abs/2204.11134) | L4DC 2022 | 2022-04-23 | [Project](https://sites.google.com/view/zestproject) | Both Goals |
| [**Coarse-to-Fine Imitation Learning: Robot Manipulation from a Single Demonstration**](https://arxiv.org/abs/2105.06411) | ICRAS 2021 | 2021-05-13 | [Project](https://www.robot-learning.uk/coarse-to-fine-imitation-learning) |  |
| [**Deep Imitation Learning for Bimanual Robotic Manipulation**](https://arxiv.org/abs/2010.05134) | NeurIPS 2020 | 2020-10-11 | ![Star](https://img.shields.io/github/stars/Rose-STL-Lab/HDR-IL?style=social&label=Star) [Github](https://github.com/Rose-STL-Lab/HDR-IL) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.3 - Learning from Human Demonstrations ******* -->
### Learning from Demonstrations
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Token Bottleneck: One Token to Remember Dynamics**](https://arxiv.org/abs/2507.06543) | arXiv | 2025-07-09 | ![Star](https://img.shields.io/github/stars/naver-ai/tobo?style=social&label=Star) [Github](https://github.com/naver-ai/tobo) | |
| [**Vision in Action: Learning Active Perception from Human Demonstrations**](https://arxiv.org/abs/2506.15666) | arXiv | 2025-06-18 | ![Star](https://img.shields.io/github/stars/haoyu-x/vision-in-action?style=social&label=Star) [Github](https://github.com/haoyu-x/vision-in-action) | |
| [**Learning Generalizable Robot Policy with Human Demonstration Video as a Prompt**](https://arxiv.org/abs/2505.20795) | arXiv | 2025-05-27 | - |  |
| [MCR: **Robots Pre-train Robots: Manipulation-Centric Robotic Representation from Large-Scale Robot Datasets**](https://arxiv.org/abs/2410.22325) | ICLR 2025 | 2024-10-29 | ![Star](https://img.shields.io/github/stars/luccachiang/robots-pretrain-robots?style=social&label=Star) [Github](https://github.com/luccachiang/robots-pretrain-robots) | IL, RepL, Alignment, Poliy Head |
| [MPI: **Learning Manipulation by Predicting Interaction**](https://www.arxiv.org/abs/2406.00439) | RSS 2024 | 2024-06-01 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/MPI?style=social&label=Star) [Github](https://github.com/OpenDriveLab/MPI) | IL, RepL, Interaction-oriented Prediction, Both Goals, Poliy Head |
| [VC-1: **Where are we in the search for an Artificial Visual Cortex for Embodied Intelligence?**](https://arxiv.org/abs/2303.18240) | NeurIPS 2023 | 2023-03-31 | ![Star](https://img.shields.io/github/stars/facebookresearch/eai-vc?style=social&label=Star)  [Github](https://github.com/facebookresearch/eai-vc) | |
| [Voltron: **Language-Driven Representation Learning for Robotics**](https://arxiv.org/abs/2302.12766) | RSS 2023 | 2023-02-24 | ![Star](https://img.shields.io/github/stars/siddk/voltron-robotics?style=social&label=Star) [Github](https://github.com/siddk/voltron-robotics) | IL, RepL, Masked Construction, Both Goals, Poliy Head |
| [MVP: **Real-World Robot Learning with Masked Visual Pre-training**](https://arxiv.org/abs/2210.03109) | CoRL 2023 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/ir413/mvp?style=social&label=Star) [Github](https://github.com/ir413/mvp) | IL, RepL, Masked Construction, Image Goal, Poliy Head |
| [**VIP: Towards Universal Visual Reward and Representation via Value-Implicit Pre-Training**](https://arxiv.org/abs/2210.00030) | ICLR 2023 | 2022-08-30 | ![Star](https://img.shields.io/github/stars/facebookresearch/vip?style=social&label=Star) [Github](https://github.com/facebookresearch/vip) | RepL, LfD, Image Goal |
| [**R3M: A Universal Visual Representation for Robot Manipulation**](https://arxiv.org/abs/2203.12601) | CoRL 2022 | 2022-03-23 | ![Star](https://img.shields.io/github/stars/facebookresearch/r3m?style=social&label=Star) [Github](https://github.com/facebookresearch/r3m) | IL, RepL, LfD, Alignment, Language Goal, Poliy Head |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.4 - Latent Action Learning ******* -->
### Latent Action Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Latent Action Diffusion for Cross-Embodiment Manipulation**](https://arxiv.org/abs/2506.14608) | arXiv | 2025-06-17 | [Project](https://mimicrobotics.github.io/lad/) | |
| [**STAR: Learning Diverse Robot Skill Abstractions through Rotation-Augmented Vector Quantization**](https://arxiv.org/abs/2506.03863) | ICML 2025 | 2025-06-04 | ![Star](https://img.shields.io/github/stars/JiuTian-VL/STAR?style=social&label=Star) [Github](https://github.com/JiuTian-VL/STAR) | |
| [**CoMo: Learning Continuous Latent Motion from Internet Videos for Scalable Robot Learning**](https://arxiv.org/abs/2505.17006) | arXiv | 2025-05-22 | ![Star](https://img.shields.io/github/stars/clamrobot/clam?style=social&label=Star) [Github](https://github.com/clamrobot/clam) | |
| [**FLARE: Robot Learning with Implicit World Modeling**](https://arxiv.org/abs/2505.15659) | arXiv | 2025-05-21 | [Project](https://research.nvidia.com/labs/gear/flare) | |
| [**DreamGen: Unlocking Generalization in Robot Learning through Neural Trajectories**](https://arxiv.org/abs/2505.12705) | arXiv | 2025-05-19 | [Project](https://research.nvidia.com/labs/gear/dreamgen/) | |
| [**CLAM: Continuous Latent Action Models for Robot Learning from Unlabeled Demonstrations**](https://arxiv.org/abs/2505.04999) | arXiv | 2025-05-08 | ![Star](https://img.shields.io/github/stars/clamrobot/clam?style=social&label=Star) [Github](https://github.com/clamrobot/clam) | |
| [**Moto: Latent Motion Token as the Bridging Language for Robot Manipulation**](https://arxiv.org/abs/2412.04445) | arXiv | 2024-12-05 | ![Star](https://img.shields.io/github/stars/TencentARC/Moto?style=social&label=Star) [Github](https://github.com/TencentARC/Moto) | |
| [**Discrete Policy: Learning Disentangled Action Space for Multi-Task Robotic Manipulation**](https://arxiv.org/abs/2409.18707) | ICRA 2025 | 2024-09-27 | [Project](https://discretepolicy.github.io/) | |
| [**IGOR: Image-GOal Representations Atomic Control Units for Foundation Models in Embodied AI**](https://www.microsoft.com/en-us/research/uploads/prod/2024/10/Project_IGOR_for_arXiv.pdf) | - | 2024 | [Project](https://www.microsoft.com/en-us/research/project/igor-image-goal-representations/) | IL, RepL, Image Prediction, Poliy Head |
| [LAPA: **Latent Action Pretraining from Videos**](https://arxiv.org/abs/2410.11758) | ICLR 2025 | 2024-10-15 | ![Star](https://img.shields.io/github/stars/LatentActionPretraining/LAPA?style=social&label=Star) [Github](https://github.com/LatentActionPretraining/LAPA) | IL, RepL, Alignment, Both Goals, Poliy Head |
| [GRIF: **Goal Representations for Instruction Following: A Semi-Supervised Language Interface to Control**](https://arxiv.org/abs/2307.00117) | CoRL 2023 | 2023-06-30 | ![Star](https://img.shields.io/github/stars/rail-berkeley/grif_release?style=social&label=Star)  [Github](https://github.com/rail-berkeley/grif_release) | IL, RepL, Alignment, Both Goals, Poliy Head, Partially labeled data |
| [**MimicPlay: Long-Horizon Imitation Learning by Watching Human Play**](https://arxiv.org/abs/2302.12422) | CoRL 2023 | 2023-02-24 | ![Star](https://img.shields.io/github/stars/j96w/MimicPlay?style=social&label=Star) [Github](https://github.com/j96w/MimicPlay) | IL, RepL, LfD, Image Goal, Poliy Head |
| [KOAP: **Imitation Learning with Limited Actions via Diffusion Planners and Deep Koopman Controllers**](https://arxiv.org/abs/2410.07584) | arXiv | 2024-10-24 | - | IL, RepL, Image Prediction, Koopman Operator |
| [**Behavior Generation with Latent Actions**](https://arxiv.org/abs/2403.03181) | ICML 2024 | 2024-03-05 | ![Star](https://img.shields.io/github/stars/jayLEE0301/vq_bet_official?style=social&label=Star) [Github](https://github.com/jayLEE0301/vq_bet_official) |  |
| [LAPO: **Learning to Act without Actions**](https://arxiv.org/abs/2312.10812) | ICLR 2024 | 2023-12-17 | ![Star](https://img.shields.io/github/stars/schmidtdominik/LAPO?style=social&label=Star) [Github](https://github.com/schmidtdominik/LAPO) | IL, RepL, Image Prediction, Latent Inverse Dynamics Model |
| [ILPO: **Imitating Latent Policies from Observation**](https://arxiv.org/abs/1805.07914) | ICML 2019 | 2018-05-21 | ![Star](https://img.shields.io/github/stars/ashedwards/ILPO?style=social&label=Star) [Github](https://github.com/ashedwards/ILPO) | IL, RepL, Latent Inverse Dynamics Model |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.5 - World Model ******* -->
### World Model
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   |  
|:--------|:--------:|:--------:|:--------:|
| [**World4Omni: A Zero-Shot Framework from Image Generation World Model to Robotic Manipulation**](https://arxiv.org/abs/2506.23919) | arXiv | 2025-06-30| [Project](https://world4omni.github.io/) | |
| [**ParticleFormer: A 3D Point Cloud World Model for Multi-Object, Multi-Material Robotic Manipulation**](https://arxiv.org/abs/2506.23126) | arXiv | 2025-06-29 | [Project](https://particleformer.github.io/) | |
| [**GAF: Gaussian Action Field as a Dvnamic World Model for Robotic Mlanipulation**](https://arxiv.org/abs/2506.14135) | arXiv | 2025-06-17 | - | |
| [**A Smooth Sea Never Made a Skilled SAILOR: Robust Imitation via Learning to Search**](https://arxiv.org/abs/2506.05294) | arXiv | 2025-06-05 | ![Star](https://img.shields.io/github/stars/arnavkj1995/SAILOR?style=social&label=Star) [Github](https://github.com/arnavkj1995/SAILOR) | |
| [**WoMAP: World Models For Embodied Open-Vocabulary Object Localization**](https://arxiv.org/abs/2506.01600) | arXiv | 2025-06-02 | [Project](https://robot-womap.github.io/) | |
| [**OSVI-WM: One-Shot Visual Imitation for Unseen Tasks using World-Model-Guided Trajectory Generation**](https://arxiv.org/abs/2505.20425) | arXiv | 2025-05-26 | - | |
| [**Vid2World: Crafting Video Diffusion Models to Interactive World Models**](https://arxiv.org/abs/2505.14357) | arXiv | 2025-05-20 | [Project](https://knightnemo.github.io/vid2world/) | |
| [**Modeling Unseen Environments with Language-guided Composable Causal Components in Reinforcement Learning**](https://arxiv.org/abs/2505.08361) | ICLR 2025 | 2025-05-13 | [Project](https://www.charonwangg.com/project/wm3c/) | |
| [**ManipDreamer: Boosting Robotic Manipulation World Model with Action Tree and Visual Guidance**](https://arxiv.org/abs/2504.16464) | arXiv | 2025-04-23 | - | |
| [**Unified World Models: Coupling Video and Action Diffusion for Pretraining on Large Robotic Datasets**](https://arxiv.org/abs/2504.02792) | arXiv | 2025-04-03 | ![Star](https://img.shields.io/github/stars/WEIRDLabUW/unified-world-model?style=social&label=Star) [Github](https://github.com/WEIRDLabUW/unified-world-model) | |
| [**Multi-Stage Manipulation with Demonstration-Augmented Reward, Policy, and World Model Learning**](https://arxiv.org/abs/2503.01837) | arXiv | 2025-03-03 | - | |
| [**Generalist World Model Pre-Training for Efficient Reinforcement Learning**](https://arxiv.org/abs/2502.19544) | arXiv | 2025-02-26 | - | |
| [**Learning View-invariant World Models for Visual Robotic Manipulation**](https://openreview.net/forum?id=vJwjWyt4Ed) | ICLR 2025 | 2025-01-23 | ![Star](https://img.shields.io/github/stars/lafmdp/ReViWo?style=social&label=Star) [Github](https://github.com/lafmdp/ReViWo) | |
| [**Cosmos World Foundation Model Platform for Physical AI**](https://arxiv.org/abs/2501.03575) | arXiv | 2025-01-07 | ![Star](https://img.shields.io/github/stars/NVIDIA/Cosmos?style=social&label=Star) [Github](https://github.com/NVIDIA/Cosmos) | |
| [Sirius-Fleet: **Multi-Task Interactive Robot Fleet Learning with Visual World Models**](https://arxiv.org/abs/2410.22689) | CoRL 2024 | 2024-10-30 | [Project](https://ut-austin-rpl.github.io/sirius-fleet/) | |
| [**MOTO: Offline Pre-training to Online Fine-tuning for Model-based Robot Learning**](https://arxiv.org/abs/2401.03306) | CoRL 2023 | 2024-01-06 | [Project](https://sites.google.com/view/mo2o) | |
| [FOWM: **Finetuning Offline World Models in the Real World**](https://arxiv.org/abs/2310.16029) | CoRL 2023 | 2023-10-24 | ![Star](https://img.shields.io/github/stars/fyhMer/fowm?style=social&label=Star) [Github](https://github.com/fyhMer/fowm) | |
| [SWIM: **Structured World Models from Human Videos**](https://arxiv.org/abs/2308.10901) | RSS 2023 | 2023-08-23 | [Project](https://human-world-model.github.io/) | |
| [**Surfer: Progressive Reasoning with World Models for Robotic Manipulation**](https://arxiv.org/abs/2306.11335) | arXiv | 2023-06-20 | ![Star](https://img.shields.io/github/stars/Necolizer/RM-PRT?style=social&label=Star) [Github](https://github.com/Necolizer/RM-PRT) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.6-Asynchronous Action Learning ******* -->
### Asynchronous Action Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**HiBerNAC: Hierarchical Brain-emulated Robotic Neural Agent Collective for Disentangling Complex Manipulation**](https://arxiv.org/abs/2506.08296) | arXiv | 2025-06-09 | - |  |
| [**Fast-in-Slow: A Dual-System Foundation Model Unifying Fast Manipulation within Slow Reasoning**](https://arxiv.org/abs/2506.01953) | arXiv | 2025-06-02 | ![Star](https://img.shields.io/github/stars/CHEN-H01/Fast-in-Slow?style=social&label=Star) [Github](https://github.com/CHEN-H01/Fast-in-Slow) |  |
| [**OpenHelix: A Short Survey, Empirical Analysis, and Open-Source Dual-System VLA Model for Robotic Manipulation**](https://arxiv.org/abs/2505.03912) | arXiv | 2025-05-06 | ![Star](https://img.shields.io/github/stars/OpenHelix-robot/OpenHelix?style=social&label=Star) [Github](https://github.com/OpenHelix-robot/OpenHelix) |  |
| [**PIVOT-R: Primitive-Driven Waypoint-Aware World Model for Robotic Manipulation**](https://arxiv.org/abs/2410.10394) | NeurIPS 2024 | 2024-10-14 | ![Star](https://img.shields.io/github/stars/abliao/PIVOT-R?style=social&label=Star) [Github](http://github.com/abliao/PIVOT-R) | IL, RepL, Image Prediction, Hierarchical, Poliy Head |
| [RoboDual: **Towards Synergistic, Generalized, and Efficient Dual-System for Robotic Manipulation**](https://arxiv.org/abs/2410.08001) | arXiv | 2024-10-10 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/RoboDual?style=social&label=Star) [Github](https://github.com/OpenDriveLab/RoboDual) |  |
| [**HiRT: Enhancing Robotic Control with Hierarchical Robot Transformers**](https://arxiv.org/abs/2410.05273) | CoRL 2024 | 2024-09-12 | - | IL, RepL, Hierarchical, Poliy Head |
| [LCB: **From LLMs to Actions: Latent Codes as Bridges in Hierarchical Robot Control**](https://arxiv.org/abs/2405.04798) | IROS 2024 | 2024-05-08 | [Project](https://fredshentu.github.io/LCB_site/) | |
| [**MResT: Multi-Resolution Sensing for Real-Time Control with Vision-Language Models**](https://arxiv.org/abs/2401.14502) | CoRL 2023 | 2024-01-25 | ![Star](https://img.shields.io/github/stars/iamlab-cmu/mrest-multi-resolution-transformer?style=social&label=Star) [Github](https://github.com/iamlab-cmu/mrest-multi-resolution-transformer) | IL, RepL, Multi-Resolution, Poliy Head |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.7-Diffusion Policy Learning ******* -->
### Diffusion Policy Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Spatial-Temporal Aware Visuomotor Diffusion Policy Learning**](https://arxiv.org/abs/2507.06710) | arXiv | 2025-07-09 | [Project](https://zhenyangliu.github.io/DP4/) | |
| [**Hybrid Diffusion Policies with Projective Geometric Algebra for Efficient Robot Manipulation Learning**](https://arxiv.org/abs/2507.05695) | arXiv | 2025-06-24 | - | |
| [**AnchorDP3: 3D Affordance Guided Sparse Diffusion Policy for Robotic Manipulation**](https://arxiv.org/abs/2506.19269) | CVPRW 2025 | 2025-06-24 | - | |
| [**Block-wise Adaptive Caching for Accelerating Diffusion Policy**](https://arxiv.org/abs/2506.13456) | arXiv | 2025-06-24 | - | |
| [**Canonical Policy: Learning Canonical 3D Representation for Equivariant Policy**](https://arxiv.org/abs/2505.18474) | arXiv | 2025-05-24 | [Project](https://zhangzhiyuanzhang.github.io/cp-website/) | |
| [**3D Equivariant Visuomotor Policy Learning via Spherical Projection**](https://arxiv.org/abs/2505.16969) | arXiv | 2025-05-22 | - | |
| [**Latent Theory of Mind: A Decentralized Diffusion Architecture for Cooperative Manipulation**](https://arxiv.org/abs/2505.09144) | arXiv | 2025-05-14 | [Project](https://stanfordmsl.github.io/LatentToM/) | |
| [**H<sup>3</sup>DP: Triply-Hierarchical Diffusion Policy for Visuomotor Learning**](https://arxiv.org/abs/2505.07819) | arXiv | 2025-05-12 | [Project](https://lyy-iiis.github.io/h3dp/) | |
| [**Demystifying Diffusion Policies: Action Memorization and Simple Lookup Table Alternatives**](https://arxiv.org/abs/2505.05787) | arXiv | 2025-05-09 |  [Project](https://stanfordmsl.github.io/alt/) | |
| [**Latent Diffusion Planning for Imitation Learning**](https://arxiv.org/abs/2504.16925) | arXiv | 2025-04-23 | ![Star](https://img.shields.io/github/stars/amberxie88/latent_diffusion_planning?style=social&label=Star) [Github](https://github.com/amberxie88/latent_diffusion_planning) | |
| [**Spatial-Temporal Graph Diffusion Policy with Kinematic Modeling for Bimanual Robotic Manipulation**](https://arxiv.org/abs/2503.10743) | CVPR 2025 | 2025-03-13 | - | |
| [**CodeDiffuser: Attention-Enhanced Diffusion Policy via VLM-Generated Code for Instruction Ambiguity**](https://arxiv.org/abs/2506.16652) | RSS 2025 | 2025-06-19 | ![Star](https://img.shields.io/github/stars/lyttttt3333/CodeDiffuser?style=social&label=Star) [Github](https://github.com/lyttttt3333/CodeDiffuser) | |
| [**Reactive Diffusion Policy: Slow-Fast Visual-Tactile Policy Learning for Contact-Rich Manipulation**](https://arxiv.org/abs/2503.02881) | RSS 2025 | 2025-03-04 | ![Star](https://img.shields.io/github/stars/xiaoxiaoxh/reactive_diffusion_policy?style=social&label=Star) [Github](https://github.com/xiaoxiaoxh/reactive_diffusion_policy) | |
| [**FRMD: Fast Robot Motion Diffusion with Consistency-Distilled Movement Primitives for Smooth Action Generation**](https://arxiv.org/abs/2503.02048) | arXiv | 2025-03-03 | - | |
| [**S<sup>2</sup>-Diffusion: Generalizing from Instance-level to Category-level Skills in Robot Manipulation**](https://arxiv.org/abs/2502.09389) | arXiv | 2025-02-13 | - | |
| [MoDE: **Efficient Diffusion Transformer Policies with Mixture of Expert Denoisers for Multitask Learning**](https://arxiv.org/abs/2412.12953) | ICLR 2025 | 2024-12-17 | ![Star](https://img.shields.io/github/stars/intuitive-robots/MoDE_Diffusion_Policy?style=social&label=Star) [Github](https://github.com/intuitive-robots/MoDE_Diffusion_Policy) | |
| [**Score and Distribution Matching Policy: Advanced Accelerated Visuomotor Policies via Matched Distillation**](https://arxiv.org/abs/2412.09265?) | arXiv | 2024-12-12 | ![Star](https://img.shields.io/github/stars/BofangJia/SDM-Policy?style=social&label=Star) [Github](https://github.com/BofangJia/SDM-Policy) | |
| [**AffordDP: Generalizable Diffusion Policy with Transferable Affordance**](https://arxiv.org/abs/2412.03142) | arXiv | 2024-12-04 | [Project](https://afforddp.github.io/) | |
| [**Instant Policy: In-Context Imitation Learning via Graph Diffusion**](https://arxiv.org/abs/2411.12633) | ICLR 2025 | 2024-11-19 | ![Star](https://img.shields.io/github/stars/vv19/instant_policy?style=social&label=Star) [Github](https://github.com/vv19/instant_policy) | |
| [STMDP: **Brain-inspired Action Generation with Spiking Transformer Diffusion Policy Model**](https://arxiv.org/abs/2411.09953) | arXiv | 2024-11-15 | - | |
| [MBA: **Motion Before Action: Diffusing Object Motion as Manipulation Condition**](https://arxiv.org/abs/2411.09658) | arXiv | 2024-11-14 | ![Star](https://img.shields.io/github/stars/Selen-Suyue/MBA?style=social&label=Star) [Github](https://github.com/Selen-Suyue/MBA) | |
| [DiT Policy: **Diffusion Transformer Policy**](https://arxiv.org/abs/2410.15959) | arXiv | 2024-10-21 | - | |
| [**CAGE: Causal Attention Enables Data-Efficient Generalizable Robotic Manipulation**](https://arxiv.org/abs/2410.14974) | arXiv | 2024-10-19 | ![Star](https://img.shields.io/github/stars/cage-policy/CAGE?style=social&label=Star) [Github](https://github.com/cage-policy/CAGE) | |
| [**RDT-1B: a Diffusion Foundation Model for Bimanual Manipulation**](https://arxiv.org/abs/2410.07864) | ICLR 2025 | 2024-10-10 | ![Star](https://img.shields.io/github/stars/thu-ml/RoboticsDiffusionTransformer?style=social&label=Star) [Github](https://github.com/thu-ml/RoboticsDiffusionTransformer) | |
| [ScaleDP: **Scaling Diffusion Policy in Transformer to 1 Billion Parameters for Robotic Manipulation**](https://arxiv.org/abs/2409.14411) | ICRA 2025 | 2024-09-22 | [Project](https://scaling-diffusion-policy.github.io/) | |
| [**SDP: Spiking Diffusion Policy for Robotic Manipulation with Learnable Channel-Wise Membrane Thresholds**](https://arxiv.org/abs/2409.11195) | arXiv | 2024-09-17 | - | |
| [DiT-Block Policy: **The Ingredients for Robotic Diffusion Transformers**](https://arxiv.org/abs/2410.10088) | arXiv | 2024-10-14 | ![Star](https://img.shields.io/github/stars/sudeepdasari/dit-policy?style=social&label=Star) [Github](https://github.com/sudeepdasari/dit-policy) | |
| [**GenDP: 3D Semantic Fields for Category-Level Generalizable Diffusion Policy**](https://arxiv.org/abs/2410.17488) | CoRL 2024 | 2024-10-23 | ![Star](https://img.shields.io/github/stars/WangYixuan12/gendp?style=social&label=Star) [Github](https://github.com/WangYixuan12/gendp) |  |
| [**EquiBot: SIM(3)-Equivariant Diffusion Policy for Generalizable and Data Efficient Learning**](https://arxiv.org/abs/2407.01479) | CoRL 2024 | 2024-07-01 | ![Star](https://img.shields.io/github/stars/yjy0625/equibot?style=social&label=Star) [Github](https://github.com/yjy0625/equibot) |  |
| [SDP: **Sparse Diffusion Policy: A Sparse, Reusable, and Flexible Policy for Robot Learning**](https://arxiv.org/abs/2407.01531) | CoRL 2024 | 2024-07-01 | ![Star](https://img.shields.io/github/stars/AnthonyHuo/SDP?style=social&label=Star) [Github](https://github.com/AnthonyHuo/SDP) | MoE |
| [**ManiCM: Real-time 3D Diffusion Policy via Consistency Model for Robotic Manipulation**](https://arxiv.org/abs/2406.01586) | arXiv | 2024-06-03 | ![Star](https://img.shields.io/github/stars/ManiCM-fast/ManiCM?style=social&label=Star) [Github](https://github.com/ManiCM-fast/ManiCM) |  |
| [**RISE: 3D Perception Makes Real-World Robot Imitation Simple and Effective**](https://arxiv.org/abs/2404.12281) | IROS 2024 | 2024-04-18 | ![Star](https://img.shields.io/github/stars/rise-policy/rise?style=social&label=Star) [Project](https://github.com/rise-policy/rise) | |
| [MDT: **Multimodal Diffusion Transformer: Learning Versatile Behavior from Multimodal Goals**](https://arxiv.org/abs/2407.05996) | RSS 2024 | 2024-07-08 | ![Star](https://img.shields.io/github/stars/intuitive-robots/mdt_policy?style=social&label=Star) [Github](https://github.com/intuitive-robots/mdt_policy) | IL, RepL, Masked Construction, DP, Partially labeled data |
| [R&D: **Render and Diffuse: Aligning Image and Action Spaces for Diffusion-based Behaviour Cloning**](https://arxiv.org/abs/2405.18196) | RSS 2024 | 2024-05-28 | ![Star](https://img.shields.io/github/stars/vv19/rendiff?style=social&label=Star) [Github](https://github.com/vv19/rendiff) | |
| [DP3: **3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations**](https://arxiv.org/abs/2403.03954) | RSS 2024 | 2024-03-06 | ![Star](https://img.shields.io/github/stars/YanjieZe/3D-Diffusion-Policy?style=social&label=Star) [Github](https://github.com/YanjieZe/3D-Diffusion-Policy) |  |
| [**PlayFusion: Skill Acquisition via Diffusion from Language-Annotated Play**](https://arxiv.org/abs/2312.04549) | CoRL 2023 | 2023-12-07 | [Project](https://play-fusion.github.io/) |  |
| [EquiDiff: **Equivariant Diffusion Policy**](https://arxiv.org/abs/2407.01812) | CoRL 2024 | 2024-07-01 | ![Star](https://img.shields.io/github/stars/pointW/equidiff?style=social&label=Star) [Code](https://github.com/pointW/equidiff) | Equivariance |
| [**StructDiffusion: Language-Guided Creation of Physically-Valid Structures using Unseen Objects**](https://arxiv.org/abs/2211.04604) | RSS 2023 | 2022-11-08 | ![Star](https://img.shields.io/github/stars/StructDiffusion/StructDiffusion?style=social&label=Star) [Github](https://github.com/StructDiffusion/StructDiffusion) |  |
| [BESO: **Goal-Conditioned Imitation Learning using Score-based Diffusion Policies**](https://arxiv.org/abs/2304.02532) | RSS 2023 | 2023-04-05 | ![Star](https://img.shields.io/github/stars/intuitive-robots/beso?style=social&label=Star) [Github](https://github.com/intuitive-robots/beso) |  |
| [**Diffusion Policy: Visuomotor Policy Learning via Action Diffusion**](https://arxiv.org/abs/2303.04137) | RSS 2023 | 2023-03-07 | ![Star](https://img.shields.io/github/stars/real-stanford/diffusion_policy?style=social&label=Star) [Github](https://github.com/real-stanford/diffusion_policy) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.8-Other Policies ******* -->
### Other Policies
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**MP1: Mean Flow Tames Policy Learning in 1-step for Robotic Manipulation**](https://arxiv.org/abs/2507.10543) | arXiv | 2025-07-14 | ![Star](https://img.shields.io/github/stars/LogSSim/MP1?style=social&label=Star) [Github](https://github.com/LogSSim/MP1) | |
| [**Reinforcement Learning with Action Chunking**](https://arxiv.org/abs/2507.07969) | arXiv | 2025-07-10 | ![Star](https://img.shields.io/github/stars/ColinQiyangLi/qc?style=social&label=Star) [Github](https://github.com/ColinQiyangLi/qc) | |
| [**Wavelet Policy: Lifting Scheme for Policy Learning in Long-Horizon Tasks**](https://arxiv.org/abs/2507.04331) | arXiv | 2025-07-06 | - | |
| [**Chain-of-Action: Trajectory Autoregressive Modeling for Robotic Manipulation**](https://arxiv.org/abs/2506.09990) | arXiv | 2025-06-11 | ![Star](https://img.shields.io/github/stars/zwbx/Chain-of-Action?style=social&label=Star) [Github](https://github.com/zwbx/Chain-of-Action) | |
| [**FreqPolicy: Efficient Flow-based Visuomotor Policy via Frequency Consistency**](https://arxiv.org/abs/2506.08822) | arXiv | 2025-06-10 | - | |
| [**Real-Time Execution of Action Chunking Flow Policies**](https://arxiv.org/abs/2506.07339) | arXiv | 2025-06-09 | [Project](https://www.pi.website/research/real_time_chunking) | |
| [**Rodrigues Network for Learning Robot Actions**](https://arxiv.org/abs/2506.02618) | arXiv | 2025-06-03 | - | |
| [**FreqPolicy: Frequency Autoregressive Visuomotor Policy with Continuous Tokens**](https://arxiv.org/abs/2506.01583) | arXiv | 2025-06-02 | - | |
| [**Streaming Flow Policy: Simplifying diffusionflow-matching policies by treating action trajectories as flow trajectories**](https://arxiv.org/abs/2505.21851) | arXiv | 2025-05-28 | [Project](https://siddancha.github.io/streaming-flow-policy/) | |
| [**Dense Policy: Bidirectional Autoregressive Learning of Actions**](https://arxiv.org/abs/2503.13217) | arXiv | 2025-03-17 | ![Star](https://img.shields.io/github/stars/Selen-Suyue/DensePolicy?style=social&label=Star) [Github](https://github.com/Selen-Suyue/DensePolicy) | |
| [**RoboBERT: An End-to-end Multimodal Robotic Manipulation Model**](https://arxiv.org/abs/2502.07837) | arXiv | 2025-02-11 | ![Star](https://img.shields.io/github/stars/PeterWangsicheng/RoboBERT?style=social&label=Star) [Github](https://github.com/PeterWangsicheng/RoboBERT) | |
| [**EnerVerse: Envisioning Embodied Future Space for Robotics Manipulation**](https://arxiv.org/abs/2501.01895) | arXiv | 2025-01-03 | [Project](https://sites.google.com/view/enerverse) | |
| [**CARP: Visuomotor Policy Learning via Coarse-to-Fine Autoregressive Prediction**](https://arxiv.org/abs/2412.06782) | arXiv | 2024-12-09 | ![Star](https://img.shields.io/github/stars/ZhefeiGong/carp?style=social&label=Star) [Github](https://github.com/ZhefeiGong/carp) | |
| [**FlowPolicy: Enabling Fast and Robust 3D Flow-based Policy via Consistency Flow Matching for Robot Manipulation**](https://arxiv.org/abs/2412.04987) | AAAI 2025 | 2024-12-06 | ![Star](https://img.shields.io/github/stars/zql-kk/FlowPolicy?style=social&label=Star) [Github](https://github.com/zql-kk/FlowPolicy) | |
| [**Autoregressive Action Sequence Learning for Robotic Manipulation**](https://arxiv.org/abs/2410.03132) | arXiv | 2024-10-04 | ![Star](https://img.shields.io/github/stars/mlzxy/arp?style=social&label=Star) [Github](https://github.com/mlzxy/arp) | |
| [**MaIL: Improving Imitation Learning with Selective State Space Models**](https://arxiv.org/abs/2406.08234) | CoRL 2024 | 2024-06-12 | ![Star](https://img.shields.io/github/stars/ALRhub/MaIL?style=social&label=Star) [Github](https://github.com/ALRhub/MaIL) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.9-Vision Language Action Models ******* -->
### Vision Language Action Models
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Confidence Calibration in Vision-Language-Action Models**](https://arxiv.org/abs/2507.17383) | arXiv | 2025-07-23 | - | |
| [**VLA-Touch: Enhancing Vision-Language-Action Models with Dual-Level Tactile Feedback**](https://arxiv.org/abs/2507.17294) | arXiv | 2025-07-23 | ![Star](https://img.shields.io/github/stars/jxbi1010/VLA-Touch?style=social&label=Star) [Github](https://github.com/jxbi1010/VLA-Touch) | |
| [**Evaluating Uncertainty and Quality of Visual Language Action-enabled Robots**](https://arxiv.org/abs/2507.17049) | arXiv | 2025-07-22 | - | |
| [**ThinkAct: Vision-Language-Action Reasoning via Reinforced Visual Latent Planning**](https://arxiv.org/abs/2507.16815) | arXiv | 2025-07-22 | [Project](https://jasper0314-huang.github.io/thinkact-vla/) | |
| [**GR-3 Technical Report**](https://arxiv.org/abs/2507.15493) | arXiv | 2025-07-18 | [Project](https://seed.bytedance.com/zh/GR3) | |
| [**EdgeVLA: Efficient Vision-Language-Action Models**](https://arxiv.org/abs/2507.14049) | arXiv | 2025-07-18 | - | |
| [**EgoVLA: Learning Vision-Language-Action Models from Egocentric Human Videos**](https://arxiv.org/abs/2507.12440) | arXiv | 2025-07-16 | [Project](https://rchalyang.github.io/EgoVLA/) | |
| [**DreamVLA: A Vision-Language-Action Model Dreamed with Comprehensive World Knowledge**](https://arxiv.org/abs/2507.04447) | arXiv | 2025-07-13 | ![Star](https://img.shields.io/github/stars/Zhangwenyao1/DreamVLA?style=social&label=Star) [Github](https://github.com/Zhangwenyao1/DreamVLA) | |
| [**Tactile-VLA: Unlocking Vision-Language-Action Model's Physical Knowledge for Tactile Generalization**](https://arxiv.org/abs/2507.09160) | arXiv | 2025-07-12 | - | |
| [**VOTE: Vision-Language-Action Optimization with Trajectory Ensemble Voting**](https://arxiv.org/abs/2507.05116) | arXiv | 2025-07-07 | ![Star](https://img.shields.io/github/stars/LukeLIN-web/VOTE?style=social&label=Star) [Github](https://github.com/LukeLIN-web/VOTE) | |` 
| [**cVLA: Towards Efficient Camera-Space VLAs**](https://arxiv.org/abs/2507.02190) | arXiv | 2025-07-02 | - | |
| [**MoIRA: Modular Instruction Routing Architecture for Multi-Task Robotics**](https://arxiv.org/abs/2507.01843) | arXiv | 2025-07-02 | - | |
| [**TriVLA: A Unified Triple-System-Based Unified Vision-Language-Action Model for General Robot Control**](https://arxiv.org/abs/2507.01424) | arXiv | 2025-07-01 | [Project](https://zhenyangliu.github.io/TriVLA/) | |
| [**VQ-VLA: Improving Vision-Language-Action Models via Scaling Vector-Quantized Action Tokenizers**](https://arxiv.org/abs/2507.01016) | ICCV 2025 | 2025-07-01 | ![Star](https://img.shields.io/github/stars/xiaoxiao0406/VQ-VLA?style=social&label=Star) [Github](https://github.com/xiaoxiao0406/VQ-VLA) | |
| [**CronusVLA: Transferring Latent Motion Across Time for Multi-Frame Prediction in Manipulation**](https://arxiv.org/abs/2506.19816) | arXiv | 2025-06-24 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/CronusVLA?style=social&label=Star) [Github](https://github.com/OpenRobotLab/CronusVLA) | |
| [UniVLA: **Unified Vision-Language-Action Model**](https://arxiv.org/abs/2506.19850) | arXiv | 2025-06-24 | ![Star](https://img.shields.io/github/stars/baaivision/UniVLA?style=social&label=Star) [Github](https://github.com/baaivision/UniVLA) | |
| [**RoboMonkey: Scaling Test-Time Sampling and Verification for Vision-Language-Action Models**](https://arxiv.org/abs/2506.17811) | arXiv | 2025-06-21 | [Project](https://robomonkey-vla.github.io/) | |
| [**RLRC: Reinforcement Learning-based Recovery for Compressed Vision-Language-Action Models**](https://arxiv.org/abs/2506.17639) | arXiv | 2025-06-21 | [Project](https://rlrc-vla.github.io/) | |
| [**VLA-OS: Structuring and Dissecting Planning Representations and Paradigms in Vision-Language-Action Models**](https://arxiv.org/abs/2506.17561) | arXiv | 2025-06-21 | ![Star](https://img.shields.io/github/stars/HeegerGao/VLA-OS?style=social&label=Star) [Github](https://github.com/HeegerGao/VLA-OS) | |
| [**ControlVLA: Few-shot Object-centric Adaptation for Pre-trained Vision-Language-Action Models**](https://arxiv.org/abs/2506.16211) | arXiv | 2025-06-19 | ![Star](https://img.shields.io/github/stars/ControlVLA/ControlVLA?style=social&label=Star) [Github](https://github.com/ControlVLA/ControlVLA) | |
| [**CEED-VLA: Consistency Vision-Language-Action Model with Early-Exit Decoding**](https://arxiv.org/abs/2506.13725) | arXiv | 2025-06-16 | ![Star](https://img.shields.io/github/stars/OpenHelix-Team/CEED-VLA?style=social&label=Star) [Github](https://github.com/OpenHelix-Team/CEED-VLA) | |
| [**SP-VLA: A Joint Model Scheduling and Token Pruning Approach for VLA Model Acceleration**](https://arxiv.org/abs/2506.12723) | arXiv | 2025-06-15 | - | |
| [**RationalVLA: A Rational Vision-Language-Action Model with Dual System**](https://arxiv.org/abs/2506.10826) | arXiv | 2025-06-12 | [Project](https://irpn-eai.github.io/rational_vla) | |
| [**EfficientVLA: Training-Free Acceleration and Compression for Vision-Language-Action Models**](https://arxiv.org/abs/2506.10100) | arXiv | 2025-06-11 | - | |
| [**SAFE: Multitask Failure Detection for Vision-Language-Action Models**](https://arxiv.org/abs/2506.09937) | arXiv | 2025-06-11 | [Project](https://vla-safe.github.io/) | |
| [**TGRPO :Fine-tuning Vision-Language-Action Model via Trajectory-wise Group Relative Policy Optimization**](https://arxiv.org/abs/2506.08440) | arXiv | 2025-06-10 | ![Star](https://img.shields.io/github/stars/hahans/TGRPO?style=social&label=Star) [Github](https://github.com/hahans/TGRPO) | |
| [**BridgeVLA: Input-Output Alignment for Efficient 3D Manipulation Learning with Vision-Language Models**](https://arxiv.org/abs/2506.07961) | arXiv | 2025-06-09 | ![Star](https://img.shields.io/github/stars/BridgeVLA/BridgeVLA?style=social&label=Star) [Github](https://github.com/BridgeVLA/BridgeVLA) | |
| [**BitVLA: 1-bit Vision-Language-Action Models for Robotics Manipulation**](https://arxiv.org/abs/2506.07530) | arXiv | 2025-06-09 | ![Star](https://img.shields.io/github/stars/ustcwhy/BitVLA?style=social&label=Star) [Github](https://github.com/ustcwhy/BitVLA) | |
| [**BEAST: Efficient Tokenization of B-Splines Encoded Action Sequences for Imitation Learning**](https://arxiv.org/abs/2506.06072) | arXiv | 2025-06-06 | ![Star](https://img.shields.io/github/stars/intuitive-robots/beast_calvin?style=social&label=Star) [Github](https://github.com/intuitive-robots/beast_calvin) | |
| [**SwitchVLA: Execution-Aware Task Switching for Vision-Language-Action Models**](https://arxiv.org/abs/2506.03574) | arXiv | 2025-06-04 | [Project](https://switchvla.github.io/) | |
| [**SmolVLA: A Vision-Language-Action Model  for Affordable and Efficient Robotics**](https://arxiv.org/abs/2506.01844) | arXiv | 2025-06-02 | ![Star](https://img.shields.io/github/stars/huggingface/lerobot?style=social&label=Star) [Github](https://github.com/huggingface/lerobot) | |
| [**OG-VLA: 3D-Aware Vision Language Action Model via Orthographic Image Generation**](https://arxiv.org/abs/2506.01196) | arXiv | 2025-06-01 | [Project](https://og-vla.github.io/) | |
| [**LoHoVLA: A Unified Vision-Language-Action Model for Long-Horizon Embodied Tasks**](https://arxiv.org/abs/2505.23705) | arXiv | 2025-05-29 | [Project](https://www.pi.website/research/knowledge_insulation) | |
| [**Knowledge Insulating Vision-Language-Action Models: Train Fast, Run Fast, Generalize Better**](https://arxiv.org/abs/2505.23705) | arXiv | 2025-05-29 | [Project](https://www.pi.website/research/knowledge_insulation) | |
| [**Agentic Robot: A Brain-Inspired Framework for Vision-Language-Action Models in Embodied Agents**](https://arxiv.org/abs/2505.23450) | arXiv | 2025-05-29 | - | |
| [**ForceVLA: Enhancing VLA Models with a Force-aware MoE for Contact-rich Manipulation**](https://arxiv.org/abs/2505.22159) | arXiv | 2025-05-28 | [Project](https://sites.google.com/view/forcevla2025) | |
| [ChatVLA-2: **Vision-Language-Action Model with Open-World Embodied Reasoning from Pretrained Knowledge**](https://arxiv.org/abs/2505.21906) | arXiv | 2025-05-28 | [Project](https://chatvla-2.github.io/) | |
| [**Hume: Introducing System-2 Thinking in Visual-Language-Action Model**](https://arxiv.org/abs/2505.21432) | arXiv | 2025-05-27 | ![Star](https://img.shields.io/github/stars/hume-vla/hume?style=social&label=Star) [Github](https://github.com/hume-vla/hume) | |
| [**Think Twice, Act Once: Token-Aware Compression and Action Reuse for Efficient Inference in Vision-Language-Action Models**](https://arxiv.org/abs/2505.21200) | arXiv | 2025-05-27 | - | |
| [**VLA-RL: Towards Masterful and General Robotic Manipulation with Scalable Reinforcement Learning**](https://arxiv.org/abs/2505.18719) | arXiv | 2025-05-24 | ![Star](https://img.shields.io/github/stars/GuanxingLu/vlarl?style=social&label=Star) [Github](https://github.com/GuanxingLu/vlarl) | |
| [**Interactive Post-Training for Vision-Language-Action Models**](https://arxiv.org/abs/2505.17016) | arXiv | 2025-05-22 | ![Star](https://img.shields.io/github/stars/Ariostgx/ript-vla?style=social&label=Star) [Github](https://github.com/Ariostgx/ript-vla) | |
| [**BadVLA: Towards Backdoor Attacks on Vision-Language-Action Models via Objective-Decoupled Optimization**](https://arxiv.org/abs/2505.16640) | arXiv | 2025-05-22 | [Project](https://badvla-project.github.io/) | |
| [**ManipLVM-R1: Reinforcement Learning for Reasoning in Embodied Manipulation with Large Vision-Language Models**](https://arxiv.org/abs/2505.16517) | arXiv | 2025-05-22 | - | |
| [**From Grounding to Manipulation: Case Studies of Foundation Model Integration in Embodied Robotic Systems**](https://arxiv.org/abs/2505.15685) | arXiv | 2025-05-21 | - | |
| [**Saliency-Aware Quantized Imitation Learning for Efficient Robotic Control**](https://arxiv.org/abs/2505.15304) | arXiv | 2025-05-21 | - | |
| [**Incentivizing Multimodal Reasoning in Large Models for Direct Robot Manipulation**](https://arxiv.org/abs/2505.12744) | arXiv | 2025-05-19 | - | |
| [**OneTwoVLA: A Unified Vision-Language-Action Model with Adaptive Reasoning**](https://arxiv.org/abs/2505.11917) | arXiv | 2025-05-17 | ![Star](https://img.shields.io/github/stars/Fanqi-Lin/OneTwoVLA?style=social&label=Star) [Github](https://github.com/Fanqi-Lin/OneTwoVLA) | |
| [**VTLA: Vision-Tactile-Language-Action Model with Preference Learning for Insertion Manipulation**](https://arxiv.org/abs/2505.09577) | arXiv | 2025-05-14 | [Project](https://sites.google.com/view/vtla) | |
| [FSD: **From Seeing to Doing: Bridging Reasoning and Decision for Robotic Manipulation**](https://arxiv.org/abs/2505.08548) | arXiv | 2025-05-13 | [Project](https://embodied-fsd.github.io/) | |
| [ECoT-Lite: **Training Strategies for Efficient Embodied Reasoning**](https://arxiv.org/abs/2505.08243) | arXiv | 2025-05-13 | - | |
| [**UniVLA: Learning to Act Anywhere with Task-centric Latent Actions**](https://www.arxiv.org/abs/2505.06111) | RSS 2025 | 2025-05-09 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/UniVLA?style=social&label=Star) [Github](https://github.com/OpenDriveLab/UniVLA) | |
| [**3D CAVLA: Leveraging Depth and 3D Context to Generalize Vision Language Action Models for Unseen Tasks**](https://arxiv.org/abs/2505.05800) | arXiv | 2025-05-09 | [Project](https://3d-cavla.github.io/) |  |
| [**OpenHelix: A Short Survey, Empirical Analysis, and Open-Source Dual-System VLA Model for Robotic Manipulation**](https://arxiv.org/abs/2505.03912) | arXiv | 2025-05-06 | ![Star](https://img.shields.io/github/stars/OpenHelix-robot/OpenHelix?style=social&label=Star) [Github](https://github.com/OpenHelix-robot/OpenHelix) |  |
| [**GraspVLA: a Grasping Foundation Model Pre-trained on Billion-scale Synthetic Action Data**](https://arxiv.org/abs/2505.03233) | arXiv | 2025-05-06 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/GraspVLA?style=social&label=Star) [Github](https://github.com/PKU-EPIC/GraspVLA) |  |
| [**Interleave-VLA: Enhancing Robot Manipulation with Interleaved Image-Text Instructions**](https://arxiv.org/abs/2505.02152) | arXiv | 2025-05-04 | [Project](https://interleave-vla-anonymous.github.io/Interleave-VLA-Anonymous/) |  |
| [**CrayonRobo: Object-Centric Prompt-Driven Vision-Language-Action Model for Robotic Manipulation**](https://arxiv.org/abs/2505.02166) | arXiv | 2025-05-04 | - |  |
| [**NORA: A Small Open-Sourced Generalist Vision Language Action Model for Embodied Tasks**](https://arxiv.org/abs/2504.19854) | arXiv | 2025-04-28 | ![Star](https://img.shields.io/github/stars/declare-lab/nora?style=social&label=Star) [Github](https://github.com/declare-lab/nora) |  |
| [**π<sub>0.5</sub>: a Vision-Language-Action Model with Open-World Generalization**](https://arxiv.org/abs/2504.16054) | arXiv | 2025-04-22 | [Project](https://www.pi.website/blog/pi05) |  |
| [**A0: An Affordance-Aware Hierarchical Model for General Robotic Manipulation**](https://arxiv.org/abs/2504.12636) | arXiv | 2025-04-17 | ![Star](https://img.shields.io/github/stars/A-embodied/A0?style=social&label=Star) [Github](https://github.com/A-embodied/A0) |  |
| [**CoT-VLA: Visual Chain-of-Thought Reasoning for Vision-Language-Action Models**](https://arxiv.org/abs/2503.22020) | CVPR 2025 | 2025-03-27 | [Project](https://cot-vla.github.io/) |  |
| [**MoLe-VLA: Dynamic Layer-skipping Vision Language Action Model via Mixture-of-Layers for Efficient Robot Manipulation**](https://arxiv.org/abs/2503.20384) | arXiv | 2025-03-26 | ![Star](https://img.shields.io/github/stars/RoyZry98/MoLe-VLA-Pytorch?style=social&label=Star) [Github](https://github.com/RoyZry98/MoLe-VLA-Pytorch/) |  |
| [**Dita: Scaling Diffusion Transformer for Generalist Vision-Language-Action Policy**](https://arxiv.org/abs/2503.19757) | arXiv | 2025-03-25 | ![Star](https://img.shields.io/github/stars/RoboDita/Dita?style=social&label=Star) [Github](https://github.com/RoboDita/Dita) |  |
| [**DataPlatter: Boosting Robotic Manipulation Generalization with Minimal Costly Data**](https://arxiv.org/abs/2503.19516) | arXiv | 2025-03-25 | - |  |
| [**AgiBot World Colosseo: A Large-scale Manipulation Platform for Scalable and Intelligent Embodied Systems**](https://arxiv.org/abs/2503.06669) | - | 2025-03-09 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/AgiBot-World?style=social&label=Star) [Github](https://github.com/OpenDriveLab/AgiBot-World) |  |
| [GO-1: **AgiBot World Colosseo: A Large-scale Manipulation Platform for Scalable and Intelligent Embodied Systems**](https://arxiv.org/abs/2503.06669) | IROS 2025 | 2025-03-09 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/AgiBot-World?style=social&label=Star) [Github](https://github.com/OpenDriveLab/AgiBot-World) |
| [**VLA Model-Expert Collaboration for Bi-directional Manipulation Learning**](https://arxiv.org/abs/2503.04163) | arXiv | 2025-03-06 | [Project](https://aoqunjin.github.io/Expert-VLA/) |  |
| [**DexGraspVLA: A Vision-Language-Action Framework Towards General Dexterous Grasping**](https://arxiv.org/abs/2502.20900) | arXiv | 2025-03-05 | ![Star](https://img.shields.io/github/stars/Psi-Robot/DexGraspVLA?style=social&label=Star) [Github](https://github.com/Psi-Robot/DexGraspVLA) |  |
| [**OTTER: A Vision-Language-Action Model with Text-Aware Visual Feature Extraction**](https://arxiv.org/abs/2503.03734) | ICML 2025 | 2025-03-05 | ![Star](https://img.shields.io/github/stars/Max-Fu/otter?style=social&label=Star) [Github](https://github.com/Max-Fu/otter) |  |
| [**Accelerating Vision-Language-Action Model Integrated with Action Chunking via Parallel Decoding**](https://arxiv.org/abs/2503.02310) | arXiv | 2025-02-28 | - |  |
| [**FLOWER: Democratizing Generalist Robot Policies with Efficient Vision-Language-Action Flow Policies**](https://openreview.net/forum?id=ifo8oWSLSq) | ICLR 2025 | 2025-02-28 | - |  |
| [**RoboBrain: A Unified Brain Model for Robotic Manipulation from Abstract to Concrete**](https://arxiv.org/abs/2502.21257) | CVPR 2025 | 2025-02-28 | [Project](https://superrobobrain.github.io/) |  |
| [OpenVLA-Oft: **Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success**](https://arxiv.org/abs/2502.19645) | arXiv | 2025-02-27 | ![Star](https://img.shields.io/github/stars/moojink/openvla-oft?style=social&label=Star) [Github](https://github.com/moojink/openvla-oft) |  |
| [**Hi Robot: Open-Ended Instruction Following with Hierarchical Vision-Language-Action Models**](https://arxiv.org/abs/2502.19417) | arXiv | 2025-02-26 | [Project](https://www.pi.website/research/hirobot) |  |
| [**ObjectVLA: End-to-End Open-World Object Manipulation Without Demonstration**](https://arxiv.org/abs/2502.19250) | arXiv | 2025-02-26 | [Project](https://objectvla.github.io/) |  |
| [**ChatVLA: Unified Multimodal Understanding and Robot Control with Vision-Language-Action Model**](https://arxiv.org/abs/2502.14420) | arXiv | 2025-02-20 | [Project](https://chatvla.github.io/) |  |
| [**Magma: A Foundation Model for Multimodal AI Agents**](https://arxiv.org/abs/2502.13130) | CVPR 2025 | 2025-02-18 | ![Star](https://img.shields.io/github/stars/microsoft/Magma?style=social&label=Star) [Github](https://github.com/microsoft/Magma) |  |
| [**DexVLA: Vision-Language Model with Plug-In Diffusion Expert for General Robot Control**](https://arxiv.org/abs/2502.05855) | arXiv | 2025-02-09 | ![Star](https://img.shields.io/github/stars/juruobenruo/DexVLA?style=social&label=Star) [Github](https://github.com/juruobenruo/DexVLA) |  |
| [**HAMSTER: Hierarchical Action Models For Open-World Robot Manipulation**](https://arxiv.org/abs/2502.05485) | ICLR 2025 | 2025-02-08 | [Project](https://hamster-robot.github.io/) |  |
| [**ConRFT: A Reinforced Fine-tuning Method for VLA Models via Consistency Policy**](https://arxiv.org/abs/2502.05450) | RSS 2025 | 2025-02-08 | [Project](https://cccedric.github.io/conrft/) |  |
| [**Probing a Vision-Language-Action Model for Symbolic States and Integration into a Cognitive Architecture**](https://arxiv.org/abs/2502.04558) | arXiv | 2025-02-06 | - |  |
| [RAD: **Action-Free Reasoning for Policy Generalization**](https://arxiv.org/abs/2502.03729) | arXiv | 2025-02-06 | [Project](https://rad-generalization.github.io/) |  |
| [**VLA-Cache: Towards Efficient Vision-Language-Action Model via Adaptive Token Caching in Robotic Manipulation**](https://arxiv.org/abs/2502.02175) | arXiv | 2025-02-04 | - |  |
| [**UP-VLA: A Unified Understanding and Prediction Model for Embodied Agent**](https://arxiv.org/abs/2501.18867) | arXiv | 2025-01-31 | - |  |
| [**SpatialVLA: Exploring Spatial Representations for Visual-Language-Action Model**](https://arxiv.org/abs/2501.15830) | RSS 2025 | 2025-01-27 | ![Star](https://img.shields.io/github/stars/SpatialVLA/SpatialVLA?style=social&label=Star) [Github](https://github.com/SpatialVLA/SpatialVLA) |  |
| [**CogACT: A Foundational Vision-Language-Action Model for Synergizing Cognition and Action in Robotic Manipulation**](https://arxiv.org/abs/2411.19650) | arXiv | 2024-12-29 | ![Star](https://img.shields.io/github/stars/microsoft/CogACT?style=social&label=Star) [Github](https://github.com/microsoft/CogACT) |  |
| [Seer: **Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation**](https://arxiv.org/abs/2412.15109) | ICLR 2025 | 2024-12-19 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/Seer?style=social&label=Star) [Github](https://github.com/OpenRobotLab/Seer/) |  |
| [RoboVLMs: **Towards Generalist Robot Policies: What Matters in Building Vision-Language-Action Models**](https://arxiv.org/abs/2412.14058) | arXiv | 2024-12-18 | ![Star](https://img.shields.io/github/stars/Robot-VLAs/RoboVLMs?style=social&label=Star) [Github](https://github.com/Robot-VLAs/RoboVLMs) |  |
| [**Emma-X: An Embodied Multimodal Action Model with Grounded Chain of Thought and Look-ahead Spatial Reasoning**](https://arxiv.org/abs/2412.11974) | arXiv | 2024-12-16 | ![Star](https://img.shields.io/github/stars/declare-lab/Emma-X?style=social&label=Star) [Github](https://github.com/declare-lab/Emma-X) |  |
| [**VLAS: Vision-Language-Action Model with Speech Instructions for Customized Robot Manipulation**](https://arxiv.org/abs/2502.13508) | ICLR 2025 | 2025-01-25 | ![Star](https://img.shields.io/github/stars/whichwhichgone/VLAS?style=social&label=Star) [Github](https://github.com/whichwhichgone/VLAS) |  |
| [**TraceVLA: Visual Trace Prompting Enhances Spatial-Temporal Awareness for Generalist Robotic Policies**](https://arxiv.org/abs/2412.10345) | ICLR 2025 | 2024-12-13 | ![Star](https://img.shields.io/github/stars/umd-huang-lab/tracevla?style=social&label=Star) [Github](https://github.com/umd-huang-lab/tracevla) |  |
| [**Diffusion-VLA: Scaling Robot Foundation Models via Unified Diffusion and Autoregression**](https://arxiv.org/abs/2412.03293) | ICML 2025 | 2024-12-14 | [Project](https://diffusion-vla.github.io/) |  |
| [**π<sub>0</sub>: A Vision-Language-Action Flow Model for General Robot Control**](https://arxiv.org/abs/2410.24164) | arXiv | 2024-10-31 | [Project](https://www.physicalintelligence.company/blog/pi0) |  |
| [BYOVLA: **Run-time Observation Interventions Make Vision-Language-Action Models More Visually Robust**](https://arxiv.org/abs/2410.01971) | arXiv | 2024-10-02 | ![Star](https://img.shields.io/github/stars/irom-lab/byovla?style=social&label=Star) [Github](https://github.com/irom-lab/byovla) |  |
| [**VLATest: Testing and Evaluating Vision-Language-Action Models for Robotic Manipulation**](https://arxiv.org/abs/2409.12894) | FSE 2025  | 2024-09-19 | ![Star](https://img.shields.io/github/stars/ma-labo/VLATest?style=social&label=Star) [Github](https://github.com/ma-labo/VLATest) |  |
| [**TinyVLA: Towards Fast, Data-Efficient Vision-Language-Action Models for Robotic Manipulation**](https://arxiv.org/abs/2409.12514) | RA-L 2025 | 2024-09-19 | ![Star](https://img.shields.io/github/stars/liyaxuanliyaxuan/TinyVLA?style=social&label=Star) [Github](https://github.com/liyaxuanliyaxuan/TinyVLA) |  |
| [**DeeR-VLA: Dynamic Inference of Multimodal Large Language Models for Efficient Robot Execution**](https://arxiv.org/abs/2411.02359) | NeurIPS 2024 | 2024-11-04 | [Github](https://github.com/yueyang130/DeeR-VLA) |  |
| [**QueST: Self-Supervised Skill Abstractions for Learning Continuous Control**](https://arxiv.org/abs/2407.15840) | NeurIPS 2024 | 2024-07-22 | ![Star](https://img.shields.io/github/stars/pairlab/QueST?style=social&label=Star) [Github](https://github.com/pairlab/QueST) |  |
| [**RoboMamba: Multimodal State Space Model for Efficient Robot Reasoning and Manipulation**](https://arxiv.org/abs/2406.04339) | NeurIPS 2024 | 2024-06-06 | ![Star](https://img.shields.io/github/stars/lmzpai/roboMamba?style=social&label=Star) [Github](https://github.com/lmzpai/roboMamba) |  |
| [DP-VLA: **A Dual Process VLA: Efficient Robotic Manipulation Leveraging VLM**](https://arxiv.org/abs/2410.15549) | CoRL 2024 | 2024-10-21 | - |  |
| [**OpenVLA: An Open-Source Vision-Language-Action Model**](https://arxiv.org/abs/2406.09246) | CoRL 2024 | 2024-06-13 | ![Star](https://img.shields.io/github/stars/openvla/openvla?style=social&label=Star) [Github](https://github.com/openvla/openvla) |  |
| [**LLARVA: Vision-Action Instruction Tuning Enhances Robot Learning**](https://arxiv.org/abs/2406.11815) | CoRL 2024 | 2024-06-17 | ![Star](https://img.shields.io/github/stars/Dantong88/LLARVA?style=social&label=Star) [Github](https://github.com/Dantong88/LLARVA) |  |
| [ECoT: **Robotic Control via Embodied Chain-of-Thought Reasoning**](https://arxiv.org/abs/2407.08693) | CoRL 2024 | 2024-07-11 | ![Star](https://img.shields.io/github/stars/MichalZawalski/embodied-CoT?style=social&label=Star) [Github](https://github.com/MichalZawalski/embodied-CoT/) |  |
| [**3D-VLA: A 3D Vision-Language-Action Generative World Model**](https://arxiv.org/abs/2403.09631) | ICML 2024 | 2024-03-14 | ![Star](https://img.shields.io/github/stars/UMass-Foundation-Model/3D-VLA?style=social&label=Star) [Github](https://github.com/UMass-Foundation-Model/3D-VLA) |  |
| [**Octo: An Open-Source Generalist Robot Policy**](https://arxiv.org/abs/2405.12213) | RSS 2024 | 2024-05-20 | ![Star](https://img.shields.io/github/stars/octo-models/octo?style=social&label=Star)  [Github](https://github.com/octo-models/octo) | |
| [**RT-H: Action Hierarchies Using Language**](https://arxiv.org/abs/2403.01823) | RSS 2024 | 2024-03-04 | [Project](https://rt-hierarchy.github.io/) |  |
| [RoboFlamingo: **Vision-Language Foundation Models as Effective Robot Imitators**](https://arxiv.org/abs/2311.01378) | ICLR 2024 | 2023-11-02 | ![Star](https://img.shields.io/github/stars/RoboFlamingo/RoboFlamingo?style=social&label=Star) [Github](https://github.com/RoboFlamingo/RoboFlamingo) |  |
| [**Open X-Embodiment: Robotic Learning Datasets and RT-X Models**](https://arxiv.org/abs/2310.08864) | ICRA 2024 | 2023-10-13 | ![Star](https://img.shields.io/github/stars/google-deepmind/open_x_embodiment?style=social&label=Star) [Github](https://github.com/google-deepmind/open_x_embodiment) | |
| [MOO: **Open-World Object Manipulation using Pre-trained Vision-Language Models**](https://arxiv.org/abs/2303.00905) | CoRL 2023 | 2023-03-02 | [Project](https://robot-moo.github.io/) |  |
| [**RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control**](https://arxiv.org/abs/2307.15818) | CoRL 2023 | 2023-07-28 | [Project](https://robotics-transformer2.github.io/) |  |
| [**RT-1: Robotics Transformer for Real-World Control at Scale**](https://arxiv.org/abs/2212.06817) | RSS 2023 | 2022-12-13 | ![Star](https://img.shields.io/github/stars/google-research/robotics_transformer?style=social&label=Star) [Github](https://github.com/google-research/robotics_transformer) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.22 - Tactile-based Action Models ******* -->
### Tactile-based Action Models
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Robotic Perception with a Large Tactile-Vision-Language Model for Physical Property Inference**](https://arxiv.org/abs/2506.19303) | arXiv | 2025-06-24 | - |
| [**ViTacFormer: Learning Cross-Modal Representation for Visuo-Tactile Dexterous Manipulation**](https://arxiv.org/abs/2506.15953) | arXiv | 2025-06-19 | - |
| [**Tactile Beyond Pixels: Multisensory Touch Representations for Robot Manipulation**](https://arxiv.org/abs/2506.14754) | arXiv | 20256-06-17 | - |
| [**Touch Begins Where Vision Ends: Generalizable Policies for Contact-rich Manipulation**](https://arxiv.org/abs/2506.13762) | arXiv | 2025-06-16 | ![Star](https://img.shields.io/github/stars/anonvital/anonvital?style=social&label=Star) [Github](https://github.com/anonvital/anonvital) |
| [**FreeTacMan: Robot-free Visuo-Tactile Data Collection System for Contact-rich Manipulation**](https://arxiv.org/abs/2506.01941) | arXiv | 2025-06-02 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/FreeTacMan?style=social&label=Star) [Github](https://github.com/OpenDriveLab/FreeTacMan) |
| [**Feel the Force: Contact-Driven Learning from Humans**](https://arxiv.org/abs/2506.01944) | arXiv | 2025-06-02 | [Project](https://feel-the-force-ftf.github.io/) |
| [**ControlTac: Force- and Position-Controlled Tactile Data Augmentation with a Single Reference Image**](https://arxiv.org/abs/2505.20498) | arXiv | 2025-05-26 | [Project](https://dongyuluo.github.io/controltac/) |
| [**CLTP: Contrastive Language-Tactile Pre-training for 3D Contact Geometry Understanding**](https://arxiv.org/abs/2505.08194) | arXiv | 2025-05-13 | [Project](https://sites.google.com/view/cltp/) |
| [**GelFusion: Enhancing Robotic Manipulation under Visual Constraints via Visuotactile Fusion**](https://arxiv.org/abs/2505.07455) | arXiv | 2025-05-12 | [Project](https://gelfusion.github.io/) |
| [**On the Importance of Tactile Sensing for Imitation Learning: A Case Study on Robotic Match Lighting**](https://arxiv.org/abs/2504.13618) | arXiv | 2025-04-18 | [Project](https://sites.google.com/view/tactile-il) |
| [**Look-to-Touch: A Vision-Enhanced Proximity and Tactile Sensor for Distance and Geometry Perception in Robotic Manipulation**](https://arxiv.org/abs/2504.10280) | arXiv | 2025-04-14 | - |
| [**TLA: Tactile-Language-Action Model for Contact-Rich Manipulation**](https://arxiv.org/abs/2503.08548) | arXiv | 2025-03-11 | [Project](https://sites.google.com/view/tactile-language-action/) |
| [**Digitizing Touch with an Artificial Multimodal Fingertip**](https://scontent-phx1-1.xx.fbcdn.net/v/t39.2365-6/465055681_924267079585273_8047410736294936611_n.pdf?_nc_cat=101&ccb=1-7&_nc_sid=3c67a6&_nc_ohc=eYsIus3g6awQ7kNvgHFzDT0&_nc_zt=14&_nc_ht=scontent-phx1-1.xx&_nc_gid=AMTquwsvbz_wl7RVbIQ8jop&oh=00_AYDMjkNHpucdF6CABQmVEn3awqGbVKQRc0VdZ78K9yxWiQ&oe=6729FC10) | arXiv | 2024-11-04 | ![Star](https://img.shields.io/github/stars/facebookresearch/digit360?style=social&label=Star) [Github](https://github.com/facebookresearch/digit360)  |
| [**Sparsh: Self-supervised touch representations for vision-based tactile sensing**](https://scontent-phx1-1.xx.fbcdn.net/v/t39.2365-6/464969941_1107633400780143_7479102347328147009_n.pdf?_nc_cat=103&ccb=1-7&_nc_sid=3c67a6&_nc_ohc=rIIjx3oS8NoQ7kNvgHoYE_8&_nc_zt=14&_nc_ht=scontent-phx1-1.xx&_nc_gid=Afu6x6FhbEXrGbbgReB-uHE&oh=00_AYBE3smKcto0X7YBse7xJmR7MDXYQdWIdRbYjvpl2wGayQ&oe=6729FA64) | CoRL 2024 | 2024 | ![Star](https://img.shields.io/github/stars/facebookresearch/sparsh?style=social&label=Star) [Github](https://github.com/facebookresearch/sparsh)  |
| [**MimicTouch: Leveraging Multi-modal Human Tactile Demonstrations for Contact-rich Manipulation**](https://arxiv.org/abs/2310.16917) | CoRL 2024 | 2023-10-25 | [Project](https://sites.google.com/view/MimicTouch)  |
| [**Octopi: Object Property Reasoning with Large Tactile-Language Models**](https://arxiv.org/abs/2405.02794) | RSS 2024 | 2024-05-05 | ![Star](https://img.shields.io/github/stars/clear-nus/octopi?style=social&label=Star) [Github](https://github.com/clear-nus/octopi)  |
| [**RoboPack: Learning Tactile-Informed Dynamics Models for Dense Packing**](https://arxiv.org/abs/2407.01418) | RSS 2024 | 2024-07-01 | [Project](https://robo-pack.github.io/)  |
| [RotateIt: **General In-Hand Object Rotation with Vision and Touch**](https://arxiv.org/abs/2309.09979) | CoRL 2023 | 2023-09-18 | [Project](https://haozhi.io/rotateit/)  |
| [T-DEX: **Dexterity from Touch: Self-Supervised Pre-Training of Tactile Representations with Robotic Play**](https://arxiv.org/abs/2303.12076) | CoRL 2023 | 2023-03-21 | ![Star](https://img.shields.io/github/stars/irmakguzey/tactile-dexterity?style=social&label=Star) [Github](https://github.com/irmakguzey/tactile-dexterity)  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


<!-- ******* 1.3.10-Reinforcement Learning ******* -->
### Reinforcement Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Equivariant Goal Conditioned Contrastive Reinforcement Learning**](https://arxiv.org/abs/2507.16139) | arXiv | 2025-07-22 | - |  |
| [**EXPO: Stable Reinforcement Learning with Expressive Policies**](https://arxiv.org/abs/2507.07986) | arXiv | 2025-07-10 | - |  |
| [**Goal-Oriented Skill Abstraction for Offline Multi-Task Reinforcement Learning**](https://arxiv.org/abs/2507.06628) | ICML 2025 | 2025-07-09 | - |  |
| [**Q-STAC: Q-Guided Stein Variational Model Predictive Actor-Critic**](https://arxiv.org/abs/2507.06625) | arXiv | 2025-07-09 | [Project](https://sites.google.com/view/q-stac#h.mprn6mj2v3sr) |  |
| [**Eye, Robot: Learning to Look to Act with a BC-RL Perception-Action Loop**](https://arxiv.org/abs/2506.10968) | arXiv | 2025-06-12 | [Project](https://www.eyerobot.net/) |  |
| [**Reinforcement Learning via Implicit Imitation Guidance**](https://arxiv.org/abs/2506.07505) | arXiv | 2025-06-09 | - |  |
| [**ReWiND: Language-Guided Rewards Teach Robot Policies without New Demonstrations**](https://arxiv.org/abs/2505.10911) | arXiv | 2025-05-16 | [Project](https://rewind-reward.github.io/) |  |
| [**What Matters for Batch Online Reinforcement Learning in Robotics?**](https://arxiv.org/abs/2505.08078) | arXiv | 2025-05-12 | [Project](https://pd-perry.github.io/batch-online-rl/) |  |
| [**Video-Enhanced Offline Reinforcement Learning: A Model-Based Approach**](https://arxiv.org/abs/2505.06482) | ICML 2025 | 2025-05-10 | ![Star](https://img.shields.io/github/stars/panmt/VeoRL?style=social&label=Star) [Github](https://github.com/panmt/VeoRL) |  |
| [**TREND: Tri-teaching for Robust Preference-based Reinforcement Learning with Demonstrations**](https://arxiv.org/abs/2505.06079) | ICRA 2025 | 2025-05-09 | [Project](https://shuaiyihuang.github.io/publications/TREND/) |  |
| [**Learning from Suboptimal Data in Continuous Control via Auto-Regressive Soft Q-Network**](https://arxiv.org/abs/2502.00288) | arXiv | 2025-02-01 | - |  |
| [**Policy Decorator: Model-Agnostic Online Refinement for Large Policy Model**](https://arxiv.org/abs/2412.13630) | ICLR 2025 | 2024-12-18 | ![Star](https://img.shields.io/github/stars/tongzhoumu/policy_decorator?style=social&label=Star) [Github](https://github.com/tongzhoumu/policy_decorator) |  |
| [**RLDG: Robotic Generalist Policy Distillation via Reinforcement Learning**](https://arxiv.org/abs/2412.09858) | arXiv | 2024-12-13 | [Project](https://generalist-distillation.github.io/) |  |
| [HIL-SERL: **Precise and Dexterous Robotic Manipulation via Human-in-the-Loop Reinforcement Learning**](https://arxiv.org/abs/2410.21845) | arXiv | 2024-10-29 | [Project](https://hil-serl.github.io/) |  |
| [**PointPatchRL - Masked Reconstruction Improves Reinforcement Learning on Point Clouds**](https://arxiv.org/abs/2410.18800) | CoRL 2024 | 2024-10-24 | [Project](https://alrhub.github.io/pprl-website) |  |
| [**SPIRE: Synergistic Planning, Imitation, and Reinforcement for Long-Horizon Manipulation**](https://arxiv.org/abs/2410.18065) | CoRL 2024 | 2024-10-23 | [Project](https://sites.google.com/view/spire-corl-2024) |  |
| [Maniwhere: **Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning**](https://arxiv.org/abs/2407.15815) | CoRL 2024 | 2024-07-22 | [Project](https://gemcollector.github.io/maniwhere/) |  |
| [PSL: **Plan-Seq-Learn: Language Model Guided RL for Solving Long Horizon Robotics Tasks**](https://arxiv.org/abs/2405.01534) | ICLR 2024 | 2024-05-02 | ![Star](https://img.shields.io/github/stars/mihdalal/planseqlearn?style=social&label=Star) [Github](https://github.com/mihdalal/planseqlearn) | |
| [**TD-MPC2: Scalable, Robust World Models for Continuous Control**](https://arxiv.org/abs/2310.16828) | ICLR 2024 | 2023-10-25 | ![Star](https://img.shields.io/github/stars/nicklashansen/tdmpc2?style=social&label=Star) [Github](https://github.com/nicklashansen/tdmpc2) | |
| [VELAP: **Expansive Latent Planning for Sparse Reward Offline Reinforcement Learning**](https://openreview.net/pdf?id=xQx1O7WXSA) | CoRL 2023 | 2023 | - | |
| [**Q-Transformer: Scalable Offline Reinforcement Learning via Autoregressive Q-Functions**](https://arxiv.org/abs/2309.10150) | CoRL 2023 | 2023-09-18 | [Project](https://qtransformer.github.io/) | |
| [PTR: **Pre-Training for Robots: Offline RL Enables Learning New Tasks from a Handful of Trials**](https://arxiv.org/abs/2210.05178) | RSS 2023 | 2022-10-11 | [Project](https://sites.google.com/view/ptr-final/) |  |
| [TD-MPC: **Temporal Difference Learning for Model Predictive Control**](https://arxiv.org/abs/2203.04955) | ICML 2022 | 2022-03-09 | ![Star](https://img.shields.io/github/stars/nicklashansen/tdmpc?style=social&label=Star) [Github](https://github.com/nicklashansen/tdmpc) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.11-Motion, Tranjectory and Flow ******* -->
### Motion, Tranjectory and Flow
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Path Planning_|
| [LACO: **Language-Conditioned Path Planning**](https://arxiv.org/abs/2308.16893) | CoRL 2023 | 2024-08-31 | ![Star](https://img.shields.io/github/stars/amberxie88/lapp?style=social&label=Star) [Github](https://github.com/amberxie88/lapp) |  |
| _Motion Planning_|
| [**Prompting with the Future: Open-World Model Predictive Control with Interactive Digital Twins**](https://arxiv.org/abs/2506.13761) | RSS 2025 | 2025-06-16 | ![Star](https://img.shields.io/github/stars/TritiumR/Prompting-with-the-Future?style=social&label=Star) [Github](https://github.com/TritiumR/Prompting-with-the-Future) |  |
| [**A Real-to-Sim-to-Real Approach to Robotic Manipulation with VLM-Generated Iterative Keypoint Rewards**](https://arxiv.org/abs/2502.08643) | ICRA 2025 | 2025-02-12 | ![Star](https://img.shields.io/github/stars/shivanshpatel35/IKER?style=social&label=Star) [Github](https://github.com/shivanshpatel35/IKER) | Motion Planning |
| [**DiffusionSeeder: Seeding Motion Optimization with Diffusion for Rapid Motion Planning**](https://arxiv.org/abs/2410.16727) | CoRL 2024 | 2024-10-22 | [Project](https://diffusion-seeder.github.io/) | Motion Planning  |
| [**ReKep: Spatio-Temporal Reasoning of Relational Keypoint Constraints for Robotic Manipulation**](https://arxiv.org/abs/2409.01652) | CoRL 2024 | 2024-09-03 | ![Star](https://img.shields.io/github/stars/huangwl18/ReKep?style=social&label=Star) [Github](https://github.com/huangwl18/ReKep) | Motion Planning |
| [**CoPa: General Robotic Manipulation through Spatial Constraints of Parts with Foundation Models**](https://arxiv.org/abs/2403.08248) | ICRAW 2024 | 2024-03-13 | ![Star](https://img.shields.io/github/stars/HaoxuHuang/copa?style=social&label=Star) [Github](https://github.com/HaoxuHuang/copa) | Motion Planning |
| [Elastic-DS: **Task Generalization with Stability Guarantees via Elastic Dynamical System Motion Policies**](https://arxiv.org/abs/2309.01884) | CoRL 2023 | 2023-09-05 | ![Star](https://img.shields.io/github/stars/tonylitianyu/Elastic-DS?style=social&label=Star) [Github](https://github.com/tonylitianyu/Elastic-DS) | IL, LfD, Motion |
| _Trajectory Optimization_|
| [**Geometry-aware 4D Video Generation for Robot Manipulation**](https://arxiv.org/abs/2507.01099) | arXiv | 2025-07-01 | ![Star](https://img.shields.io/github/stars/lzylucy/4dgen?style=social&label=Star) [Github](https://github.com/lzylucy/4dgen) |  |
| [**Robotic Manipulation by Imitating Generated Videos Without Physical Demonstrations**](https://arxiv.org/abs/2507.00990) | arXiv | 2025-07-01 | ![Star](https://img.shields.io/github/stars/shivanshpatel35/rigvid?style=social&label=Star) [Github](https://github.com/shivanshpatel35/rigvid) |  |
| [**ORION: Vision-based Manipulation from Single Human Video with Open-World Object Graphs**](https://arxiv.org/abs/2405.20321) | arXiv | 2024-05-30 | [Project](https://ut-austin-rpl.github.io/ORION-release/) |  |
| [PointFlowMatch: **Learning Robotic Manipulation Policies from Point Clouds with Conditional Flow Matching**](https://arxiv.org/abs/2409.07343) | CoRL 2024 | 2024-09-11 | [Project](http://pointflowmatch.cs.uni-freiburg.de/) |  |
| [**RoboTAP: Tracking Arbitrary Points for Few-Shot Visual Imitation**](https://arxiv.org/abs/2308.15975) | ICRA 2024 | 2023-08-30 | ![Star](https://img.shields.io/github/stars/google-deepmind/tapnet?style=social&label=Star) [Github](https://github.com/google-deepmind/tapnet/blob/main/colabs/tapir_clustering.ipynb) |  |
| [**VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models**](https://arxiv.org/abs/2307.05973) | CoRL 2023 | 2023-07-12 | ![Star](https://img.shields.io/github/stars/huangwl18/VoxPoser?style=social&label=Star)  [Github](https://github.com/huangwl18/VoxPoser) | Zero-shot Trajectory Optimization |
| [**LATTE: LAnguage Trajectory TransformEr**](https://arxiv.org/abs/2208.02918) | ICRA 2023 | 2022-08-04 | ![Star](https://img.shields.io/github/stars/arthurfenderbucker/LaTTe-Language-Trajectory-TransformEr?style=social&label=Star)  [Github](https://github.com/arthurfenderbucker/LaTTe-Language-Trajectory-TransformEr) |  |
| _Keypoint-conditioned policy_|
| [**Knowledge-Driven Imitation Learning: Enabling Generalization Across Diverse Conditions**](https://arxiv.org/abs/2506.21057) | arXiv | 2025-06-26 | ![Star](https://img.shields.io/github/stars/mioam/KnowledgeIL?style=social&label=Star) [Github](https://github.com/mioam/KnowledgeIL) |  |
| [**ATK: Automatic Task-driven Keypoint Selection for Robust Policy Learning**](https://arxiv.org/abs/2506.13867) | arXiv | 2025-06-16 | [Project](https://yunchuzhang.github.io/ATK/) |  |
| _Trajectory-conditioned policy_|
| [**Diffusion Trajectory-guided Policy for Long-horizon Robot Manipulation**](https://arxiv.org/abs/2502.10040) | arXiv | 2025-02-14 | - |  |
| [**P3-PO: Prescriptive Point Priors for Visuo-Spatial Generalization of Robot Policies**](https://arxiv.org/abs/2412.06784) | arXiv | 2024-12-09 | ![Star](https://img.shields.io/github/stars/mlevy2525/P3PO?style=social&label=Star) [Github](https://github.com/mlevy2525/P3PO) |  |
| [**Track2Act: Predicting Point Tracks from Internet Videos enables Generalizable Robot Manipulation**](https://arxiv.org/abs/2405.01527) | ECCV 2024 | 2024-05-02 | ![Star](https://img.shields.io/github/stars/homangab/Track-2-Act?style=social&label=Star) [Github](https://github.com/homangab/Track-2-Act) |  |
| [ATM: **Any-point Trajectory Modeling for Policy Learning**](https://arxiv.org/abs/2401.00025) | RSS 2024 | 2023-12-28 | ![Star](https://img.shields.io/github/stars/Large-Trajectory-Model/any-point-trajectory-modeling?style=social&label=Star) [Github](https://github.com/Large-Trajectory-Model/any-point-trajectory-modeling) |  |
| [AWE: **Waypoint-Based Imitation Learning for Robotic Manipulation**](https://arxiv.org/abs/2307.14326) | CoRL 2023 | 2023-07-26 | ![Star](https://img.shields.io/github/stars/lucys0/awe?style=social&label=Star) [Github](https://github.com/lucys0/awe) | IL, Waypoint |
| _Flow-conditioned policy_|
| [**EC-Flow: Enabling Versatile Robotic Manipulation from Action-Unlabeled Videos via Embodiment-Centric Flow**](https://arxiv.org/abs/2507.06224) | ICCV 2025 | 2025-07-08 | ![Star](https://img.shields.io/github/stars/YixiangChen515/EC-Flow?style=social&label=Star) [Github](https://github.com/YixiangChen515/EC-Flow) |  |
| [**VLM-SFD: VLM-Assisted Siamese Flow Diffusion Framework for Dual-Arm Cooperative Manipulation**](https://arxiv.org/abs/2506.13428) | arXiv | 2025-06-16 | [Project](https://sites.google.com/view/vlm-sfd/) |  |
| [**3DFlowAction: Learning Cross-Embodiment Manipulation from 3D Flow World Model**](https://arxiv.org/abs/2506.06199) | arXiv | 2025-06-06 | ![Star](https://img.shields.io/github/stars/Hoyyyaard/3DFlowAction?style=social&label=Star) [Github](https://github.com/Hoyyyaard/3DFlowAction/) |  |
| [**VIP: Vision Instructed Pre-training for Robotic Manipulation**](https://arxiv.org/abs/2410.07169) | arXiv | 2024-10-09 | ![Star](https://img.shields.io/github/stars/Lizhuoling/VIRT?style=social&label=Star) [Github](https://github.com/Lizhuoling/VIRT) |  |
| [**ManiTrend: Bridging Future Generation and Action Prediction with 3D Flow for Robotic Manipulation**](https://arxiv.org/abs/2502.10028) | arXiv | 2024-02-14 | - |  |
| [Im2Flow2Act: **Flow as the Cross-Domain Manipulation Interface**](https://www.arxiv.org/abs/2407.15208) | CoRL 2024 | 2024-07-21 | ![Star](https://img.shields.io/github/stars/real-stanford/im2Flow2Act?style=social&label=Star) [Github](https://github.com/real-stanford/im2Flow2Act) |  |
| [AVDC: **Learning to Act from Actionless Videos through Dense Correspondences**](https://arxiv.org/abs/2310.08576) | ICLR 2024 | 2023-10-12 | ![Star](https://img.shields.io/github/stars/flow-diffusion/AVDC?style=social&label=Star) [Github](https://github.com/flow-diffusion/AVDC) | Optical Flow |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.12-Data Collection, Selection and Augmentation ******* -->
### Data Collection, Selection and Augmentation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Hardware_ |
| [**Strong, Accurate, and Low-Cost Robot Manipulator**](https://arxiv.org/abs/2507.15693) | arXiv | 2025-07-21 | - |  |
| [**Touch in the Wild: Learning Fine-Grained Manipulation with a Portable Visuo-Tactile Gripper**](https://arxiv.org/abs/2507.15062) | RSSW 2025 | 2025-07-20 | ![Star](https://img.shields.io/github/stars/YolandaXinyueZhu/touch_in_the_wild?style=social&label=Star) [Github](https://github.com/YolandaXinyueZhu/touch_in_the_wild) |  |
| [**Dexterous Teleoperation of 20-DoF ByteDexter Hand via Human Motion Retargeting**](https://arxiv.org/abs/2507.03227) | arXiv | 2025-07-04 | [Project](https://byte-dexter.github.io/) |  |
| [**DexWrist: A Robotic Wrist for Constrained and Dynamic Manipulation**](https://arxiv.org/abs/2507.01008) | arXiv | 2025-07-01 | [Project](https://dexwrist.csail.mit.edu/) |  |
| [**RAPID Hand: A Robust, Affordable, Perception-Integrated, Dexterous Manipulation Platform for Generalist Robot Autonomy**](https://arxiv.org/abs/2506.07490) | arXiv | 2025-05-09 | [Project](https://rapid-hand.github.io/) |  |
| [**Demonstrating Learning from Humans on Open-Source Dexterous Robot Hands**](https://www.roboticsproceedings.org/rss20/p014.pdf) | RSS 2024 | 2024 | - | Dexterous Hand |
| [**Touchless Interactive Teaching of Soft Robots through Flexible Bimodal Sensory Interfaces**](https://www.nature.com/articles/s41467-022-32702-5) | NC 2022 | 2022-08-22 | - | Soft Hand |
| _Data Collection_ |
| [**Fast Bilateral Teleoperation and Imitation Learning Using Sensorless Force Control via Accurate Dynamics Model**](https://arxiv.org/abs/2507.06174) | arXiv | 2025-07-08 | - |  |
| [**TypeTele: Releasing Dexterity in Teleoperation by Dexterous Manipulation Types**](https://arxiv.org/abs/2507.01857) | arXiv | 2025-07-02 | [Project](https://isee-laboratory.github.io/TypeTele/) |
| [**CUPID: Curating Data your Robot Loves with Influence Functions**](https://arxiv.org/abs/2506.19121) | arXiv | 2025-06-23 | [Project](https://cupid-curation.github.io/) |  |
| [**Compliant Residual DAgger: Improving Real-World Contact-Rich Manipulation with Human Corrections**](https://arxiv.org/abs/2506.16685) | arXiv | 2025-06-20 | [Project](https://compliant-residual-dagger.github.io/) |  |
| [**mimic-one: a Scalable Model Recipe for General Purpose Robot Dexterity**](https://arxiv.org/abs/2506.11916) | arXiv | 2025-06-13 | [Project](https://mimicrobotics.github.io/mimic-one/) |  |
| [**ExoStart: Efficient learning for dexterous manipulation with sensorized exoskeleton demonstrations**](https://arxiv.org/abs/2506.11775) | arXiv | 2025-06-13 | [Project](https://sites.google.com/view/exostart) |  |  
| [**EgoZero: Robot Learning from Smart Glasses**](https://arxiv.org/abs/2505.20290) | arXiv | 2025-05-26 | [Project](https://egozero-robot.github.io/) |  |  
| [**Guiding Data Collection via Factored Scaling Curves**](https://arxiv.org/abs/2505.07728) | arXiv | 2025-05-12 | [Project](https://factored-data-scaling.github.io/) |  |  
| [**Kaiwu: A Multimodal Manipulation Dataset and Framework for Robot Learning and Human-Robot Interaction**](https://arxiv.org/abs/2503.05231) | arXiv | 2025-03-07 | - |  |  
| [**AVR: Active Vision-Driven Robotic Precision Manipulation with Viewpoint and Focal Length Optimization**](https://arxiv.org/abs/2503.01439) | arXiv | 2025-03-03 | [Project](https://avr-robot.github.io/) |  |  
| [**Physics-Driven Data Generation for Contact-Rich Manipulation via Trajectory Optimization**](https://arxiv.org/abs/2502.20382) | arXiv | 2025-02-27 | [Project](https://lujieyang.github.io/physicsgen/) |  |  
| [**DemoGen: Synthetic Demonstration Generation for Data-Efficient Visuomotor Policy Learning**](https://arxiv.org/abs/2502.16932) | RSS 2025 | 2025-02-24 | ![Star](https://img.shields.io/github/stars/TEA-Lab/DemoGen?style=social&label=Star) [Github](https://github.com/TEA-Lab/DemoGen) |  |  
| [**Re<sup>3</sup>Sim: Generating High-Fidelity Simulation Data via 3D-Photorealistic Real-to-Sim for Robotic Manipulation**](https://arxiv.org/abs/2502.08645) | arXiv | 2025-02-12 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/Re3Sim?style=social&label=Star) [Github](https://github.com/OpenRobotLab/Re3Sim) |  |  
| [**ALPHA-α and Bi-ACT Are All You Need: Importance of Position and Force Information/Control for Imitation Learning of Unimanual and Bimanual Robotic Manipulation with Low-Cost System**](https://arxiv.org/abs/2411.09942) | arXiv | 2024-11-15 | [Project](https://mertcookimg.github.io/alpha-biact/) |  |
| [**DexUMI: Using Human Hand as the Universal Manipulation Interface for Dexterous Manipulation**](https://arxiv.org/abs/2505.21864) | RSSW 2025 | 2025-05-28 | ![Star](https://img.shields.io/github/stars/real-stanford/DexUMI?style=social&label=Star) [Github](https://github.com/real-stanford/DexUMI) |  |
| [**TeleMoMa: A Modular and Versatile Teleoperation System for Mobile Manipulation**](https://arxiv.org/abs/2403.07869) | arXiv | 2024-03-12 | ![Star](https://img.shields.io/github/stars/UT-Austin-RobIn/telemoma?style=social&label=Star) [Github](https://github.com/UT-Austin-RobIn/telemoma) | |
| [**SkillMimicGen: Automated Demonstration Generation for Efficient Skill Learning and Deployment**](https://arxiv.org/abs/2410.18907) | CoRL 2024 | 2024-10-24 | [Project](https://skillgen.github.io/) |  |
| [NILS: **Scaling Robot Policy Learning via Zero-Shot Labeling with Foundation Models**](https://arxiv.org/abs/2410.17772) | CoRL 2024 | 2024-10-23 | [Project](https://robottasklabeling.github.io/) |  |
| [SOAR: **Autonomous Improvement of Instruction Following Skills via Foundation Models**](https://arxiv.org/abs/2407.20635) | CoRL 2024 | 2024-07-30 | ![Star](https://img.shields.io/github/stars/rail-berkeley/soar?style=social&label=Star) [Github](https://github.com/rail-berkeley/soar) |  |
| [**Manipulate-Anything: Automating Real-World Robots using Vision-Language Models**](https://arxiv.org/abs/2406.18915) | CoRL 2024 | 2024-06-27 | [Project](https://robot-ma.github.io/) | |
| [**DexCap: Scalable and Portable Mocap Data Collection System for Dexterous Manipulation**](https://arxiv.org/abs/2403.07788) | CoRL 2024 | 2024-03-12 | ![Star](https://img.shields.io/github/stars/j96w/DexCap?style=social&label=Star) [Github](https://github.com/j96w/DexCap) | |
| [**Universal Manipulation Interface: In-The-Wild Robot Teaching Without In-The-Wild Robots**](https://arxiv.org/abs/2402.10329) | RSS 2024 | 2024-02-15 | ![Star](https://img.shields.io/github/stars/real-stanford/universal_manipulation_interface?style=social&label=Star) [Github](https://github.com/real-stanford/universal_manipulation_interface) | |
| [**AirExo: Low-Cost Exoskeletons for Learning Whole-Arm Manipulation in the Wild**](https://arxiv.org/abs/2309.14975) | ICRA 2024 | 2023-09-26 | ![Star](https://img.shields.io/github/stars/AirExo/collector?style=social&label=Star) [Github](https://github.com/AirExo/collector) | |
| [**SPRINT: Scalable Policy Pre-Training via Language Instruction Relabeling**](https://arxiv.org/abs/2306.11886) | ICRA 2024 | 2023-06-20 | ![Star](https://img.shields.io/github/stars/clvrai/sprint?style=social&label=Star) [Github](https://github.com/clvrai/sprint) | |
| [**Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition**](https://arxiv.org/abs/2307.14535) | CoRL 2023 | 2023-07-26 | ![Star](https://img.shields.io/github/stars/real-stanford/scalingup?style=social&label=Star) [Github](https://github.com/real-stanford/scalingup) |  |
| [**AnyTeleop: A General Vision-Based Dexterous Robot Arm-Hand Teleoperation System**](https://arxiv.org/abs/2307.04577) | RSS 2023 | 2023-07-10 | [Project](https://yzqin.github.io/anyteleop/)  | |
| [DIAL: **Robotic Skill Acquisition via Instruction Augmentation with Vision-Language Models**](https://arxiv.org/abs/2211.11736) | RSS 2023 | 2022-11-21 | [Project](https://instructionaugmentation.github.io/) |  |
| [**RoboCat: A Self-Improving Generalist Agent for Robotic Manipulation**](https://arxiv.org/abs/2306.11706) | TMLR 2023 | 2023-06-20 | ![Star](https://img.shields.io/github/stars/kyegomez/RoboCAT?style=social&label=Star) [Github](https://github.com/kyegomez/RoboCAT) | |
| _Data Selection_ |
| [**Is Diversity All You Need for Scalable Robotic Manipulation?**](https://arxiv.org/abs/2507.06219) | arXiv | 2025-07-08 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/AgiBot-World?style=social&label=Star) [Github](https://github.com/OpenDriveLab/AgiBot-World) |  |
| [**SCIZOR: A Self-Supervised Approach to Data Curation for Large-Scale Imitation Learning**](https://arxiv.org/abs/2505.22626) | arXiv | 2025-05-28 | [Project](https://ut-austin-rpl.github.io/SCIZOR/) |  |
| [**Robot Data Curation with Mutual Information Estimators**](https://arxiv.org/abs/2502.08623) | arXiv | 2025-02-12 | [Project](https://joeyhejna.com/demonstration-info/) |  |
| [**What Matters in Learning from Large-Scale Datasets for Robot Manipulation**](https://openreview.net/forum?id=LqhorpRLIm) | ICLR 2025 | 2025-01-23 | [Project](https://mimiclabs-iclr.github.io/) |  |
| [AMF: **Active Fine-Tuning of Generalist Policies**](https://arxiv.org/abs/2410.05026) | arXiv | 2024-10-07 | - |  |
| [**Re-Mix: Optimizing Data Mixtures for Large Scale Imitation Learning**](https://arxiv.org/abs/2408.14037) | CoRL 2024 | 2024-08-26 | ![Star](https://img.shields.io/github/stars/jhejna/remix?style=social&label=Star) [Github](https://github.com/jhejna/remix) |  |
| [**An Unbiased Look at Datasets for Visuo-Motor Pre-Training**](https://arxiv.org/abs/2310.09289) | CoRL 2023 | 2023-10-13 | ![Star](https://img.shields.io/github/stars/SudeepDasari/data4robotics?style=social&label=Star) [Github](https://github.com/SudeepDasari/data4robotics) | |
| [**Data Quality in Imitation Learning**](https://arxiv.org/abs/2306.02437) | NeurIPS 2023 | 2023-06-04 | - |  |
| _Data Retrieval_ |
| [**STRAP: Robot Sub-Trajectory Retrieval for Augmented Policy Learning**](https://arxiv.org/abs/2412.15182) | ICLR 2025 | 2024-12-19 | [Project](https://weirdlabuw.github.io/strap/) | |
| [**Retrieval-Augmented Embodied Agents**](https://arxiv.org/abs/2404.11699) | CVPR 2024 | 2024-04-17 | - | |
| [**Behavior Retrieval: Few-Shot Imitation Learning by Querying Unlabeled Datasets**](https://arxiv.org/abs/2304.08742) | RSS 2023 | 2023-04-08 | ![Star](https://img.shields.io/github/stars/MaxDu17/BehaviorRetrieval?style=social&label=Star) [Github](https://github.com/MaxDu17/BehaviorRetrieval) | |
| _Data Augmentation_ |
| [**RoboPearls: Editable Video Simulation for Robot Manipulation**](https://arxiv.org/abs/2506.22756) | ICCV 2025| 2025-06-28 | [Project](https://tangtaogo.github.io/RoboPearls/) |  |
| [**RoboEngine: Plug-and-Play Robot Data Augmentation with Semantic Robot Segmentation and Background Generation**](https://arxiv.org/abs/2503.18738) | arXiv | 2025-03-24 | ![Star](https://img.shields.io/github/stars/michaelyuancb/roboengine?style=social&label=Star) [Github](https://github.com/michaelyuancb/roboengine) |  |
| [**Predictive Red Teaming: Breaking Policies Without Breaking Robots**](https://arxiv.org/abs/2502.06575) | arXiv | 2025-02-10 | [Project](https://predictive-red-team.github.io/) |  |
| [**RoCoDA: Counterfactual Data Augmentation for Data-Efficient Robot Learning from Demonstrations**](https://arxiv.org/abs/2411.16959) | arXiv | 2024-11-25 | [Project](https://rocoda.github.io/) |  |
| [**View-Invariant Policy Learning via Zero-Shot Novel View Synthesis**](https://arxiv.org/abs/2409.03685) | CoRL 2024 | 2024-09-05 | ![Star](https://img.shields.io/github/stars/s-tian/VISTA?style=social&label=Star) [Github](https://github.com/s-tian/VISTA) |  |
| [**RoVi-Aug: Robot and Viewpoint Augmentation for Cross-Embodiment Robot Learning**](https://arxiv.org/abs/2409.03403) | CoRL 2024 | 2024-09-05 | [Project](https://rovi-aug.github.io/) |  |
| [**Diffusion Augmented Agents: A Framework for Efficient Exploration and Transfer Learning**](https://arxiv.org/abs/2407.20798) | CoLLAs 2024 | 2024-07-30 | [Project](https://sites.google.com/view/diffusion-augmented-agents/) |  |
| [**Diffusion Meets DAgger: Supercharging Eye-in-hand Imitation Learning**](https://arxiv.org/abs/2402.17768) | RSS 2024 | 2023-02-27 | ![Star](https://img.shields.io/github/stars/ErinZhang1998/dmd_diffusion?style=social&label=Star) [Github](https://github.com/ErinZhang1998/dmd_diffusion) | |
| [ROSIE: **Scaling Robot Learning with Semantically Imagined Experience**](https://arxiv.org/abs/2302.11550) | RSS 2023 | 2023-02-22 | [Project](https://diffusion-rosie.github.io/) |  |
| [**GenAug: Retargeting behaviors to unseen situations via Generative Augmentation**](https://arxiv.org/abs/2302.06671) | RSS 2023 | 2023-02-13 | ![Star](https://img.shields.io/github/stars/genaug/genaug?style=social&label=Star) [Github](https://github.com/genaug/genaug) |  |
| _Evaluation_|
| [**Efficient Evaluation of Multi-Task Robot Policies With Active Experiment Selection**](https://arxiv.org/abs/2502.09829) | arXiv | 2025-02-14 | - |  |
| [**Contrast Sets for Evaluating Language-Guided Robot Policies**](https://arxiv.org/abs/2406.13636) | CoRL 2024 | 2024-06-19 | - |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.13-Affordance Learning ******* -->
### Affordance Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Articulated Object Affordance_ |
| [**ManipGPT: Is Affordance Segmentation by Large Vision Models Enough for Articulated Object Manipulation?**](https://arxiv.org/abs/2412.10050) | arXiv | 2024-12-13 | - | |
| [**UniAff: A Unified Representation of Affordances for Tool Usage and Articulation with Vision-Language Models**](https://arxiv.org/abs/2409.20551) | ICRA 2025 | 2024-09-16 | [Project](https://sites.google.com/view/uni-aff/home) | |
| [**A3VLM: Actionable Articulation-Aware Vision Language Model**](https://arxiv.org/abs/2406.07549) | CoRL 2024 | 2024-06-14 | ![Star](https://img.shields.io/github/stars/changhaonan/A3VLM?style=social&label=Star) [Github](https://github.com/changhaonan/A3VLM) | |
| [**AIC MLLM: Autonomous Interactive Correction MLLM for Robust Robotic Manipulation**](https://arxiv.org/abs/2406.11548) | CoRL 2024 | 2024-06-17 | [Project](https://sites.google.com/view/aic-mllm) | |
| [**SAGE: Bridging Semantic and Actionable Parts for Generalizable Manipulation of Articulated Objects**](https://arxiv.org/abs/2312.01307) | RSS 2024 | 2023-12-03 | ![Star](https://img.shields.io/github/stars/geng-haoran/SAGE?style=social&label=Star) [Github](https://github.com/geng-haoran/SAGE) | |
| [**Kinematic-aware Prompting for Generalizable Articulated Object Manipulation with LLMs**](https://arxiv.org/abs/2311.02847) | ICRA 2024 | 2023-11-06 | ![Star](https://img.shields.io/github/stars/GeWu-Lab/LLM_articulated_object_manipulation?style=social&label=Star) [Github](https://github.com/GeWu-Lab/LLM_articulated_object_manipulation) | |
| [**Ditto: Building Digital Twins of Articulated Objects from Interaction**](https://arxiv.org/abs/2202.08227) | CVPR 2022 | 2022-08-16 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/Ditto?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/Ditto) | |
| _Part-Based Object Affordance_ |
| [**PartInstruct: Part-level Instruction Following for Fine-grained Robot Manipulation**](https://arxiv.org/abs/2505.21652) | RSS 2025 | 2025-05-27 | ![Star](https://img.shields.io/github/stars/SCAI-JHU/PartInstruct?style=social&label=Star)  [Github](https://github.com/SCAI-JHU/PartInstruct) | |
| [3DAPNet: **Language-Conditioned Affordance-Pose Detection in 3D Point Clouds**](https://arxiv.org/abs/2309.10911) | ICRA 2024 | 2023-09-19 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/Language-Conditioned-Affordance-Pose-Detection-in-3D-Point-Clouds?style=social&label=Star)  [Github](https://github.com/Fsoft-AIC/Language-Conditioned-Affordance-Pose-Detection-in-3D-Point-Clouds) | |
| [CPM: **Composable Part-Based Manipulation**](https://arxiv.org/abs/2405.05876) | CoRL 2023 | 2024-05-09 | [Project](https://cpmcorl2023.github.io/) | |
| [**PartManip: Learning Cross-Category Generalizable Part Manipulation Policy from Point Cloud Observations**](https://arxiv.org/abs/2303.16958) | CVPR 2023 | 2023-03-29 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/PartManip?style=social&label=Star)  [Github](https://github.com/PKU-EPIC/PartManip) | |
| [**GAPartNet: Cross-Category Domain-Generalizable Object Perception and Manipulation via Generalizable and Actionable Parts**](https://arxiv.org/abs/2211.05272) | CVPR 2023 | 2022-11-10 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/GAPartNet?style=social&label=Star) [Github](https://github.com/PKU-EPIC/GAPartNet) | |
| _Spatial Affordance_ |
| [**T-Rex: Task-Adaptive Spatial Representation Extraction for Robotic Manipulation with Vision-Language Models**](https://arxiv.org/abs/2506.19498) | arXiv | 2025-06-24 | - | |
| [**Bridging Perception and Action: Spatially-Grounded Mid-Level Representations for Robot Generalization**](https://arxiv.org/abs/2506.06196) | arXiv | 2025-06-06 | [Project](https://mid-level-moe.github.io/) | |
| [**Robotic Visual Instruction**](https://arxiv.org/abs/2505.00693) | CVPR 2025 | 2025-05-01 | [Project](https://robotic-visual-instruction.github.io/#) | |
| [**RoboSpatial: Teaching Spatial Understanding to 2D and 3D Vision-Language Models for Robotics**](https://arxiv.org/abs/2411.16537) | arXiv | 2024-11-25 | [Project](https://chanh.ee/RoboSpatial/) | |
| [**SpatialBot: Precise Spatial Understanding with Vision Language Models**](https://arxiv.org/abs/2406.13642) | ICRA 2025 | 2024-06-19 | ![Star](https://img.shields.io/github/stars/BAAI-DCAI/SpatialBot?style=social&label=Star)  [Github](https://github.com/BAAI-DCAI/SpatialBot) | |
| [**RoboPoint: A Vision-Language Model for Spatial Affordance Prediction for Robotics**](https://arxiv.org/abs/2406.10721) | CoRL 2024 | 2024-06-15 | ![Star](https://img.shields.io/github/stars/wentaoyuan/RoboPoint?style=social&label=Star) [Github](https://github.com/wentaoyuan/RoboPoint) | |
| [**SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning Capabilities**](https://arxiv.org/abs/2401.12168) | CVPR 2024 | 2024-01-22 | [Project](https://spatial-vlm.github.io/) | |
| _Visual Affordance_|
| [**UAD: Unsupervised Affordance Distillation for Generalization in Robotic Manipulation**](https://arxiv.org/abs/2506.09284) | arXiv | 2025-06-10 | ![Star](https://img.shields.io/github/stars/TangYihe/unsup-affordance?style=social&label=Star) [Github](https://github.com/TangYihe/unsup-affordance) | |
| [**RAM: Retrieval-Based Affordance Transfer for Generalizable Zero-Shot Robotic Manipulation**](https://arxiv.org/abs/2407.04689) | CoRL 2024 | 2024-07-05 | ![Star](https://img.shields.io/github/stars/yxKryptonite/RAM_code?style=social&label=Star) [Github](https://github.com/yxKryptonite/RAM_code) | |
| [**MOKA: Open-World Robotic Manipulation through Mark-Based Visual Prompting**](https://arxiv.org/abs/2403.03174) | RSS 2024 | 2024-03-05 | ![Star](https://img.shields.io/github/stars/moka-manipulation/moka?style=social&label=Star) [Github](https://github.com/moka-manipulation/moka) |  |
| [**SLAP: Spatial-Language Attention Policies**](https://arxiv.org/abs/2304.11235) | CoRL 2023 | 2023-04-21 | ![Star](https://img.shields.io/github/stars/facebookresearch/home-robot?style=social&label=Star)  [Github](https://github.com/facebookresearch/home-robot/tree/main/projects/slap_manipulation) | |
| [**KITE: Keypoint-Conditioned Policies for Semantic Manipulation**](https://arxiv.org/abs/2306.16605) | CoRL 2023 | 2023-06-29 | [Project](https://sites.google.com/view/kite-website/home) | |
| [HULC++: **Grounding Language with Visual Affordances over Unstructured Data**](https://arxiv.org/abs/2210.01911) | ICRA 2023 | 2022-10-04 | ![Star](https://img.shields.io/github/stars/mees/hulc2?style=social&label=Star) [Github](https://github.com/mees/hulc2) | IL, RepL, Language Goal, Poliy Head, Visual Affordance  |
| [**CLIPort: What and Where Pathways for Robotic Manipulation**](https://arxiv.org/abs/2109.12098) | CoRL 2022 | 2021-09-24 | ![Star](https://img.shields.io/github/stars/cliport/cliport?style=social&label=Star) [Github](https://github.com/cliport/cliport) | |
| [VAPO: **Affordance Learning from Play for Sample-Efficient Policy Learning**](https://arxiv.org/abs/2203.00352) | ICRA 2022 | 2022-03-01 | [Project](http://vapo.cs.uni-freiburg.de/) | RepL, RL, Object-Centric |
| [**Transporter Networks: Rearranging the Visual World for Robotic Manipulation**](https://arxiv.org/abs/2010.14406) | CoRL 2020 | 2020-10-27 | ![Star](https://img.shields.io/github/stars/google-research/ravens?style=social&label=Star) [Github](https://github.com/google-research/ravens) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.14-3D Representation for Manipulation ******* -->
### 3D Representation for Manipulation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [RoboSplat: **Novel Demonstration Generation with Gaussian Splatting Enables Robust One-Shot Manipulation**](https://arxiv.org/abs/2504.13175) | RSS 2025 | 2025-04-17 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/robosplat?style=social&label=Star) [Github](https://github.com/OpenRobotLab/robosplat) | |
| [**G3Flow: Generative 3D Semantic Flow for Pose-aware and Generalizable Object Manipulation**](https://arxiv.org/abs/2411.18369) | arXiv | 2024-11-27 | ![Star](https://img.shields.io/github/stars/TianxingChen/G3Flow?style=social&label=Star) [Github](https://github.com/TianxingChen/G3Flow) | |
| [**MSGField: A Unified Scene Representation Integrating Motion, Semantics, and Geometry for Robotic Manipulation**](https://arxiv.org/abs/2410.15730) | arXiv | 2024-10-21 | ![Star](https://img.shields.io/github/stars/ShengYu724/MSGField?style=social&label=Star) [Github](https://github.com/ShengYu724/MSGField) | 2DGS |
| [**Splat-MOVER: Multi-Stage, Open-Vocabulary Robotic Manipulation via Editable Gaussian Splatting**](https://arxiv.org/abs/2405.04378) | CoRL 2024 | 2024-05-07 | ![Star](https://img.shields.io/github/stars/StanfordMSL/Splat-MOVER?style=social&label=Star) [Github](https://github.com/StanfordMSL/Splat-MOVER) | 3DGS |
| [**IMAGINATION POLICY: Using Generative Point Cloud Models for Learning Manipulation Policies**](https://arxiv.org/abs/2406.11740) | CoRL 2024 | 2024-06-17 | [Project](https://haojhuang.github.io/imagine_page/) |  |
| [**Physically Embodied Gaussian Splatting: A Realtime Correctable World Model for Robotics**](https://arxiv.org/abs/2406.10788) | CoRL 2024 | 2024-06-16 | [Project](https://embodied-gaussians.github.io/) | 3DGS |
| [**RiEMann: Near Real-Time SE(3)-Equivariant Robot Manipulation without Point Cloud Segmentation**](https://arxiv.org/abs/2403.19460) | CoRL 2024 | 2024-03-28 | ![Star](https://img.shields.io/github/stars/HeegerGao/RiEMann?style=social&label=Star) [Github](https://github.com/HeegerGao/RiEMann) |  |
| [**RoboEXP: Action-Conditioned Scene Graph via Interactive Exploration for Robotic Manipulation**](https://arxiv.org/abs/2402.15487) | CoRL 2024 | 2024-02-23 | ![Star](https://img.shields.io/github/stars/Jianghanxiao/RoboEXP?style=social&label=Star) [Github](https://github.com/Jianghanxiao/RoboEXP) | 3D reasoning, action-conditioned scene graph (ACSG) task |
| [**D<sup>3</sup>Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Rearrangement**](https://arxiv.org/abs/2309.16118) | CoRL 2024 | 2023-09-28 | ![Star](https://img.shields.io/github/stars/WangYixuan12/d3fields?style=social&label=Star) [Github](https://github.com/WangYixuan12/d3fields) |  |
| [**Object-Aware Gaussian Splatting for Robotic Manipulation**](https://openreview.net/pdf?id=gdRI43hDgo) | ICRAW 2024 | 2024-04-24 | [Project](https://object-aware-gaussian.github.io/) | 3DGS |
| [F3RM: **Distilled Feature Fields Enable Few-Shot Language-Guided Manipulation**](https://arxiv.org/abs/2308.07931) | CoRL 2023 | 2023-07-27 | ![Star](https://img.shields.io/github/stars/f3rm/f3rm?style=social&label=Star) [Github](https://github.com/f3rm/f3rm) | NeRF |
| [R-NDF: **SE(3)-Equivariant Relational Rearrangement with Neural Descriptor Fields**](https://arxiv.org/abs/2211.09786) | CORL 2022 | 2022-11-17 | ![Star](https://img.shields.io/github/stars/anthonysimeonov/relational_ndf?style=social&label=Star)  [Github](https://github.com/anthonysimeonov/relational_ndf) |  |
| [NDF: **Neural Descriptor Fields: SE(3)-Equivariant Object Representations for Manipulation**](https://arxiv.org/abs/2112.05124) | ICRA 2022 | 2021-12-09 | ![Star](https://img.shields.io/github/stars/anthonysimeonov/ndf_robot?style=social&label=Star) [Github](https://github.com/anthonysimeonov/ndf_robot) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.15-3D Representation Policy Learning ******* -->
### 3D Representation Policy Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Diffusion Policy (DP)_|
| [**PRISM: Pointcloud Reintegrated Inference via Segmentation and Cross-attention for Manipulation**](https://arxiv.org/abs/2507.04633) | arXiv | 2025-07-07 | ![Star](https://img.shields.io/github/stars/czknuaa/PRISM?style=social&label=Star) [Github](https://github.com/czknuaa/PRISM) |  |
| [PPI: **Gripper Keypose and Object Pointflow as Interfaces for Bimanual Robotic Manipulation**](https://arxiv.org/abs/2504.17784) | RSS 2025 | 2025-04-24 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/PPI?style=social&label=Star) [Github](https://github.com/OpenRobotLab/PPI) |  |
| [**GravMAD: Grounded Spatial Value Maps Guided Action Diffusion for Generalized 3D Manipulation**](https://arxiv.org/abs/2409.20154) | ICLR 2025 | 2024-09-30 | [Project](https://gravmad.github.io/) |  |
| [**3D Diffuser Actor: Policy Diffusion with 3D Scene Representations**](https://arxiv.org/abs/2402.10885) | CoRL 2024 | 2024-02-16 | ![Star](https://img.shields.io/github/stars/nickgkan/3d_diffuser_actor?style=social&label=Star) [Github](https://github.com/nickgkan/3d_diffuser_actor) |  |
| [DP3: **3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations**](https://arxiv.org/abs/2403.03954) | RSS 2024 | 2024-03-06 | ![Star](https://img.shields.io/github/stars/YanjieZe/3D-Diffusion-Policy?style=social&label=Star) [Github](https://github.com/YanjieZe/3D-Diffusion-Policy) |  |
| _Reconstruction_ |
| [**CL3R: 3D Reconstruction and Contrastive Learning for Enhanced Robotic Manipulation Representations**](https://arxiv.org/abs/2507.08262) | arXiv | 2025-07-11 | - |  |
| [**EquAct: An SE(3)-Equivariant Multi-Task Transformer for Open-Loop Robotic Manipulation**](https://arxiv.org/abs/2505.21351) | arXiv | 2025-05-27 | - |  |
| [**Lift3D Foundation Policy: Lifting 2D Large-Scale Pretrained Models for Robust 3D Robotic Manipulation**](https://arxiv.org/abs/2411.18623) | arXiv | 2024-11-27 | ![Star](https://img.shields.io/github/stars/PKU-HMI-Lab/LIFT3D?style=social&label=Star) [Github](https://github.com/PKU-HMI-Lab/LIFT3D) |  |
| [**SPA: 3D Spatial-Awareness Enables Effective Embodied Representation**](https://arxiv.org/abs/2410.08208) | ICLR 2025 | 2024-10-10 | ![Star](https://img.shields.io/github/stars/HaoyiZhu/SPA?style=social&label=Star) [Github](https://github.com/HaoyiZhu/SPA) | |
| [**ManiGaussian: Dynamic Gaussian Splatting for Multi-task Robotic Manipulation**](https://arxiv.org/abs/2403.08321) | ECCV 2024 | 2024-03-13 | ![Star](https://img.shields.io/github/stars/GuanxingLu/ManiGaussian?style=social&label=Star) [Github](https://github.com/GuanxingLu/ManiGaussian) | 3DGS, IL, Language Goal, Reconstruction/Prediction |
| [SGRv2: **Leveraging Locality to Boost Sample Efficiency in Robotic Manipulation**](https://arxiv.org/abs/2406.10615) | CoRL 2024 | 2024-06-15 | ![Star](https://img.shields.io/github/stars/TongZhangTHU/sgr?style=social&label=Star) [Github](https://github.com/TongZhangTHU/sgr) |  |
| [**RVT-2: Learning Precise Manipulation from Few Demonstrations**](https://arxiv.org/abs/2406.08545) | RSS 2024 | 2024-01-12 | ![Star](https://img.shields.io/github/stars/nvlabs/rvt?style=social&label=Star) [Github](https://github.com/nvlabs/rvt) |  |
| [**GNFactor: Multi-Task Real Robot Learning with Generalizable Neural Feature Fields**](https://arxiv.org/abs/2308.16891) | CoRL 2023 | 2023-08-31 | ![Star](https://img.shields.io/github/stars/YanjieZe/GNFactor?style=social&label=Star) [Github](https://github.com/YanjieZe/GNFactor) | NeRF, IL, Language Goal, Reconstruction |
| [3D4RL: **Visual Reinforcement Learning with Self-Supervised 3D Representations**](https://arxiv.org/abs/2210.07241) | RA-L 2023 | 2022-10-13 | ![Star](https://img.shields.io/github/stars/YanjieZe/rl3d?style=social&label=Star) [Github](https://github.com/YanjieZe/rl3d) | RL, RepL, Reconstruction, Image Goal |
| [**PolarNet: 3D Point Clouds for Language-Guided Robotic Manipulation**](https://arxiv.org/abs/2309.15596) | CoRL 2023 | 2023-09-27 | ![Star](https://img.shields.io/github/stars/vlc-robot/polarnet?style=social&label=Star) [Github](https://github.com/vlc-robot/polarnet) |  |
| [**M2T2: Multi-Task Masked Transformer for Object-centric Pick and Place**](https://arxiv.org/abs/2311.00926) | CoRL 2023 | 2023-11-02 | ![Star](https://img.shields.io/github/stars/NVlabs/M2T2?style=social&label=Star) [Github](https://github.com/NVlabs/M2T2) |  |
| [PerAct: **Perceiver-Actor: A Multi-Task Transformer for Robotic Manipulation**](https://arxiv.org/abs/2209.05451) | CoRL 2022 | 2022-09-12 | ![Star](https://img.shields.io/github/stars/peract/peract?style=social&label=Star)  [Github](https://github.com/peract/peract) | PerAct |
| _Visual Goal Generation_ |
| [**3D-MVP: 3D Multiview Pretraining for Robotic Manipulation**](https://arxiv.org/abs/2406.18158) | CVPR 2025 | 2024-06-26 | [Project](https://jasonqsy.github.io/3DMVP/) |  |
| [ActAIM2: **Discovering Robotic Interaction Modes with Discrete Representation Learning**](https://arxiv.org/abs/2410.20258) | CoRL 2024 | 2024-10-26 | [Project](https://actaim2.github.io/) |  |
| [**SAM-E: Leveraging Visual Foundation Model with Sequence Imitation for Embodied Manipulation**](https://arxiv.org/abs/2405.19586) | ICML 2024 | 2024-05-30 | ![Star](https://img.shields.io/github/stars/pipixiaqishi1/SAM-E?style=social&label=Star) [Github](https://github.com/pipixiaqishi1/SAM-E) |  |
| [**RVT: Robotic View Transformer for 3D Object Manipulation**](https://arxiv.org/abs/2306.14896) | CoRL 2023 | 2023-06-26 | ![Star](https://img.shields.io/github/stars/nvlabs/rvt?style=social&label=Star) [Github](https://github.com/nvlabs/rvt) |  |
| [GROOT: **Learning Generalizable Manipulation Policies with Object-Centric 3D Representations**](https://arxiv.org/abs/2310.14386) | CoRL 2023 | 2023-10-22 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/GROOT?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/GROOT) | IL, RepL, TP, Object-Centric, PC |
| _3D Policy_ |
| [**FlowRAM: Grounding Flow Matching Policy with Region-Aware Mamba Framework for Robotic Manipulation**](https://arxiv.org/abs/2506.16201) | arXiv | 2025-06-19 | - |  |
| [**EmbodiedMAE: A Unified 3D Multi-Modal Representation for Robot Manipulation**](https://arxiv.org/abs/2505.10105) | arXiv | 2025-05-15 | - |  |
| [**FP3: A 3D Foundation Policy for Robotic Manipulation**](https://arxiv.org/abs/2503.08950) | arXiv | 2025-03-11 | ![Star](https://img.shields.io/github/stars/horipse01/3d-foundation-policy?style=social&label=Star) [Github](https://github.com/horipse01/3d-foundation-policy) |  |
| [**VidBot: Learning Generalizable 3D Actions from In-the-Wild 2D Human Videos for Zero-Shot Robotic Manipulation**](https://arxiv.org/abs/2503.07135) | CVPR 2025 | 2025-03-10 | [Project](https://hanzhic.github.io/vidbot-project/) |  |
| [SPHINX: **What's the Move? Hybrid Imitation Learning via Salient Points**](https://arxiv.org/abs/2412.05426) | ICLR 2025 | 2024-12-06 | ![Star](https://img.shields.io/github/stars/priyasundaresan/sphinx?style=social&label=Star) [Github](https://github.com/priyasundaresan/sphinx) |  |
| [OBSBench: **Point Cloud Matters: Rethinking the Impact of Different Observation Spaces on Robot Learning**](https://arxiv.org/abs/2402.02500) | NeuIPS 2024 | 2024-02-04 | ![Star](https://img.shields.io/github/stars/HaoyiZhu/PointCloudMatters?style=social&label=Star) [Github](https://github.com/HaoyiZhu/PointCloudMatters) |
| [SGR: **A Universalc Semantic-Geometric Representation for Robotic Manipulation**](https://arxiv.org/abs/2306.10474) | CoRL 2023 | 2023-06-18 | ![Star](https://img.shields.io/github/stars/TongZhangTHU/sgr?style=social&label=Star) [Github](https://github.com/TongZhangTHU/sgr) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.16-Reasoning, Planning and Code Generation ******* -->
### High-level Planner
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Control_|
| [**DEMONSTRATE: Zero-shot Language to Robotic Control via Multi-task Demonstration Learning**](https://arxiv.org/abs/2507.12855) | arXiv | 2025-07-17 | - |  |
| _Task Planning_ |
| [**Imagine, Verify, Execute: Memory-Guided Agentic Exploration with Vision-Language Models**](https://arxiv.org/abs/2505.07815) | arXiv | 2025-05-12 | [Project](https://ive-robot.github.io/) |  |
| [**MALMM: Multi-Agent Large Language Models for Zero-Shot Robotics Manipulation**](https://arxiv.org/abs/2411.17636) | arXiv | 2024-11-26 | [Project](https://malmm1.github.io/) |  |
| [**Socratic Planner: Inquiry-Based Zero-Shot Planning for Embodied Instruction Following**](https://arxiv.org/abs/2404.15190) | arXiv | 2024-04-21 | - | |
| [**Polaris: Open-ended Interactive Robotic Manipulation via Syn2Real Visual Grounding and Large Language Models**](https://arxiv.org/abs/2408.07975) | IROS 2024 | 2024-08-15 | [Project](https://star-uu-wang.github.io/Polaris/) |  |
| [PG-InstructBLIP: **Physically Grounded Vision-Language Models for Robotic Manipulation**](https://arxiv.org/abs/2309.02561) | ICRA 2024 | 2023-09-05 | [Project](https://iliad.stanford.edu/pg-vlm/) |  |
| [**RoCo: Dialectic Multi-Robot Collaboration with Large Language Models**](https://arxiv.org/abs/2307.04738) | ICRA 2024 | 2023-07-10 | ![Star](https://img.shields.io/github/stars/MandiZhao/robot-collab?style=social&label=Star) [Github](https://github.com/MandiZhao/robot-collab) | |
| [**REFLECT: Summarizing Robot Experiences for Failure Explanation and Correction**](https://arxiv.org/abs/2306.15724) | CoRL 2023 | 2023-06-27 | ![Star](https://img.shields.io/github/stars/real-stanford/reflect?style=social&label=Star) [Github](https://github.com/real-stanford/reflect) | |
| [Saycan: **Do As I Can, Not As I Say: Grounding Language in Robotic Affordances**](https://arxiv.org/abs/2204.01691) | CoRL 2023 | 2022-04-04 | ![Star](https://img.shields.io/github/stars/google-research/google-research?style=social&label=Star) [Github](https://github.com/google-research/google-research/tree/master/saycan) | |
| [**LLM+P: Empowering Large Language Models with Optimal Planning Proficiency**](https://arxiv.org/abs/2304.11477) | arXiv | 2023-04-22 | ![Star](https://img.shields.io/github/stars/Cranial-XIX/llm-pddl?style=social&label=Star) [Github](https://github.com/Cranial-XIX/llm-pddl) | |
| [**Inner Monologue: Embodied Reasoning through Planning with Language Models**](https://arxiv.org/abs/2207.05608) | CoRL 2022 | 2022-07-12 | [Project](https://innermonologue.github.io/) | |
| [SHOWTELL: **Teaching Robots with Show and Tell: Using Foundation Models to Synthesize Robot Policies from Language and Visual Demonstrations**](https://openreview.net/pdf?id=G8UcwxNAoD) | CoRL 2024 | 2024-09-06 | [Project](https://robo-showtell.github.io/) |  |
| [GIRAF: **Gesture-Informed Robot Assistance via Foundation Models**](https://arxiv.org/abs/2309.02721) | CoRL 2023 | 2023-09-06 | [Project](https://sites.google.com/view/giraf23) | |
| [**LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models**](https://arxiv.org/abs/2212.04088) | ICCV 2023 | 2022-12-08 | ![Star](https://img.shields.io/github/stars/OSU-NLP-Group/LLM-Planner?style=social&label=Star) [Github](https://github.com/OSU-NLP-Group/LLM-Planner/) |  |
| _Code Generation_ |
| [**Robotic Programmer: Video Instructed Policy Code Generation for Robotic Manipulation**](https://arxiv.org/abs/2501.04268) | arXiv | 2025-01-08 | [Project](https://video2code.github.io/RoboPro-website/) | |
| [**Demo2Code: From Summarizing Demonstrations to Synthesizing Code via Extended Chain-of-Thought**](https://arxiv.org/abs/2305.16744) | NeurIPS 2023 | 2023-05-26 | [Project](https://portal-cornell.github.io/demo2code/) | |
| [**Instruct2Act: Mapping Multi-modality Instructions to Robotic Actions with Large Language Model**](https://arxiv.org/abs/2305.11176) | arXiv | 2023-05-18 | ![Star](https://img.shields.io/github/stars/OpenGVLab/Instruct2Act?style=social&label=Star) [Github](https://github.com/OpenGVLab/Instruct2Act) | LLMs, VLMs, Code Generation |
| [**ProgPrompt: Generating Situated Robot Task Plans using Large Language Models**](https://arxiv.org/abs/2209.11302) | ICRA 2023 | 2022-09-22 | ![Star](https://img.shields.io/github/stars/NVlabs/progprompt-vh?style=social&label=Star) [Github](https://github.com/NVlabs/progprompt-vh) | LLMs, Code Generation |
| [**ChatGPT for Robotics: Design Principles and Model Abilities**](https://arxiv.org/abs/2306.17582) | IEEE Access 2023 | 2023-02-20 | ![Star](https://img.shields.io/github/stars/microsoft/PromptCraft-Robotics?style=social&label=Star) [Github](https://github.com/microsoft/PromptCraft-Robotics) | LLMs, Code Generation |
| [**Code as Policies: Language Model Programs for Embodied Control**](https://arxiv.org/abs/2209.07753) | ICRA 2023 | 2022-09-16 | ![Star](https://img.shields.io/github/stars/google-research/google-research?style=social&label=Star) [Github](https://github.com/google-research/google-research/tree/master/code_as_policies) | LLMs, Code Generation |
| [**TidyBot: Personalized Robot Assistance with Large Language Models**](https://arxiv.org/abs/2305.05658) | Autonomous Robots 2023 | 2023-05-09 | ![Star](https://img.shields.io/github/stars/jimmyyhwu/tidybot?style=social&label=Star) [Github](https://github.com/jimmyyhwu/tidybot) | LLMs, Code Generation |
| [**Statler: State-Maintaining Language Models for Embodied Reasoning**](https://arxiv.org/abs/2306.17840) | ICRA 2024 | 2023-06-30 | ![Star](https://img.shields.io/github/stars/ripl/statler?style=social&label=Star) [Github](https://github.com/ripl/statler) | LLMs, Code Generation |
| [**InterPreT: Interactive Predicate Learning from Language Feedback for Generalizable Task Planning**](https://arxiv.org/abs/2405.19758) | RSS 2024 | 2023-05-30 | ![Star](https://img.shields.io/github/stars/hmz-15/interactive-predicate-learning?style=social&label=Star) [Github](https://github.com/hmz-15/interactive-predicate-learning) | Code Generation, Task Planning, PDDL |
| [**Text2Motion: From Natural Language Instructions to Feasible Plans**](https://arxiv.org/abs/2303.12153) | Autonomous Robots 2023 | 2023-03-21 | [Project](https://sites.google.com/stanford.edu/text2motion) |  |
| _Multimodal Reasoning_ |
| [**RoboBrain 2.0 Technical Report**](https://arxiv.org/abs/2507.02029) | arXiv | 2025-07-02 | ![Star](https://img.shields.io/github/stars/FlagOpen/RoboBrain2.0?style=social&label=Star) [Github](https://github.com/FlagOpen/RoboBrain2.0) |  |
| [**EmbodiedVSR: Dynamic Scene Graph-Guided Chain-of-Thought Reasoning for Visual Spatial Tasks**](https://arxiv.org/abs/2503.11089) | arXiv | 2025-03-14 | - |  |
| [**Can We Detect Failures Without Failure Data? Uncertainty-Aware Runtime Failure Detection for Imitation Learning Policies**](https://arxiv.org/abs/2503.08558) | arXiv | 2025-03-11 | [Project](https://cxu-tri.github.io/FAIL-Detect-Website/) |  |
| [**SoFar: Language-Grounded Orientation Bridges Spatial Reasoning and Object Manipulation**](https://arxiv.org/abs/2502.13143) | arXiv | 2025-02-18 | ![Star](https://img.shields.io/github/stars/qizekun/SoFar?style=social&label=Star) [Github](https://github.com/qizekun/SoFar) |  |
| [**From Foresight to Forethought: VLM-In-the-Loop Policy Steering via Latent Alignment**](https://arxiv.org/abs/2502.01828) | arXiv | 2025-02-03 | - |  |
| [**Code-as-Monitor: Constraint-aware Visual Programming for Reactive and Proactive Robotic Failure Detection**](https://arxiv.org/abs/2412.04455) | CVPR 2025 | 2024-12-05 | [Project](https://zhoues.github.io/Code-as-Monitor/) | VLMs, Failure Detection |
| [**AHA: A Vision-Language-Model for Detecting and Reasoning Over Failures in Robotic Manipulation**](https://arxiv.org/abs/2410.00371) | ICLR 2025 | 2024-10-01 | [Project](https://aha-vlm.github.io/) | VLMs, Failure Detection |
| [λ-Repformer: **Task Success Prediction for Open-Vocabulary Manipulation Based on Multi-Level Aligned Representations**](https://arxiv.org/abs/2410.00436) | CoRL 2024 | 2024-10-01 | [Project](https://lambda-repformer-project-pa-eziy1.kinsta.page/) | RepL, Multi-level, E-D TP, Both Goals |
| [**ManipLLM: Embodied Multimodal Large Language Model for Object-Centric Robotic Manipulation**](https://arxiv.org/abs/2312.16217) | CVPR 2024 | 2023-12-24 | ![Star](https://img.shields.io/github/stars/clorislili/ManipLLM?style=social&label=Star) [Github](https://github.com/clorislili/ManipLLM) |  |
| [**EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought**](https://arxiv.org/abs/2305.15021) | NeurIPS 2023 | 2023-05-24 | ![Star](https://img.shields.io/github/stars/EmbodiedGPT/EmbodiedGPT_Pytorch?style=social&label=Star) [Github](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch) |  |
| [Matcha: **Chat with the Environment: Interactive Multimodal Perception Using Large Language Models**](https://arxiv.org/abs/2303.08268) | IROS 2023 | 2023-03-14 | ![Star](https://img.shields.io/github/stars/xf-zhao/Matcha-agent?style=social&label=Star) [Github](https://github.com/xf-zhao/Matcha-agent) |  |
| [**PaLM-E: An Embodied Multimodal Language Model**](https://arxiv.org/abs/2303.03378) | ICML 2023 | 2023-03-06 | ![Star](https://img.shields.io/github/stars/kyegomez/PALM-E?style=social&label=Star) [Github](https://github.com/kyegomez/PALM-E) |  |
| [**Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language**](https://arxiv.org/abs/2204.00598) | ICLR 2023 | 2022-04-01 | [Project](https://github.com/google-research/google-research/tree/master/socraticmodels) |  |
<!--  
| Reasoning w/o robotics |
| [**Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents**](https://arxiv.org/abs/2201.07207) | ICML 2022 | 2022-01-18 | [Github](https://github.com/huangwl18/language-planner) | |
| [**Large Language Models as Commonsense Knowledge for Large-Scale Task Planning**](https://arxiv.org/abs/2305.14078) | NeurIPS 2023 | 2023-05-23 | [Github](https://github.com/llm-mcts/llm-mcts) | |
| [**LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models**](https://arxiv.org/abs/2212.04088) | ICCV 2023 | 2022-12-08 | [Github](https://github.com/OSU-NLP-Group/LLM-Planner/) | |
| [**ReAct: Synergizing Reasoning and Acting in Language Models**](https://arxiv.org/abs/2210.03629) | ICLR 2023 | 2022-10-06 | [Github](https://github.com/ysymyth/ReAct) | | 
| [**Reasoning with Language Model is Planning with World Model**](https://arxiv.org/abs/2210.03629) | EMNLP 2023 | 2023-05-24 | [Github](https://github.com/maitrix-org/llm-reasoners) | | 
| [**Dynamic Planning with a LLM**](https://arxiv.org/abs/2308.06391) | arXiv | 2023-08-11 | [Github](https://github.com/itl-ed/llm-dp) | | 
| [**SMART-LLM: Smart Multi-Agent Robot Task Planning using Large Language Models**](https://arxiv.org/abs/2309.10062) | arXiv | 2023-09-18 | [Github](https://github.com/SMARTlab-Purdue/SMART-LLM) | | 
-->

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.17-Generalization ******* -->
### Generalization 
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Generalization with Benchmarks_ |
| [**A Taxonomy for Evaluating Generalist Robot Policies**](https://arxiv.org/abs/2503.01238) | arXiv | 2024-03-03 | [Project](https://stargen-taxonomy.github.io/) |  |
| _Generalization using Data_ |
| [**Mirage: Cross-Embodiment Zero-Shot Policy Transfer with Cross-Painting**](https://arxiv.org/abs/2402.19249) | RSS 2024 | 2024-02-29 | ![Star](https://img.shields.io/github/stars/BerkeleyAutomation/mirage?style=social&label=Star) [Github](https://github.com/BerkeleyAutomation/mirage) |  |
| [**Decomposing the Generalization Gap in Imitation Learning for Visual Robotic Manipulation**](https://arxiv.org/abs/2307.03659) | ICRA 2024 | 2024-02-29 | ![Star](https://img.shields.io/github/stars/RLAgent/factor-world?style=social&label=Star) [Github](https://github.com/RLAgent/factor-world) |  
| _Compositional Generalization_ |
| [**Policy Architectures for Compositional Generalization in Control**](https://arxiv.org/abs/2203.05960) | NeurIPSW 2022 | 2022-03-10 | ![Star](https://img.shields.io/github/stars/facebookresearch/entity-factored-rl?style=social&label=Star) [Github](https://github.com/facebookresearch/entity-factored-rl) | Compositional Generalization |
| [PROGRAMPORT: **Programmatically Grounded, Compositionally Generalizable Robotic Manipulation**](https://arxiv.org/abs/2304.13826) | ICLR 2023 | 2023-04-26 | [Project](https://progport.github.io/) | Compositional Generalization |
| [**Efficient Data Collection for Robotic Manipulation via Compositional Generalization**](https://arxiv.org/abs/2403.05110) | RSS 2024 | 2024-03-08 | [Project](https://iliad.stanford.edu/robot-data-comp/) | Compositional Generalization |
| _Sim2Real or real2real Generalization_ |
| [**Real2Render2Real: Scaling Robot Data Without Dynamics Simulation or Robot Hardware**](https://arxiv.org/abs/2505.09601) | arXiv | 2025-05-14 | [Project](https://real2render2real.com/) |  |
| [**X-Sim: Cross-Embodiment Learning via Real-to-Sim-to-Real**](http://arxiv.org/abs/2505.07096) | arXiv | 2025-05-11 | ![Star](https://img.shields.io/github/stars/portal-cornell/X-Sim?style=social&label=Star) [Github](https://github.com/portal-cornell/X-Sim) |  |
| [**Sim-and-Real Co-Training: A Simple Recipe for Vision-Based Robotic Manipulation**](https://arxiv.org/abs/2405.10020) | arXiv | 2025-03-31 | [Project](https://co-training.github.io/) |  |
| [**Natural Language Can Help Bridge the Sim2Real Gap**](https://arxiv.org/abs/2405.10020) | RSS 2024 | 2024-05-16 | ![Star](https://img.shields.io/github/stars/UT-Austin-RobIn/lang4sim2real?style=social&label=Star) [Github](https://github.com/UT-Austin-RobIn/lang4sim2real) |  |
| [RialTo: **Reconciling Reality through Simulation: A Real-to-Sim-to-Real Approach for Robust Manipulation**](https://arxiv.org/abs/2403.03949) | RSS 2024 | 2024-03-06 | ![Star](https://img.shields.io/github/stars/real-to-sim-to-real/RialToPolicyLearning?style=social&label=Star) [Github](https://github.com/real-to-sim-to-real/RialToPolicyLearning) |  |
| [Domain Randomization: **Sim-to-Real Transfer of Robotic Control with Dynamics Randomization**](https://arxiv.org/abs/1710.06537) | ICRA 2018 | 2017-10-18 |  |  |
| _Disentangled Representation Learning_ |
| [**Zero-Shot Visual Generalization in Robot Manipulation**](https://arxiv.org/abs/2505.11719) | arXiv | 2022-05-16 | [Project](https://sites.google.com/view/vis-gen-robotics/home) |  |
| [**Merging and Disentangling Views in Visual Reinforcement Learning for Robotic Manipulation**](https://arxiv.org/abs/2505.04619) | arXiv | 2025-05-07 | ![Star](https://img.shields.io/github/stars/aalmuzairee/mad?style=social&label=Star) [Github](https://github.com/aalmuzairee/mad) |  |
| [**Disentangled Object-Centric Image Representation for Robotic Manipulation**](https://arxiv.org/abs/2503.11565) | arXiv | 2025-03-14 | - |  |
| _Generalization for Long-horizon and Complex Task_ |
| [**BT-TL-DMPs: A Novel Robot TAMP Framework Combining Behavior Tree, Temporal Logic and Dynamical Movement Primitives**](https://arxiv.org/abs/2507.14582) | arXiv | 2025-07-19 | [Project](https://nkrobotlab.github.io/BT-TL-DMPs/) | |
| [**Bootstrapping Imitation Learning for Long-horizon Manipulation via Hierarchical Data Collection Space**](https://arxiv.org/abs/2505.17389) | arXiv | 2025-05-23 | [Project](https://hd-space-robotics.github.io/) | |
| [**RoboHorizon: An LLM-Assisted Multi-View World Model for Long-Horizon Robotic Manipulation**](https://arxiv.org/abs/2501.06605) | arXiv | 2025-01-11 | - | |
| [ManipGen: **Local Policies Enable Zero-shot Long-horizon Manipulation**](https://arxiv.org/abs/2410.22332) | CoRLW 2024 | 2024-10-29 | [Project](https://mihdalal.github.io/manipgen/) | |
| [TBBF: **A Backbone for Long-Horizon Robot Task Understanding**](https://arxiv.org/abs/2408.01334) | RA-L 2025 | 2024-08-02 | [Project](https://sites.google.com/view/therbligsbasedbackbone/home) | |
| [**STAP: Sequencing Task-Agnostic Policies**](https://arxiv.org/abs/2210.12250) | ICRA 2023 | 2022-10-21 | ![Star](https://img.shields.io/github/stars/agiachris/STAP?style=social&label=Star) [Github](https://github.com/agiachris/STAP) |  |
| [BOSS: **Bootstrap Your Own Skills: Learning to Solve New Tasks with Large Language Model Guidance**](https://arxiv.org/abs/2310.10021) | CoRL 2023 | 2023-12-16 | ![Star](https://img.shields.io/github/stars/clvrai/boss?style=social&label=Star) [Github](https://github.com/clvrai/boss) | Skill Bootstrapping |
| [BLADE: **Learning Compositional Behaviors from Demonstration and Language**](https://openreview.net/pdf?id=fR1rCXjCQX) | CoRL 2024 | 2024 | [Project](https://blade-bot.github.io/) | IL, RepL, Poliy Head, Few-Shot Policy Adaptation |
| [PALO: **Policy Adaptation via Language Optimization: Decomposing Tasks for Few-Shot Imitation**](https://arxiv.org/abs/2408.16228) | CoRL 2024 | 2024-08-29 | ![Star](https://img.shields.io/github/stars/vivekmyers/palo?style=social&label=Star) [Github](https://github.com/vivekmyers/palo) | Fine-grained Atom Action |
| _Lifelong Learning_ |
| [**Dynamic Mixture of Progressive Parameter-Efficient Expert Library for Lifelong Robot Learning**](https://arxiv.org/abs/2506.05985) | arXiv | 2025-06-06 | - |  |
| [**Think Small, Act Big: Primitive Prompt Learning for Lifelong Robot Manipulation**](https://arxiv.org/abs/2504.00420) | CVPR 2025 | 2025-04-01 | - |  |
| _Few-shot_ |
| [**Few-Shot Vision-Language Action-Incremental Policy Learning**](https://arxiv.org/abs/2504.15517) | arXiv | 2025-04-22 | ![Star](https://img.shields.io/github/stars/codeshop715/FSAIL?style=social&label=Star) [Github](https://github.com/codeshop715/FSAIL) |  |
| [**You Only Teach Once: Learn One-Shot Bimanual Robotic Manipulation from Video Demonstrations**](https://arxiv.org/abs/2501.14208) | arXiv | 2025-01-24 | ![Star](https://img.shields.io/github/stars/hnuzhy/YOTO?style=social&label=Star) [Github](https://github.com/hnuzhy/YOTO) |  |
| [**Learning Generalizable 3D Manipulation With 10 Demonstrations**](https://arxiv.org/abs/2411.10203) | arXiv | 2024-11-15 | ![Star](https://img.shields.io/github/stars/renyu2016/Generalized-3D-Manipulation?style=social&label=Star) [Github](https://github.com/renyu2016/Generalized-3D-Manipulation) |  |
| _Incremental Learning_ |
| [**iManip: Skill-Incremental Learning for Robotic Manipulation**](https://arxiv.org/abs/2503.07087) | arXiv | 2025-03-10 | - |  |
|  _Test-Time Adaptation_ |
| [**Adapting by Analogy: OOD Generalization of Visuomotor Policies via Functional Correspondence**](https://arxiv.org/abs/2506.12678) | arXiv | 2025-06-15 | - |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.18-Generalization ******* -->
### Generalist
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Generalist with Different Embodiment Types_ |
| [**RoboOS: A Hierarchical Embodied Framework for Cross-Embodiment and Multi-Agent Collaboration**](https://arxiv.org/abs/2505.03673) | arXiv | 2025-05-06 | ![Star](https://img.shields.io/github/stars/FlagOpen/RoboOS?style=social&label=Star) [Github](https://github.com/FlagOpen/RoboOS) | Cross-Embodied |
| [CrossFormer: **Scaling Cross-Embodied Learning: One Policy for Manipulation, Navigation, Locomotion and Aviation**](https://arxiv.org/abs/2408.11812) | CoRL 2024 | 2024-08-21 | ![Star](https://img.shields.io/github/stars/rail-berkeley/crossformer?style=social&label=Star) [Github](https://github.com/rail-berkeley/crossformer) | Cross-Embodied |
| [ARIO: **All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents**](https://arxiv.org/abs/2408.10899) | arXiv | 2024-08-20 | [Project](https://imaei.github.io/project_pages/ario/) | Cross-Embodied |
| [HPT: **Scaling Proprioceptive-Visual Learning with Heterogeneous Pre-trained Transformers**](https://arxiv.org/abs/2409.20537) | NeurIPS 2024 | 2024-09-30 | ![Star](https://img.shields.io/github/stars/liruiw/HPT?style=social&label=Star) [Github](https://github.com/liruiw/HPT) |  |
| _Generalist in Different Embodied Tasks_|
| [LEO: **An Embodied Generalist Agent in 3D World**](https://arxiv.org/abs/2311.12871) | ICML 2024 | 2023-11-18 | ![Star](https://img.shields.io/github/stars/embodied-generalist/embodied-generalist?style=social&label=Star) [Github](https://github.com/embodied-generalist/embodied-generalist) |  |
| _Manipulation Generalist_|
| [**Beyond Sight: Finetuning Generalist Robot Policies with Heterogeneous Sensors via Language Grounding**](https://arxiv.org/abs/2501.04693) | arXiv | 2025-01-08 | ![Star](https://img.shields.io/github/stars/fuse-model/FuSe?style=social&label=Star) [Github](https://github.com/fuse-model/FuSe) |
| [**RLDG: Robotic Generalist Policy Distillation via Reinforcement Learning**](https://arxiv.org/abs/2412.09858) | arXiv | 2024-12-13 | [Project](https://generalist-distillation.github.io/) |  |
| [**RoboMM: All-in-One Multimodal Large Model for Robotic Manipulation**](https://arxiv.org/abs/2412.07215) | arXiv | 2024-12-10 | ![Star](https://img.shields.io/github/stars/RoboUniview/RoboMM?style=social&label=Star) [Github](https://github.com/RoboUniview/RoboMM) |  |
| [**Effective Tuning Strategies for Generalist Robot Manipulation Policies**](https://arxiv.org/abs/2410.01220) | arXiv | 2024-10-02 | - | |
| [**Octo: An Open-Source Generalist Robot Policy**](https://arxiv.org/abs/2405.12213) | RSS 2024 | 2024-05-20 | ![Star](https://img.shields.io/github/stars/octo-models/octo?style=social&label=Star) [Github](https://github.com/octo-models/octo) | |
| [V-GPS: **Steering Your Generalists: Improving Robotic Foundation Models via Value Guidance**](https://arxiv.org/abs/2410.13816) | CoRL 2024 | 2024-10-17 | [Project](https://nakamotoo.github.io/V-GPS/index.html) |  |
| [**Open X-Embodiment: Robotic Learning Datasets and RT-X Models**](https://arxiv.org/abs/2310.08864) | ICRA 2024 | 2023-10-13 | ![Star](https://img.shields.io/github/stars/google-deepmind/open_x_embodiment?style=social&label=Star)  [Github](https://github.com/google-deepmind/open_x_embodiment) | |
| [**RoboAgent: Generalization and Efficiency in Robot Manipulation via Semantic Augmentations and Action Chunking**](https://arxiv.org/abs/2309.01918) | ICRA 2024 | 2023-09-05 | ![Star](https://img.shields.io/github/stars/robopen/roboagent?style=social&label=Star) [Github](https://github.com/robopen/roboagent) | |
| [Maniwhere: **Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning**](https://arxiv.org/abs/2407.15815) | CoRL 2024 | 2024-07-22 | [Project](https://gemcollector.github.io/maniwhere/) |  |
| [**CAGE: Causal Attention Enables Data-Efficient Generalizable Robotic Manipulation**](https://arxiv.org/abs/2407.15815) | arXiv | 2024-10-19 | [Project](https://cage-policy.github.io/) |  |
| [**Robot Utility Models: General Policies for Zero-Shot Deployment in New Environments**](https://arxiv.org/abs/2409.05865) | arXiv | 2024-09-09 | [Github](https://github.com/haritheja-e/robot-utility-models/) |  |
| More for [VLAs](#vision-language-action-models) |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.19-Human-Robot Interaction and Collaboration ******* -->
### Human-Robot Interaction and Collaboration
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Maximizing Alignment with Minimal Feedback: Efficiently Learning Rewards for Visuomotor Robot Policy Alignment**](https://arxiv.org/abs/2412.04835) | arXiv | 2024-12-06 | [Project](https://sites.google.com/berkeley.edu/rapl) |  |
| [**Vocal Sandbox: Continual Learning and Adaptation for Situated Human-Robot Collaboration**](https://openreview.net/pdf?id=ypaYtV1CoG) | CoRL 2024 | 2024-09-06 | [Project](https://vocal-sandbox.github.io/) |  |
| [**APRICOT: Active Preference Learning and Constraint-Aware Task Planning with LLMs**](https://openreview.net/pdf?id=nQslM6f7dW) | CoRL 2024 | - | [Project](https://portal-cornell.github.io/apricot/) |  |
| [**Text2Interaction: Establishing Safe and Preferable Human-Robot Interaction**](https://arxiv.org/abs/2408.06105) | CoRL 2024 | 2024-08-12 | ![Star](https://img.shields.io/github/stars/JakobThumm/text2interaction?style=social&label=Star) [Github](https://github.com/JakobThumm/text2interaction) |  |
| [**GenH2R: Learning Generalizable Human-to-Robot Handover via Scalable Simulation, Demonstration, and Imitation**](https://arxiv.org/abs/2401.00929) | CVPR 2024 | 2024-01-01  | ![Star](https://img.shields.io/github/stars/chenjy2003/genh2r?style=social&label=Star) [Github](https://github.com/chenjy2003/genh2r)  |
| [KNOWNO: **Robots That Ask For Help: Uncertainty Alignment for Large Language Model Planners**](https://arxiv.org/abs/2307.01928) | CoRL 2023 | 2023-07-04 | [Github](https://github.com/google-research/google-research/tree/master/language_model_uncertainty) | |
| [LILAC: **Yell At Your Robot: Improving On-the-Fly from Language Corrections**](https://arxiv.org/abs/2403.12910) | arXiv | 2024-03-19 | ![Star](https://img.shields.io/github/stars/yay-robot/yay_robot?style=social&label=Star) [Github](https://github.com/yay-robot/yay_robot) | |
| [YAY Robot: **"No, to the Right" -- Online Language Corrections for Robotic Manipulation via Shared Autonomy**](https://arxiv.org/abs/2301.02555) | HRI 2023 | 2023-01-06 | ![Star](https://img.shields.io/github/stars/Stanford-ILIAD/lilac?style=social&label=Star) [Github](https://github.com/Stanford-ILIAD/lilac) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


<!-- ******* 1.3.23-Dexterous Manipulation ******* -->
### Dexterous Manipulation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   |  
|:--------|:--------:|:--------:|:--------:|
| _Non-learning Control_ |
| [**Dexterous manipulation using both palm and fingers**](https://ieeexplore.ieee.org/document/6907059/) | ICRA 2014 | 2014-05 | - |
| [**On Dexterity and Dexterous Manipulation**](https://ieeexplore.ieee.org/document/6088576) | ICAR 2011 | 2011-06 | - |
| [**Dexterous Manipulation by Rolling and Finger Gaiting**](https://ieeexplore.ieee.org/abstract/document/677060/) | ICAR 1998 | 1998-05 | - |
| [**Kinematic and Force Analysis of Articulated Mechanical Hands**](https://asmedigitalcollection.asme.org/mechanicaldesign/article-abstract/105/1/35/433931/Kinematic-and-Force-Analysis-of-Articulated) | JMTAD 1998 | 1983-01 | - |
| _RL_ |
| [**DexMachina: Functional Retargeting for Bimanual Dexterous Manipulation**](https://arxiv.org/abs/2505.24853) | arXiv | 2025-05-30 | ![Star](https://img.shields.io/github/stars/MandiZhao/dexmachina?style=social&label=Star) [Code](https://github.com/MandiZhao/dexmachina) |
| [**DORA: Object Affordance-Guided Reinforcement Learning for Dexterous Robotic Manipulation**](https://arxiv.org/abs/2505.14819) | arXiv | 2025-05-20 | [Project](https://sites.google.com/view/dora-manip) |
| [**Sequential Dexterity: Chaining Dexterous Policies for Long-Horizon Manipulation**](https://arxiv.org/abs/2309.00987) | CoRL 2023 | 2023-09-02 | ![Star](https://img.shields.io/github/stars/sequential-dexterity/SeqDex?style=social&label=Star) [Github](https://github.com/sequential-dexterity/SeqDex) | |
| [**Learning Dexterous Manipulation from Exemplar Object Trajectories and Pre-Grasps**](https://arxiv.org/abs/2209.11221) | ICRA 2023 | 2022-09-22 | ![Star](https://img.shields.io/github/stars/facebookresearch/TCDM?style=social&label=Star) [Code](https://github.com/facebookresearch/TCDM) |
| [**DexPoint: Generalizable Point Cloud Reinforcement Learning for Sim-to-Real Dexterous Manipulation**](https://arxiv.org/abs/2211.09423) | CoRL 2022 | 2022-11-17 | ![Star](https://img.shields.io/github/stars/yzqin/dexpoint-release?style=social&label=Star) [Code](https://github.com/yzqin/dexpoint-release) |
| [**Deep dynamics models for learning dexterous manipulation**](https://arxiv.org/abs/1909.11652) | CoRL 2020 | 2019-09-25 | ![Star](https://img.shields.io/github/stars/google-research/pddm?style=social&label=Star) [Code](https://github.com/google-research/pddm) |
| [**Dexterous manipulation with deep reinforcement learning: Efficient, general, and low-cost**](https://arxiv.org/abs/1810.06045) | ICRA 2019 | 2018-10-14 | [Project](https://sites.google.com/view/deeprl-handmanipulation) |
| _IL_|
| [**CordViP: Correspondence-based Visuomotor Policy for Dexterous Manipulation in Real-World**](https://arxiv.org/abs/2502.08449) | RSS 2025 | 2025-02-12 | ![Star](https://img.shields.io/github/stars/xuanxuanzzzii/cordvip?style=social&label=Star) [Code](https://github.com/xuanxuanzzzii/cordvip) |
| [**DexHandDiff: Interaction-aware Diffusion Planning for Adaptive Dexterous Manipulation**](https://arxiv.org/abs/2402.14795) | CVPR 2025 | 2024-11-27 | ![Star](https://img.shields.io/github/stars/Liang-ZX/DexHandDiff?style=social&label=Star) [Code](https://github.com/Liang-ZX/DexHandDiff) |
| [**Bunny-VisionPro: Real-Time Bimanual Dexterous Teleoperation for Imitation Learning**](https://arxiv.org/abs/2407.03162) | arXiv | 2024-07-03 | ![Star](https://img.shields.io/github/stars/Dingry/BunnyVisionPro?style=social&label=Star) [Github](https://github.com/Dingry/BunnyVisionPro) |
| [**CyberDemo: Augmenting Simulated Human Demonstration for Real-World Dexterous Manipulation**](https://arxiv.org/abs/2402.14795) | CVPR 2024 | 2024-02-22 | ![Star](https://img.shields.io/github/stars/zerchen/vividex_mujoco?style=social&label=Star) [Code](https://github.com/zerchen/vividex_mujoco) |
| [**State-Only Imitation Learning for Dexterous Manipulation**](https://arxiv.org/abs/2004.04650) | IROS 2021 | 2020-04-07 | [Project](https://people.eecs.berkeley.edu/~ilija/soil/) |
| [**Learning Dexterous Manipulation Policies from Experience and Imitation**](https://arxiv.org/abs/1611.05095) | arXiv | 2016-11-15 | - |
| _RL+IL_ |
| [**ViViDex: Learning Vision-based Dexterous Manipulation from Human Videos**](https://arxiv.org/abs/2404.15709) | ICRA 2025 | 2024-04-24 | ![Star](https://img.shields.io/github/stars/wang59695487/hand_teleop_real_sim_mix_adr?style=social&label=Star) [Code](https://github.com/wang59695487/hand_teleop_real_sim_mix_adr) |
| [**Object-Centric Dexterous Manipulation from Human Motion Data**](https://arxiv.org/abs/2411.04005) | CoRL 2024 | 2024-11-06 | ![Star](https://img.shields.io/github/stars/cypypccpy/ObjDexEnvs?style=social&label=Star) [Code](https://github.com/cypypccpy/ObjDexEnvs) |
| [**REBOOT: Reuse Data for Bootstrapping Efficient Real-World Dexterous Manipulation**](https://arxiv.org/abs/2309.03322) | CORL 2023 | 2023-09-06 | [Project](https://sites.google.com/view/reboot-dexterous) |
| [**Dexterous Imitation Made Easy: A Learning-Based Framework for Efficient Dexterous Manipulation**](https://arxiv.org/abs/2203.13251) | ICRA 2023 | 2023-03-24 | ![Star](https://img.shields.io/github/stars/NYU-robot-learning/DIME-Models?style=social&label=Star) [Code](https://github.com/NYU-robot-learning/DIME-Models) |
| _VLA_ |
| [**Being-H0: Vision-Language-Action Pretraining from Large-Scale Human Videos**](https://arxiv.org/abs/2507.15597) | arXiv | 2025-07-21 | ![Star](https://img.shields.io/github/stars/BeingBeyond/Being-H0?style=social&label=Star) [Code](https://github.com/BeingBeyond/Being-H0) |
| [**A Careful Examination of Large Behavior Models for Multitask Dexterous Manipulation**](https://arxiv.org/abs/2507.05331) | arXiv | 2025-07-07 | [Project](https://toyotaresearchinstitute.github.io/lbm1/) |
| [**Object-Focus Actor for Data-efficient Robot Generalization Dexterous Manipulation**](https://arxiv.org/abs/2505.15098) | arXiv | 2025-05-21 | ![Star](https://img.shields.io/github/stars/Louis-ZhangLe/BRMData?style=social&label=Star) [Code](https://github.com/Louis-ZhangLe/BRMData) |
| _Addordance_ |
| [**MAPLE: Encoding Dexterous Robotic Manipulation Priors Learned From Egocentric Videos**](https://arxiv.org/abs/2504.06084) | arXiv | 2025-04-08 | ![Star](https://img.shields.io/github/stars/algvr/maple?style=social&label=Star) [Code](https://github.com/algvr/maple) |
| [**Dexterous Functional Grasping**](https://arxiv.org/abs/2312.02975) | CoRL 2023 | 2023-12-05 | [Project](https://dexfunc.github.io/) |
| [**DEFT: Dexterous Fine-Tuning for Real-World Hand Policies**](https://arxiv.org/abs/2310.19797) | CoRL 2023 | 2023-10-30 | [Project](https://dexterous-finetuning.github.io/) |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.23 - Soft Robotic Manipulation ******* -->
### Soft Robotic Manipulation
|  Title  |   Venue  |   Date   |   Code   |  
|:--------|:--------:|:--------:|:--------:|
| _Non-learning Control_|
| [**Multi-segment Soft Robot Control via Deep Koopman-based Model Predictive Control**](https://arxiv.org/abs/2505.003548) | arXiv | 2025-05-01 | [Project](https://pinkmoon-io.github.io/DKMPC/) |
| [**Discrete Cosserat Static Model-Based Control of Soft Manipulator**](https://ieeexplore.ieee.org/document/10041751) | RA-L 2023 | 2023-02-09 | - |
| [**Adaptive Dynamic Sliding Mode Control of Soft Continuum Manipulators**](https://arxiv.org/abs/2109.11388) | ICRA 2022 | 2021-09-23 | - |
| [**Dynamic Control of Multisection Three-Dimensional Continuum Manipulators Based on Virtual Discrete-Jointed Robot Models**](https://ieeexplore.ieee.org/document/9107505) | RA-L 2022 | 2021-10-19 | - |
| [**Robust Control of a Multi-Axis Shape Memory Alloy-Driven Soft Manipulator**](https://arxiv.org/abs/2110.10022) | TMECH 2020 | 2020-06-03 | - |
| [**Modeling and Control of Soft Robots Using the Koopman Operator and Model Predictive Control**](https://arxiv.org/abs/1902.02827) | RSS 2019 | 2019-02-07 | - |
| [**Vision-Based Online Learning Kinematic Control for Soft Robots Using Local Gaussian Process Regression**](https://ieeexplore.ieee.org/document/8616838) | RA-L 2019 | 2019-01-17 | - |
| [**Kinematics for Multisection Continuum Robots**](https://ieeexplore.ieee.org/document/1588999) | T-RO 2006 | 2006-02-06 | - |
| _Non-learning Control + DL Models_|
| [**A Data-efficient Neural ODE Framework for Optimal Control of Soft Manipulators**](https://openreview.net/forum?id=PalhNjBJqv) | CoRL 2023 | 2023-08-31 | ![Star](https://img.shields.io/github/stars/MohammadKasaei/SoftRobotSimulator?style=social&label=Star) [Code](https://github.com/MohammadKasaei/SoftRobotSimulator) |
| [**Stable Open Loop Control of Soft Robotic Manipulators**](https://ieeexplore.ieee.org/document/8268050/) | RA-L 2018 | 2018-01-24 | - |
| [**Closed-Loop Dynamic Control of a Soft Manipulator Using Deep Reinforcement Learning**](https://ieeexplore.ieee.org/document/9697385) | BIOINSPIR BIOMIM 2017 | 2017-10-06 | - |
| _RL_ |
| [**Continual Policy Distillation of Reinforcement Learning-based Controllers for Soft Robotic In-Hand Manipulation**](https://arxiv.org/abs/2404.04219) | RoboSoft 2024 | 2024-04-05 | - |
| [**A Cable-Actuated Soft Manipulator for Dexterous Grasping Based on Deep Reinforcement Learning**](https://onlinelibrary.wiley.com/doi/abs/10.1002/aisy.202400112) | Adv. Intell. Syst. 2024 | 2024-08-29 | - |
| [**RL-Based Adaptive Controller for High Precision Reaching in a Soft Robot Arm**](https://ieeexplore.ieee.org/document/10478622) | T-RO 2024 | 2024-03-26 | - |
| [**SofToss: Learning to Throw Objects With a Soft Robot**](https://ieeexplore.ieee.org/abstract/document/10268286) | RAM 2023 | 2023-09-29 | - |
| [**Towards Adaptive Continuous Control of Soft Robotic Manipulator using Reinforcement Learning**](https://ieeexplore.ieee.org/document/9981335) | IROS 2022 | 2022-12-26 | - |
| [**Closed-Loop Dynamic Control of a Soft Manipulator Using Deep Reinforcement Learning**](https://ieeexplore.ieee.org/document/9697385) | RA-L 2022 | 2022-01-31 | - |
| [**Model-Based Reinforcement Learning for Closed-Loop Dynamic Control of Soft Robotic Manipulators**](https://ieeexplore.ieee.org/document/8531756) | T-RO 2018 | 2018-12-12 | - |
| [**Model-free Control for Soft Manipulators based on Reinforcement Learning**](https://ieeexplore.ieee.org/document/8206123) | IROS 2017 | 2017-12-14 | - |
| _IL_ |
| [**KineSoft: Learning Proprioceptive Manipulation Policies with Soft Robot Hands**](https://arxiv.org/abs/2503.01078) | arXiv | 2025-03-03 | [Project](https://kinesoft-policy.github.io/) |
| [**Soft DAgger: Sample-Efficient Imitation Learning for Control of Soft Robots**](https://www.mdpi.com/1424-8220/23/19/8278) | Sensors 2023 | 2023-10-06 | - |
| _RL+IL_ |
| [**Sensor-Space Based Robust Kinematic Control of Redundant Soft Manipulator by Learning**](https://arxiv.org/abs/2507.16842) | arXiv | 2025-07-19 | - |
| _Other Learning-based Methods_ |
| [**Toward the Use of Proxies for Efficient Learning Manipulation and Locomotion Strategies on Soft Robots**](https://arxiv.org/abs/2310.17029) | RA-L 2023 | 2023-10-25 | - |
| [**Controlling Soft Robotic Arms Using Continual Learning**](https://ieeexplore.ieee.org/document/9730039) | RA-L 2022 | 2022-03-08 | - |
| [**Learning Closed Loop Kinematic Controllers for Continuum Manipulators in Unstructured Environments**](https://www.liebertpub.com/doi/abs/10.1089/soro.2016.0051) | Soft Robot 2017 | 2017-09-01 | - |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.23-Deformable Object Manipulation ******* -->
### Deformable Object Manipulation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   |  
|:--------|:--------:|:--------:|:--------:|
| _Non-learning Control_ |
| [**Model Predictive Control for Dynamic Cloth Manipulation: Parameter Learning and Experimental Validation**](https://arxiv.org/abs/2209.05798) | TCST 2024 | 2022-09-13 | - |
| [**Manipulating Deformable Objects by Interleaving Prediction, Planning, and Control**](https://arxiv.org/abs/2001.09950) | IJRR 2020 | 2020-01-27 | - |
| [**Parametrized Shape Models for Clothing**](https://ieeexplore.ieee.org/abstract/document/5980453/) | ICRA 2011 | 2011-05 | - |
| [**Manipulation Planning for Deformable Linear Objects**](https://ieeexplore.ieee.org/document/4359263) | T-RO 2007 | 2007-12 | - |
| _RL_ |
| [**SoftGPT: Learn Goal-oriented Soft Object Manipulation Skills by Generative Pre-trained Heterogeneous Graph Transformer**](https://arxiv.org/abs/2306.12677) | IROS 2023 | 2023-06-22 | - |
| [**Sim-to-Real Reinforcement Learning for Deformable Object Manipulation**](https://arxiv.org/abs/1806.07851) | CoRL 2018 | 2018-06-20 | ![Star](https://img.shields.io/github/stars/JanMatas/Rainbow_ddpg?style=social&label=Star) [Code](https://github.com/JanMatas/Rainbow_ddpg) |
| _IL_ |
| [**Movement Primitive Diffusion: Learning Gentle Robotic Manipulation of Deformable Objects**](https://arxiv.org/abs/2312.10008) | RA-L 2024 | 2023-12-15 | ![Star](https://img.shields.io/github/stars/ScheiklP/movement-primitive-diffusion?style=social&label=Star) [Code](https://github.com/ScheiklP/movement-primitive-diffusion) |
| [**DexDeform: Dexterous Deformable Object Manipulation with Human Demonstrations and Differentiable Physics**](https://arxiv.org/abs/2304.03223) | ICLR 2023 | 2023-04-27 | ![Star](https://img.shields.io/github/stars/sizhe-li/DexDeform?style=social&label=Star) [Code](https://github.com/sizhe-li/DexDeform) |
| _RL+IL_ |
| [**Learning Deformable Object Manipulation from Expert Demonstrations**](https://arxiv.org/abs/2207.10148) | RA-L 2022 | 2022-07-20 | ![Star](https://img.shields.io/github/stars/uscresl/dmfd?style=social&label=Star) [Code](https://github.com/uscresl/dmfd) |
| _3D Representations_ |
| [**DoughNet: A Visual Predictive Model for Topological Manipulation of Deformable Objects**](https://arxiv.org/abs/2404.12524) | ECCV 2024 | 2024-04-18 | ![Star](https://img.shields.io/github/stars/dornik/doughnet?style=social&label=Star) [Code](https://github.com/dornik/doughnet) |
| [**Interactive Perception for Deformable Object Manipulation**](https://arxiv.org/abs/2403.05177) | RA-L 2024 | 2024-03-08 | - |
| [**DeformNet: Latent Space Modeling and Dynamics Prediction for Deformable Object Manipulation**](https://arxiv.org/abs/2402.07648) | ICRA 2024 | 2024-02-12 | - |
| [**DeformGS: Scene Flow in Highly Deformable Scenes for Deformable Object Manipulation**](https://arxiv.org/abs/2312.00583) | WAFR 2024 | 2023-12-30 | ![Star](https://img.shields.io/github/stars/momentum-robotics-lab/deformgs?style=social&label=Star) [Code](https://github.com/momentum-robotics-lab/deformgs) |
| _Addordance_ |
| [**Learning Efficient Robotic Garment Manipulation with Standardization**](https://arxiv.org/abs/2506.22769) | ICML 2025 | 2025-06-28 | [Project](https://hellohaia.github.io/APS/) |
| [**Learning Language-Conditioned Deformable Object Manipulation with Graph Dynamics**](https://arxiv.org/abs/2303.01310) | ICRA 2024 | 2023-03-02 | [Project](https://hellohaia.github.io/APS/) |
| [**Learning Foresightful Dense Visual Affordance for Deformable Object Manipulation**](https://arxiv.org/abs/2303.11057) | ICCV 2023 | 2023-03-20 | ![Star](https://img.shields.io/github/stars/TritiumR/DeformableAffordance?style=social&label=Star) [Code](https://github.com/TritiumR/DeformableAffordance) |
| [**3-D Deformable Object Manipulation Using Deep Neural Networks**](https://ieeexplore.ieee.org/document/8769898) | RA-L 2019 | 2019-07-23 | [Project](https://sites.google.com/view/mso-deep) |
| _Estimating Physical Properties_ |
| [**Deformable Linear Objects Manipulation With Online Model Parameters Estimation**](https://ieeexplore.ieee.org/document/10412116) | RA-L 2024 | 2024-01-24 | - |
| [**GenDOM: Generalizable One-shot Deformable Object Manipulation with Parameter-Aware Policy**](https://arxiv.org/abs/2309.09051) | ICRA 2024 | 2023-09-16 | ![Star](https://img.shields.io/github/stars/Kuroki1931/UniDOM?style=social&label=Star) [Code](https://github.com/Kuroki1931/UniDOM) |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.21-Mobile Manipulation ******* -->
### Mobile Manipulation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Robot Design_ |
| [**Mobile ALOHA: Learning Bimanual Mobile Manipulation with Low-Cost Whole-Body Teleoperation**](https://arxiv.org/abs/2401.02117) | CoRL 2024 | 2024-01-04 | ![Star](https://img.shields.io/github/stars/MarkFzp/mobile-aloha?style=social&label=Star) [Github](https://github.com/MarkFzp/mobile-aloha) |
| [**Mobile Manipulation and Mobility as Manipulation – Design and Algorithms of RoboSimian**](https://journals.sagepub.com/doi/abs/10.1177/02783640022067977) | JFR 2015 | 2015-12 | - |
| [**Development and Control of a Holonomic Mobile Robot for Mobile Manipulation Tasks**](https://journals.sagepub.com/doi/abs/10.1177/02783640022067977) | IJRR 2000 | 2000-11 | - |
| _Non-learning Control_ |
| [**An Architecture for Reactive Mobile Manipulation On-The-Move**](https://arxiv.org/abs/2212.06991) | ICRA 2023 | 2022-12-14 | ![Star](https://img.shields.io/github/stars/BenBurgessLimerick/ManipulationOnTheMove?style=social&label=Star) [Github](https://github.com/BenBurgessLimerick/ManipulationOnTheMove) |
| [**A Holistic Approach to Reactive Mobile Manipulation**](https://arxiv.org/abs/2109.04749) | RA-L 2022 | 2021-09-10 | ![Star](https://img.shields.io/github/stars/petercorke/robotics-toolbox-python?style=social&label=Star) [Github](https://github.com/petercorke/robotics-toolbox-python) |
| [**Perceptive Model Predictive Control for Continuous Mobile Manipulation**](https://ieeexplore.ieee.org/document/9145591) | RA-L 2020 | 2020-06-21 | ![Star](https://img.shields.io/github/stars/leggedrobotics/perceptive_mpc?style=social&label=Star) [Github](https://github.com/leggedrobotics/perceptive_mpc) |
| [**Mobile Manipulation Through An Assistive Home Robot**](https://ieeexplore.ieee.org/document/6385907) | IROS 2012 | 2012-12 | - |
| [**Mobile Manipulation in Unstructured Environments: Perception, Planning, and Execution**](https://ieeexplore.ieee.org/document/6213233) | RAM 2012 | 2012-06 | - |
| [**An Optimization Approach to Planning for Mobile Manipulation**](https://ieeexplore.ieee.org/abstract/document/4543365/) | ICRA 2008 | 2008-06 | - |
| _RL_ |
| [**Robi Butler: Multimodal Remote Interaction with a Household Robot Assistant**](https://arxiv.org/abs/2409.20548) | ICRA 2025 | 2024-09-30 | [Project](https://robibutler.github.io/) |
| [**Harmonic Mobile Manipulation**](https://arxiv.org/abs/2312.06639) | IROS 2024 | 2023-12-11 | ![Star](https://img.shields.io/github/stars/RchalYang/harmonic_mobile_manipulation?style=social&label=Star) [Github](https://github.com/RchalYang/harmonic_mobile_manipulation) |
| [Causal MoMa: **Causal Policy Gradient for Whole-Body Mobile Manipulation**](https://arxiv.org/abs/2305.04866) | RSS 2023 | 2023-05-04 | ![Star](https://img.shields.io/github/stars/JiahengHu/CausalMoMa?style=social&label=Star) [Github](https://github.com/JiahengHu/CausalMoMa) |
| [**Learning Kinematic Feasibility for Mobile Manipulation through Deep Reinforcement Learning**](https://arxiv.org/abs/2101.05325) | RA-L 2021 | 2021-01-13 | ![Star](https://img.shields.io/github/stars/robot-learning-freiburg/kinematic-feasibility-rl?style=social&label=Star) [Github](https://github.com/robot-learning-freiburg/kinematic-feasibility-rl) |
| [**Spatial Action Maps for Mobile Manipulation**](https://arxiv.org/abs/2004.09141) | RSS 2020 | 2020-04-20 | ![Star](https://img.shields.io/github/stars/jimmyyhwu/spatial-action-maps?style=social&label=Star) [Github](https://github.com/jimmyyhwu/spatial-action-maps) |
| [**Learning Mobile Manipulation through Deep Reinforcement Learning**](https://www.mdpi.com/1424-8220/20/3/939) | Sensors 2020 | 2020-02-10 | [Project](https://robibutler.github.io/) |
| _IL_ |
| [**Object-Centric Mobile Manipulation through SAM2-Guided Perception and Imitation Learning**](https://www.arxiv.org/abs/2507.10899) | arXiv | 2025-07-15 | - |
| [**HoMeR: Learning In-the-Wild Mobile Manipulation via Hybrid Imitation and Whole-Body Control**](https://arxiv.org/abs/2506.01185) | arXiv | 2025-06-01 | ![Star](https://img.shields.io/github/stars/priyasundaresan/homer?style=social&label=Star) [Github](https://github.com/priyasundaresan/homer) |
| [**Skill Transformer: A Monolithic Policy for Mobile Manipulation**](https://arxiv.org/abs/2308.09873) | ICCV 2023 | 2023-08-19 | ![Star](https://img.shields.io/github/stars/WhoKnowsssss/skill_transformer?style=social&label=Star) [Github](https://github.com/WhoKnowsssss/skill_transformer) |
| [**MOMA-Force: Visual-Force Imitation for Real-World Mobile Manipulation**](https://arxiv.org/abs/2308.03624) | IROS 2023 | 2023-08-07 | [Project](https://visual-force-imitation.github.io/) |
| _RL+IL_ |
| [**Adaptive Mobile Manipulation for Articulated Objects In the Open World**](https://arxiv.org/abs/2401.14403) | arXiv | 2024-01-25 | [Project](https://open-world-mobilemanip.github.io/) |
| _VLA_ |
| [**MoManipVLA: Transferring Vision-language-action Models for General Mobile Manipulation**](https://arxiv.org/abs/2503.13446) | CVPR 2025 | 2025-03-17 | [Project](https://gary3410.github.io/momanipVLA/) |
| _High-level Planner_ |
| [**Robi Butler: Multimodal Remote Interaction with a Household Robot Assistant**](https://arxiv.org/abs/2409.20548) | ICRA 2025 | 2024-09-30 | [Project](https://robibutler.github.io/) |
| [MoMa-LLM: **Language-Grounded Dynamic Scene Graphs for Interactive Object Search with Mobile Manipulation**](https://arxiv.org/abs/2403.08605) | RA-L 2024 | 2024-03-13 | [Project](https://github.com/robot-learning-freiburg/MoMa-LLM) |
| [**SayPlan: Grounding Large Language Models using 3D Scene Graphs for Scalable Robot Task Planning**](https://arxiv.org/abs/2307.06135) | CoRL 2023 | 2023-07-12 | [Project](https://sayplan.github.io/) |
| _3D Representations_ |
| [**TaMMa: Target-driven Multi-subscene Mobile Manipulation**](https://openreview.net/pdf?id=EiqQEsOMZt) | CoRL 2024 | 2024-09-06 | - |
| [**Active-Perceptive Motion Generation for Mobile Manipulation**](https://arxiv.org/abs/2310.00433) | ICRA 2024 | 2023-10-30 | ![Star](https://img.shields.io/github/stars/pearl-robot-lab/ActPerMoMa?style=social&label=Star) [Github](https://github.com/pearl-robot-lab/ActPerMoMa) |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

### Quadrupedal Manipulation
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Non-learning Control_ |
| [**LocoMan: Advancing Versatile Quadrupedal Dexterity with Lightweight Loco-Manipulators**](https://arxiv.org/abs/2403.18197) | IROS 2024 | 2024-03-27 | ![Star](https://img.shields.io/github/stars/linchangyi1/LocoMan?style=social&label=Star) [Github](https://github.com/linchangyi1/LocoMan) |
| [**Bayesian Multi-Task Learning MPC for Robotic Mobile Manipulation**](https://arxiv.org/abs/2211.10270) | RA-L 2023 | 2022-11-18 | - |
| [**RoLoMa: Robust Loco-Manipulation for Quadruped Robots with Arms**](https://arxiv.org/abs/2203.01446) | Auton Robot 2023 | 2022-03-02 | - |
| [**Optimisation of Body-ground Contact for Augmenting Whole-Body Loco-manipulation of Quadruped Robots**](https://arxiv.org/abs/2002.10552) | IROS 2020 | 2020-02-24 | - |
| _RL_ |
| [**Efficient Learning of A Unified Policy For Whole-body Manipulation and Locomotion Skills**](https://arxiv.org/abs/2507.04229) | arXiv | 2025-07-06 | [Project](https://ecstayalive.github.io/posts/PhysicsFeasibilityGuidedOptimization/) |
| [**Learning Unified Force and Position Control for Legged Loco-Manipulation**](https://arxiv.org/abs/2505.20829) | arXiv | 2025-05-27 | [Project](https://unified-force.github.io/) |
| [**QuadWBG: Generalizable Quadrupedal Whole-Body Grasping**](https://arxiv.org/abs/2411.06782) | ICRA 2025 | 2024-11-11 | [Project](https://ecstayalive.github.io/posts/PhysicsFeasibilityGuidedOptimization/) |
| [**Learning Whole-Body Loco-Manipulation for Omni-Directional Task Space Pose Tracking with a Wheeled-Quadrupedal-Manipulator**](https://arxiv.org/abs/2412.03012) | RA-L 2024 | 2024-12-04 | [Project](https://clearlab-sustech.github.io/RFM_loco_mani/) |
| [**Continuously Improving Mobile Manipulation with Autonomous Real-World RL**](https://arxiv.org/abs/2409.20568) | CoRL 2024 | 2024-09-30 | [Project](https://continual-mobile-manip.github.io/) |
| [**Visual Whole-Body Control for Legged Loco-Manipulation**](https://arxiv.org/abs/2403.16967) | CoRL 2024 | 2024-03-25 | ![Star](https://img.shields.io/github/stars/Ericonaldo/visual_wholebody?style=social&label=Star) [Github](https://github.com/Ericonaldo/visual_wholebody) |
| [**HiLMa-Res: A General Hierarchical Framework via Residual RL for Combining Quadrupedal Locomotion and Manipulation**](https://arxiv.org/abs/2407.06584) | IROS 2024 | 2024-07-09 | - |
| [**Pedipulate: Enabling Manipulation Skills using a Quadruped Robot's Leg**](https://arxiv.org/abs/2402.10837) | ICRA 2024 | 2024-02-16 | [Project](https://sites.google.com/leggedrobotics.com/pedipulate) |
| [**GAMMA: Graspability-Aware Mobile MAnipulation Policy Learning based on Online Grasping Pose Fusion**](https://arxiv.org/abs/2309.15459) | ICRA 2024 | 2023-09-27 | ![Star](https://img.shields.io/github/stars/user432/gamma?style=social&label=Star) [Github](https://github.com/user432/gamma) |
| [**RoboDuet: Learning a Cooperative Policy for Whole-body Legged Loco-Manipulation**](https://arxiv.org/abs/2403.173679) | RA-L 2025 | 2024-03-26 | ![Star](https://img.shields.io/github/stars/locomanip-duet/RoboDuet?style=social&label=Star) [Github](https://github.com/locomanip-duet/RoboDuet) |
| [**Learning Whole-body Manipulation for Quadrupedal Robot**](https://arxiv.org/abs/2308.16820) | RA-L 2023 | 2023-08-31 | - |
| [**Legs as Manipulator: Pushing Quadrupedal Agility Beyond Locomotion**](https://arxiv.org/abs/2303.11330) | ICRA 2023 | 2023-03-20 | [Project](https://robot-skills.github.io/) |
| [**Deep Whole-Body Control: Learning a Unified Policy for Manipulation and Locomotion**](https://arxiv.org/abs/2210.10044) | CoRL 2022 | 2022-11-18 | ![Star](https://img.shields.io/github/stars/MarkFzp/Deep-Whole-Body-Control?style=social&label=Star) [Github](https://github.com/MarkFzp/Deep-Whole-Body-Control) |
| _IL_ |
| [**Human2LocoMan: Learning Versatile Quadrupedal Manipulation with Human Pretraining**](https://arxiv.org/abs/2506.16475) | RSS 2025 | 2025-06-19  | ![Star](https://img.shields.io/github/stars/chrisyrniu/Human2LocoMan?style=social&label=Star) [Github](https://github.com/chrisyrniu/Human2LocoMan) |
| _RL+IL_ |
| [**WildLMa: Long Horizon Loco-Manipulation in the Wild**](https://arxiv.org/abs/2411.15131) | ICRA 2025 | 2024-11-22 | [Project](https://wildlma.github.io/) |
| [**Learning Visual Quadrupedal Loco-Manipulation from Demonstrations**](https://arxiv.org/abs/2403.203280) | IROS 2024 | 2024-03-29 | [Project](https://zhengmaohe.github.io/leg-manip/) |
| [**ASC: Adaptive Skill Coordination for Robotic Mobile Manipulation**](https://arxiv.org/abs/2304.00410) | RA-L 2023 | 2023-04-01 | [Project](https://adaptiveskillcoordination.github.io/) |
| _VLA_ |
| [**MoRE: Unlocking Scalability in Reinforcement Learning for Quadruped Vision-Language-Action Models**](https://arxiv.org/abs/2503.08007) | ICRA 2025 | 2025-03-11 | - |
| [**GeRM: A Generalist Robotic Model with Mixture-of-experts for Quadruped Robot**](https://arxiv.org/abs/2403.13358) | IROS 2024 | 2024-03-08 | ![Star](https://img.shields.io/github/stars/Songwxuan/GeRM?style=social&label=Star) [Github](https://github.com/Songwxuan/GeRM) |
| [**QUAR-VLA: Vision-Language-Action Model for Quadruped Robots**](https://arxiv.org/abs/2312.14457) | ECCV 2024 | 2023-12-22 | [Project](https://sites.google.com/view/quar-vla/quar-vla-eccv24) |
| _High-level Planner_ |
| [**Long-horizon Locomotion and Manipulation on a Quadrupedal Robot with Large Language Models**](https://arxiv.org/abs/2404.05291) | arXiv | 2024-04-08 | [Project](https://sites.google.com/view/long-horizon-robot) |
| _3D Representations_ | 
| [**Learning Generalizable Feature Fields for Mobile Manipulation**](https://arxiv.org/abs/2403.07563) | arXiv | 2024-03-12 | [Project](https://geff-b1.github.io/) |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.20-Humanoid Manipulation ******* -->
### Humanoid Manipulation
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Non-learning Control_ |
| [**Dynamics and Balance of a Humanoid Robot During Manipulation Tasks**](https://web.archive.org/web/20170829005551id_/http://www.cns.atr.jp/~karim/ar.pdf) | Adv Robotics 2012 | 2012-07 | - | |
| [**Dynamics and Balance of a Humanoid Robot During Manipulation Tasks**](https://ieeexplore.ieee.org/document/1638349) | T-RO 2006 | 2006-06 | - | |
| _Non-learning Control+DL Models_ |
| [**OKAMI: Teaching Humanoid Robots Manipulation Skills through Single Video Imitation**](https://arxiv.org/abs/2410.11792) | CoRL 2024 | 2014-10-15 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/OKAMI?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/OKAMI) | |
| _RL_ |
| [**FLAM: Foundation Model-Based Body Stabilization for Humanoid Locomotion and Manipulation**](https://arxiv.org/abs/2503.22249) | arXiv | 2025-03-28 | ![Star](https://img.shields.io/github/stars/Xianqi-Zhang/FLAM?style=social&label=Star) [Github](https://github.com/Xianqi-Zhang/FLAM) | |
| [**Sim-to-Real Reinforcement Learning for Vision-Based Dexterous Manipulation on Humanoids**](https://arxiv.org/abs/2502.20396) | arXiv | 2023-06-15 | [Project](https://toruowo.github.io/recipe/) | |
| [**Hierarchical Planning and Control for Box Loco-Manipulation**](https://arxiv.org/abs/2306.09532) | PACMCGIT 2023 | 2023-06-15 | ![Star](https://img.shields.io/github/stars/ZhaomingXie/box_manipulation_release?style=social&label=Star) [Github](https://github.com/ZhaomingXie/box_manipulation_release) | |
| _IL_ |
| [**Towards Human-level Intelligence via Human-like Whole-Body Manipulation**](https://arxiv.org/abs/2507.17141) | arXiv | 2025-07-23 | - | |
| [**TACT: Humanoid Whole-body Contact Manipulation through Deep Imitation Learning with Tactile Modality**](https://arxiv.org/abs/2506.15146) | RA-L 2025 | 2025-06-18 | - | |
| [**Humanoid Policy ~ Human Policy**](https://arxiv.org/abs/2503.13441) | IROS 2025 | 2025-03-17 | ![Star](https://img.shields.io/github/stars/RogerQi/human-policy?style=social&label=Star) [Github](https://github.com/RogerQi/human-policy)| |
| [iDP3: **Generalizable Humanoid Manipulation with 3D Diffusion Policies**](https://arxiv.org/abs/2410.10803) | IROS 2025 | 2024-10-14 | ![Star](https://img.shields.io/github/stars/YanjieZe/Improved-3D-Diffusion-Policy?style=social&label=Star) [Github](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy)| |
| [**OmniH2O: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation and Learning**](https://arxiv.org/abs/2406.08858) | CoRL 2024 | 2024-06-13 | ![Star](https://img.shields.io/github/stars/LeCAR-Lab/human2humanoid?style=social&label=Star) [Github](https://github.com/LeCAR-Lab/human2humanoid) | |
| [**Deep Imitation Learning for Humanoid Loco-manipulation through Human Teleoperation**](https://arxiv.org/abs/2309.01952) | Humanoids 2023 | 2023-09-20 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/TRILL?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/TRILL) | |
| _RL+IL_ |
| [**Hierarchical Vision-Language Planning for Multi-Step Humanoid Manipulation**](https://arxiv.org/abs/2506.22827) | RSSW 2025 | 2025-06-28 | [Project](https://vlp-humanoid.github.io/) | |
| [**CooHOI: Learning Cooperative Human-Object Interaction with Manipulated Object Dynamics**](https://arxiv.org/abs/2406.14558) | NeurIPS 2024 | 2024-06-20 | ![Star](https://img.shields.io/github/stars/Winston-Gu/CooHOI?style=social&label=Star) [Github](https://github.com/Winston-Gu/CooHOI) | |
| _VLA_ |
| [**GR00T N1: An Open Foundation Model for Generalist Humanoid Robots**](https://arxiv.org/abs/2503.14734) | arXiv | 2025-03-18 | [Project](https://developer.nvidia.com/isaac/gr00t) | |
| [**Humanoid-VLA: Towards Universal Humanoid Control with Visual Integration**](https://arxiv.org/abs/2502.14795) | arXiv | 2025-02-20 | - | |
| [**HumanVLA: Towards Vision-Language Directed Object Rearrangement by Physical Humanoid**](https://arxiv.org/abs/2406.19972) | NeurIPS | 2024-06-28 | ![Star](https://img.shields.io/github/stars/AllenXuuu/HumanVLA?style=social&label=Star) [Github](https://github.com/AllenXuuu/HumanVLA) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.24-Other Applications ******* -->
### Other Applications
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Household_ |
| [**Towards the development of a soft manipulator as an assistive robot for personal care of elderly people**](https://journals.sagepub.com/doi/full/10.1177/1729881416687132) | IJARS 2017 | 2017-04-11  | - |
| _Precise Manipulation_ |
| [**RICE: Reactive Interaction Controller for Cluttered Canopy Environment**](https://arxiv.org/abs/2506.10383) | RA-L 2025 | 2025-06-12  | - |
| [**Find the Fruit: Designing a Zero-Shot Sim2Real Deep RL Planner for Occlusion Aware Plant Manipulation**](https://arxiv.org/abs/2505.16547) | arXiv | 2025-05-22  | - |
| [**FoAR: Force-Aware Reactive Policy for Contact-Rich Robotic Manipulation**](https://arxiv.org/abs/2411.15753) | arXiv | 2024-11-24 | [Project](https://tonyfang.net/FoAR/)  |
| [**ForceMimic: Force-Centric Imitation Learning with Force-Motion Capture System for Contact-Rich Manipulation**](https://arxiv.org/abs/2410.07554) | arXiv | 2024-10-10 | [Project](https://forcemimic.github.io/)  |
| [**Predicting Object Interactions with Behavior Primitives: An Application in Stowing Tasks**](https://arxiv.org/abs/2309.16873) | CoRL 2023 | 2023-09-28 | ![Star](https://img.shields.io/github/stars/haonan16/Stow?style=social&label=Star) [Github](https://github.com/haonan16/Stow)  |
| [VAPORS: **Learning Sequential Acquisition Policies for Robot-Assisted Feeding**](https://arxiv.org/abs/2309.05197) | CoRL 2023 | 2023-09-11  | [Project](https://sites.google.com/view/vaporsbot) |
| [**HANDLOOM: Learned Tracing of One-Dimensional Objects for Inspection and Manipulation**](https://arxiv.org/abs/2303.08975) | CoRL 2023 | 2023-03-15 | [Project](https://github.com/vainaviv/handloom)  |
| [**RoboCook: Long-Horizon Elasto-Plastic Object Manipulation with Diverse Tools**](https://arxiv.org/abs/2306.14447) | CoRL 2023 | 2023-06-26  | ![Star](https://img.shields.io/github/stars/hshi74/robocook?style=social&label=Star) [Github](https://github.com/hshi74/robocook) |
| _Object Rearrangement_ |
| [**PACA: Perspective-Aware Cross-Attention Representation for Zero-Shot Scene Rearrangement**](https://arxiv.org/abs/2410.22059) | WACV 2025 | 2024-10-29  | - |
| [**LGMCTS: Language-Guided Monte-Carlo Tree Search for Executable Semantic Object Rearrangement**](https://arxiv.org/abs/2309.15821) | IROS 2024 | 2023-09-27  | ![Star](https://img.shields.io/github/stars/changhaonan/LGMCTS-D?style=social&label=Star) [Github](https://github.com/changhaonan/LGMCTS-D)  |
| [LLM-GROP: **Task and Motion Planning with Large Language Models for Object Rearrangement**](https://arxiv.org/abs/2303.06247) | IROS 2023 | 2023-03-10 | [Colab](https://colab.research.google.com/drive/1cSqoSc6Gk9KM9p-GwHSIIL5VfZICGW3B?usp=sharing)  |
| [**DALL-E-Bot: Introducing Web-Scale Diffusion Models to Robotics**](https://arxiv.org/abs/2210.02438) | RA-L 2023 | 2022-10-05 | [Project](https://www.robot-learning.uk/)  |
| _Non-prehensile Manipulation_ |
| [**HACMan: Learning Hybrid Actor-Critic Maps for 6D Non-Prehensile Manipulation**](https://arxiv.org/abs/2305.03942) | CoRL 2023 | 2023-05-06  | ![Star](https://img.shields.io/github/stars/HACMan-2023/HACMan?style=social&label=Star) [Github](https://github.com/HACMan-2023/HACMan)  |
| _Tool Manipulation_ |
| [**RobotSmith: Generative Robotic Tool Design for Acquisition of Complex Manipulation Skills**](https://arxiv.org/abs/2506.14763) | arXiv | 2025-06-17 | [Project](https://chunru-lin.github.io/RobotSmith/) | |
| [**Leveraging Language for Accelerated Learning of Tool Manipulation**](https://arxiv.org/abs/2206.13074) | CoRL 2023 | 2022-06-27 | ![Star](https://img.shields.io/github/stars/irom-lab/ATLA?style=social&label=Star) [Github](https://github.com/irom-lab/ATLA) | |
| _Responsible Manipulation_|
| [**Learning Robust Motion Skills via Critical Adversarial Attacks for Humanoid Robots**](https://arxiv.org/abs/2507.08303) | arXiv | 2025-07-11 | - | |
| [**Adversarial Attacks on Robotic Vision Language Action Models**](https://arxiv.org/abs/2506.03350) | arXiv | 2025-06-03 | ![Star](https://img.shields.io/github/stars/eliotjones1/robogcg?style=social&label=Star) [Github](https://github.com/eliotjones1/robogcg) | |
| [**Adversarial Data Collection: Human-Collaborative Perturbations for Efficient and Robust Robotic Imitation Learning**](https://arxiv.org/abs/2503.11646) | arXiv | 2025-03-14 | - | |
| [**How vulnerable is my policy? Adversarial attacks on modern behavior cloning policies**](https://arxiv.org/abs/2502.03698) | arXiv | 2025-02-06 | - | |
| [**Don't Let Your Robot be Harmful: Responsible Robotic Manipulation**](https://arxiv.org/abs/2411.18289) | arXiv | 2024-11-27 | ![Star](https://img.shields.io/github/stars/kodenii/Responsible-Robotic-Manipulation?style=social&label=Star) [Github](https://github.com/kodenii/Responsible-Robotic-Manipulation) | |
| [**TrojanRobot: Backdoor Attacks Against LLM-based Embodied Robots in the Physical World**](https://arxiv.org/abs/2411.11683) | arXiv | 2024-11-18 | [Project](https://trojanrobot.github.io/) | |
| _Medical Science_|
| [**S3D: A Spatial Steerable Surgical Drilling Framework for Robotic Spinal Fixation Procedures**](https://arxiv.org/abs/2507.01779) | IROS 2025 | 2025-07-02 | - | |
| [**SonoGym: High Performance Simulation for Challenging Surgical Tasks with Robotic Ultrasound**](https://arxiv.org/abs/2507.01152) | arXiv | 2025-07-01 | ![Star](https://img.shields.io/github/stars/SonoGym/SonoGym?style=social&label=Star) [Github](https://github.com/SonoGym/SonoGym) | |
| _AI4Science_|
| [**Enhancing Autonomous Manipulator Control with Human-in-loop for Uncertain Assembly Environments**](https://arxiv.org/abs/2507.11006) | CASE 2025 | 2025-07-15 | - | |
| [**CapsDT: Diffusion-Transformer for Capsule Robot Manipulation**](https://arxiv.org/abs/2506.16263) | arXiv | 2025-06-19 | - | |
| [**LabUtopia: High-Fidelity Simulation and Hierarchical Benchmark for Scientific Embodied Agents**](https://arxiv.org/abs/2505.22634) | arXiv | 2025-05-28 | - | |
| [**RoboCulture: A Robotics Platform for Automated Biological Experimentation**](https://arxiv.org/abs/2505.14941) | arXiv | 2025-05-20 | - | |
| _Sports_ |
| [**SpikePingpong: High-Frequency Spike Vision-based Robot Learning for Precise Striking in Table Tennis Game**](https://arxiv.org/abs/2506.06690) | arXiv | 2025-06-07 | - | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


<!-- ******* 2 - Benchmarks ******* -->
## 📊 Awesome Simulators, Benchmarks and Dataset

<!-- ******* 2.1 - Grasp Datasets ******* -->
### Grasp Datasets
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**MapleGrasp: Mask-guided Feature Pooling for Language-driven Efficient Robotic Grasping**](https://arxiv.org/abs/2506.06535) | arXiv | 2025-06-06 | - | |
| [**GraspClutter6D: A Large-scale Real-world Dataset for Robust Perception and Grasping in Cluttered Scenes**](https://arxiv.org/abs/2504.06866) | arXiv | 2025-04-09 | [Project](https://sites.google.com/view/graspclutter6d) | |
| [**QDGset: A Large Scale Grasping Dataset Generated with Quality-Diversity**](https://arxiv.org/abs/2410.02319) | arXiv | 2024-10-03 | [Project](https://github.com/qdgrasp/qdgrasp.github.io/blob/main/qdg_set.md) | |
| [**Dex1B: Learning with 1B Demonstrations for Dexterous Manipulation**](https://arxiv.org/abs/2506.17198) | RSS 2025 | 2025-06-20 | [Project](https://jianglongye.com/dex1b/) | |
| [**Real-to-Sim Grasp: Rethinking the Gap between Simulation and Real World in Grasp Detection**](https://arxiv.org/abs/2410.06521) | CoRL 2024 | 2024-10-09 | [Project](https://isee-laboratory.github.io/R2SGrasp/) | |
| [**DexGraspNet 2.0: Learning Generative Dexterous Grasping in Large-scale Synthetic Cluttered Scenes**](https://openreview.net/attachment?id=5W0iZR9J7h&name=pdf) | CoRL 2024 | 2024 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/DexGraspNet2?style=social&label=Star) [Github](https://github.com/PKU-EPIC/DexGraspNet2)  |
| [Grasp-Anything-6D: **Language-Driven 6-DoF Grasp Detection Using Negative Prompt Guidance**](https://arxiv.org/abs/2407.13842) | ECCV 2024 | 2024-07-18 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance?style=social&label=Star) [Github](https://github.com/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance) |  |
| [Grasp-Anything++: **Language-driven Grasp Detection**](https://arxiv.org/abs/2406.09489) | CVPR 2024 | 2024-06-13 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/LGD?style=social&label=Star) [Github](https://github.com/Fsoft-AIC/LGD) |  |
| [**Grasp-Anything: Large-scale Grasp Dataset from Foundation Models**](https://arxiv.org/abs/2309.09818) | ICRA 2024 | 2023-09-18 | ![Star](https://img.shields.io/github/stars/Fsoft-AIC/Grasp-Anything?style=social&label=Star) [Github](https://github.com/Fsoft-AIC/Grasp-Anything) | |
| [**MetaGraspNetV2: All-in-One Dataset Enabling Fast and Reliable Robotic Bin Picking via Object Relationship Reasoning and Dexterous Grasping**](https://ieeexplore.ieee.org/document/10309974) | TASE 2023 | 2023-11-06 | ![Star](https://img.shields.io/github/stars/maximiliangilles/MetaGraspNet?style=social&label=Star) [Github](https://github.com/maximiliangilles/MetaGraspNet) | |
| [**DexGraspNet: A Large-Scale Robotic Dexterous Grasp Dataset for General Objects Based on Simulation**](https://arxiv.org/abs/2210.02697) | ICRA 2023 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/DexGraspNet?style=social&label=Star) [Github](https://github.com/PKU-EPIC/DexGraspNet) | |
| [**MetaGraspNet: A Large-Scale Benchmark Dataset for Scene-Aware Ambidextrous Bin Picking via Physics-based Metaverse Synthesis**](https://arxiv.org/abs/2208.03963) | CASE 2022 | 2022-08-08 | ![Star](https://img.shields.io/github/stars/maximiliangilles/MetaGraspNet?style=social&label=Star) [Github](https://github.com/maximiliangilles/MetaGraspNet) | |
| [**REGRAD: A Large-Scale Relational Grasp Dataset for Safe and Object-Specific Robotic Grasping in Clutter**](https://arxiv.org/abs/2104.14118) | ICRA 2021 | 2021-04-29 | ![Star](https://img.shields.io/github/stars/poisonwine/REGRAD?style=social&label=Star) [Github](https://github.com/poisonwine/REGRAD) | |
| [**ACRONYM: A Large-Scale Grasp Dataset Based on Simulation**](https://arxiv.org/abs/2011.09584) | ICRA 2021 | 2020-11-18 | ![Star](https://img.shields.io/github/stars/NVlabs/acronym?style=social&label=Star) [Github](https://github.com/NVlabs/acronym) | |
| [**GraspNet-1Billion: A Large-Scale Benchmark for General Object Grasping**](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_GraspNet-1Billion_A_Large-Scale_Benchmark_for_General_Object_Grasping_CVPR_2020_paper.pdf) | CVPR 2020 | 2020-08-05 | ![Star](https://img.shields.io/github/stars/graspnet/graspnet-baseline?style=social&label=Star) [Github](https://github.com/graspnet/graspnet-baseline) | |
| [**Jacquard: A Large Scale Dataset for Robotic Grasp Detection**](https://arxiv.org/abs/1803.11469) | IROS 2018 | 2018-03-30 | [Project](https://jacquard.liris.cnrs.fr/) | |
| [Cornell: **Efficient Grasping from RGBD Images: Learning Using a New Rectangle Representation**](https://ieeexplore.ieee.org/document/5980145) | ICRA 2011 | 2011-08 | - | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 2.2 - Single-Embodiment Manipulation Simulators and Benchmarks ******* -->
### Single-Embodiment Manipulation Simulators and Benchmarks
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Basic Manipulation with a Single Arm_ |
| [**LADEV: A Language-Driven Testing and Evaluation Platform for Vision-Language-Action Models in Robotic Manipulation**](https://arxiv.org/abs/2410.05191) | arXiv | 2024-10-07 | - | For VLA |
| [**GenSim2: Scaling Robot Data Generation with Multi-modal and Reasoning LLMs**](https://arxiv.org/abs/2410.03645) | CoRL 2024 | 2024-10-04 | ![Star](https://img.shields.io/github/stars/GenSim2/gensim2?style=social&label=Star) [Github](https://github.com/GenSim2/gensim2) |
| [SIMPLER: **Evaluating Real-World Robot Manipulation Policies in Simulation**](https://arxiv.org/abs/2405.05941) | CoRL 2024 | 2024-05-09 | ![Star](https://img.shields.io/github/stars/simpler-env/SimplerEnv?style=social&label=Star) [Github](https://github.com/simpler-env/SimplerEnv) | For VLA |
| [**LIBERO: Benchmarking Knowledge Transfer for Lifelong Robot Learning**](https://arxiv.org/abs/2306.03310) | NeurIPS 2023 | 2023-06-05 | ![Star](https://img.shields.io/github/stars/Lifelong-Robot-Learning/LIBERO?style=social&label=Star) [Github](https://github.com/Lifelong-Robot-Learning/LIBERO) | |
| [**ARNOLD: A Benchmark for Language-Grounded Task Learning With Continuous States in Realistic 3D Scenes**](https://arxiv.org/abs/2304.04321) | ICCV 2023 | 2023-04-09 | ![Star](https://img.shields.io/github/stars/arnold-benchmark/arnold?style=social&label=Star) [Github](https://github.com/arnold-benchmark/arnold) | |
| [**VIMA: General Robot Manipulation with Multimodal Prompts**](https://arxiv.org/abs/2210.03094) | ICML 2023 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/vimalabs/VIMA?style=social&label=Star) [Github](https://github.com/vimalabs/VIMA) | |
| [**ManiSkill2: A Unified Benchmark for Generalizable Manipulation Skills**](https://arxiv.org/abs/2302.04659) | ICLR 2023 | 2023-02-09 | ![Star](https://img.shields.io/github/stars/haosulab/ManiSkill2?style=social&label=Star) [Github](https://github.com/haosulab/ManiSkill2) | |
| [**VLMbench: A Compositional Benchmark for Vision-and-Language Manipulation**](https://arxiv.org/abs/2206.08522) | NeurIPS 2022 | 2022-06-17 | ![Star](https://img.shields.io/github/stars/eric-ai-lab/VLMbench?style=social&label=Star) [Github](https://github.com/eric-ai-lab/VLMbench) | |
| [**ManiSkill: Generalizable Manipulation Skill Benchmark with Large-Scale Demonstrations**](https://arxiv.org/abs/2107.14483) | NeurIPS D&B 2021 | 2021-07-30 | ![Star](https://img.shields.io/github/stars/haosulab/ManiSkill?style=social&label=Star) [Github](https://github.com/haosulab/ManiSkill) | |
| [Robomimic: **What Matters in Learning from Offline Human Demonstrations for Robot Manipulation**](https://arxiv.org/abs/2108.03298) | CoRL 2021 | 2021-08-06 | ![Star](https://img.shields.io/github/stars/ARISE-Initiative/robomimic?style=social&label=Star) [Github](https://github.com/ARISE-Initiative/robomimic) | |
| [**RLBench: The Robot Learning Benchmark & Learning Environment**](https://arxiv.org/abs/1909.12271) | RA-L 2020 | 2019-09-26 | ![Star](https://img.shields.io/github/stars/stepjam/RLBench?style=social&label=Star) [Github](https://github.com/stepjam/RLBench) | |
| [Franka-Kitchen: **Relay Policy Learning: Solving Long-Horizon Tasks via Imitation and Reinforcement Learning**](https://arxiv.org/abs/1910.11956) | CoRL 2019 | 2019-10-25 | [Project](https://relay-policy-learning.github.io/) |
| [**Meta-World: A Benchmark and Evaluation for Multi-Task and Meta Reinforcement Learning**](https://arxiv.org/abs/1910.10897) | CoRL 2019 | 2019-10-24 | ![Star](https://img.shields.io/github/stars/Farama-Foundation/Metaworld?style=social&label=Star) [Github](https://github.com/Farama-Foundation/Metaworld) |
| _Basic Manipulation with Bimanual Arms_ |
| [**RoboEval: Where Robotic Manipulation Meets Structured and Scalable Evaluation**](https://arxiv.org/abs/2507.00435) | arXiv | 2025-07-01 | ![Star](https://img.shields.io/github/stars/Robo-Eval/RoboEval?style=social&label=Star) [Github](https://github.com/Robo-Eval/RoboEval) | |
| [**RoboTwin 2.0: A Scalable Data Generator and Benchmark with Strong Domain Randomization for Robust Bimanual Robotic Manipulation**](https://arxiv.org/abs/2506.18088) | arXiv | 2025-06-22 | ![Star](https://img.shields.io/github/stars/robotwin-Platform/RoboTwin?style=social&label=Star) [Github](https://github.com/robotwin-Platform/RoboTwin) | |
| [**RoboTwin: Dual-Arm Robot Benchmark with Generative Digital Twins**](https://arxiv.org/abs/2504.13059) | CVPR 2025 | 2025-04-17 | ![Star](https://img.shields.io/github/stars/TianxingChen/RoboTwin?style=social&label=Star) [Github](https://github.com/TianxingChen/RoboTwin) | |
| _Basic Manipulation with Long-horizon Tasks_ |
| [**RoboCerebra: A Large-scale Benchmark for Long-horizon Robotic Manipulation Evaluation**](https://arxiv.org/abs/2506.06677) | arXiv | 2025-06-07 | [Project](https://robocerebra.github.io/) | |
| [**MuBlE: MuJoCo and Blender simulation Environment and Benchmark for Task Planning in Robot Manipulation**](https://arxiv.org/abs/2503.02834) | arXiv | 2025-03-03 | ![Star](https://img.shields.io/github/stars/michaal94/MuBlE?style=social&label=Star) [Github](https://github.com/michaal94/MuBlE) | |
| [**VLABench: A Large-Scale Benchmark for Language-Conditioned Robotics Manipulation with Long-Horizon Reasoning Tasks**](https://arxiv.org/abs/2412.18194) | arXiv | 2024-12-24 | ![Star](https://img.shields.io/github/stars/OpenMOSS/VLABench?style=social&label=Star) [Github](https://github.com/OpenMOSS/VLABench) | |
| [**CALVIN: A Benchmark for Language-Conditioned Policy Learning for Long-Horizon Robot Manipulation Tasks**](https://arxiv.org/abs/2112.03227) | RA-L 2022 | 2021-12-06 | ![Star](https://img.shields.io/github/stars/mees/calvin?style=social&label=Star) [Github](https://github.com/mees/calvin) | |
| _Basic Manipulation with Genralization Tasks_ |
| [INT-ACT: **From Intention to Execution: Probing the Generalization Boundaries of Vision-Language-Action Models**](https://arxiv.org/abs/2506.09930) | arXiv | 2025-06-11 | ![Star](https://img.shields.io/github/stars/ai4ce/INT-ACT?style=social&label=Star) [Github](https://github.com/ai4ce/INT-ACT) | |
| [AGNOSTOS: **Exploring the Limits of Vision-Language-Action Manipulations in Cross-task Generalization**](https://arxiv.org/abs/2505.15660) | arXiv | 2025-05-21 | ![Star](https://img.shields.io/github/stars/jiaming-zhou/X-ICM?style=social&label=Star) [Github](https://github.com/jiaming-zhou/X-ICM) | |
| [Gembench: **Towards Generalizable Vision-Language Robotic Manipulation: A Benchmark and LLM-guided 3D Policy**](https://arxiv.org/abs/2410.01345) | ICRA 2025 | 2024-10-02 | ![Star](https://img.shields.io/github/stars/vlc-robot/robot-3dlotus?style=social&label=Star) [Github](https://github.com/vlc-robot/robot-3dlotus) | |
| [**THE COLOSSEUM: A Benchmark for Evaluating Generalization for Robotic Manipulation**](https://arxiv.org/abs/2402.08191) | RSSW 2024 | 2024-02-13 | ![Star](https://img.shields.io/github/stars/robot-colosseum/robot-colosseum?style=social&label=Star) [Github](https://github.com/robot-colosseum/robot-colosseum) | |
| [**KitchenShift: Evaluating Zero-Shot Generalization of Imitation-Based Policy Learning Under Domain Shifts**](https://openreview.net/pdf?id=DdglKo8hBq0) | NeurIPSW 2021 | 2021 | ![Star](https://img.shields.io/github/stars/etaoxing/kitchen-shift?style=social&label=Star) [Github](https://github.com/etaoxing/kitchen-shift) |
| _Basic Manipulation in Real World_ |
| [**AutoEval: Autonomous Evaluation of Generalist Robot Manipulation Policies in the Real World**](https://arxiv.org/pdf/2503.24278) | arXiv | 2025-03-31 | ![Star](https://img.shields.io/github/stars/zhouzypaul/auto_eval?style=social&label=Star) [Github](https://github.com/zhouzypaul/auto_eval) | |
| _Basic Manipulation with High-level Planner_ |
| [**GENMANIP: LLM-driven Simulation for Generalizable Instruction-Following Manipulation**](https://arxiv.org/abs/2506.10966) | CVPR 2025 | 2025-06-12 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/GenManip?style=social&label=Star) [Github](https://github.com/OpenRobotLab/GenManip) | |
| [**ALFRED: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks**](https://arxiv.org/abs/1912.01734) | CVPR 2020 | 2019-12-03 | ![Star](https://img.shields.io/github/stars/askforalfred/alfred?style=social&label=Star) [Github](https://github.com/askforalfred/alfred) | |
| _Basic Manipulation with Tactile Representations_ |
| [**ManiFeel: Benchmarking and Understanding Visuotactile Manipulation Policy Learning**](https://arxiv.org/abs/2505.18472) | arXiv | 2025-05-24 | [Project](https://zhengtongxu.github.io/manifeel-website/) | |
| [**TacCompress: A Benchmark for Multi-Point Tactile Data Compression in Dexterous Manipulation**](https://arxiv.org/abs/2505.16289) | arXiv | 2025-05-22 | - | |
| [**TacSL: A Library for Visuotactile Sensor Simulation and Learning**](https://arxiv.org/abs/2408.06506) | T-RO 2025 | 2024-08-12 | ![Star](https://img.shields.io/github/stars/isaac-sim/IsaacGymEnvs?style=social&label=Star) [Github](https://github.com/isaac-sim/IsaacGymEnvs/blob/tacsl/isaacgymenvs/tacsl_sensors/install/tacsl_setup.md) | |
| [**Efficient Tactile Simulation with Differentiability for Robotic Manipulation**](https://openreview.net/pdf?id=6BIffCl6gsM) | CoRL 2022 | 2022-09-10 | ![Star](https://img.shields.io/github/stars/eanswer/TactileSimulation?style=social&label=Star) [Github](https://github.com/eanswer/TactileSimulation) | |
| _Dexterous Manipulation_ |
| [**TriFinger: An Open-Source Robot for Learning Dexterity**](https://arxiv.org/abs/2008.03596) | CoRL 2021 | 2020-08-08 | ![Star](https://img.shields.io/github/stars/open-dynamic-robot-initiative/trifinger_simulation?style=social&label=Star) [Github](https://github.com/open-dynamic-robot-initiative/trifinger_simulation) | |
| [**Learning Complex Dexterous Manipulation with Deep Reinforcement Learning and Demonstrations**](https://arxiv.org/abs/1709.10087) | RSS 2018 | 2017-09-28 | ![Star](https://img.shields.io/github/stars/aravindr93/hand_dapg?style=social&label=Star) [Github](https://github.com/aravindr93/hand_dapg) | |
| _Deformable Object Manipulation_ |
| [**DaXBench: Benchmarking Deformable Object Manipulation with Differentiable Physics**](https://arxiv.org/abs/2210.13066) | ICLR 2023 | 2022-10-24 | ![Star](https://img.shields.io/github/stars/AdaCompNUS/DaXBench?style=social&label=Star) [Github](https://github.com/AdaCompNUS/DaXBench) | |
| [**PlasticineLab: A Soft-Body Manipulation Benchmark with Differentiable Physics**](https://arxiv.org/abs/2104.03311) | ICLR 2021 | 2021-04-07 | ![Star](https://img.shields.io/github/stars/hzaskywalker/PlasticineLab?style=social&label=Star) [Github](https://github.com/hzaskywalker/PlasticineLab) | |
| [**SoftGym: Benchmarking Deep Reinforcement Learning for Deformable Object Manipulation**](https://arxiv.org/abs/2011.07215) | CoRL 2020 | 2020-11-14 | ![Star](https://img.shields.io/github/stars/Xingyu-Lin/softgym?style=social&label=Star) [Github](https://github.com/Xingyu-Lin/softgym) | |
| _Mobile Manipulation_ |
| [**HomeRobot: Open-Vocabulary Mobile Manipulation**](https://arxiv.org/abs/2306.11565) | CoRL 2023 | 2023-06-20 | ![Star](https://img.shields.io/github/stars/facebookresearch/home-robot?style=social&label=Star) [Github](https://github.com/facebookresearch/home-robot) | |
| [**BEHAVIOR-1K: A Human-Centered, Embodied AI Benchmark with 1,000 Everyday Activities and Realistic Simulation**](https://arxiv.org/abs/2403.09227) | CoRL 2022 | 2024-03-14 | [Project](https://behavior.stanford.edu/) | |
| [**ManipulaTHOR: A Framework for Visual Object Manipulation**](https://arxiv.org/abs/2104.11213) | CVPR 2021 | 2021-04-22 | ![Star](https://img.shields.io/github/stars/allenai/manipulathor?style=social&label=Star) [Github](https://github.com/allenai/manipulathor) | |
| _Humanoid Manipulation_ |
| [**HumanoidGen: Data Generation for Bimanual Dexterous Manipulation via LLM Reasoning**](https://arxiv.org/abs/2507.00833) | arXiv | 2025-07-01 | ![Star](https://img.shields.io/github/stars/TeleHuman/HumanoidGen?style=social&label=Star) [Github](https://github.com/TeleHuman/HumanoidGen) | |
| [**BiGym: A Demo-Driven Mobile Bi-Manual Manipulation Benchmark**](https://arxiv.org/abs/2407.07788) | arXiv | 2024-07-10 | ![Star](https://img.shields.io/github/stars/chernyadev/bigym?style=social&label=Star) [Github](https://github.com/chernyadev/bigym) | |
| [**HumanoidBench: Simulated Humanoid Benchmark for Whole-Body Locomotion and Manipulation**](https://arxiv.org/abs/2403.10506) | arXiv | 2024-03-15 | ![Star](https://img.shields.io/github/stars/carlosferrazza/humanoid-bench?style=social&label=Star) [Github](https://github.com/carlosferrazza/humanoid-bench) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 2.3 - Cross-Embodiment Simulators and Benchmarks ******* -->
### Cross-Embodiment Simulators and Benchmarks
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**VIKI-R: Coordinating Embodied Multi-Agent Cooperation via Reinforcement Learning**](https://arxiv.org/abs/2506.09049) | arXiv | 2025-06-10 | ![Star](https://img.shields.io/github/stars/MARS-EAI/VIKI-R?style=social&label=Star) [Github](https://github.com/MARS-EAI/VIKI-R) |
| [**ImagineBench: Evaluating Reinforcement Learning with Large Language Model Rollouts**](https://arxiv.org/abs/2505.10010) | arXiv | 2025-05-15 | ![Star](https://img.shields.io/github/stars/LAMDA-RL/ImagineBench?style=social&label=Star) [Github](https://github.com/LAMDA-RL/ImagineBench) |
| [**RoboVerse: Towards a Unified Platform, Dataset and Benchmark for Scalable and Generalizable Robot Learning**](https://arxiv.org/abs/2504.18904) | RSS 2025 | 2025-04-26 | ![Star](https://img.shields.io/github/stars/RoboVerseOrg/RoboVerse?style=social&label=Star) [Github](https://github.com/RoboVerseOrg/RoboVerse) |
| [**ManiSkill3: GPU Parallelized Robotics Simulation and Rendering for Generalizable Embodied AI**](https://arxiv.org/abs/2410.00425) | RSS 2025 | 2024-10-01 | ![Star](https://img.shields.io/github/stars/haosulab/ManiSkill?style=social&label=Star) [Github](https://github.com/haosulab/ManiSkill) |
| **GENESIS: A generative world for general-purpose robotics & embodied AI learning** | - | 2024-12 | ![Star](https://img.shields.io/github/stars/Genesis-Embodied-AI/Genesis?style=social&label=Star) [Github](https://github.com/Genesis-Embodied-AI/Genesis) |
| [**RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots**](https://arxiv.org/abs/2406.02523) | RSS 2024 | 2024-06-04 | ![Star](https://img.shields.io/github/stars/robocasa/robocasa?style=social&label=Star) [Github](https://github.com/robocasa/robocasa) |  |
| [CortexBench: **Where are we in the search for an Artificial Visual Cortex for Embodied Intelligence?**](https://arxiv.org/abs/2303.18240) | NeurIPS 2023 | 2023-03-31 | ![Star](https://img.shields.io/github/stars/facebookresearch/eai-vc?style=social&label=Star) [Github](https://github.com/facebookresearch/eai-vc) | |
| [Isaac Lab: **Orbit: A Unified Simulation Framework for Interactive Robot Learning Environments**](https://arxiv.org/abs/2301.04195) | RA-L 2023 | 2023-01-10 | ![Star](https://img.shields.io/github/stars/isaac-sim/IsaacLab?style=social&label=Star) [Github](https://github.com/isaac-sim/IsaacLab) |
| [**robosuite: A Modular Simulation Framework and Benchmark for Robot Learning**](https://arxiv.org/abs/2009.12293) | arXiv | 2020-09-25 | ![Star](https://img.shields.io/github/stars/ARISE-Initiative/robosuite?style=social&label=Star) [Github](https://github.com/ARISE-Initiative/robosuite) |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 2.4 - Other Simulators and Benchmarks ******* -->
### Other Simulators and Benchmarks
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**FLAME: A Federated Learning Benchmark for Robotic Manipulation**](https://arxiv.org/abs/2503.01729) | arXiv | 2025-03-03 | - | |
| [**Two by Two: Learning Multi-Task Pairwise Objects Assembly for Generalizable Robot Manipulation**](https://arxiv.org/abs/2504.06961) | CVPR 2025 | 2025-04-09 | ![Star](https://img.shields.io/github/stars/TEA-Lab/TwoByTWo?style=social&label=Star) [Github](https://github.com/TEA-Lab/TwoByTWo) | |
| [**FMB: a Functional Manipulation Benchmark for Generalizable Robotic Learning**](https://arxiv.org/abs/2401.08553) | IJRR 2024 | 2024-01-16 | ![Star](https://img.shields.io/github/stars/rail-berkeley/fmb?style=social&label=Star) [Github](https://github.com/rail-berkeley/fmb) | Functional Manipulation |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 2.5 - Trajectory Datasets ******* -->
### Trajectory Datasets
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**RoboFAC: A Comprehensive Framework for Robotic Failure Analysis and Correction**](https://arxiv.org/abs/2505.12224) | arXiv | 2024-05-18 | - | |
| [**AgiBot World Colosseo: A Large-scale Manipulation Platform for Scalable and Intelligent Embodied Systems**](https://arxiv.org/abs/2503.06669) | IROS 2025 | 2025-03-09 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/AgiBot-World?style=social&label=Star) [Github](https://github.com/OpenDriveLab/AgiBot-World) |
| [**RoboMIND: Benchmark on Multi-embodiment Intelligence Normative Data for Robot Manipulation**](https://arxiv.org/abs/2412.13877) | arXiv | 2024-12-18 | ![Star](https://img.shields.io/github/stars/x-humanoid-robomind/x-humanoid-robomind.github.io?style=social&label=Star) [Github](https://github.com/x-humanoid-robomind/x-humanoid-robomind.github.io) |
| [ARIO: **All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents**](https://arxiv.org/abs/2408.10899) | arXiv | 2024-08-20 | [Dataset](https://openi.pcl.ac.cn/ARIO/ARIO_Dataset) | |
| [**DROID: A Large-Scale In-The-Wild Robot Manipulation Dataset**](https://arxiv.org/abs/2403.12945) | RSS 2024 | 2024-03-19 | ![Star](https://img.shields.io/github/stars/droid-dataset/droid_policy_learning?style=social&label=Star) [Github](https://github.com/droid-dataset/droid_policy_learning) | |
| [**Open X-Embodiment: Robotic Learning Datasets and RT-X Models**](https://arxiv.org/abs/2310.08864) | ICRA 2024 | 2023-10-13 | ![Star](https://img.shields.io/github/stars/google-deepmind/open_x_embodiment?style=social&label=Star) [Github](https://github.com/google-deepmind/open_x_embodiment) | |
| [**RoboAgent: Generalization and Efficiency in Robot Manipulation via Semantic Augmentations and Action Chunking**](https://arxiv.org/abs/2309.01918) | ICRA 2024 | 2024-09-05 | ![Star](https://img.shields.io/github/stars/robopen/roboagent?style=social&label=Star) [Github](https://github.com/robopen/roboagent) | |
| [**BridgeData V2: A Dataset for Robot Learning at Scale**](https://arxiv.org/abs/2308.12952) | CoRL 2023 | 2023-08-24 | ![Star](https://img.shields.io/github/stars/rail-berkeley/bridge_data_v2?style=social&label=Star) [Github](https://github.com/rail-berkeley/bridge_data_v2) | |
| [**RH20T: A Comprehensive Robotic Dataset for Learning Diverse Skills in One-Shot**](https://arxiv.org/abs/2307.00595) | RSSW 2023 | 2023-07-02 | [Project](https://rh20t.github.io/) | |
| [**RT-1: Robotics Transformer for Real-World Control at Scale**](https://arxiv.org/abs/2212.06817) | RSS 2023 | 2022-12-13 | [Dataset](https://console.cloud.google.com/storage/browser/gresearch/rt-1-data-release?inv=1&invt=Ab39vQ) | |
| [**BC-Z: Zero-Shot Task Generalization with Robotic Imitation Learning**](https://arxiv.org/abs/2202.02005) | CoRL 2021 | 2022-02-04 | [Dataset](https://www.kaggle.com/datasets/google/bc-z-robot) | |
| [**Bridge Data: Boosting Generalization of Robotic Skills with Cross-Domain Datasets**](https://arxiv.org/abs/2109.13396) | CoRL 2018 | 2021-09-27 | ![Star](https://img.shields.io/github/stars/yanlai00/bridge_data_imitation_learning?style=social&label=Star) [Github](https://github.com/yanlai00/bridge_data_imitation_learning) | |
| [**Multiple Interactions Made Easy (MIME): Large Scale Demonstrations Data for Imitation**](https://arxiv.org/abs/1810.07121) | CoRL 2018 | 2018-10-16 | - | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 2.6 - Embodied QA and Affordance Datasets ******* -->
### Embodied QA and Affordance Datasets
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**PAC Bench: Do Foundation Models Understand Prerequisites for Executing Manipulation Policies?**](https://arxiv.org/abs/2506.23725) | arXiv | 2024-06-30 | [Project](https://pacbench.github.io/) | |
| [**Robo2VLM: Visual Question Answering from Large-Scale In-the-Wild Robot Manipulation Datasets**](https://arxiv.org/abs/2505.15517) | arXiv | 2024-05-21 | [Huggingface](https://huggingface.co/datasets/keplerccc/Robo2VLM-1) | |
| [**PointArena: Probing Multimodal Grounding Through Language-Guided Pointing**](https://arxiv.org/abs/2505.09990) | arXiv | 2024-05-15 | ![Star](https://img.shields.io/github/stars/pointarena/pointarena?style=social&label=Star) [Github](https://github.com/pointarena/pointarena) | |
| [**ManipBench: Benchmarking Vision-Language Models for Low-Level Robot Manipulation**](https://arxiv.org/abs/2505.09698) | arXiv | 2024-05-14 | [Project](https://manipbench.github.io/) | |
| [**ManipVQA: Injecting Robotic Affordance and Physically Grounded Information into Multi-Modal Large Language Models**](https://arxiv.org/abs/2403.11289) | IROS 2024 | 2024-03-17 | ![Star](https://img.shields.io/github/stars/SiyuanHuang95/ManipVQA?style=social&label=Star) [Github](https://github.com/SiyuanHuang95/ManipVQA) | |
| [**OpenEQA: Embodied Question Answering in the Era of Foundation Models**](https://open-eqa.github.io/assets/pdfs/paper.pdf) | CVPR 2024 | 2024 | ![Star](https://img.shields.io/github/stars/facebookresearch/open-eqa?style=social&label=Star) [Github](https://github.com/facebookresearch/open-eqa) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>



<!-- ******* 3 - Techniques ******* -->
## 🛠️ Awesome Techniques
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| **Awesome-Implicit-NeRF-Robotics: [Neural Fields in Robotics: A Survey](https://arxiv.org/abs/2410.20220)** | - | 2024-10-26 | ![Star](https://img.shields.io/github/stars/zubair-irshad/Awesome-Implicit-NeRF-Robotics?style=social&label=Star) [Github](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics) | |
| **Awesome-Video-Robotic-Papers** | - | 2024 | ![Star](https://img.shields.io/github/stars/H-Freax/Awesome-Video-Robotic-Papers?style=social&label=Star) [Github](https://github.com/H-Freax/Awesome-Video-Robotic-Papers) | |
| **Awesome-Generalist-Robots-via-Foundation-Models: [Neural Fields in Robotics: A Survey](https://arxiv.org/abs/2312.08782)** | - | 2024 | ![Star](https://img.shields.io/github/stars/JeffreyYH/Awesome-Generalist-Robots-via-Foundation-Models?style=social&label=Star) [Github](https://github.com/JeffreyYH/Awesome-Generalist-Robots-via-Foundation-Models) | |
| **Awesome-Robotics-3D** | - | 2024 | ![Star](https://img.shields.io/github/stars/zubair-irshad/Awesome-Robotics-3D?style=social&label=Star) [Github](https://github.com/zubair-irshad/Awesome-Robotics-3D) | |
| **Awesome-Robotics-Foundation-Models: [Foundation Models in Robotics: Applications, Challenges, and the Future](https://arxiv.org/abs/2312.07843)** | - | 2023-12-13 | ![Star](https://img.shields.io/github/stars/robotics-survey/Awesome-Robotics-Foundation-Models?style=social&label=Star) [Github](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models/tree/main) | |
| **Awesome-LLM-Robotics** | - | 2022 |  ![Star](https://img.shields.io/github/stars/GT-RIPL/Awesome-LLM-Robotics?style=social&label=Star) [Github](https://github.com/GT-RIPL/Awesome-LLM-Robotics) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>



## ✨ Citation

If you find this repository useful, please consider citing this list:
```
@misc{ccbci&openhelix2024roboticsmanipulation,
    title = {Awesome-Robotics-Manipulation},
    author = {CC-BCI Group and OpenHelix Team},
    journal = {GitHub repository},
    url = {https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation},
    year = {2024},
}
```

- [XJTU Cognitive Computing and Brain-Computer Interaction (CC-BCI) Group](https://gr.xjtu.edu.cn/en/web/chenbd/home),  Prof. Badong Chen [[Google Scholar](https://scholar.google.com/citations?user=mq6tPX4AAAAJ&hl=en)].
- [OpenHelix Team](https://github.com/OpenHelix-Team),  Ph.D. Stu. Pengxiang Ding [[Google Scholar](https://scholar.google.com/citations?user=QyBSTzEAAAAJ&hl=en)].

