## 🏠 Table of Contents

- Low-level Learning-based Control
  - [Data Collection and Utilization](#data-collection-and-utilization)
    - [Data Collection](#data-collection)
        - [Human Teleoperation](#human-teleoperation)
        - [Human-in-the-Loop Enhancement](#human-in-the-Loop-enhancement)
        - [Automatic Generation](#automatic-generation)
        - [Crowdsourcing](#crowdsourcing)
    - [Data Utilization](#data-utilization)
        - [Data Expansion](#data-expansion)
        - [Data Reweighting](#data-reweighting)
        - [Data Selection](#data-selection)
        - [Data Retrieval](#data-retrieval)
        - [Data Augmentation](#data-augmentation)
  - [Learning Strategy](#learning-strategy)
    - [Imitation Learning (IL)](#imitation-learning-il)
      - [Imitation Learning from Action](#imitation-learning-from-action)
      - [Imitation Learning from Observation](#imitation-learning-from-observation)
    - [Reinforcement Learning (RL)](#reinforcement-learning-rl)
      - [Model-free Reinforcement Learning](#model-free-reinforcement-learning)
      - [Model-based Reinforcement Learning](#model-based-reinforcement-learning)
    - [RL and IL](#rl-and-il)
    - [Learning with Auxiliary Tasks](#learning-with-auxiliary-tasks)
      - [World Model](#world-model)
      - [Image/Video Prediction](#imagevideo-prediction)
      - [Contrastive Learning](#contrastive-learning)
      - [Masked Reconstruction](#masked-reconstruction)
      - [Text-Grounded Goal Extraction](#text-grounded-goal-extraction)
      - [Vision-Grounded Goal Extraction](#vision-grounded-goal-extraction)
  - [Input Modality](#modality)
      - [Vision Action Models](#vision-action-models)
      - [Vision Language Action Models](#vision-language-action-models)
          - [2D Vision Language Action Models](#2d-vision-language-action-models)
          - [3D Vision Language Action Models](#3d-vision-language-action-models)
      - [Tactile-based Action Models](#tactile-based-action-models)
      - [Other Modalities](#other-modalities)
  - [Latent Learning](#latent-learning)
      - [Pretrained Latent Learning](#pretrained-latent-learning)
      - [Latent Action Learning](#latent-action-learning)
  - [Policy Learning](#policy-learning)
      - [Diffusion Policy](#diffusion-policy)
      - [Other Policies](#other-policies)



## Data Collection and Utilization

<!-- Data Collection -->
<div align="center">

### <i>Data Collection</i>

</div>

### Human Teleoperation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**BEAVR: Bimanual, multi-Embodiment, Accessible, Virtual Reality Teleoperation System for Robots**](https://arxiv.org/abs/2508.09606) | ICCR 2025 | 2025-08-13 | ![Star](https://img.shields.io/github/stars/ARCLab-MIT/BEAVR-Bot?style=social&label=Star) [Github](https://github.com/ARCLab-MIT/BEAVR-Bot) |  |
| [**XRoboToolkit: A Cross-Platform Framework for Robot Teleoperation**](https://arxiv.org/abs/2508.00097) | arXiv | 2025-07-31 | [Github](https://github.com/XR-Robotics) |  |
| [**Fast Bilateral Teleoperation and Imitation Learning Using Sensorless Force Control via Accurate Dynamics Model**](https://arxiv.org/abs/2507.06174) | arXiv | 2025-07-08 | - |  |
| [**Dexterous Teleoperation of 20-DoF ByteDexter Hand via Human Motion Retargeting**](https://arxiv.org/abs/2507.03227) | arXiv | 2025-07-04 | [Project](https://byte-dexter.github.io/) |  |
| [**TypeTele: Releasing Dexterity in Teleoperation by Dexterous Manipulation Types**](https://arxiv.org/abs/2507.01857) | arXiv | 2025-07-02 | [Project](https://isee-laboratory.github.io/TypeTele/) |
| [**mimic-one: a Scalable Model Recipe for General Purpose Robot Dexterity**](https://arxiv.org/abs/2506.11916) | arXiv | 2025-06-13 | [Project](https://mimicrobotics.github.io/mimic-one/) |  |
| [**ExoStart: Efficient Learning for Dexterous Manipulation with Sensorized Exoskeleton Demonstrations**](https://arxiv.org/abs/2506.11775) | arXiv | 2025-06-13 | [Project](https://sites.google.com/view/exostart) | Exoskeleton Gloves |
| [**FreeTacMan: Robot-free Visuo-Tactile Data Collection System for Contact-rich Manipulation**](https://arxiv.org/abs/2506.01941) | arXiv | 2025-06-02 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/FreeTacMan?style=social&label=Star) [Github](https://github.com/OpenDriveLab/FreeTacMan) |
| [**Bootstrapping Imitation Learning for Long-horizon Manipulation via Hierarchical Data Collection Space**](https://arxiv.org/abs/2505.17389) | arXiv | 2025-05-23 | [Project](https://hd-space-robotics.github.io/) |  |
| [**Adversarial Data Collection: Human-Collaborative Perturbations for Efficient and Robust Robotic Imitation Learning**](https://arxiv.org/abs/2503.11646) | arXiv | 2025-03-14 | [Project](https://sites.google.com/view/adc-robot) |  |
| [**Kaiwu: A Multimodal Manipulation Dataset and Framework for Robot Learning and Human-Robot Interaction**](https://arxiv.org/abs/2503.05231) | arXiv | 2025-03-07 | - |  |
| [**AirExo-2: Scaling up Generalizable Robotic Imitation Learning with Low-Cost Exoskeletons**](https://arxiv.org/abs/2503.03081) | arXiv | 2025-03-05 | [Project](https://airexo.tech/airexo2/) |  |
| [**AVR: Active Vision-Driven Robotic Precision Manipulation with Viewpoint and Focal Length Optimization**](https://arxiv.org/abs/2503.01439) | arXiv | 2025-03-03 | [Project](https://avr-robot.github.io/) |  |
| [**DexUMI: Using Human Hand as the Universal Manipulation Interface for Dexterous Manipulation**](https://arxiv.org/abs/2505.21864) | RSSW 2025 | 2025-05-28 | ![Star](https://img.shields.io/github/stars/real-stanford/DexUMI?style=social&label=Star) [Github](https://github.com/real-stanford/DexUMI) |  |
| [**Reactive Diffusion Policy: Slow-Fast Visual-Tactile Policy Learning for Contact-Rich Manipulation**](https://arxiv.org/abs/2503.02881) | RSS 2025 | 2025-03-04 | ![Star](https://img.shields.io/github/stars/xiaoxiaoxh/reactive_diffusion_policy?style=social&label=Star) [Github](https://github.com/xiaoxiaoxh/reactive_diffusion_policy) | |
| [**ALPHA-α and Bi-ACT Are All You Need: Importance of Position and Force Information/Control for Imitation Learning of Unimanual and Bimanual Robotic Manipulation with Low-Cost System**](https://arxiv.org/abs/2411.09942) | IEEE Access 2025 | 2024-11-15 | [Project](https://mertcookimg.github.io/alpha-biact/) |  |
| [**ARCap: Collecting High-quality Human Demonstrations for Robot Learning with Augmented Reality Feedback**](https://arxiv.org/abs/2410.08464) | ICRA 2025 | 2024-10-11 | ![Star](https://img.shields.io/github/stars/Ericcsr/ARCap?style=social&label=Star) [Github](https://github.com/Ericcsr/ARCap) |  |
| [**Bunny-VisionPro: Real-Time Bimanual Dexterous Teleoperation for Imitation Learning**](https://arxiv.org/abs/2407.03162) | arXiv | 2024-07-03 | ![Star](https://img.shields.io/github/stars/Dingry/BunnyVisionPro?style=social&label=Star) [Github](https://github.com/Dingry/BunnyVisionPro) |  |
| [**A Perspective on AI-Guided Molecular Simulations in VR: Exploring Strategies for Imitation Learning in Hyperdimensional Molecular Systems**](https://arxiv.org/abs/2409.07189) | ECAIW 2024 | 2024-09-11 | - |  |
| [**GELLO: A General, Low-Cost, and Intuitive Teleoperation Framework for Robot Manipulators**](https://arxiv.org/abs/2309.13037) | IROS 2024 | 2023-09-22 | ![Star](https://img.shields.io/github/stars/wuphilipp/gello_software?style=social&label=Star) [Github](https://github.com/wuphilipp/gello_software) |  |
| [**EgoMimic: Scaling Imitation Learning via Egocentric Video**](https://arxiv.org/abs/2410.24221) | CoRLW 2024 | 2024-10-31 | ![Star](https://img.shields.io/github/stars/SimarKareer/EgoMimic?style=social&label=Star) [Github](https://github.com/SimarKareer/EgoMimic) | Bi, Aria Glasses |
| [**Active Vision Might Be All You Need: Exploring Active Vision in Bimanual Robotic Manipulation**](https://arxiv.org/abs/2409.17435) | CoRLW 2024 | 2024-09-26 | ![Star](https://img.shields.io/github/stars/soltanilara/av-aloha?style=social&label=Star) [Github](https://github.com/soltanilara/av-aloha) | Bi, VR |
| [**OPEN TEACH: A Versatile Teleoperation System for Robotic Manipulation**](https://arxiv.org/abs/2403.07870) | CoRL 2024 | 2024-03-12 | ![Star](https://img.shields.io/github/stars/aadhithya14/Open-Teach?style=social&label=Star) [Github](https://github.com/aadhithya14/Open-Teach) | |
| [**DexCap: Scalable and Portable Mocap Data Collection System for Dexterous Manipulation**](https://arxiv.org/abs/2403.07788) | CoRL 2024 | 2024-03-12 | ![Star](https://img.shields.io/github/stars/j96w/DexCap?style=social&label=Star) [Github](https://github.com/j96w/DexCap) | |
| [**Tilde: Teleoperation for Dexterous In-Hand Manipulation Learning with a DeltaHand**](https://arxiv.org/abs/2405.18804) | RSS 2024 | 2024-05-29 | ![Star](https://img.shields.io/github/stars/iamlab-cmu/DeltaHands?style=social&label=Star) [Github](https://github.com/iamlab-cmu/DeltaHands) | |
| [**Universal Manipulation Interface: In-The-Wild Robot Teaching Without In-The-Wild Robots**](https://arxiv.org/abs/2402.10329) | RSS 2024 | 2024-02-15 | ![Star](https://img.shields.io/github/stars/real-stanford/universal_manipulation_interface?style=social&label=Star) [Github](https://github.com/real-stanford/universal_manipulation_interface) | |
| [**TeleMoMa: A Modular and Versatile Teleoperation System for Mobile Manipulation**](https://arxiv.org/abs/2403.07869) | ICRAW 2024 | 2024-03-12 | ![Star](https://img.shields.io/github/stars/UT-Austin-RobIn/telemoma?style=social&label=Star) [Github](https://github.com/UT-Austin-RobIn/telemoma) | |
| [**AirExo: Low-Cost Exoskeletons for Learning Whole-Arm Manipulation in the Wild**](https://arxiv.org/abs/2309.14975) | ICRA 2024 | 2023-09-26 | ![Star](https://img.shields.io/github/stars/AirExo/collector?style=social&label=Star) [Github](https://github.com/AirExo/collector) | |
| [**AnyTeleop: A General Vision-Based Dexterous Robot Arm-Hand Teleoperation System**](https://arxiv.org/abs/2307.04577) | RSS 2023 | 2023-07-10 | [Project](https://yzqin.github.io/anyteleop/)  | |
| [**Training Robots without Robots: Deep Imitation Learning for Master-to-Robot Policy Transfer**](https://arxiv.org/abs/2202.09574) | RA-L 2023 | 2022-02-19 | - |  |
| [**Visual Imitation Made Easy**](https://arxiv.org/abs/2008.04899) | CoRL 2021 | 2020-8-11 | ![Star](https://img.shields.io/github/stars/sarahisyoung/Visual-Imitation-Made-Easy?style=social&label=Star) [Github](https://github.com/sarahisyoung/Visual-Imitation-Made-Easy) |  |
| [**Deep Imitation Learning for Complex Manipulation Tasks from Virtual Reality Teleoperation**](https://arxiv.org/abs/1710.04615) | ICRA 2018 | 2017-10-12 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Human-in-the-Loop Enhancement
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**CUPID: Curating Data your Robot Loves with Influence Functions**](https://arxiv.org/abs/2506.19121) | arXiv | 2025-06-23 | [Project](https://cupid-curation.github.io/) |  |
| [**Compliant Residual DAgger: Improving Real-World Contact-Rich Manipulation with Human Corrections**](https://arxiv.org/abs/2506.16685) | arXiv | 2025-06-20 | [Project](https://compliant-residual-dagger.github.io/) |  |
| [**IntervenGen: Interventional Data Generation for Robust and Data-Efficient Robot Imitation Learning**](https://arxiv.org/abs/2405.01472) | IROS 2024 | 2024-05-02 | [Project](https://sites.google.com/view/intervengen2024) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Automatic Generation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Constraint-Preserving Data Generation for Visuomotor Policy Learning**](https://arxiv.org/abs/2508.03944) | CoRL 2025 | 2025-08-11 | [Project](https://cp-gen.github.io/) |  |  
| [**HybridGen: VLM-Guided Hybrid Planning for Scalable Data Generation of Imitation Learning**](https://arxiv.org/abs/2503.13171) | arXiv | 2025-03-17 | - |  |  
| [**Physics-Driven Data Generation for Contact-Rich Manipulation via Trajectory Optimization**](https://arxiv.org/abs/2502.20382) | RSS 2025 | 2025-02-27 | [Project](https://lujieyang.github.io/physicsgen/) |  |  
| [**DemoGen: Synthetic Demonstration Generation for Data-Efficient Visuomotor Policy Learning**](https://arxiv.org/abs/2502.16932) | RSS 2025 | 2025-02-24 | ![Star](https://img.shields.io/github/stars/TEA-Lab/DemoGen?style=social&label=Star) [Github](https://github.com/TEA-Lab/DemoGen) |  |  
| [**Re<sup>3</sup>Sim: Generating High-Fidelity Simulation Data via 3D-Photorealistic Real-to-Sim for Robotic Manipulation**](https://arxiv.org/abs/2502.08645) | arXiv | 2025-02-12 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/Re3Sim?style=social&label=Star) [Github](https://github.com/OpenRobotLab/Re3Sim) |  | 
| [**DexMimicGen: Automated Data Generation for Bimanual Dexterous Manipulation via Imitation Learning**](https://arxiv.org/abs/2410.24185) | ICRA 2025 | 2024-10-31 | ![Star](https://img.shields.io/github/stars/NVlabs/dexmimicgen?style=social&label=Star) [Github](https://github.com/NVlabs/dexmimicgen) |  |  
| [**ARCADE: Scalable Demonstration Collection and Generation via Augmented Reality for Imitation Learning**](https://arxiv.org/abs/2410.15994) | IROS 2024 | 2024-10-21 | ![Star](https://img.shields.io/github/stars/YY-GX/ARCADE?style=social&label=Star) [Github](https://github.com/YY-GX/ARCADE/tree/Unity_ROS) |  |  
| [**MILES: Making Imitation Learning Easy with Self-Supervision**](https://arxiv.org/abs/2410.19693) | CoRL 2024 | 2024-10-25 | ![Star](https://img.shields.io/github/stars/gpapagiannis/miles-imitation?style=social&label=Star) [Github](https://github.com/gpapagiannis/miles-imitation) |  |
| [**SkillMimicGen: Automated Demonstration Generation for Efficient Skill Learning and Deployment**](https://arxiv.org/abs/2410.18907) | CoRL 2024 | 2024-10-24 | [Project](https://skillgen.github.io/) |  |
| [NILS: **Scaling Robot Policy Learning via Zero-Shot Labeling with Foundation Models**](https://arxiv.org/abs/2410.17772) | CoRL 2024 | 2024-10-23 | [Project](https://robottasklabeling.github.io/) |  |
| [SOAR: **Autonomous Improvement of Instruction Following Skills via Foundation Models**](https://arxiv.org/abs/2407.20635) | CoRL 2024 | 2024-07-30 | ![Star](https://img.shields.io/github/stars/rail-berkeley/soar?style=social&label=Star) [Github](https://github.com/rail-berkeley/soar) |  |
| [**Manipulate-Anything: Automating Real-World Robots using Vision-Language Models**](https://arxiv.org/abs/2406.18915) | CoRL 2024 | 2024-06-27 | [Project](https://robot-ma.github.io/) | |
| [**SPRINT: Scalable Policy Pre-Training via Language Instruction Relabeling**](https://arxiv.org/abs/2306.11886) | ICRA 2024 | 2023-06-20 | ![Star](https://img.shields.io/github/stars/clvrai/sprint?style=social&label=Star) [Github](https://github.com/clvrai/sprint) | |
| [**Offline Imitation Learning with Variational Counterfactual Reasoning**](https://arxiv.org/abs/2310.04706) | NeurIPS 2023 | 2023-10-07 | ![Star](https://img.shields.io/github/stars/ZexuSun/OILCA-NeurIPS23?style=social&label=Star) [Github](https://github.com/ZexuSun/OILCA-NeurIPS23) |  |
| [**MimicGen: A Data Generation System for Scalable Robot Learning using Human Demonstrations**](https://arxiv.org/abs/2310.17596) | CoRL 2023 | 2023-10-26 | ![Star](https://img.shields.io/github/stars/NVlabs/mimicgen?style=social&label=Star) [Github](https://github.com/NVlabs/mimicgen) |  |
| [**Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition**](https://arxiv.org/abs/2307.14535) | CoRL 2023 | 2023-07-26 | ![Star](https://img.shields.io/github/stars/real-stanford/scalingup?style=social&label=Star) [Github](https://github.com/real-stanford/scalingup) |  |
| [**RoboCat: A Self-Improving Generalist Agent for Robotic Manipulation**](https://arxiv.org/abs/2306.11706) | TMLR 2023 | 2023-06-20 | ![Star](https://img.shields.io/github/stars/kyegomez/RoboCAT?style=social&label=Star) [Github](https://github.com/kyegomez/RoboCAT) | |
| [DIAL: **Robotic Skill Acquisition via Instruction Augmentation with Vision-Language Models**](https://arxiv.org/abs/2211.11736) | RSS 2023 | 2022-11-21 | [Project](https://instructionaugmentation.github.io/) |  |
| [**SEIL: Simulation-augmented Equivariant Imitation Learning**](https://arxiv.org/abs/2211.00194) | ICRA 2023 | 2022-11-26 | ![Star](https://img.shields.io/github/stars/SaulBatman/SEIL?style=social&label=Star) [Github](https://github.com/SaulBatman/SEIL) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Crowdsourcing
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**EgoZero: Robot Learning from Smart Glasses**](https://arxiv.org/abs/2505.20290) | arXiv | 2025-05-26 | ![Star](https://img.shields.io/github/stars/vliu15/egozero?style=social&label=Star) [Github](https://github.com/vliu15/egozero) | Aria Glasses |  
| [**AR2-D2:Training a Robot Without a Robot**](https://arxiv.org/abs/2306.13818) | CoRL 2023 | 2023-06-23 | ![Star](https://img.shields.io/github/stars/jiafei1224/AR2-D2?style=social&label=Star) [Github](https://github.com/jiafei1224/AR2-D2) |  |
| [**Learning Multi-Arm Manipulation Through Collaborative Teleoperation**](https://arxiv.org/abs/2012.06738) | ICRA 2021 | 2020-12-12 | [Project](https://roboturk.stanford.edu/multiarm) |  |
| [**Scaling Robot Supervision to Hundreds of Hours with RoboTurk: Robotic Manipulation Dataset through Human Reasoning and Dexterity**](https://arxiv.org/abs/1911.04052) | IROS 2019 | 2019-11-11 | [Project](https://roboturk.stanford.edu/realrobotdataset) |  |
| [**RoboTurk: A Crowdsourcing Platform for Robotic Skill Learning through Imitation**](https://arxiv.org/abs/1811.02790) | CoRL 2018 | 2018-11-07 | [Project](https://roboturk.stanford.edu/) |  |
| [**Accelerating Imitation Learning through Crowdsourcing**](https://ieeexplore.ieee.org/document/6907558) | ICRA 2014 | 2014-09-29 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>


<!-- Data Utilization -->
<div align="center">

### <i>Data Utilization</i>

</div>

### Data Expansion
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**DataPlatter: Boosting Robotic Manipulation Generalization with Minimal Costly Data**](https://arxiv.org/abs/2503.19516) | arXiv | 2025-03-25 | ![Star](https://img.shields.io/github/stars/notFoundThisPerson/RoboTron-Craft?style=social&label=Star) [Github](https://github.com/notFoundThisPerson/RoboTron-Craft) |  |
| [**TASTE-Rob: Advancing Video Generation of Task-Oriented Hand-Object Interaction for Generalizable Robotic Manipulation**](https://arxiv.org/abs/2503.11423) | CVPR 2025 | 2025-03-14 | ![Star](https://img.shields.io/github/stars/GAP-LAB-CUHK-SZ/TASTE-Rob?style=social&label=Star) [Github](https://github.com/GAP-LAB-CUHK-SZ/TASTE-Rob) | Video Generation |
| [**Diff-DAgger: Uncertainty Estimation with Diffusion Policy for Robotic Manipulation**](https://arxiv.org/abs/2410.14868) | ICRA 2025 | 2024-10-18 | ![Star](https://img.shields.io/github/stars/sean1295/DiffDAgger?style=social&label=Star) [Github](https://github.com/sean1295/DiffDAgger) |  |
| [**JUICER: Data-Efficient Imitation Learning for Robotic Assembly**](https://arxiv.org/abs/2507.06219) | IROS 2024 | 2024-04-04 | ![Star](https://img.shields.io/github/stars/ankile/imitation-juicer?style=social&label=Star) [Github](https://github.com/ankile/imitation-juicer) |  |
| [**Learning Category-Level Generalizable Object Manipulation Policy via Generative Adversarial Self-Imitation Learning from Demonstrations**](https://arxiv.org/abs/2203.02107) | RA-L 2022 | 2022-03-04 | ![Star](https://img.shields.io/github/stars/wkwan7/Category_Level_Manipulation?style=social&label=Star) [Github](https://github.com/wkwan7/Category_Level_Manipulation) | GAIL |
| [**Self-Imitation Learning by Planning**](https://arxiv.org/abs/2103.13834) | ICRA 2021 | 2021-03-25 | - |  |
| [**SAFARI: Safe and Active Robot Imitation Learning with Imagination**](https://arxiv.org/abs/2011.09586) | NeurIPSW 2020 | 2020-11-18 | [Project](https://www.robot-learning.uk/safari) |  |
| [**Scalable Multi-Task Imitation Learning with Autonomous Improvement**](https://arxiv.org/abs/2003.02636) | ICRA 2020 | 2020-03-25 | [Project](https://sites.google.com/view/scalable-mili/) |  |
| [**Generative predecessor models for sample-efficient imitation learning**](https://arxiv.org/abs/1904.01139) | ICLR 2019 | 2019-04-01 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Data Reweighting
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Towards Balanced Behavior Cloning from Imbalanced Datasets**](https://arxiv.org/abs/2508.06319) | arXiv | 2025-08-08 | [Project](https://collab.me.vt.edu/data_curation/) |  |
| [**Policy Learning from Large Vision-Language Model Feedback without Reward Modeling**](https://arxiv.org/abs/2507.23391) | IROS 2025 | 2025-07-31 | ![Star](https://img.shields.io/github/stars/tunglm2203/plare?style=social&label=Star) [Github](https://github.com/tunglm2203/plare) |  |
| [**Feasibility-aware Imitation Learning from Observations through a Hand-mounted Demonstration Interface**](https://arxiv.org/abs/2503.09018) | arXiv | 2025-03-12 | - |  |
| [**Imitation Learning by Estimating Expertise of Demonstrators**](https://arxiv.org/abs/2202.01288) | ICML 2022 | 2022-02-02 | ![Star](https://img.shields.io/github/stars/Stanford-ILIAD/ILEED?style=social&label=Star) [Github](https://github.com/Stanford-ILIAD/ILEED) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Data Selection
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Is Diversity All You Need for Scalable Robotic Manipulation?**](https://arxiv.org/abs/2507.06219) | arXiv | 2025-07-08 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/AgiBot-World?style=social&label=Star) [Github](https://github.com/OpenDriveLab/AgiBot-World) |  |
| [**SCIZOR: A Self-Supervised Approach to Data Curation for Large-Scale Imitation Learning**](https://arxiv.org/abs/2505.22626) | arXiv | 2025-05-28 | [Project](https://ut-austin-rpl.github.io/SCIZOR/) |  |
| [**DataMIL: Selecting Data for Robot Imitation Learning with Datamodels**](https://arxiv.org/abs/2505.09603) | arXiv | 2025-05-14 | [Project](https://robin-lab.cs.utexas.edu/datamodels4imitation/) |  |
| [**Guiding Data Collection via Factored Scaling Curves**](https://arxiv.org/abs/2505.07728) | arXiv | 2025-05-12 | [Project](https://factored-data-scaling.github.io/) |  |  
| [**Robot Data Curation with Mutual Information Estimators**](https://arxiv.org/abs/2502.08623) | arXiv | 2025-02-12 | [Project](https://joeyhejna.com/demonstration-info/) |  |
| [**What Matters in Learning from Large-Scale Datasets for Robot Manipulation**](https://openreview.net/forum?id=LqhorpRLIm) | ICLR 2025 | 2025-01-23 | [Project](https://mimiclabs-iclr.github.io/) |  |
| [**How to Train Your Robots? The Impact of Demonstration Modality on Imitation Learning**](https://arxiv.org/abs/2503.07017) | ICRA 2025 | 2025-03-10 | - |  |
| [AMF: **Active Fine-Tuning of Generalist Policies**](https://arxiv.org/abs/2410.05026) | arXiv | 2024-10-07 | - |  |
| [**Re-Mix: Optimizing Data Mixtures for Large Scale Imitation Learning**](https://arxiv.org/abs/2408.14037) | CoRL 2024 | 2024-08-26 | ![Star](https://img.shields.io/github/stars/jhejna/remix?style=social&label=Star) [Github](https://github.com/jhejna/remix) |  |
| [**How to Leverage Diverse Demonstrations in Offline Imitation Learning**](https://arxiv.org/abs/2405.17476) | ICML 2024 | 2024-05-24 | ![Star](https://img.shields.io/github/stars/HansenHua/ILID-ICML24?style=social&label=Star) [Github](https://github.com/HansenHua/ILID-ICML24) |  |
| [**Learning from Imperfect Demonstrations with Self-Supervision for Robotic Manipulation**](https://arxiv.org/abs/2401.08957) | arXiv | 2024-01-17 | - | |
| [**Learning to Discern: Imitating Heterogeneous Human Demonstrations with Preference and Representation Learning**](https://arxiv.org/abs/2310.14196) | CoRL 2023 | 2023-10-22 | - |  |
| [**Data Quality in Imitation Learning**](https://arxiv.org/abs/2306.02437) | NeurIPS 2023 | 2023-06-04 | - |  |
| [**An Unbiased Look at Datasets for Visuo-Motor Pre-Training**](https://arxiv.org/abs/2310.09289) | CoRL 2023 | 2023-10-13 | ![Star](https://img.shields.io/github/stars/SudeepDasari/data4robotics?style=social&label=Star) [Github](https://github.com/SudeepDasari/data4robotics) |  |
| [**Extraneousness-Aware Imitation Learning**](https://arxiv.org/abs/2210.01379) | ICRA 2023 | 2022-10-04 | ![Star](https://img.shields.io/github/stars/zhengrc19/eil-code?style=social&label=Star) [Github](https://github.com/zhengrc19/eil-code) |  |
| [**Eliciting Compatible Demonstrations for Multi-Human Imitation Learning**](https://arxiv.org/abs/2210.08073) | CoRL 2022 | 2022-10-14 | ![Star](https://img.shields.io/github/stars/kanishkg/elicit?style=social&label=Star) [Github](https://github.com/kanishkg/elicit) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Data Retrieval
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**COLLAGE: Adaptive Fusion-based Retrieval for Augmented Policy Learning**](https://arxiv.org/abs/2508.01131) | CoRL 2025 | 2025-08-11 | [Project](https://robin-lab.cs.utexas.edu/COLLAGE/) | |
| [**Retrieve-Augmented Generation for Speeding up Diffusion Policy without Additional Training**](https://arxiv.org/abs/2507.21452) | arXiv | 2025-07-29 | - | |
| [**STRAP: Robot Sub-Trajectory Retrieval for Augmented Policy Learning**](https://arxiv.org/abs/2412.15182) | ICLR 2025 | 2024-12-19 | [Project](https://weirdlabuw.github.io/strap/) | |
| [**FlowRetrieval: Flow-Guided Data Retrieval for Few-Shot Imitation Learning**](https://arxiv.org/abs/2408.16944) | CoRL 2024 | 2024-08-29 | ![Star](https://img.shields.io/github/stars/lihenglin/bridge_training_code?style=social&label=Star) [Github](https://github.com/lihenglin/bridge_training_code) | |
| [**Offline Imitation Learning Through Graph Search and Retrieval**](https://arxiv.org/abs/2407.15403) | RSS 2024 | 2024-07-22 | [Project](https://zhaohengyin.github.io/gsr/) | |
| [**Retrieval-Augmented Embodied Agents**](https://arxiv.org/abs/2404.11699) | CVPR 2024 | 2024-04-17 | - | |
| [**DINOBot: Robot Manipulation via Retrieval and Alignment with Vision Foundation Models**](https://arxiv.org/abs/2402.13181) | ICRA 2024 | 2024-02-20 | [GitHub Gist](https://gist.github.com/normandipalo/fbc21f23606fbe3d407e22c363cb134e) | |
| [**On the Effectiveness of Retrieval, Alignment, and Replay in Manipulation**](https://arxiv.org/abs/2312.12345) | RA-L 2024 | 2023-12-19 | [Project](https://www.robot-learning.uk/retrieval-alignment-replay) | |
| [**Behavior Retrieval: Few-Shot Imitation Learning by Querying Unlabeled Datasets**](https://arxiv.org/abs/2304.08742) | RSS 2023 | 2023-04-08 | ![Star](https://img.shields.io/github/stars/MaxDu17/BehaviorRetrieval?style=social&label=Star) [Github](https://github.com/MaxDu17/BehaviorRetrieval) | |
| [**Learning and Retrieval from Prior Data for Skill-based Imitation Learning**](https://arxiv.org/abs/2210.11435) | CoRL 2022 | 2022-10-20 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/sailor?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/sailor) | |
| [**The Surprising Effectiveness of Representation Learning for Visual Imitation**](https://arxiv.org/abs/2112.01511) | RSS 2022 | 2021-12-02 | ![Star](https://img.shields.io/github/stars/jyopari/VINN?style=social&label=Star) [Github](https://github.com/jyopari/VINN) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Data Augmentation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Masquerade: Learning from In-the-wild Human Videos using Data-Editing**](https://arxiv.org/abs/2508.09976) | arXiv | 2025-08-13 | [Project](https://masquerade-robot.github.io/) |  |
| [**Shortcut Learning in Generalist Robot Policies: The Role of Dataset Diversity and Fragmentation**](https://arxiv.org/abs/2508.06426) | CoRL 2025 | 2025-08-08 | [Project](https://lucky-light-sun.github.io/proj/shortcut-learning-in-grps/) |  |
| [**RoboPearls: Editable Video Simulation for Robot Manipulation**](https://arxiv.org/abs/2506.22756) | ICCV 2025 | 2025-06-28 | [Project](https://tangtaogo.github.io/RoboPearls/) |  |
| [**ControlTac: Force- and Position-Controlled Tactile Data Augmentation with a Single Reference Image**](https://arxiv.org/abs/2505.20498) | arXiv | 2025-05-26 | [Project](https://dongyuluo.github.io/controltac/) |
| [**H2R: A Human-to-Robot Data Augmentation for Robot Pre-training from Videos**](https://arxiv.org/abs/2505.11920) | CVPRW 2025 | 2025-05-17 | - |  |
| [**Robust Offline Imitation Learning Through State-level Trajectory Stitching**](https://arxiv.org/abs/2503.22524) | arXiv | 2025-03-28 | - |  |
| [**RoboEngine: Plug-and-Play Robot Data Augmentation with Semantic Robot Segmentation and Background Generation**](https://arxiv.org/abs/2503.18738) | arXiv | 2025-03-24 | ![Star](https://img.shields.io/github/stars/michaelyuancb/roboengine?style=social&label=Star) [Github](https://github.com/michaelyuancb/roboengine) |  |
| [**Predictive Red Teaming: Breaking Policies Without Breaking Robots**](https://arxiv.org/abs/2502.06575) | arXiv | 2025-02-10 | [Project](https://predictive-red-team.github.io/) |  |
| [**RoCoDA: Counterfactual Data Augmentation for Data-Efficient Robot Learning from Demonstrations**](https://arxiv.org/abs/2411.16959) | arXiv | 2024-11-25 | [Project](https://rocoda.github.io/) |  |
| [**Stem-OB: Generalizable Visual Imitation Learning with Stem-Like Convergent Observation through Diffusion Inversion**](https://arxiv.org/abs/2411.04919) | arXiv | 2024-11-07 | ![Star](https://img.shields.io/github/stars/hukz18/Stem-Ob-Code?style=social&label=Star) [Github](https://github.com/hukz18/Stem-Ob-Code) |  |
| [**DABI: Evaluation of Data Augmentation Methods Using Downsampling in Bilateral Control-Based Imitation Learning with Images**](https://arxiv.org/abs/2410.04370) | ICRA 2025 | 2024-10-06 | [Project](https://mertcookimg.github.io/dabi/) |  |
| [**Towards Effective Utilization of Mixed-Quality Demonstrations in Robotic Manipulation via Segment-Level Selection and Optimization**](https://arxiv.org/abs/2409.19917) | ICRA 2025 | 2024-09-30 | ![Star](https://img.shields.io/github/stars/junxix/s2i?style=social&label=Star) [Github](https://github.com/junxix/s2i) |  |
| [**Green Screen Augmentation Enables Scene Generalisation in Robotic Manipulation**](https://arxiv.org/abs/2407.07868) | arXiv | 2024-07-10 | ![Star](https://img.shields.io/github/stars/eugeneteoh/greenaug?style=social&label=Star) [Github](https://github.com/eugeneteoh/greenaug) |  |
| [**View-Invariant Policy Learning via Zero-Shot Novel View Synthesis**](https://arxiv.org/abs/2409.03685) | CoRL 2024 | 2024-09-05 | ![Star](https://img.shields.io/github/stars/s-tian/VISTA?style=social&label=Star) [Github](https://github.com/s-tian/VISTA) |  |
| [**RoVi-Aug: Robot and Viewpoint Augmentation for Cross-Embodiment Robot Learning**](https://arxiv.org/abs/2409.03403) | CoRL 2024 | 2024-09-05 | [Project](https://rovi-aug.github.io/) |  |
| [GENIMA: **Generative Image as Action Models**](https://arxiv.org/abs/2407.07875) | CoRL 2024 | 2024-07-10 | ![Star](https://img.shields.io/github/stars/MohitShridhar/genima?style=social&label=Star)  [Github](https://github.com/MohitShridhar/genima) |  |
| [**RT-Sketch: Goal-Conditioned Imitation Learning from Hand-Drawn Sketches**](https://arxiv.org/abs/2403.02709) | CoRL 2024 | 2024-03-05 | [Project](https://rt-sketch.github.io/) | Sketch |
| [**Diffusion Augmented Agents: A Framework for Efficient Exploration and Transfer Learning**](https://arxiv.org/abs/2407.20798) | CoLLAs 2024 | 2024-07-30 | [Project](https://sites.google.com/view/diffusion-augmented-agents/) |  |
| [**Diffusion Meets DAgger: Supercharging Eye-in-hand Imitation Learning**](https://arxiv.org/abs/2402.17768) | RSS 2024 | 2023-02-27 | ![Star](https://img.shields.io/github/stars/ErinZhang1998/dmd_diffusion?style=social&label=Star) [Github](https://github.com/ErinZhang1998/dmd_diffusion) | |
| [**Offline Imitation Learning with Variational Counterfactual Reasoning**](https://arxiv.org/abs/2310.04706) | NeurIPSS 2023 | 2023-10-07 | ![Star](https://img.shields.io/github/stars/ZexuSun/OILCA-NeurIPS23?style=social&label=Star) [Github](https://github.com/ZexuSun/OILCA-NeurIPS23) |  |
| [ROSIE: **Scaling Robot Learning with Semantically Imagined Experience**](https://arxiv.org/abs/2302.11550) | RSS 2023 | 2023-02-22 | [Project](https://diffusion-rosie.github.io/) |  |
| [**GenAug: Retargeting behaviors to unseen situations via Generative Augmentation**](https://arxiv.org/abs/2302.06671) | RSS 2023 | 2023-02-13 | ![Star](https://img.shields.io/github/stars/genaug/genaug?style=social&label=Star) [Github](https://github.com/genaug/genaug) |  |
| [**Identifying Expert Behavior in Offline Training Datasets Improves Behavioral Cloning of Robotic Manipulation Policies**](https://arxiv.org/abs/2301.13019) | RA-L 2023 | 2023-01-30 | ![Star](https://img.shields.io/github/stars/genaug/genaug?style=social&label=Star) [Github](https://github.com/genaug/genaug) |  |
| [**Data Augmentation for Manipulation**](https://arxiv.org/abs/2205.02886) | RSS 2022 | 2022-05-05 | ![Star](https://img.shields.io/github/stars/UM-ARM-Lab/data-augmentation-for-manipulation?style=social&label=Star) [Github](https://github.com/UM-ARM-Lab/data-augmentation-for-manipulation) |  |
| [**Goal-conditioned Imitation Learning**](https://arxiv.org/abs/1906.05838) | NeurIPS 2019 | 2019-06-13 | ![Star](https://img.shields.io/github/stars/dingyiming0427/goalgail?style=social&label=Star) [Github](https://github.com/dingyiming0427/goalgail) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>



## Learning Strategy

<div align="center">

### <i>Imitation Learning (IL)</i>

</div>

### Imitation Learning from Action
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Sampling / Search-based IL_ |
| [**A Smooth Sea Never Made a Skilled SAILOR: Robust Imitation via Learning to Search**](https://arxiv.org/abs/2506.05294) | arXiv | 2025-06-05 | ![Star](https://img.shields.io/github/stars/arnavkj1995/SAILOR?style=social&label=Star) [Github](https://github.com/arnavkj1995/SAILOR) |  |
| [**A Structured Prediction Approach for Robot Imitation Learning**](https://arxiv.org/abs/2309.14829) | IJRR 2024 | 2023-09-26 | - | Search-based IL |
| [**Guided Imitation of Task and Motion Planning**](https://arxiv.org/abs/2112.03386) | CoRL 2021 | 2021-12-06 | - |  |
| [**Learning to Search: Functional Gradient Techniques for Imitation Learning**](https://link.springer.com/article/10.1007/s10514-009-9121-3) | AR 2009 | 2009-06-17 | - | Search-based IL |
| [**Discovering Otimal Imitation Strategies**](https://www.sciencedirect.com/science/article/abs/pii/S0921889004000387) | RAS 2004 | 2004-05-18 | - | Search-based IL |
| _Optimization-based IL_ |
| [**Contractive Dynamical Imitation Policies for Efficient Out-of-Sample Recovery**](https://arxiv.org/abs/2412.07544) | ICLR 2025 | 2024-12-10 | ![Star](https://img.shields.io/github/stars/aminabyaneh/scds-contractive-imitation?style=social&label=Star) [Github](https://github.com/aminabyaneh/scds-contractive-imitation) |  |
| [**Neural ODE-based Imitation Learning (NODE-IL): Data-Efficient Imitation Learning for Long-Horizon Multi-Skill Robot Manipulation**](https://ieeexplore.ieee.org/document/10802736/) | IROS 2024 | 2024-12-25 | - | MPC + IL |
| [**A Comparison of Imitation Learning Algorithms for Bimanual Manipulation**](https://arxiv.org/abs/2408.06536) | RA-L 2024 | 2024-08-13 | ![Star](https://img.shields.io/github/stars/ir-lab/bimanual-imitation?style=social&label=Star) [Github](https://github.com/ir-lab/bimanual-imitation) |  |
| [**LeTO: Learning Constrained Visuomotor Policy with Differentiable Trajectory Optimization**](https://arxiv.org/abs/2401.17500) | TASE 2024 | 2024-01-30 | ![Star](https://img.shields.io/github/stars/ZhengtongXu/LeTO?style=social&label=Star) [Github](https://github.com/ZhengtongXu/LeTO) |  |
| [**Optimizing Demonstrated Robot Manipulation Skills for Temporal Logic Constraints**](https://arxiv.org/abs/2209.03001) | IROS 2022 | 2022-09-07 | - |  |
| [**Learning Context-Adaptive Task Constraints for Robotic Manipulation**](https://arxiv.org/abs/2008.02610) | RAS 2021 | 2020-08-06 | - |  |
| _Movement Primitives-based IL_ |
| [**Dynamical System-based Imitation Learning for Visual Servoing using the Large Projection Formulation**](https://ieeexplore.ieee.org/document/10160935) | ICRA 2023 | 2023-07-04 | - |  |
| [**A Framework of Hybrid Force/Motion Skills Learning for Robots**](https://ieeexplore.ieee.org/document/8964480) | TCDS 2020 | 2020-01-22 | - |  |
| [**Combining Imitation Learning With Constraint-Based Task Specification and Control**](https://ieeexplore.ieee.org/document/8637010) | RA-L 2019 | 2019-02-07 | - |  |
| [**Generalizing Robot Imitation Learning with Invariant Hidden Semi-Markov Models**](https://arxiv.org/abs/1811.07489) | WAFR 2018 | 2018-11-19 | - |  |
| [**Towards Learning of Generic Skills for Robotic Manipulation**](https://www.dfki.de/fileadmin/user_upload/import/7056_131009_Towards_Learning_of_Generic_Skills_for_Robotic_Manipulation_KI_Metzen.pdf) | KI 2014 | 2013-12-03 | - |  |
| _Behavior Cloning (BC) from Action_|
| [**CIVIL: Causal and Intuitive Visual Imitation Learning**](https://arxiv.org/abs/2504.17959) | arXiv | 2025-04-22 | ![Star](https://img.shields.io/github/stars/CIVIL2025/Implementation?style=social&label=Star) [Github](https://github.com/CIVIL2025/Implementation) |  |
| [**SPECI: Skill Prompts based Hierarchical Continual Imitation Learning for Robot Manipulation**](https://arxiv.org/abs/2504.15561) | arXiv | 2025-04-22 | - |  |
| [**GenOSIL: Generalized Optimal and Safe Robot Control using Parameter-Conditioned Imitation Learning**](https://arxiv.org/abs/2503.12243) | arXiv | 2025-03-15 | [Project](https://mumukshtayal.github.io/GenOSIL/) |  |
| [**Action-Constrained Imitation Learning**](https://arxiv.org/pdf/2508.14379) | ICML 2025 | 2025-08-20 | ![Star](https://img.shields.io/github/stars/NYCU-RL-Bandits-Lab/ACRL-Baselines?style=social&label=Star) [Github](https://github.com/NYCU-RL-Bandits-Lab/ACRL-Baselines) |  |
| [**Behavioral Exploration: Learning to Explore via In-Context Adaptation**](https://arxiv.org/abs/2507.09041) | ICML 2025 | 2025-07-11 | - |  |
| [**Learning to Transfer Human Hand Skills for Robot Manipulations**](https://arxiv.org/abs/2501.04169) | arXiv | 2025-01-07 | [Project](https://rureadyo.github.io/MocapRobot/) |  |
| [**Effective Tuning Strategies for Generalist Robot Manipulation Policies**](https://arxiv.org/abs/2410.01220) | arXiv | 2024-10-02 | - | |
| [**Data Scaling Laws in Imitation Learning for Robotic Manipulation**](https://arxiv.org/abs/2410.18647) | ICLR 2025 | 2024-10-24 | ![Star](https://img.shields.io/github/stars/Fanqi-Lin/Data-Scaling-Laws?style=social&label=Star) [Github](https://github.com/Fanqi-Lin/Data-Scaling-Laws) | |
| [**Imitating Task and Motion Planning with Visuomotor Transformers**](https://arxiv.org/abs/2305.16309) | CoRL 2023 | 2023-05-25 | ![Star](https://img.shields.io/github/stars/NVlabs/Optimus?style=social&label=Star) [Github](https://github.com/NVlabs/Optimus) |  |
| [**CACTI: A Framework for Scalable Multi-Task Multi-Scene Visual Imitation Learning**](https://arxiv.org/abs/2212.05711) | CoRLW 2022 | 2022-12-12 | [Project](https://cacti-framework.github.io/) |  |
| [**End-to-End Stable Imitation Learning via Autonomous Neural Dynamic Policies**](https://arxiv.org/abs/2305.12886) | ICRAW 2023 | 2023-05-22 | - |  |
| [**Masked Imitation Learning: Discovering Environment-Invariant Modalities in Multimodal Demonstrations**](https://arxiv.org/abs/2209.07682) | arXiv | 2022-09-16 | [Project](https://sites.google.com/view/mask-imitation-learning) |  |
| [**Imitation Learning with Additional Constraints on Motion Style using Parametric Bias**](https://arxiv.org/abs/2407.08057) | RA-L 2021 | 2021-07-10 | - |  |
| [**Transformer-based Deep Imitation Learning for Dual-arm Robot Manipulation**](https://arxiv.org/abs/2108.00385) | IROS 2021 | 2021-08-01 | [Project](https://sites.google.com/view/multi-task-fine) |  |
| [HDR‑IL: **Deep Imitation Learning for Bimanual Robotic Manipulation**](https://arxiv.org/abs/2010.05134) | NeurIPS 2020 | 2020-10-11 | ![Star](https://img.shields.io/github/stars/Rose-STL-Lab/HDR-IL?style=social&label=Star) [Github](https://github.com/Rose-STL-Lab/HDR-IL) |  |
| [**Imitation Learning Based on Bilateral Control for Human–Robot Cooperation**](https://arxiv.org/abs/1909.13018) | RA-L 2020 | 2019-09-28 | - | |
| [**Non-parametric Imitation Learning of Robot Motor Skills**](https://ieeexplore.ieee.org/document/8794267) | ICRA 2019 | 2019-08-12 | - | Non‑parametric BC |
| [**Imitation Learning as Cause-Effect Reasoning**](https://www.academia.edu/100336403/Imitation_Learning_as_Cause_Effect_Reasoning) | ICAGI 2016 | 2016-06-25 | - |  |
| _Behavior Cloning (BC) from Pose_|
| [**Exploring Pose-Guided Imitation Learning for Robotic Precise Insertion**](https://arxiv.org/abs/2505.09424) | arXiv | 2025-05-14 | ![Star](https://img.shields.io/github/stars/sunhan1997/PoseInsert?style=social&label=Star) [Github](https://github.com/sunhan1997/PoseInsert) |  |
| [**ZeroMimic: Distilling Robotic Manipulation Skills from Web Videos**](https://arxiv.org/abs/2503.23877) | ICRA 2025 | 2025-03-31 | ![Star](https://img.shields.io/github/stars/junyaoshi/ZeroMimic?style=social&label=Star) [Github](https://github.com/junyaoshi/ZeroMimic) |  |
| [**RiEMann: Near Real-Time SE(3)-Equivariant Robot Manipulation without Point Cloud Segmentation**](https://arxiv.org/abs/2403.19460) | CoRL 2024 | 2024-03-28 | ![Star](https://img.shields.io/github/stars/HeegerGao/RiEMann?style=social&label=Star) [Github](https://github.com/HeegerGao/RiEMann) |  |
| _Inverse Reinforcement Learning (IRL)_ |
| [**SPRINQL: Sub-optimal Demonstrations driven Offline Imitation Learning**](https://arxiv.org/abs/2402.13147) | NeurIPS 2024 | 2024-02-20 | ![Star](https://img.shields.io/github/stars/hmhuy0/SPRINQL?style=social&label=Star) [Github](https://github.com/hmhuy0/SPRINQL) |  |
| [**GenH2R: Learning Generalizable Human-to-Robot Handover via Scalable Simulation, Demonstration, and Imitation**](https://arxiv.org/abs/2401.00929) | CVPR 2024 | 2024-01-01  | ![Star](https://img.shields.io/github/stars/chenjy2003/genh2r?style=social&label=Star) [Github](https://github.com/chenjy2003/genh2r)  |
| [**A Divergence Minimization Perspective on Imitation Learning Methods**](https://arxiv.org/abs/1911.02256) | CoRL 2021 | 2021-11-06 | ![Star](https://img.shields.io/github/stars/KamyarGh/rl_swiss?style=social&label=Star) [Github](https://github.com/KamyarGh/rl_swiss/blob/master/reproducing/fmax_paper.md) | |
| [**Inverse KKT: Learning cost functions of manipulation tasks from demonstrations**](https://journals.sagepub.com/doi/abs/10.1177/0278364917745980) | IJRR 2017 | 2017-12-05 | - |  |
| _Adversarial IL_ |
| [**Visually Robust Adversarial Imitation Learning from Videos with Contrastive Learning**](https://arxiv.org/abs/2407.12792) | arXiv | 2024-07-18 | - |  |
| [**OLLIE: Imitation Learning from Offline Pretraining to Online Finetuning**](https://arxiv.org/abs/2405.17477) | ICML 2024 | 2024-05-24 | - | IL + GAIL |
| [**Diffusion-Reward Adversarial Imitation Learning**](https://arxiv.org/abs/2405.16194) | NeurIPS 2024 | 2024-05-25 | ![Star](https://img.shields.io/github/stars/NVlabs/DRAIL?style=social&label=Star) [Github](https://github.com/NVlabs/DRAIL) |  |
| [**Learning from Guided Play: Improving Exploration for Adversarial Imitation Learning with Simple Auxiliary Tasks**](https://arxiv.org/abs/2301.00051) | arXiv | 2022-12-30 | ![Star](https://img.shields.io/github/stars/utiasSTARS/lfgp?style=social&label=Star) [Github](https://github.com/utiasSTARS/lfgp) |  |
| [**Adversarial Imitation Learning with Preferences**](https://openreview.net/forum?id=bhfp5GlDtGe) | ICLR 2023 | 2023-02-02 | - | |
| [LAPAL: **Latent Policies for Adversarial Imitation Learning**](https://arxiv.org/abs/2206.11299) | arXiv | 2022-06-22 | ![Star](https://img.shields.io/github/stars/tianyudwang/LAPAL?style=social&label=Star) [Github](https://github.com/tianyudwang/LAPAL) |  |
| [DMIL: **Discriminator-Guided Model-Based Offline Imitation Learning**](https://arxiv.org/abs/2207.00244) | CoRL 2022 | 2022-07-01 | - |  |
| [**ARC - Actor Residual Critic for Adversarial Imitation Learning**](https://arxiv.org/abs/2206.02095) | CoRL 2022 | 2022-06-05 | ![Star](https://img.shields.io/github/stars/Ankur-Deka/Actor-Residual-Critic?style=social&label=Star) [Github](https://github.com/Ankur-Deka/Actor-Residual-Critic) |  |
| [LfGP: **Learning from Guided Play: A Scheduled Hierarchical Approach for Improving Exploration in Adversarial Imitation Learning**](https://arxiv.org/abs/2112.08932) | NeurIPSW 2021 | 2021-12-16 | ![Star](https://img.shields.io/github/stars/utiasSTARS/lfgp?style=social&label=Star) [Github](https://github.com/utiasSTARS/lfgp) |  |
| [V-MAIL: **Visual Adversarial Imitation Learning using Variational Models**](https://arxiv.org/abs/2107.08829) | NeurIPS 2021 | 2021-06-10 | ![Star](https://img.shields.io/github/stars/rmrafailov/VMAIL?style=social&label=Star) [Github](https://github.com/rmrafailov/VMAIL) |  |
| [**What Matters for Adversarial Imitation Learning?**](https://arxiv.org/abs/2106.00672) | NeurIPS 2021 | 2021-06-10 | - |  |
| [Option-GAIL: **Adversarial Option-Aware Hierarchical Imitation Learning**](https://arxiv.org/abs/2106.05530) | ICML 2021 | 2021-06-10 | - |  |
| [**Adversarial Imitation Learning with Trajectorial Augmentation and Correction**](https://arxiv.org/abs/2103.13887) | ICRA 2021 | 2021-03-25 | - |  |
| _Latent Learning IL_ |
| [**Latent Policy Barrier: Learning Robust Visuomotor Policies by Staying In-Distribution**](https://arxiv.org/abs/2508.05941) | arXiv | 2025-08-08 | [Project](https://project-latentpolicybarrier.github.io/) |  |
| [**Rethinking Latent Redundancy in Behavior Cloning: An Information Bottleneck Approach for Robot Manipulation**](https://arxiv.org/abs/2502.02853) | ICML 2025 | 2025-02-05 | ![Star](https://img.shields.io/github/stars/BaiShuanghao/BC-IB?style=social&label=Star) [Github](https://github.com/BaiShuanghao/BC-IB) |  |
| [**Generalization Capability for Imitation Learning**](https://arxiv.org/abs/2504.18538) | arXiv | 2025-04-25 | - |  |
| [**Memory-Consistent Neural Networks for Imitation Learning**](https://arxiv.org/abs/2310.06171) | ICLR 2024 | 2023-10-09 | ![Star](https://img.shields.io/github/stars/kaustubhsridhar/MCNN?style=social&label=Star) [Github](https://github.com/kaustubhsridhar/MCNN) |  |
| [**A System for Imitation Learning of Contact-Rich Bimanual Manipulation Policies**](https://arxiv.org/abs/2208.00596) | IROS 2022 | 2022-08-01 | ![Star](https://img.shields.io/github/stars/ir-lab/irl_control?style=social&label=Star) [Github](https://github.com/ir-lab/irl_control/tree/iros2022-dev/irl_control/learning) |  |
| [**Robotic Manipulation Skill Acquisition Via Demonstration Policy Learning**](https://ieeexplore.ieee.org/document/9471764) | TCDS 2021 | 2025-07-02 | - | Temporal |
| [**Vision-based Robot Manipulation Learning via Human Demonstrations**](https://arxiv.org/abs/2003.00385) | arXiv | 2020-03-01 | - | Temporal |
| [**Generalization Guarantees for Imitation Learning**](https://arxiv.org/abs/2008.01913) | CoRL 2020 | 2020-08-05 | ![Star](https://img.shields.io/github/stars/irom-princeton/PAC-Imitation?style=social&label=Star) [Github](https://github.com/irom-princeton/PAC-Imitation) |  |
| [**Task-Relevant Adversarial Imitation Learning**](https://arxiv.org/abs/1910.01077) | CoRL 2020 | 2019-10-02 | - |  |
| [**Imitation Learning from Visual Data with Multiple Intentions**](https://openreview.net/forum?id=Hk3ddfWRW) | ICLR 2018 | 2018-02-16 | - |  |
| [**An Approach for Imitation Learning on Riemannian Manifolds**](https://ieeexplore.ieee.org/document/7829369) | RA-L 2017 | 2017-01-23 | - |  |
| _In-Context IL_ |
| [**Learning Generalizable Robot Policy with Human Demonstration Video as a Prompt**](https://arxiv.org/abs/2505.20795) | arXiv | 2025-05-27 | - |  |
| [RIP: **Robust Instant Policy: Leveraging Student's t-Regression Model for Robust In-context Imitation Learning of Robot Manipulation**](https://arxiv.org/abs/2506.15157) | IROS 2025 | 2025-06-18 | [Project](https://sites.google.com/view/robustinstantpolicy) | ICIL |
| [**Instant Policy: In-Context Imitation Learning via Graph Diffusion**](https://arxiv.org/abs/2411.12633) | ICLR 2025 | 2024-11-19 | ![Star](https://img.shields.io/github/stars/vv19/instant_policy?style=social&label=Star) [Github](https://github.com/vv19/instant_policy) | |
| [ICRT: **In-Context Imitation Learning via Next-Token Prediction**](https://arxiv.org/abs/2408.15980) | ICRA 2025 | 2024-08-28 | ![Star](https://img.shields.io/github/stars/Max-Fu/icrt?style=social&label=Star) [Github](https://github.com/Max-Fu/icrt) |  |
| [**Human-in-the-Loop Task and Motion Planning for Imitation Learning**](https://arxiv.org/abs/2310.16014) | CoRL 2023 | 2023-10-24 | [Project](https://hitltamp.github.io/) |  |
| [IGA: **Few-Shot In-Context Imitation Learning via Implicit Graph Alignment**](https://arxiv.org/abs/2310.12238) | CoRL 2023 | 2023-10-18 | ![Star](https://img.shields.io/github/stars/vv19/iga?style=social&label=Star) [Github](https://github.com/vv19/iga) |  |
| [**Transformers for One-Shot Visual Imitation**](https://arxiv.org/abs/2011.05970) | CoRL 2023 | 2011-11-11 | ![Star](https://img.shields.io/github/stars/SudeepDasari/one_shot_transformers?style=social&label=Star) [Github](https://github.com/SudeepDasari/one_shot_transformers) |  |
| _Interactive IL_ |
| [LLM-iTeach: **LLM-based Interactive Imitation Learning for Robotic Manipulation**](https://arxiv.org/abs/2504.21769) | arXiv | 2025-04-30 | ![Star](https://img.shields.io/github/stars/Tubicor/LLM-iTeach?style=social&label=Star) [Github](https://github.com/Tubicor/LLM-iTeach) |  |
| [**RoboCopilot: Human-in-the-loop Interactive Imitation Learning for Robot Manipulation**](https://arxiv.org/abs/2503.07771) | arXiv | 2025-03-10 | - |  |
| [**Model-Based Runtime Monitoring with Interactive Imitation Learning**](https://arxiv.org/abs/2310.17552) | ICRA 2024 | 2023-10-26 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/sirius-fleet?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/sirius-fleet) |  |
| [**VITAL: Interactive Few-Shot Imitation Learning via Visual Human-in-the-Loop Corrections**](https://arxiv.org/abs/2407.21244) | arXiv | 2024-07-30 | - |  |
| [**CHG-DAgger: Interactive Imitation Learning with Human-Policy Cooperative Control**](https://openreview.net/forum?id=nWiHRy3ZXy) | CoRLW 2024 | 2024-10-26 | - |  |
| [LILAC: **Yell At Your Robot: Improving On-the-Fly from Language Corrections**](https://arxiv.org/abs/2403.12910) | RSS 2024 | 2024-03-19 | ![Star](https://img.shields.io/github/stars/yay-robot/yay_robot?style=social&label=Star) [Github](https://github.com/yay-robot/yay_robot) | |
| [Sirius: **Robot Learning on the Job: Human-in-the-Loop Autonomy and Learning During Deployment**](https://arxiv.org/abs/2211.08416) | RSS 2023 | 2022-11-15 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/sirius?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/sirius) |  |
| [YAY Robot: **"No, to the Right" -- Online Language Corrections for Robotic Manipulation via Shared Autonomy**](https://arxiv.org/abs/2301.02555) | HRI 2023 | 2023-01-06 | ![Star](https://img.shields.io/github/stars/Stanford-ILIAD/lilac?style=social&label=Star) [Github](https://github.com/Stanford-ILIAD/lilac) | |
| [**Correct Me if I am Wrong: Interactive Learning for Robotic Manipulation**](https://arxiv.org/abs/2110.03316) | RA-L 2022 | 2021-10-07 | ![Star](https://img.shields.io/github/stars/robot-learning-freiburg/CEILing?style=social&label=Star) [Github](https://github.com/robot-learning-freiburg/CEILing) |  |
| [**ThriftyDAgger: Budget-Aware Novelty and Risk Gating for Interactive Imitation Learning**](https://arxiv.org/abs/2109.08273) | CoRL 2021 | 2021-09-17 | ![Star](https://img.shields.io/github/stars/ryanhoque/thriftydagger?style=social&label=Star) [Github](https://github.com/ryanhoque/thriftydagger) |  |
| [**LazyDAgger: Reducing Context Switching in Interactive Imitation Learning**](https://arxiv.org/abs/2104.00053) | CASE 2021 | 2021-03-31 | - |  |
| [**Human-in-the-Loop Imitation Learning using Remote Teleoperation**](https://arxiv.org/abs/2012.06733) | arXiv | 2020-12-12 | [Project](https://sites.google.com/stanford.edu/iwr) |  |
| [TIPS: **Interactive Imitation Learning in State-Space**](https://arxiv.org/abs/2008.00524) | CoRL 2020 | 2020-08-02 | ![Star](https://img.shields.io/github/stars/sjauhri/Interactive-Learning-in-State-space?style=social&label=Star) [Github](https://github.com/sjauhri/Interactive-Learning-in-State-space) |  |
| [**Interactive Imitation Learning of Object Movement Skills**](https://link.springer.com/article/10.1007/s10514-011-9261-0) | Auton. Robots 2012 | 2011-12-02 | - |  |
| _Efficiency_ |
| [**SAIL: Faster-than-Demonstration Execution of Imitation Learning Policies**](https://arxiv.org/abs/2506.11948) | arXiv | 2025-06-13 | [Project](https://demospeedup.github.io/) | Efficient Inference |
| [**DemoSpeedup: Accelerating Visuomotor Policies via Entropy-Guided Demonstration Acceleration**](https://arxiv.org/abs/2506.05064) | arXiv | 2025-06-05 | [Project](https://demospeedup.github.io/) |  |
| [**Subconscious Robotic Imitation Learning**](https://arxiv.org/abs/2412.20368) | arXiv | 2024-12-29 | - |  |
| [**Bridging the Resource Gap: Deploying Advanced Imitation Learning Models onto Affordable Embedded Platforms**](https://arxiv.org/abs/2411.11406) | IEEE ROBIO 2024 | 2024-11-18 | - |  |
| [**Efficient and Interpretable Robot Manipulation with Graph Neural Networks**](https://arxiv.org/abs/2102.13177) | RA-L 2022 | 2021-02-25 | - |  |
| _Robustness_ |
| [**Towards Safe Imitation Learning via Potential Field-Guided Flow Matching**](https://arxiv.org/abs/2508.08707) | IROS 2025 | 2025-08-12 | - |  |
| [**Counterfactual Behavior Cloning: Offline Imitation Learning from Imperfect Human Demonstrations**](https://www.arxiv.org/abs/2505.10760) | arXiv | 2025-05-16 | - |  |
| [**How vulnerable is my policy? Adversarial attacks on modern behavior cloning policies**](https://arxiv.org/abs/2502.03698) | arXiv | 2025-02-06 | - | |
| [**Out-of-Distribution Recovery with Object-Centric Keypoint Inverse Policy for Visuomotor Imitation Learning**](https://arxiv.org/abs/2411.03294) | IROS 2025 | 2024-11-05 | [Project](https://sites.google.com/view/ocr-penn) | Failure |
| [**Can We Detect Failures Without Failure Data? Uncertainty-Aware Runtime Failure Detection for Imitation Learning Policies**](https://arxiv.org/abs/2503.08558) | RSS 2025 | 2025-03-11 | ![Star](https://img.shields.io/github/stars/CXU-TRI/FAIL-Detect?style=social&label=Star) [Github](https://github.com/CXU-TRI/FAIL-Detect) | Failure |
| [**RAIL: Reachability-Aided Imitation Learning for Safe Policy Execution**](https://arxiv.org/abs/2409.19190) | ICRA 2025 | 2024-09-28 | ![Star](https://img.shields.io/github/stars/goldenhazard/RAIL_release?style=social&label=Star) [Github](https://github.com/goldenhazard/RAIL_release) | Safe |
| [**CCIL: Continuity-based Data Augmentation for Corrective Imitation Learning**](https://arxiv.org/abs/2310.12972) | ICLR 2024 | 2023-10-19 | ![Star](https://img.shields.io/github/stars/personalrobotics/CCIL?style=social&label=Star) [Github](https://github.com/personalrobotics/CCIL) |  |
| [**Bayesian Disturbance Injection: Robust Imitation Learning of Flexible Policies for Robot Manipulation**](https://arxiv.org/abs/2211.03393) | NN 2023 | 2022-11-07 | - |  |
| [**Imitation Learning with Inconsistent Demonstrations through Uncertainty-based Data Manipulation**](https://ieeexplore.ieee.org/document/9561686/) | ICRA 2021 | 2021-10-18 | - |  |
| [**Causal Reasoning in Simulation for Structure and Transfer Learning of Robot Manipulation Policies**](https://arxiv.org/abs/2103.16772) | ICRA 2021 | 2021-03-31 | [Project](https://sites.google.com/view/crest-causal-struct-xfer-manip) |  |
| [**DART: Noise Injection for Robust Imitation Learning**](https://arxiv.org/abs/1703.09327) | CoRL 2017 | 2017-03-27 | ![Star](https://img.shields.io/github/stars/BerkeleyAutomation/DART?style=social&label=Star) [Github](https://github.com/BerkeleyAutomation/DART) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

<!-- ******* 1.3.2 - Imitation Learning from Observation ******* -->
### Imitation Learning from Observation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| _Reward/Occupancy Recovery_ |
| [**Diffusion Imitation from Observation**](https://arxiv.org/abs/2410.05429) | NeurIPS 2024 | 2024-10-07 | ![Star](https://img.shields.io/github/stars/NTURobotLearningLab/DIFO?style=social&label=Star) [Github](https://github.com/NTURobotLearningLab/DIFO) | AIL |
| [**Imitation Learning from Observation with Automatic Discount Scheduling**](https://arxiv.org/abs/2310.07433) | ICLR 2024 | 2023-10-11 | ![Star](https://img.shields.io/github/stars/dwjshift/IL_ADS?style=social&label=Star) [Github](https://github.com/dwjshift/IL_ADS) | IRL |
| [**Learning Reward Functions for Robotic Manipulation by Observing Humans**](https://arxiv.org/abs/2211.09019) | ICRA 2023 | 2022-11-16 | - | IRL |
| _State / Representation Alignment and Matching_ |
| [DILO: **A Dual Approach to Imitation Learning from Observations with Offline Datasets**](https://arxiv.org/abs/2406.08805) | CoRL 2024 | 2024-06-13 | ![Star](https://img.shields.io/github/stars/hari-sikchi/DILO?style=social&label=Star) [Github](https://github.com/hari-sikchi/DILO) |  |
| [**LIV: Language-Image Representations and Rewards for Robotic Control**](https://arxiv.org/abs/2306.00958) | ICML 2023 | 2023-06-01 | ![Star](https://img.shields.io/github/stars/penn-pal-lab/LIV?style=social&label=Star) [Github](https://github.com/penn-pal-lab/LIV) | RepL, LfD, Both Goals, Alignment |
| [**VIP: Towards Universal Visual Reward and Representation via Value-Implicit Pre-Training**](https://arxiv.org/abs/2210.00030) | ICLR 2023 | 2022-08-30 | ![Star](https://img.shields.io/github/stars/facebookresearch/vip?style=social&label=Star) [Github](https://github.com/facebookresearch/vip) | RepL, LfD, Image Goal |
| [**NIFT: Neural Interaction Field and Template for Object Manipulation**](https://arxiv.org/abs/2210.10992) | ICRA 2023 | 2022-10-20 | ![Star](https://img.shields.io/github/stars/zzilch/NIFT?style=social&label=Star) [Github](https://github.com/zzilch/NIFT) |  |
| [ZeST: **Can Foundation Models Perform Zero-Shot Task Specification For Robot Manipulation?**](https://arxiv.org/abs/2204.11134) | L4DC 2022 | 2022-04-23 | [Project](https://sites.google.com/view/zestproject) | Both Goals |
| [**Human-to-Robot Imitation in the Wild**](https://arxiv.org/abs/2207.09450) | RSS 2022 | 2022-07-19 | [Project](https://human2robot.github.io/#) |  |
| [**Ergodic Imitation: Learning from What to Do and What Not to Do**](https://arxiv.org/abs/2103.17098) | ICRA 2021 | 2021-03-31 | - |  |
| [**A Geometric Perspective on Visual Imitation Learning**](https://arxiv.org/abs/2003.02768) | IROS 2020 | 2020-03-05 | - |  |
| [**To Follow or not to Follow: Selective Imitation Learning from Observations**](https://arxiv.org/abs/1912.07670) | CoRL 2019 | 2019-12-16 | [Project](https://youngwoon.github.io/silo/) |  |
| [**Graph-Structured Visual Imitation**](https://arxiv.org/abs/1907.05518) | CoRL 2019 | 2019-07-11 | - |  |
| [**Hindsight Generative Adversarial Imitation Learning**](https://arxiv.org/abs/1903.07854) | arXiv | 2019-03-19 | - |  |
| [**A Cognitive Framework for Imitation Learning**](https://www.sciencedirect.com/science/article/abs/pii/S0921889006000200) | RAS 2006 | 2006-03-13 | - | Conceptual |
| _Model-based / Physics-grounded_ |
| [**MimicFunc: Imitating Tool Manipulation from a Single Human Video via Functional Correspondence**](https://arxiv.org/abs/2508.13534) | CoRL 2025 | 2025-08-19 | ![Star](https://img.shields.io/github/stars/mkt1412/FUNCTO_public?style=social&label=Star) [Github](https://github.com/mkt1412/FUNCTO_public) |  |
| [**Diff-LfD: Contact-aware Model-based Learning from Visual Demonstration for Robotic Manipulation via Differentiable Physics-based Simulation and Rendering**](https://openreview.net/forum?id=DYPOvNot5F) | CoRL 2023 | 2023-08-31 | - |  |
| [**Imitation Learning as State Matching via Differentiable Physics**](https://arxiv.org/abs/2206.04873) | CVPR 2023 | 2022-06-10 | ![Star](https://img.shields.io/github/stars/sail-sg/ILD?style=social&label=Star) [Github](https://github.com/sail-sg/ILD) |  |
| _BC from Observation_ |
| [**Point Policy: Unifying Observations and Actions with Key Points for Robot Manipulation**](https://arxiv.org/abs/2502.20391) | arXiv | 2025-02-27 | ![Star](https://img.shields.io/github/stars/siddhanthaldar/Point-Policy?style=social&label=Star) [Github](https://github.com/siddhanthaldar/Point-Policy) |  |
| [**Giving Robots a Hand: Learning Generalizable Manipulation with Eye-in-Hand Human Video Demonstrations**](https://arxiv.org/abs/2307.05959) | arXiv | 2023-07-12 | [Project](https://giving-robots-a-hand.github.io/) |  |
| [**Zero-Shot Robot Manipulation from Passive Human Videos**](https://arxiv.org/abs/2302.02011) | arXiv | 2023-02-03 | [Project](https://sites.google.com/view/human-0shot-robot) |  |
| [**Learning Sensorimotor Primitives of Sequential Manipulation Tasks from Visual Demonstrations**](https://arxiv.org/abs/2203.03797) | arXiv | 2022-03-08 | - |  |
| [**Motion Reasoning for Goal-Based Imitation Learning**](https://arxiv.org/abs/1911.05864) | ICRA 2020 | 2019-11-13 | - |  |
| [**Learning Actions from Human Demonstration Video for Robotic Manipulation**](https://arxiv.org/abs/1909.04312) | IROS 2019 | 2019-09-10 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

---

<div align="center">

### <i>Reinforcement Learning (RL)</i>

</div>

<!-- ******* 1.3.10 - Model-free Reinforcement Learning ******* -->
### Model-free Reinforcement Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| Coming soon |
<!-- | _Movement Primitives_ |
| [**Contextual Latent-Movements Off-Policy Optimization for Robotic Manipulation Skills**](https://arxiv.org/abs/2010.13766) | CVPR 2022 | 2021-10-23 | ![Star](https://img.shields.io/github/stars/stepjam/ARM?style=social&label=Star) [Github](https://github.com/stepjam/ARM) |  |

| _RL + Optimization-based Control_ |
| [**Decoupling Skill Learning from Robotic Control for Generalizable Object Manipulation**](https://arxiv.org/abs/2303.04016) | ICRA 2023 | 2023-03-07 | [Project](https://kl-research.github.io/decoupskill) |  |


| [**Actor-Critic for Continuous Action Chunks: A Reinforcement Learning Framework for Long-Horizon Robotic Manipulation with Sparse Reward**](https://arxiv.org/abs/2508.11143) | arXiv | 2023-08-15 | - |  |
| [**SegDAC: Segmentation-Driven Actor-Critic for Visual Reinforcement Learning**](https://arxiv.org/abs/2508.09325) | arXiv | 2023-08-12 | [Project](https://segdac.github.io/) |  |
| [**Learning Task Execution Hierarchies for Redundant Robots**](https://arxiv.org/abs/2508.10780) | arXiv | 2023-08-14 | - |  |

| [**Ag2x2: Robust Agent-Agnostic Visual Representations for Zero-Shot Bimanual Manipulation**](https://arxiv.org/abs/2507.19817) | IROS 2025 | 2025-07-26 | ![Star](https://img.shields.io/github/stars/ziyin-xiong/Ag2x2?style=social&label=Star) [Github](https://github.com/ziyin-xiong/Ag2x2) |

| _On-Policy_ |

| _Off-Policy_ |
| [**A Task-Adaptive Deep Reinforcement Learning Framework for Dual-Arm Robot Manipulation**](https://ieeexplore.ieee.org/document/10409120) | TASE.2024 | 2024-01-18 | - |  |
| [**Coarse-to-Fine Q-attention: Efficient Learning for Visual Robotic Manipulation via Discretisation**](https://arxiv.org/abs/2106.12534) | ICRA 2021 | 2021-06-26 | ![Star](https://img.shields.io/github/stars/SamuelePolimi/lampo?style=social&label=Star) [Github](https://github.com/SamuelePolimi/lampo) |  |
| [**Efficient Robotic Manipulation Through Offline-to-Online Reinforcement Learning and Goal-Aware State Information**](https://arxiv.org/abs/2110.10905) | ICRA 2021 | 2021-10-21 | ![Star](https://img.shields.io/github/stars/SamuelePolimi/lampo?style=social&label=Star) [Github](https://github.com/SamuelePolimi/lampo) |  |

| _Reward Shaping from LLM_ |
| [**Towards Autonomous Reinforcement Learning for Real-World Robotic Manipulation with Large Language Models**](https://arxiv.org/abs/2503.04280) | RA-L 2025 | 2025-03-06 | ![Star](https://img.shields.io/github/stars/turcato-niccolo/towardsARL?style=social&label=Star) [Github](https://github.com/turcato-niccolo/towardsARL) |  | -->

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

<!-- ******* 1.3.10 - Model-free Reinforcement Learning ******* -->
### Model-based Reinforcement Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| Coming soon |
<!-- | [**Equivariant Goal Conditioned Contrastive Reinforcement Learning**](https://arxiv.org/abs/2507.16139) | arXiv | 2025-07-22 | - |  |

| _Reward Shaping from LLM_ |
| [**Accelerating Reinforcement Learning of Robotic Manipulations via Feedback from Large Language Models**](https://arxiv.org/abs/2311.02379) | CoRLW 2023 | 2023-11-04 | - |  |


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
| [**Merging and Disentangling Views in Visual Reinforcement Learning for Robotic Manipulation**](https://arxiv.org/abs/2505.04619) | arXiv | 2025-05-07 | ![Star](https://img.shields.io/github/stars/aalmuzairee/mad?style=social&label=Star) [Github](https://github.com/aalmuzairee/mad) |  |
| [**Learning from Suboptimal Data in Continuous Control via Auto-Regressive Soft Q-Network**](https://arxiv.org/abs/2502.00288) | arXiv | 2025-02-01 | - |  |
| [**Policy Decorator: Model-Agnostic Online Refinement for Large Policy Model**](https://arxiv.org/abs/2412.13630) | ICLR 2025 | 2024-12-18 | ![Star](https://img.shields.io/github/stars/tongzhoumu/policy_decorator?style=social&label=Star) [Github](https://github.com/tongzhoumu/policy_decorator) |  |
| [**ARMADA: Augmented Reality for Robot Manipulation and Robot-Free Data Acquisition**](https://arxiv.org/abs/2412.10631) | arXiv | 2024-12-14 | [Project](https://nataliya.dev/armada) |  |
| [HIL-SERL: **Precise and Dexterous Robotic Manipulation via Human-in-the-Loop Reinforcement Learning**](https://arxiv.org/abs/2410.21845) | arXiv | 2024-10-29 | [Project](https://hil-serl.github.io/) |  |
| [**PointPatchRL - Masked Reconstruction Improves Reinforcement Learning on Point Clouds**](https://arxiv.org/abs/2410.18800) | CoRL 2024 | 2024-10-24 | [Project](https://alrhub.github.io/pprl-website) |  |
| [**SPIRE: Synergistic Planning, Imitation, and Reinforcement for Long-Horizon Manipulation**](https://arxiv.org/abs/2410.18065) | CoRL 2024 | 2024-10-23 | [Project](https://sites.google.com/view/spire-corl-2024) |  |
| [Maniwhere: **Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning**](https://arxiv.org/abs/2407.15815) | CoRL 2024 | 2024-07-22 | [Project](https://gemcollector.github.io/maniwhere/) |  |
| [PSL: **Plan-Seq-Learn: Language Model Guided RL for Solving Long Horizon Robotics Tasks**](https://arxiv.org/abs/2405.01534) | ICLR 2024 | 2024-05-02 | ![Star](https://img.shields.io/github/stars/mihdalal/planseqlearn?style=social&label=Star) [Github](https://github.com/mihdalal/planseqlearn) | |
| [**TD-MPC2: Scalable, Robust World Models for Continuous Control**](https://arxiv.org/abs/2310.16828) | ICLR 2024 | 2023-10-25 | ![Star](https://img.shields.io/github/stars/nicklashansen/tdmpc2?style=social&label=Star) [Github](https://github.com/nicklashansen/tdmpc2) | |
| [VELAP: **Expansive Latent Planning for Sparse Reward Offline Reinforcement Learning**](https://openreview.net/pdf?id=xQx1O7WXSA) | CoRL 2023 | 2023 | - | |
| [**Q-Transformer: Scalable Offline Reinforcement Learning via Autoregressive Q-Functions**](https://arxiv.org/abs/2309.10150) | CoRL 2023 | 2023-09-18 | [Project](https://qtransformer.github.io/) | |
| [PTR: **Pre-Training for Robots: Offline RL Enables Learning New Tasks from a Handful of Trials**](https://arxiv.org/abs/2210.05178) | RSS 2023 | 2022-10-11 | [Project](https://sites.google.com/view/ptr-final/) |  |
| [TD-MPC: **Temporal Difference Learning for Model Predictive Control**](https://arxiv.org/abs/2203.04955) | ICML 2022 | 2022-03-09 | ![Star](https://img.shields.io/github/stars/nicklashansen/tdmpc?style=social&label=Star) [Github](https://github.com/nicklashansen/tdmpc) |  | -->


<p align="right">(<a href="#table-of-contents">back to top</a>)</p>


---


<!-- ******* 1.3.3 - RL and IL ******* -->
### RL and IL
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Methods support for RL and IL_ |
| [**Dual RL: Unification and New Methods for Reinforcement and Imitation Learning**](https://arxiv.org/abs/2302.08560) | ICLR 2024 | 2023-02-16 | ![Star](https://img.shields.io/github/stars/hari-sikchi/DVL?style=social&label=Star) [Github](https://github.com/hari-sikchi/DVL) | |
| [**Frame Mining: a Free Lunch for Learning Robotic Manipulation from 3D Point Clouds**](https://arxiv.org/abs/2210.07442) | CoRL 2022 | 2022-10-14 | ![Star](https://img.shields.io/github/stars/xuanlinli17/corl_22_frame_mining?style=social&label=Star) [Github](https://github.com/xuanlinli17/corl_22_frame_mining) |  |
| _IL Pre-training + RL Fine-tuning_ |
| [**Sketch-to-Skill: Bootstrapping Robot Learning with Human Drawn Trajectory Sketches**](https://arxiv.org/abs/2503.11918) | RSS 2025 | 2025-03-14 | - | |
| [**Precise and Dexterous Robotic Manipulation via Human-in-the-Loop Reinforcement Learning**](https://arxiv.org/abs/2410.21845) | arXiv | 2024-10-29 | ![Star](https://img.shields.io/github/stars/rail-berkeley/hil-serl?style=social&label=Star) [Github](https://github.com/rail-berkeley/hil-serl) | |
| [**PLANRL: A Motion Planning and Imitation Learning Framework to Bootstrap Reinforcement Learning**](https://arxiv.org/abs/2408.04054) | arXiv | 2024-08-07 | ![Star](https://img.shields.io/github/stars/raaslab/HYBRID-RL?style=social&label=Star) [Github](https://github.com/raaslab/HYBRID-RL) | |
| [**Coherent Soft Imitation Learning**](https://arxiv.org/abs/2305.16498) | NeurIPS 2023 | 2023-05-25 | ![Star](https://img.shields.io/github/stars/google-deepmind/csil?style=social&label=Star) [Github](https://github.com/google-deepmind/csil) | |
| [**Q-attention: Enabling Efficient Learning for Vision-based Robotic Manipulation**](https://arxiv.org/abs/2105.14829) | RA-L 2022 | 2021-05-31 | ![Star](https://img.shields.io/github/stars/stepjam/ARM?style=social&label=Star) [Github](https://github.com/stepjam/ARM) | |
| [FERM: **A Framework for Efficient Robotic Manipulation**](https://openreview.net/pdf?id=RBfB8MOxjE-) | NeurIPSW 2021 | 2021-10-13 | ![Star](https://img.shields.io/github/stars/PhilipZRH/ferm?style=social&label=Star) [Github](https://github.com/PhilipZRH/ferm) | |
| [**Demonstration-Guided Reinforcement Learning with Learned Skills**](https://arxiv.org/abs/2107.10253) | CoRL 2021 | 2021-07-21 | ![Star](https://img.shields.io/github/stars/clvrai/skild?style=social&label=Star) [Github](https://github.com/clvrai/skild) | |
| [**Skill Learning and Task Outcome Prediction for Manipulation**](https://ieeexplore.ieee.org/document/5980200) | ICRA 2011 | 2011-08-18 | - | |
| _RL Pre-training + IL Fine-tuning_ |
| [**How to Spend Your Robot Time: Bridging Kickstarting and Offline Reinforcement Learning for Vision-based Robotic Manipulation**](https://arxiv.org/abs/2205.03353) | IROS 2022 | 2022-05-06 | - | |
| [**Distilling Motion Planner Augmented Policies into Visual Control Policies for Robot Manipulation**](https://arxiv.org/abs/2111.06383) | CoRL 2021 | 2021-11-11 | ![Star](https://img.shields.io/github/stars/clvrai/mopa-pd?style=social&label=Star) [Github](https://github.com/clvrai/mopa-pd) | |
| _Reward Shaping from IL_ |
| [**Imitation Learning from a Single Temporally Misaligned Video**](https://arxiv.org/abs/2502.05397) | ICML 2025 | 2025-02-08 | ![Star](https://img.shields.io/github/stars/portal-cornell/orca?style=social&label=Star) [Github](https://github.com/portal-cornell/orca) | |
| [**From Imitation to Refinement -- Residual RL for Precise Assembly**](https://arxiv.org/abs/2407.16677) | CoRLW 2024 | 2024-07-23 | ![Star](https://img.shields.io/github/stars/ankile/robust-rearrangement?style=social&label=Star) [Github](https://github.com/ankile/robust-rearrangement) | |
| [**RoboCLIP: One Demonstration is Enough to Learn Robot Policies**](https://arxiv.org/abs/2310.07899) | NeurIPS 2023 | 2023-10-11 | ![Star](https://img.shields.io/github/stars/sumedh7/RoboCLIP?style=social&label=Star) [Github](https://github.com/sumedh7/RoboCLIP) | |
| [**Watch and Match: Supercharging Imitation with Regularized Optimal Transport**](https://arxiv.org/abs/2206.154692) | arXiv | 2022-06-30 | ![Star](https://img.shields.io/github/stars/siddhanthaldar/ROT?style=social&label=Star) [Github](https://github.com/siddhanthaldar/ROT) |  |
| [**Generalizable Imitation Learning from Observation via Inferring Goal Proximity**](https://openreview.net/forum?id=lp9foO8AFoD) | NeurIPS 2021 | 2021-11-10 | ![Star](https://img.shields.io/github/stars/clvrai/goal_prox_il?style=social&label=Star) [Github](https://github.com/clvrai/goal_prox_il) | |
| [**Better-than-Demonstrator Imitation Learning via Automatically-Ranked Demonstrations**](https://arxiv.org/abs/1907.03976D) | CoRL 2019 2021 | 2019-07-09 | ![Star](https://img.shields.io/github/stars/dsbrown1331/CoRL2019-DREX?style=social&label=Star) [Github](https://github.com/dsbrown1331/CoRL2019-DREX) | IRL |
| [**Learning by Watching: Physical Imitation of Manipulation Skills from Human Videos**](https://arxiv.org/abs/2101.07241) | IROS 2021 | 2021-01-18 | [Project](https://www.pair.toronto.edu/lbw-kp/) | |
| [**Offline Learning from Demonstrations and Unlabeled Experience**](https://arxiv.org/abs/2011.13885) | NeurIPSW 2020 | 2020-11-27 | ![Star](https://img.shields.io/github/stars/stanford-iprl-lab/Concept2Robot?style=social&label=Star) [Github](https://github.com/stanford-iprl-lab/Concept2Robot) | |
| [**Concept2Robot: Learning Manipulation Concepts from Instructions and Human Demonstrations**](https://www.roboticsproceedings.org/rss16/p082.pdf) | RSS 2020 | 2020-01-30 | ![Star](https://img.shields.io/github/stars/stanford-iprl-lab/Concept2Robot?style=social&label=Star) [Github](https://github.com/stanford-iprl-lab/Concept2Robot) | |
| [**IRIS: Implicit Reinforcement without Interaction at Scale for Learning Control from Offline Robot Manipulation Data**](https://arxiv.org/abs/1911.05321) | ICRA 2020 | 2019-11-13 | [Project](https://sites.google.com/stanford.edu/iris/) | |
| [**Reinforcement and Imitation Learning for Diverse Visuomotor Skills**](https://arxiv.org/abs/1802.09564) | RSS 2018 | 2018-02-26 | - | |
| [**Imitation from Observation: Learning to Imitate Behaviors from Raw Video via Context Translation**](https://arxiv.org/abs/1707.03374) | ICRA 2018 | 2017-07-11 | ![Star](https://img.shields.io/github/stars/wyndwarrior/imitation_from_observation?style=social&label=Star) [Github](https://github.com/wyndwarrior/imitation_from_observation) | |
| [**Unsupervised Perceptual Rewards for Imitation Learning**](https://arxiv.org/abs/1612.06699) | RSS 2017 | 2016-12-20 | [Project](https://sermanet.github.io/rewards/) | |
| [**Guided Cost Learning: Deep Inverse Optimal Control via Policy Optimization**](https://arxiv.org/abs/1603.00448) | ICML 2016 | 2016-03-01 | - | IRL |
| _Joint Optimization_ |
| [**IN-RIL: Interleaved Reinforcement and Imitation Learning for Policy Fine-Tuning**](https://arxiv.org/abs/2505.10442) | arXiv | 2025-05-15 | ![Star](https://img.shields.io/github/stars/ucd-dare/IN-RIL?style=social&label=Star) [Github](https://github.com/ucd-dare/IN-RIL) | |
RA-L 2024 | 2024-03-11 | [Gitlab](https://rlingua.github.io/) | |
| [**Accelerating Interactive Human-like Manipulation Learning with GPU-based Simulation and High-quality Demonstrations**](https://arxiv.org/abs/2212.02126) | Humanoids 2022 | 2022-12-05 | [Project](https://git.ais.uni-bonn.de/mosbach/gym-grasp) | |
| [**AW-Opt: Learning Robotic Skills with Imitation and Reinforcement at Scale**](https://arxiv.org/abs/2111.05424) | CoRL 2021 | 2021-11-09 | [Project](https://awopt.github.io/) | |
| [**Augmenting GAIL with BC for Sample Efficient Imitation Learning**](https://arxiv.org/abs/2001.07798) | CoRL 2021 | 2020-01-21 | ![Star](https://img.shields.io/github/stars/rohitrango/BC-regularized-GAIL?style=social&label=Star) [Github](https://github.com/rohitrango/BC-regularized-GAIL) | |
| _In-Context RL_ |
| [**Demonstration-Conditioned Reinforcement Learning for Few-Shot Imitation**](https://proceedings.mlr.press/v139/dance21a.html) | ICML 2021 | 2021-06-11 | - | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

---

<div align="center">

### <i>Learning with Auxiliary Tasks</i>

</div>

### World Model
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   |  
|:--------|:--------:|:--------:|:--------:|
| _Generative Visual WMs_ |
| [**OSVI-WM: One-Shot Visual Imitation for Unseen Tasks using World-Model-Guided Trajectory Generation**](https://arxiv.org/abs/2505.20425) | arXiv | 2025-05-26 | - | |
| [**Vid2World: Crafting Video Diffusion Models to Interactive World Models**](https://arxiv.org/abs/2505.14357) | arXiv | 2025-05-20 | [Project](https://knightnemo.github.io/vid2world/) | |
| [**Unified World Models: Coupling Video and Action Diffusion for Pretraining on Large Robotic Datasets**](https://arxiv.org/abs/2504.02792) | RSS 2025 | 2025-04-03 | ![Star](https://img.shields.io/github/stars/WEIRDLabUW/unified-world-model?style=social&label=Star) [Github](https://github.com/WEIRDLabUW/unified-world-model) | |
| [**Dream to Manipulate: Compositional World Models Empowering Robot Imitation Learning with Imagination**](https://arxiv.org/abs/2412.14957) | ICLR 2025 | 2024-12-19 | ![Star](https://img.shields.io/github/stars/leobarcellona/drema_code?style=social&label=Star) [Github](https://github.com/leobarcellona/drema_code) | |
| [SWIM: **Structured World Models from Human Videos**](https://arxiv.org/abs/2308.10901) | RSS 2023 | 2023-08-23 | [Project](https://human-world-model.github.io/) | |
| _3D/Physics-consistent WMs_ |
| [**3DFlowAction: Learning Cross-Embodiment Manipulation from 3D Flow World Model**](https://arxiv.org/abs/2506.06199) | arXiv | 2025-06-06 | ![Star](https://img.shields.io/github/stars/Hoyyyaard/3DFlowAction?style=social&label=Star) [Github](https://github.com/Hoyyyaard/3DFlowAction/) |  |
| [**ParticleFormer: A 3D Point Cloud World Model for Multi-Object, Multi-Material Robotic Manipulation**](https://arxiv.org/abs/2506.23126) | arXiv | 2025-06-29 | [Project](https://particleformer.github.io/) | |
| [**GAF: Gaussian Action Field as a Dvnamic World Model for Robotic Mlanipulation**](https://arxiv.org/abs/2506.14135) | arXiv | 2025-06-17 | - | |
| [**ManiGaussian++: General Robotic Bimanual Manipulation with Hierarchical Gaussian World Model**](https://arxiv.org/abs/2506.19842) | IROS 2025 | 2025-06-24 | ![Star](https://img.shields.io/github/stars/April-Yz/ManiGaussian_Bimanual?style=social&label=Star) [Github](https://github.com/April-Yz/ManiGaussian_Bimanual) | |
| [**GWM: Towards Scalable Gaussian World Models for Robotic Manipulation**](https://arxiv.org/abs/2508.17600) | ICCV 2025 | 2025-08-25 | [Project](https://gaussian-world-model.github.io/) | |
| [**Physically Embodied Gaussian Splatting: A Realtime Correctable World Model for Robotics**](https://arxiv.org/abs/2406.10788) | CoRL 2024 | 2024-06-16 | [Project](https://embodied-gaussians.github.io/) | 3DGS |
| [**ManiGaussian: Dynamic Gaussian Splatting for Multi-task Robotic Manipulation**](https://arxiv.org/abs/2403.08321) | ECCV 2024 | 2024-03-13 | ![Star](https://img.shields.io/github/stars/GuanxingLu/ManiGaussian?style=social&label=Star) [Github](https://github.com/GuanxingLu/ManiGaussian) |  |
| _Policy Learning with WMs_ |
| [**Physical Autoregressive Model for Robotic Manipulation without Action Pretraining**](https://arxiv.org/abs/2508.09822) | arXiv | 2025-08-13 | [Project](https://songzijian1999.github.io/PAR_ProjectPage/) |  |
| [**A Smooth Sea Never Made a Skilled SAILOR: Robust Imitation via Learning to Search**](https://arxiv.org/abs/2506.05294) | arXiv | 2025-06-05 | ![Star](https://img.shields.io/github/stars/arnavkj1995/SAILOR?style=social&label=Star) [Github](https://github.com/arnavkj1995/SAILOR) |  |
| [**Coupled Distributional Random Expert Distillation for World Model Online Imitation Learning**](https://arxiv.org/abs/2505.02228) | arXiv | 2025-05-04 | - | |
| [**DiWA: Diffusion Policy Adaptation with World Models**](https://www.arxiv.org/abs/2508.03645) | CoRL 2025 | 2025-08-05 | ![Star](https://img.shields.io/github/stars/acl21/diwa?style=social&label=Star) [Github](https://github.com/acl21/diwa) | |
| [DEMO3: **Multi-Stage Manipulation with Demonstration-Augmented Reward, Policy, and World Model Learning**](https://arxiv.org/abs/2503.01837) | ICML 2025 | 2025-03-03 | ![Star](https://img.shields.io/github/stars/adrialopezescoriza/demo3?style=social&label=Star) [Github](https://github.com/adrialopezescoriza/demo3) | |
| [**WoMAP: World Models For Embodied Open-Vocabulary Object Localization**](https://arxiv.org/abs/2506.01600) | RSSW 2025 | 2025-06-02 | [Project](https://robot-womap.github.io/) | |
| [**Generalist World Model Pre-Training for Efficient Reinforcement Learning**](https://arxiv.org/abs/2502.19544) | ICLRW 2025 | 2025-02-26 | - | |
| [WM3C: **Modeling Unseen Environments with Language-guided Composable Causal Components in Reinforcement Learning**](https://arxiv.org/abs/2505.08361) | ICLR 2025 | 2025-05-13 | [Project](https://www.charonwangg.com/project/wm3c/) | |
| [ReViWo: **Learning View-invariant World Models for Visual Robotic Manipulation**](https://openreview.net/forum?id=vJwjWyt4Ed) | ICLR 2025 | 2025-01-23 | ![Star](https://img.shields.io/github/stars/lafmdp/ReViWo?style=social&label=Star) [Github](https://github.com/lafmdp/ReViWo) | |
| [**LUMOS: Language-Conditioned Imitation Learning with World Models**](https://arxiv.org/abs/2503.10370) | ICRA 2025 | 2025-03-13 | [Project](http://lumos.cs.uni-freiburg.de/) | |
| [**Get Back Here: Robust Imitation by Return-to-Distribution Planning**](https://arxiv.org/abs/2305.01400) | arXiv | 2024-05-02 | - | |
| [**VLMPC: Vision-Language Model Predictive Control for Robotic Manipulation**](https://arxiv.org/abs/2407.09829) | RSS 2024 | 2024-07-13 | ![Star](https://img.shields.io/github/stars/PPjmchen/VLMPC?style=social&label=Star) [Github](https://github.com/PPjmchen/VLMPC) | |
| [**MOTO: Offline Pre-training to Online Fine-tuning for Model-based Robot Learning**](https://arxiv.org/abs/2401.03306) | CoRL 2023 | 2024-01-06 | [Project](https://sites.google.com/view/mo2o) | |
| [FOWM: **Finetuning Offline World Models in the Real World**](https://arxiv.org/abs/2310.16029) | CoRL 2023 | 2023-10-24 | ![Star](https://img.shields.io/github/stars/fyhMer/fowm?style=social&label=Star) [Github](https://github.com/fyhMer/fowm) | |
| [MV-MWM: **Multi-View Masked World Models for Visual Robotic Manipulation**](https://arxiv.org/abs/2302.02408) | ICML 2023 | 2023-02-05 | ![Star](https://img.shields.io/github/stars/younggyoseo/MV-MWM?style=social&label=Star) [Github](https://github.com/younggyoseo/MV-MWM) | |
| [**Surfer: Progressive Reasoning with World Models for Robotic Manipulation**](https://arxiv.org/abs/2306.11335) | arXiv | 2023-06-20 | ![Star](https://img.shields.io/github/stars/Necolizer/RM-PRT?style=social&label=Star) [Github](https://github.com/Necolizer/RM-PRT) | |
| _Systemization and Deployment_ |
| [**Genie Envisioner: A Unified World Foundation Platform for Robotic Manipulation**](https://arxiv.org/abs/2508.05635) | arXiv | 2025-08-07 | ![Star](https://img.shields.io/github/stars/AgibotTech/Genie-Envisioner?style=social&label=Star) [Github](https://github.com/AgibotTech/Genie-Envisioner) | |
| [**Cosmos World Foundation Model Platform for Physical AI**](https://arxiv.org/abs/2501.03575) | arXiv | 2025-01-07 | ![Star](https://img.shields.io/github/stars/NVIDIA/Cosmos?style=social&label=Star) [Github](https://github.com/NVIDIA/Cosmos) | |
| [Sirius-Fleet: **Multi-Task Interactive Robot Fleet Learning with Visual World Models**](https://arxiv.org/abs/2410.22689) | CoRL 2024 | 2024-10-30 | [Project](https://ut-austin-rpl.github.io/sirius-fleet/) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Visual Prediction
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Image/Video Prediction_ |
| [**Video Generators are Robot Policies**](https://arxiv.org/abs/2508.00795) | arXiv | 2025-08-01 | ![Star](https://img.shields.io/github/stars/cvlab-columbia/videopolicy?style=social&label=Star) [Github](https://github.com/cvlab-columbia/videopolicy) |  |
| [**ERMV: Editing 4D Robotic Multi-view images to enhance embodied agentss**](https://arxiv.org/abs/2507.17462) | arXiv | 2025-07-23 | ![Star](https://img.shields.io/github/stars/IRMVLab/ERMV?style=social&label=Star) [Github](https://github.com/IRMVLab/ERMV) |  |
| [**Generalist Bimanual Manipulation via Foundation Video Diffusion Models**](https://arxiv.org/abs/2507.12898) | arXiv | 2025-07-17 | - |  |
| [**RwoR: Generating Robot Demonstrations from Human Hand Collection for Policy Learning without Robot**](https://arxiv.org/abs/2507.03930) | arXiv | 2025-07-05 | - |  |
| [**World4Omni: A Zero-Shot Framework from Image Generation World Model to Robotic Manipulation**](https://arxiv.org/abs/2506.23919) | arXiv | 2025-06-30 | [Project](https://world4omni.github.io/) | |
| [**RoboEnvision: A Long-Horizon Video Generation Model for Multi-Task Robot Manipulation**](https://arxiv.org/abs/2506.22007) | arXiv | 2025-06-27 | [Project](https://rwor.github.io/) |  |
| [SAIL: **Self-Adapting Improvement Loops for Robotic Learning**](https://arxiv.org/abs/2506.06658) | arXiv | 2025-06-07 | [Project](https://diffusion-supervision.github.io/sail/) |  |
| [**ORV: 4D Occupancy-centric Robot Video Generation**](https://arxiv.org/abs/2506.03079) | arXiv | 2025-06-03 | ![Star](https://img.shields.io/github/stars/OrangeSodahub/ORV?style=social&label=Star) [Github](https://github.com/OrangeSodahub/ORV) |  |
| [**ManipDreamer: Boosting Robotic Manipulation World Model with Action Tree and Visual Guidance**](https://arxiv.org/abs/2504.16464) | arXiv | 2025-04-23 | - | |
| [**EnerVerse: Envisioning Embodied Future Space for Robotics Manipulation**](https://arxiv.org/abs/2501.01895) | arXiv | 2025-01-03 | [Project](https://sites.google.com/view/enerverse) | |
| [**Gen2Act: Human Video Generation in Novel Scenarios enables Generalizable Robot Manipulation**](https://arxiv.org/abs/2409.16283) | CoRL 2025 | 
 2024-09-24 | [Project](https://homangab.github.io/gen2act/) |  |
| [**GEVRM: Goal-Expressive Video Generation Model For Robust Visual Manipulation**](https://arxiv.org/abs/2502.09268) | ICLR 2025 | 2025-02-13 | - |  |
| [Seer: **Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation**](https://arxiv.org/abs/2412.15109) | ICLR 2025 | 2024-12-19 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/Seer?style=social&label=Star) [Github](https://github.com/OpenRobotLab/Seer/) |  |
| [VPP: **Video Prediction Policy: A Generalist Robot Policy with Predictive Visual Representations**](https://arxiv.org/abs/2412.14803) | ICML 2025 | 2024-12-19 | [Project](https://video-prediction-policy.github.io/) |  |
| [**GHIL-Glue: Hierarchical Control with Filtered Subgoal Images**](https://arxiv.org/abs/2410.20018) | arXiv | 2024-10-26 | [Project](https://ghil-glue.github.io/) |  |
| [**VideoAgent: Self-Improving Video Generation**](https://arxiv.org/abs/2410.10076) | arXiv | 2024-10-14 | ![Star](https://img.shields.io/github/stars/video-as-agent/videoagent?style=social&label=Star) [Github](https://github.com/video-as-agent/videoagent) |  |
| [**GR-2: A Generative Video-Language-Action Model with Web-Scale Knowledge for Robot Manipulation**](https://arxiv.org/abs/2410.06158) | arXiv | 2024-10-08 | [Project](https://gr2-manipulation.github.io/) |  |
| [**GR-MG: Leveraging Partially Annotated Data via Multi-Modal Goal Conditioned Policy**](https://arxiv.org/abs/2408.14368) | RA-L 2025 | 2024-08-26 | ![Star](https://img.shields.io/github/stars/bytedance/GR-MG?style=social&label=Star) [Github](https://github.com/bytedance/GR-MG) | |
 | [**VidMan: Exploiting Implicit Dynamics from Video Diffusion Model for Effective Robot Manipulation**](https://arxiv.org/abs/2411.09153) | NeurIPS 2024 | 2024-11-14 | - |  |
| [CLOVER: **Closed-Loop Visuomotor Control with Generative Expectation for Robotic Manipulation**](https://arxiv.org/abs/2409.09016) | NeurIPS 2024 | 2024-09-13 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/CLOVER?style=social&label=Star) [Github](https://github.com/OpenDriveLab/CLOVER) | |
| [**VILP: Imitation Learning with Latent Video Planning**](https://arxiv.org/abs/2502.01784) | RA-L 2025 | 2025-02-03 | ![Star](https://img.shields.io/github/stars/ZhengtongXu/VILP?style=social&label=Star) [Github](https://github.com/ZhengtongXu/VILP) |  |
| [**FoAM: Foresight-Augmented Multi-Task Imitation Policy for Robotic Manipulation**](https://arxiv.org/abs/2409.19528) | arXiv | 2024-09-29 | ![Star](https://img.shields.io/github/stars/LitaoLiu01/FoAM-main?style=social&label=Star) [Github](https://github.com/LitaoLiu01/FoAM-main) |  |
| [R&D: **Render and Diffuse: Aligning Image and Action Spaces for Diffusion-based Behaviour Cloning**](https://arxiv.org/abs/2405.18196) | RSS 2024 | 2024-05-28 | ![Star](https://img.shields.io/github/stars/vv19/rendiff?style=social&label=Star) [Github](https://github.com/vv19/rendiff) | |
| [GR-1: **Unleashing Large-Scale Video Generative Pre-training for Visual Robot Manipulation**](https://arxiv.org/abs/2312.13139) | ICLR 2024 | 2023-12-20 | ![Star](https://img.shields.io/github/stars/bytedance/GR-1?style=social&label=Star) [Github](https://github.com/bytedance/GR-1) |  |
| [SuSIE: **Zero-Shot Robotic Manipulation with Pretrained Image-Editing Diffusion Models**](https://arxiv.org/abs/2310.10639) | ICLR 2024 | 2023-10-16 | ![Star](https://img.shields.io/github/stars/kvablack/susie?style=social&label=Star) [Github](https://github.com/kvablack/susie) |  |
| [VLP: **Video Language Planning**](https://arxiv.org/abs/2310.10625) | ICLR 2024 | 2023-10-16 | ![Star](https://img.shields.io/github/stars/video-language-planning/vlp_code?style=social&label=Star) [Github][Github](https://github.com/video-language-planning/vlp_code) | |
| [HOPMan: **Towards Generalizable Zero-Shot Manipulation via Translating Human Interaction Plans**](https://arxiv.org/abs/2312.00775) | ICRA 2024 | 2023-12-01 | [Project](https://homangab.github.io/hopman/) |  |
| [**Future-guided Offline Imitation Learning for Long Action Sequences via Video Interpolation and Future-trajectory Prediction**](https://www.sciencedirect.com/science/article/abs/pii/S0925231223004484) | Neucom 2023 | 2023-08-28 | - |  |
| [**Third-Person Visual Imitation Learning via Decoupled Hierarchical Controller**](https://arxiv.org/abs/1911.09676) | NeurIPS 2019 | 2019-11-21 | ![Star](https://img.shields.io/github/stars/pathak22/hierarchical-imitation?style=social&label=Star) [Github](https://github.com/pathak22/hierarchical-imitation) |  |
| _Point Cloud Prediction_ |
| [**4D Visual Pre-training for Robot Learning**](https://arxiv.org/abs/2508.17230) | ICCV 2025 | 2025-08-24 | [Project](https://4d-visual-pretraining.github.io/n) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Contrastive Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**CLASS: Contrastive Learning via Action Sequence Supervision for Robot Manipulation**](https://www.arxiv.org/abs/2508.01600) | CoRL 2025 | 2025-08-03 | ![Star](https://img.shields.io/github/stars/sean1295/CLASS?style=social&label=Star) [Github](https://github.com/sean1295/CLASS) |  |
| [Σ-agent: **Contrastive Imitation Learning for Language-guided Multi-Task Robotic Manipulation**](https://arxiv.org/abs/2406.09738) | CoRL 2024 | 2024-06-14 | [Project](https://teleema.github.io/projects/Sigma_Agent/) | IL, RepL, Poliy Head, Alignment |
| [**Vid2Robot: End-to-end Video-conditioned Policy Learning with Cross-Attention Transformers**](https://arxiv.org/abs/2403.12943) | RSS 2024 | 2024-03-19 | [Project](https://vid2robot.github.io/) | IL, RepL, LfD, E-D, Poliy Head, Language Goal, Alignment |
| [**R3M: A Universal Visual Representation for Robot Manipulation**](https://arxiv.org/abs/2203.12601) | CoRL 2022 | 2022-03-23 | ![Star](https://img.shields.io/github/stars/facebookresearch/r3m?style=social&label=Star) [Github](https://github.com/facebookresearch/r3m) | IL, RepL, LfD, Alignment, Language Goal, Poliy Head |
| [HULC: **What Matters in Language Conditioned Robotic Imitation Learning over Unstructured Data**](https://arxiv.org/abs/2204.06252) | RA-L 2022 | 2022-04-13 | ![Star](https://img.shields.io/github/stars/lukashermann/hulc?style=social&label=Star) [Github](https://github.com/lukashermann/hulc) | IL, RepL, Alignment, Language Goal, Poliy Head |
| [**BC-Z: Zero-Shot Task Generalization with Robotic Imitation Learning**](https://arxiv.org/abs/2202.02005) | CoRL 2021 | 2022-02-04 | ![Star](https://img.shields.io/github/stars/google-research/tensor2robot?style=social&label=Star) [Github](https://github.com/google-research/tensor2robot/tree/master/research/bcz) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Masked Reconstruction
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _2D_ |
| [STP: **Spatiotemporal Predictive Pre-training for Robotic Motor Control**](https://arxiv.org/abs/2403.05304) | arXiv | 2024-03-08 | - |  |
| [**MUTEX: Learning Unified Policies from Multimodal Task Specifications**](https://arxiv.org/abs/2309.14320) | CoRL 2023 | 2023-09-25 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/mutex?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/mutex) |  |
| [**Robot Learning with Sensorimotor Pre-training**](https://arxiv.org/abs/2306.10007) | CoRL 2023 | 2023-06-16 | [Project](https://robotic-pretrained-transformer.github.io/) | |
| [Voltron: **Language-Driven Representation Learning for Robotics**](https://arxiv.org/abs/2302.12766) | RSS 2023 | 2023-02-24 | ![Star](https://img.shields.io/github/stars/siddk/voltron-robotics?style=social&label=Star) [Github](https://github.com/siddk/voltron-robotics) |  |
| [MVP: **Real-World Robot Learning with Masked Visual Pre-training**](https://arxiv.org/abs/2210.03109) | CoRL 2022 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/ir413/mvp?style=social&label=Star) [Github](https://github.com/ir413/mvp) |  |
| _3D_ |
| [**Train Once, Deploy Anywhere: Realize Data-Efficient Dynamic Object Manipulation**](https://arxiv.org/abs/2508.14042) | arXiv | 2025-08-19 | - |  |
| [**CL3R: 3D Reconstruction and Contrastive Learning for Enhanced Robotic Manipulation Representations**](https://arxiv.org/abs/2507.08262) | arXiv | 2025-07-11 | - |  |
| [**EquAct: An SE(3)-Equivariant Multi-Task Transformer for Open-Loop Robotic Manipulation**](https://arxiv.org/abs/2505.21351) | arXiv | 2025-05-27 | - |  |
| [**Lift3D Foundation Policy: Lifting 2D Large-Scale Pretrained Models for Robust 3D Robotic Manipulation**](https://arxiv.org/abs/2411.18623) | CVPR 2025 | 2024-11-27 | ![Star](https://img.shields.io/github/stars/PKU-HMI-Lab/LIFT3D?style=social&label=Star) [Github](https://github.com/PKU-HMI-Lab/LIFT3D) |  |
| [**3D-MVP: 3D Multiview Pretraining for Robotic Manipulation**](https://arxiv.org/abs/2406.18158) | CVPR 2025 | 2024-06-26 | [Project](https://jasonqsy.github.io/3DMVP/) |  |
| [**SPA: 3D Spatial-Awareness Enables Effective Embodied Representation**](https://arxiv.org/abs/2410.08208) | ICLR 2025 | 2024-10-10 | ![Star](https://img.shields.io/github/stars/HaoyiZhu/SPA?style=social&label=Star) [Github](https://github.com/HaoyiZhu/SPA) | |
| [**ManiGaussian: Dynamic Gaussian Splatting for Multi-task Robotic Manipulation**](https://arxiv.org/abs/2403.08321) | ECCV 2024 | 2024-03-13 | ![Star](https://img.shields.io/github/stars/GuanxingLu/ManiGaussian?style=social&label=Star) [Github](https://github.com/GuanxingLu/ManiGaussian) |  |
| [SGRv2: **Leveraging Locality to Boost Sample Efficiency in Robotic Manipulation**](https://arxiv.org/abs/2406.10615) | CoRL 2024 | 2024-06-15 | ![Star](https://img.shields.io/github/stars/TongZhangTHU/sgr?style=social&label=Star) [Github](https://github.com/TongZhangTHU/sgr) |  |
| [**RVT-2: Learning Precise Manipulation from Few Demonstrations**](https://arxiv.org/abs/2406.08545) | RSS 2024 | 2024-01-12 | ![Star](https://img.shields.io/github/stars/nvlabs/rvt?style=social&label=Star) [Github](https://github.com/nvlabs/rvt) |  |
| [**GNFactor: Multi-Task Real Robot Learning with Generalizable Neural Feature Fields**](https://arxiv.org/abs/2308.16891) | CoRL 2023 | 2023-08-31 | ![Star](https://img.shields.io/github/stars/YanjieZe/GNFactor?style=social&label=Star) [Github](https://github.com/YanjieZe/GNFactor) | NeRF, IL, Language Goal, Reconstruction |
| [3D4RL: **Visual Reinforcement Learning with Self-Supervised 3D Representations**](https://arxiv.org/abs/2210.07241) | RA-L 2023 | 2022-10-13 | ![Star](https://img.shields.io/github/stars/YanjieZe/rl3d?style=social&label=Star) [Github](https://github.com/YanjieZe/rl3d) | RL, RepL, Reconstruction, Image Goal |
| [**PolarNet: 3D Point Clouds for Language-Guided Robotic Manipulation**](https://arxiv.org/abs/2309.15596) | CoRL 2023 | 2023-09-27 | ![Star](https://img.shields.io/github/stars/vlc-robot/polarnet?style=social&label=Star) [Github](https://github.com/vlc-robot/polarnet) |  |
| [**M2T2: Multi-Task Masked Transformer for Object-centric Pick and Place**](https://arxiv.org/abs/2311.00926) | CoRL 2023 | 2023-11-02 | ![Star](https://img.shields.io/github/stars/NVlabs/M2T2?style=social&label=Star) [Github](https://github.com/NVlabs/M2T2) |  |
| [SPARTN: **NeRF in the Palm of Your Hand: Corrective Augmentation for Robotics via Novel-View Synthesis**](https://arxiv.org/abs/2301.08556) | CVPR 2023 | 2023-01-18 | [Project](https://bland.website/spartn/) |  |
| [PerAct: **Perceiver-Actor: A Multi-Task Transformer for Robotic Manipulation**](https://arxiv.org/abs/2209.05451) | CoRL 2022 | 2022-09-12 | ![Star](https://img.shields.io/github/stars/peract/peract?style=social&label=Star)  [Github](https://github.com/peract/peract) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Text-Grounded Goal Extraction
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**RACER: Rich Language-Guided Failure Recovery Policies for Imitation Learning**](https://arxiv.org/abs/2409.14674) | ICRA 2025 | 2024-09-23 | ![Star](https://img.shields.io/github/stars/sled-group/RACER?style=social&label=Star) [Github](https://github.com/sled-group/RACER) |  |
| [COTPC: **Chain-of-Thought Predictive Control**](https://arxiv.org/abs/2304.00776) | ICML 2024 | 2023-04-03 | ![Star](https://img.shields.io/github/stars/SeanJia/CoTPC?style=social&label=Star) [Github](https://github.com/SeanJia/CoTPC) | IL, RepL, CoT  |
| [**EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought**](https://arxiv.org/abs/2305.15021) | NeurIPS 2023 | 2023-05-24 | ![Star](https://img.shields.io/github/stars/EmbodiedGPT/EmbodiedGPT_Pytorch?style=social&label=Star) [Github](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch) |  |
| [OCI: **Object-Centric Instruction Augmentation for Robotic Manipulation**](https://arxiv.org/abs/2401.02814) | ICRA 2024 | 2024-01-05 | [Project](https://oci-robotics.github.io/) |  |


### Vision-Grounded Goal Extraction
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Detection_ |
| [**VIOLA: Imitation Learning for Vision-Based Manipulation with Object Proposal Priors**](https://arxiv.org/abs/2210.11339) | CoRL 2022 | 2020-10-22 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/VIOLA?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/VIOLA) | Detection |
| _Segmentation_ |
| [**Gondola: Grounded Vision Language Planning for Generalizable Robotic Manipulation**](https://arxiv.org/abs/2506.11261) | arXiv | 2025-06-12 | [Project](https://cshizhe.github.io/projects/robot_gondola.html) | Segmentation |
| [**Disentangled Object-Centric Image Representation for Robotic Manipulation**](https://arxiv.org/abs/2503.11565) | arXiv | 2025-03-14 | - |  |
| [**Imit Diff: Semantics Guided Diffusion Transformer with Dual Resolution Fusion for Imitation Learning**](https://arxiv.org/abs/2502.09649) | arXiv | 2025-02-11 | - | Segmentation |
| [**SAM-E: Leveraging Visual Foundation Model with Sequence Imitation for Embodied Manipulation**](https://arxiv.org/abs/2405.19586) | ICML 2024 | 2024-05-30 | ![Star](https://img.shields.io/github/stars/pipixiaqishi1/SAM-E?style=social&label=Star) [Github](https://github.com/pipixiaqishi1/SAM-E) |  |
| [GROOT: **Learning Generalizable Manipulation Policies with Object-Centric 3D Representations**](https://arxiv.org/abs/2310.14386) | CoRL 2023 | 2023-10-22 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/GROOT?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/GROOT) |  |
| _Heatmap_ |
| [ActAIM2: **Discovering Robotic Interaction Modes with Discrete Representation Learning**](https://arxiv.org/abs/2410.20258) | CoRL 2024 | 2024-10-26 | [Project](https://actaim2.github.io/) |  |
| [**RVT: Robotic View Transformer for 3D Object Manipulation**](https://arxiv.org/abs/2306.14896) | CoRL 2023 | 2023-06-26 | ![Star](https://img.shields.io/github/stars/nvlabs/rvt?style=social&label=Star) [Github](https://github.com/nvlabs/rvt) |  |
| _Gaze_ |
| [**Look, Focus, Act: Efficient and Robust Robot Learning via Human Gaze and Foveated Vision Transformers**](https://arxiv.org/abs/2507.15833) | arXiv | 2025-07-21 | ![Star](https://img.shields.io/github/stars/ian-chuang/gaze-av-aloha?style=social&label=Star) [Github](https://github.com/ian-chuang/gaze-av-aloha) |  |
| [**Where Do We Look When We Teach? Analyzing Human Gaze Behavior Across Demonstration Devices in Robot Imitation Learning**](https://arxiv.org/abs/2506.05808) | arXiv | 2025-06-06 | - | Gaze |
| [**Enhancing Reusability of Learned Skills for Robot Manipulation via Gaze and Bottleneck**](https://arxiv.org/abs/2502.18121) | arXiv | 2025-02-25 | ![Star](https://img.shields.io/github/stars/crumbyRobotics/gazebot?style=social&label=Star) [Github](https://github.com/crumbyRobotics/gazebot) | Gaze |
| [**Gaze-Guided Task Decomposition for Imitation Learning in Robotic Manipulation**](https://arxiv.org/abs/2501.15071) | arXiv | 2025-01-25 | ![Star](https://img.shields.io/github/stars/crumbyRobotics/GazeTaskDecomp?style=social&label=Star) [Github](https://github.com/crumbyRobotics/GazeTaskDecomp) | Gaze |
| [**VIRT: Vision Instructed Transformer for Robotic Manipulation**](https://arxiv.org/abs/2410.07169) | arXiv | 2024-10-09 | ![Star](https://img.shields.io/github/stars/Lizhuoling/VIRT?style=social&label=Star) [Github](https://github.com/Lizhuoling/VIRT) |  |
| [**Using Human Gaze in Few-shot Imitation Learning for Robot Manipulation**](https://ieeexplore.ieee.org/document/9981706) | IROS 2022 | 2022-12-26 | - | Gaze |
| [**Memory-based Gaze Prediction in Deep Imitation Learning for Robot Manipulation**](https://arxiv.org/abs/2202.04877) | ICRA 2022 | 2022-02-10 | - | Gaze |
| [**Generalization Through Hand-Eye Coordination: An Action Space for Learning Spatially-Invariant Visuomotor Control**](https://arxiv.org/abs/2103.00375) | IROS 2021 | 2021-02-28 | [Project](https://sites.google.com/stanford.edu/han) | Gaze |
| [**Gaze-Based Dual Resolution Deep Imitation Learning for High-Precision Dexterous Robot Manipulation**](https://arxiv.org/abs/2102.01295) | RA-L 2021 | 2021-02-02 | - | Gaze |
| [**Using Human Gaze to Improve Robustness Against Irrelevant Objects in Robot Manipulation Tasks**](https://ieeexplore.ieee.org/document/9103290) | RA-L 2020 | 2020-05-28| - | Gaze |
| _Keypoint_|
| [**Knowledge-Driven Imitation Learning: Enabling Generalization Across Diverse Conditions**](https://arxiv.org/abs/2506.21057) | arXiv | 2025-06-26 | ![Star](https://img.shields.io/github/stars/mioam/KnowledgeIL?style=social&label=Star) [Github](https://github.com/mioam/KnowledgeIL) |  |
| [**ATK: Automatic Task-driven Keypoint Selection for Robust Policy Learning**](https://arxiv.org/abs/2506.13867) | arXiv | 2025-06-16 | [Project](https://yunchuzhang.github.io/ATK/) |  |
| [**SKIL: Semantic Keypoint Imitation Learning for Generalizable Data-efficient Manipulation**](https://arxiv.org/abs/2501.14400) | RSS 2025 | 2025-01-24 | ![Star](https://img.shields.io/github/stars/SKIL-robotics/SKIL?style=social&label=Star) [Github](https://github.com/SKIL-robotics/SKIL) |  |
| [**HAMSTER: Hierarchical Action Models For Open-World Robot Manipulation**](https://arxiv.org/abs/2502.05485) | ICLR 2025 | 2025-02-08 | [Project](https://hamster-robot.github.io/) |  |
| [KAT: **Keypoint Abstraction using Large Models for Object-Relative Imitation Learning**](https://arxiv.org/abs/2410.23254) | ICRA 2025 | 2024-10-30 | ![Star](https://img.shields.io/github/stars/FANG-Xiaolin/KALM?style=social&label=Star) [Github](https://github.com/FANG-Xiaolin/KALM) |  |
| [**Keypoint Action Tokens Enable In-Context Imitation Learning in Robotics**](https://arxiv.org/abs/2403.19578) | RSS 2024 | 2024-03-28 | [Colab](https://colab.research.google.com/drive/1ZxZDahvLBE2EGo8_98Lk0Zr8IvUIDjMc?usp=sharing) |  |
| [**Bi-KVIL: Keypoints-based Visual Imitation Learning of Bimanual Manipulation Tasks**](https://arxiv.org/abs/2403.03270) | ICRA 2024 | 2024-03-05 | ![Star](https://img.shields.io/github/stars/wyngjf/bi-kvil-pub?style=social&label=Star) [Github](https://github.com/wyngjf/bi-kvil-pub) |  |
| [**K-VIL: Keypoints-based Visual Imitation Learning**](https://arxiv.org/abs/2209.03277) | T-RO 2023 | 2022-09-07 | ![Star](https://img.shields.io/gitlab/stars/paper-code/kvil_public?style=social&label=Star) [Gitlab](https://gitlab.com/paper-code/kvil_public) |  |
| _Key-patch_|
| [**CALAMARI: Contact-Aware and Language conditioned spatial Action MApping for contact-RIch manipulation**](https://openreview.net/pdf?id=Nii0_rRJwN) | CoRL 2023 | 2023-08-30 | [Project](https://www.mmintlab.com/research/calamari/) | key-patch |
| _Keypose_|
| [**KOI: Accelerating Online Imitation Learning via Hybrid Key-state Guidance**](https://www.arxiv.org/abs/2408.02912) | CoRL 2024 | 2024-08-06 | ![Star](https://img.shields.io/github/stars/GeWu-Lab/Keystate_Online_Imitation?style=social&label=Star) [Github](https://github.com/GeWu-Lab/Keystate_Online_Imitation) | Key-state |
| [**BiKC: Keypose-Conditioned Consistency Policy for Bimanual Robotic Manipulation**](https://arxiv.org/abs/2406.10093) | arXiv | 2024-06-14 | ![Star](https://img.shields.io/github/stars/ManUtdMoon/BiKC?style=social&label=Star) [Github](https://github.com/ManUtdMoon/BiKC) |  |
| _Waypoint_ |
| [**VIEW: Visual Imitation Learning with Waypoints**](https://arxiv.org/abs/2404.17906) | Auton. Robots 2025 | 2024-04-27 | ![Star](https://img.shields.io/github/stars/VT-Collab/view?style=social&label=Star) [Github](https://github.com/VT-Collab/view) |  |
| [SPHINX: **What's the Move? Hybrid Imitation Learning via Salient Points**](https://arxiv.org/abs/2412.05426) | ICLR 2025 | 2024-12-06 | ![Star](https://img.shields.io/github/stars/priyasundaresan/sphinx?style=social&label=Star) [Github](https://github.com/priyasundaresan/sphinx) |  |
| [AWE: **Waypoint-Based Imitation Learning for Robotic Manipulation**](https://arxiv.org/abs/2307.14326) | CoRL 2023 | 2023-07-26 | ![Star](https://img.shields.io/github/stars/lucys0/awe?style=social&label=Star) [Github](https://github.com/lucys0/awe) |  |
| _Visual Trace_ |
| [**L2D2: Robot Learning from 2D Drawings**](https://arxiv.org/abs/2505.12072) | arXiv | 2025-05-17 | [Project](https://collab.me.vt.edu/L2D2/) | Visual Trace |
| [**AimBot: A Simple Auxiliary Visual Cue to Enhance Spatial Awareness of Visuomotor Policies**](https://arxiv.org/abs/2508.08113) | CoRL 2025 | 2025-08-11 | ![Star](https://img.shields.io/github/stars/aimbot-reticle/openpi0-aimbot?style=social&label=Star)  [Github](https://github.com/aimbot-reticle/openpi0-aimbot) | Visual Trace |
| _Visual Track_|
| [**Diffusion Trajectory-guided Policy for Long-horizon Robot Manipulation**](https://arxiv.org/abs/2502.10040) | arXiv | 2025-02-14 | - |  |
| [**Motion Tracks: A Unified Representation for Human-Robot Transfer in Few-Shot Imitation Learning**](https://arxiv.org/abs/2501.06994) | arXiv | 2025-01-13 | [Project](https://portal-cornell.github.io/motion_track_policy/) |  |
| [**P3-PO: Prescriptive Point Priors for Visuo-Spatial Generalization of Robot Policies**](https://arxiv.org/abs/2412.06784) | arXiv | 2024-12-09 | ![Star](https://img.shields.io/github/stars/mlevy2525/P3PO?style=social&label=Star) [Github](https://github.com/mlevy2525/P3PO) |  |
| [**Track2Act: Predicting Point Tracks from Internet Videos enables Generalizable Robot Manipulation**](https://arxiv.org/abs/2405.01527) | ECCV 2024 | 2024-05-02 | ![Star](https://img.shields.io/github/stars/homangab/Track-2-Act?style=social&label=Star) [Github](https://github.com/homangab/Track-2-Act) |  |
| [ATM: **Any-point Trajectory Modeling for Policy Learning**](https://arxiv.org/abs/2401.00025) | RSS 2024 | 2023-12-28 | ![Star](https://img.shields.io/github/stars/Large-Trajectory-Model/any-point-trajectory-modeling?style=social&label=Star) [Github](https://github.com/Large-Trajectory-Model/any-point-trajectory-modeling) |  |
| _Flow_|
| [**ActionSink: Toward Precise Robot Manipulation with Dynamic Integration of Action Flow**](https://www.arxiv.org/abs/2508.03218) | arXiv | 2025-08-05 | - |  |
| [**VLM-SFD: VLM-Assisted Siamese Flow Diffusion Framework for Dual-Arm Cooperative Manipulation**](https://arxiv.org/abs/2506.13428) | arXiv | 2025-06-16 | [Project](https://sites.google.com/view/vlm-sfd/) |  |
| [**3DFlowAction: Learning Cross-Embodiment Manipulation from 3D Flow World Model**](https://arxiv.org/abs/2506.06199) | arXiv | 2025-06-06 | ![Star](https://img.shields.io/github/stars/Hoyyyaard/3DFlowAction?style=social&label=Star) [Github](https://github.com/Hoyyyaard/3DFlowAction/) |  |
| [**ManiTrend: Bridging Future Generation and Action Prediction with 3D Flow for Robotic Manipulation**](https://arxiv.org/abs/2502.10028) | arXiv | 2025-02-14 | - |  |
| [**GenFlowRL: Shaping Rewards with Generative Object-Centric Flow in Visual Reinforcement Learning**](https://arxiv.org/abs/2508.11049) | ICCV 2025 | 2025-08-14 | [Project](https://colinyu1.github.io/genflowrl/) |  |
| [**EC-Flow: Enabling Versatile Robotic Manipulation from Action-Unlabeled Videos via Embodiment-Centric Flow**](https://arxiv.org/abs/2507.06224) | ICCV 2025 | 2025-07-08 | ![Star](https://img.shields.io/github/stars/YixiangChen515/EC-Flow?style=social&label=Star) [Github](https://github.com/YixiangChen515/EC-Flow) |  |
| [**VIP: Vision Instructed Pre-training for Robotic Manipulation**](https://arxiv.org/abs/2410.07169) | ICML 2025 | 2024-10-09 | ![Star](https://img.shields.io/github/stars/Lizhuoling/VIRT?style=social&label=Star) [Github](https://github.com/Lizhuoling/VIRT) |  |
| [**G3Flow: Generative 3D Semantic Flow for Pose-aware and Generalizable Object Manipulation**](https://arxiv.org/abs/2411.18369) | CVPR 2025 | 2024-11-27 | ![Star](https://img.shields.io/github/stars/TianxingChen/G3Flow?style=social&label=Star) [Github](https://github.com/TianxingChen/G3Flow) | Semantic Flow |
| [Im2Flow2Act: **Flow as the Cross-Domain Manipulation Interface**](https://www.arxiv.org/abs/2407.15208) | CoRL 2024 | 2024-07-21 | ![Star](https://img.shields.io/github/stars/real-stanford/im2Flow2Act?style=social&label=Star) [Github](https://github.com/real-stanford/im2Flow2Act) |  |
| [AVDC: **Learning to Act from Actionless Videos through Dense Correspondences**](https://arxiv.org/abs/2310.08576) | ICLR 2024 | 2023-10-12 | ![Star](https://img.shields.io/github/stars/flow-diffusion/AVDC?style=social&label=Star) [Github](https://github.com/flow-diffusion/AVDC) | Optical Flow |
| [**ToolFlowNet: Robotic Manipulation with Tools via Predicting Tool Flow from Point Clouds**](https://arxiv.org/abs/2211.09006) | CoRL 2022 | 2022-11-16 | ![Star](https://img.shields.io/github/stars/DanielTakeshi/softgym_tfn?style=social&label=Star) [Github](https://github.com/DanielTakeshi/softgym_tfn) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>



## Input Modality

### Vision Action Models
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| Comming soon |

<div align="center">

### <i>Vision Language Action Models</i>

</div>

### 2D Vision Language Action Models
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Language-conditioned Policy_ |
| [**SEM: Enhancing Spatial Understanding for Robust Robot Manipulation**](https://arxiv.org/abs/2505.16196) | arXiv | 2025-05-22 | ![Star](https://img.shields.io/github/stars/HorizonRobotics/robo_orchard_lab?style=social&label=Star) [Github](https://github.com/HorizonRobotics/robo_orchard_lab/tree/master/projects/sem/robotwin) |  |
| [**Bi-LAT: Bilateral Control-Based Imitation Learning via Natural Language and Action Chunking with Transformers**](https://arxiv.org/abs/2504.01301) | arXiv | 2025-04-02 | [Project](https://mertcookimg.github.io/bi-lat/) |  |
| [**RoboBERT: An End-to-end Multimodal Robotic Manipulation Model**](https://arxiv.org/abs/2502.07837) | arXiv | 2025-02-11 | ![Star](https://img.shields.io/github/stars/PeterWangsicheng/RoboBERT?style=social&label=Star) [Github](https://github.com/PeterWangsicheng/RoboBERT) | |
| [**Dita: Scaling Diffusion Transformer for Generalist Vision-Language-Action Policy**](https://arxiv.org/abs/2503.19757) | arXiv | 2025-03-25 | ![Star](https://img.shields.io/github/stars/RoboDita/Dita?style=social&label=Star) [Github](https://github.com/RoboDita/Dita) |  |
| [**OTTER: A Vision-Language-Action Model with Text-Aware Visual Feature Extraction**](https://arxiv.org/abs/2503.03734) | ICML 2025 | 2025-03-05 | ![Star](https://img.shields.io/github/stars/Max-Fu/otter?style=social&label=Star) [Github](https://github.com/Max-Fu/otter) |  |
| [**RoboGround: Robotic Manipulation with Grounded Vision-Language Priors**](https://arxiv.org/abs/2504.21530) | CVPR 2025 | 2025-04-30 | ![Star](https://img.shields.io/github/stars/ZzZZCHS/RoboGround?style=social&label=Star) [Github](https://github.com/ZzZZCHS/RoboGround) |  |
| [**BAKU: An Efficient Transformer for Multi-Task Policy Learning**](https://arxiv.org/abs/2406.07539) | NeurIPS 2024 | 2024-06-11 | ![Star](https://img.shields.io/github/stars/siddhanthaldar/BAKU?style=social&label=Star) [Github](https://github.com/siddhanthaldar/BAKU) |  |
| [**Uncertainty-Aware Deployment of Pre-trained Language-Conditioned Imitation Learning Policies**](https://arxiv.org/abs/2403.18222) | IROS 2024 | 2024-03-27 | ![Star](https://img.shields.io/github/stars/BobWu1998/uncertainty_quant_all?style=social&label=Star) [Github](https://github.com/BobWu1998/uncertainty_quant_all) |  |
| [**STEER: Flexible Robotic Manipulation via Dense Language Grounding**](https://arxiv.org/abs/2411.03409) | CoRLW 2024 | 2023-11-05 | [Project](https://lauramsmith.github.io/steer/) |  |
| [**Mastering Robot Manipulation with Multimodal Prompts through Pretraining and Multi-task Fine-tuning**](https://arxiv.org/abs/2310.09676) | ICML 2024 | 2023-10-14 | [Project](https://midas-icml.github.io/) | Autoregressive |
| [**Octo: An Open-Source Generalist Robot Policy**](https://arxiv.org/abs/2405.12213) | RSS 2024 | 2024-05-20 | ![Star](https://img.shields.io/github/stars/octo-models/octo?style=social&label=Star)  [Github](https://github.com/octo-models/octo) | |
| [MDT: **Multimodal Diffusion Transformer: Learning Versatile Behavior from Multimodal Goals**](https://arxiv.org/abs/2407.05996) | RSS 2024 | 2024-07-08 | ![Star](https://img.shields.io/github/stars/intuitive-robots/mdt_policy?style=social&label=Star) [Github](https://github.com/intuitive-robots/mdt_policy) | Masked Construction, Partially labeled data |
| [**Language-Conditioned Imitation Learning with Base Skill Priors under Unstructured Data**](https://arxiv.org/abs/2305.19075) | RA-L 2024 | 2023-05-30 | [Project](https://language-play.github.io/) | Partially labeled data |
| [**Transferring Foundation Models for Generalizable Robotic Manipulation**](https://arxiv.org/abs/2306.05716) | WACV 2023 | 2023-06-09 | - |  |
| [**CALAMARI: Contact-Aware and Language conditioned spatial Action MApping for contact-RIch manipulation**](https://openreview.net/pdf?id=Nii0_rRJwN) | CoRL 2023 | 2023-08-30 | [Project](https://www.mmintlab.com/research/calamari/) | key |
| [**MResT: Multi-Resolution Sensing for Real-Time Control with Vision-Language Models**](https://arxiv.org/abs/2401.14502) | CoRL 2023 | 2024-01-25 | ![Star](https://img.shields.io/github/stars/iamlab-cmu/mrest-multi-resolution-transformer?style=social&label=Star) [Github](https://github.com/iamlab-cmu/mrest-multi-resolution-transformer) | IL, RepL, Multi-Resolution, Poliy Head |
| [**VIMA: General Robot Manipulation with Multimodal Prompts**](https://arxiv.org/abs/2210.03094) | ICML 2023 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/vimalabs/VIMA?style=social&label=Star) [Github](https://github.com/vimalabs/VIMA) | MLP |
| [**RT-1: Robotics Transformer for Real-World Control at Scale**](https://arxiv.org/abs/2212.06817) | RSS 2023 | 2022-12-13 | ![Star](https://img.shields.io/github/stars/google-research/robotics_transformer?style=social&label=Star) [Github](https://github.com/google-research/robotics_transformer) |  |
| [HULC++: **Grounding Language with Visual Affordances over Unstructured Data**](https://arxiv.org/abs/2210.01911) | ICRA 2023 | 2022-10-04 | ![Star](https://img.shields.io/github/stars/mees/hulc2?style=social&label=Star) [Github](https://github.com/mees/hulc2) |  |
| [**Grounding Object Relations in Language-Conditioned Robotic Manipulation with Semantic-Spatial Reasoning**](https://arxiv.org/abs/2303.17919) | AAAIW 2023 | 2023-03-31 | ![Star](https://img.shields.io/github/stars/vimalabs/VIMA?style=social&label=Star) [Github](https://github.com/vimalabs/VIMA) |  |
| [HULC: **What Matters in Language Conditioned Robotic Imitation Learning over Unstructured Data**](https://arxiv.org/abs/2204.06252) | RA-L 2022 | 2022-04-13 | ![Star](https://img.shields.io/github/stars/lukashermann/hulc?style=social&label=Star) [Github](https://github.com/lukashermann/hulc) |  |
| [**LISA: Learning Interpretable Skill Abstractions from Language**](https://arxiv.org/abs/2203.00054) | NeurIPS 2022 | 2022-03-28 | ![Star](https://img.shields.io/github/stars/Div99/LISA?style=social&label=Star) [Github](https://github.com/Div99/LISA) |  |
| [**Language Conditioned Imitation Learning over Unstructured Data**](https://arxiv.org/abs/2005.07648) | RSS 2021 | 2020-05-15 | [Project](https://language-play.github.io/) | Partially labeled data |
| [**Language-Conditioned Imitation Learning for Robot Manipulation Tasks**](https://arxiv.org/abs/2010.12083) | NeurIPS 2020 | 2020-10-22 | ![Star](https://img.shields.io/github/stars/ir-lab/LanguagePolicies?style=social&label=Star) [Github](https://github.com/ir-lab/LanguagePolicies) |  |
| _LLM/VLM-based VLA_ |
| [**GR-3 Technical Report**](https://arxiv.org/abs/2507.15493) | arXiv | 2025-07-18 | [Project](https://seed.bytedance.com/zh/GR3) | |
| [**cVLA: Towards Efficient Camera-Space VLAs**](https://arxiv.org/abs/2507.02190) | arXiv | 2025-07-02 | - | Keypose |
| [UniVLA: **Unified Vision-Language-Action Model**](https://arxiv.org/abs/2506.19850) | arXiv | 2025-06-24 | ![Star](https://img.shields.io/github/stars/baaivision/UniVLA?style=social&label=Star) [Github](https://github.com/baaivision/UniVLA) | |
| [ChatVLA-2: **Vision-Language-Action Model with Open-World Embodied Reasoning from Pretrained Knowledge**](https://arxiv.org/abs/2505.21906) | arXiv | 2025-05-28 | [Project](https://chatvla-2.github.io/) | |
| [**Interleave-VLA: Enhancing Robot Manipulation with Interleaved Image-Text Instructions**](https://arxiv.org/abs/2505.02152) | arXiv | 2025-05-04 | [Project](https://interleave-vla-anonymous.github.io/Interleave-VLA-Anonymous/) |  |
| [**HybridVLA: Collaborative Diffusion and Autoregression in a Unified Vision-Language-Action Model**](https://arxiv.org/abs/2503.10631) | arXiv | 2025-03-13 | ![Star](https://img.shields.io/github/stars/PKU-HMI-Lab/Hybrid-VLA?style=social&label=Star) [Github](https://github.com/PKU-HMI-Lab/Hybrid-VLA) |  |
| [OpenVLA-Oft: **Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success**](https://arxiv.org/abs/2502.19645) | arXiv | 2025-02-27 | ![Star](https://img.shields.io/github/stars/moojink/openvla-oft?style=social&label=Star) [Github](https://github.com/moojink/openvla-oft) |  |
| [**ObjectVLA: End-to-End Open-World Object Manipulation Without Demonstration**](https://arxiv.org/abs/2502.19250) | arXiv | 2025-02-26 | [Project](https://objectvla.github.io/) |  |
| [**ChatVLA: Unified Multimodal Understanding and Robot Control with Vision-Language-Action Model**](https://arxiv.org/abs/2502.14420) | arXiv | 2025-02-20 | ![Star](https://img.shields.io/github/stars/tutujingyugang1/ChatVLA_public?style=social&label=Star) [Github](https://github.com/tutujingyugang1/ChatVLA_public) |  |
| [**DexVLA: Vision-Language Model with Plug-In Diffusion Expert for General Robot Control**](https://arxiv.org/abs/2502.05855) | arXiv | 2025-02-09 | ![Star](https://img.shields.io/github/stars/juruobenruo/DexVLA?style=social&label=Star) [Github](https://github.com/juruobenruo/DexVLA) |  |
| [**CogACT: A Foundational Vision-Language-Action Model for Synergizing Cognition and Action in Robotic Manipulation**](https://arxiv.org/abs/2411.19650) | arXiv | 2024-12-29 | ![Star](https://img.shields.io/github/stars/microsoft/CogACT?style=social&label=Star) [Github](https://github.com/microsoft/CogACT) |  |
| [RoboVLMs: **Towards Generalist Robot Policies: What Matters in Building Vision-Language-Action Models**](https://arxiv.org/abs/2412.14058) | arXiv | 2024-12-18 | ![Star](https://img.shields.io/github/stars/Robot-VLAs/RoboVLMs?style=social&label=Star) [Github](https://github.com/Robot-VLAs/RoboVLMs) |  |
| [**Diffusion-VLA: Scaling Robot Foundation Models via Unified Diffusion and Autoregression**](https://arxiv.org/abs/2412.03293) | ICML 2025 | 2024-12-14 | [Project](https://diffusion-vla.github.io/) |  |
| [**π<sub>0</sub>: A Vision-Language-Action Flow Model for General Robot Control**](https://arxiv.org/abs/2410.24164) | arXiv | 2024-10-31 | ![Star](https://img.shields.io/github/stars/Physical-Intelligence/openpi?style=social&label=Star) [Github](https://github.com/Physical-Intelligence/openpi) |  |
| [**Magma: A Foundation Model for Multimodal AI Agents**](https://arxiv.org/abs/2502.13130) | CVPR 2025 | 2025-02-18 | ![Star](https://img.shields.io/github/stars/microsoft/Magma?style=social&label=Star) [Github](https://github.com/microsoft/Magma) |  |
| [**RoboMamba: Multimodal State Space Model for Efficient Robot Reasoning and Manipulation**](https://arxiv.org/abs/2406.04339) | NeurIPS 2024 | 2024-06-06 | ![Star](https://img.shields.io/github/stars/lmzpai/roboMamba?style=social&label=Star) [Github](https://github.com/lmzpai/roboMamba) |  |
| [**OpenVLA: An Open-Source Vision-Language-Action Model**](https://arxiv.org/abs/2406.09246) | CoRL 2024 | 2024-06-13 | ![Star](https://img.shields.io/github/stars/openvla/openvla?style=social&label=Star) [Github](https://github.com/openvla/openvla) |  |
| [RoboFlamingo: **Vision-Language Foundation Models as Effective Robot Imitators**](https://arxiv.org/abs/2311.01378) | ICLR 2024 | 2023-11-02 | ![Star](https://img.shields.io/github/stars/RoboFlamingo/RoboFlamingo?style=social&label=Star) [Github](https://github.com/RoboFlamingo/RoboFlamingo) |  |
| [**RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control**](https://arxiv.org/abs/2307.15818) | CoRL 2023 | 2023-07-28 | [Project](https://robotics-transformer2.github.io/) |  |
| _Model-agnostic_ |
| [**Grounding Actions in Camera Space: Observation-Centric Vision-Language-Action Policy**](https://arxiv.org/abs/2508.13103) | arXiv | 2025-08-18 | - | |
| [**Leveraging OS-Level Primitives for Robotic Action Management**](https://arxiv.org/abs/2508.10259) | arXiv | 2025-08-14 | - | |
| [**AR-VRM: Imitating Human Motions for Visual Robot Manipulation with Analogical Reasoning**](https://arxiv.org/abs/2508.07626) | ICCV 2025 | 2025-08-11 | ![Star](https://img.shields.io/github/stars/idejie/ar?style=social&label=Star) [Github](https://github.com/idejie/ar) | In-Context VLA |
| [**Improving Pre-Trained Vision-Language-Action Policies with Model-Based Search**](https://arxiv.org/abs/2508.12211) | arXiv | 2025-08-17 | - | |
| [**Confidence Calibration in Vision-Language-Action Models**](https://arxiv.org/abs/2507.17383) | arXiv | 2025-07-23 | - | |
| [**VOTE: Vision-Language-Action Optimization with Trajectory Ensemble Voting**](https://arxiv.org/abs/2507.05116) | arXiv | 2025-07-07 | ![Star](https://img.shields.io/github/stars/LukeLIN-web/VOTE?style=social&label=Star) [Github](https://github.com/LukeLIN-web/VOTE) | |
| [**MoIRA: Modular Instruction Routing Architecture for Multi-Task Robotics**](https://arxiv.org/abs/2507.01843) | arXiv | 2025-07-02 | - | |
| [**CronusVLA: Transferring Latent Motion Across Time for Multi-Frame Prediction in Manipulation**](https://arxiv.org/abs/2506.19816) | arXiv | 2025-06-24 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/CronusVLA?style=social&label=Star) [Github](https://github.com/OpenRobotLab/CronusVLA) | |
| [**RoboMonkey: Scaling Test-Time Sampling and Verification for Vision-Language-Action Models**](https://arxiv.org/abs/2506.17811) | arXiv | 2025-06-21 | [Project](https://robomonkey-vla.github.io/) | |
| [**RICL: Adding In-Context Adaptability to Pre-Trained Vision-Language-Action Models**](https://www.arxiv.org/abs/2508.02062) | CoRL 2025 | 2025-08-04 | ![Star](https://img.shields.io/github/stars/ricl-vla/ricl_openpi?style=social&label=Star) [Github](https://github.com/ricl-vla/ricl_openpi) | In-Context VLA |
| [**VLA Model-Expert Collaboration for Bi-directional Manipulation Learning**](https://arxiv.org/abs/2503.04163) | arXiv | 2025-03-06 | [Project](https://aoqunjin.github.io/Expert-VLA/) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### 2D Vision Language Action Models with RL
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**CO-RFT: Efficient Fine-Tuning of Vision-Language-Action Models through Chunked Offline Reinforcement Learning**](https://arxiv.org/abs/2508.02219) | arXiv | 2025-08-04 | - |  |
| [**ThinkAct: Vision-Language-Action Reasoning via Reinforced Visual Latent Planning**](https://arxiv.org/abs/2507.16815) | arXiv | 2025-07-22 | [Project](https://jasper0314-huang.github.io/thinkact-vla/) | |
| [**RLRC: Reinforcement Learning-based Recovery for Compressed Vision-Language-Action Models**](https://arxiv.org/abs/2506.17639) | arXiv | 2025-06-21 | [Project](https://rlrc-vla.github.io/) | |
| [**TGRPO :Fine-tuning Vision-Language-Action Model via Trajectory-wise Group Relative Policy Optimization**](https://arxiv.org/abs/2506.08440) | arXiv | 2025-06-10 | ![Star](https://img.shields.io/github/stars/hahans/TGRPO?style=social&label=Star) [Github](https://github.com/hahans/TGRPO) | |
| [**VLA-RL: Towards Masterful and General Robotic Manipulation with Scalable Reinforcement Learning**](https://arxiv.org/abs/2505.18719) | arXiv | 2025-05-24 | ![Star](https://img.shields.io/github/stars/GuanxingLu/vlarl?style=social&label=Star) [Github](https://github.com/GuanxingLu/vlarl) | |
| [RIPT-VLA: **Interactive Post-Training for Vision-Language-Action Models**](https://arxiv.org/abs/2505.17016) | arXiv | 2025-05-22 | ![Star](https://img.shields.io/github/stars/Ariostgx/ript-vla?style=social&label=Star) [Github](https://github.com/Ariostgx/ript-vla) |  |
| [**ManipLVM-R1: Reinforcement Learning for Reasoning in Embodied Manipulation with Large Vision-Language Models**](https://arxiv.org/abs/2505.16517) | arXiv | 2025-05-22 | - | |
| [**Incentivizing Multimodal Reasoning in Large Models for Direct Robot Manipulation**](https://arxiv.org/abs/2505.12744) | arXiv | 2025-05-19 | - | |
| [**ConRFT: A Reinforced Fine-tuning Method for VLA Models via Consistency Policy**](https://arxiv.org/abs/2502.05450) | RSS 2025 | 2025-02-08 | ![Star](https://img.shields.io/github/stars/cccedric/conrft?style=social&label=Star) [Github](https://github.com/cccedric/conrft) |  |
| [**RLDG: Robotic Generalist Policy Distillation via Reinforcement Learning**](https://arxiv.org/abs/2412.09858) | arXiv | 2024-12-13 | [Project](https://generalist-distillation.github.io/) |  |
| [V-GPS: **Steering Your Generalists: Improving Robotic Foundation Models via Value Guidance**](https://arxiv.org/abs/2410.13816) | CoRL 2024 | 2024-10-17 | [Project](https://nakamotoo.github.io/V-GPS/index.html) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### 2D Vision Language Action Models with Latent Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**MemoryVLA: Perceptual-Cognitive Memory in Vision-Language-Action Models for Robotic Manipulation**](https://arxiv.org/abs/2508.19236) | arXiv | 2025-08-26 | [Project](https://shihao1895.github.io/MemoryVLA/) | |
| [**UniVLA: Learning to Act Anywhere with Task-centric Latent Actions**](https://www.arxiv.org/abs/2505.06111) | RSS 2025 | 2025-05-09 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/UniVLA?style=social&label=Star) [Github](https://github.com/OpenDriveLab/UniVLA) | |
| [**villa-X: Enhancing Latent Action Modeling in Vision-Language-Action Models**](https://arxiv.org/abs/2507.23682) | arXiv | 2025-07-31 | ![Star](https://img.shields.io/github/stars/microsoft/villa-x?style=social&label=Star) [Github](https://github.com/microsoft/villa-x) | |
| [**VQ-VLA: Improving Vision-Language-Action Models via Scaling Vector-Quantized Action Tokenizers**](https://arxiv.org/abs/2507.01016) | ICCV 2025 | 2025-07-01 | ![Star](https://img.shields.io/github/stars/xiaoxiao0406/VQ-VLA?style=social&label=Star) [Github](https://github.com/xiaoxiao0406/VQ-VLA) | |
| [**DeeR-VLA: Dynamic Inference of Multimodal Large Language Models for Efficient Robot Execution**](https://arxiv.org/abs/2411.02359) | NeurIPS 2024 | 2024-11-04 | [Github](https://github.com/yueyang130/DeeR-VLA) |  |
| [**QueST: Self-Supervised Skill Abstractions for Learning Continuous Control**](https://arxiv.org/abs/2407.15840) | NeurIPS 2024 | 2024-07-22 | ![Star](https://img.shields.io/github/stars/pairlab/QueST?style=social&label=Star) [Github](https://github.com/pairlab/QueST) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### 2D Vision Language Action Models with Auxiliary Tasks
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _CoT VLA_ |
| [**FlowVLA: Thinking in Motion with a Visual Chain of Thought**](https://arxiv.org/abs/2508.18269) | arXiv | 2025-08-25 | [Project](https://irpn-lab.github.io/FlowVLA/) |  |
| [**Information-Theoretic Graph Fusion with Vision-Language-Action Model for Policy Reasoning and Dual Robotic Control**](https://www.arxiv.org/abs/2508.05342) | arXiv | 2025-08-07 | - |  |
| [**OneTwoVLA: A Unified Vision-Language-Action Model with Adaptive Reasoning**](https://arxiv.org/abs/2505.11917) | arXiv | 2025-05-17 | ![Star](https://img.shields.io/github/stars/Fanqi-Lin/OneTwoVLA?style=social&label=Star) [Github](https://github.com/Fanqi-Lin/OneTwoVLA) | |
| [ECoT-Lite: **Training Strategies for Efficient Embodied Reasoning**](https://arxiv.org/abs/2505.08243) | arXiv | 2025-05-13 | - | |
| [**GraspVLA: a Grasping Foundation Model Pre-trained on Billion-scale Synthetic Action Data**](https://arxiv.org/abs/2505.03233) | arXiv | 2025-05-06 | ![Star](https://img.shields.io/github/stars/PKU-EPIC/GraspVLA?style=social&label=Star) [Github](https://github.com/PKU-EPIC/GraspVLA) |  |
| [**π<sub>0.5</sub>: a Vision-Language-Action Model with Open-World Generalization**](https://arxiv.org/abs/2504.16054) | arXiv | 2025-04-22 | [Project](https://www.pi.website/blog/pi05) |  |
| [DIARC‑OpenVLA: **Probing a Vision-Language-Action Model for Symbolic States and Integration into a Cognitive Architecture**](https://arxiv.org/abs/2502.04558) | arXiv | 2025-02-06 | - |  |
| [RAD: **Action-Free Reasoning for Policy Generalization**](https://arxiv.org/abs/2502.03729) | arXiv | 2025-02-06 | [Project](https://rad-generalization.github.io/) |  |
| [**UP-VLA: A Unified Understanding and Prediction Model for Embodied Agent**](https://arxiv.org/abs/2501.18867) | ICML 2025 | 2025-01-31 | ![Star](https://img.shields.io/github/stars/CladernyJorn/UP-VLA?style=social&label=Star) [Github](https://github.com/CladernyJorn/UP-VLA) |  |
| [**Emma-X: An Embodied Multimodal Action Model with Grounded Chain of Thought and Look-ahead Spatial Reasoning**](https://arxiv.org/abs/2412.11974) | arXiv | 2024-12-16 | ![Star](https://img.shields.io/github/stars/declare-lab/Emma-X?style=social&label=Star) [Github](https://github.com/declare-lab/Emma-X) |  |
| [**CoT-VLA: Visual Chain-of-Thought Reasoning for Vision-Language-Action Models**](https://arxiv.org/abs/2503.22020) | CVPR 2025 | 2025-03-27 | [Project](https://cot-vla.github.io/) |  |
| [ECoT: **Robotic Control via Embodied Chain-of-Thought Reasoning**](https://arxiv.org/abs/2407.08693) | CoRL 2024 | 2024-07-11 | ![Star](https://img.shields.io/github/stars/MichalZawalski/embodied-CoT?style=social&label=Star) [Github](https://github.com/MichalZawalski/embodied-CoT/) |  |
| [**RT-H: Action Hierarchies Using Language**](https://arxiv.org/abs/2403.01823) | RSS 2024 | 2024-03-04 | [Project](https://rt-hierarchy.github.io/) |  |
| _Text Goal Extraction_ |
| [**VLA-OS: Structuring and Dissecting Planning Representations and Paradigms in Vision-Language-Action Models**](https://arxiv.org/abs/2506.17561) | arXiv | 2025-06-21 | ![Star](https://img.shields.io/github/stars/HeegerGao/VLA-OS?style=social&label=Star) [Github](https://github.com/HeegerGao/VLA-OS) | |
| _Visual Goal Extraction_ |
| [**ControlVLA: Few-shot Object-centric Adaptation for Pre-trained Vision-Language-Action Models**](https://arxiv.org/abs/2506.16211) | arXiv | 2025-06-19 | ![Star](https://img.shields.io/github/stars/ControlVLA/ControlVLA?style=social&label=Star) [Github](https://github.com/ControlVLA/ControlVLA) | Segmentation |
| [**CrayonRobo: Object-Centric Prompt-Driven Vision-Language-Action Model for Robotic Manipulation**](https://arxiv.org/abs/2505.02166) | CVPR 2025 | 2025-05-04 | - | Contact Point, Visual Trace |
| [**A0: An Affordance-Aware Hierarchical Model for General Robotic Manipulation**](https://arxiv.org/abs/2504.12636) | arXiv | 2025-04-17 | ![Star](https://img.shields.io/github/stars/A-embodied/A0?style=social&label=Star) [Github](https://github.com/A-embodied/A0) | Keypoints |
| [Seer: **Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation**](https://arxiv.org/abs/2412.15109) | ICLR 2025 | 2024-12-19 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/Seer?style=social&label=Star) [Github](https://github.com/OpenRobotLab/Seer/) | Image Prediction |
| [**TraceVLA: Visual Trace Prompting Enhances Spatial-Temporal Awareness for Generalist Robotic Policies**](https://arxiv.org/abs/2412.10345) | ICLR 2025 | 2024-12-13 | ![Star](https://img.shields.io/github/stars/umd-huang-lab/tracevla?style=social&label=Star) [Github](https://github.com/umd-huang-lab/tracevla) | Visual Trace |
| [**LLARVA: Vision-Action Instruction Tuning Enhances Robot Learning**](https://arxiv.org/abs/2406.11815) | CoRL 2024 | 2024-06-17 | ![Star](https://img.shields.io/github/stars/Dantong88/LLARVA?style=social&label=Star) [Github](https://github.com/Dantong88/LLARVA) | Visual Trace |
| [MOO: **Open-World Object Manipulation using Pre-trained Vision-Language Models**](https://arxiv.org/abs/2303.00905) | CoRL 2023 | 2023-03-02 | [Project](https://robot-moo.github.io/) | BBox |
| _Reconstruction_ |
| [**ReconVLA: Reconstructive Vision-Language-Action Model as Effective Robot Perceiver**](https://arxiv.org/abs/2508.10333) | arXiv | 2025-08-23 | ![Star](https://img.shields.io/github/stars/Chowzy069/Reconvla?style=social&label=Star) [Github](https://github.com/Chowzy069/Reconvla) | |
| [**DreamVLA: A Vision-Language-Action Model Dreamed with Comprehensive World Knowledge**](https://arxiv.org/abs/2507.04447) | arXiv | 2025-07-13 | ![Star](https://img.shields.io/github/stars/Zhangwenyao1/DreamVLA?style=social&label=Star) [Github](https://github.com/Zhangwenyao1/DreamVLA) | |
| [GO-1: **AgiBot World Colosseo: A Large-scale Manipulation Platform for Scalable and Intelligent Embodied Systems**](https://arxiv.org/abs/2503.06669) | IROS 2025 | 2025-03-09 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/AgiBot-World?style=social&label=Star) [Github](https://github.com/OpenDriveLab/AgiBot-World) |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### 2D Structured Vision Language Action Models
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Hierarchical VLA_|
| [**HiBerNAC: Hierarchical Brain-emulated Robotic Neural Agent Collective for Disentangling Complex Manipulation**](https://arxiv.org/abs/2506.08296) | arXiv | 2025-06-09 | - |  |
| [**Hi Robot: Open-Ended Instruction Following with Hierarchical Vision-Language-Action Models**](https://arxiv.org/abs/2502.19417) | arXiv | 2025-02-26 | [Project](https://www.pi.website/research/hirobot) |  |
| [**PIVOT-R: Primitive-Driven Waypoint-Aware World Model for Robotic Manipulation**](https://arxiv.org/abs/2410.10394) | NeurIPS 2024 | 2024-10-14 | ![Star](https://img.shields.io/github/stars/abliao/PIVOT-R?style=social&label=Star) [Github](http://github.com/abliao/PIVOT-R) | IL, RepL, Image Prediction, Hierarchical, Poliy Head |
| _Dual-System VLA_|
| [**Galaxea Open-World Dataset and G0 Dual-System VLA Model**]() | - | 2025 | ![Star](https://img.shields.io/github/stars/OpenGalaxea/G0?style=social&label=Star) [Github](https://github.com/OpenGalaxea/G0) | |
| [**TriVLA: A Unified Triple-System-Based Unified Vision-Language-Action Model for General Robot Control**](https://arxiv.org/abs/2507.01424) | arXiv | 2025-07-01 | [Project](https://zhenyangliu.github.io/TriVLA/) | |
| [**RationalVLA: A Rational Vision-Language-Action Model with Dual System**](https://arxiv.org/abs/2506.10826) | arXiv | 2025-06-12 | [Project](https://irpn-eai.github.io/rational_vla) | |
| [**Fast-in-Slow: A Dual-System Foundation Model Unifying Fast Manipulation within Slow Reasoning**](https://arxiv.org/abs/2506.01953) | arXiv | 2025-06-02 | ![Star](https://img.shields.io/github/stars/CHEN-H01/Fast-in-Slow?style=social&label=Star) [Github](https://github.com/CHEN-H01/Fast-in-Slow) |  |
| [**Hume: Introducing System-2 Thinking in Visual-Language-Action Model**](https://arxiv.org/abs/2505.21432) | arXiv | 2025-05-27 | ![Star](https://img.shields.io/github/stars/hume-vla/hume?style=social&label=Star) [Github](https://github.com/hume-vla/hume) | |
| [**OpenHelix: A Short Survey, Empirical Analysis, and Open-Source Dual-System VLA Model for Robotic Manipulation**](https://arxiv.org/abs/2505.03912) | arXiv | 2025-05-06 | ![Star](https://img.shields.io/github/stars/OpenHelix-robot/OpenHelix?style=social&label=Star) [Github](https://github.com/OpenHelix-robot/OpenHelix) |  |
| [RoboDual: **Towards Synergistic, Generalized, and Efficient Dual-System for Robotic Manipulation**](https://arxiv.org/abs/2410.08001) | arXiv | 2024-10-10 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/RoboDual?style=social&label=Star) [Github](https://github.com/OpenDriveLab/RoboDual) |  |
| [**HiRT: Enhancing Robotic Control with Hierarchical Robot Transformers**](https://arxiv.org/abs/2410.05273) | CoRL 2024 | 2024-09-12 | - | IL, RepL, Hierarchical, Poliy Head |
| [DP-VLA: **A Dual Process VLA: Efficient Robotic Manipulation Leveraging VLM**](https://arxiv.org/abs/2410.15549) | CoRL 2024 | 2024-10-21 | - |  |
| [LCB: **From LLMs to Actions: Latent Codes as Bridges in Hierarchical Robot Control**](https://arxiv.org/abs/2405.04798) | IROS 2024 | 2024-05-08 | [Project](https://fredshentu.github.io/LCB_site/) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### 2D Vision Language Action Models with Efficiency and Robustness
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Efficiency_ |
| [**CogVLA: Cognition-Aligned Vision-Language-Action Model via Instruction-Driven Routing & Sparsification**](https://arxiv.org/abs/2508.21046) | arXiv | 2025-08-28 | ![Star](https://img.shields.io/github/stars/JiuTian-VL/CogVLA?style=social&label=Star) [Github](https://github.com/JiuTian-VL/CogVLA) |  |
| [**TTF-VLA: Temporal Token Fusion via Pixel-Attention Integration for Vision-Language-Action Models**](https://arxiv.org/abs/2508.19257) | arXiv | 2025-08-15 | - |  |
| [**Spec-VLA: Speculative Decoding for Vision-Language-Action Models with Relaxed Acceptance**](https://arxiv.org/abs/2507.22424) | arXiv | 2025-07-30 | - |  |
| [**EdgeVLA: Efficient Vision-Language-Action Models**](https://arxiv.org/abs/2507.14049) | arXiv | 2025-07-18 | - | |
| [**CEED-VLA: Consistency Vision-Language-Action Model with Early-Exit Decoding**](https://arxiv.org/abs/2506.13725) | arXiv | 2025-06-16 | ![Star](https://img.shields.io/github/stars/OpenHelix-Team/CEED-VLA?style=social&label=Star) [Github](https://github.com/OpenHelix-Team/CEED-VLA) | |
| [**SP-VLA: A Joint Model Scheduling and Token Pruning Approach for VLA Model Acceleration**](https://arxiv.org/abs/2506.12723) | arXiv | 2025-06-15 | - | |
| [**EfficientVLA: Training-Free Acceleration and Compression for Vision-Language-Action Models**](https://arxiv.org/abs/2506.10100) | arXiv | 2025-06-11 | - | |
| [**BEAST: Efficient Tokenization of B-Splines Encoded Action Sequences for Imitation Learning**](https://arxiv.org/abs/2506.06072) | arXiv | 2025-06-06 | ![Star](https://img.shields.io/github/stars/intuitive-robots/beast_calvin?style=social&label=Star) [Github](https://github.com/intuitive-robots/beast_calvin) | |
| [**BitVLA: 1-bit Vision-Language-Action Models for Robotics Manipulation**](https://arxiv.org/abs/2506.07530) | arXiv | 2025-06-09 | ![Star](https://img.shields.io/github/stars/ustcwhy/BitVLA?style=social&label=Star) [Github](https://github.com/ustcwhy/BitVLA) | |
| [**SmolVLA: A Vision-Language-Action Model  for Affordable and Efficient Robotics**](https://arxiv.org/abs/2506.01844) | arXiv | 2025-06-02 | ![Star](https://img.shields.io/github/stars/huggingface/lerobot?style=social&label=Star) [Github](https://github.com/huggingface/lerobot) | |
| [**Knowledge Insulating Vision-Language-Action Models: Train Fast, Run Fast, Generalize Better**](https://arxiv.org/abs/2505.23705) | arXiv | 2025-05-29 | [Project](https://www.pi.website/research/knowledge_insulation) | |
| [**Think Twice, Act Once: Token-Aware Compression and Action Reuse for Efficient Inference in Vision-Language-Action Models**](https://arxiv.org/abs/2505.21200) | arXiv | 2025-05-27 | - | |
| [**Saliency-Aware Quantized Imitation Learning for Efficient Robotic Control**](https://arxiv.org/abs/2505.15304) | arXiv | 2025-05-21 | - | |
| [**NORA: A Small Open-Sourced Generalist Vision Language Action Model for Embodied Tasks**](https://arxiv.org/abs/2504.19854) | arXiv | 2025-04-28 | ![Star](https://img.shields.io/github/stars/declare-lab/nora?style=social&label=Star) [Github](https://github.com/declare-lab/nora) |  |
| [**MoLe-VLA: Dynamic Layer-skipping Vision Language Action Model via Mixture-of-Layers for Efficient Robot Manipulation**](https://arxiv.org/abs/2503.20384) | arXiv | 2025-03-26 | ![Star](https://img.shields.io/github/stars/RoyZry98/MoLe-VLA-Pytorch?style=social&label=Star) [Github](https://github.com/RoyZry98/MoLe-VLA-Pytorch/) |  |
| [**Accelerating Vision-Language-Action Model Integrated with Action Chunking via Parallel Decoding**](https://arxiv.org/abs/2503.02310) | arXiv | 2025-02-28 | - |  |
| [**VLA-Cache: Towards Efficient Vision-Language-Action Model via Adaptive Token Caching in Robotic Manipulation**](https://arxiv.org/abs/2502.02175) | arXiv | 2025-02-04 | ![Star](https://img.shields.io/github/stars/siyuhsu/vla-cache?style=social&label=Star) [Github](https://github.com/siyuhsu/vla-cache) |  |
| [**Quantization-Aware Imitation-Learning for Resource-Efficient Robotic Control**](https://arxiv.org/abs/2412.01034) | arXiv | 2024-12-02 | - | |
| [**FLOWER: Democratizing Generalist Robot Policies with Efficient Vision-Language-Action Flow Policies**](https://openreview.net/forum?id=ifo8oWSLSq) | ICLRW 2025 | 2025-02-28 | ![Star](https://img.shields.io/github/stars/intuitive-robots/flower_vla_calvin?style=social&label=Star) [Github](https://github.com/intuitive-robots/flower_vla_calvin) |  |
| [**TinyVLA: Towards Fast, Data-Efficient Vision-Language-Action Models for Robotic Manipulation**](https://arxiv.org/abs/2409.12514) | RA-L 2025 | 2024-09-19 | ![Star](https://img.shields.io/github/stars/liyaxuanliyaxuan/TinyVLA?style=social&label=Star) [Github](https://github.com/liyaxuanliyaxuan/TinyVLA) |  |
| [**TAIL: Task-specific Adapters for Imitation Learning with Large Pretrained Models**](https://arxiv.org/abs/2310.05905) | ICLR 2024 | 2023-10-09 | - | |
| _Robust_ |
| [**SAFE: Multitask Failure Detection for Vision-Language-Action Models**](https://arxiv.org/abs/2506.09937) | arXiv | 2025-06-11 | [Project](https://vla-safe.github.io/) | Failure Recovery |
| [**SwitchVLA: Execution-Aware Task Switching for Vision-Language-Action Models**](https://arxiv.org/abs/2506.03574) | arXiv | 2025-06-04 | [Project](https://switchvla.github.io/) | |
| [**Adversarial Attacks on Robotic Vision Language Action Models**](https://arxiv.org/abs/2506.03350) | arXiv | 2025-06-03 | ![Star](https://img.shields.io/github/stars/eliotjones1/robogcg?style=social&label=Star) [Github](https://github.com/eliotjones1/robogcg) | Attack |
| [**BadVLA: Towards Backdoor Attacks on Vision-Language-Action Models via Objective-Decoupled Optimization**](https://arxiv.org/abs/2505.16640) | arXiv | 2025-05-22 | ![Star](https://img.shields.io/github/stars/Zxy-MLlab/BadVLA?style=social&label=Star) [Github](https://github.com/Zxy-MLlab/BadVLA) | Attack |
| [**Can We Detect Failures Without Failure Data? Uncertainty-Aware Runtime Failure Detection for Imitation Learning Policies**](https://arxiv.org/abs/2503.08558) | RSS 2025 | 2025-03-11 | ![Star](https://img.shields.io/github/stars/CXU-TRI/FAIL-Detect?style=social&label=Star) [Github](https://github.com/CXU-TRI/FAIL-Detect) | Failure Recovery |
| [BYOVLA: **Run-time Observation Interventions Make Vision-Language-Action Models More Visually Robust**](https://arxiv.org/abs/2410.01971) | arXiv | 2024-10-02 | ![Star](https://img.shields.io/github/stars/irom-lab/byovla?style=social&label=Star) [Github](https://github.com/irom-lab/byovla) |  |
| [**RACER: Rich Language-Guided Failure Recovery Policies for Imitation Learning**](https://arxiv.org/abs/2409.146743) | ICRA 2025 | 2024-09-23 | ![Star](https://img.shields.io/github/stars/sled-group/RACER?style=social&label=Star) [Github](https://github.com/sled-group/RACER) | Failure Recovery |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### 2D Vision Language Action Models for Generalization
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Long-horizon_|
| [**LoHoVLA: A Unified Vision-Language-Action Model for Long-Horizon Embodied Tasks**](https://arxiv.org/abs/2505.23705) | arXiv | 2025-05-29 | [Project](https://www.pi.website/research/knowledge_insulation) | |
| [**Agentic Robot: A Brain-Inspired Framework for Vision-Language-Action Models in Embodied Agents**](https://arxiv.org/abs/2505.23450) | arXiv | 2025-05-29 | ![Star](https://img.shields.io/github/stars/Agentic-Robot/agentic-robot?style=social&label=Star) [Github](https://github.com/Agentic-Robot/agentic-robot) | |
| [**Long-VLA: Unleashing Long-Horizon Capability of Vision Language Action Model for Robot Manipulation**](https://arxiv.org/abs/2508.19958) | CoRL 2025 | 2025-08-27 | [Project](https://long-vla.github.io/) | |
| [**Long‑Horizon Language‑Conditioned Imitation Learning for Robotic Manipulation**](https://ieeexplore.ieee.org/abstract/document/10934975/) | TMECH 2025 | 2025-03-20 | - | Partially labeled data |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### 3D Vision Language Action Models
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**GeoVLA: Empowering 3D Representations in Vision-Language-Action Models**](https://arxiv.org/abs/2508.09071) | arXiv | 2025-08-12 | [Project](https://linsun449.github.io/GeoVLA/) |  |
| [**GraphCoT-VLA: A 3D Spatial-Aware Reasoning Vision-Language-Action Model for Robotic Manipulation with Ambiguous Instructions**](https://arxiv.org/abs/2508.07650) | arXiv | 2025-08-11 | - |  |
| [**Learning to See and Act: Task-Aware View Planning for Robotic Manipulation**](https://arxiv.org/abs/2508.05186) | arXiv | 2025-08-07 | ![Star](https://img.shields.io/github/stars/HCPLab-SYSU/TAVP?style=social&label=Star) [Github](https://github.com/HCPLab-SYSU/TAVP) |  |
| [**Evo-0: Vision-Language-Action Model with Implicit Spatial Understanding**](https://arxiv.org/abs/2507.00416) | arXiv | 2025-07-01 | - | |
| [**BridgeVLA: Input-Output Alignment for Efficient 3D Manipulation Learning with Vision-Language Models**](https://arxiv.org/abs/2506.07961) | arXiv | 2025-06-09 | ![Star](https://img.shields.io/github/stars/BridgeVLA/BridgeVLA?style=social&label=Star) [Github](https://github.com/BridgeVLA/BridgeVLA) | |
| [**OG-VLA: 3D-Aware Vision Language Action Model via Orthographic Image Generation**](https://arxiv.org/abs/2506.01196) | arXiv | 2025-06-01 | [Project](https://og-vla.github.io/) | |
| [**FP3: A 3D Foundation Policy for Robotic Manipulation**](https://arxiv.org/abs/2503.08950) | arXiv | 2025-03-11 | ![Star](https://img.shields.io/github/stars/horipse01/3d-foundation-policy?style=social&label=Star) [Github](https://github.com/horipse01/3d-foundation-policy) |  |
| [**SpatialVLA: Exploring Spatial Representations for Visual-Language-Action Model**](https://arxiv.org/abs/2501.15830) | RSS 2025 | 2025-01-27 | ![Star](https://img.shields.io/github/stars/SpatialVLA/SpatialVLA?style=social&label=Star) [Github](https://github.com/SpatialVLA/SpatialVLA) |  |
| [**RoboMM: All-in-One Multimodal Large Model for Robotic Manipulation**](https://arxiv.org/abs/2412.07215) | arXiv | 2024-12-10 | ![Star](https://img.shields.io/github/stars/RoboUniview/RoboMM?style=social&label=Star) [Github](https://github.com/RoboUniview/RoboMM) |  |
| [**3D CAVLA: Leveraging Depth and 3D Context to Generalize Vision Language Action Models for Unseen Tasks**](https://arxiv.org/abs/2505.05800) | CVPRW 2025 | 2025-05-09 | ![Star](https://img.shields.io/github/stars/vineet2104/3dcavla?style=social&label=Star) [Github](https://github.com/vineet2104/3dcavla) |  |
| [**VoxAct-B: Voxel-Based Acting and Stabilizing Policy for Bimanual Manipulation**](https://arxiv.org/abs/2407.04152) | CoRL 2024 | 2024-07-04 | ![Star](https://img.shields.io/github/stars/VoxAct-B/voxactb?style=social&label=Star) [Github](https://github.com/VoxAct-B/voxactb) |  |
| [**VIHE: Virtual In-Hand Eye Transformer for 3D Robotic Manipulation**](https://arxiv.org/abs/2403.11461) | IROS 2024 | 2024-03-13 | ![Star](https://img.shields.io/github/stars/doublelei/VIHE?style=social&label=Star) [Github](https://github.com/doublelei/VIHE) |  |
| [**3D-VLA: A 3D Vision-Language-Action Generative World Model**](https://arxiv.org/abs/2403.09631) | ICML 2024 | 2024-03-14 | ![Star](https://img.shields.io/github/stars/UMass-Foundation-Model/3D-VLA?style=social&label=Star) [Github](https://github.com/UMass-Foundation-Model/3D-VLA) |  |
| [**ChainedDiffuser: Unifying Trajectory Diffusion and Keypose Prediction for Robotic Manipulation**](https://openreview.net/forum?id=W0zgY2mBTA8) | CoRL 2023 | 2023-08-31 | ![Star](https://img.shields.io/github/stars/zhouxian/act3d-chained-diffuser?style=social&label=Star) [Github](https://github.com/zhouxian/act3d-chained-diffuser) |  |
| [SGR: **A Universalc Semantic-Geometric Representation for Robotic Manipulation**](https://arxiv.org/abs/2306.10474) | CoRL 2023 | 2023-06-18 | ![Star](https://img.shields.io/github/stars/TongZhangTHU/sgr?style=social&label=Star) [Github](https://github.com/TongZhangTHU/sgr) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Evaluation of Vision Language Action Models
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Evaluating Uncertainty and Quality of Visual Language Action-enabled Robots**](https://arxiv.org/abs/2507.17049) | arXiv | 2025-07-22 | - | |
| [**Is Your Imitation Learning Policy Better than Mine? Policy Comparison with Near-Optimal Stopping**](https://arxiv.org/abs/2503.10966) | arXiv | 2025-03-14 | - |  |
| [**A Taxonomy for Evaluating Generalist Robot Policies**](https://arxiv.org/abs/2503.01238) | arXiv | 2024-03-03 | [Project](https://stargen-taxonomy.github.io/) |  |
| [**Efficient Evaluation of Multi-Task Robot Policies With Active Experiment Selection**](https://arxiv.org/abs/2502.09829) | arXiv | 2025-02-14 | - |  |
| [**VLATest: Testing and Evaluating Vision-Language-Action Models for Robotic Manipulation**](https://arxiv.org/abs/2409.12894) | PACMSE 2025 | 2024-09-19 | ![Star](https://img.shields.io/github/stars/ma-labo/VLATest?style=social&label=Star) [Github](https://github.com/ma-labo/VLATest) |  |
| [**Contrast Sets for Evaluating Language-Guided Robot Policies**](https://arxiv.org/abs/2406.13636) | CoRL 2024 | 2024-06-19 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>


---


### Tactile-based Action Models
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Robot Deisgn_ |
| [**Look-to-Touch: A Vision-Enhanced Proximity and Tactile Sensor for Distance and Geometry Perception in Robotic Manipulation**](https://arxiv.org/abs/2504.10280) | arXiv | 2025-04-14 | - |  |
| [**Touch in the Wild: Learning Fine-Grained Manipulation with a Portable Visuo-Tactile Gripper**](https://arxiv.org/abs/2507.15062) | RSSW 2025 | 2025-07-20 | ![Star](https://img.shields.io/github/stars/YolandaXinyueZhu/touch_in_the_wild?style=social&label=Star) [Github](https://github.com/YolandaXinyueZhu/touch_in_the_wild) |  |
| [**Digitizing Touch with an Artificial Multimodal Fingertip**](https://arxiv.org/abs/2411.02479) | arXiv | 2024-11-04 | ![Star](https://img.shields.io/github/stars/facebookresearch/digit360?style=social&label=Star) [Github](https://github.com/facebookresearch/digit360) | Tactile 
| _Pretrianed Latent Learning_ |
| [**CLTP: Contrastive Language-Tactile Pre-training for 3D Contact Geometry Understanding**](https://arxiv.org/abs/2505.08194) | arXiv | 2025-05-13 | [Project](https://sites.google.com/view/cltp/) |
| [**SimShear: Sim-to-Real Shear-based Tactile Servoing**](https://arxiv.org/abs/2508.20561) | CoRL 2025 | 2025-08-28 | [Project](https://yijionglin.github.io/simshear/) |
| [**Sparsh: Self-supervised Touch Representations for Vision-based Tactile Sensing**](https://arxiv.org/abs/2410.24090) | CoRL 2024 | 2024-10-31 | ![Star](https://img.shields.io/github/stars/facebookresearch/sparsh?style=social&label=Star) [Github](https://github.com/facebookresearch/sparsh) |
| _TA_ |
| [**Feel the Force: Contact-Driven Learning from Humans**](https://arxiv.org/abs/2506.01944) | arXiv | 2025-06-02 | [Project](https://feel-the-force-ftf.github.io/) | TA + Force |
| [**Seq2Seq Imitation Learning for Tactile Feedback-based Manipulation**](https://arxiv.org/abs/2303.02646) | ICRA 2023 | 2023-03-05 | - | |
| _TVA_ |
| [**ViTacFormer: Learning Cross-Modal Representation for Visuo-Tactile Dexterous Manipulation**](https://arxiv.org/abs/2506.15953) | arXiv | 2025-06-19 | - | Touch Prediction |
| [**GelFusion: Enhancing Robotic Manipulation under Visual Constraints via Visuotactile Fusion**](https://arxiv.org/abs/2505.07455) | arXiv | 2025-05-12 | [Project](https://gelfusion.github.io/) |
| [**Reactive Diffusion Policy: Slow-Fast Visual-Tactile Policy Learning for Contact-Rich Manipulation**](https://arxiv.org/abs/2503.02881) | RSS 2025 | 2025-03-04 | ![Star](https://img.shields.io/github/stars/xiaoxiaoxh/reactive_diffusion_policy?style=social&label=Star) [Github](https://github.com/xiaoxiaoxh/reactive_diffusion_policy) | |
| [**On the Importance of Tactile Sensing for Imitation Learning: A Case Study on Robotic Match Lighting**](https://arxiv.org/abs/2504.13618) | ICRAW 2025 | 2025-04-18 | [Project](https://sites.google.com/view/tactile-il) |
| [**VITaL Pretraining: Visuo-Tactile Pretraining for Tactile and Non-Tactile Manipulation Policies**](https://arxiv.org/abs/2403.11898) | ICRA 2025 | 2024-03-18 | ![Star](https://img.shields.io/github/stars/Abraham190137/TactileACT?style=social&label=Star) [Github](https://github.com/Abraham190137/TactileACT) |  |
| [**VTTB: A Visuo-Tactile Learning Approach for Robot-Assisted Bed Bathing**](https://ieeexplore.ieee.org/document/10517379) | RL-A 2024 | 2024-05-01 | [Project](https://sites.google.com/view/vttbathing) |  |
| [**RoboPack: Learning Tactile-Informed Dynamics Models for Dense Packing**](https://arxiv.org/abs/2407.01418) | RSS 2024 | 2024-07-01 | [Project](https://robo-pack.github.io/) | MPC |
| [**Multimodal and Force-Matched Imitation Learning with a See-Through Visuotactile Sensor**](https://arxiv.org/abs/2311.01248) | T-RO 2024 | 2023-11-02 | ![Star](https://img.shields.io/github/stars/SAIC-MONTREAL/tactile-il?style=social&label=Star) [Github](https://github.com/SAIC-MONTREAL/tactile-il) |  |
| [RotateIt: **General In-Hand Object Rotation with Vision and Touch**](https://arxiv.org/abs/2309.09979) | CoRL 2023 | 2023-09-18 | [Project](https://haozhi.io/rotateit/) |
| [T-DEX: **Dexterity from Touch: Self-Supervised Pre-Training of Tactile Representations with Robotic Play**](https://arxiv.org/abs/2303.12076) | CoRL 2023 | 2023-03-21 | ![Star](https://img.shields.io/github/stars/irmakguzey/tactile-dexterity?style=social&label=Star) [Github](https://github.com/irmakguzey/tactile-dexterity) |
| _TLA_ |
| [**TLA: Tactile-Language-Action Model for Contact-Rich Manipulation**](https://arxiv.org/abs/2503.08548) | arXiv | 2025-03-11 | [Project](https://sites.google.com/view/tactile-language-action/) |
| [**Octopi: Object Property Reasoning with Large Tactile-Language Models**](https://arxiv.org/abs/2405.02794) | RSS 2024 | 2024-05-05 | ![Star](https://img.shields.io/github/stars/clear-nus/octopi?style=social&label=Star) [Github](https://github.com/clear-nus/octopi) |
| _TAA_ |
| [**MimicTouch: Leveraging Multi-modal Human Tactile Demonstrations for Contact-rich Manipulation**](https://arxiv.org/abs/2310.16917) | CoRL 2024 | 2023-10-25 | [Project](https://sites.google.com/view/MimicTouch) |
| _TLAA_ |
| [**Beyond Sight: Finetuning Generalist Robot Policies with Heterogeneous Sensors via Language Grounding**](https://arxiv.org/abs/2501.04693) | arXiv | 2025-01-08 | ![Star](https://img.shields.io/github/stars/fuse-model/FuSe?style=social&label=Star) [Github](https://github.com/fuse-model/FuSe) |
| _TVLA_ |
| [**OmniVTLA: Vision-Tactile-Language-Action Model with Semantic-Aligned Tactile Sensing**](https://arxiv.org/abs/2508.08706) | arXiv | 2025-08-23 | - | |
| [**VLA-Touch: Enhancing Vision-Language-Action Models with Dual-Level Tactile Feedback**](https://arxiv.org/abs/2507.17294) | arXiv | 2025-07-23 | ![Star](https://img.shields.io/github/stars/jxbi1010/VLA-Touch?style=social&label=Star) [Github](https://github.com/jxbi1010/VLA-Touch) | |
| [**Tactile-VLA: Unlocking Vision-Language-Action Model's Physical Knowledge for Tactile Generalization**](https://arxiv.org/abs/2507.09160) | arXiv | 2025-07-12 | - | |
| [**Robotic Perception with a Large Tactile-Vision-Language Model for Physical Property Inference**](https://arxiv.org/abs/2506.19303) | arXiv | 2025-06-24 | - |
| [**VTLA: Vision-Tactile-Language-Action Model with Preference Learning for Insertion Manipulation**](https://arxiv.org/abs/2505.09577) | arXiv | 2025-05-14 | [Project](https://sites.google.com/view/vtla) | |
| _Multimodal_ |
| [**Tactile Beyond Pixels: Multisensory Touch Representations for Robot Manipulation**](https://arxiv.org/abs/2506.14754) | arXiv | 20256-06-17 | - |
| _Hierarchical Policy_ |
| [**Touch Begins Where Vision Ends: Generalizable Policies for Contact-rich Manipulation**](https://arxiv.org/abs/2506.13762) | arXiv | 2025-06-16 | ![Star](https://img.shields.io/github/stars/anonvital/anonvital?style=social&label=Star) [Github](https://github.com/anonvital/anonvital) |
| [**Feeling the Force: Integrating Force and Pose for Fluent Discovery through Imitation Learning to Open Medicine Bottles**](https://ieeexplore.ieee.org/document/8206196) | IROS 2017 | 2017-12-14 | - |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

---

<!-- ******* 1.3.10 - Other Modalities ******* -->
### Other Modalities
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Joint_ |
| [**Redundancy-aware Action Spaces for Robot Learning**](https://arxiv.org/abs/2406.04144) | arXiv | 2024-06-06 | ![Star](https://img.shields.io/github/stars/mazpie/redundancy-action-spaces?style=social&label=Star) [Github](https://github.com/mazpie/redundancy-action-spaces) | |
| _Force_ |
| [**ForceVLA: Enhancing VLA Models with a Force-aware MoE for Contact-rich Manipulation**](https://arxiv.org/abs/2505.22159) | arXiv | 2025-05-28 | [Project](https://sites.google.com/view/forcevla2025) | |
| [**FoAR: Force-Aware Reactive Policy for Contact-Rich Robotic Manipulation**](https://arxiv.org/abs/2411.15753) | RA-L 2025 | 2024-11-24 | ![Star](https://img.shields.io/github/stars/Alan-Heoooh/FoAR?style=social&label=Star) [Github](https://github.com/Alan-Heoooh/FoAR) |
| [**Immersive Demonstrations are the Key to Imitation Learning**](https://arxiv.org/abs/2301.09157) | ICRA 2023 | 2023-01-22 | - |
| [**Robotic Imitation of Human Assembly Skills Using Hybrid Trajectory and Force Learning**](https://arxiv.org/abs/2103.05912) | ICRA 2021 | 2021-03-10 | - |
| [**Imitation Learning for Object Manipulation Based on Position/Force Information Using Bilateral Control**](https://arxiv.org/abs/1811.03759) | IROS 2018 | 2018-11-09 | - |
| [**Imitation Learning of Positional and Force Skills Demonstrated via Kinesthetic Teaching and Haptic Input**](https://arxiv.org/abs/1811.03759) | Advanced Robotics 2011 | 2012-04-02 | - |
| _Audio_ |
| [**VLAS: Vision-Language-Action Model with Speech Instructions for Customized Robot Manipulation**](https://arxiv.org/abs/2502.13508) | ICLR 2025 | 2025-01-25 | ![Star](https://img.shields.io/github/stars/whichwhichgone/VLAS?style=social&label=Star) [Github](https://github.com/whichwhichgone/VLAS) |  |
| [MS-Bot: **Play to the Score: Stage-Guided Dynamic Multi-Sensory Fusion for Robotic Manipulation**](https://arxiv.org/abs/2408.01366) | CoRL 2024 | 2024-08-02 | ![Star](https://img.shields.io/github/stars/GeWu-Lab/MS-Bot?style=social&label=Star) [Github](https://github.com/GeWu-Lab/MS-Bot) | IL, RepL, Multimodal, Poliy Head |
| [**ManiWAV: Learning Robot Manipulation from In-the-Wild Audio-Visual Data**](https://arxiv.org/abs/2406.19464) | CoRL 2024 | 2024-06-27 | ![Star](https://img.shields.io/github/stars/real-stanford/maniwav?style=social&label=Star) [Github](https://github.com/real-stanford/maniwav) |  |
| [**MUTEX: Learning Unified Policies from Multimodal Task Specifications**](https://arxiv.org/abs/2309.14320) | CoRL 2023 | 2023-09-25 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/mutex?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/mutex) | IL, RepL, Multimodal, E-D, Masked Construction, TP |
| [**See, Hear, and Feel: Smart Sensory Fusion for Robotic Manipulation**](https://arxiv.org/abs/2212.03858) | CoRL 2022 | 2022-12-07 | ![Star](https://img.shields.io/github/stars/JunzheJosephZhu/see_hear_feel?style=social&label=Star) [Github](https://github.com/JunzheJosephZhu/see_hear_feel) | V+T+A |
| [**Play it by Ear: Learning Skills amidst Occlusion through Audio-Visual Imitation Learning**](https://arxiv.org/abs/2205.14850) | RSS 2022 | 2022-05-30 | ![Star](https://img.shields.io/github/stars/MaxDu17/PlayItByEar_Code?style=social&label=Star) [Github](https://github.com/MaxDu17/PlayItByEar_Code) |  |
| _EEG_ |
| [**Improving Continuous Grasp Force Decoding from EEG with Time-Frequency Regressors and Premotor-Parietal Network Integration**](https://arxiv.org/abs/2508.07677) | TSMC 2025 | 2025-08-11 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>


## Latent Learning

### Pretrained Latent Learning
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Token Bottleneck: One Token to Remember Dynamics**](https://arxiv.org/abs/2507.06543) | arXiv | 2025-07-09 | ![Star](https://img.shields.io/github/stars/naver-ai/tobo?style=social&label=Star) [Github](https://github.com/naver-ai/tobo) | |
| [**PCHands: PCA-based Hand Pose Synergy Representation on Manipulators with N-DoF**](https://arxiv.org/abs/2508.07945) | Humanoids 2025 | 2025-08-11 | [Project](https://hsp-iit.github.io/PCHands/) |  |
| [**EmbodiedMAE: A Unified 3D Multi-Modal Representation for Robot Manipulation**](https://arxiv.org/abs/2505.10105) | arXiv | 2025-05-15 | - |  |
| [**Maximizing Alignment with Minimal Feedback: Efficiently Learning Rewards for Visuomotor Robot Policy Alignment**](https://arxiv.org/abs/2412.04835) | arXiv | 2024-12-06 | [Project](https://sites.google.com/berkeley.edu/rapl) |  |
| [**Adaptive Wiping: Adaptive Contact-rich Manipulation through Few-shot Imitation Learning with Force-Torque Feedback and Pre-trained Object Representations**](https://arxiv.org/abs/2505.06451) | RA-L 2024 | 2024-11-13 | [Project](https://sites.google.com/view/adaptive-wiping) |  |
| [MCR: **Robots Pre-train Robots: Manipulation-Centric Robotic Representation from Large-Scale Robot Datasets**](https://arxiv.org/abs/2410.22325) | ICLR 2025 | 2024-10-29 | ![Star](https://img.shields.io/github/stars/luccachiang/robots-pretrain-robots?style=social&label=Star) [Github](https://github.com/luccachiang/robots-pretrain-robots) | IL, RepL, Alignment, Poliy Head |
| [**RoboUniView: Visual-Language Model with Unified View Representation for Robotic Manipulation**](https://arxiv.org/abs/2406.18977) | arXiv | 2024-06-27 | ![Star](https://img.shields.io/github/stars/liufanfanlff/RoboUniviewa?style=social&label=Star) [Github](https://github.com/liufanfanlff/RoboUniviewa) |  |
| [OBSBench: **Point Cloud Matters: Rethinking the Impact of Different Observation Spaces on Robot Learning**](https://arxiv.org/abs/2402.02500) | NeuIPS 2024 | 2024-02-04 | ![Star](https://img.shields.io/github/stars/HaoyiZhu/PointCloudMatters?style=social&label=Star) [Github](https://github.com/HaoyiZhu/PointCloudMatters) |
| [**Theia: Distilling Diverse Vision Foundation Models for Robot Learning**](https://arxiv.org/abs/2407.20179) | CoRL 2024 | 2024-07-29 | ![Star](https://img.shields.io/github/stars/bdaiinstitute/theia?style=social&label=Star) [Github](https://github.com/bdaiinstitute/theia) | IL, RepL, KD in VLMs, Poliy Head |
| [**Ag2Manip: Learning Novel Manipulation Skills with Agent-Agnostic Visual and Action Representations**](https://arxiv.org/abs/2404.17521) | IROS 2024 | 2024-04-26 | ![Star](https://img.shields.io/github/stars/Xiaoyao-Li/Ag2Manip?style=social&label=Star) [Github](https://github.com/Xiaoyao-Li/Ag2Manip) | IL, RepL, KD in VLMs, Poliy Head |
| [MPI: **Learning Manipulation by Predicting Interaction**](https://www.arxiv.org/abs/2406.00439) | RSS 2024 | 2024-06-01 | ![Star](https://img.shields.io/github/stars/OpenDriveLab/MPI?style=social&label=Star) [Github](https://github.com/OpenDriveLab/MPI) | IL, RepL, Interaction-oriented Prediction, Both Goals, Poliy Head |
| [**Human-oriented Representation Learning for Robotic Manipulation**](https://arxiv.org/abs/2310.03023) | RSS 2024 | 2023-10-04 | [Project](https://sites.google.com/view/human-oriented-robot-learning) |  |
| [**Generalizable Imitation Learning Through Pre-Trained Representations**](https://arxiv.org/abs/2311.09350) | arXiv | 2023-11-15 | - | |
| [VC-1: **Where are we in the search for an Artificial Visual Cortex for Embodied Intelligence?**](https://arxiv.org/abs/2303.18240) | NeurIPS 2023 | 2023-03-31 | ![Star](https://img.shields.io/github/stars/facebookresearch/eai-vc?style=social&label=Star)  [Github](https://github.com/facebookresearch/eai-vc) | |
| [**Exploring Visual Pre-training for Robot Manipulation: Datasets, Models and Methods**](https://arxiv.org/abs/2308.03620) | IROS 2023 | 2023-08-07 | [Project](https://explore-pretrain-robot.github.io/) |  |
| [Voltron: **Language-Driven Representation Learning for Robotics**](https://arxiv.org/abs/2302.12766) | RSS 2023 | 2023-02-24 | ![Star](https://img.shields.io/github/stars/siddk/voltron-robotics?style=social&label=Star) [Github](https://github.com/siddk/voltron-robotics) | IL, RepL, Masked Construction, Both Goals, Poliy Head |
| [MVP: **Real-World Robot Learning with Masked Visual Pre-training**](https://arxiv.org/abs/2210.03109) | CoRL 2023 | 2022-10-06 | ![Star](https://img.shields.io/github/stars/ir413/mvp?style=social&label=Star) [Github](https://github.com/ir413/mvp) | IL, RepL, Masked Construction, Image Goal, Poliy Head |
| [**R3M: A Universal Visual Representation for Robot Manipulation**](https://arxiv.org/abs/2203.12601) | CoRL 2022 | 2022-03-23 | ![Star](https://img.shields.io/github/stars/facebookresearch/r3m?style=social&label=Star) [Github](https://github.com/facebookresearch/r3m) | IL, RepL, LfD, Alignment, Language Goal, Poliy Head |
| [MIR: **Manipulator-Independent Representations for Visual Imitation**](https://arxiv.org/abs/2103.09016) | RSS 2021 | 2021-03-16 | [Project](https://sites.google.com/view/mir4vi/qualitative-videos) |  |
| [AT-Net: **Attentive Task-Net: Self Supervised Task-Attention Network for Imitation Learning using Video Demonstration**](https://ieeexplore.ieee.org/document/9197544) | ICRA 2020 | 2020-09-15 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

<!-- ******* 1.3.4 - Latent Action Learning ******* -->
### Latent Action Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Latent Action Diffusion for Cross-Embodiment Manipulation**](https://arxiv.org/abs/2506.14608) | arXiv | 2025-06-17 | [Project](https://mimicrobotics.github.io/lad/) | |
| [**CoMo: Learning Continuous Latent Motion from Internet Videos for Scalable Robot Learning**](https://arxiv.org/abs/2505.17006) | arXiv | 2025-05-22 | ![Star](https://img.shields.io/github/stars/clamrobot/clam?style=social&label=Star) [Github](https://github.com/clamrobot/clam) | |
| [**FLARE: Robot Learning with Implicit World Modeling**](https://arxiv.org/abs/2505.15659) | arXiv | 2025-05-21 | [Project](https://research.nvidia.com/labs/gear/flare) | |
| [**DreamGen: Unlocking Generalization in Robot Learning through Neural Trajectories**](https://arxiv.org/abs/2505.12705) | arXiv | 2025-05-19 | [Project](https://research.nvidia.com/labs/gear/dreamgen/) | |
| [**CLAM: Continuous Latent Action Models for Robot Learning from Unlabeled Demonstrations**](https://arxiv.org/abs/2505.04999) | arXiv | 2025-05-08 | ![Star](https://img.shields.io/github/stars/clamrobot/clam?style=social&label=Star) [Github](https://github.com/clamrobot/clam) | |
| [**STAR: Learning Diverse Robot Skill Abstractions through Rotation-Augmented Vector Quantization**](https://arxiv.org/abs/2506.03863) | ICML 2025 | 2025-06-04 | ![Star](https://img.shields.io/github/stars/JiuTian-VL/STAR?style=social&label=Star) [Github](https://github.com/JiuTian-VL/STAR) | |
| [**Moto: Latent Motion Token as the Bridging Language for Robot Manipulation**](https://arxiv.org/abs/2412.04445) | arXiv | 2024-12-05 | ![Star](https://img.shields.io/github/stars/TencentARC/Moto?style=social&label=Star) [Github](https://github.com/TencentARC/Moto) | |
| [**IGOR: Image-GOal Representations Atomic Control Units for Foundation Models in Embodied AI**](https://arxiv.org/abs/2411.00785) | arXiv | 2024-11-17 | [Project](https://www.microsoft.com/en-us/research/project/igor-image-goal-representations/) |  |
| [KOAP: **Imitation Learning with Limited Actions via Diffusion Planners and Deep Koopman Controllers**](https://arxiv.org/abs/2410.07584) | arXiv | 2024-10-24 | - | IL, RepL, Image Prediction, Koopman Operator |
| [LAPA: **Latent Action Pretraining from Videos**](https://arxiv.org/abs/2410.11758) | ICLR 2025 | 2024-10-15 | ![Star](https://img.shields.io/github/stars/LatentActionPretraining/LAPA?style=social&label=Star) [Github](https://github.com/LatentActionPretraining/LAPA) |  |
| [**Discrete Policy: Learning Disentangled Action Space for Multi-Task Robotic Manipulation**](https://arxiv.org/abs/2409.18707) | ICRA 2025 | 2024-09-27 | [Project](https://discretepolicy.github.io/) | |
| [**KOROL: Learning Visualizable Object Feature with Koopman Operator Rollout for Manipulation**](https://arxiv.org/abs/2407.00548) | CoRL 2024 | 2024-07-10 | ![Star](https://img.shields.io/github/stars/hychen-naza/KOROL?style=social&label=Star) [Github](https://github.com/hychen-naza/KOROL) |  |
| [**Rethinking Mutual Information for Language Conditioned Skill Discovery on Imitation Learning**](https://arxiv.org/abs/2402.17511) | AAAI 2024 | 2024-02-27 | - | |
| [**Behavior Generation with Latent Actions**](https://arxiv.org/abs/2403.03181) | ICML 2024 | 2024-03-05 | ![Star](https://img.shields.io/github/stars/jayLEE0301/vq_bet_official?style=social&label=Star) [Github](https://github.com/jayLEE0301/vq_bet_official) |  |
| [LAPO: **Learning to Act without Actions**](https://arxiv.org/abs/2312.10812) | ICLR 2024 | 2023-12-17 | ![Star](https://img.shields.io/github/stars/schmidtdominik/LAPO?style=social&label=Star) [Github](https://github.com/schmidtdominik/LAPO) | IL, RepL, Image Prediction, Latent Inverse Dynamics Model |
| [GRIF: **Goal Representations for Instruction Following: A Semi-Supervised Language Interface to Control**](https://arxiv.org/abs/2307.00117) | CoRL 2023 | 2023-06-30 | ![Star](https://img.shields.io/github/stars/rail-berkeley/grif_release?style=social&label=Star)  [Github](https://github.com/rail-berkeley/grif_release) | Partially labeled data |
| [**On the Utility of Koopman Operator Theory in Learning Dexterous Manipulation Skills**](https://arxiv.org/abs/2303.13446) | CoRL 2023 | 2023-03-23 | ![Star](https://img.shields.io/github/stars/GT-STAR-Lab/KODex?style=social&label=Star) [Github](https://github.com/GT-STAR-Lab/KODex) | |
| [**MimicPlay: Long-Horizon Imitation Learning by Watching Human Play**](https://arxiv.org/abs/2302.12422) | CoRL 2023 | 2023-02-24 | ![Star](https://img.shields.io/github/stars/j96w/MimicPlay?style=social&label=Star) [Github](https://github.com/j96w/MimicPlay) | IL, RepL, LfD, Image Goal, Poliy Head |
| [**Chain of Thought Imitation with Procedure Cloning**](https://arxiv.org/abs/2205.10816) | NeurIPS 2022 | 2022-05-22 | ![Star](https://img.shields.io/github/stars/google-research/google-research?style=social&label=Star) [Github](https://github.com/google-research/google-research/tree/master/procedure_cloning) |  |
| [ILPO: **Imitating Latent Policies from Observation**](https://arxiv.org/abs/1805.07914) | ICML 2019 | 2018-05-21 | ![Star](https://img.shields.io/github/stars/ashedwards/ILPO?style=social&label=Star) [Github](https://github.com/ashedwards/ILPO) | IL, RepL, Latent Inverse Dynamics Model |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>



## Policy Learning

### Transformer-based Policies
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Autoregressive-based Policy_ |
| [**Bridging Perception and Action: Spatially-Grounded Mid-Level Representations for Robot Generalization**](https://arxiv.org/abs/2506.06196) | arXiv | 2025-06-06 | [Project](https://mid-level-moe.github.io/) | |
| [**Dense Policy: Bidirectional Autoregressive Learning of Actions**](https://arxiv.org/abs/2503.13217) | ICCV 2025 | 2025-03-17 | ![Star](https://img.shields.io/github/stars/Selen-Suyue/DensePolicy?style=social&label=Star) [Github](https://github.com/Selen-Suyue/DensePolicy) | |
| [**CARP: Visuomotor Policy Learning via Coarse-to-Fine Autoregressive Prediction**](https://arxiv.org/abs/2412.06782) | ICCV 2025 | 2024-12-09 | ![Star](https://img.shields.io/github/stars/ZhefeiGong/carp?style=social&label=Star) [Github](https://github.com/ZhefeiGong/carp) | |
| [**Autoregressive Action Sequence Learning for Robotic Manipulation**](https://arxiv.org/abs/2410.03132) | RA-L 2025 | 2024-10-04 | ![Star](https://img.shields.io/github/stars/mlzxy/arp?style=social&label=Star) [Github](https://github.com/mlzxy/arp) | |
| [**Transformer Adapters for Robot Learning**](https://openreview.net/forum?id=H--wvRYBmF) | CoRLW 2022 | 2022-11-17 | - | |
| _ACT-based Policy_ | 
| [**Improving Generalization Ability of Robotic Imitation Learning by Resolving Causal Confusion in Observations**](https://arxiv.org/abs/2507.22380) | arXiv | 2025-07-30 | - | |
| [**Reinforcement Learning with Action Chunking**](https://arxiv.org/abs/2507.07969) | arXiv | 2025-07-10 | ![Star](https://img.shields.io/github/stars/ColinQiyangLi/qc?style=social&label=Star) [Github](https://github.com/ColinQiyangLi/qc) | |
| [**Chain-of-Action: Trajectory Autoregressive Modeling for Robotic Manipulation**](https://arxiv.org/abs/2506.09990) | arXiv | 2025-06-11 | ![Star](https://img.shields.io/github/stars/zwbx/Chain-of-Action?style=social&label=Star) [Github](https://github.com/zwbx/Chain-of-Action) | |
| [**Bi-LAT: Bilateral Control-Based Imitation Learning via Natural Language and Action Chunking with Transformers**](https://arxiv.org/abs/2504.01301) | arXiv | 2025-04-02 | [Project](https://mertcookimg.github.io/bi-lat/) |  |
| [**Haptic-ACT: Bridging Human Intuition with Compliant Robotic Manipulation via Immersive VR**](https://arxiv.org/abs/2409.11925) | arXiv | 2024-09-18 | [Project](https://sites.google.com/view/hapticact) | |
| [**BAKU: An Efficient Transformer for Multi-Task Policy Learning**](https://arxiv.org/abs/2406.07539) | NeurIPS 2024 | 2024-06-11 | ![Star](https://img.shields.io/github/stars/siddhanthaldar/BAKU?style=social&label=Star) [Github](https://github.com/siddhanthaldar/BAKU) |  |
| [**ALOHA Unleashed: A Simple Recipe for Robot Dexterity**](https://arxiv.org/abs/2410.13126) | CoRL 2024 | 2024-10-17 | [Project](https://aloha-unleashed.github.io/) |
| [**InterACT: Inter-dependency Aware Action Chunking with Hierarchical Attention Transformers for Bimanual Manipulation**](https://arxiv.org/abs/2409.07914) | CoRL 2024 | 2024-09-12 | ![Star](https://img.shields.io/github/stars/soltanilara/InterACT-LeRobot?style=social&label=Star) [Github](https://github.com/soltanilara/InterACT-LeRobot) | |
| [**Bi-ACT: Bilateral Control-Based Imitation Learning via Action Chunking with Transformer**](https://arxiv.org/abs/2401.17698) | AIM 2024 | 2024-01-31 | [Project](https://mertcookimg.github.io/bi-act/) | |
| [**RoboAgent: Generalization and Efficiency in Robot Manipulation via Semantic Augmentations and Action Chunking**](https://arxiv.org/abs/2309.01918) | ICRA 2024 | 2023-09-05 | ![Star](https://img.shields.io/github/stars/robopen/roboagent?style=social&label=Star) [Github](https://github.com/robopen/roboagent) | |
| [ACT: **Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware**](https://arxiv.org/abs/2304.13705) | RSS 2023 | 2023-04-23 | ![Star](https://img.shields.io/github/stars/tonyzhaozh/aloha?style=social&label=Star) [Github](https://github.com/tonyzhaozh/aloha) |  |
| Show only a subset |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Diffusion Policy
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _2D_ |
| [**Self-Guided Action Diffusion**](https://arxiv.org/abs/2508.12189) | arXiv | 2025-08-17 | ![Star](https://img.shields.io/github/stars/rhea-mal/guided_bid?style=social&label=Star) [Github](https://github.com/rhea-mal/guided_bid) | |
| [**KDPE: A Kernel Density Estimation Strategy for Diffusion Policy Trajectory Selection**](https://arxiv.org/abs/2508.10511) | CoRL 2025 | 2025-08-14 | ![Star](https://img.shields.io/github/stars/kdpe-robotics/kdpe?style=social&label=Star) [Github](https://github.com/kdpe-robotics/kdpe) | |
| [**Real-time Iteration Scheme for Diffusion Policy**](https://www.arxiv.org/abs/2508.05396) | IROS 2025 | 2025-08-07 | ![Star](https://img.shields.io/github/stars/RTI-DP/rti-dp?style=social&label=Star) [Github](https://github.com/RTI-DP/rti-dp) | |
| [**Hybrid Diffusion Policies with Projective Geometric Algebra for Efficient Robot Manipulation Learning**](https://arxiv.org/abs/2507.05695) | arXiv | 2025-06-24 | - | |
| [**Latent Theory of Mind: A Decentralized Diffusion Architecture for Cooperative Manipulation**](https://arxiv.org/abs/2505.09144) | arXiv | 2025-05-14 | [Project](https://stanfordmsl.github.io/LatentToM/) | |
| [**Demystifying Diffusion Policies: Action Memorization and Simple Lookup Table Alternatives**](https://arxiv.org/abs/2505.05787) | arXiv | 2025-05-09 |  [Project](https://stanfordmsl.github.io/alt/) | |
| [**Latent Diffusion Planning for Imitation Learning**](https://arxiv.org/abs/2504.16925) | arXiv | 2025-04-23 | ![Star](https://img.shields.io/github/stars/amberxie88/latent_diffusion_planning?style=social&label=Star) [Github](https://github.com/amberxie88/latent_diffusion_planning) | |
| [**HybridVLA: Collaborative Diffusion and Autoregression in a Unified Vision-Language-Action Model**](https://arxiv.org/abs/2503.10631) | arXiv | 2025-03-13 | ![Star](https://img.shields.io/github/stars/PKU-HMI-Lab/Hybrid-VLA?style=social&label=Star) [Github](https://github.com/PKU-HMI-Lab/Hybrid-VLA) | Autoregressive and Diffusion |
| [**FRMD: Fast Robot Motion Diffusion with Consistency-Distilled Movement Primitives for Smooth Action Generation**](https://arxiv.org/abs/2503.02048) | arXiv | 2025-03-03 | - | |
| [**On-Device Diffusion Transformer Policy for Efficient Robot Manipulation**](https://arxiv.org/abs/2508.00697) | ICCV 2025 | 2025-08-01 | - |  |
| [**Dita: Scaling Diffusion Transformer for Generalist Vision-Language-Action Policy**](https://arxiv.org/abs/2503.19757) | ICCV 2025 | 2025-03-25 | ![Star](https://img.shields.io/github/stars/RoboDita/Dita?style=social&label=Star) [Github](https://github.com/RoboDita/Dita) |  |
| [**S<sup>2</sup>-Diffusion: Generalizing from Instance-level to Category-level Skills in Robot Manipulation**](https://arxiv.org/abs/2502.09389) | arXiv | 2025-02-13 | - | |
| [**DisDP: Robust Imitation Learning via Disentangled Diffusion Policies**](https://openreview.net/forum?id=0GSL9VRBib) | RLC 2025 | 2025-05-10 | - |
| [**Reactive Diffusion Policy: Slow-Fast Visual-Tactile Policy Learning for Contact-Rich Manipulation**](https://arxiv.org/abs/2503.02881) | RSS 2025 | 2025-03-04 | ![Star](https://img.shields.io/github/stars/xiaoxiaoxh/reactive_diffusion_policy?style=social&label=Star) [Github](https://github.com/xiaoxiaoxh/reactive_diffusion_policy) | |
| [**Spatial-Temporal Graph Diffusion Policy with Kinematic Modeling for Bimanual Robotic Manipulation**](https://arxiv.org/abs/2503.10743) | CVPR 2025 | 2025-03-13 | - | |
| [MoDE: **Efficient Diffusion Transformer Policies with Mixture of Expert Denoisers for Multitask Learning**](https://arxiv.org/abs/2412.12953) | ICLR 2025 | 2024-12-17 | ![Star](https://img.shields.io/github/stars/intuitive-robots/MoDE_Diffusion_Policy?style=social&label=Star) [Github](https://github.com/intuitive-robots/MoDE_Diffusion_Policy) | |
| [**AffordDP: Generalizable Diffusion Policy with Transferable Affordance**](https://arxiv.org/abs/2412.03142) | arXiv | 2024-12-04 | [Project](https://afforddp.github.io/) | |
| [**SPOT: SE(3) Pose Trajectory Diffusion for Object-Centric Manipulation**](https://arxiv.org/abs/2411.00965) | arXiv | 2024-11-01 | ![Star](https://img.shields.io/github/stars/NVlabs/object_centric_diffusion?style=social&label=Star) [Github](https://github.com/NVlabs/object_centric_diffusion) | |
| [**CAGE: Causal Attention Enables Data-Efficient Generalizable Robotic Manipulation**](https://arxiv.org/abs/2410.14974) | ICRA 2025 | 2024-10-19 | ![Star](https://img.shields.io/github/stars/cage-policy/CAGE?style=social&label=Star) [Github](https://github.com/cage-policy/CAGE) | |
| [**RDT-1B: a Diffusion Foundation Model for Bimanual Manipulation**](https://arxiv.org/abs/2410.07864) | ICLR 2025 | 2024-10-10 | ![Star](https://img.shields.io/github/stars/thu-ml/RoboticsDiffusionTransformer?style=social&label=Star) [Github](https://github.com/thu-ml/RoboticsDiffusionTransformer) | |
| [ScaleDP: **Scaling Diffusion Policy in Transformer to 1 Billion Parameters for Robotic Manipulation**](https://arxiv.org/abs/2409.14411) | ICRA 2025 | 2024-09-22 | [Project](https://scaling-diffusion-policy.github.io/) | |
| [DiT-Block Policy: **The Ingredients for Robotic Diffusion Transformers**](https://arxiv.org/abs/2410.10088) | arXiv | 2024-10-14 | ![Star](https://img.shields.io/github/stars/sudeepdasari/dit-policy?style=social&label=Star) [Github](https://github.com/sudeepdasari/dit-policy) | |
| [EquiDiff: **Equivariant Diffusion Policy**](https://arxiv.org/abs/2407.01812) | CoRL 2024 | 2024-07-01 | ![Star](https://img.shields.io/github/stars/pointW/equidiff?style=social&label=Star) [Code](https://github.com/pointW/equidiff) | Equivariance |
| [SDP: **Sparse Diffusion Policy: A Sparse, Reusable, and Flexible Policy for Robot Learning**](https://arxiv.org/abs/2407.01531) | CoRL 2024 | 2024-07-01 | ![Star](https://img.shields.io/github/stars/AnthonyHuo/SDP?style=social&label=Star) [Github](https://github.com/AnthonyHuo/SDP) | MoE |
| [**APEX: Ambidextrous Dual-Arm Robotic Manipulation Using Collision-Free Generative Diffusion Models**](https://arxiv.org/abs/2404.02284) | IROS 2024 | 2024-04-02 | [Project](https://sites.google.com/view/apex-dual-arm/home) |
| [HDP: **Hierarchical Diffusion Policy for Kinematics-Aware Multi-Task Robotic Manipulation**](https://arxiv.org/abs/2403.03890) | CVPR 2024 | 2024-03-06 | ![Star](https://img.shields.io/github/stars/dyson-ai/hdp?style=social&label=Star) [Github](https://github.com/dyson-ai/hdp) | |
| [**Subgoal Diffuser: Coarse-to-fine Subgoal Generation to Guide Model Predictive Control for Robot Manipulation**](https://arxiv.org/abs/2403.13085) | ICRA 2024 | 2024-03-19 | [Project](https://sites.google.com/view/subgoal-diffuser-mpc) |  |
| [**C3DM: Constrained-Context Conditional Diffusion Models for Imitation Learning**](https://arxiv.org/abs/2311.01419) | TMLR 2024 | 2023-11-02 | [Project](https://sites.google.com/view/c3dm-imitation-learning) |  |
| [**PlayFusion: Skill Acquisition via Diffusion from Language-Annotated Play**](https://arxiv.org/abs/2312.04549) | CoRL 2023 | 2023-12-07 | [Project](https://play-fusion.github.io/) |  |
| [BESO: **Goal-Conditioned Imitation Learning using Score-based Diffusion Policies**](https://arxiv.org/abs/2304.02532) | RSS 2023 | 2023-04-05 | ![Star](https://img.shields.io/github/stars/intuitive-robots/beso?style=social&label=Star) [Github](https://github.com/intuitive-robots/beso) |  |
| [**Diffusion Policy: Visuomotor Policy Learning via Action Diffusion**](https://arxiv.org/abs/2303.04137) | RSS 2023 | 2023-03-07 | ![Star](https://img.shields.io/github/stars/real-stanford/diffusion_policy?style=social&label=Star) [Github](https://github.com/real-stanford/diffusion_policy) |  |
| _3D_ |
| [**OmniD: Generalizable Robot Manipulation Policy via Image-Based BEV Representation**](https://arxiv.org/abs/2508.11898) | arXiv | 2025-08-16 | ![Star](https://img.shields.io/github/stars/1mather/omnid?style=social&label=Star) [Github](https://github.com/1mather/omnid) |  |
| [**Spatial-Temporal Aware Visuomotor Diffusion Policy Learning**](https://arxiv.org/abs/2507.06710) | arXiv | 2025-07-09 | [Project](https://zhenyangliu.github.io/DP4/) | |
| [**PRISM: Pointcloud Reintegrated Inference via Segmentation and Cross-attention for Manipulation**](https://arxiv.org/abs/2507.04633) | arXiv | 2025-07-07 | ![Star](https://img.shields.io/github/stars/czknuaa/PRISM?style=social&label=Star) [Github](https://github.com/czknuaa/PRISM) |  |
| [**Block-wise Adaptive Caching for Accelerating Diffusion Policy**](https://arxiv.org/abs/2506.13456) | arXiv | 2025-06-24 | - | |
| [**Canonical Policy: Learning Canonical 3D Representation for Equivariant Policy**](https://arxiv.org/abs/2505.18474) | arXiv | 2025-05-24 | [Project](https://zhangzhiyuanzhang.github.io/cp-website/) | |
| [**3D Equivariant Visuomotor Policy Learning via Spherical Projection**](https://arxiv.org/abs/2505.16969) | arXiv | 2025-05-22 | - | |
| [**H<sup>3</sup>DP: Triply-Hierarchical Diffusion Policy for Visuomotor Learning**](https://arxiv.org/abs/2505.07819) | arXiv | 2025-05-12 | [Project](https://lyy-iiis.github.io/h3dp/) | |
| [**Towards Fusing Point Cloud and Visual Representations for Imitation Learning**](https://arxiv.org/abs/2502.12320) | arXiv | 2025-02-17 | ![Star](https://img.shields.io/github/stars/ALRhub/FPVNet?style=social&label=Star) [Github](https://github.com/ALRhub/FPVNet) |  |
| [**CodeDiffuser: Attention-Enhanced Diffusion Policy via VLM-Generated Code for Instruction Ambiguity**](https://arxiv.org/abs/2506.16652) | RSS 2025 | 2025-06-19 | ![Star](https://img.shields.io/github/stars/lyttttt3333/CodeDiffuser?style=social&label=Star) [Github](https://github.com/lyttttt3333/CodeDiffuser) | |
| [PPI: **Gripper Keypose and Object Pointflow as Interfaces for Bimanual Robotic Manipulation**](https://arxiv.org/abs/2504.17784) | RSS 2025 | 2025-04-24 | ![Star](https://img.shields.io/github/stars/OpenRobotLab/PPI?style=social&label=Star) [Github](https://github.com/OpenRobotLab/PPI) |  |
| [**Score and Distribution Matching Policy: Advanced Accelerated Visuomotor Policies via Matched Distillation**](https://arxiv.org/abs/2412.09265) | arXiv | 2024-12-12 | ![Star](https://img.shields.io/github/stars/BofangJia/SDM-Policy?style=social&label=Star) [Github](https://github.com/BofangJia/SDM-Policy) | |
| [**AnchorDP3: 3D Affordance Guided Sparse Diffusion Policy for Robotic Manipulation**](https://arxiv.org/abs/2506.19269) | CVPRW 2025 | 2025-06-24 | - | |
| [MBA: **Motion Before Action: Diffusing Object Motion as Manipulation Condition**](https://arxiv.org/abs/2411.09658) | RA-L 2025 | 2024-11-14 | ![Star](https://img.shields.io/github/stars/Selen-Suyue/MBA?style=social&label=Star) [Github](https://github.com/Selen-Suyue/MBA) | |
| [**GravMAD: Grounded Spatial Value Maps Guided Action Diffusion for Generalized 3D Manipulation**](https://arxiv.org/abs/2409.20154) | ICLR 2025 | 2024-09-30 | [Project](https://gravmad.github.io/) |  |
| [**ManiCM: Real-time 3D Diffusion Policy via Consistency Model for Robotic Manipulation**](https://arxiv.org/abs/2406.01586) | arXiv | 2024-06-03 | ![Star](https://img.shields.io/github/stars/ManiCM-fast/ManiCM?style=social&label=Star) [Github](https://github.com/ManiCM-fast/ManiCM) |  |
| [**GenDP: 3D Semantic Fields for Category-Level Generalizable Diffusion Policy**](https://arxiv.org/abs/2410.17488) | CoRL 2024 | 2024-10-23 | ![Star](https://img.shields.io/github/stars/WangYixuan12/gendp?style=social&label=Star) [Github](https://github.com/WangYixuan12/gendp) |  |
| [**EquiBot: SIM(3)-Equivariant Diffusion Policy for Generalizable and Data Efficient Learning**](https://arxiv.org/abs/2407.01479) | CoRL 2024 | 2024-07-01 | ![Star](https://img.shields.io/github/stars/yjy0625/equibot?style=social&label=Star) [Github](https://github.com/yjy0625/equibot) |  |
| [**RISE: 3D Perception Makes Real-World Robot Imitation Simple and Effective**](https://arxiv.org/abs/2404.12281) | IROS 2024 | 2024-04-18 | ![Star](https://img.shields.io/github/stars/rise-policy/rise?style=social&label=Star) [Github](https://github.com/rise-policy/rise) | |
| [**3D Diffuser Actor: Policy Diffusion with 3D Scene Representations**](https://arxiv.org/abs/2402.10885) | CoRL 2024 | 2024-02-16 | ![Star](https://img.shields.io/github/stars/nickgkan/3d_diffuser_actor?style=social&label=Star) [Github](https://github.com/nickgkan/3d_diffuser_actor) |  |
| [DP3: **3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations**](https://arxiv.org/abs/2403.03954) | RSS 2024 | 2024-03-06 | ![Star](https://img.shields.io/github/stars/YanjieZe/3D-Diffusion-Policy?style=social&label=Star) [Github](https://github.com/YanjieZe/3D-Diffusion-Policy) |  |
| [**StructDiffusion: Language-Guided Creation of Physically-Valid Structures using Unseen Objects**](https://arxiv.org/abs/2211.04604) | RSS 2023 | 2022-11-08 | ![Star](https://img.shields.io/github/stars/StructDiffusion/StructDiffusion?style=social&label=Star) [Github](https://github.com/StructDiffusion/StructDiffusion) |  

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Flow Matching Policy
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**3D FlowMatch Actor: Unified 3D Policy for Single- and Dual-Arm Manipulation**](https://arxiv.org/abs/2508.11002) | arXiv | 2025-08-14 | ![Star](https://img.shields.io/github/stars/nickgkan/3d_flowmatch_actor?style=social&label=Star) [Github](https://github.com/nickgkan/3d_flowmatch_actor) | |
| [**VFP: Variational Flow-Matching Policy for Multi-Modal Robot Manipulation**](https://www.arxiv.org/abs/2508.01622) | arXiv | 2025-08-03 | [Project](https://sites.google.com/view/varfp/) | |
| [**MP1: Mean Flow Tames Policy Learning in 1-step for Robotic Manipulation**](https://arxiv.org/abs/2507.10543) | arXiv | 2025-07-14 | ![Star](https://img.shields.io/github/stars/LogSSim/MP1?style=social&label=Star) [Github](https://github.com/LogSSim/MP1) | |
| [**Real-Time Execution of Action Chunking Flow Policies**](https://arxiv.org/abs/2506.07339) | arXiv | 2025-06-09 | [Project](https://www.pi.website/research/real_time_chunking) | |
| [**Streaming Flow Policy: Simplifying diffusion flow-matching policies by treating action trajectories as flow trajectories**](https://arxiv.org/abs/2505.21851) | arXiv | 2025-05-28 | [Project](https://siddancha.github.io/streaming-flow-policy/) | |
| [**GenFlowRL: Shaping Rewards with Generative Object-Centric Flow in Visual Reinforcement Learning**](https://arxiv.org/abs/2508.11049) | ICCV 2025 | 2025-08-14 | [Project](https://colinyu1.github.io/genflowrl/) |  |
| [**H-RDT: Human Manipulation Enhanced Bimanual Robotic Manipulation**](https://www.arxiv.org/abs/2507.23523) | RSS 2025 | 2025-07-31 | ![Star](https://img.shields.io/github/stars/HongzheBi/H_RDT?style=social&label=Star) [Github](https://github.com/HongzheBi/H_RDT) |  |
| [**FlowRAM: Grounding Flow Matching Policy with Region-Aware Mamba Framework for Robotic Manipulation**](https://arxiv.org/abs/2506.16201) | CVPR 2025 | 2025-06-19 | - |  |
| [**FLOWER: Democratizing Generalist Robot Policies with Efficient Vision-Language-Action Flow Policies**](https://openreview.net/forum?id=ifo8oWSLSq) | ICLRW 2025 | 2025-02-28 | ![Star](https://img.shields.io/github/stars/intuitive-robots/flower_vla_calvin?style=social&label=Star) [Github](https://github.com/intuitive-robots/flower_vla_calvin) |  |
| [**X-IL: Exploring the Design Space of Imitation Learning Policies**](https://arxiv.org/abs/2502.12330) | ICLRW 2025 | 2025-02-17 | ![Star](https://img.shields.io/github/stars/ALRhub/X_IL?style=social&label=Star) [Github](https://github.com/ALRhub/X_IL) |  |
| [**Affordance-based Robot Manipulation with Flow Matching**](https://arxiv.org/abs/2409.01083) | arXiv | 2024-09-02 | ![Star](https://img.shields.io/github/stars/HRI-EU/flow_matching?style=social&label=Star) [Github](https://github.com/HRI-EU/flow_matching) | |
| [**FlowPolicy: Enabling Fast and Robust 3D Flow-based Policy via Consistency Flow Matching for Robot Manipulation**](https://arxiv.org/abs/2412.04987) | AAAI 2025 | 2024-12-06 | ![Star](https://img.shields.io/github/stars/zql-kk/FlowPolicy?style=social&label=Star) [Github](https://github.com/zql-kk/FlowPolicy) | |
| [**Robot Manipulation with Flow Matching**](https://arxiv.org/abs/2507.10543) | CoRLW 2024 | 2024-10-29 | ![Star](https://img.shields.io/github/stars/HRI-EU/flow_matching?style=social&label=Star) [Github](https://github.com/HRI-EU/flow_matching) | |
| [PointFlowMatch: **Learning Robotic Manipulation Policies from Point Clouds with Conditional Flow Matching**](https://arxiv.org/abs/2409.07343) | CoRL 2024 | 2024-09-11 | ![Star](https://img.shields.io/github/stars/robot-learning-freiburg/PointFlowMatch?style=social&label=Star) [Github][Project](https://github.com/robot-learning-freiburg/PointFlowMatch) |  |
| [**AdaFlow: Imitation Learning with Variance-Adaptive Flow-Based Policies**](https://arxiv.org/abs/2402.04292) | NeurIPS 2024 | 2024-02-06 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Other Policies
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| _Mamba-based Policy_ |
| [**MTIL: Encoding Full History with Mamba for Temporal Imitation Learning**](https://arxiv.org/abs/2505.12410) | arXiv | 2025-05-18 | ![Star](https://img.shields.io/github/stars/yulinzhouZYL/MTIL?style=social&label=Star) [Github](https://github.com/yulinzhouZYL/MTIL) | |
| [**FlowRAM: Grounding Flow Matching Policy with Region-Aware Mamba Framework for Robotic Manipulation**](https://arxiv.org/abs/2506.16201) | CVPR 2025 | 2025-06-19 | - |  |
| [**Mamba as a Motion Encoder for Robotic Imitation Learning**](https://arxiv.org/abs/2409.02636) | IEEE Access 2025 | 2024-09-04 | - | |
| [**RoboMamba: Multimodal State Space Model for Efficient Robot Reasoning and Manipulation**](https://arxiv.org/abs/2406.04339) | NeurIPS 2024 | 2024-06-06 | ![Star](https://img.shields.io/github/stars/lmzpai/roboMamba?style=social&label=Star) [Github](https://github.com/lmzpai/roboMamba) |  |
| [**MaIL: Improving Imitation Learning with Mamba**](https://arxiv.org/abs/2406.08234) | CoRL 2024 | 2024-06-12 | ![Star](https://img.shields.io/github/stars/ALRhub/MaIL?style=social&label=Star) [Github](https://github.com/ALRhub/MaIL) | |
| _SNN-based Policy_ |
| [**Fully Spiking Actor-Critic Neural Network for Robotic Manipulation**](https://arxiv.org/abs/2508.12038) | arXiv | 2025-08-16 | - | |
| [**Multimodal Spiking Neural Network for Space Robotic Manipulation**](https://arxiv.org/abs/2508.07287) | arXiv | 2025-08-10 | ![Star](https://img.shields.io/github/stars/mazpie/redundancy-action-spaces?style=social&label=Star) [Github](https://github.com/mazpie/redundancy-action-spaces) | |
| [STMDP: **Brain-inspired Action Generation with Spiking Transformer Diffusion Policy Model**](https://arxiv.org/abs/2411.09953) | arXiv | 2024-11-15 | - | |
| [**SDP: Spiking Diffusion Policy for Robotic Manipulation with Learnable Channel-Wise Membrane Thresholds**](https://arxiv.org/abs/2409.11195) | arXiv | 2024-09-17 | - | |
| _Frequency-based Policy_ |
| [**Wavelet Policy: Lifting Scheme for Policy Learning in Long-Horizon Tasks**](https://arxiv.org/abs/2507.04331) | arXiv | 2025-07-06 | - | |
| [**FreqPolicy: Efficient Flow-based Visuomotor Policy via Frequency Consistency**](https://arxiv.org/abs/2506.08822) | arXiv | 2025-06-10 | - | |
| [**FreqPolicy: Frequency Autoregressive Visuomotor Policy with Continuous Tokens**](https://arxiv.org/abs/2506.01583) | arXiv | 2025-06-02 | - | |
| [**Fourier Transporter: Bi-Equivariant Robotic Manipulation in 3D**](https://arxiv.org/abs/2401.12046) | ICLR 2024 | 2024-01-22 | - |
| _Kinematics-based Policy_ |
| [**Rodrigues Network for Learning Robot Actions**](https://arxiv.org/abs/2506.02618) | arXiv | 2025-06-03 | - | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

