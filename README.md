# awesome-embodied-ai-must-read

A curated list of essential Embodied AI papers, systems, datasets, and engineering references.

**Curated for signal, not coverage**.

## Inclusion Criteria

A paper, project, dataset, or system should satisfy at least one of the following:

- **Foundational:** Introduced an influential concept, benchmark, architecture, training recipe, or research direction.
- **Engineering-relevant:** Contains reusable lessons about system design, data collection, simulation, deployment, evaluation, scaling, or infrastructure.
- **Reproducible or inspectable:** Provides code, data, models, benchmark environments, project pages, or unusually clear implementation details.
- **Field-shaping:** Frequently cited, widely adopted, or clearly changed how people build or evaluate embodied agents.

## Entry Format

Use this compact format for each entry:

```markdown
### 2026

- **Short Name** **[Institution]** Title · Type (optional) [[paper](paper_url)] [[project](project_url)]

Example:
- **SayCan** **[Google Research]** Do As I Can, Not As I Say: Grounding Language in Robotic Affordances · Agentic Embodied AI [[paper](https://say-can.github.io/assets/palm_saycan.pdf)] [[project](https://say-can.github.io/)]
```

## Categories

- [Foundations and Surveys](#foundations-and-surveys)
- [Agentic Embodied AI & Embodied MLLM](#agentic-embodied-ai--embodied-mllm)
- [Simulators and Benchmarks](#simulators-and-benchmarks)
- [Vision-Language-Action Models](#vision-language-action-models)
- [World Models](#world-models)
- [Data and Teleoperation](#data-and-teleoperation)
- [Systems, Infrastructure, and Deployment](#systems-infrastructure-and-deployment)
- [Open-Source Projects Worth Studying](#open-source-projects-worth-studying)

## Foundations and Surveys

### 2026

- **World Model Survey** **[Bohan Hou]** World Model for Robot Learning: A Comprehensive Survey · Survey / World Models for Robot Learning [[paper](https://arxiv.org/pdf/2605.00080)] [[project](-)]
- **WAM Survey** **[Fudan University]** World Action Models: The Next Frontier in Embodied AI · Survey / World Action Models [[paper](https://arxiv.org/abs/2605.12090)] [[project](-)]

### 2025

- **VLA Anatomy** **[Imperial College London]** An Anatomy of Vision-Language-Action Models: From Modules to Milestones and Challenges · Survey / Vision-Language-Action Models [[paper](https://arxiv.org/pdf/2512.11362)] [[project](https://suyuz1.github.io/VLA-Survey-Anatomy/)]
- **Action Tokenization Survey** **[PKU-PsiBot]** A Survey on Vision-Language-Action Models: An Action Tokenization Perspective · Survey / Vision-Language-Action Models [[paper](https://arxiv.org/pdf/2507.01925)] [[project](-)]

### 2024

- **VLA Survey** **[CUHK]** A Survey on Vision-Language-Action Models for Embodied AI · Survey / Vision-Language-Action Models [[paper](https://arxiv.org/pdf/2405.14093)] [[project](https://github.com/yueen-ma/Awesome-VLA)]

## Vision-Language-Action Models

### 2026

- **Hy-Embodied-0.5-VLA** **[Tencent]** Hy-Embodied-0.5-VLA: From Vision-Language-Action Models to a Real-World Robot Learning Stack · VLA / Real-World Robot Learning Stack [[paper](https://arxiv.org/pdf/2606.14409v1)] [[project](https://tairos.tencent.com/openSourceModels/hy-embodied-0.5-vla)]
- **Qwen-VLA** **[Qwen]** Qwen-VLA: Unifying Vision-Language-Action Modeling across Tasks, Environments, and Robot Embodiments · Unified VLA / Cross-Embodiment [[paper](https://arxiv.org/pdf/2605.30280)] [[project](https://github.com/QwenLM/Qwen-VLA)]
- **MolmoAct2** **[Allen AI]** MolmoAct2: Action Reasoning Models for Real-world Deployment · Action Reasoning Model / Real-World Deployment [[paper](https://arxiv.org/abs/2605.02881)] [[project](https://allenai.org/blog/molmoact2)]
- **GENE-26.5** **[Genesis]** GENE-26.5: Advancing Robotic Manipulation to Human Level · Embodied Foundation Model / Robotic Manipulation [[paper](-)] [[project](https://www.genesis.ai/blog/gene-26-5-advancing-robotic-manipulation-to-human-level)]
- **GEN-1** **[Generalist AI]** GEN-1: Scaling Embodied Foundation Models to Mastery · Embodied Foundation Model / Physical Interaction [[paper](-)] [[project](https://generalistai.com/blog/apr-02-2026-GEN-1)]
- **A1** **[A1 Team]** A1: A Fully Transparent Open-Source, Adaptive and Efficient Truncated Vision-Language-Action Model · Efficient VLA / Adaptive Inference [[paper](https://arxiv.org/abs/2604.05672)] [[project](-)]
- **Xiaomi-Robotics-0** **[Xiaomi]** Xiaomi-Robotics-0: An Open-Sourced Vision-Language-Action Model with Real-Time Execution · Open-Source VLA / Real-Time Execution [[paper](https://arxiv.org/abs/2602.12684)] [[project](https://xiaomi-robotics-0.github.io/)]
- **ABot-M0** **[AMap Group]** ABot-M0: VLA Foundation Model for Robotic Manipulation with Action Manifold Learning · VLA / Action Manifold Learning [[paper](https://arxiv.org/pdf/2602.11236)] [[project](https://amap-cvlab.github.io/ABot-Manipulation/)]
- **RDT2** **[Tsinghua University]** RDT2: Exploring the Scaling Limit of UMI Data Towards Zero-Shot Cross-Embodiment Generalization · VLA / Cross-Embodiment Generalization [[paper](https://arxiv.org/pdf/2602.03310)] [[project](https://rdt-robotics.github.io/rdt2/)]
- **GR00T N1.7** **[NVIDIA]** GR00T N1.7 · Humanoid Foundation Model / VLA [[paper](-)] [[project](https://huggingface.co/nvidia/GR00T-N1.7-3B)]
- **MEM** **[Physical Intelligence]** MEM: Multi-Scale Embodied Memory for Vision Language Action Models · VLA / Multi-Scale Embodied Memory [[paper](https://arxiv.org/abs/2603.03596)] [[project](https://www.pi.website/research/mem)]
- **LingBot-VLA** **[Ant Group]** A Pragmatic VLA Foundation Model · VLA / Real-World Robot Learning [[paper](https://arxiv.org/pdf/2601.18692)] [[project](https://technology.robbyant.com/lingbot-vla/)]
- **Being-H0.5** **[BeingBeyond]** Being-H0.5: Scaling Human-Centric Robot Learning for Cross-Embodiment Generalization · VLA / Human-Centric Robot Learning [[paper](https://arxiv.org/pdf/2601.12993)] [[project](https://research.beingbeyond.com/being-h05)]
- **BagelVLA** **[BagelVLA Team]** BagelVLA: Enhancing Long-Horizon Manipulation via Interleaved Vision-Language-Action Generation · VLA / Long-Horizon Manipulation [[paper](https://arxiv.org/abs/2602.09849)] [[project](-)]

### 2025

- **RynnVLA-002** **[Alibaba DAMO Academy]** RynnVLA-002: A Unified Vision-Language-Action and World Model · Unified VLA / World Model [[paper](https://arxiv.org/pdf/2511.17502)] [[project](https://github.com/alibaba-damo-academy/RynnVLA-002)]
- **Evo-1** **[Shanghai Jiao Tong University]** Evo-1: Lightweight Vision-Language-Action Model with Preserved Semantic Alignment · Lightweight VLA / Efficient Deployment [[paper](https://arxiv.org/abs/2511.04555)] [[project](https://github.com/MINT-SJTU/Evo-1)]
- **X-VLA** **[Tsinghua University]** X-VLA: Soft-Prompted Transformer as Scalable Cross-Embodiment Vision-Language-Action Model · Cross-Embodiment VLA [[paper](https://arxiv.org/pdf/2510.10274)] [[project](https://thu-air-dream.github.io/X-VLA/)]
- **InternVLA-M1** **[Shanghai AI Lab]** InternVLA-M1: A Spatially Guided Vision-Language-Action Framework for Generalist Robot Policy · Spatially Guided VLA [[paper](https://arxiv.org/pdf/2510.13778)] [[project](https://internrobotics.github.io/internvla-m1.github.io/)]
- **Spatial Forcing** **[OpenHelix Team]** Spatial Forcing: Implicit Spatial Representation Alignment for Vision-language-action Model · Spatial Alignment / VLA [[paper](https://arxiv.org/pdf/2510.12276)] [[project](https://spatial-forcing.github.io/)]
- **VLA-0** **[NVIDIA]** VLA-0: Building State-of-the-Art VLAs with Zero Modification · VLA / Model Adaptation [[paper](https://arxiv.org/pdf/2510.13054)] [[project](https://vla0.github.io/)]
- **EmbodiedOneVision** **[EO Robotics]** EmbodiedOneVision: Interleaved Vision-Text-Action Pretraining for General Robot Control · Interleaved VLA Pretraining [[paper](https://arxiv.org/pdf/2508.21112)] [[project](https://eo-robotics.ai/eo-1)]
- **MolmoAct** **[Allen AI]** MolmoAct: Action Reasoning Models that can Reason in Space · Action Reasoning Model / Spatial Reasoning [[paper](https://arxiv.org/abs/2508.07917)] [[project](https://allenai.org/blog/molmoact)]
- **UniVLA** **[BAAI]** UniVLA: Unified Vision-Language-Action Model · Unified VLA / Interleaved Token Modeling [[paper](https://arxiv.org/abs/2506.19850)] [[project](https://github.com/baaivision/UniVLA)]
- **Action Chunking Flow** **[Physical Intelligence]** Real-Time Execution of Action Chunking Flow Policies · VLA / Real-Time Flow Policy [[paper](https://arxiv.org/pdf/2506.07339)] [[project](https://www.pi.website/research/real_time_chunking)]
- **SmolVLA** **[Hugging Face]** SmolVLA: A Small Vision-Language-Action Model for Efficient Robot Learning · Compact VLA / Efficient Robot Learning [[paper](https://huggingface.co/blog/smolvla)] [[project](https://github.com/huggingface/lerobot)]
- **Knowledge Insulation** **[Physical Intelligence]** Knowledge Insulating Vision-Language-Action Models: Train Fast, Run Fast, Generalize Better · Efficient VLA Training / Generalization [[paper](https://arxiv.org/pdf/2505.23705)] [[project](https://pi.website/research/knowledge_insulation)]
- **π0.5** **[Physical Intelligence]** π0.5: A Vision-Language-Action Model with Open-World Generalization · VLA / Open-World Generalization [[paper](https://arxiv.org/pdf/2504.16054)] [[project](https://www.pi.website/blog/pi05)]
- **GR00T N1** **[NVIDIA]** GR00T N1: An Open Foundation Model for Generalist Humanoid Robots · Humanoid Foundation Model / VLA [[paper](https://arxiv.org/pdf/2503.14734)] [[project](https://github.com/NVIDIA/Isaac-GR00T)]
- **OpenVLA-OFT** **[Stanford]** Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success · VLA Fine-Tuning / Efficient Adaptation [[paper](https://arxiv.org/abs/2502.19645)] [[project](https://openvla-oft.github.io/)]
- **Hi Robot** **[Physical Intelligence]** Hi Robot: Open-Ended Instruction Following with Hierarchical Vision-Language-Action Models · Hierarchical VLA / Instruction Following [[paper](https://arxiv.org/pdf/2502.19417)] [[project](https://www.pi.website/research/hirobot)]
- **Gemini Robotics** **[Google DeepMind]** Gemini Robotics: Bringing AI into the Physical World · Robotics Foundation Model / VLA [[paper](https://storage.googleapis.com/deepmind-media/gemini-robotics/gemini_robotics_report.pdf)] [[project](-)]
- **FAST** **[Physical Intelligence]** FAST: Efficient Action Tokenization for Vision-Language-Action Models · Action Tokenization / VLA [[paper](https://arxiv.org/pdf/2501.09747)] [[project](-)]
- **LLaVA-VLA** **[OpenHelix Team]** LLaVA-VLA: A Simple Yet Powerful Vision-Language-Action Model · VLA [[paper](-)] [[project](https://github.com/OpenHelix-Team/LLaVA-VLA)]
- **GEN-0** **[Generalist AI]** Embodied Foundation Models That Scale with Physical Interaction · Embodied Foundation Model / Physical Interaction [[paper](-)] [[project](https://generalistai.com/blog/nov-04-2025-GEN-0)]
- **Wall-OSS** **[X Square Robot]** Wall-OSS: Igniting VLMs toward the Embodied Space · Embodied VLM / VLA [[paper](https://x2robot.cn-wlcb.ufileos.com/wall_oss.pdf)] [[project](https://x2robot.com/en/research/68bc2cde8497d7f238dde690)]

### 2024

- **CogACT** **[Microsoft Research]** CogACT: A Foundational Vision-Language-Action Model for Synergizing Cognition and Action in Robotic Manipulation · Foundational VLA / Manipulation [[paper](https://www.arxiv.org/pdf/2411.19650)] [[project](https://cogact.github.io/)]
- **π0** **[Physical Intelligence]** π0: A Vision-Language-Action Flow Model for General Robot Control · VLA Flow Model / General Robot Control [[paper](https://www.physicalintelligence.company/download/pi0.pdf)] [[project](https://www.physicalintelligence.company/blog/pi0)]
- **RDT-1B** **[RDT Team]** RDT-1B: a Diffusion Foundation Model for Bimanual Manipulation · Diffusion Foundation Model / Bimanual Manipulation [[paper](https://arxiv.org/pdf/2410.07864)] [[project](https://rdt-robotics.github.io/rdt-robotics/)]
- **MiniVLA** **[Stanford ILIAD]** MiniVLA: A Better VLA with a Smaller Footprint · Compact VLA [[paper](https://ai.stanford.edu/blog/minivla/)] [[project](https://github.com/Stanford-ILIAD/openvla-mini)]
- **Embodied CoT** **[Stanford]** Robotic Control via Embodied Chain-of-Thought Reasoning · VLA / Embodied Reasoning [[paper](https://arxiv.org/pdf/2407.08693)] [[project](-)]
- **OpenVLA** **[Stanford]** OpenVLA: An Open-Source Vision-Language-Action Model · Open-Source VLA [[paper](https://arxiv.org/pdf/2406.09246)] [[project](https://openvla.github.io/)]
- **Octo** **[UC Berkeley]** Octo: An Open-Source Generalist Robot Policy · Generalist Robot Policy / VLA [[paper](https://arxiv.org/pdf/2405.12213)] [[project](https://octo-models.github.io/)]

### 2023

- **RT-2** **[Google DeepMind]** RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control · VLA / Robotic Control [[paper](https://arxiv.org/pdf/2307.15818)] [[project](https://robotics-transformer2.github.io/)]

## Agentic Embodied AI & Embodied MLLM

### 2025

- **RoboBrain 2.0** **[BAAI]** RoboBrain 2.0 Technical Report · Embodied Foundation Model / Generalist Agent [[paper](https://arxiv.org/pdf/2507.02029)] [[project](https://superrobobrain.github.io/)]
- **RoboRefer** **[Beihang University]** RoboRefer: Towards Spatial Referring with Reasoning in Vision-Language Models for Robotics · Embodied VLM / Spatial Reasoning [[paper](https://arxiv.org/pdf/2506.04308)] [[project](https://zhoues.github.io/RoboRefer/)]
- **FSD** **[Tianjin University]** From Seeing to Doing: Bridging Reasoning and Decision for Robotic Manipulation · Embodied VLM / Robotic Manipulation [[paper](https://arxiv.org/pdf/2505.08548)] [[project](https://embodied-fsd.github.io/)]
- **Cosmos-Reason1** **[NVIDIA]** Cosmos-Reason1: From Physical Common Sense To Embodied Reasoning · Embodied MLLM / Physical Reasoning [[paper](https://arxiv.org/pdf/2503.15558)] [[project](https://github.com/nvidia-cosmos/cosmos-reason1)]

### 2023

- **Code as Policies** **[Robotics at Google]** Code as Policies: Language Model Programs for Embodied Control · Language Model Program / Embodied Control [[paper](https://arxiv.org/pdf/2209.07753)] [[project](https://code-as-policies.github.io/)]

### 2022

- **Inner Monologue** **[Robotics at Google]** Inner Monologue: Embodied Reasoning through Planning with Language Models · Embodied Reasoning / Language Planning [[paper](https://arxiv.org/pdf/2207.05608)] [[project](https://innermonologue.github.io/)]

## Simulators and Benchmarks

### 2026

- **MolmoSpace** **[Allen AI]** MolmoSpaces: A Large-Scale Open Ecosystem for Robot Navigation and Manipulation · Public Leaderboard / Embodied Spatial Evaluation [[paper](https://arxiv.org/pdf/2602.11337)] [[project](https://allenai.org/blog/molmospaces)]
- **SIMPLE** **[USC]** SIMPLE: Simulation-Based Policy Learning and Evaluation for Humanoid Loco-manipulation · Simulator / Benchmark / Humanoid Loco-manipulation [[paper](https://arxiv.org/abs/2606.08278)] [[project](https://github.com/physical-superintelligence-lab/SIMPLE)]
- **RoboLab** **[NVIDIA]** RoboLab: A High-Fidelity Simulation Benchmark for Analysis of Task Generalist Policies · Simulator / Benchmark / Generalist Robot Policies [[paper](https://arxiv.org/abs/2604.09860)] [[project](https://research.nvidia.com/labs/srl/projects/robolab/index.html)]
- **EBench** **[Shanghai AI Lab]** EBench: Elemental Diagnosis of Generalist Mobile Manipulation Policies · Benchmark / Generalist Mobile Manipulation Evaluation [[paper](https://arxiv.org/abs/2606.18239)] [[project](https://internrobotics.github.io/EBench-home/)]
- **ManipArena** **[Sun Yat-sen University]** ManipArena: Comprehensive Real-World Evaluation of Reasoning-Oriented Generalist Robot Manipulation · Benchmark / Real Device / Real-World Evaluation [[paper](https://arxiv.org/abs/2603.28545)] [[project](-)]
- **ManipulationNet** **[ManipulationNet Team]** ManipulationNet: An Infrastructure for Benchmarking Real-World Robot Manipulation with Physical Skill Challenges and Embodied Multimodal Reasoning · Benchmark / Public Real Device Evaluation / Robot Manipulation [[paper](https://arxiv.org/abs/2603.04363)] [[project](https://manipulation-net.org/)]
- **RoboCasa365** **[UT Austin]** RoboCasa365: A Large-Scale Simulation Framework for Training and Benchmarking Generalist Robots · Simulator / Benchmark / Household Mobile Manipulation [[paper](https://arxiv.org/abs/2603.04356)] [[project](https://robocasa.ai/)]

### 2025

- **LIBERO-Plus** **[Fudan University]** LIBERO-Plus: In-depth Robustness Analysis of Vision-Language-Action Models · Benchmark / VLA Robustness Analysis [[paper](https://arxiv.org/abs/2510.13626)] [[project](https://sylvestf.github.io/LIBERO-plus/)]
- **RoboArena** **[UC Berkeley]** RoboArena: Distributed Real-World Evaluation of Generalist Robot Policies · Benchmark / Real-World Distributed Evaluation [[paper](https://arxiv.org/abs/2506.18123)] [[project](https://robo-arena.github.io/)]
- **RoboTwin 2.0** **[SJTU]** RoboTwin 2.0: A Scalable Data Generator and Benchmark with Strong Domain Randomization for Robust Bimanual Robotic Manipulation · Data Generator / Benchmark / Bimanual Manipulation [[paper](https://arxiv.org/pdf/2506.18088)] [[project](https://robotwin-platform.github.io/)]

### 2024

- **PerAct2** **[KIT]** PerAct2: Benchmarking and Learning for Robotic Bimanual Manipulation Tasks · Benchmark / Bimanual Manipulation [[paper](https://arxiv.org/abs/2407.00278)] [[project](http://bimanual.github.io/)]
- **RoboCasa** **[UT Austin]** RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots · Simulator / Benchmark / Generalist Robots [[paper](https://arxiv.org/abs/2406.02523)] [[project](https://robocasa.ai/)]
- **SIMPLER** **[UC San Diego]** Evaluating Real-World Robot Manipulation Policies in Simulation · Simulator / Benchmark / Real-to-Sim Evaluation [[paper](https://arxiv.org/abs/2405.05941)] [[project](https://simpler-env.github.io/)]

### 2023

- **LIBERO** **[UT Austin]** LIBERO: Benchmarking Knowledge Transfer for Lifelong Robot Learning · Benchmark / Lifelong Robot Learning [[paper](https://arxiv.org/abs/2306.03310)] [[project](https://libero-project.github.io/)]

### 2021

- **CALVIN** **[University of Freiburg]** CALVIN: A Benchmark for Language-Conditioned Policy Learning for Long-Horizon Robot Manipulation Tasks · Benchmark / Language-Conditioned Long-Horizon Manipulation [[paper](https://arxiv.org/abs/2112.03227)] [[project](http://calvin.cs.uni-freiburg.de/)]

## World Models

### 2026

- **μ0** **[University of Maryland]** μ0: A Scalable 3D Interaction-Trace World Model · 3D Interaction-Trace World Model / Cross-Embodiment Manipulation [[paper](https://arxiv.org/abs/2606.13769)] [[project](-)]
- **GigaWorld-Policy** **[OpenGigaAI]** GigaWorld-Policy: An Efficient Action-Centered World-Action Model · World Action Model / Action-Centered Policy [[paper](https://arxiv.org/pdf/2603.17240)] [[project](https://gigaai-research.github.io/GigaWorld-Policy/)]
- **Fast-WAM** **[Tsinghua University]** Fast-WAM: Do World Action Models Need Test-time Future Imagination? · World Action Model / Policy Inference [[paper](https://arxiv.org/pdf/2603.16666)] [[project](https://yuantianyuan01.github.io/FastWAM/)]
- **DiT4DiT** **[Mondo Robotics]** DiT4DiT: Jointly Modeling Video Dynamics and Actions for Generalizable Robot Control · World Model / Robot Control [[paper](https://arxiv.org/pdf/2603.10448)] [[project](https://dit4dit.github.io/)]
- **DreamZero** **[NVIDIA]** World Action Models are Zero-shot Policies · World Action Model / Zero-shot Policy [[paper](https://arxiv.org/pdf/2602.15922)] [[project](https://dreamzero0.github.io/)]
- **LingBot-VA** **[LingBot Team]** Causal World Modeling for Robot Control · World Model / Robot Control [[paper](https://arxiv.org/pdf/2601.21998)] [[project](https://github.com/robbyant/lingbot-va)]
- **Cosmos Policy** **[NVIDIA]** Cosmos Policy: Fine-Tuning Video Models for Visuomotor Control and Planning · World Action Model / Visuomotor Control [[paper](https://arxiv.org/pdf/2601.16163)] [[project](https://research.nvidia.com/labs/dir/cosmos-policy/cosmos_policy_index.html)]
- **PointWorld** **[Stanford]** PointWorld: Scaling 3D World Models for In-The-Wild Robotic Manipulation · 3D World Model / Robotic Manipulation [[paper](https://arxiv.org/abs/2601.03782)] [[project](https://point-world.github.io/)]

### 2025

- **Motus** **[Tsinghua University]** Motus: A Unified Latent Action World Model · Latent Action World Model [[paper](https://arxiv.org/pdf/2512.13030)] [[project](https://motus-robotics.github.io/motus)]
- **RynnVLA-002** **[Alibaba DAMO Academy]** RynnVLA-002: A Unified Vision-Language-Action and World Model · Unified VLA / World Model [[paper](https://arxiv.org/pdf/2511.17502)] [[project](https://github.com/alibaba-damo-academy/RynnVLA-002)]
- **WorldVLA** **[Alibaba DAMO Academy]** WorldVLA: Towards Autoregressive Action World Model · Autoregressive Action World Model [[paper](https://arxiv.org/pdf/2506.21539)] [[project](https://github.com/alibaba-damo-academy/WorldVLA)]
- **3DFlowAction** **[3DFlowAction Team]** 3DFlowAction: Learning Cross-Embodiment Manipulation from 3D Flow World Model · Geometric World Model / Cross-Embodiment Manipulation [[paper](https://arxiv.org/pdf/2506.06199)] [[project](https://github.com/Hoyyyaard/3DFlowAction/)]
- **LaPA** **[KAIST]** Latent Action Pretraining from Videos · Latent Action Model / Video Pretraining [[paper](https://arxiv.org/pdf/2410.11758)] [[project](https://latentactionpretraining.github.io/)]

### 2024

- **VLP** **[Video Language Planning Team]** Video Language Planning · Video World Model / Planning [[paper](https://arxiv.org/pdf/2310.10625)] [[project](https://video-language-planning.github.io/)]

### 2023

- **UniPi** **[Google Research]** Learning Universal Policies via Text-Guided Video Generation · Text-Guided Video Policy / World Model [[paper](https://arxiv.org/pdf/2302.00111)] [[project](https://research.google/blog/unipi-learning-universal-policies-via-text-guided-video-generation/)]

## Data and Teleoperation

### 2026

- **EgoScale** **[NVIDIA]** EgoScale: Scaling Dexterous Manipulation with Diverse Egocentric Human Data · Egocentric Human Data / Dexterous Manipulation / Cross-Embodiment Transfer [[paper](https://arxiv.org/abs/2602.16710)] [[project](https://research.nvidia.com/labs/gear/egoscale/)]

## Systems, Infrastructure, and Deployment

## Open-Source Projects Worth Studying

### 2026

- **StarVLA** **[StarVLA Community]** StarVLA: A Lego-like Codebase for Vision-Language-Action Model Developing · VLA Framework / Training & Evaluation [[paper](https://arxiv.org/abs/2604.05014)] [[project](https://github.com/starVLA/starVLA)]
- **RLinf** **[Tsinghua University]** RLinf-USER: A Unified and Extensible System for Real-World Online Policy Learning in Embodied AI · Real-World Online Learning System [[paper](https://arxiv.org/abs/2602.07837)] [[project](https://github.com/RLinf/RLinf)]
- **LeRobot** **[Hugging Face]** LeRobot: An Open-Source Library for End-to-End Robot Learning · Robot Learning Library / Data / Training / Deployment [[paper](https://arxiv.org/abs/2602.22818)] [[project](https://github.com/huggingface/lerobot)]

### 2025

- **GR00T N1** **[NVIDIA]** GR00T N1: An Open Foundation Model for Generalist Humanoid Robots · Open-Source Humanoid Foundation Model / VLA [[paper](https://arxiv.org/abs/2503.14734)] [[project](https://github.com/NVIDIA/Isaac-GR00T)]
- **OpenPI** **[Physical Intelligence]** OpenPI: Open-source models and code for pi0, pi0-FAST, and pi0.5 · Open-Source VLA Model / Training / Inference [[paper](https://arxiv.org/abs/2410.24164)] [[project](https://github.com/Physical-Intelligence/openpi)]

### 2024

- **OpenVLA** **[Stanford]** OpenVLA: An Open-Source Vision-Language-Action Model · Open-Source VLA Model [[paper](https://arxiv.org/abs/2406.09246)] [[project](https://github.com/openvla/openvla)]

## Contribution Rules

Before adding a new entry, ask:

- Would a serious embodied AI researcher or engineer still benefit from reading this one year later?
- Does it provide more than a result table?
- Is the contribution specific enough to explain in one or two sentences?
- Does it teach something reusable about embodied AI systems?

If the answer is unclear, leave it out.

## Citation

If you find this repository useful, please cite it as:

```bibtex
@misc{yuan2026awesomeembodiedaimustread,
  title        = {awesome-embodied-ai-must-read},
  author       = {Yifu Yuan},
  year         = {2026},
  howpublished = {\url{https://github.com/pickxiguapi/awesome-embodied-ai-must-read}},
  note         = {A curated list of essential Embodied AI papers, systems, datasets, and engineering references}
}
```

## License

This repository is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

Please also cite the original papers, datasets, benchmarks, and projects listed here when using them.
