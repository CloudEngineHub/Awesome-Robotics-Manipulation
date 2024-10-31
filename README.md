# Awesome-Robotics-Manipulation

 **A Survey on Robot Manipulation**

Please feel free to send me pull requests or email to add papers!


<!-- ******* 0-Content Table ******* -->
 ---
<font size=5><center><b> Table of Contents </b> </center></font>
- [Awesome Papers](#awesome-papers)
  - [Survey](#survey)
  - [Grasp](#grasp)
    - [Rectangle-based Grasp](#rectangle-based-grasp)
    - [6-DoF Grasp](#6-dof-grasp)
    - [Grasp with 3D Techniques](#grasp-with-3d-techniques)
    - [Language-Driven Grasp](#language-driven-grasp)
    - [Grasp with Transparent Objects](#grasp-with-transparent-objects)
  - [Manipulation](#manipulation)
    - [Representation Learning with Auxiliary Tasks](#representation-learning-with-auxiliary-tasks)
    - [Visual Representation Learning](#visual-representation-learning)
    - [Multimodal Representation Learning](#multimodal-representation-learning)
    - [Latent Action Learning](#latent-action-learning)
    - [World Model](#world-model)
    - [Asynchronous Action Learning](#asynchronous-action-learning)
    - [Diffusion Policy Learning](#diffusion-policy-learning)
    - [Other Policies](#other-policies)
    - [Vision Language Action Models](#vision-language-action-models)
    - [Reinforcement Learning](#reinforcement-learning)
    - [Motion, Tranjectory and Flow](#motion-tranjectory-and-flow)
    - [Data Collection, Selection and Augmentation](#data-collection-selection-and-augmentation)
    - [Affordance Learning](#affordance-learning)
    - [3D Representation for Manipulation](#3d-representation-for-manipulation)
    - [3D Representation Policy Learning](#3d-representation-policy-learning)
    - [Reasoning, Planning and Code Generation](#reasoning-planning-and-code-generation)
    - [Generalization](#generalization)
    - [Generalist](#generalist)
    - [Human-Robot Interaction and Collaboration](#human-robot-interaction-and-collaboration)
    - [Tactile](#tactile)
    - [Dexterous Manipulation](#dexterous-manipulation)
    - [Other Applications](#other-applications)
- [Awesome Benchmarks](#awesome-datasets)
  - [Grasp Datasets](#grasp-datasets)
  - [Manipulation Benchmarks](#manipulation-benchmarks)
  - [Cross-Embodiment Benchmarks](#cross-embodiment-benchmarks)
- [Awesome-techniques](#awesome-techniques)
---



<!-- ******* 1-Papers ******* -->
# Awesome Papers


<!-- ******* 1.1-Survey ******* -->
## Survey
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**A Survey of Embodied Learning for Object-Centric Robotic Manipulation**](https://arxiv.org/abs/2408.11537) | arXiv | 2024-08-21 | [Github](https://github.com/RayYoh/OCRM_survey) | Manipulation |
| [**Aligning Cyber Space with Physical World: A Comprehensive Survey on Embodied AI**](https://arxiv.org/abs/2407.06886) | arXiv | 2024-07-09 | [Github](https://github.com/HCPLab-SYSU/Embodied_AI_Paper_List) | Embodied Agent |
| [**A Survey on Vision-Language-Action Models for Embodied AI**](https://arxiv.org/abs/2405.14093) | arXiv | 2024-05-23 | - | VLA Models |
| [**Language-conditioned Learning for Robotic Manipulation: A Survey**](https://arxiv.org/abs/2312.10807) | arXiv | 2023-12-17 | [Github](https://github.com/hk-zh/language-conditioned-robot-manipulation-models) | Manipulation |
| [**Deep Learning Approaches to Grasp Synthesis: A Review**](https://arxiv.org/abs/2207.02556) | T-RO 2023 | 2023-07-06 | [Github](https://rhys-newbury.github.io/projects/6dof/) | Grasp |
<!-- 
| [**Teleoperation of Humanoid Robots: A Survey**](https://arxiv.org/abs/2301.04317) | T-RO 2024 | 2023-01-11 | [Project](https://humanoid-teleoperation.github.io/) | Humanoid Robot | 
-->

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


<!-- ******* 1.2-Grasp ******* -->
## Grasp

<!-- ******* 1.2.1-Rectangle-based Grasp ******* -->
### Rectangle-based Grasp
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Lightweight Language-driven Grasp Detection using Conditional Consistency Model**](https://arxiv.org/abs/2407.17967) | IROS 2024 | 2024-07-25 | [Github](https://github.com/Fsoft-AIC/Lightweight-Language-driven-Grasp-Detection) | |
| [**End-to-end Trainable Deep Neural Network for Robotic Grasp Detection and Semantic Segmentation from RGB**](https://arxiv.org/abs/2107.05287) | ICRA 2021 | 2021-07-12 | [Github](https://github.com/stefan-ainetter/grasp_det_seg_cnn) | grasp_det_seg_cnn |
| [**Antipodal Robotic Grasping using Generative Residual Convolutional Neural Network**](https://arxiv.org/abs/1909.04810) | IROS 2020 | 2019-09-11 | [Github](https://github.com/skumra/robotic-grasping) | GR-ConvNet |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.2-6-DoF Grasp ******* -->
### 6-DoF Grasp
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Real-to-Sim Grasp: Rethinking the Gap between Simulation and Real World in Grasp Detection**](https://arxiv.org/abs/2410.06521) | CoRL 2024 | 2024-10-09 | [Project](https://isee-laboratory.github.io/R2SGrasp/) | Real2Sim |
| [**OrbitGrasp: SE(3)-Equivariant Grasp Learning**](https://arxiv.org/abs/2407.03531) | CoRL 2024 | 2024-07-03 | [Project](https://orbitgrasp.github.io/) | Equivariance |
| [**EquiGraspFlow: SE(3)-Equivariant 6-DoF Grasp Pose Generative Flows**](https://openreview.net/pdf?id=5lSkn5v4LK) | CoRL 2024 | - | [Github](https://github.com/bdlim99/EquiGraspFlow) | Equivariance |
| [**An Economic Framework for 6-DoF Grasp Detection**](https://arxiv.org/abs/2407.08366) | ECCV 2024 | 2024-07-11 | [Github](https://github.com/iSEE-Laboratory/EconomicGrasp) | Scene-level |
| [**Generalizing 6-DoF Grasp Detection via Domain Prior Knowledge**](https://arxiv.org/abs/2404.01727) | CVPR 2024 | 2024-04-02 | [Github](https://github.com/mahaoxiang822/Generalizing-Grasp) | Generalization |
| [**Rethinking 6-Dof Grasp Detection: A Flexible Framework for High-Quality Grasping**](https://arxiv.org/abs/2403.15054) | arXiv 2024 | 2024-03-22 | - | Target-oriented |
| [**Efficient Heatmap-Guided 6-Dof Grasp Detection in Cluttered Scenes**](https://arxiv.org/abs/2403.18546) | RA-L 2023 | 2024-03-27 | [Github](https://github.com/THU-VCLab/HGGD) | Scene-level|
| [**AnyGrasp: Robust and Efficient Grasp Perception in Spatial and Temporal Domains**](https://arxiv.org/abs/2212.08333) | T-RO 2023 | 2022-12-16 | [Github](https://github.com/graspnet/anygrasp_sdk) | |
| [**GraspNet-1Billion: A Large-Scale Benchmark for General Object Grasping**](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_GraspNet-1Billion_A_Large-Scale_Benchmark_for_General_Object_Grasping_CVPR_2020_paper.pdf) | CVPR 2020 | 2020 | [Github](https://github.com/graspnet/graspnet-baseline) | Scene-level |
| [**6-DOF GraspNet: Variational Grasp Generation for Object Manipulation**](https://arxiv.org/abs/1905.10520) | ICCV 2019 | 2019-05-25 | - | VAE |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.3-Grasp with 3D Techniques ******* -->
### Grasp with 3D Techniques
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| _SDF_|
| [**Implicit Grasp Diffusion: Bridging the Gap between Dense Prediction and Sampling-based Grasping**](https://openreview.net/pdf?id=VUhlMfEekm) | CoRL 2024 | - | [Gitlab](https://gitlab.kuleuven.be/detry-lab/public/implicit-grasp-diffusion) | Diffusion |
| [**Learning Any-View 6DoF Robotic Grasping in Cluttered Scenes via Neural Surface Rendering**](https://arxiv.org/abs/2306.07392) | RSS 2024 | 2023-06-12 | - | |
| _NeRF_ |
| [**Language Embedded Radiance Fields for Zero-Shot Task-Oriented Grasping**](https://arxiv.org/abs/2309.07970) | CoRL 2023 | 2023-09-14 | [Github](https://github.com/lerftogo/lerftogo) | LERF |
| [**GraspNeRF: Multiview-based 6-DoF Grasp Detection for Transparent and Specular Objects Using Generalizable NeRF**](https://arxiv.org/abs/2210.06575) | ICRA 2023 | 2022-10-12 | [Github](https://github.com/PKU-EPIC/GraspNeRF) | |
| _3D Gaussian Splatting (3DGS)_ |
| [**GraspSplats: Efficient Manipulation with 3D Feature Splatting**](https://arxiv.org/abs/2409.02084) | CoRL 2024 | 2024-09-03 | [Github](https://github.com/jimazeyu/GraspSplats) | |
| [**GaussianGrasper: 3D Language Gaussian Splatting for Open-vocabulary Robotic Grasping**](https://arxiv.org/abs/2403.09637) | RA-L 2024 | 2024-03-14 | [Github](https://github.com/MrSecant/GaussianGrasper) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.4-Language-Driven Grasp ******* -->
### Language-Driven Grasp
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**RTAGrasp: Learning Task-Oriented Grasping from Human Videos via Retrieval, Transfer, and Alignment**](https://arxiv.org/abs/2409.16033) | arXiv | 2024-09-24 | [Project](https://sites.google.com/view/rtagrasp/home) | LfD |
| [**Language-Driven 6-DoF Grasp Detection Using Negative Prompt Guidance**](https://arxiv.org/abs/2407.13842) | ECCV 2024 | 2024-07-18 | [Github](https://github.com/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance) | |
| [**Reasoning Grasping via Multimodal Large Language Model**](https://arxiv.org/abs/2402.06798) | CoRL 2024 | 2024-02-09 | [Project](https://reasoning-grasping.github.io/) | LLMs |
| [**ThinkGrasp: A Vision-Language System for Strategic Part Grasping in Clutter**](https://arxiv.org/abs/2407.11298) | CoRL 2024 | 2024-07-16 | [Github](https://github.com/H-Freax/ThinkGrasp) | MLLMs |
| [**Towards Open-World Grasping with Large Vision-Language Models**](https://arxiv.org/abs/2406.18722) | CoRL 2024 | 2024-06-26 | [Project](https://gtziafas.github.io/OWG_project/) | MLLMs |
| [**Reasoning Tuning Grasp: Adapting Multi-Modal Large Language Models for Robotic Grasping**](https://openreview.net/pdf?id=3mKb5iyZ2V) | CoRL 2023 Workshop | 2023-10-21 | [Project](https://sites.google.com/view/rt-grasp) | Tunning MLLMs |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.2.5-Grasp with Transparent Objects ******* -->
### Grasp with Transparent Objects
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**T<sup>2</sup>SQNet: A Recognition Model for Manipulating Partially Observed Transparent Tableware Objects**](https://openreview.net/pdf?id=M0JtsLuhEE) | CoRL 2024 | - | [Github](https://github.com/seungyeon-k/T2SQNet-public) | |
| [**ASGrasp: Generalizable Transparent Object Reconstruction and Grasping from RGB-D Active Stereo Camera**](https://arxiv.org/abs/2405.05648) | ICRA 2024 | 2024-05-09 | [Github](https://github.com/jun7-shi/ASGrasp) | |
| [**Dex-NeRF: Using a Neural Radiance Field to Grasp Transparent Objects**](https://arxiv.org/abs/2110.14217) | CoRL 2021 | 2021-10-27 | [Project](https://sites.google.com/view/dex-nerf) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


<!-- ******* 1.3-Manipulation ******* -->
## Manipulation

<!-- ******* 1.3.1-Representation Learning with Auxiliary Tasks ******* -->
### Representation Learning with Auxiliary Tasks
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| _Contrastive Learning (Alignment)_ |
| [**Contrastive Imitation Learning for Language-guided Multi-Task Robotic Manipulation**](https://arxiv.org/abs/2406.09738) | CoRL 2024 | 2024-06-14 | [Project](https://teleema.github.io/projects/Sigma_Agent/) | IL, RepL, Poliy Head, Alignment |
| [**Vid2Robot: End-to-end Video-conditioned Policy Learning with Cross-Attention Transformers**](https://arxiv.org/abs/2403.12943) | RSS 2024 | 2024-03-19 | [Project](https://vid2robot.github.io/) | IL, RepL, LfD, E-D, Poliy Head, Language Goal, Alignment |
| [**R3M: A Universal Visual Representation for Robot Manipulation**](https://arxiv.org/abs/2203.12601) | CoRL 2023 | 2022-03-23 | [Github](https://github.com/facebookresearch/r3m) | IL, RepL, LfD, Alignment, Language Goal, Poliy Head |
| [HULC: **What Matters in Language Conditioned Robotic Imitation Learning over Unstructured Data**](https://arxiv.org/abs/2204.06252) | RA-L 2022 | 2022-04-13 | [Github](https://github.com/lukashermann/hulc) | IL, RepL, Alignment, Language Goal, Poliy Head |
| [**BC-Z: Zero-Shot Task Generalization with Robotic Imitation Learning**](https://arxiv.org/abs/2202.02005) | CoRL 2021 | 2022-02-04 | [Github](https://github.com/google-research/tensor2robot/tree/master/research/bcz) | IL, RepL, Language Goal, Alignment, Poliy Head |
| _Masked Construction_ |
| [**Spatiotemporal Predictive Pre-training for Robotic Motor Control**](https://arxiv.org/abs/2403.05304) | arXiv | 2024-03-08 | - | IL, RepL, Masked Construction, Image Prediction, Poliy Head  |
| [**MUTEX: Learning Unified Policies from Multimodal Task Specifications**](https://arxiv.org/abs/2309.14320) | CoRL 2023 | 2023-09-25 | [Github](https://github.com/UT-Austin-RPL/mutex) | IL, RepL, Multimodal, E-D, Masked Construction, TP |
| [**Language-Driven Representation Learning for Robotics**](https://arxiv.org/abs/2302.12766) | RSS 2023 | 2023-02-24 | [Github](https://github.com/siddk/voltron-robotics) | IL, RepL, Masked Construction, Both Goals, Poliy Head |
| [**Real-World Robot Learning with Masked Visual Pre-training**](https://arxiv.org/abs/2210.03109) | CoRL 2022 | 2022-10-06 | [Github](https://github.com/ir413/mvp) | IL, RepL, Masked Construction, Image Goal, Poliy Head |
| _Text Goal Generation_ |
| [**RACER: Rich Language-Guided Failure Recovery Policies for Imitation Learning**](https://arxiv.org/abs/2409.14674) | arXiv | 2024-09-23 | [Github](https://github.com/sled-group/RACER) | IL, RepL, Human Intervention Generation, Poliy Head, Language Goal |
| [**EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought**](https://arxiv.org/abs/2305.15021) | NeurIPS 2023 | 2023-05-24 | [Github](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch) |  |
| [**Chain-of-Thought Predictive Control**](https://arxiv.org/abs/2304.00776) | ICML 2024 | 2023-04-03 | [Github](https://github.com/SeanJia/CoTPC) | IL, RepL, CoT  |
| _Visual Goal Generation_ |
| [**KOI: Accelerating Online Imitation Learning via Hybrid Key-state Guidance**](https://www.arxiv.org/abs/2408.02912) | CoRL 2024 | 2024-08-06 | [Github](https://github.com/GeWu-Lab/Keystate_Online_Imitation) | Online IL, Motion Key States |
| [GENIMA: **Generative Image as Action Models**](https://arxiv.org/abs/2407.07875) | CoRL 2024 | 2024-07-10 | [Github](https://github.com/MohitShridhar/genima) | diffusion, draw joint-actions |
| [**Any-point Trajectory Modeling for Policy Learning**](https://arxiv.org/abs/2401.00025) | CoRL 2024 | 2023-12-28 | [Github](https://github.com/Large-Trajectory-Model/any-point-trajectory-modeling) | IL, RepL, Point Trajectories Generation |
| [**Learning Manipulation by Predicting Interaction**](https://www.arxiv.org/abs/2406.00439) | RSS 2024 | 2024-06-01 | [Github](https://github.com/OpenDriveLab/MPI) | IL, RepL, Interaction-oriented Prediction, Both Goals, Poliy Head |
| [**Object-Centric Instruction Augmentation for Robotic Manipulation**](https://arxiv.org/abs/2401.02814) | ICRA 2024 | 2024-01-05 | [Project](https://oci-robotics.github.io/) |  IL, RepL, Object-Centric Information Generation, Poliy Head, Language Goal |
| [**CALAMARI: Contact-Aware and Language conditioned spatial Action MApping for contact-RIch manipulation**](https://openreview.net/pdf?id=Nii0_rRJwN) | CoRL 2023 | 2023 | [Project](https://www.mmintlab.com/research/calamari/) | RepL, Language Goal, Contact Goal Generation |
| [**Towards Generalizable Zero-Shot Manipulation via Translating Human Interaction Plans**](https://arxiv.org/abs/2312.00775) | ICRA 2024 | 2023-12-01 | [Project](https://homangab.github.io/hopman/) | IL, RepL, LfD, Image Goal, E-D, TP, Human-Plan Generation |
| _Video Prediction_ |
| [**GR-2: A Generative Video-Language-Action Model with Web-Scale Knowledge for Robot Manipulation**](https://arxiv.org/abs/2410.06158) | arXiv | 2024-10-08 | [Project](https://gr2-manipulation.github.io/) | IL, RepL, Image Prediction, TP |
| [**Unleashing Large-Scale Video Generative Pre-training for Visual Robot Manipulation**](https://arxiv.org/abs/2312.13139) | ICLR 2024 | 2023-12-20 | [Github](https://github.com/bytedance/GR-1) | IL, RepL, Image Prediction, TP |
| [**Video Language Planning**](https://arxiv.org/abs/2310.10625) | ICLR 2024 | 2023-10-16 | [Github](https://github.com/video-language-planning/vlp_code) | |
| [**GR-MG: Leveraging Partially Annotated Data via Multi-Modal Goal Conditioned Policy**](https://arxiv.org/abs/2408.14368) | arXiv | 2024-08-26 | [Github](https://github.com/bytedance/GR-MG/tree/main) | IL, RepL, Image Prediction, Text State Prediction, Partially labeled data, TP |
| [**VLMPC: Vision-Language Model Predictive Control for Robotic Manipulation**](https://arxiv.org/abs/2407.09829) | RSS 2024 | 2024-07-13 | [Github](https://github.com/PPjmchen/VLMPC) | IL, RepL, Video Prediction, MPC |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.2-Visual Representation Learning ******* -->
### Visual Representation Learning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Theia: Distilling Diverse Vision Foundation Models for Robot Learning**](https://arxiv.org/abs/2407.20179) | CoRL 2024 | 2024-07-29 | [Github](https://github.com/bdaiinstitute/theia) | IL, RepL, KD in VLMs, Poliy Head |
| [**Learning Manipulation by Predicting Interaction**](https://www.arxiv.org/abs/2406.00439) | RSS 2024 | 2024-06-01 | [Github](https://github.com/OpenDriveLab/MPI) | IL, RepL, Interaction-oriented Prediction, Both Goals, Poliy Head |
| [**Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware**](https://arxiv.org/abs/2304.13705) | RSS 2023 | 2023-04-23 | [Github](https://github.com/tonyzhaozh/aloha) | IL, RepL, E-D, TP |
| [**Language-Driven Representation Learning for Robotics**](https://arxiv.org/abs/2302.12766) | RSS 2023 | 2023-02-24 | [Github](https://github.com/siddk/voltron-robotics) | IL, RepL, Masked Construction, Both Goals, Poliy Head |
| [**VIMA: General Robot Manipulation with Multimodal Prompts**](https://arxiv.org/abs/2210.03094) | ICML 2023 | 2022-10-06 | [Github](https://github.com/vimalabs/VIMA) | Benchmark, E-D, TP, Multimodal Prompt |
| [**Real-World Robot Learning with Masked Visual Pre-training**](https://arxiv.org/abs/2210.03109) | CoRL 2022 | 2022-10-06 | [Github](https://github.com/ir413/mvp) | IL, RepL, Masked Construction, Image Goal, Poliy Head |
| [**R3M: A Universal Visual Representation for Robot Manipulation**](https://arxiv.org/abs/2203.12601) | CoRL 2023 | 2022-03-23 | [Github](https://github.com/facebookresearch/r3m) | IL, RepL, LfD, Alignment, Language Goal, Poliy Head |
| [**LIV: Language-Image Representations and Rewards for Robotic Control**](https://arxiv.org/abs/2306.00958) | ICML 2023 | 2023-06-01 | [Github](https://github.com/penn-pal-lab/LIV) | RepL, LfD, Both Goals, Alignment |
| [**VIP: Towards Universal Visual Reward and Representation via Value-Implicit Pre-Training**](https://arxiv.org/abs/2210.00030) | ICLR 2023 | 2022-08-30 | [Github](https://github.com/facebookresearch/vip) | RepL, LfD, Image Goal |
| [**Can Foundation Models Perform Zero-Shot Task Specification For Robot Manipulation?**](https://arxiv.org/abs/2204.11134) | L4DC 2022 | 2022-04-23 | [Project](https://sites.google.com/view/zestproject) | Both Goals |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.3-Multimodal Representation Learning ******* -->
### Multimodal Representation Learning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Play to the Score: Stage-Guided Dynamic Multi-Sensory Fusion for Robotic Manipulation**](https://arxiv.org/abs/2408.01366) | arXiv | 2024-08-02 | [Github](https://github.com/sled-group/RACER) | IL, RepL, Multimodal, Poliy Head |
| [**MUTEX: Learning Unified Policies from Multimodal Task Specifications**](https://arxiv.org/abs/2309.14320) | CoRL 2023 | 2023-09-25 | [Github](https://github.com/UT-Austin-RPL/mutex) | IL, RepL, Multimodal, E-D, Masked Construction, TP |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.4-Latent Action Learning ******* -->
### Latent Action Learning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**IGOR: Image-GOal Representations Atomic Control Units for Foundation Models in Embodied AI**](https://www.microsoft.com/en-us/research/uploads/prod/2024/10/Project_IGOR_for_arXiv.pdf) | - | 2024 | [Github](https://www.microsoft.com/en-us/research/project/igor-image-goal-representations/) | IL, RepL, Image Prediction, Poliy Head |
| [**Latent Action Pretraining from Videos**](https://arxiv.org/abs/2410.11758) | arXiv | 2024-10-15 | [Github](https://github.com/LatentActionPretraining/LAPA) | IL, RepL, Alignment, Both Goals,   Poliy Head |
| [**Goal Representations for Instruction Following: A Semi-Supervised Language Interface to Control**](https://arxiv.org/abs/2307.00117) | CoRL 2023 | 2023-06-30 | [Github](https://github.com/rail-berkeley/grif_release) | IL, RepL, Alignment, Both Goals, Poliy Head, Partially labeled data |
| [**MimicPlay: Long-Horizon Imitation Learning by Watching Human Play**](https://arxiv.org/abs/2302.12422) | CoRL 2023 | 2023-02-24 | [Github](https://github.com/j96w/MimicPlay) | IL, RepL, LfD, Image Goal, Poliy Head |
| [**Imitation Learning with Limited Actions via Diffusion Planners and Deep Koopman Controllers**](https://arxiv.org/abs/2410.07584) | arXiv | 2024-10-24 | - | IL, RepL, Image Prediction, Koopman Operator |
| [**Learning to Act without Actions**](https://arxiv.org/abs/2312.10812) | ICLR 2024 | 2023-12-17 | [Github](https://github.com/schmidtdominik/LAPO) | IL, RepL, Image Prediction, Latent Inverse Dynamics Model |
| [**Imitating Latent Policies from Observation**](https://arxiv.org/abs/1805.07914) | ICML 2019 | 2018-05-21 | [Github](https://github.com/ashedwards/ILPO) | IL, RepL, Latent Inverse Dynamics Model |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.5-World Model ******* -->
### World Model
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Finetuning Offline World Models in the Real World**](https://arxiv.org/abs/2310.16029) | CoRL 2023 | 2023-10-24 | [Github](https://github.com/fyhMer/fowm) | |
| [**Structured World Models from Human Videos**](https://arxiv.org/abs/2308.10901) | RSS 2023 | 2023-08-23 | [Github](https://human-world-model.github.io/) | |
| [**Surfer: Progressive Reasoning with World Models for Robotic Manipulation**](https://arxiv.org/abs/2306.11335) | arXiv | 2023-06-20 | [Github](https://github.com/Necolizer/RM-PRT) | |
| [**MOTO: Offline Pre-training to Online Fine-tuning for Model-based Robot Learning**](https://arxiv.org/abs/2401.03306) | CoRL 2023 | 2024-01-06 | [Project](https://sites.google.com/view/mo2o) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.6-Asynchronous Action Learning ******* -->
### Asynchronous Action Learning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**PIVOT-R: Primitive-Driven Waypoint-Aware World Model for Robotic Manipulation**](https://arxiv.org/abs/2410.10394) | arXiv | 2024-10-14 | [Project](https://abliao.github.io/PIVOT-R/) | IL, RepL, Image Prediction, Hierarchical, Poliy Head |
| [**HiRT: Enhancing Robotic Control with Hierarchical Robot Transformers**](https://arxiv.org/abs/2410.05273) | arXiv | 2024-09-12 | - | IL, RepL, Hierarchical, Poliy Head |
| [**MResT: Multi-Resolution Sensing for Real-Time Control with Vision-Language Models**](https://arxiv.org/abs/2401.14502) | CoRL 2023 | 2024-01-25 | [Github](https://github.com/iamlab-cmu/mrest-multi-resolution-transformer) | IL, RepL, Multi-Resolution, Poliy Head |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.7-Diffusion Policy Learning ******* -->
### Diffusion Policy Learning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Diffusion Transformer Policy**](https://arxiv.org/abs/2410.15959) | arXiv | 2024-10-21 | - | |
| [MDT: **Multimodal Diffusion Transformer: Learning Versatile Behavior from Multimodal Goals**](https://arxiv.org/abs/2407.05996) | RSS 2024 | 2024-07-08 | [Github](https://github.com/intuitive-robots/mdt_policy) | IL, RepL, Masked Construction, DP, Partially labeled data |
| [**Render and Diffuse: Aligning Image and Action Spaces for Diffusion-based Behaviour Cloning**](https://arxiv.org/abs/2405.18196) | RSS 2024 | 2024-05-28 | [Github](https://github.com/vv19/rendiff) | |
| [**3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations**](https://arxiv.org/abs/2403.03954) | RSS 2024 | 2024-03-06 | [Github](https://github.com/YanjieZe/3D-Diffusion-Policy) | DP3 |
| [**PlayFusion: Skill Acquisition via Diffusion from Language-Annotated Play**](https://arxiv.org/abs/2312.04549) | CoRL 2023 | 2023-12-07 | [Project](https://play-fusion.github.io/) |  |
| [**Equivariant Diffusion Policy**](https://arxiv.org/abs/2407.01812) | CoRL 2024 | 2024-07-01 | [Code](https://github.com/pointW/equidiff) | Equivariance |
| [**EquiBot: SIM(3)-Equivariant Diffusion Policy for Generalizable and Data Efficient Learning**](https://arxiv.org/abs/2407.01479) | CoRL 2024 | 2024-07-01 | [Github](https://github.com/yjy0625/equibot) |  |
| [**Sparse Diffusion Policy: A Sparse, Reusable, and Flexible Policy for Robot Learning**](https://arxiv.org/abs/2407.01531) | CoRL 2024 | 2024-07-01 | [Github](https://github.com/AnthonyHuo/SDP) | MoE |
| [**StructDiffusion: Language-Guided Creation of Physically-Valid Structures using Unseen Objects**](https://arxiv.org/abs/2211.04604) | RSS 2023 | 2022-11-08 | [Github](https://github.com/StructDiffusion/StructDiffusion) |  |
| [**Goal-Conditioned Imitation Learning using Score-based Diffusion Policies**](https://arxiv.org/abs/2304.02532) | RSS 2023 | 2023-04-05 | [Github](https://github.com/intuitive-robots/beso) |  |
| [**Diffusion Policy: Visuomotor Policy Learning via Action Diffusion**](https://arxiv.org/abs/2303.04137) | RSS 2023 | 2023-03-07 | [Github](https://github.com/real-stanford/diffusion_policy) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.8-Other Policies ******* -->
### Other Policies
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Autoregressive Action Sequence Learning for Robotic Manipulation**](https://arxiv.org/abs/2410.03132) | arXiv | 2024-10-04 | [Github](https://github.com/mlzxy/arp) | |
| [**MaIL: Improving Imitation Learning with Selective State Space Models**](https://arxiv.org/abs/2406.08234) | CoRL 2024 | 2024-06-12 | - | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.9-Vision Language Action Models ******* -->
### Vision Language Action Models
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Run-time Observation Interventions Make Vision-Language-Action Models More Visually Robust**](https://arxiv.org/abs/2410.01971) | arXiv | 2024-10-02 | [Github](https://github.com/irom-lab/byovla) |  |
| [**TinyVLA: Towards Fast, Data-Efficient Vision-Language-Action Models for Robotic Manipulation**](https://arxiv.org/abs/2409.12514) | arXiv | 2024-09-19 | [Github](https://github.com/lesjie-wen/tinyvla) |  |
| [**RoboMamba: Multimodal State Space Model for Efficient Robot Reasoning and Manipulation**](https://arxiv.org/abs/2406.04339) | NeurIPS 2024 | 2024-06-06 | [Github](https://github.com/lmzpai/roboMamba) |  |
| [**A Dual Process VLA: Efficient Robotic Manipulation Leveraging VLM**](https://arxiv.org/abs/2410.15549) | CoRL 2024 | 2024-10-21 | - |  |
| [**OpenVLA: An Open-Source Vision-Language-Action Model**](https://arxiv.org/abs/2406.09246) | CoRL 2024 | 2024-06-13 | [Github](https://github.com/openvla/openvla) |  |
| [**LLARVA: Vision-Action Instruction Tuning Enhances Robot Learning**](https://arxiv.org/abs/2406.11815) | CoRL 2024 | 2024-06-17 | [Github](https://github.com/Dantong88/LLARVA) |  |
| [**Robotic Control via Embodied Chain-of-Thought Reasoning**](https://arxiv.org/abs/2406.11815) | CoRL 2024 | 2024-07-11 | [Github](https://github.com/MichalZawalski/embodied-CoT/) |  |
| [**3D-VLA: A 3D Vision-Language-Action Generative World Model**](https://arxiv.org/abs/2403.09631) | ICML 2024 | 2024-03-14 | [Github](https://github.com/UMass-Foundation-Model/3D-VLA) |  |
| [**Octo: An Open-Source Generalist Robot Policy**](https://arxiv.org/abs/2405.12213) | RSS 2024 | 2024-05-20 | [Github](https://github.com/octo-models/octo) | |
| [**RT-H: Action Hierarchies Using Language**](https://arxiv.org/abs/2403.01823) | arXiv | 2024-03-04 | [Project](https://rt-hierarchy.github.io/) |  |
| [**Open X-Embodiment: Robotic Learning Datasets and RT-X Models**](https://arxiv.org/abs/2310.08864) | ICRA 2024 | 2023-10-13 | [Github](https://github.com/google-deepmind/open_x_embodiment) | |
| [**Open-World Object Manipulation using Pre-trained Vision-Language Models**](https://arxiv.org/abs/2303.00905) | CoRL 2023 | 2023-03-02 | [Project](https://robot-moo.github.io/) | MOO |
| [**RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control**](https://arxiv.org/abs/2307.15818) | CoRL 2023 | 2023-07-28 | [Project](https://robotics-transformer2.github.io/) |  |
| [**RT-1: Robotics Transformer for Real-World Control at Scale**](https://arxiv.org/abs/2212.06817) | RSS 2023 | 2022-12-13 | [Github](https://github.com/google-research/robotics_transformer) |  |
| [**Vision-Language Foundation Models as Effective Robot Imitators**](https://arxiv.org/abs/2311.01378) | ICLR 2024 | 2023-11-02 | [Github](https://github.com/RoboFlamingo/RoboFlamingo) | RoboFlamingo |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.10-Reinforcement Learning ******* -->
### Reinforcement Learning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**SPIRE: Synergistic Planning, Imitation, and Reinforcement for Long-Horizon Manipulation**](https://arxiv.org/abs/2410.18065) | CoRL 2024 | 2024-10-23 | [Project](https://sites.google.com/view/spire-corl-2024) |  |
| [**Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning**](https://arxiv.org/abs/2407.15815) | CoRL 2024 | 2024-07-22 | [Project](https://gemcollector.github.io/maniwhere/) |  |
| [**Pre-Training for Robots: Offline RL Enables Learning New Tasks from a Handful of Trials**](https://arxiv.org/abs/2210.05178) | RSS 2023 | 2022-10-11 | [Project](https://sites.google.com/view/ptr-final/) |  |
| [**Expansive Latent Planning for Sparse Reward Offline Reinforcement Learning**](https://openreview.net/pdf?id=xQx1O7WXSA) | CoRL 2023 | 2023 | - | |
| [**Q-Transformer: Scalable Offline Reinforcement Learning via Autoregressive Q-Functions**](https://arxiv.org/abs/2309.10150) | CoRL 2023 | 2023-09-18 | [Project](https://qtransformer.github.io/) | |
| [**Sim2Real Transfer for Reinforcement Learning without Dynamics Randomization**](https://arxiv.org/abs/2002.11635) | CoRL 2023 | 2020-02-19 | - | |
| [**Plan-Seq-Learn: Language Model Guided RL for Solving Long Horizon Robotics Tasks**](https://arxiv.org/abs/2405.01534) | ICLR 2024 | 2024-05-02 | [Github](https://github.com/mihdalal/planseqlearn) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.11-Motion, Tranjectory and Flow ******* -->
### Motion, Tranjectory and Flow
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| _Path Planning_|
| [**Language-Conditioned Path Planning**](https://arxiv.org/abs/2308.16893) | CORL 2023 | 2024-08-31 | [Github](https://github.com/amberxie88/lapp) |  |
| _Motion Planning_|
| [**DiffusionSeeder: Seeding Motion Optimization with Diffusion for Rapid Motion Planning**](https://arxiv.org/abs/2410.16727) | CoRL 2024 | 2024-10-22 | [Project](https://diffusion-seeder.github.io/) | Motion Planning  |
| [**ReKep: Spatio-Temporal Reasoning of Relational Keypoint Constraints for Robotic Manipulation**](https://arxiv.org/abs/2409.01652) | CoRL 2024 | 2024-09-03 | [Github](https://github.com/huangwl18/ReKep) | Motion Planning |
| [**CoPa: General Robotic Manipulation through Spatial Constraints of Parts with Foundation Models**](https://arxiv.org/abs/2403.08248) | ICRAW 2024 | 2024-03-13 | [Github](https://github.com/HaoxuHuang/copa) | Motion Planning |
| [**Task Generalization with Stability Guarantees via Elastic Dynamical System Motion Policies**](https://arxiv.org/abs/2309.01884) | CoRL 2023 | 2023-09-05 | [Github](https://github.com/tonylitianyu/Elastic-DS) | IL, LfD, Motion |
| _Trajectory Optimization_|
| [**ORION: Vision-based Manipulation from Single Human Video with Open-World Object Graphs**](https://arxiv.org/abs/2405.20321) | arXiv | 2024-05-30 | [Github](https://ut-austin-rpl.github.io/ORION-release/) |  |
| [**Learning Robotic Manipulation Policies from Point Clouds with Conditional Flow Matching**](https://arxiv.org/abs/2409.07343) | CoRL 2024 | 2024-09-11 | [Project](http://pointflowmatch.cs.uni-freiburg.de/) |  |
| [**RoboTAP: Tracking Arbitrary Points for Few-Shot Visual Imitation**](https://arxiv.org/abs/2308.15975) | ICRA 2024 | 2023-08-30 | [Github](https://github.com/google-deepmind/tapnet/blob/main/colabs/tapir_clustering.ipynb) |  |
| [**VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models**](https://arxiv.org/abs/2307.05973) | CoRL 2023 | 2023-07-12 | [Github](https://github.com/huangwl18/VoxPoser) | Zero-shot Trajectory Optimization |
| [**LATTE: LAnguage Trajectory TransformEr**](https://arxiv.org/abs/2208.02918) | ICRA 2023 | 2022-08-04 | [Github](https://github.com/arthurfenderbucker/LaTTe-Language-Trajectory-TransformEr) |  |
| _Trajectory-conditioned policy_|
| [**Track2Act: Predicting Point Tracks from Internet Videos enables Generalizable Robot Manipulation**](https://arxiv.org/abs/2405.01527) | ECCV 2024 | 2024-05-02 | [Github](https://github.com/homangab/Track-2-Act/) |  |
| [**Any-point Trajectory Modeling for Policy Learning**](https://arxiv.org/abs/2401.00025) | CoRL 2024 | 2023-12-28 | [Github](https://github.com/Large-Trajectory-Model/any-point-trajectory-modeling) |  |
| [**Waypoint-Based Imitation Learning for Robotic Manipulation**](https://arxiv.org/abs/2307.14326) | CoRL 2023 | 2023-07-26 | [Github](https://github.com/lucys0/awe) | IL, Waypoint |
| _Flow-conditioned policy_|
| [**Flow as the Cross-Domain Manipulation Interface**](https://www.arxiv.org/abs/2407.15208) | CoRL 2024 | 2024-07-21 | [Github](https://github.com/real-stanford/im2Flow2Act) |  |
| [**Learning to Act from Actionless Videos through Dense Correspondences**](https://arxiv.org/abs/2310.08576) | ICLR 2024 | 2023-10-12 | [Github](https://github.com/flow-diffusion/AVDC) | Optical Flow |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.12-Data Collection, Selection and Augmentation ******* -->
### Data Collection, Selection and Augmentation
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| _Data Collection_ |
| [**Scaling Robot Policy Learning via Zero-Shot Labeling with Foundation Models**](https://arxiv.org/abs/2410.17772) | CoRL 2024 | 2024-10-23 | [Project](https://robottasklabeling.github.io/) |  |
| [**Autonomous Improvement of Instruction Following Skills via Foundation Models**](https://arxiv.org/abs/2407.20635) | CoRL 2024 | 2024-07-30 | [Github](https://github.com/rail-berkeley/soar) |  |
| [**Manipulate-Anything: Automating Real-World Robots using Vision-Language Models**](https://arxiv.org/abs/2406.18915) | CoRL 2024 | 2024-06-27 | [Project](https://robot-ma.github.io/) | |
| [**DexCap: Scalable and Portable Mocap Data Collection System for Dexterous Manipulation**](https://arxiv.org/abs/2403.07788) | CoRL 2024 | 2024-03-12 | [Github](https://github.com/j96w/DexCap) | |
| [**SPRINT: Scalable Policy Pre-Training via Language Instruction Relabeling**](https://arxiv.org/abs/2306.11886) | ICRA 2024 | 2023-06-20 | [Github](https://github.com/clvrai/sprint) | |
| [**Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition**](https://arxiv.org/abs/2307.14535) | CoRL 2023 | 2023-07-26 | [Github](https://github.com/real-stanford/scalingup) |  |
| [**Robotic Skill Acquisition via Instruction Augmentation with Vision-Language Models**](https://arxiv.org/abs/2211.11736) | RSS 2023 | 2022-11-21 | [Project](https://instructionaugmentation.github.io/) |  |
| [**RoboCat: A Self-Improving Generalist Agent for Robotic Manipulation**](https://arxiv.org/abs/2306.11706) | TMLR 2023 | 2023-06-20 | - | |
| _Data Selection_ |
| [**Re-Mix: Optimizing Data Mixtures for Large Scale Imitation Learning**](https://arxiv.org/abs/2408.14037) | CoRL 2024 | 2024-08-26 | [Github](https://github.com/jhejna/remix) |  |
| [**An Unbiased Look at Datasets for Visuo-Motor Pre-Training**](https://arxiv.org/abs/2310.09289) | CoRL 2023 | 2023-10-13 | [Github](https://github.com/SudeepDasari/data4robotics) | |
| _Data Retrieval_ |
| [**Retrieval-Augmented Embodied Agents**](https://arxiv.org/abs/2404.11699) | CVPR 2024 | 2024-04-17 | - | |
| [**Behavior Retrieval: Few-Shot Imitation Learning by Querying Unlabeled Datasets**](https://arxiv.org/abs/2304.08742) | RSS 2023 | 2023-04-08 | [Github](https://github.com/MaxDu17/BehaviorRetrieval) | |
| _Data Augmentation_ |
| [**RoVi-Aug: Robot and Viewpoint Augmentation for Cross-Embodiment Robot Learning**](https://arxiv.org/abs/2409.03403) | CoRL 2024 | 2024-09-05 | [Project](https://rovi-aug.github.io/) |  |
| [**Diffusion Augmented Agents: A Framework for Efficient Exploration and Transfer Learning**](https://arxiv.org/abs/2407.20798) | CoLLAs 2024 | 2024-07-30 | [Project](https://sites.google.com/view/diffusion-augmented-agents/) |  |
| [**Diffusion Meets DAgger: Supercharging Eye-in-hand Imitation Learning**](https://arxiv.org/abs/2402.17768) | RSS 2024 | 2023-02-27 | [Github](https://github.com/ErinZhang1998/dmd_diffusion) | |
| [**GenAug: Retargeting behaviors to unseen situations via Generative Augmentation**](https://arxiv.org/abs/2302.06671) | RSS 2023 | 2023-02-13 | [Github](https://github.com/genaug/genaug) |  |
| _Evaluation_|
| [**Contrast Sets for Evaluating Language-Guided Robot Policies**](https://arxiv.org/abs/2406.13636) | CoRL 2024 | 2024-06-19 | - |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


<!-- ******* 1.3.13-Affordance Learning ******* -->
### Affordance Learning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| _Articulated Object Affordance_ |
| [**UniAff: A Unified Representation of Affordances for Tool Usage and Articulation with Vision-Language Models**](https://arxiv.org/abs/2409.20551) | arXiv | 2024-09-16 | [Project](https://sites.google.com/view/uni-aff/home) | |
| [**A3VLM: Actionable Articulation-Aware Vision Language Model**](https://arxiv.org/abs/2406.07549) | CoRL 2024 | 2024-06-14 | [Github](https://github.com/changhaonan/A3VLM) | |
| [**AIC MLLM: Autonomous Interactive Correction MLLM for Robust Robotic Manipulation**](https://arxiv.org/abs/2406.11548) | CoRL 2024 | 2024-06-17 | [Project](https://sites.google.com/view/aic-mllm) | |
| [**SAGE: Bridging Semantic and Actionable Parts for Generalizable Manipulation of Articulated Objects**](https://arxiv.org/abs/2312.01307) | RSS 2024 | 2023-12-03 | [Github](https://github.com/geng-haoran/SAGE) | |
| [**Kinematic-aware Prompting for Generalizable Articulated Object Manipulation with LLMs**](https://arxiv.org/abs/2311.02847) | ICRA 2024 | 2023-11-06 | [Github](https://github.com/GeWu-Lab/LLM_articulated_object_manipulation) | |
| [**Ditto: Building Digital Twins of Articulated Objects from Interaction**](https://arxiv.org/abs/2202.08227) | CVPR 2022 | 2022-08-16 | [Github](https://github.com/UT-Austin-RPL/Ditto) | |
| _Part-Based Object Affordance_ |
| [**Language-Conditioned Affordance-Pose Detection in 3D Point Clouds**](https://arxiv.org/abs/2309.10911) | ICRA 2024 | 2023-09-19 | [Github](https://github.com/Fsoft-AIC/Language-Conditioned-Affordance-Pose-Detection-in-3D-Point-Clouds) | |
| [**Composable Part-Based Manipulation**](https://arxiv.org/abs/2405.05876) | CoRL 2023 | 2024-05-09 | [Project](https://cpmcorl2023.github.io/) | |
| [**PartManip: Learning Cross-Category Generalizable Part Manipulation Policy from Point Cloud Observations**](https://arxiv.org/abs/2303.16958) | CVPR 2023 | 2023-03-29 | [Github](https://github.com/PKU-EPIC/PartManip) | |
| [**GAPartNet: Cross-Category Domain-Generalizable Object Perception and Manipulation via Generalizable and Actionable Parts**](https://arxiv.org/abs/2211.05272) | CVPR 2023 | 2022-11-10 | [Github](https://github.com/PKU-EPIC/GAPartNet) | |
| _Spatial Affordance_ |
| [**SpatialBot: Precise Spatial Understanding with Vision Language Models**](https://arxiv.org/abs/2406.13642) | arXiv | 2024-06-19 | [Github](https://github.com/BAAI-DCAI/SpatialBot) | |
| [**RoboPoint: A Vision-Language Model for Spatial Affordance Prediction for Robotics**](https://arxiv.org/abs/2406.10721) | CoRL 2024 | 2024-06-15 | [Github](https://github.com/wentaoyuan/RoboPoint) | |
| [**SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning Capabilities**](https://arxiv.org/abs/2401.12168) | CVPR 2024 | 2024-01-22 | [Project](https://spatial-vlm.github.io/) | |
| _Visual Affordance_|
| [**RAM: Retrieval-Based Affordance Transfer for Generalizable Zero-Shot Robotic Manipulation**](https://arxiv.org/abs/2407.04689) | CoRL 2024 | 2024-07-05 | [Github](https://github.com/yxKryptonite/RAM_code) | |
| [**MOKA: Open-World Robotic Manipulation through Mark-Based Visual Prompting**](https://arxiv.org/abs/2403.03174) | RSS 2024 | 2024-03-05 | [Github](https://github.com/moka-manipulation/moka) |  |
| [**SLAP: Spatial-Language Attention Policies**](https://arxiv.org/abs/2304.11235) | CoRL 2023 | 2023-04-21 | [Github](https://github.com/facebookresearch/home-robot/tree/main/projects/slap_manipulation) | |
| [**KITE: Keypoint-Conditioned Policies for Semantic Manipulation**](https://arxiv.org/abs/2306.16605) | CoRL 2023 | 2023-06-29 | [Project](https://sites.google.com/view/kite-website/home) | |
| [HULC++: **Grounding Language with Visual Affordances over Unstructured Data**](https://arxiv.org/abs/2210.01911) | ICRA 2023 | 2022-10-04 | [Github](https://github.com/mees/hulc2) | IL, RepL, Language Goal, Poliy Head, Visual Affordance  |
| [**CLIPort: What and Where Pathways for Robotic Manipulation**](https://arxiv.org/abs/2109.12098) | CoRL 2022 | 2021-09-24 | [Github](https://github.com/cliport/cliport) | |
| [**Affordance Learning from Play for Sample-Efficient Policy Learning**](https://arxiv.org/abs/2203.00352) | ICRA 2022 | 2022-03-01 | [Project](http://vapo.cs.uni-freiburg.de/) | RepL, RL, Object-Centric |
| [**Transporter Networks: Rearranging the Visual World for Robotic Manipulation**](https://arxiv.org/abs/2010.14406) | CoRL 2020 | 2020-10-27 | [Github](https://github.com/google-research/ravens) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.14-3D Representation for Manipulation ******* -->
### 3D Representation for Manipulation
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**MSGField: A Unified Scene Representation Integrating Motion, Semantics, and Geometry for Robotic Manipulation**](https://arxiv.org/abs/2410.15730) | arXiv | 2024-10-21 | [Github](https://github.com/ShengYu724/MSGField) | 2DGS |
| [**Splat-MOVER: Multi-Stage, Open-Vocabulary Robotic Manipulation via Editable Gaussian Splatting**](https://arxiv.org/abs/2405.04378) | arXiv | 2024-05-07 | [Github](https://github.com/StanfordMSL/Splat-MOVER) | 3DGS |
| [**IMAGINATION POLICY: Using Generative Point Cloud Models for Learning Manipulation Policies**](https://arxiv.org/abs/2406.11740) | CoRL 2024 | 2024-06-17 | [Project](https://haojhuang.github.io/imagine_page/) |  |
| [**Physically Embodied Gaussian Splatting: A Realtime Correctable World Model for Robotics**](https://arxiv.org/abs/2406.10788) | CoRL 2024 | 2024-06-16 | [Dataset](https://huggingface.co/datasets/anon211/embodied_gaussians/tree/main) | 3DGS |
| [**RiEMann: Near Real-Time SE(3)-Equivariant Robot Manipulation without Point Cloud Segmentation**](https://arxiv.org/abs/2403.19460) | CoRL 2024 | 2024-03-28 | [Github](https://github.com/HeegerGao/RiEMann) |  |
| [**RoboEXP: Action-Conditioned Scene Graph via Interactive Exploration for Robotic Manipulation**](https://arxiv.org/abs/2402.15487) | CoRL 2024 | 2024-02-23 | [Github](https://github.com/Jianghanxiao/RoboEXP) | 3D reasoning, action-conditioned scene graph (ACSG) task |
| [**D<sup>3</sup>Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Rearrangement**](https://arxiv.org/abs/2309.16118) | CoRL 2024 | 2023-09-28 | [Github](https://github.com/WangYixuan12/d3fields) |  |
| [**Object-Aware Gaussian Splatting for Robotic Manipulation**](https://openreview.net/pdf?id=gdRI43hDgo) | ICRAW 2024 | - | [Project](https://object-aware-gaussian.github.io/) | 3DGS |
| [**Distilled Feature Fields Enable Few-Shot Language-Guided Manipulation**](https://arxiv.org/abs/2308.07931) | CoRL 2023 | 2023-07-27 | [Github](https://github.com/f3rm/f3rm) | NeRF |
| [**Neural Descriptor Fields: SE(3)-Equivariant Object Representations for Manipulation**](https://arxiv.org/abs/2112.05124) | ICRA 2022 | 2021-12-09 | [Github](https://github.com/anthonysimeonov/ndf_robot) |  |
| [**SE(3)-Equivariant Relational Rearrangement with Neural Descriptor Fields**](https://arxiv.org/abs/2211.09786) | CORL 2022 | 2022-11-17 | [Github](https://github.com/anthonysimeonov/relational_ndf) |  |

<!-- ******* 1.3.15-3D Representation Policy Learning ******* -->
### 3D Representation Policy Learning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| _Diffusion Policy (DP)_|
| [**3D Diffuser Actor: Policy Diffusion with 3D Scene Representations**](https://arxiv.org/abs/2402.10885) | CoRL 2024 | 2024-02-16 | [Github](https://github.com/nickgkan/3d_diffuser_actor) |  |
| [DP3: **3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations**](https://arxiv.org/abs/2403.03954) | RSS 2024 | 2024-03-06 | [Github](https://github.com/YanjieZe/3D-Diffusion-Policy) |  |
| Reconstruction |
| [**ManiGaussian: Dynamic Gaussian Splatting for Multi-task Robotic Manipulation**](https://arxiv.org/abs/2403.08321) | ECCV 2024 | 2024-03-13 | [Github](https://github.com/GuanxingLu/ManiGaussian) | 3DGS, IL, Language Goal, Reconstruction/Prediction |
| [SGRv2: **Leveraging Locality to Boost Sample Efficiency in Robotic Manipulation**](https://arxiv.org/abs/2406.10615) | CoRL 2024 | 2024-06-15 | [Github](https://github.com/TongZhangTHU/sgr) |  |
| [**GNFactor: Multi-Task Real Robot Learning with Generalizable Neural Feature Fields**](https://arxiv.org/abs/2308.16891) | CoRL 2023 | 2023-08-31 | [Github](https://github.com/YanjieZe/GNFactor) | NeRF, IL, Language Goal, Reconstruction |
| [**Visual Reinforcement Learning with Self-Supervised 3D Representations**](https://arxiv.org/abs/2210.07241) | RA-L 2023 | 2022-10-13 | [Github](https://github.com/YanjieZe/rl3d) | RL, RepL, Reconstruction, Image Goal |
| [**PolarNet: 3D Point Clouds for Language-Guided Robotic Manipulation**](https://arxiv.org/abs/2309.15596) | CoRL 2023 | 2023-09-27 | [Github](https://github.com/vlc-robot/polarnet) |  |
| [**M2T2: Multi-Task Masked Transformer for Object-centric Pick and Place**](https://arxiv.org/abs/2311.00926) | CoRL 2023 | 2023-11-02 | [Github](https://github.com/NVlabs/M2T2) |  |
| [PerAct: **Perceiver-Actor: A Multi-Task Transformer for Robotic Manipulation**](https://arxiv.org/abs/2209.05451) | CoRL 2022 | 2022-09-12 | [Github](https://github.com/peract/peract) | PerAct |
| _Visual Goal Generation_ |
| [**3D-MVP: 3D Multiview Pretraining for Robotic Manipulation**](https://arxiv.org/abs/2406.18158) | CoRL 2024 | 2024-06-26 | [Project](https://jasonqsy.github.io/3DMVP/) |  |
| [**SAM-E: Leveraging Visual Foundation Model with Sequence Imitation for Embodied Manipulation**](https://arxiv.org/abs/2405.19586) | ICML 2024 | 2024-05-30 | [Github](https://github.com/pipixiaqishi1/SAM-E) |  |
| [**RVT: Robotic View Transformer for 3D Object Manipulation**](https://arxiv.org/abs/2306.14896) | CoRL 2023 | 2023-06-26 | [Github](https://github.com/nvlabs/rvt) |  |
| [**Learning Generalizable Manipulation Policies with Object-Centric 3D Representations**](https://arxiv.org/abs/2310.14386) | CoRL 2023 | 2023-10-22 | [Github](https://github.com/UT-Austin-RPL/GROOT) | IL, RepL, TP, Object-Centric, PC |
| [SGR: **A Universal Semantic-Geometric Representation for Robotic Manipulation**](https://arxiv.org/abs/2306.10474) | CoRL 2023 | 2023-06-18 | [Github](https://github.com/TongZhangTHU/sgr) |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.16-Reasoning, Planning and Code Generation ******* -->
### Reasoning, Planning and Code Generation
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| _Task Planning_ |
| [**AHA: A Vision-Language-Model for Detecting and Reasoning Over Failures in Robotic Manipulation**](https://arxiv.org/abs/2410.00371) | arXiv | 2024-10-01 | [Project](https://aha-vlm.github.io/) | VLMs, Failure Detection |
| [**REFLECT: Summarizing Robot Experiences for Failure Explanation and Correction**](https://arxiv.org/abs/2306.15724) | CoRL 2023 | 2023-06-27 | [Github](https://github.com/real-stanford/reflect) | |
| [**Polaris: Open-ended Interactive Robotic Manipulation via Syn2Real Visual Grounding and Large Language Models**](https://arxiv.org/abs/2408.07975) | IROS 2024 | 2024-08-15 | [Project](https://star-uu-wang.github.io/Polaris/) |  |
| [**Physically Grounded Vision-Language Models for Robotic Manipulation**](https://arxiv.org/abs/2309.02561) | ICRA 2024 | 2023-09-05 | [Project](https://iliad.stanford.edu/pg-vlm/) |  |
| [**Socratic Planner: Inquiry-Based Zero-Shot Planning for Embodied Instruction Following**](https://arxiv.org/abs/2404.15190) | arXiv | 2024-04-21 | - | |
| [Saycan: **Do As I Can, Not As I Say: Grounding Language in Robotic Affordances**](https://arxiv.org/abs/2204.01691) | CoRL 2023 | 2024-04-04 | [Github](https://github.com/google-research/google-research/tree/master/saycan) | |
| [**LLM+P: Empowering Large Language Models with Optimal Planning Proficiency**](https://arxiv.org/abs/2304.11477) | arXiv | 2023-04-22 | [Github](https://github.com/Cranial-XIX/llm-pddl) | |
| [**Inner Monologue: Embodied Reasoning through Planning with Language Models**](https://arxiv.org/abs/2207.05608) | CoRL 2022 | 2022-07-12 | [Project](https://innermonologue.github.io/) | |
| [**Teaching Robots with Show and Tell: Using Foundation Models to Synthesize Robot Policies from Language and Visual Demonstrations**](https://openreview.net/pdf?id=G8UcwxNAoD) | CoRL 2024 | - | [Project](https://robo-showtell.github.io/) |  |
| [**RoCo: Dialectic Multi-Robot Collaboration with Large Language Models**](https://arxiv.org/abs/2307.04738) | ICRA 2024 | 2023-07-10 | [Github](https://github.com/MandiZhao/robot-collab) | |
| [**Gesture-Informed Robot Assistance via Foundation Models**](https://arxiv.org/abs/2309.02721) | CoRL 2023 | 2023-09-06 | [Project](https://sites.google.com/view/giraf23) | |
| _Code Generation_ |
| [**Instruct2Act: Mapping Multi-modality Instructions to Robotic Actions with Large Language Model**](https://arxiv.org/abs/2305.11176) | arXiv | 2023-05-18 | [Github](https://github.com/OpenGVLab/Instruct2Act) | LLMs, VLMs, Code Generation |
| [**ProgPrompt: Generating Situated Robot Task Plans using Large Language Models**](https://arxiv.org/abs/2209.11302) | ICRA 2023 | 2022-09-22 | [Github](https://github.com/NVlabs/progprompt-vh) | LLMs, Code Generation |
| [**ChatGPT for Robotics: Design Principles and Model Abilities**](https://arxiv.org/abs/2306.17582) | IEEE Access 2023 | 2023-02-20 | [Github](https://github.com/microsoft/PromptCraft-Robotics) | LLMs, Code Generation |
| [**Code as Policies: Language Model Programs for Embodied Control**](https://arxiv.org/abs/2209.07753) | ICRA 2023 | 2022-09-16 | [Github](https://github.com/google-research/google-research/tree/master/code_as_policies) | LLMs, Code Generation |
| [**TidyBot: Personalized Robot Assistance with Large Language Models**](https://arxiv.org/abs/2305.05658) | Autonomous Robots 2023 | 2023-05-09 | [Github](https://github.com/jimmyyhwu/tidybot) | LLMs, Code Generation |
| [**Statler: State-Maintaining Language Models for Embodied Reasoning**](https://arxiv.org/abs/2306.17840) | ICRA 2024 | 2023-06-30 | [Github](https://github.com/ripl/statler) | LLMs, Code Generation |
| [**InterPreT: Interactive Predicate Learning from Language Feedback for Generalizable Task Planning**](https://arxiv.org/abs/2405.19758) | RSS 2024 | 2023-05-30 | [Github](https://github.com/hmz-15/interactive-predicate-learning) | Code Generation, Task Planning, PDDL |
| [**Text2Motion: From Natural Language Instructions to Feasible Plans**](https://arxiv.org/abs/2303.12153) | Autonomous Robots 2023 | 2023-03-21 | [Project](https://sites.google.com/stanford.edu/text2motion) |  |
| _Multimodal Reasoning_ |
| _Task Success Prediction_ |
| [**AHA: A Vision-Language-Model for Detecting and Reasoning Over Failures in Robotic Manipulation**](https://arxiv.org/abs/2410.00371) | arXiv | 2024-10-01 | [Project](https://aha-vlm.github.io/) | VLMs, Failure Detection |
| [**Task Success Prediction for Open-Vocabulary Manipulation Based on Multi-Level Aligned Representations**](https://arxiv.org/abs/2410.00436) | CoRL 2024 | 2024-10-01 | [Project](https://lambda-repformer-project-pa-eziy1.kinsta.page/) | RepL, Multi-level, E-D TP, Both Goals |
| [**EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought**](https://arxiv.org/abs/2305.15021) | NeurIPS 2023 | 2023-05-24 | [Github](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch) |  |
| [**ManipLLM: Embodied Multimodal Large Language Model for Object-Centric Robotic Manipulation**](https://arxiv.org/abs/2312.16217) | CVPR 2024 | 2023-12-24 | [Github](https://github.com/clorislili/ManipLLM) |  |
| [**Chat with the Environment: Interactive Multimodal Perception Using Large Language Models**](https://arxiv.org/abs/2303.08268) | IROS 2023 | 2023-03-14 | [Github](https://github.com/xf-zhao/Matcha-agent) |  |
| [**PaLM-E: An Embodied Multimodal Language Model**](https://arxiv.org/abs/2303.03378) | IROS 2023 | 2023-03-06 | [Github](https://github.com/kyegomez/PALM-E) |  |
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
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| _Generalization with Data_ |
| [**Mirage: Cross-Embodiment Zero-Shot Policy Transfer with Cross-Painting**](https://arxiv.org/abs/2402.19249) | RSS 2024 | 2024-02-29 | [Github](https://github.com/BerkeleyAutomation/mirage) |  |
| [**Decomposing the Generalization Gap in Imitation Learning for Visual Robotic Manipulation**](https://arxiv.org/abs/2307.03659) | ICRA 2024 | 2024-02-29 | [Github](https://github.com/RLAgent/factor-world) |  
| _Compositional Generalization_ |
| [**Policy Architectures for Compositional Generalization in Control**](https://arxiv.org/abs/2203.05960) | NeurIPSW 2022 | 2022-03-10 | [Github](https://github.com/facebookresearch/entity-factored-rl) | Compositional Generalization |
| [**Programmatically Grounded, Compositionally Generalizable Robotic Manipulation**](https://arxiv.org/abs/2304.13826) | ICLR 2023 | 2023-04-26 | [Project](https://progport.github.io/) | Compositional Generalization |
| [**Efficient Data Collection for Robotic Manipulation via Compositional Generalization**](https://arxiv.org/abs/2403.05110) | RSS 2024 | 2024-03-08 | [Project](https://iliad.stanford.edu/robot-data-comp/) | Compositional Generalization |
| _Sim2Real Generalization_ |
| [**Natural Language Can Help Bridge the Sim2Real Gap**](https://arxiv.org/abs/2405.10020) | RSS 2024 | 2024-05-16 | [Github](https://github.com/UT-Austin-RobIn/lang4sim2real) |  |
| [**Reconciling Reality through Simulation: A Real-to-Sim-to-Real Approach for Robust Manipulation**](https://arxiv.org/abs/2403.03949) | RSS 2024 | 2024-03-06 | [Github](https://github.com/real-to-sim-to-real/RialToPolicyLearning) |  |
| _Generalization for Long-horizon and Complex Task_ |
| [**A Backbone for Long-Horizon Robot Task Understanding**](https://arxiv.org/abs/2408.01334) | arXiv | 2024-08-02 | [Project](https://sites.google.com/view/therbligsbasedbackbone/home) | |
| [**STAP: Sequencing Task-Agnostic Policies**](https://arxiv.org/abs/2210.12250) | ICRA 2023 | 2022-10-21 | [Github](https://github.com/agiachris/STAP) |  |
| [BOSS: **Bootstrap Your Own Skills: Learning to Solve New Tasks with Large Language Model Guidance**](https://arxiv.org/abs/2310.10021) | CoRL 2023 | 2023-12-16 | [Github](https://github.com/clvrai/boss) | Skill Bootstrapping |
| [**Learning Compositional Behaviors from Demonstration and Language**](https://openreview.net/pdf?id=fR1rCXjCQX) | CoRL 2024 | 2024 | - | IL, RepL, Poliy Head, Few-Shot Policy Adaptation |
| [**Policy Adaptation via Language Optimization: Decomposing Tasks for Few-Shot Imitation**](https://arxiv.org/abs/2408.16228) | CoRL 2024 | 2024-08-29 | [Github](https://github.com/vivekmyers/palo) | Fine-grained Atom Action |

<!-- ******* 1.3.18-Generalization ******* -->
### Generalist
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| _Generalist with Different Embodiment Types_ |
| [**Scaling Cross-Embodied Learning: One Policy for Manipulation, Navigation, Locomotion and Aviation**](https://arxiv.org/abs/2408.11812) | CoRL 2024 | 2024-08-21 | [Github](https://github.com/rail-berkeley/crossformer) | Cross-Embodied |
| [**All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents**](https://arxiv.org/abs/2408.10899) | arXiv | 2024-08-20 | [Project](https://imaei.github.io/project_pages/ario/) | Cross-Embodied |
| [**Scaling Proprioceptive-Visual Learning with Heterogeneous Pre-trained Transformers**](https://arxiv.org/abs/2409.20537) | NeurIPS 2024 | 2024-09-30 | [Github](https://github.com/liruiw/HPT) |  |
| _Generalist in Different Embodied Tasks_|
| [**An Embodied Generalist Agent in 3D World**](https://arxiv.org/abs/2311.12871) | ICML 2024 | 2023-11-18 | [Github](https://github.com/embodied-generalist/embodied-generalist) |  |
| _Manipulation Generalist_|
| [**Octo: An Open-Source Generalist Robot Policy**](https://arxiv.org/abs/2405.12213) | RSS 2024 | 2024-05-20 | [Github](https://github.com/octo-models/octo) | |
| [**Steering Your Generalists: Improving Robotic Foundation Models via Value Guidance**](https://arxiv.org/abs/2410.13816) | CoRL 2024 | 2024-10-17 | [Project](https://nakamotoo.github.io/V-GPS/index.html) |  |
| [**Towards Synergistic, Generalized, and Efficient Dual-System for Robotic Manipulation**](https://arxiv.org/abs/2410.08001) | CoRL 2024 | 2024-10-10 | [Project](https://opendrivelab.com/RoboDual/) |  |
| [**Open X-Embodiment: Robotic Learning Datasets and RT-X Models**](https://arxiv.org/abs/2310.08864) | ICRA 2024 | 2023-10-13 | [Github](https://github.com/google-deepmind/open_x_embodiment) | |
| [**Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning**](https://arxiv.org/abs/2407.15815) | CoRL 2024 | 2024-07-22 | [Project](https://gemcollector.github.io/maniwhere/) |  |
| [**CAGE: Causal Attention Enables Data-Efficient Generalizable Robotic Manipulation**](https://arxiv.org/abs/2407.15815) | arXiv | 2024-10-19 | [Project](https://cage-policy.github.io/) |  |
| [**Robot Utility Models: General Policies for Zero-Shot Deployment in New Environments**](https://arxiv.org/abs/2409.05865) | arXiv | 2024-09-09 | [Github](https://github.com/haritheja-e/robot-utility-models/) |  |
| More for [VLAs](#vision-language-action-models) |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.19-Human-Robot Interaction and Collaboration ******* -->
### Human-Robot Interaction and Collaboration
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Vocal Sandbox: Continual Learning and Adaptation for Situated Human-Robot Collaboration**](https://openreview.net/pdf?id=ypaYtV1CoG) | CoRL 2024 | - | [Project](https://vocal-sandbox.github.io/) |  |
| [**APRICOT: Active Preference Learning and Constraint-Aware Task Planning with LLMs**](https://openreview.net/pdf?id=nQslM6f7dW) | CoRL 2024 | - | [Project](https://portal-cornell.github.io/apricot/) |  |
| [**Text2Interaction: Establishing Safe and Preferable Human-Robot Interaction**](https://arxiv.org/abs/2408.06105) | CoRL 2024 | 2024-08-12 | [Github](https://github.com/JakobThumm/text2interaction) |  |
| [KNOWNO: **Robots That Ask For Help: Uncertainty Alignment for Large Language Model Planners**](https://arxiv.org/abs/2307.01928) | CoRL 2023 | 2023-07-04 | [Github](https://github.com/google-research/google-research/tree/master/language_model_uncertainty) | HRI, Task Planning |
| [**Yell At Your Robot: Improving On-the-Fly from Language Corrections**](https://arxiv.org/abs/2403.12910) | arXiv | 2024-03-19 | [Github](https://github.com/yay-robot/yay_robot) | |
| [**"No, to the Right" -- Online Language Corrections for Robotic Manipulation via Shared Autonomy**](https://arxiv.org/abs/2301.02555) | HRI 2023 | 2023-01-06 | [Github](https://github.com/Stanford-ILIAD/lilac) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.20-Human-Robot Interaction and Collaboration ******* -->
### Mobile Manipulation
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**TaMMa: Target-driven Multi-subscene Mobile Manipulation**](https://openreview.net/pdf?id=EiqQEsOMZt) | CoRL 2024 | - | - |
| [**SayPlan: Grounding Large Language Models using 3D Scene Graphs for Scalable Robot Task Planning**](https://arxiv.org/abs/2307.06135) | CoRL 2023 | 2024-07-12 | [Project](https://sayplan.github.io/) |
| [**GAMMA: Graspability-Aware Mobile MAnipulation Policy Learning based on Online Grasping Pose Fusion**](https://arxiv.org/abs/2309.15459) | ICRA 2024 | 2023-09-27 | [Github](https://github.com/user432/gamma) |
| [**Robi Butler: Remote Multimodal Interactions with Household Robot Assistant**](https://arxiv.org/abs/2409.20548) | arXiv | 2024-09-30 | [Project](https://robibutler.github.io/) |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!--
## Humanoid
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**OKAMI: Teaching Humanoid Robots Manipulation Skills through Single Video Imitation**](https://arxiv.org/abs/2410.11792) | CoRL 2024 | 2024-10-15 | [Project](https://ut-austin-rpl.github.io/OKAMI/)  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>
-->

<!-- ******* 1.3.21-Tactile ******* -->
### Tactile
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**MimicTouch: Leveraging Multi-modal Human Tactile Demonstrations for Contact-rich Manipulation**](https://arxiv.org/abs/2310.16917) | CoRL 2024 | 2023-10-25 | [Project](https://sites.google.com/view/MimicTouch)  |
| [**Octopi: Object Property Reasoning with Large Tactile-Language Models**](https://arxiv.org/abs/2405.02794) | RSS 2024 | 2024-05-05 | [Github](https://github.com/clear-nus/octopi)  |
| [**RoboPack: Learning Tactile-Informed Dynamics Models for Dense Packing**](https://arxiv.org/abs/2407.01418) | RSS 2024 | 2024-07-01 | [Project](https://robo-pack.github.io/)  |
| [**General In-Hand Object Rotation with Vision and Touch**](https://arxiv.org/abs/2309.09979) | CoRL 2023 | 2023-09-18 | [Project](https://haozhi.io/rotateit/)  |
| [**Dexterity from Touch: Self-Supervised Pre-Training of Tactile Representations with Robotic Play**](https://arxiv.org/abs/2303.12076) | CoRL 2023 | 2023-03-21 | [Github](https://github.com/irmakguzey/tactile-dexterity)  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.22-Dexterous Manipulation ******* -->
### Dexterous Manipulation
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Bunny-VisionPro: Real-Time Bimanual Dexterous Teleoperation for Imitation Learning**](https://arxiv.org/abs/2407.03162) | arXiv | 2024-07-03 | [Github](https://github.com/Dingry/BunnyVisionPro) |
| [**DexGraspNet 2.0: Learning Generative Dexterous Grasping in Large-scale Synthetic Cluttered Scenes**](https://openreview.net/attachment?id=5W0iZR9J7h&name=pdf) | CoRL 2024 | 2024 | - |
| [**DexGraspNet: A Large-Scale Robotic Dexterous Grasp Dataset for General Objects Based on Simulation**](https://arxiv.org/abs/2210.02697) | ICRA 2023 | 2022-10-06 | [Github](https://github.com/PKU-EPIC/DexGraspNet)  | |
| [**Demonstrating Learning from Humans on Open-Source Dexterous Robot Hands**](https://www.roboticsproceedings.org/rss20/p014.pdf) | RSS 2024 | 2024 | [Github](https://github.com/PKU-EPIC/DexGraspNet)  | |
| [**CyberDemo: Augmenting Simulated Human Demonstration for Real-World Dexterous Manipulation**](https://arxiv.org/abs/2402.14795) | CVPR 2024 | 2024-02-22 | [Github](https://github.com/wang59695487/hand_teleop_real_sim_mix_adr)  | |
| [**Dexterous Functional Grasping**](https://arxiv.org/abs/2312.02975) | CoRL 2023 | 2023-12-05 | [Project](https://dexfunc.github.io/)  | |
| [**DEFT: Dexterous Fine-Tuning for Real-World Hand Policies**](https://arxiv.org/abs/2310.19797) | CoRL 2023 | 2023-10-30 | [Project](https://dexterous-finetuning.github.io/)  | |
| [**REBOOT: Reuse Data for Bootstrapping Efficient Real-World Dexterous Manipulation**](https://arxiv.org/abs/2309.03322) | CoRL 2023 | 2023-09-06 | [Project](https://sites.google.com/view/reboot-dexterous)  | |
| [**Sequential Dexterity: Chaining Dexterous Policies for Long-Horizon Manipulation**](https://arxiv.org/abs/2309.00987) | CoRL 2023 | 2023-09-02 | [Github](https://github.com/sequential-dexterity/SeqDex)  | |
| [**AnyTeleop: A General Vision-Based Dexterous Robot Arm-Hand Teleoperation System**](https://arxiv.org/abs/2307.04577) | RSS 2023 | 2023-07-10 | [Project](https://yzqin.github.io/anyteleop/)  | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 1.3.23-Other Applications ******* -->
### Other Applications
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| _Deformable Object Manipulation_ |
| [**HANDLOOM: Learned Tracing of One-Dimensional Objects for Inspection and Manipulation**](https://arxiv.org/abs/2303.08975) | CoRL 2023 | 2023-03-15 | [Project](https://github.com/vainaviv/handloom)  |
| _Stowing Tasks_ |
| [**Predicting Object Interactions with Behavior Primitives: An Application in Stowing Tasks**](https://arxiv.org/abs/2309.16873) | CoRL 2023 | 2023-09-28 | [Github](https://github.com/haonan16/Stow/)  |
| _Object Rearrangement_ |
| [**LGMCTS: Language-Guided Monte-Carlo Tree Search for Executable Semantic Object Rearrangement**](https://arxiv.org/abs/2309.15821) | IROS 2024 | 2023-09-27  | [Github](https://github.com/changhaonan/LGMCTS-D)  |
| [**Task and Motion Planning with Large Language Models for Object Rearrangement**](https://arxiv.org/abs/2303.06247) | IROS 2023 | 2023-03-10 | [Colab](https://colab.research.google.com/drive/1cSqoSc6Gk9KM9p-GwHSIIL5VfZICGW3B?usp=sharing)  |
| [**DALL-E-Bot: Introducing Web-Scale Diffusion Models to Robotics**](https://arxiv.org/abs/2210.02438) | RA-L 2023 | 2022-10-05 | [Project](https://www.robot-learning.uk/)  |
| _Human-to-Robot Handover_ |
| [**GenH2R: Learning Generalizable Human-to-Robot Handover via Scalable Simulation, Demonstration, and Imitation**](https://arxiv.org/abs/2401.00929) | CVPR 2024 | 2024-01-01  | [Github](https://github.com/chenjy2003/genh2r)  |
| _Cook_ |
| [**RoboCook: Long-Horizon Elasto-Plastic Object Manipulation with Diverse Tools**](https://arxiv.org/abs/2306.14447) | CoRL 2023 | 2023-06-26  | [Github](https://github.com/hshi74/robocook)  |
| _Non-prehensile Manipulation_ |
| [**RoboCook: Long-Horizon Elasto-Plastic Object Manipulation with Diverse Tools**](https://arxiv.org/abs/2305.03942) | CoRL 2023 | 2023-05-06  | [Github](https://github.com/HACMan-2023/HACMan)  |
| _Feed_ |
| [**Learning Sequential Acquisition Policies for Robot-Assisted Feeding**](https://arxiv.org/abs/2309.05197) | CoRL 2023 | 2023-09-11  | [Github](https://sites.google.com/view/vaporsbot)  |
| _Tool Manipulation_ |
| [**Leveraging Language for Accelerated Learning of Tool Manipulation**](https://arxiv.org/abs/2206.13074) | CoRL 2023 | 2022-06-27 | [Github](https://github.com/irom-lab/ATLA) | Tool Manipulation |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


<!-- ******* 2-Benchmarks ******* -->
# Awesome Benchmarks

<!-- ******* 2.1-Grasp Datasets ******* -->
## Grasp Datasets
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Real-to-Sim Grasp: Rethinking the Gap between Simulation and Real World in Grasp Detection**](https://arxiv.org/abs/2410.06521) | CoRL 2024 | 2024-10-09 | [Project](https://isee-laboratory.github.io/R2SGrasp/) | |
| [**Language-Driven 6-DoF Grasp Detection Using Negative Prompt Guidance**](https://arxiv.org/abs/2407.13842) | ECCV 2024 | 2024-07-18 | [Github](https://github.com/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance) | Grasp-Anything-6D |
| [**Language-driven Grasp Detection**](https://arxiv.org/abs/2406.09489) | CVPR 2024 | 2024-06-13 | [Github](https://github.com/Fsoft-AIC/LGD) | Grasp-Anything++ |
| [**Grasp-Anything: Large-scale Grasp Dataset from Foundation Models**](https://arxiv.org/abs/2309.09818) | ICRA 2024 | 2023-09-18 | [Github](https://github.com/Fsoft-AIC/Grasp-Anything) | Grasp-Anything |
| [**GraspNet-1Billion: A Large-Scale Benchmark for General Object Grasping**](https://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_GraspNet-1Billion_A_Large-Scale_Benchmark_for_General_Object_Grasping_CVPR_2020_paper.pdf) | CVPR 2020 | 2020 | [Github](https://github.com/graspnet/graspnet-baseline) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 2.2-Manipulation Benchmarks ******* -->
## Manipulation Benchmarks
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| _Manipulation in Home Environment_ |
| [**RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots**](https://arxiv.org/abs/2406.02523) | RSS 2024 | 2024-06-04 | [Github](https://github.com/robocasa/robocasa) |  |
| [**ARNOLD: A Benchmark for Language-Grounded Task Learning With Continuous States in Realistic 3D Scenes**](https://arxiv.org/abs/2304.04321) | ICCV 2023 | 2023-04-09 | [Github](https://github.com/arnold-benchmark/arnold) | |
| [**HomeRobot: Open-Vocabulary Mobile Manipulation**](https://arxiv.org/abs/2306.11565) | CoRL 2023 | 2023-06-20 | [Github](https://github.com/facebookresearch/home-robot) | |
| [**ALFRED: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks**](https://arxiv.org/abs/1912.01734) | CVPR 2020 | 2019-12-03 | [Github](https://github.com/askforalfred/alfred) | |
| _Manipulation in On-Table Environment_ |
| [**GenSim2: Scaling Robot Data Generation with Multi-modal and Reasoning LLMs**](https://arxiv.org/abs/2410.03645) | CoRL 2024 | 2024-10-04 | [Github](https://github.com/GenSim2/gensim2) |
| [**THE COLOSSEUM: A Benchmark for Evaluating Generalization for Robotic Manipulation**](https://arxiv.org/abs/2402.08191) | RSS 2024 | 2024-02-13 | [Github](https://github.com/robot-colosseum/robot-colosseum) | |
| [**VIMA: General Robot Manipulation with Multimodal Prompts**](https://arxiv.org/abs/2210.03094) | ICML 2023 | 2022-10-06 | [Github](https://github.com/vimalabs/VIMA) | |
| [**CALVIN: A Benchmark for Language-Conditioned Policy Learning for Long-Horizon Robot Manipulation Tasks**](https://arxiv.org/abs/2112.03227) | RA-L 2021 | 2021-12-06 | [Github](https://github.com/mees/calvin) | |
| [**RLBench: The Robot Learning Benchmark & Learning Environment**](https://arxiv.org/abs/1909.12271) | RA-L 2020 | 2019-09-26 | [Github](https://github.com/stepjam/RLBench) | |
| [**KitchenShift: Evaluating Zero-Shot Generalization of Imitation-Based Policy Learning Under Domain Shifts**](https://openreview.net/pdf?id=DdglKo8hBq0) | NeurIPSW 2021 | 2021 | [Github](https://github.com/etaoxing/kitchen-shift) |
| [**Evaluating Real-World Robot Manipulation Policies in Simulation**](https://arxiv.org/abs/2405.05941) | CoRL 2024 | 2024-05-09 | [Github](https://github.com/simpler-env/SimplerEnv) | For VLA |
| [**LADEV: A Language-Driven Testing and Evaluation Platform for Vision-Language-Action Models in Robotic Manipulation**](https://arxiv.org/abs/2410.05191) | arXiv | 2024-10-07 | - | For VLA |
| [**ClutterGen: A Cluttered Scene Generator for Robot Learning**](https://arxiv.org/abs/2407.05425) | CoRL 2024 | 2024-07-07 | [Github](https://github.com/generalroboticslab/ClutterGen) |  |
| _Tactile Manipulation_ |
| [**Efficient Tactile Simulation with Differentiability for Robotic Manipulation**](https://openreview.net/pdf?id=6BIffCl6gsM) | CoRL 2022 | 2022 | [Github](https://github.com/eanswer/TactileSimulation) | |
| _Functional Manipulation_ |
| [**FMB: a Functional Manipulation Benchmark for Generalizable Robotic Learning**](https://arxiv.org/abs/2401.08553) | IJRR 2024 | 2024-01-16 | [Github](https://github.com/rail-berkeley/fmb) |
| _Robot Trajectory Datasets_ |
| [**Open X-Embodiment: Robotic Learning Datasets and RT-X Models**](https://arxiv.org/abs/2310.08864) | ICRA 2024 | 2023-10-13 | [Github](https://github.com/google-deepmind/open_x_embodiment) | |
| [**DROID: A Large-Scale In-The-Wild Robot Manipulation Dataset**](https://arxiv.org/abs/2403.12945) | ICRA 2024 | 2024-03-19 | [Project](https://droid-dataset.github.io/) | |
| [**BridgeData V2: A Dataset for Robot Learning at Scale**](https://arxiv.org/abs/2308.12952) | CoRL 2023 | 2024-08-24 | [Github](https://github.com/rail-berkeley/bridge_data_v2) | |
| _Embodied QA Datasets_ |
| [**ManipVQA: Injecting Robotic Affordance and Physically Grounded Information into Multi-Modal Large Language Models**](https://arxiv.org/abs/2403.11289) | IROS 2024 | 2024-03-17 | [Github](https://github.com/SiyuanHuang95/ManipVQA) | |
| [**OpenEQA: Embodied Question Answering in the Era of Foundation Models**](https://open-eqa.github.io/assets/pdfs/paper.pdf) | CVPR 2024 | 2024 | [Github](https://github.com/facebookresearch/open-eqa) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>

<!-- ******* 2.3-Cross-Embodiment Benchmarks ******* -->
## Cross-Embodiment Benchmarks
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| **GENESIS: A generative world for general-purpose robotics & embodied AI learning** | - | - | [Github](https://github.com/Genesis-Embodied-AI/Genesis) |
| [**ManiSkill3: GPU Parallelized Robotics Simulation and Rendering for Generalizable Embodied AI**](https://arxiv.org/abs/2410.00425) | arXiv | 2024-10-01 | [Github](https://github.com/haosulab/ManiSkill) |
| [**All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents**](https://arxiv.org/abs/2408.10899) | arXiv | 2024-08-20 | [Dataset](https://openi.pcl.ac.cn/ARIO/ARIO_Dataset) | |
| [**Where are we in the search for an Artificial Visual Cortex for Embodied Intelligence?**](https://arxiv.org/abs/2408.10899) | arXiv | 2024-08-20 | [Dataset](https://openi.pcl.ac.cn/ARIO/ARIO_Dataset) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


<!-- ******* 3-Techniques ******* -->
# Awesome-techniques
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| **Awesome-Implicit-NeRF-Robotics: [Neural Fields in Robotics: A Survey](https://arxiv.org/abs/2410.20220)** | - | 2024-10-26 | [Github](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics) | |
| **Awesome-Video-Robotic-Papers: [Neural Fields in Robotics: A Survey](https://arxiv.org/abs/2410.20220)** | - | 2024 | [Github](https://github.com/H-Freax/Awesome-Video-Robotic-Papers) | |
| **Awesome-Generalist-Robots-via-Foundation-Models: [Neural Fields in Robotics: A Survey](https://arxiv.org/abs/2312.08782)** | - | 2024 | [Github](https://github.com/JeffreyYH/Awesome-Generalist-Robots-via-Foundation-Models) | |
| **Awesome-Robotics-3D** | - | 2024 | [Github](https://github.com/zubair-irshad/Awesome-Robotics-3D) | |
| **Awesome-Robotics-Foundation-Models: [Foundation Models in Robotics: Applications, Challenges, and the Future](https://arxiv.org/abs/2312.07843)** | - | 2023-12-13 | [Github](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models/tree/main) | |
| **Awesome-LLM-Robotics** | - | 2022 | [Github](https://github.com/GT-RIPL/Awesome-LLM-Robotics) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


 <!-- 
## Large Language Models

## Vision-Language Models

## 3D
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Learning 2D Invariant Affordance Knowledge for 3D Affordance Grounding**](https://arxiv.org/abs/2408.13024) | arXiv | 2024-08-23 | [Github](https://github.com/goxq/MIFAG-code) | |
| [**Mamba3D: Enhancing Local Features for 3D Point Cloud Analysis via State Space Model**](https://arxiv.org/abs/2404.14966) | MM 2024 | 2024-04-23 | [Github](https://github.com/xhanxu/Mamba3D) | |
| [**PointMamba: A Simple State Space Model for Point Cloud Analysis**](https://arxiv.org/abs/2402.10739) | NeuIPS 2024 | 2024-02-16 | [Github](https://github.com/LMD0311/PointMamba) | |
| [**Point Transformer V3: Simpler, Faster, Stronger**](https://arxiv.org/abs/2312.10035) | CVPR 2024 | 2023-12-15 | [Github](https://github.com/Pointcept/PointTransformerV3) | |
| [**Point Transformer V2: Grouped Vector Attention and Partition-based Pooling**](https://arxiv.org/abs/2210.05666) | NeurIPS 2022 | 2022-10-11 | [Github](https://github.com/Pointcept/PointTransformerV2) | |
| [**Point Transformer**](https://arxiv.org/abs/2402.10739) | ICCV 2021 | 2020-12-16 | [Github](https://github.com/POSTECH-CVLab/point-transformer) | |
| [**PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space**](https://arxiv.org/abs/1706.02413) | NeurIPS 2017  | 2017-06-07 | [Github](https://github.com/charlesq34/pointnet2) | |
| [**PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation**](https://arxiv.org/abs/1612.00593) | CVPR 2017 | 2016-12-02 | [Github](https://github.com/charlesq34/pointnet) | |
| [**LERF: Language Embedded Radiance Fields**](https://arxiv.org/abs/2303.09553) | ICCV 2023 | 2023-03-16 | [Github](https://github.com/kerrj/lerf) | |
| [**3D Gaussian Splatting for Real-Time Radiance Field Rendering**](https://arxiv.org/abs/2308.04079) | TOG 2023 | 2023-08-08 | [Github](https://github.com/graphdeco-inria/gaussian-splatting) | |
| [**LangSplat: 3D Language Gaussian Splatting**](https://arxiv.org/abs/2312.16084) | CVPR 2024 | 2023-12-26 | [Github](https://github.com/minghanqin/LangSplat) | |
--> 



## Citation
If you find this repository useful, please consider citing this list:
```
@misc{bai2024roboticsmanipulation,
    title = {Awesome-Robotics-Manipulation},
    author = {Shuanghao Bai},
    journal = {GitHub repository},
    url = {https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation},
    year = {2024},
}
```

