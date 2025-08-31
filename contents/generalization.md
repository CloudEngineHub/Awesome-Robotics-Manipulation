<h2 id="table-of-contents">🏠 Table of Contents</h2>

- Generalization
    - [Task Generalization](#task-generalization)
        - [Compositional Generalization](#compositional-generalization)
        - [Cross-Embodiment Generalization](#cross-embodiment-generalization)
        - [Long-horizon Generalization](#long-horizon-generalization)
        - [Few-shot Learning](#few-shot-generalization)
        - [Meta Learning](#meta-generalization)
        - [Lifelong/Continual/Incremental Learning](#lifelongcontinualincremental-learning)
        - [Incremental Learning](#incremental-learning)
        - [Test-Time Adaptation](#test-time-adaptation)
    - [Environment Generalization](#environment-generalization)
        - [Sim2Real or Real2Real Generalization](#sim2real-or-real2real-generalization)
        - [SE(3)/SIM(3)-Equivariance (View Changes)](#se3sim3-equivariance-view-changes)
        - [Lighting/background/distractor Changes](#lightingbackgrounddistractor-changes)



## Task Generalization

### Compositional Generalization
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Efficient Data Collection for Robotic Manipulation via Compositional Generalization**](https://arxiv.org/abs/2403.05110) | RSS 2024 | 2024-03-08 | [Project](https://iliad.stanford.edu/robot-data-comp/) | Compositional Generalization |
| [PROGRAMPORT: **Programmatically Grounded, Compositionally Generalizable Robotic Manipulation**](https://arxiv.org/abs/2304.13826) | ICLR 2023 | 2023-04-26 | [Project](https://progport.github.io/) | Compositional Generalization |
| [**Policy Architectures for Compositional Generalization in Control**](https://arxiv.org/abs/2203.05960) | NeurIPSW 2022 | 2022-03-10 | ![Star](https://img.shields.io/github/stars/facebookresearch/entity-factored-rl?style=social&label=Star) [Github](https://github.com/facebookresearch/entity-factored-rl) | Compositional Generalization |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Cross-Embodiment Generalization
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**3DFlowAction: Learning Cross-Embodiment Manipulation from 3D Flow World Model**](https://arxiv.org/abs/2506.06199) | arXiv | 2025-06-06 | ![Star](https://img.shields.io/github/stars/Hoyyyaard/3DFlowAction?style=social&label=Star) [Github](https://github.com/Hoyyyaard/3DFlowAction/) |  |
| [**RoboOS: A Hierarchical Embodied Framework for Cross-Embodiment and Multi-Agent Collaboration**](https://arxiv.org/abs/2505.03673) | arXiv | 2025-05-06 | ![Star](https://img.shields.io/github/stars/FlagOpen/RoboOS?style=social&label=Star) [Github](https://github.com/FlagOpen/RoboOS) |  |
| [**X-Sim: Cross-Embodiment Learning via Real-to-Sim-to-Real**](http://arxiv.org/abs/2505.07096) | arXiv | 2025-05-11 | ![Star](https://img.shields.io/github/stars/portal-cornell/X-Sim?style=social&label=Star) [Github](https://github.com/portal-cornell/X-Sim) |  |
| [**Crossing the Human-Robot Embodiment Gap with Sim-to-Real RL using One Human Demonstration**](https://arxiv.org/abs/2504.12609) | arXiv | 2025-04-17 | ![Star](https://img.shields.io/github/stars/tylerlum/human2sim2robot?style=social&label=Star) [Github](https://github.com/tylerlum/human2sim2robot) |  |
| [**LEGATO: Cross-Embodiment Imitation Using a Grasping Tool**](https://arxiv.org/abs/2411.03682) | RA-L 2025 | 2024-11-06 | ![Star](https://img.shields.io/github/stars/UT-HCRL/LEGATO?style=social&label=Star) [Github](https://github.com/UT-HCRL/LEGATO) | |
| [**Cross-Embodiment Robot Manipulation Skill Transfer using Latent Space Alignment**](https://arxiv.org/abs/2406.01968) | arXiv | 2024-06-04 | ![Star](https://img.shields.io/github/stars/ExistentialRobotics/cross_embodiment_transfer?style=social&label=Star) [Github](https://github.com/ExistentialRobotics/cross_embodiment_transfer) | |
| [HPT: **Scaling Proprioceptive-Visual Learning with Heterogeneous Pre-trained Transformers**](https://arxiv.org/abs/2409.20537) | NeurIPS 2024 | 2024-09-30 | ![Star](https://img.shields.io/github/stars/liruiw/HPT?style=social&label=Star) [Github](https://github.com/liruiw/HPT) |  |
| [CrossFormer: **Scaling Cross-Embodied Learning: One Policy for Manipulation, Navigation, Locomotion and Aviation**](https://arxiv.org/abs/2408.11812) | CoRL 2024 | 2024-08-21 | ![Star](https://img.shields.io/github/stars/rail-berkeley/crossformer?style=social&label=Star) [Github](https://github.com/rail-berkeley/crossformer) | Cross-Embodied |
| [**Pushing the Limits of Cross-Embodiment Learning for Manipulation and Navigation**](https://arxiv.org/abs/2402.19432) | RSS 2024 | 2024-02-29 | ![Star](https://img.shields.io/github/stars/JonathanYang0127/omnimimic?style=social&label=Star) [Github](https://github.com/JonathanYang0127/omnimimic) | |
| [**Mirage: Cross-Embodiment Zero-Shot Policy Transfer with Cross-Painting**](https://arxiv.org/abs/2402.19249) | RSS 2024 | 2024-02-29 | ![Star](https://img.shields.io/github/stars/BerkeleyAutomation/mirage?style=social&label=Star) [Github](https://github.com/BerkeleyAutomation/mirage) | |
| [**XSkill: Cross Embodiment Skill Discovery**](https://arxiv.org/abs/2307.09955) | CoRL 2023 | 2023-07-19 | ![Star](https://img.shields.io/github/stars/real-stanford/xskill?style=social&label=Star) [Github](https://github.com/real-stanford/xskill) | |
| [**Modularity through Attention: Efficient Training and Transfer of Language-Conditioned Policies for Robot Manipulation**](https://arxiv.org/abs/2212.04573) | CoRL 2022 | 2022-12-08 | ![Star](https://img.shields.io/github/stars/ir-lab/ModAttn?style=social&label=Star) [Github](https://github.com/ir-lab/ModAttn) | |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Long-horizon Generalization
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Long-VLA: Unleashing Long-Horizon Capability of Vision Language Action Model for Robot Manipulation**](https://arxiv.org/abs/2508.19958) | CoRL 2025 | 2025-08-27 | [Project](https://long-vla.github.io/) | |
| [**BT-TL-DMPs: A Novel Robot TAMP Framework Combining Behavior Tree, Temporal Logic and Dynamical Movement Primitives**](https://arxiv.org/abs/2507.14582) | arXiv | 2025-07-19 | - | |
| [**Look Before You Leap: Using Serialized State Machine for Language Conditioned Robotic Manipulation**](https://arxiv.org/abs/2503.05114) | arXiv | 2025-03-07 | [Project](https://hd-space-robotics.github.io/) | |
| [**Bootstrapping Imitation Learning for Long-horizon Manipulation via Hierarchical Data Collection Space**](https://arxiv.org/abs/2505.17389) | arXiv | 2025-05-23 | [Project](https://hd-space-robotics.github.io/) | |
| [**RoboHorizon: An LLM-Assisted Multi-View World Model for Long-Horizon Robotic Manipulation**](https://arxiv.org/abs/2501.06605) | arXiv | 2025-01-11 | - | |
| [**The Art of Imitation: Learning Long-Horizon Manipulation Tasks from Few Demonstrations**](https://arxiv.org/abs/2407.13432) | arXiv | 2024-07-18 | ![Star](https://img.shields.io/github/stars/robot-learning-freiburg/TAPAS?style=social&label=Star) [Github](https://github.com/robot-learning-freiburg/TAPAS) |  |
| [**DexSkills: Skill Segmentation Using Haptic Data for Learning Autonomous Long-Horizon Robotic Manipulation Tasks**](https://arxiv.org/abs/2405.03476) | arXiv | 2024-05-06 | ![Star](https://img.shields.io/github/stars/ARQ-CRISP/DexSkills?style=social&label=Star) [Github](https://github.com/ARQ-CRISP/DexSkills) |  |
| [**What's the Move? Hybrid Imitation Learning via Salient Points**](https://arxiv.org/abs/2412.05426) | ICLR 2025 | 2024-12-06 | ![Star](https://img.shields.io/github/stars/priyasundaresan/sphinx?style=social&label=Star) [Github](https://github.com/priyasundaresan/sphinx) | |
| [**Hierarchical Hybrid Learning for Long-Horizon Contact-Rich Robotic Assembly**](https://arxiv.org/abs/2409.16451) | arXiv | 2024-09-24 | [Project](https://long-horizon-assembly.github.io/) | |
| [TBBF: **A Backbone for Long-Horizon Robot Task Understanding**](https://arxiv.org/abs/2408.01334) | RA-L 2025 | 2024-08-02 | [Project](https://sites.google.com/view/therbligsbasedbackbone/home) | |
| [**SCaR: Refining Skill Chaining for Long-Horizon Robotic Manipulation via Dual Regularization**](https://openreview.net/forum?id=RnxJc4vTVi) | NeurIPS 2024 | 2024-09-26 | [Project](https://sites.google.com/view/scar8297) | |
| [ManipGen: **Local Policies Enable Zero-shot Long-horizon Manipulation**](https://arxiv.org/abs/2410.22332) | CoRLW 2024 | 2024-10-29 | [Project](https://mihdalal.github.io/manipgen/) | |
| [BLADE: **Learning Compositional Behaviors from Demonstration and Language**](https://arxiv.org/abs/2505.21981) | CoRL 2024 | 2025-05-28 | [Project](https://blade-bot.github.io/) | IL, RepL, Poliy Head, Few-Shot Policy Adaptation |
| [PALO: **Policy Adaptation via Language Optimization: Decomposing Tasks for Few-Shot Imitation**](https://arxiv.org/abs/2408.16228) | CoRL 2024 | 2024-08-29 | ![Star](https://img.shields.io/github/stars/vivekmyers/palo?style=social&label=Star) [Github](https://github.com/vivekmyers/palo) | Fine-grained Atom Action |
| [**PRIME: Scaffolding Manipulation Tasks with Behavior Primitives for Data-Efficient Imitation Learning**](https://arxiv.org/abs/2403.00929) | RA-L 2024 | 2024-03-01 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/PRIME?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/PRIME) |  |
| [**Hierarchical Human-to-Robot Imitation Learning for Long-Horizon Tasks via Cross-Domain Skill Alignment**](https://ieeexplore.ieee.org/document/10610084) | ICRA 2024 | 2024-08-08 | - | |
| [**GO-DICE: Goal-Conditioned Option-Aware Offline Imitation Learning via Stationary Distribution Correction Estimation**](https://arxiv.org/abs/2312.10802) | AAAI 2024 | 2023-12-17 | - |  |
| [**Hybrid Hierarchical Learning for Solving Complex Sequential Tasks Using the Robotic Manipulation Network ROMAN**](https://arxiv.org/abs/2307.00125) | NMI 2023 | 2023-07-30 | - |  |
| [BOSS: **Bootstrap Your Own Skills: Learning to Solve New Tasks with Large Language Model Guidance**](https://arxiv.org/abs/2310.10021) | CoRL 2023 | 2023-12-16 | ![Star](https://img.shields.io/github/stars/clvrai/boss?style=social&label=Star) [Github](https://github.com/clvrai/boss) | Skill Bootstrapping |
| [**HYDRA: Hybrid Robot Actions for Imitation Learning**](https://arxiv.org/abs/2306.17237) | CoRL 2023 | 2023-06-29 | [Project](https://sites.google.com/view/hydra-il-2023) |  |
| [**STAP: Sequencing Task-Agnostic Policies**](https://arxiv.org/abs/2210.12250) | ICRA 2023 | 2022-10-21 | ![Star](https://img.shields.io/github/stars/agiachris/STAP?style=social&label=Star) [Github](https://github.com/agiachris/STAP) |  |
| [**Divide & Conquer Imitation Learning**](https://arxiv.org/abs/2204.07404) | IROS 2022 | 2022-02-15 | - |  |
| [**Bottom-Up Skill Discovery from Unsegmented Demonstrations for Long-Horizon Robot Manipulation**](https://arxiv.org/abs/2109.13841) | RA-L 2022 | 2021-09-28 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/BUDS?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/BUDS) |  |
| [**Adversarial Skill Chaining for Long-Horizon Robot Manipulation via Terminal State Regularization**](https://arxiv.org/abs/2111.07999) | CoRL 2021 | 2021-11-15 | ![Star](https://img.shields.io/github/stars/clvrai/skill-chaining?style=social&label=Star) [Github](https://github.com/clvrai/skill-chaining) |  |
| [**Sequential Robot Imitation Learning from Observations**](https://journals.sagepub.com/doi/abs/10.1177/02783649211032721) | IJRR 2021 | 2021-08-06 | - |  |
| [**SQUIRL: Robust and Efficient Learning from Video Demonstration of Long-Horizon Robotic Manipulation Tasks**](https://arxiv.org/abs/2003.04956) | IROS 2020 | 2020-03-10 | [Project](https://crlab.cs.columbia.edu/squirl/) |  |
| [**Learning to Generalize Across Long-Horizon Tasks from Human Demonstrations**](https://arxiv.org/abs/2003.06085) | RSS 2020 | 2020-03-13 | [Project](https://sites.google.com/view/gti2020/) |  |
| [**Learning to Combine Primitive Skills: A Step towards Versatile Robotic Manipulation**](https://arxiv.org/abs/1908.00722) | ICRA 2020 | 2019-08-02 | ![Star](https://img.shields.io/github/stars/rstrudel/rlbc?style=social&label=Star) [Github](https://github.com/rstrudel/rlbc) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Few-shot Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Elastic Motion Policy: An Adaptive Dynamical System for Robust and Efficient One-Shot Imitation Learning**](https://arxiv.org/abs/2503.08029) | IROS 2025 | 2025-03-11 | [Project](https://elastic-motion-policy.github.io/EMP/) |  |
| [**VidBot: Learning Generalizable 3D Actions from In-the-Wild 2D Human Videos for Zero-Shot Robotic Manipulation**](https://arxiv.org/abs/2503.07135) | CVPR 2025 | 2025-03-10 | [Project](https://hanzhic.github.io/vidbot-project/) |  |
| [**One-Shot Dual-Arm Imitation Learning**](https://arxiv.org/abs/2503.06831) | ICRA 2025 | 2025-03-10 | [Project](https://www.robot-learning.uk/one-shot-dual-arm) |  |
| [**You Only Teach Once: Learn One-Shot Bimanual Robotic Manipulation from Video Demonstrations**](https://arxiv.org/abs/2501.14208) | RSS 2025 | 2025-01-24 | ![Star](https://img.shields.io/github/stars/hnuzhy/YOTO?style=social&label=Star) [Github](https://github.com/hnuzhy/YOTO) |  |
| [**Zero-Shot Offline Imitation Learning via Optimal Transport**](https://arxiv.org/abs/2410.08751) | arXiv | 2024-10-11 | ![Star](https://img.shields.io/github/stars/martius-lab/zilot?style=social&label=Star) [Github](https://github.com/martius-lab/zilot) |  |
| [**Vision-based Manipulation from Single Human Video with Open-World Object Graphs**](https://arxiv.org/abs/2405.20321) | CoRLW 2024 | 2024-05-30 | [Project](https://ut-austin-rpl.github.io/ORION-release/) |  |
| [**DITTO: Demonstration Imitation by Trajectory Transformation**](https://arxiv.org/abs/2403.15203) | IROS 2024 | 2024-03-22 | ![Star](https://img.shields.io/github/stars/robot-learning-freiburg/DITTO?style=social&label=Star) [Github](https://github.com/robot-learning-freiburg/DITTO) |  
| [**CoBT: Collaborative Programming of Behaviour Trees from One Demonstration for Robot Manipulation**](https://arxiv.org/abs/2404.05870) | ICRA 2024 | 2024-04-08 | ![Star](https://img.shields.io/github/stars/jainaayush2006/CoBT?style=social&label=Star) [Github](https://github.com/jainaayush2006/CoBT) |  
| [**Zero-Shot Visual Generalization in Robot Manipulation**](https://arxiv.org/abs/2505.11719) | arXiv | 2022-05-16 | [Project](https://sites.google.com/view/vis-gen-robotics/home) |  |
| [**One-Shot Domain-Adaptive Imitation Learning via Progressive Learning**](https://arxiv.org/abs/2204.11251) | TASE 2022 | 2022-04-24 | - |  |
| [**Demonstrate Once, Imitate Immediately (DOME): Learning Visual Servoing for One-Shot Imitation Learning**](https://arxiv.org/abs/2204.02863) | IROS 2022 | 2022-04-06 | [Project](https://www.robot-learning.uk/dome) |  |
| [**Coarse-to-Fine Imitation Learning: Robot Manipulation from a Single Demonstration**](https://arxiv.org/abs/2105.06411) | ICRA 2021 | 2021-05-13 | [Project](https://www.robot-learning.uk/coarse-to-fine-imitation-learning) |  |
| [**SOZIL: Self-Optimal Zero-Shot Imitation Learning**](https://ieeexplore.ieee.org/document/9552943) | TCDS 2021 | 2021-09-30 | - |  |
| [**Zero-Shot Visual Imitation**](https://arxiv.org/abs/1804.08606) | ICLR 2018  | 2018-04-23 | ![Star](https://img.shields.io/github/stars/pathak22/zeroshot-imitation?style=social&label=Star) [Github](https://github.com/pathak22/zeroshot-imitation) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Meta Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Few-Shot Vision-Language Action-Incremental Policy Learning**](https://arxiv.org/abs/2504.15517) | arXiv | 2025-04-22 | ![Star](https://img.shields.io/github/stars/codeshop715/FSAIL?style=social&label=Star) [Github](https://github.com/codeshop715/FSAIL) |  |
| [**Learning Generalizable 3D Manipulation With 10 Demonstrations**](https://arxiv.org/abs/2411.10203) | arXiv | 2024-11-15 | ![Star](https://img.shields.io/github/stars/renyu2016/Generalized-3D-Manipulation?style=social&label=Star) [Github](https://github.com/renyu2016/Generalized-3D-Manipulation) |  |
| [**One-Shot Imitation Learning with Invariance Matching for Robotic Manipulation**](https://arxiv.org/abs/2405.13178) | RSS 2024 | 2024-05-21 | ![Star](https://img.shields.io/github/stars/mlzxy/imop?style=social&label=Star) [Github](https://github.com/mlzxy/imop) | |
| [**One-Shot Imitation Learning With Graph Neural Networks for Pick-and-Place Manipulation Tasks**](https://ieeexplore.ieee.org/document/10202200/) | RA-L 2023 | 2023-08-02 | - |
| [**One-Shot Imitation Learning: A Pose Estimation Perspective**](https://arxiv.org/pdf/2310.12077) | CoRL 2023 | 2023-10-18 | [Project](https://www.robot-learning.uk/pose-estimation-perspective) |  |
| [**One-shot Imitation Learning via Interaction Warping**](https://arxiv.org/abs/2306.12392) | CoRL 2023 | 2023-06-21 | ![Star](https://img.shields.io/github/stars/ondrejbiza/shapewarping?style=social&label=Star) [Github](https://github.com/ondrejbiza/shapewarping) |
| [**Teach a Robot to FISH: Versatile Imitation from One Minute of Demonstrations**](https://arxiv.org/abs/2303.01497) | RSS 2023 | 2023-03-02 | ![Star](https://img.shields.io/github/stars/siddhanthaldar/FISH?style=social&label=Star) [Github](https://github.com/siddhanthaldar/FISH) |
| [**Meta-Reinforcement Learning via Language Instructions**](https://arxiv.org/abs/2209.04924) | ICRA 2023 | 2022-09-11 | ![Star](https://img.shields.io/github/stars/yaoxt3/MILLION?style=social&label=Star) [Github](https://github.com/yaoxt3/MILLION) |
| [**Transfering Hierarchical Structure with Dual Meta Imitation Learning**](https://arxiv.org/abs/2201.11981) | CoRL 2022 | 2022-01-28 | - |
| [**Towards More Generalizable One-shot Visual Imitation Learning**](https://arxiv.org/abs/2110.13423) | ICRA 2022 | 2021-10-26 | ![Star](https://img.shields.io/github/stars/rll-research/mosaic?style=social&label=Star) [Github](https://github.com/rll-research/mosaic) | | 
| [**Attentive One-Shot Meta-Imitation Learning From Visual Demonstration**](https://ieeexplore.ieee.org/document/9812281) | ICRA 2022 | 2021-07-12 | - | | 
| [**Meta-Imitation Learning by Watching Video Demonstrations**](https://openreview.net/forum?id=KTPuIsx4pmo) | ICLR 2022 | 2022-01-29 | - | | 
| [**Visual Goal-Directed Meta-Learning with Contextual Planning Networks**](https://arxiv.org/abs/2111.09908) | CVPRW 2021 | 2021-11-18 | - | | 
| [**Watch, Try, Learn: Meta-Learning from Demonstrations and Reward**](https://arxiv.org/abs/1906.03352) | ICLR 2020 | 2019-06-07 | - | | 
| [**One-Shot Hierarchical Imitation Learning of Compound Visuomotor Tasks**](https://arxiv.org/abs/1810.11043) | arXiv | 2018-10-08 | [Project](https://sites.google.com/view/one-shot-hil) | | 
| [**Task-Embedded Control Networks for Few-Shot Imitation Learning**](https://arxiv.org/abs/1810.03237) | CoRL 2018 | 2018-10-08 | ![Star](https://img.shields.io/github/stars/stepjam/TecNets?style=social&label=Star) [Github](https://github.com/stepjam/TecNets) | | 
| [**One-Shot Imitation from Observing Humans via Domain-Adaptive Meta-Learning**](https://arxiv.org/abs/1802.01557) | RSS 2018 | 2018-02-05 | ![Star](https://img.shields.io/github/stars/tianheyu927/mil?style=social&label=Star) [Github](https://github.com/tianheyu927/mil) | | 
| [**One-Shot Visual Imitation Learning via Meta-Learning**](https://arxiv.org/abs/1709.04905) | CoRL 2017 | 2017-09-14 | ![Star](https://img.shields.io/github/stars/tianheyu927/mil?style=social&label=Star) [Github](https://github.com/tianheyu927/mil) | | 
| [**One-Shot Imitation Learning**](https://arxiv.org/abs/1703.07326) | NeurIPS 2017 | 2017-03-21 | [Project](https://sites.google.com/view/nips2017-one-shot-imitation/home) | | 

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Lifelong/Continual/Incremental Learning
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**T2S: Tokenized Skill Scaling for Lifelong Imitation Learning**](https://arxiv.org/abs/2508.01167) | arXiv | 2025-08-12 | - |  |
| [**Dynamic Mixture of Progressive Parameter-Efficient Expert Library for Lifelong Robot Learning**](https://arxiv.org/abs/2506.05985) | arXiv | 2025-06-06 | - |  |
| [**SPECI: Skill Prompts based Hierarchical Continual Imitation Learning for Robot Manipulation**](https://arxiv.org/abs/2504.15561) | arXiv | 2025-04-22 | - |  |
| [**Think Small, Act Big: Primitive Prompt Learning for Lifelong Robot Manipulation**](https://arxiv.org/abs/2504.00420) | CVPR 2025 | 2025-04-01 | - |  |
| [**iManip: Skill-Incremental Learning for Robotic Manipulation**](https://arxiv.org/abs/2503.07087) | arXiv | 2025-03-10 | - |  |
| [**M2Distill: Multi-Modal Distillation for Lifelong Imitation Learning**](https://arxiv.org/abs/2410.00064) | ICRA 2025 | 2024-10-30 | - |  |
| [**LOTUS: Continual Imitation Learning for Robot Manipulation Through Unsupervised Skill Discovery**](https://arxiv.org/abs/2311.02058) | ICRA 2024 | 2023-11-03 | ![Star](https://img.shields.io/github/stars/UT-Austin-RPL/Lotus?style=social&label=Star) [Github](https://github.com/UT-Austin-RPL/Lotus) |  |
| [**CRIL: Continual Robot Imitation Learning via Generative and Prediction Model**](https://arxiv.org/abs/2106.09422) | IROS 2021 | 2021-06-17 | ![Star](https://img.shields.io/github/stars/HeegerGao/CRIL?style=social&label=Star) [Github](https://github.com/HeegerGao/CRIL) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Test-Time Adaptation
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Adapting by Analogy: OOD Generalization of Visuomotor Policies via Functional Correspondence**](https://arxiv.org/abs/2506.12678) | arXiv | 2025-06-15 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>



## Environment Generalization

### Sim2Real or Real2Real Generalization
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Real2Render2Real: Scaling Robot Data Without Dynamics Simulation or Robot Hardware**](https://arxiv.org/abs/2505.09601) | arXiv | 2025-05-14 | [Project](https://real2render2real.com/) |  |
| [**Sim-and-Real Co-Training: A Simple Recipe for Vision-Based Robotic Manipulation**](https://arxiv.org/abs/2405.10020) | arXiv | 2025-03-31 | [Project](https://co-training.github.io/) |  |
| [**Robot Policy Evaluation for Sim-to-Real Transfer: A Benchmarking Perspective**](https://arxiv.org/abs/2508.11117) | RSSW 2025 | 2025-08-14 | - |  |
| [**ScissorBot: Learning Generalizable Scissor Skill for Paper Cutting via Simulation, Imitation, and Sim2Real**](https://arxiv.org/abs/2409.13966) | CoRL 2024 | 2024-09-21 | ![Star](https://img.shields.io/github/stars/jiangranlv/ScissorBot?style=social&label=Star) [Github](https://github.com/jiangranlv/ScissorBot) |  |
| [Maniwhere: **Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning**](https://arxiv.org/abs/2407.15815) | CoRL 2024 | 2024-07-22 | [Project](https://gemcollector.github.io/maniwhere/) |  |
| [**Natural Language Can Help Bridge the Sim2Real Gap**](https://arxiv.org/abs/2405.10020) | RSS 2024 | 2024-05-16 | ![Star](https://img.shields.io/github/stars/UT-Austin-RobIn/lang4sim2real?style=social&label=Star) [Github](https://github.com/UT-Austin-RobIn/lang4sim2real) |  |
| [RialTo: **Reconciling Reality through Simulation: A Real-to-Sim-to-Real Approach for Robust Manipulation**](https://arxiv.org/abs/2403.03949) | RSS 2024 | 2024-03-06 | ![Star](https://img.shields.io/github/stars/real-to-sim-to-real/RialToPolicyLearning?style=social&label=Star) [Github](https://github.com/real-to-sim-to-real/RialToPolicyLearning) |  |
| [**Practical Visual Deep Imitation Learning via Task-Level Domain Consistency**](https://ieeexplore.ieee.org/document/10161202) | ICRA 2023 | 2023-07-04 | - |  |
| [**RetinaGAN: An Object-aware Approach to Sim-to-Real Transfer**](https://arxiv.org/abs/2011.03148) | ICRA 2021 | 2020-11-06 | [Project](https://retinagan.github.io/) |  |
| [**Self-Supervised Sim-to-Real Adaptation for Visual Robotic Manipulation**](https://arxiv.org/abs/1910.09470) | ICRA 2020 | 2019-10-21 | - |  |
| [**Transferring Visuomotor Learning from Simulation to the Real World for Robotics Manipulation Tasks**](https://ieeexplore.ieee.org/document/8594519) | IROS 2018 | 2019-01-06 | - |  |
| [**Sim-to-Real Transfer of Robotic Control with Dynamics Randomization**](https://arxiv.org/abs/1710.06537) | ICRA 2018 | 2017-10-18 | - |  |
| [Domain Randomization: **Sim-to-Real Transfer of Robotic Control with Dynamics Randomization**](https://arxiv.org/abs/1710.06537) | ICRA 2018 | 2017-10-18 | - |  |
| [**Transferring End-to-End Visuomotor Control from Simulation to Real World for a Multi-Stage Task**](https://arxiv.org/abs/1710.06537) | CoRL 2017 | 2017-07-07 | - |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### SE(3)/SIM(3)-Equivariance (View Changes)
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Vision in Action: Learning Active Perception from Human Demonstrations**](https://arxiv.org/abs/2506.15666) | arXiv | 2025-06-18 | ![Star](https://img.shields.io/github/stars/haoyu-x/vision-in-action?style=social&label=Star) [Github](https://github.com/haoyu-x/vision-in-action) | |
| [**Imitation Learning for Active Neck Motion Enabling Robot Manipulation beyond the Field of View**](https://arxiv.org/abs/2506.17624) | arXiv | 2025-06-21 | - | View Changes |
| [**Adapt3R: Adaptive 3D Scene Representation for Domain Transfer in Imitation Learning**](https://arxiv.org/abs/2503.04877) | arXiv | 2025-03-06 | ![Star](https://img.shields.io/github/stars/pairlab/Adapt3R?style=social&label=Star) [Github](https://github.com/pairlab/Adapt3R) | View Changes & Cross-Embodiment |
| [**ET-SEED: Efficient Trajectory-Level SE(3) Equivariant Diffusion Policy**](https://arxiv.org/abs/2411.03990) | ICLR 2025 | 2024-11-06 | ![Star](https://img.shields.io/github/stars/yuechen0614/ET-SEED?style=social&label=Star) [Github](https://github.com/yuechen0614/ET-SEED) |  |
| [**EquiBot: SIM(3)-Equivariant Diffusion Policy for Generalizable and Data Efficient Learning**](https://arxiv.org/abs/2407.01479) | CoRL 2024 | 2024-07-01 | ![Star](https://img.shields.io/github/stars/yjy0625/equibot?style=social&label=Star) [Github](https://github.com/yjy0625/equibot) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>

### Lighting/background/distractor Changes
<!-- |  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
|  Title  |   Venue  |   Date   |   Code   | 
|:--------|:--------:|:--------:|:--------:|
| [**Physically-based Lighting Augmentation for Robotic Manipulation**](https://www.arxiv.org/abs/2508.01442) | arXiv | 2025-08-02 | - | Lighting Changes |
| [**Is an object-centric representation beneficial for robotic manipulation ?**](https://arxiv.org/abs/2506.19408) | arXiv | 2025-06-24 | - |  |
| [**SwitchVLA: Execution-Aware Task Switching for Vision-Language-Action Models**](https://arxiv.org/abs/2506.03574) | arXiv | 2025-06-04 | [Project](https://switchvla.github.io/) | |
| [**Diffusion-VLA: Scaling Robot Foundation Models via Unified Diffusion and Autoregression**](https://arxiv.org/abs/2412.03293) | ICML 2025 | 2024-12-14 | [Project](https://diffusion-vla.github.io/) |  |
| [**Decomposing the Generalization Gap in Imitation Learning for Visual Robotic Manipulation**](https://arxiv.org/abs/2307.03659) | ICRA 2024 | 2024-02-29 | ![Star](https://img.shields.io/github/stars/RLAgent/factor-world?style=social&label=Star) [Github](https://github.com/RLAgent/factor-world) | 
| [**Decomposing the Generalization Gap in Imitation Learning for Visual Robotic Manipulation**](https://arxiv.org/abs/2307.03659) | ICRA 2024 | 2023-07-07 | ![Star](https://img.shields.io/github/stars/RLAgent/factor-world?style=social&label=Star) [Github](https://github.com/RLAgent/factor-world) |  |
| [**Robot Learning from Human Demonstrations with Inconsistent Contexts**](https://www.sciencedirect.com/science/article/pii/S0921889023001057) | RAS 2023 | 2023-06-01 | - |  |
| [**Spatial Generalization of Visual Imitation Learning with Position-Invariant Regularization**](https://openreview.net/forum?id=N00uQFLlvHC) | RSSW 2023 | 2023-06-24 | - | Position Changes |
| [**Cross-context Visual Imitation Learning from Demonstrations**](https://ieeexplore.ieee.org/document/9196868) | ICRA 2020 | 2020-09-16 | [Project](https://vsislab.github.io/ccvil/) |  |

<p align="right">(<a href="#table-of-contents">back to top</a>)</p>
