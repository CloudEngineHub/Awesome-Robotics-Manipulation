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
| [**Implicit Grasp Diffusion: Bridging the Gap between Dense Prediction and Sampling-based Grasping**](https://openreview.net/pdf?id=VUhlMfEekm) | CoRL 2024 | - | [Gitlab](https://gitlab.kuleuven.be/detry-lab/public/implicit-grasp-diffusion) | |
| [**GraspSplats: Efficient Manipulation with 3D Feature Splatting**](https://arxiv.org/abs/2409.02084) | CoRL 2024 | 2024-09-03 | [Github](https://github.com/jimazeyu/GraspSplats) | |


### SE(3) Grasp
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**OrbitGrasp: SE(3)-Equivariant Grasp Learning**](https://arxiv.org/abs/2407.03531) | CoRL 2024 | 2024-07-03 | [Project](https://orbitgrasp.github.io/) | |
| [**EquiGraspFlow: SE(3)-Equivariant 6-DoF Grasp Pose Generative Flows**](https://openreview.net/pdf?id=5lSkn5v4LK) | CoRL 2024 | - | [Github](https://github.com/bdlim99/EquiGraspFlow) | |
| [**Real-to-Sim Grasp: Rethinking the Gap between Simulation and Real World in Grasp Detection**](https://arxiv.org/abs/2410.06521) | CoRL 2024 | 2024-10-09 | [Project](https://isee-laboratory.github.io/R2SGrasp/) | |
| [**Rethinking 6-Dof Grasp Detection: A Flexible Framework for High-Quality Grasping**](https://arxiv.org/abs/2403.15054) | arXiv 2024 | 2024-03-22 | - | |


### LLM and VLM
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Reasoning Grasping via Multimodal Large Language Model**](https://arxiv.org/abs/2402.06798) | CoRL 2024 | 2024-02-09 | [Project](https://reasoning-grasping.github.io/) | |
| [**Towards Open-World Grasping with Large Vision-Language Models**](https://arxiv.org/abs/2406.18722) | CoRL 2024 | 2024-06-26 | [Project](https://gtziafas.github.io/OWG_project/) | |
| [**Reasoning Tuning Grasp: Adapting Multi-Modal Large Language Models for Robotic Grasping**](https://openreview.net/pdf?id=3mKb5iyZ2V) | CoRL 2023 Workshop | 2023-10-21 | [Project](https://sites.google.com/view/rt-grasp) | Tunning VLM for planar grasp detection |


### Transparent
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**T<sup>2</sup>SQNet: A Recognition Model for Manipulating Partially Observed Transparent Tableware Objects**](https://openreview.net/pdf?id=M0JtsLuhEE) | CoRL 2024 | - | [Github](https://github.com/seungyeon-k/T2SQNet-public) | |



## Policy Learning for Manipulation

### Representation Policy Learning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Task Success Prediction for Open-Vocabulary Manipulation Based on Multi-Level Aligned Representations**](https://arxiv.org/abs/2410.00436) | CoRL 2024 | 2024-10-01 | [Project](https://lambda-repformer-project-pa-eziy1.kinsta.page/) |
| [**Contrastive Imitation Learning for Language-guided Multi-Task Robotic Manipulation**](https://arxiv.org/abs/2406.09738) | CoRL 2024 | 2024-06-14 | [Project](https://teleema.github.io/projects/Sigma_Agent/) | |
| [**Theia: Distilling Diverse Vision Foundation Models for Robot Learning**](https://arxiv.org/abs/2407.20179) | CoRL 2024 | 2024-07-29 | [Github](https://github.com/bdaiinstitute/theia) | |
|
| [**PIVOT-R: Primitive-Driven Waypoint-Aware World Model for Robotic Manipulation**](https://arxiv.org/abs/2410.10394) | arXiv | 2024-10-14 | [Project](https://abliao.github.io/PIVOT-R/) | Hierarchical |
| [**HiRT: Enhancing Robotic Control with Hierarchical Robot Transformers**](https://arxiv.org/abs/2410.05273) | arXiv | 2024-09-12 | - | Hierarchical |
|
| [**GR-2: A Generative Video-Language-Action Model with Web-Scale Knowledge for Robot Manipulation**](https://arxiv.org/abs/2410.06158) | arXiv | 2024-10-08 | [Project](https://gr2-manipulation.github.io/) | |
| [**Unleashing Large-Scale Video Generative Pre-training for Visual Robot Manipulation**](https://arxiv.org/abs/2312.13139) | ICLR 2024 | 2023-12-20 | [Github](https://github.com/bytedance/GR-1) | GR-1 |
| [**GR-MG: Leveraging Partially Annotated Data via Multi-Modal Goal Conditioned Policy**](https://arxiv.org/abs/2408.14368) | arXiv | 2024-08-26 | [Github](https://github.com/bytedance/GR-MG/tree/main) | Partially labeled data |
|
| [**Leveraging Locality to Boost Sample Efficiency in Robotic Manipulation**](https://arxiv.org/abs/2406.10615) | CoRL 2024 | 2024-06-15 | [Github](https://github.com/TongZhangTHU/sgr) | SGRv2 |
| [**A Universal Semantic-Geometric Representation for Robotic Manipulation**](https://arxiv.org/abs/2306.10474) | CoRL 2023 | 2023-06-18 | [Github](https://github.com/TongZhangTHU/sgr) | SGR |
|
| [**Learning Compositional Behaviors from Demonstration and Language**](https://openreview.net/pdf?id=fR1rCXjCQX) | CoRL 2024 | - | - | Fine-grained Atom action |
| [**Policy Adaptation via Language Optimization: Decomposing Tasks for Few-Shot Imitation**](https://arxiv.org/abs/2408.16228) | CoRL 2024 | 2024-08-29 | [Github](https://github.com/vivekmyers/palo) | Fine-grained Atom action |




### Generative and Diffusion Policy Learning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Generative Image as Action Models**](https://arxiv.org/abs/2407.07875) | CoRL 2024 | 2024-07-10 | [Github](https://github.com/MohitShridhar/genima) | GENIMA, diffusion, draw joint-actions |
| [**Goal-Conditioned Imitation Learning using Score-based Diffusion Policies**](https://arxiv.org/abs/2304.02532) | RSS 2023 | 2023-04-05 | [Github](https://github.com/intuitive-robots/beso) |  |
|
| [**Multimodal Diffusion Transformer: Learning Versatile Behavior from Multimodal Goals**](https://arxiv.org/abs/2407.05996) | RSS 2024 | 2024-07-08 | [Github](https://github.com/intuitive-robots/mdt_policy) | Partially labeled data |
| [**Diffusion Transformer Policy**](https://arxiv.org/abs/2410.15959) | arXiv | 2024-10-21 | - | |
| [**Equivariant Diffusion Policy**](https://arxiv.org/abs/2407.01812) | CoRL 2024 | 2024-07-01 | [Code](https://github.com/pointW/equidiff) |  |
| [**Sparse Diffusion Policy: A Sparse, Reusable, and Flexible Policy for Robot Learning**](https://arxiv.org/abs/2407.01531) | CoRL 2024 | 2024-07-01 | [Github](https://github.com/AnthonyHuo/SDP) |  |
| [**EquiBot: SIM(3)-Equivariant Diffusion Policy for Generalizable and Data Efficient Learning**](https://arxiv.org/abs/2407.01479) | CoRL 2024 | 2024-07-01 | [Github](https://github.com/yjy0625/equibot) |  |
| [**IMAGINATION POLICY: Using Generative Point Cloud Models for Learning Manipulation Policies**](https://arxiv.org/abs/2406.11740) | CoRL 2024 | 2024-06-17 | [Project](https://haojhuang.github.io/imagine_page/) |  |
|
| [**Imitation Learning with Limited Actions via Diffusion Planners and Deep Koopman Controllers**](https://arxiv.org/abs/2410.07584) | arXiv | 2024-10-10 | - |  |
| [**Autoregressive Action Sequence Learning for Robotic Manipulation**](https://arxiv.org/abs/2410.03132) | arXiv | 2024-10-04 | [Github](https://github.com/mlzxy/arp) | |
| [**MaIL: Improving Imitation Learning with Selective State Space Models**](https://arxiv.org/abs/2406.08234) | CoRL 2024 | 2024-06-12 | - | |




### Vision Language Action Models
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**OpenVLA: An Open-Source Vision-Language-Action Model**](https://arxiv.org/abs/2406.09246) | CoRL 2024 | 2024-06-13 | [Github](https://github.com/openvla/openvla) |  |
| [**LLARVA: Vision-Action Instruction Tuning Enhances Robot Learning**](https://arxiv.org/abs/2406.11815) | CoRL 2024 | 2024-06-17 | [Github](https://github.com/Dantong88/LLARVA) |  |
| [**Robotic Control via Embodied Chain-of-Thought Reasoning**](https://arxiv.org/abs/2406.11815) | CoRL 2024 | 2024-07-11 | [Github](https://github.com/MichalZawalski/embodied-CoT/) |  |



### Reinforcement
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**SPIRE: Synergistic Planning, Imitation, and Reinforcement for Long-Horizon Manipulation**](https://arxiv.org/abs/2410.18065) | CoRL 2024 | 2024-10-23 | [Project](https://sites.google.com/view/spire-corl-2024) |  |
| [**Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning**](https://arxiv.org/abs/2407.15815) | CoRL 2024 | 2024-07-22 | [Project](https://gemcollector.github.io/maniwhere/) |  |


### Online Imitation Learnings
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**KOI: Accelerating Online Imitation Learning via Hybrid Key-state Guidance**](https://www.arxiv.org/abs/2408.02912) | CoRL 2024 | 2024-08-06 | [Github](https://github.com/GeWu-Lab/Keystate_Online_Imitation) | |


### SE(3)-Equivariant Robot Manipulation
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Generative Image as Action Models**](https://arxiv.org/abs/2403.19460) | CoRL 2024 | 2024-03-28 | [Github](https://github.com/HeegerGao/RiEMann) |  |


### Motion Planning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**DiffusionSeeder: Seeding Motion Optimization with Diffusion for Rapid Motion Planning**](https://arxiv.org/abs/2410.16727) | CoRL 2024 | 2024-10-22 | [Project](https://diffusion-seeder.github.io/) |  |
| [**ReKep: Spatio-Temporal Reasoning of Relational Keypoint Constraints for Robotic Manipulation**](https://arxiv.org/abs/2409.01652) | CoRL 2024 | 2024-09-03 | [Code](https://github.com/huangwl18/ReKep) |  |


### Flow and Tranjectory
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Learning Robotic Manipulation Policies from Point Clouds with Conditional Flow Matching**](https://arxiv.org/abs/2409.07343) | CoRL 2024 | 2024-09-11 | [Project](http://pointflowmatch.cs.uni-freiburg.de/) |  |



### Data Selection and Augmentation
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**RoVi-Aug: Robot and Viewpoint Augmentation for Cross-Embodiment Robot Learning**](https://arxiv.org/abs/2409.03403) | CoRL 2024 | 2024-09-05 | [Project](https://rovi-aug.github.io/) |  |
| [**Re-Mix: Optimizing Data Mixtures for Large Scale Imitation Learning**](https://arxiv.org/abs/2408.14037) | CoRL 2024 | 2024-08-26 | [Github](https://github.com/jhejna/remix) |  |
| [**Scaling Robot Policy Learning via Zero-Shot Labeling with Foundation Models**](https://arxiv.org/abs/2410.17772) | CoRL 2024 | 2024-10-23 | [Project](https://robottasklabeling.github.io/) |  |
| [**Autonomous Improvement of Instruction Following Skills via Foundation Models**](https://arxiv.org/abs/2407.20635) | CoRL 2024 | 2024-07-30 | [Github](https://github.com/rail-berkeley/soar) |  |



## Affordance
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**RoboPoint: A Vision-Language Model for Spatial Affordance Prediction for Robotics**](https://arxiv.org/abs/2406.10721) | CoRL 2024 | 2024-06-15 | [Github](https://github.com/wentaoyuan/RoboPoint) | |
| [**A3VLM: Actionable Articulation-Aware Vision Language Model**](https://arxiv.org/abs/2406.07549) | CoRL 2024 | 2024-06-14 | [Github](https://github.com/changhaonan/A3VLM) | |
| [**AIC MLLM: Autonomous Interactive Correction MLLM for Robust Robotic Manipulation**](https://arxiv.org/abs/2406.11548) | CoRL 2024 | 2024-06-17 | [Project](https://sites.google.com/view/aic-mllm) | |
| [**RAM: Retrieval-Based Affordance Transfer for Generalizable Zero-Shot Robotic Manipulation**](https://arxiv.org/abs/2407.04689) | CoRL 2024 | 2024-07-05 | [Github](https://github.com/yxKryptonite/RAM_code) | |





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
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Vocal Sandbox: Continual Learning and Adaptation for Situated Human-Robot Collaboration**](https://openreview.net/pdf?id=ypaYtV1CoG) | CoRL 2024 | - | [Project](https://vocal-sandbox.github.io/) |  |
| [**APRICOT: Active Preference Learning and Constraint-Aware Task Planning with LLMs**](https://openreview.net/pdf?id=nQslM6f7dW) | CoRL 2024 | - | [Project](https://portal-cornell.github.io/apricot/) |  |
| [**Text2Interaction: Establishing Safe and Preferable Human-Robot Interaction**](https://arxiv.org/abs/2408.06105) | CoRL 2024 | 2024-08-12 | [Github](https://github.com/JakobThumm/text2interaction) |  |
|
| [**Teaching Robots with Show and Tell: Using Foundation Models to Synthesize Robot Policies from Language and Visual Demonstrations**](https://openreview.net/pdf?id=G8UcwxNAoD) | CoRL 2024 | - | [Project](https://robo-showtell.github.io/) |  |
| [**Text2Motion: From Natural Language Instructions to Feasible Plans**](https://arxiv.org/abs/2303.12153) | Autonomous Robots 2023 | 2023-03-21 | [Project](https://sites.google.com/stanford.edu/text2motion) |  |
| [**STAP: Sequencing Task-Agnostic Policies**](https://arxiv.org/abs/2210.12250) | ICRA 2023 | 2022-10-21 | [Github](https://github.com/agiachris/STAP) |  |


## Generalization and Generalist
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Scaling Cross-Embodied Learning: One Policy for Manipulation, Navigation, Locomotion and Aviation**](https://arxiv.org/abs/2408.11812) | CoRL 2024 | 2024-08-21 | [Github](https://github.com/rail-berkeley/crossformer) | Cross-Embodied |
| [**All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents**](https://arxiv.org/abs/2408.10899) | arXiv | 2024-08-20 | [Project](https://imaei.github.io/project_pages/ario/) | Cross-Embodied |
|
| [**An Embodied Generalist Agent in 3D World**](https://arxiv.org/abs/2311.12871) | ICML 2024 | 2023-11-18 | [Github](https://github.com/embodied-generalist/embodied-generalist) |  |
| [**Steering Your Generalists: Improving Robotic Foundation Models via Value Guidance**](https://arxiv.org/abs/2410.13816) | CoRL 2024 | 2024-10-17 | [Project](https://nakamotoo.github.io/V-GPS/index.html) |  |
| [**Towards Synergistic, Generalized, and Efficient Dual-System for Robotic Manipulation**](https://arxiv.org/abs/2410.08001) | CoRL 2024 | 2024-10-10 | [Project](https://opendrivelab.com/RoboDual/) |  |
| [**Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning**](https://arxiv.org/abs/2407.15815) | CoRL 2024 | 2024-07-22 | [Project](https://gemcollector.github.io/maniwhere/) |  |



## Mobile Manipulation
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**TaMMa: Target-driven Multi-subscene Mobile Manipulation**](https://openreview.net/pdf?id=EiqQEsOMZt) | CoRL 2024 | - | - |


## Humanoid
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**OKAMI: Teaching Humanoid Robots Manipulation Skills through Single Video Imitation**](https://arxiv.org/abs/2410.11792) | CoRL 2024 | 2024-10-15 | [Project](https://ut-austin-rpl.github.io/OKAMI/)  |


# Awesome-benchmarks
## Evaluating methods
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Contrast Sets for Evaluating Language-Guided Robot Policies**](https://arxiv.org/abs/2406.13636) | CoRL 2024 | 2024-06-19 | - |  |
| [**Evaluating Real-World Robot Manipulation Policies in Simulation**](https://arxiv.org/abs/2405.05941) | CoRL 2024 | 2024-05-09 | [Github](https://github.com/simpler-env/SimplerEnv) |  |

## Grasp datasets
| [**Real-to-Sim Grasp: Rethinking the Gap between Simulation and Real World in Grasp Detection**](https://arxiv.org/abs/2410.06521) | CoRL 2024 | 2024-10-09 | [Project](https://isee-laboratory.github.io/R2SGrasp/) | |

# Manipulation
| [**All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents**](https://arxiv.org/abs/2408.10899) | arXiv | 2024-08-20 | [Dataset](https://openi.pcl.ac.cn/ARIO/ARIO_Dataset) | |





# Awesome-simulators
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**GenSim2: Scaling Robot Data Generation with Multi-modal and Reasoning LLMs**](https://arxiv.org/abs/2410.03645) | CoRL 2024 | 2024-10-04 | [Github](https://github.com/GenSim2/gensim2) |



# Awesome-techniques
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|


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





