# Awesome-Robotics-Manipulation

 **A Survey on Robot Manipulation**

 ---
<font size=5><center><b> Table of Contents </b> </center></font>
- [Awesome Papers](#awesome-papers)
  - [Survey](#survey)
  - [Policy Learning for Grasp](#policy-learning-for-grasp)
  - [Policy Learning for Manipulation](#policy-learning-for-manipulation)
  - [Robotics for 3D](#robotics-for-3d)
  - [Planning and Reasoning](#planning-and-reasoning)
  - [Generalization and Generalist](#generalization-and-generalist)
- [Awesome Datasets](#awesome-datasets)
- [Awesome Simulators](#awesome-simulators)
---

# Awesome Papers


## Survey
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**A Survey of Embodied Learning for Object-Centric Robotic Manipulation**](https://arxiv.org/abs/2408.11537) | arXiv | 2024-08-21 | [Github](https://github.com/RayYoh/OCRM_survey) | Manipulation |
| [**Aligning Cyber Space with Physical World: A Comprehensive Survey on Embodied AI**](https://arxiv.org/abs/2407.06886) | arXiv | 2024-07-09 | [Github](https://github.com/HCPLab-SYSU/Embodied_AI_Paper_List) | Embodied Agent |
| [**A Survey on Vision-Language-Action Models for Embodied AI**](https://arxiv.org/abs/2405.14093) | arXiv | 2024-05-23 | - | VLA Models |
| [**Teleoperation of Humanoid Robots: A Survey**](https://arxiv.org/abs/2301.04317) | T-RO 2024 | 2023-01-11 | [Project](https://humanoid-teleoperation.github.io/) | Humanoid Robot |




## Policy Learning for Grasp

### 3D
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**GraspNeRF: Multiview-based 6-DoF Grasp Detection for Transparent and Specular Objects Using Generalizable NeRF**](https://arxiv.org/abs/2210.06575) | ICRA 2023 | 2022-10-12 | [Github](https://github.com/PKU-EPIC/GraspNeRF) | |
| [**Language Embedded Radiance Fields for Zero-Shot Task-Oriented Grasping**](https://arxiv.org/abs/2309.07970) | CoRL 2023 | 2023-09-14 | [Github](https://github.com/lerftogo/lerftogo) | |
| [**GaussianGrasper: 3D Language Gaussian Splatting for Open-vocabulary Robotic Grasping**](https://arxiv.org/abs/2403.09637) | RA-L 2024 | 2024-03-14 | [Github](https://github.com/MrSecant/GaussianGrasper) | |






## Policy Learning for Manipulation

### Representation Learning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Task Success Prediction for Open-Vocabulary Manipulation Based on Multi-Level Aligned Representations**](https://arxiv.org/abs/2410.00436) | CoRL 2024 | 2024-10-01 | [Project](https://lambda-repformer-project-pa-eziy1.kinsta.page/) |
| [**Learning Compositional Behaviors from Demonstration and Language**](https://openreview.net/pdf?id=fR1rCXjCQX) | CoRL 2024 | - | - | Fine-grained Atom action |
| [**Contrastive Imitation Learning for Language-guided Multi-Task Robotic Manipulation**](https://arxiv.org/abs/2406.09738) | CoRL 2024 | 2024-06-14 | [Project](https://teleema.github.io/projects/Sigma_Agent/) | |


### Policy Learning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Generative Image as Action Models**](https://arxiv.org/abs/2407.07875) | CoRL 2024 | 2024-07-10 | [Github](https://github.com/MohitShridhar/genima) | GENIMA, diffusion, draw joint-actions |



### Vision Language Action Models
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|


### SE(3)-Equivariant Robot Manipulation
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Generative Image as Action Models**](https://arxiv.org/abs/2403.19460) | CoRL 2024 | 2024-03-28 | [Github](https://github.com/HeegerGao/RiEMann) |  |







## Affordance

### Spatial
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**RoboPoint: A Vision-Language Model for Spatial Affordance Prediction for Robotics**](https://arxiv.org/abs/2406.10721) | CoRL 2024 | 2024-06-15 | [Github](https://github.com/wentaoyuan/RoboPoint) | |

### Articulation
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**A3VLM: Actionable Articulation-Aware Vision Language Model**](https://arxiv.org/abs/2406.07549) | CoRL 2024 | 2024-06-14 | [Github](https://github.com/changhaonan/A3VLM) | |
| [**AIC MLLM: Autonomous Interactive Correction MLLM for Robust Robotic Manipulation**](https://arxiv.org/abs/2406.11548) | CoRL 2024 | 2024-06-17 | [Project](https://sites.google.com/view/aic-mllm) | |





## Robotics for 3D
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**MSGField: A Unified Scene Representation Integrating Motion, Semantics, and Geometry for Robotic Manipulation**]() | arXiv | - | [Github](https://github.com/ShengYu724/MSGField) | 2DGS |
| [**RoboEXP: Action-Conditioned Scene Graph via Interactive Exploration for Robotic Manipulation**](https://arxiv.org/abs/2402.15487) | CoRL 2024 | 2024-02-23 | [Github](https://github.com/Jianghanxiao/RoboEXP) | 3D reasoning, action-conditioned scene graph (ACSG) task |
| [**Physically Embodied Gaussian Splatting: A Realtime Correctable World Model for Robotics**](https://arxiv.org/abs/2406.10788) | CoRL 2024 | 2024-06-16 | [Dataset](https://huggingface.co/datasets/anon211/embodied_gaussians/tree/main) | 3DGS |
| [**3D Diffuser Actor: Policy Diffusion with 3D Scene Representations**](https://arxiv.org/abs/2402.10885) | CoRL 2024 | 2024-02-16 | [Github](https://github.com/nickgkan/3d_diffuser_actor) |  |
| [**3D-MVP: 3D Multiview Pretraining for Robotic Manipulation**](https://arxiv.org/abs/2402.10885) | CoRL 2024 | 2024-06-26 | [Project](https://jasonqsy.github.io/3DMVP/) | 3D-MVP |
| [**3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations**](https://arxiv.org/abs/2403.03954) | RSS 2024 | 2024-03-06 | [Github](https://github.com/YanjieZe/3D-Diffusion-Policy) | DP3 |
| [**Visual Reinforcement Learning with Self-Supervised 3D Representations**](https://arxiv.org/abs/2210.07241) | RA-L 2023 | 2022-10-13 | [Github](https://github.com/YanjieZe/rl3d) |  |
| [**Distilled Feature Fields Enable Few-Shot Language-Guided Manipulation**](https://arxiv.org/abs/2308.07931) | CoRL 2023 | 2023-07-27 | [Github](https://github.com/f3rm/f3rm) |  |
| [**Object-Aware Gaussian Splatting for Robotic Manipulation**](https://openreview.net/pdf?id=gdRI43hDgo) | ICRAW 2024 | - | [Project](https://object-aware-gaussian.github.io/) |  |
| [**Splat-MOVER: Multi-Stage, Open-Vocabulary Robotic Manipulation via Editable Gaussian Splatting**](https://openreview.net/pdf?id=gdRI43hDgo) | arXiv | 2024-05-07 | [Github](https://github.com/StanfordMSL/Splat-MOVER) |  |
| [**GNFactor: Multi-Task Real Robot Learning with Generalizable Neural Feature Fields**](https://arxiv.org/abs/2308.16891) | CoRL 2023 | 2023-08-31 | [Github](https://github.com/YanjieZe/GNFactor) |  |
| [**ManiGaussian: Dynamic Gaussian Splatting for Multi-task Robotic Manipulation**](https://arxiv.org/abs/2403.08321) | ECCV 2024 | 2024-03-13 | [Github](https://github.com/GuanxingLu/ManiGaussian) |  |






## Planning and Reasoning

### Language Planning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|


### Code Planning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|




## Generalization and Generalist
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents**](https://arxiv.org/abs/2408.10899) | arXiv | 2024-08-20 | [Dataset](https://openi.pcl.ac.cn/ARIO/ARIO_Dataset) | |
| [**An Embodied Generalist Agent in 3D World**](https://arxiv.org/abs/2311.12871) | ICML 2024 | 2023-11-18 | [Github](https://github.com/embodied-generalist/embodied-generalist) |  |
| [**Steering Your Generalists: Improving Robotic Foundation Models via Value Guidance**](https://arxiv.org/abs/2410.13816) | CoRL 2024 | 2024-10-17 | [Project](https://nakamotoo.github.io/V-GPS/index.html) |  |



## Mobile Manipulation
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**TaMMa: Target-driven Multi-subscene Mobile Manipulation**](https://openreview.net/pdf?id=EiqQEsOMZt) | CoRL 2024 | - | - |



# Awesome-datasets



# Awesome-simulators
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**GenSim2: Scaling Robot Data Generation with Multi-modal and Reasoning LLMs**](https://arxiv.org/abs/2410.03645) | CoRL 2024 | 2024-10-04 | [Github](https://github.com/GenSim2/gensim2) |



# Awesome-techniques

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






