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
- **Short Name** **[Year]** **[Institution]** Title · Type (optional) [[paper](paper_url)] [[project](project_url)]

Example:
- **SayCan** **[2022]** **[Google Research et al.]** Do As I Can, Not As I Say: Grounding Language in Robotic Affordances · Agentic Embodied AI [[paper](https://say-can.github.io/assets/palm_saycan.pdf)] [[project](https://say-can.github.io/)]

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

- **WAM Survey** **[2026]** **[Fudan University et al.]** World Action Models: The Next Frontier in Embodied AI · Survey / World Action Models [[paper](https://arxiv.org/abs/2605.12090)] [[project](-)]
- **VLA Anatomy** **[2025]** **[Imperial College London et al.]** An Anatomy of Vision-Language-Action Models: From Modules to Milestones and Challenges · Survey / Vision-Language-Action Models [[paper](https://arxiv.org/pdf/2512.11362)] [[project](https://suyuz1.github.io/VLA-Survey-Anatomy/)]
- **Action Tokenization Survey** **[2025]** **[PKU-PsiBot]** A Survey on Vision-Language-Action Models: An Action Tokenization Perspective · Survey / Vision-Language-Action Models [[paper](https://arxiv.org/pdf/2507.01925)] [[project](-)]
- **VLA Survey** **[2024]** **[CUHK et al.]** A Survey on Vision-Language-Action Models for Embodied AI · Survey / Vision-Language-Action Models [[paper](https://arxiv.org/pdf/2405.14093)] [[project](https://github.com/yueen-ma/Awesome-VLA)]

## Vision-Language-Action Models




## Agentic Embodied AI & Embodied MLLM

- **RoboBrain 2.0** **[2025]** **[BAAI]** RoboBrain 2.0 Technical Report · Embodied Foundation Model / Generalist Agent [[paper](https://arxiv.org/pdf/2507.02029)] [[project](https://superrobobrain.github.io/)]
- **RoboRefer** **[2025]** **[Beihang University et al.]** RoboRefer: Towards Spatial Referring with Reasoning in Vision-Language Models for Robotics · Embodied VLM / Spatial Reasoning [[paper](https://arxiv.org/pdf/2506.04308)] [[project](https://zhoues.github.io/RoboRefer/)]
- **FSD** **[2025]** **[Tianjin University]** From Seeing to Doing: Bridging Reasoning and Decision for Robotic Manipulation · Embodied VLM / Robotic Manipulation [[paper](https://arxiv.org/pdf/2505.08548)] [[project](https://embodied-fsd.github.io/)]
- **Cosmos-Reason1** **[2025]** **[NVIDIA]** Cosmos-Reason1: From Physical Common Sense To Embodied Reasoning · Embodied MLLM / Physical Reasoning [[paper](https://arxiv.org/pdf/2503.15558)] [[project](https://github.com/nvidia-cosmos/cosmos-reason1)]
- **Code as Policies** **[2023]** **[Robotics at Google]** Code as Policies: Language Model Programs for Embodied Control · Language Model Program / Embodied Control [[paper](https://arxiv.org/pdf/2209.07753)] [[project](https://code-as-policies.github.io/)]
- **Inner Monologue** **[2022]** **[Robotics at Google]** Inner Monologue: Embodied Reasoning through Planning with Language Models · Embodied Reasoning / Language Planning [[paper](https://arxiv.org/pdf/2207.05608)] [[project](https://innermonologue.github.io/)]

## Simulators and Benchmarks

- **MolmoSpace** **[2026]** **[Allen AI]** MolmoSpaces: A Large-Scale Open Ecosystem for Robot Navigation and Manipulation · Public Leaderboard / Embodied Spatial Evaluation [[paper](https://arxiv.org/pdf/2602.11337)] [[project](https://allenai.org/blog/molmospaces)]
- **SIMPLE** **[2026]** **[USC]** SIMPLE: Simulation-Based Policy Learning and Evaluation for Humanoid Loco-manipulation · Simulator / Benchmark / Humanoid Loco-manipulation [[paper](https://arxiv.org/abs/2606.08278)] [[project](https://github.com/physical-superintelligence-lab/SIMPLE)]
- **RoboLab** **[2026]** **[NVIDIA et al.]** RoboLab: A High-Fidelity Simulation Benchmark for Analysis of Task Generalist Policies · Simulator / Benchmark / Generalist Robot Policies [[paper](https://arxiv.org/abs/2604.09860)] [[project](https://research.nvidia.com/labs/srl/projects/robolab/index.html)]
- **EBench** **[2026]** **[Shanghai AI Lab et al.]** EBench: Elemental Diagnosis of Generalist Mobile Manipulation Policies · Benchmark / Generalist Mobile Manipulation Evaluation [[paper](https://arxiv.org/abs/2606.18239)] [[project](https://internrobotics.github.io/EBench-home/)]
- **ManipArena** **[2026]** **[Sun Yat-sen University et al.]** ManipArena: Comprehensive Real-World Evaluation of Reasoning-Oriented Generalist Robot Manipulation · Benchmark / Real Device / Real-World Evaluation [[paper](https://arxiv.org/abs/2603.28545)] [[project](-)]
- **ManipulationNet** **[2026]** **[ManipulationNet Team]** ManipulationNet: An Infrastructure for Benchmarking Real-World Robot Manipulation with Physical Skill Challenges and Embodied Multimodal Reasoning · Benchmark / Public Real Device Evaluation / Robot Manipulation [[paper](https://arxiv.org/abs/2603.04363)] [[project](https://manipulation-net.org/)]
- **RoboCasa365** **[2026]** **[UT Austin et al.]** RoboCasa365: A Large-Scale Simulation Framework for Training and Benchmarking Generalist Robots · Simulator / Benchmark / Household Mobile Manipulation [[paper](https://arxiv.org/abs/2603.04356)] [[project](https://robocasa.ai/)]
- **LIBERO-Plus** **[2025]** **[Fudan University et al.]** LIBERO-Plus: In-depth Robustness Analysis of Vision-Language-Action Models · Benchmark / VLA Robustness Analysis [[paper](https://arxiv.org/abs/2510.13626)] [[project](https://sylvestf.github.io/LIBERO-plus/)]
- **RoboArena** **[2025]** **[UC Berkeley et al.]** RoboArena: Distributed Real-World Evaluation of Generalist Robot Policies · Benchmark / Real-World Distributed Evaluation [[paper](https://arxiv.org/abs/2506.18123)] [[project](https://robo-arena.github.io/)]
- **RoboTwin 2.0** **[2025]** **[SJTU et al.]** RoboTwin 2.0: A Scalable Data Generator and Benchmark with Strong Domain Randomization for Robust Bimanual Robotic Manipulation · Data Generator / Benchmark / Bimanual Manipulation [[paper](https://arxiv.org/pdf/2506.18088)] [[project](https://robotwin-platform.github.io/)]
- **PerAct2** **[2024]** **[KIT et al.]** PerAct2: Benchmarking and Learning for Robotic Bimanual Manipulation Tasks · Benchmark / Bimanual Manipulation [[paper](https://arxiv.org/abs/2407.00278)] [[project](http://bimanual.github.io/)]
- **RoboCasa** **[2024]** **[UT Austin et al.]** RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots · Simulator / Benchmark / Generalist Robots [[paper](https://arxiv.org/abs/2406.02523)] [[project](https://robocasa.ai/)]
- **SIMPLER** **[2024]** **[UC San Diego et al.]** Evaluating Real-World Robot Manipulation Policies in Simulation · Simulator / Benchmark / Real-to-Sim Evaluation [[paper](https://arxiv.org/abs/2405.05941)] [[project](https://simpler-env.github.io/)]
- **LIBERO** **[2023]** **[UT Austin et al.]** LIBERO: Benchmarking Knowledge Transfer for Lifelong Robot Learning · Benchmark / Lifelong Robot Learning [[paper](https://arxiv.org/abs/2306.03310)] [[project](https://libero-project.github.io/)]
- **CALVIN** **[2021]** **[University of Freiburg]** CALVIN: A Benchmark for Language-Conditioned Policy Learning for Long-Horizon Robot Manipulation Tasks · Benchmark / Language-Conditioned Long-Horizon Manipulation [[paper](https://arxiv.org/abs/2112.03227)] [[project](http://calvin.cs.uni-freiburg.de/)]

## World Models

- **μ0** **[2026]** **[University of Maryland et al.]** μ0: A Scalable 3D Interaction-Trace World Model · 3D Interaction-Trace World Model / Cross-Embodiment Manipulation [[paper](https://arxiv.org/abs/2606.13769)] [[project](-)]
- **GigaWorld-Policy** **[2026]** **[OpenGigaAI et al.]** GigaWorld-Policy: An Efficient Action-Centered World-Action Model · World Action Model / Action-Centered Policy [[paper](https://arxiv.org/pdf/2603.17240)] [[project](https://gigaai-research.github.io/GigaWorld-Policy/)]
- **Fast-WAM** **[2026]** **[Tsinghua University et al.]** Fast-WAM: Do World Action Models Need Test-time Future Imagination? · World Action Model / Policy Inference [[paper](https://arxiv.org/pdf/2603.16666)] [[project](https://yuantianyuan01.github.io/FastWAM/)]
- **DiT4DiT** **[2026]** **[Mondo Robotics et al.]** DiT4DiT: Jointly Modeling Video Dynamics and Actions for Generalizable Robot Control · World Model / Robot Control [[paper](https://arxiv.org/pdf/2603.10448)] [[project](https://dit4dit.github.io/)]
- **DreamZero** **[2026]** **[NVIDIA et al.]** World Action Models are Zero-shot Policies · World Action Model / Zero-shot Policy [[paper](https://arxiv.org/pdf/2602.15922)] [[project](https://dreamzero0.github.io/)]
- **LingBot-VA** **[2026]** **[LingBot Team]** Causal World Modeling for Robot Control · World Model / Robot Control [[paper](https://arxiv.org/pdf/2601.21998)] [[project](https://github.com/robbyant/lingbot-va)]
- **Cosmos Policy** **[2026]** **[NVIDIA]** Cosmos Policy: Fine-Tuning Video Models for Visuomotor Control and Planning · World Action Model / Visuomotor Control [[paper](https://arxiv.org/pdf/2601.16163)] [[project](https://research.nvidia.com/labs/dir/cosmos-policy/cosmos_policy_index.html)]
- **PointWorld** **[2026]** **[Stanford et al.]** PointWorld: Scaling 3D World Models for In-The-Wild Robotic Manipulation · 3D World Model / Robotic Manipulation [[paper](https://arxiv.org/abs/2601.03782)] [[project](https://point-world.github.io/)]
- **Motus** **[2025]** **[Tsinghua University et al.]** Motus: A Unified Latent Action World Model · Latent Action World Model [[paper](https://arxiv.org/pdf/2512.13030)] [[project](https://motus-robotics.github.io/motus)]
- **RynnVLA-002** **[2025]** **[Alibaba DAMO Academy]** RynnVLA-002: A Unified Vision-Language-Action and World Model · Unified VLA / World Model [[paper](https://arxiv.org/pdf/2511.17502)] [[project](https://github.com/alibaba-damo-academy/RynnVLA-002)]
- **WorldVLA** **[2025]** **[Alibaba DAMO Academy]** WorldVLA: Towards Autoregressive Action World Model · Autoregressive Action World Model [[paper](https://arxiv.org/pdf/2506.21539)] [[project](https://github.com/alibaba-damo-academy/WorldVLA)]
- **3DFlowAction** **[2025]** **[3DFlowAction Team]** 3DFlowAction: Learning Cross-Embodiment Manipulation from 3D Flow World Model · Geometric World Model / Cross-Embodiment Manipulation [[paper](https://arxiv.org/pdf/2506.06199)] [[project](https://github.com/Hoyyyaard/3DFlowAction/)]
- **LaPA** **[2025]** **[KAIST et al.]** Latent Action Pretraining from Videos · Latent Action Model / Video Pretraining [[paper](https://arxiv.org/pdf/2410.11758)] [[project](https://latentactionpretraining.github.io/)]
- **VLP** **[2024]** **[Video Language Planning Team]** Video Language Planning · Video World Model / Planning [[paper](https://arxiv.org/pdf/2310.10625)] [[project](https://video-language-planning.github.io/)]
- **UniPi** **[2023]** **[Google Research]** Learning Universal Policies via Text-Guided Video Generation · Text-Guided Video Policy / World Model [[paper](https://arxiv.org/pdf/2302.00111)] [[project](https://research.google/blog/unipi-learning-universal-policies-via-text-guided-video-generation/)]

## Data and Teleoperation

## Systems, Infrastructure, and Deployment

## Open-Source Projects Worth Studying

- **StarVLA** **[2026]** **[StarVLA Community]** StarVLA: A Lego-like Codebase for Vision-Language-Action Model Developing · VLA Framework / Training & Evaluation [[paper](https://arxiv.org/abs/2604.05014)] [[project](https://github.com/starVLA/starVLA)]
- **RLinf** **[2026]** **[Tsinghua University et al.]** RLinf-USER: A Unified and Extensible System for Real-World Online Policy Learning in Embodied AI · Real-World Online Learning System [[paper](https://arxiv.org/abs/2602.07837)] [[project](https://github.com/RLinf/RLinf)]
- **LeRobot** **[2026]** **[Hugging Face]** LeRobot: An Open-Source Library for End-to-End Robot Learning · Robot Learning Library / Data / Training / Deployment [[paper](https://arxiv.org/abs/2602.22818)] [[project](https://github.com/huggingface/lerobot)]
- **GR00T N1** **[2025]** **[NVIDIA]** GR00T N1: An Open Foundation Model for Generalist Humanoid Robots · Open-Source Humanoid Foundation Model / VLA [[paper](https://arxiv.org/abs/2503.14734)] [[project](https://github.com/NVIDIA/Isaac-GR00T)]
- **OpenPI** **[2025]** **[Physical Intelligence]** OpenPI: Open-source models and code for pi0, pi0-FAST, and pi0.5 · Open-Source VLA Model / Training / Inference [[paper](https://arxiv.org/abs/2410.24164)] [[project](https://github.com/Physical-Intelligence/openpi)]
- **OpenVLA** **[2024]** **[Stanford et al.]** OpenVLA: An Open-Source Vision-Language-Action Model · Open-Source VLA Model [[paper](https://arxiv.org/abs/2406.09246)] [[project](https://github.com/openvla/openvla)]

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
