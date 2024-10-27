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


<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


## Policy Learning for Grasp

### 3D <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**GraspNeRF: Multiview-based 6-DoF Grasp Detection for Transparent and Specular Objects Using Generalizable NeRF**](https://arxiv.org/abs/2210.06575) | ICRA 2023 | 2022-10-12 | [Github](https://github.com/PKU-EPIC/GraspNeRF) | |
| [**Language Embedded Radiance Fields for Zero-Shot Task-Oriented Grasping**](https://arxiv.org/abs/2309.07970) | CoRL 2023 | 2023-09-14 | [Github](https://github.com/lerftogo/lerftogo) | |
| [**GaussianGrasper: 3D Language Gaussian Splatting for Open-vocabulary Robotic Grasping**](https://arxiv.org/abs/2403.09637) | RA-L 2024 | 2024-03-14 | [Github](https://github.com/MrSecant/GaussianGrasper) | |
| [**Implicit Grasp Diffusion: Bridging the Gap between Dense Prediction and Sampling-based Grasping**](https://openreview.net/pdf?id=VUhlMfEekm) | CoRL 2024 | - | [Gitlab](https://gitlab.kuleuven.be/detry-lab/public/implicit-grasp-diffusion) | |
| [**GraspSplats: Efficient Manipulation with 3D Feature Splatting**](https://arxiv.org/abs/2409.02084) | CoRL 2024 | 2024-09-03 | [Github](https://github.com/jimazeyu/GraspSplats) | |
| [**Learning Any-View 6DoF Robotic Grasping in Cluttered Scenes via Neural Surface Rendering**](https://arxiv.org/abs/2306.07392) | RSS 2024 | 2023-06-12 | - | |


### Rectangle-based Grasp <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Lightweight Language-driven Grasp Detection using Conditional Consistency Model**](https://arxiv.org/abs/2407.17967) | IROS 2024 | 2024-07-25 | [Github](https://github.com/Fsoft-AIC/Lightweight-Language-driven-Grasp-Detection) | |


### SE(3) / 6-DoF Grasp <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**OrbitGrasp: SE(3)-Equivariant Grasp Learning**](https://arxiv.org/abs/2407.03531) | CoRL 2024 | 2024-07-03 | [Project](https://orbitgrasp.github.io/) | |
| [**EquiGraspFlow: SE(3)-Equivariant 6-DoF Grasp Pose Generative Flows**](https://openreview.net/pdf?id=5lSkn5v4LK) | CoRL 2024 | - | [Github](https://github.com/bdlim99/EquiGraspFlow) | |
| [**Real-to-Sim Grasp: Rethinking the Gap between Simulation and Real World in Grasp Detection**](https://arxiv.org/abs/2410.06521) | CoRL 2024 | 2024-10-09 | [Project](https://isee-laboratory.github.io/R2SGrasp/) | |
| [**Rethinking 6-Dof Grasp Detection: A Flexible Framework for High-Quality Grasping**](https://arxiv.org/abs/2403.15054) | arXiv 2024 | 2024-03-22 | - | |
| [**Generalizing 6-DoF Grasp Detection via Domain Prior Knowledge**](https://arxiv.org/abs/2404.01727) | CVPR 2024 | 2024-04-02 | [Github](https://github.com/mahaoxiang822/Generalizing-Grasp) | |
| [**An Economic Framework for 6-DoF Grasp Detection**](https://arxiv.org/abs/2407.08366) | ECCV 2024 | 2024-07-11 | [Github](https://github.com/iSEE-Laboratory/EconomicGrasp) | |
| [**Efficient Heatmap-Guided 6-Dof Grasp Detection in Cluttered Scenes**](https://arxiv.org/abs/2403.18546) | RA-L 2023 | 2024-03-27 | [Github](https://github.com/THU-VCLab/HGGD) | |
| [**Language-Driven 6-DoF Grasp Detection Using Negative Prompt Guidance**](https://arxiv.org/abs/2407.13842) | ECCV 2024 | 2024-07-18 | [Github](https://github.com/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance) | |


### LLM and VLM <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Reasoning Grasping via Multimodal Large Language Model**](https://arxiv.org/abs/2402.06798) | CoRL 2024 | 2024-02-09 | [Project](https://reasoning-grasping.github.io/) | |
| [**Towards Open-World Grasping with Large Vision-Language Models**](https://arxiv.org/abs/2406.18722) | CoRL 2024 | 2024-06-26 | [Project](https://gtziafas.github.io/OWG_project/) | |
| [**Reasoning Tuning Grasp: Adapting Multi-Modal Large Language Models for Robotic Grasping**](https://openreview.net/pdf?id=3mKb5iyZ2V) | CoRL 2023 Workshop | 2023-10-21 | [Project](https://sites.google.com/view/rt-grasp) | Tunning VLM for planar grasp detection |


### Task-oriented <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**RTAGrasp: Learning Task-Oriented Grasping from Human Videos via Retrieval, Transfer, and Alignment**](https://arxiv.org/abs/2409.16033) | arXiv | 2024-09-24 | [Project](https://sites.google.com/view/rtagrasp/home) | |
| [**ASGrasp: Generalizable Transparent Object Reconstruction and Grasping from RGB-D Active Stereo Camera**](https://arxiv.org/abs/2405.05648) | ICRA 2024 | 2024-05-09 | [Github](https://github.com/jun7-shi/ASGrasp) | |


### Transparent <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**T<sup>2</sup>SQNet: A Recognition Model for Manipulating Partially Observed Transparent Tableware Objects**](https://openreview.net/pdf?id=M0JtsLuhEE) | CoRL 2024 | - | [Github](https://github.com/seungyeon-k/T2SQNet-public) | |


<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


## Policy Learning for Manipulation

### Imitation Learning <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**BC-Z: Zero-Shot Task Generalization with Robotic Imitation Learning**](https://arxiv.org/abs/2202.02005) | CoRL 2021 | 2022-02-04 | [Github](https://github.com/google-research/tensor2robot/tree/master/research/bcz) | |


### Representation Policy Learning <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Contrastive Imitation Learning for Language-guided Multi-Task Robotic Manipulation**](https://arxiv.org/abs/2406.09738) | CoRL 2024 | 2024-06-14 | [Project](https://teleema.github.io/projects/Sigma_Agent/) | |
| Additional Text Information Input |
| [**Task Success Prediction for Open-Vocabulary Manipulation Based on Multi-Level Aligned Representations**](https://arxiv.org/abs/2410.00436) | CoRL 2024 | 2024-10-01 | [Project](https://lambda-repformer-project-pa-eziy1.kinsta.page/) |
| Additional Visual Information Input |
| [**Vid2Robot: End-to-end Video-conditioned Policy Learning with Cross-Attention Transformers**](https://arxiv.org/abs/2403.12943) | RSS 2024 | 2024-03-19 | [Project](https://vid2robot.github.io/) | |
| [**Theia: Distilling Diverse Vision Foundation Models for Robot Learning**](https://arxiv.org/abs/2407.20179) | CoRL 2024 | 2024-07-29 | [Github](https://github.com/bdaiinstitute/theia) | |
| [**Object-Centric Instruction Augmentation for Robotic Manipulation**](https://arxiv.org/abs/2406.09738) | ICRA 2024 | 2024-01-05 | [Project](https://oci-robotics.github.io/) | |
| [**Affordance Learning from Play for Sample-Efficient Policy Learning**](https://arxiv.org/abs/2203.00352) | ICRA 2022 | 2022-03-01 | [Project](http://vapo.cs.uni-freiburg.de/) | VAPO |
| [**CALAMARI: Contact-Aware and Language conditioned spatial Action MApping for contact-RIch manipulation**](https://openreview.net/pdf?id=Nii0_rRJwN) | CoRL 2023 | 2023 | [Project](https://www.mmintlab.com/research/calamari/) |  |
| Additional Task Output |
| [**R3M: A Universal Visual Representation for Robot Manipulation**](https://arxiv.org/abs/2203.12601) | CoRL 2023 | 2022-03-23 | [Github](https://github.com/facebookresearch/r3m) | Contrastive Learning |
| [**Learning Manipulation by Predicting Interaction**](https://www.arxiv.org/abs/2406.00439) | RSS 2024 | 2024-06-01 | [Github](https://github.com/OpenDriveLab/MPI) |  |
| [**Language-Driven Representation Learning for Robotics**](https://arxiv.org/abs/2302.12766) | RSS 2023 | 2023-02-24 | [Github](https://github.com/siddk/voltron-robotics) | Mask |
| [**Real-World Robot Learning with Masked Visual Pre-training**](https://arxiv.org/abs/2210.03109) | CoRL 2022 | 2022-10-06 | [Github](https://github.com/ir413/mvp) | Mask |
| [**VLMPC: Vision-Language Model Predictive Control for Robotic Manipulation**](https://arxiv.org/abs/2407.09829) | RSS 2024 | 2024-07-13 | [Github](https://github.com/PPjmchen/VLMPC) | Video Prediction |
| Latent |
| [**Latent Action Pretraining from Videos**](https://arxiv.org/abs/2410.11758) | arXiv  | 2024-10-15 | [Github](https://github.com/LatentActionPretraining/LAPA) | |
| [**MimicPlay: Long-Horizon Imitation Learning by Watching Human Play**](https://arxiv.org/abs/2302.12422) | CoRL 2023  | 2023-02-24 | [Github](https://github.com/j96w/MimicPlay) | |
| |
| [**PIVOT-R: Primitive-Driven Waypoint-Aware World Model for Robotic Manipulation**](https://arxiv.org/abs/2410.10394) | arXiv | 2024-10-14 | [Project](https://abliao.github.io/PIVOT-R/) | Hierarchical |
| [**HiRT: Enhancing Robotic Control with Hierarchical Robot Transformers**](https://arxiv.org/abs/2410.05273) | arXiv | 2024-09-12 | - | Hierarchical |
| [**MResT: Multi-Resolution Sensing for Real-Time Control with Vision-Language Models**](https://arxiv.org/abs/2401.14502) | CoRL 2023 | 2024-01-25 | [Github](https://github.com/iamlab-cmu/mrest-multi-resolution-transformer) |  |
| |
| [**GR-2: A Generative Video-Language-Action Model with Web-Scale Knowledge for Robot Manipulation**](https://arxiv.org/abs/2410.06158) | arXiv | 2024-10-08 | [Project](https://gr2-manipulation.github.io/) | |
| [**Unleashing Large-Scale Video Generative Pre-training for Visual Robot Manipulation**](https://arxiv.org/abs/2312.13139) | ICLR 2024 | 2023-12-20 | [Github](https://github.com/bytedance/GR-1) | GR-1 |
| |
| [**GR-MG: Leveraging Partially Annotated Data via Multi-Modal Goal Conditioned Policy**](https://arxiv.org/abs/2408.14368) | arXiv | 2024-08-26 | [Github](https://github.com/bytedance/GR-MG/tree/main) | Partially labeled data |
| [**Goal Representations for Instruction Following: A Semi-Supervised Language Interface to Control**](https://arxiv.org/abs/2307.00117) | CoRL 2023 | 2023-06-30 | [Github](https://github.com/rail-berkeley/grif_release) | Partially labeled data |
| [**Grounding Language with Visual Affordances over Unstructured Data**](https://arxiv.org/abs/2210.01911) | ICRA 2023 | 2022-10-04 | [Github](https://github.com/mees/hulc2) | HULC++ |
| [**What Matters in Language Conditioned Robotic Imitation Learning over Unstructured Data**](https://arxiv.org/abs/2204.06252) | RA-L 2022 | 2022-04-13 | [Github](https://github.com/lukashermann/hulc) | HULC |
| |
| [**Leveraging Locality to Boost Sample Efficiency in Robotic Manipulation**](https://arxiv.org/abs/2406.10615) | CoRL 2024 | 2024-06-15 | [Github](https://github.com/TongZhangTHU/sgr) | SGRv2 |
| [**A Universal Semantic-Geometric Representation for Robotic Manipulation**](https://arxiv.org/abs/2306.10474) | CoRL 2023 | 2023-06-18 | [Github](https://github.com/TongZhangTHU/sgr) | SGR |
| |
| [**Learning Compositional Behaviors from Demonstration and Language**](https://openreview.net/pdf?id=fR1rCXjCQX) | CoRL 2024 | 2024 | - | Fine-grained Atom action |
| [**Policy Adaptation via Language Optimization: Decomposing Tasks for Few-Shot Imitation**](https://arxiv.org/abs/2408.16228) | CoRL 2024 | 2024-08-29 | [Github](https://github.com/vivekmyers/palo) | Fine-grained Atom action |
| |
| [**Can Foundation Models Perform Zero-Shot Task Specification For Robot Manipulation?**](https://arxiv.org/abs/2204.11134) | L4DC 2022 | 2022-04-23 | [Project](https://sites.google.com/view/zestproject) | |
| Simple V-L policy|
| [**Leveraging Language for Accelerated Learning of Tool Manipulation**](https://arxiv.org/abs/2206.13074) | CoRL 2023 | 2022-06-27 | [Github](https://github.com/irom-lab/ATLA) | |
| World Model |
| [**Structured World Models from Human Videos**](https://arxiv.org/abs/2308.10901) | RSS 2023 | 2023-08-23 | [Github](https://human-world-model.github.io/) | |
| [**Finetuning Offline World Models in the Real World**](https://arxiv.org/abs/2310.16029) | CoRL 2023 | 2023-10-24 | [Github](https://github.com/fyhMer/fowm) | |





### Generative and Diffusion Policy Learning <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| Additional Task Output |
| [**Render and Diffuse: Aligning Image and Action Spaces for Diffusion-based Behaviour Cloning**](https://arxiv.org/abs/2405.18196) | RSS 2024 | 2024-05-28 | [Github](https://github.com/vv19/rendiff) | |
| |
| [**Generative Image as Action Models**](https://arxiv.org/abs/2407.07875) | CoRL 2024 | 2024-07-10 | [Github](https://github.com/MohitShridhar/genima) | GENIMA, diffusion, draw joint-actions |
| [**Multimodal Diffusion Transformer: Learning Versatile Behavior from Multimodal Goals**](https://arxiv.org/abs/2407.05996) | RSS 2024 | 2024-07-08 | [Github](https://github.com/intuitive-robots/mdt_policy) | Partially labeled data |
| |
| [**Goal-Conditioned Imitation Learning using Score-based Diffusion Policies**](https://arxiv.org/abs/2304.02532) | RSS 2023 | 2023-04-05 | [Github](https://github.com/intuitive-robots/beso) |  |
| [**Diffusion Transformer Policy**](https://arxiv.org/abs/2410.15959) | arXiv | 2024-10-21 | - | |
| [**Equivariant Diffusion Policy**](https://arxiv.org/abs/2407.01812) | CoRL 2024 | 2024-07-01 | [Code](https://github.com/pointW/equidiff) |  |
| [**Sparse Diffusion Policy: A Sparse, Reusable, and Flexible Policy for Robot Learning**](https://arxiv.org/abs/2407.01531) | CoRL 2024 | 2024-07-01 | [Github](https://github.com/AnthonyHuo/SDP) |  |
| [**EquiBot: SIM(3)-Equivariant Diffusion Policy for Generalizable and Data Efficient Learning**](https://arxiv.org/abs/2407.01479) | CoRL 2024 | 2024-07-01 | [Github](https://github.com/yjy0625/equibot) |  |
| [**StructDiffusion: Language-Guided Creation of Physically-Valid Structures using Unseen Objects**](https://arxiv.org/abs/2211.04604) | RSS 2023 | 2022-11-08 | [Github](https://github.com/StructDiffusion/StructDiffusion) |  |
| [**Diffusion Policy: Visuomotor Policy Learning via Action Diffusion**](https://arxiv.org/abs/2303.04137) | RSS 2023 | 2023-03-07 | [Github](https://github.com/real-stanford/diffusion_policy) |  |
| |
| [**IMAGINATION POLICY: Using Generative Point Cloud Models for Learning Manipulation Policies**](https://arxiv.org/abs/2406.11740) | CoRL 2024 | 2024-06-17 | [Project](https://haojhuang.github.io/imagine_page/) |  |
| [**Imitation Learning with Limited Actions via Diffusion Planners and Deep Koopman Controllers**](https://arxiv.org/abs/2410.07584) | arXiv | 2024-10-10 | - |  |
| [**Autoregressive Action Sequence Learning for Robotic Manipulation**](https://arxiv.org/abs/2410.03132) | arXiv | 2024-10-04 | [Github](https://github.com/mlzxy/arp) | |
| [**MaIL: Improving Imitation Learning with Selective State Space Models**](https://arxiv.org/abs/2406.08234) | CoRL 2024 | 2024-06-12 | - | |




### Vision Language Action Models <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**A Dual Process VLA: Efficient Robotic Manipulation Leveraging VLM**](https://arxiv.org/abs/2410.15549) | CoRL 2024 | 2024-10-21 | - |  |
| [**OpenVLA: An Open-Source Vision-Language-Action Model**](https://arxiv.org/abs/2406.09246) | CoRL 2024 | 2024-06-13 | [Github](https://github.com/openvla/openvla) |  |
| [**LLARVA: Vision-Action Instruction Tuning Enhances Robot Learning**](https://arxiv.org/abs/2406.11815) | CoRL 2024 | 2024-06-17 | [Github](https://github.com/Dantong88/LLARVA) |  |
| [**Robotic Control via Embodied Chain-of-Thought Reasoning**](https://arxiv.org/abs/2406.11815) | CoRL 2024 | 2024-07-11 | [Github](https://github.com/MichalZawalski/embodied-CoT/) |  |
| [**Octo: An Open-Source Generalist Robot Policy**](https://arxiv.org/abs/2405.12213) | RSS 2024 | 2024-05-20 | [Github](https://github.com/octo-models/octo) | |
| [**Open X-Embodiment: Robotic Learning Datasets and RT-X Models**](https://arxiv.org/abs/2310.08864) | ICRA 2024 | 2023-10-13 | [Github](https://github.com/google-deepmind/open_x_embodiment) | |
| [**Open-World Object Manipulation using Pre-trained Vision-Language Models**](https://arxiv.org/abs/2303.00905) | CoRL 2023 | 2023-03-02 | [Project](https://robot-moo.github.io/) | MOO |
| [**Vision-Language Foundation Models as Effective Robot Imitators**](https://arxiv.org/abs/2311.01378) | ICLR 2024 | 2023-11-02 | [Github](https://github.com/RoboFlamingo/RoboFlamingo) | RoboFlamingo |
| [**RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control**](https://arxiv.org/abs/2307.15818) | CoRL 2023 | 2023-07-28 | [Project](https://robotics-transformer2.github.io/) |  |
| [**TinyVLA: Towards Fast, Data-Efficient Vision-Language-Action Models for Robotic Manipulation**](https://arxiv.org/abs/2409.12514) | arXiv | 2024-09-19 | [Github](https://github.com/lesjie-wen/tinyvla) |  |
| [**3D-VLA: A 3D Vision-Language-Action Generative World Model**](https://arxiv.org/abs/2403.09631) | ICML 2024 | 2024-03-14 | [Github](https://github.com/UMass-Foundation-Model/3D-VLA) |  |
| [**RT-H: Action Hierarchies Using Language**](https://arxiv.org/abs/2403.01823) | arXiv | 2024-03-04 | [Project](https://rt-hierarchy.github.io/) |  |
| [**RoboMamba: Multimodal State Space Model for Efficient Robot Reasoning and Manipulation**](https://arxiv.org/abs/2406.04339) | NeurIPS 2024 | 2024-06-06 | [Github](https://github.com/lmzpai/roboMamba) |  |



### Reinforcement <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**SPIRE: Synergistic Planning, Imitation, and Reinforcement for Long-Horizon Manipulation**](https://arxiv.org/abs/2410.18065) | CoRL 2024 | 2024-10-23 | [Project](https://sites.google.com/view/spire-corl-2024) |  |
| [**Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning**](https://arxiv.org/abs/2407.15815) | CoRL 2024 | 2024-07-22 | [Project](https://gemcollector.github.io/maniwhere/) |  |
| [**Pre-Training for Robots: Offline RL Enables Learning New Tasks from a Handful of Trials**](https://arxiv.org/abs/2210.05178) | RSS 2023 | 2022-10-11 | [Project](https://sites.google.com/view/ptr-final/) |  |
| [**VIP: Towards Universal Visual Reward and Representation via Value-Implicit Pre-Training**](https://arxiv.org/abs/2210.00030) | ICLR 2023 | 2022-08-30 | [Github](https://github.com/facebookresearch/vip) | |
| [**Expansive Latent Planning for Sparse Reward Offline Reinforcement Learning**](https://openreview.net/pdf?id=xQx1O7WXSA) | CoRL 2023 | 2023 | - | |


### Online Imitation Learnings <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**KOI: Accelerating Online Imitation Learning via Hybrid Key-state Guidance**](https://www.arxiv.org/abs/2408.02912) | CoRL 2024 | 2024-08-06 | [Github](https://github.com/GeWu-Lab/Keystate_Online_Imitation) | |


### Few-Shot Imitation Learnings <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Behavior Retrieval: Few-Shot Imitation Learning by Querying Unlabeled Datasets**](https://arxiv.org/abs/2304.08742) | RSS 2023 | 2023-04-08 | [Github](https://github.com/MaxDu17/BehaviorRetrieval) | |


### SE(3)-Equivariant Robot Manipulation <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Generative Image as Action Models**](https://arxiv.org/abs/2403.19460) | CoRL 2024 | 2024-03-28 | [Github](https://github.com/HeegerGao/RiEMann) |  |


### Motion Planning <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**DiffusionSeeder: Seeding Motion Optimization with Diffusion for Rapid Motion Planning**](https://arxiv.org/abs/2410.16727) | CoRL 2024 | 2024-10-22 | [Project](https://diffusion-seeder.github.io/) |  |
| [**ReKep: Spatio-Temporal Reasoning of Relational Keypoint Constraints for Robotic Manipulation**](https://arxiv.org/abs/2409.01652) | CoRL 2024 | 2024-09-03 | [Github](https://github.com/huangwl18/ReKep) |  |
| [**CoPa: General Robotic Manipulation through Spatial Constraints of Parts with Foundation Models**](https://arxiv.org/abs/2403.08248) | ICRAW 2024 | 2024-03-13 | [Github](https://github.com/HaoxuHuang/copa) |  |
| [**VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models**](https://arxiv.org/abs/2307.05973) | CoRL 2023 | 2023-07-12 | [Github](https://github.com/huangwl18/VoxPoser) |  |


### Path Planning <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Language-Conditioned Path Planning**](https://arxiv.org/abs/2308.16893 | CORL 2023 | 2024-08-31 | [Github](https://github.com/amberxie88/lapp) |  |


### Flow and Tranjectory <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Learning Robotic Manipulation Policies from Point Clouds with Conditional Flow Matching**](https://arxiv.org/abs/2409.07343) | CoRL 2024 | 2024-09-11 | [Project](http://pointflowmatch.cs.uni-freiburg.de/) |  |
| [**Learning to Act from Actionless Videos through Dense Correspondences**](https://arxiv.org/abs/2310.08576) | ICLR 2024 | 2023-10-12 | [Github](https://github.com/flow-diffusion/AVDC) |  |
| |
| [**Flow as the Cross-Domain Manipulation Interface**](https://www.arxiv.org/abs/2407.15208) | CoRL 2024 | 2024-07-21 | [Github](https://github.com/real-stanford/im2Flow2Act) |  |
| [**ORION: Vision-based Manipulation from Single Human Video with Open-World Object Graphs**](https://arxiv.org/abs/2405.20321) | arXiv | 2024-05-30 | [Github](https://ut-austin-rpl.github.io/ORION-release/) |  |
| [**Any-point Trajectory Modeling for Policy Learning**](https://arxiv.org/abs/2401.00025) | CoRL 2024 | 2023-12-28 | [Github](https://github.com/Large-Trajectory-Model/any-point-trajectory-modeling) |  |
| [**Track2Act: Predicting Point Tracks from Internet Videos enables Generalizable Robot Manipulation**](https://arxiv.org/abs/2407.09829) | ECCV 2024 | 2024-07-13 | [Github](https://github.com/homangab/Track-2-Act/) |  |
| [**RoboTAP: Tracking Arbitrary Points for Few-Shot Visual Imitation**](https://arxiv.org/abs/2308.15975) | ICRA 2024 | 2023-08-30 | [Github](https://github.com/google-deepmind/tapnet/blob/main/colabs/tapir_clustering.ipynb) |  |


### Data Generation, Selection and Augmentation <a href="#awesome-robotics-manipulation">🔝</a>
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**RoVi-Aug: Robot and Viewpoint Augmentation for Cross-Embodiment Robot Learning**](https://arxiv.org/abs/2409.03403) | CoRL 2024 | 2024-09-05 | [Project](https://rovi-aug.github.io/) |  |
| [**Re-Mix: Optimizing Data Mixtures for Large Scale Imitation Learning**](https://arxiv.org/abs/2408.14037) | CoRL 2024 | 2024-08-26 | [Github](https://github.com/jhejna/remix) |  |
| [**Scaling Robot Policy Learning via Zero-Shot Labeling with Foundation Models**](https://arxiv.org/abs/2410.17772) | CoRL 2024 | 2024-10-23 | [Project](https://robottasklabeling.github.io/) |  |
| [**Autonomous Improvement of Instruction Following Skills via Foundation Models**](https://arxiv.org/abs/2407.20635) | CoRL 2024 | 2024-07-30 | [Github](https://github.com/rail-berkeley/soar) |  |
| [**Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition**](https://arxiv.org/abs/2307.14535) | CoRL 2023 | 2023-07-26 | [Github](https://github.com/real-stanford/scalingup) |  |
| [**Robotic Skill Acquisition via Instruction Augmentation with Vision-Language Models**](https://arxiv.org/abs/2211.11736) | RSS 2023 | 2022-11-21 | [Project](https://instructionaugmentation.github.io/) |  |
| [**GenAug: Retargeting behaviors to unseen situations via Generative Augmentation**](https://arxiv.org/abs/2302.06671) | RSS 2023 | 2023-02-13 | [Github](https://github.com/genaug/genaug) |  |
| [**An Unbiased Look at Datasets for Visuo-Motor Pre-Training**](https://arxiv.org/abs/2310.09289) | CoRL 2023 | 2023-10-13 | [Github](https://github.com/SudeepDasari/data4robotics) |
| [**Diffusion Meets DAgger: Supercharging Eye-in-hand Imitation Learning**](https://arxiv.org/abs/2402.17768) | RSS 2024 | 2023-02-27 | [Github](https://github.com/ErinZhang1998/dmd_diffusion) |


## Affordance
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**SpatialBot: Precise Spatial Understanding with Vision Language Models**](https://arxiv.org/abs/2406.13642) | arXiv | 2024-06-19 | [Github](https://github.com/BAAI-DCAI/SpatialBot) | |
| [**RoboPoint: A Vision-Language Model for Spatial Affordance Prediction for Robotics**](https://arxiv.org/abs/2406.10721) | CoRL 2024 | 2024-06-15 | [Github](https://github.com/wentaoyuan/RoboPoint) | |
| |
| [**A3VLM: Actionable Articulation-Aware Vision Language Model**](https://arxiv.org/abs/2406.07549) | CoRL 2024 | 2024-06-14 | [Github](https://github.com/changhaonan/A3VLM) | |
| [**AIC MLLM: Autonomous Interactive Correction MLLM for Robust Robotic Manipulation**](https://arxiv.org/abs/2406.11548) | CoRL 2024 | 2024-06-17 | [Project](https://sites.google.com/view/aic-mllm) | |
| [**RAM: Retrieval-Based Affordance Transfer for Generalizable Zero-Shot Robotic Manipulation**](https://arxiv.org/abs/2407.04689) | CoRL 2024 | 2024-07-05 | [Github](https://github.com/yxKryptonite/RAM_code) | |
| [**Kinematic-aware Prompting for Generalizable Articulated Object Manipulation with LLMs**](https://arxiv.org/abs/2311.02847) | ICRA 2024 | 2023-11-06 | [Github](https://github.com/GeWu-Lab/LLM_articulated_object_manipulation) | |
| |
| [**SAGE: Bridging Semantic and Actionable Parts for Generalizable Manipulation of Articulated Objects**](https://arxiv.org/abs/2312.01307) | RSS 2024 | 2023-12-03 | [Github](https://github.com/geng-haoran/SAGE) | |




<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


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
| |
| [**GNFactor: Multi-Task Real Robot Learning with Generalizable Neural Feature Fields**](https://arxiv.org/abs/2308.16891) | CoRL 2023 | 2023-08-31 | [Github](https://github.com/YanjieZe/GNFactor) |  |
| [**ManiGaussian: Dynamic Gaussian Splatting for Multi-task Robotic Manipulation**](https://arxiv.org/abs/2403.08321) | ECCV 2024 | 2024-03-13 | [Github](https://github.com/GuanxingLu/ManiGaussian) |  |
| [**SAM-E: Leveraging Visual Foundation Model with Sequence Imitation for Embodied Manipulation**](https://arxiv.org/abs/2405.19586) | ICML 2024 | 2024-05-30 | [Github](https://github.com/pipixiaqishi1/SAM-E) |  |
| [**PolarNet: 3D Point Clouds for Language-Guided Robotic Manipulation**](https://arxiv.org/abs/2309.15596) | CoRL 2023 | 2023-09-27 | [Github](https://github.com/vlc-robot/polarnet) |  |
| [**RVT: Robotic View Transformer for 3D Object Manipulation**](https://arxiv.org/abs/2306.14896) | CoRL 2023 | 2023-06-26 | [Github](https://github.com/nvlabs/rvt) |  |
| [**Perceiver-Actor: A Multi-Task Transformer for Robotic Manipulation**](https://arxiv.org/abs/2209.05451) | CoRL 2022 | 2022-09-12 | [Github](https://github.com/peract/peract) |  |
| [**M2T2: Multi-Task Masked Transformer for Object-centric Pick and Place**](https://arxiv.org/abs/2311.00926) | CoRL 2023 | 2023-11-02 | [Github](https://github.com/NVlabs/M2T2) |  |
| |
| [**D<sup>3</sup>Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Rearrangement**](https://arxiv.org/abs/2309.16118) | CoRL 2024 | 2023-09-28 | [Github](https://github.com/WangYixuan12/d3fields) |  |



<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


## Planning and Reasoning
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Vocal Sandbox: Continual Learning and Adaptation for Situated Human-Robot Collaboration**](https://openreview.net/pdf?id=ypaYtV1CoG) | CoRL 2024 | - | [Project](https://vocal-sandbox.github.io/) |  |
| [**APRICOT: Active Preference Learning and Constraint-Aware Task Planning with LLMs**](https://openreview.net/pdf?id=nQslM6f7dW) | CoRL 2024 | - | [Project](https://portal-cornell.github.io/apricot/) |  |
| [**Text2Interaction: Establishing Safe and Preferable Human-Robot Interaction**](https://arxiv.org/abs/2408.06105) | CoRL 2024 | 2024-08-12 | [Github](https://github.com/JakobThumm/text2interaction) |  |
| |
| [**Teaching Robots with Show and Tell: Using Foundation Models to Synthesize Robot Policies from Language and Visual Demonstrations**](https://openreview.net/pdf?id=G8UcwxNAoD) | CoRL 2024 | - | [Project](https://robo-showtell.github.io/) |  |
| [**Text2Motion: From Natural Language Instructions to Feasible Plans**](https://arxiv.org/abs/2303.12153) | Autonomous Robots 2023 | 2023-03-21 | [Project](https://sites.google.com/stanford.edu/text2motion) |  |
| [**STAP: Sequencing Task-Agnostic Policies**](https://arxiv.org/abs/2210.12250) | ICRA 2023 | 2022-10-21 | [Github](https://github.com/agiachris/STAP) |  |
| [**Robots That Ask For Help: Uncertainty Alignment for Large Language Model Planners**](https://arxiv.org/abs/2307.01928) | CoRL 2023 | 2023-07-04 | [Github](https://github.com/google-research/google-research/tree/master/language_model_uncertainty) |  |
| [**Statler: State-Maintaining Language Models for Embodied Reasoning**](https://arxiv.org/abs/2306.17840) | ICRA 2024 | 2023-06-30 | [Github](https://github.com/ripl/statler) |  |
| [**InterPreT: Interactive Predicate Learning from Language Feedback for Generalizable Task Planning**](https://arxiv.org/abs/2405.19758) | RSS 2024 | 2023-05-30 | [Github](https://github.com/hmz-15/interactive-predicate-learning) |  |
| [**SayPlan: Grounding Large Language Models using 3D Scene Graphs for Scalable Robot Task Planning**](https://arxiv.org/abs/2310.10021) | CoRL 2023 | 2023-12-16 | [Github](https://github.com/clvrai/boss) | BOSS |
| |
| [**MOKA: Open-World Robotic Manipulation through Mark-Based Visual Prompting**](https://arxiv.org/abs/2403.03174) | RSS 2024 | 2024-03-05 | [Github](https://github.com/moka-manipulation/moka) |  |
| [**Polaris: Open-ended Interactive Robotic Manipulation via Syn2Real Visual Grounding and Large Language Models**](https://arxiv.org/abs/2408.07975) | IROS 2024 | 2024-08-15 | [Project](https://star-uu-wang.github.io/Polaris/) |  |
| [**Physically Grounded Vision-Language Models for Robotic Manipulation**](https://arxiv.org/abs/2309.02561) | ICRA 2024 | 2023-09-05 | [Project](https://iliad.stanford.edu/pg-vlm/) |  |
| |
| [**ManipLLM: Embodied Multimodal Large Language Model for Object-Centric Robotic Manipulation**](https://arxiv.org/abs/2312.16217) | CVPR 2024 | 2023-12-24 | [Github](https://github.com/clorislili/ManipLLM) |  |
| [**Chat with the Environment: Interactive Multimodal Perception Using Large Language Models**](https://arxiv.org/abs/2303.08268) | IROS 2023 | 2023-03-14 | [Github](https://github.com/xf-zhao/Matcha-agent) |  |




<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>



## Generalization and Generalist
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Scaling Cross-Embodied Learning: One Policy for Manipulation, Navigation, Locomotion and Aviation**](https://arxiv.org/abs/2408.11812) | CoRL 2024 | 2024-08-21 | [Github](https://github.com/rail-berkeley/crossformer) | Cross-Embodied |
| [**All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents**](https://arxiv.org/abs/2408.10899) | arXiv | 2024-08-20 | [Project](https://imaei.github.io/project_pages/ario/) | Cross-Embodied |
| |
| [**An Embodied Generalist Agent in 3D World**](https://arxiv.org/abs/2311.12871) | ICML 2024 | 2023-11-18 | [Github](https://github.com/embodied-generalist/embodied-generalist) |  |
| |
| [**Scaling Proprioceptive-Visual Learning with Heterogeneous Pre-trained Transformers**](https://arxiv.org/abs/2409.20537) | NeurIPS 2024 | 2024-09-30 | [Github](https://github.com/liruiw/HPT) |  |
| |
| [**Octo: An Open-Source Generalist Robot Policy**](https://arxiv.org/abs/2405.12213) | RSS 2024 | 2024-05-20 | [Github](https://github.com/octo-models/octo) | |
| [**Open X-Embodiment: Robotic Learning Datasets and RT-X Models**](https://arxiv.org/abs/2310.08864) | ICRA 2024 | 2023-10-13 | [Github](https://github.com/google-deepmind/open_x_embodiment) | |
| [**Steering Your Generalists: Improving Robotic Foundation Models via Value Guidance**](https://arxiv.org/abs/2410.13816) | CoRL 2024 | 2024-10-17 | [Project](https://nakamotoo.github.io/V-GPS/index.html) |  |
| [**Towards Synergistic, Generalized, and Efficient Dual-System for Robotic Manipulation**](https://arxiv.org/abs/2410.08001) | CoRL 2024 | 2024-10-10 | [Project](https://opendrivelab.com/RoboDual/) |  |
| [**Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning**](https://arxiv.org/abs/2407.15815) | CoRL 2024 | 2024-07-22 | [Project](https://gemcollector.github.io/maniwhere/) |  |
| [**CAGE: Causal Attention Enables Data-Efficient Generalizable Robotic Manipulation**](https://arxiv.org/abs/2407.15815) | arXiv | 2024-10-19 | [Project](https://cage-policy.github.io/) |  |
| [**Robot Utility Models: General Policies for Zero-Shot Deployment in New Environments**](https://arxiv.org/abs/2409.05865) | arXiv | 2024-09-09 | [Github](https://github.com/haritheja-e/robot-utility-models/) |  |
| Compositional Generalization |
| [**Policy Architectures for Compositional Generalization in Control**](https://arxiv.org/abs/2203.05960) | NeurIPSW 2022 | 2022-03-10 | [Github](https://github.com/facebookresearch/entity-factored-rl) | Compositional Generalization |
| [**Programmatically Grounded, Compositionally Generalizable Robotic Manipulation**](https://arxiv.org/abs/2304.13826) | ICLR 2023 | 2023-04-26 | [Project](https://progport.github.io/) | Compositional Generalization |
| [**Efficient Data Collection for Robotic Manipulation via Compositional Generalization**](https://arxiv.org/abs/2403.05110) | RSS 2024 | 2024-03-08 | [Project](https://iliad.stanford.edu/robot-data-comp/) | Compositional Generalization |
| Sim2Real |
| [**Natural Language Can Help Bridge the Sim2Real Gap**](https://arxiv.org/abs/2405.10020) | RSS 2024 | 2024-05-16 | [Github](https://github.com/UT-Austin-RobIn/lang4sim2real) |  |
| [**Reconciling Reality through Simulation: A Real-to-Sim-to-Real Approach for Robust Manipulation**](https://arxiv.org/abs/2403.03949) | RSS 2024 | 2024-03-06 | [Github](https://github.com/real-to-sim-to-real/RialToPolicyLearning) |  |
| Data |
| [**Mirage: Cross-Embodiment Zero-Shot Policy Transfer with Cross-Painting**](https://arxiv.org/abs/2402.19249) | RSS 2024 | 2024-02-29 | [Github](https://github.com/BerkeleyAutomation/mirage) |  |



<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>



## Mobile Manipulation
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**TaMMa: Target-driven Multi-subscene Mobile Manipulation**](https://openreview.net/pdf?id=EiqQEsOMZt) | CoRL 2024 | - | - |
| [**SayPlan: Grounding Large Language Models using 3D Scene Graphs for Scalable Robot Task Planning**](https://arxiv.org/abs/2307.06135) | CoRL 2023 | 2024-07-12 | [Project](https://sayplan.github.io/) |



<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


## Humanoid
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**OKAMI: Teaching Humanoid Robots Manipulation Skills through Single Video Imitation**](https://arxiv.org/abs/2410.11792) | CoRL 2024 | 2024-10-15 | [Project](https://ut-austin-rpl.github.io/OKAMI/)  |



<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


## Other Application
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**HANDLOOM: Learned Tracing of One-Dimensional Objects for Inspection and Manipulation**](https://arxiv.org/abs/2303.08975) | CoRL 2023 | 2023-03-15 | [Project](https://github.com/vainaviv/handloom)  |
| [**Predicting Object Interactions with Behavior Primitives: An Application in Stowing Tasks**](https://arxiv.org/abs/2309.16873) | CoRL 2023 | 2023-09-28 | [Github](https://github.com/haonan16/Stow/)  |




<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>



# Awesome-benchmarks
## Evaluating methods 
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Contrast Sets for Evaluating Language-Guided Robot Policies**](https://arxiv.org/abs/2406.13636) | CoRL 2024 | 2024-06-19 | - |  |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


## Grasp Datasets
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Real-to-Sim Grasp: Rethinking the Gap between Simulation and Real World in Grasp Detection**](https://arxiv.org/abs/2410.06521) | CoRL 2024 | 2024-10-09 | [Project](https://isee-laboratory.github.io/R2SGrasp/) | |
| [**Language-Driven 6-DoF Grasp Detection Using Negative Prompt Guidance**](https://arxiv.org/abs/2407.13842) | ECCV 2024 | 2024-07-18 | [Github](https://github.com/Fsoft-AIC/Language-Driven-6-DoF-Grasp-Detection-Using-Negative-Prompt-Guidance) | Grasp-Anything-6D |
| [**Language-driven Grasp Detection**](https://arxiv.org/abs/2406.09489) | CVPR 2024 | 2024-06-13 | [Github](https://github.com/Fsoft-AIC/LGD) | Grasp-Anything++ |
| [**Grasp-Anything: Large-scale Grasp Dataset from Foundation Models**](https://arxiv.org/abs/2309.09818) | ICRA 2024 | 2023-09-18 | [Github](https://github.com/Fsoft-AIC/Grasp-Anything) | Grasp-Anything |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


## Manipulation Benchmarks
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots**](https://arxiv.org/abs/2406.02523) | RSS 2024 | 2024-06-04 | [Github](https://github.com/robocasa/robocasa) |  |
| [**GenSim2: Scaling Robot Data Generation with Multi-modal and Reasoning LLMs**](https://arxiv.org/abs/2410.03645) | CoRL 2024 | 2024-10-04 | [Github](https://github.com/GenSim2/gensim2) |
| [**THE COLOSSEUM: A Benchmark for Evaluating Generalization for Robotic Manipulation**](https://arxiv.org/abs/2402.08191) | RSS 2024 | 2024-02-13 | [Github](https://github.com/robot-colosseum/robot-colosseum) | |
| [**Evaluating Real-World Robot Manipulation Policies in Simulation**](https://arxiv.org/abs/2405.05941) | CoRL 2024 | 2024-05-09 | [Github](https://github.com/simpler-env/SimplerEnv) | For VLA |
| [**LADEV: A Language-Driven Testing and Evaluation Platform for Vision-Language-Action Models in Robotic Manipulation**](https://arxiv.org/abs/2405.05941) | CoRL 2024 | 2024-05-09 | [Github](https://github.com/simpler-env/SimplerEnv) | For VLA |
| [**KitchenShift: Evaluating Zero-Shot Generalization of Imitation-Based Policy Learning Under Domain Shifts**](https://arxiv.org/abs/2410.05191) | arXiv |2024-10-07 | -   |
| |
| [**Open X-Embodiment: Robotic Learning Datasets and RT-X Models**](https://arxiv.org/abs/2310.08864) | ICRA 2024 | 2023-10-13 | [Github](https://github.com/google-deepmind/open_x_embodiment) | |
| [**DROID: A Large-Scale In-The-Wild Robot Manipulation Dataset**](https://arxiv.org/abs/2403.12945) | ICRA 2024 | 2024-03-19 | [Project](https://droid-dataset.github.io/) | |




<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>


## Cross-Embodiment Benchmarks
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents**](https://arxiv.org/abs/2408.10899) | arXiv | 2024-08-20 | [Dataset](https://openi.pcl.ac.cn/ARIO/ARIO_Dataset) | |
| [**Where are we in the search for an Artificial Visual Cortex for Embodied Intelligence?**](https://arxiv.org/abs/2408.10899) | arXiv | 2024-08-20 | [Dataset](https://openi.pcl.ac.cn/ARIO/ARIO_Dataset) | |

<p align=right>(<a href=#awesome-robotics-manipulation>back to top</a>)</p>




# Awesome-techniques
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| **Awesome-Robotics-3D** | - | - | [Github](https://github.com/zubair-irshad/Awesome-Robotics-3D) | |


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





