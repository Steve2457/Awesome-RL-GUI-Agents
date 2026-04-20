# Awesome Reinforcement Learning for GUI Agents

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](CONTRIBUTING.md)

This repository provides a comprehensive and curated list of research papers, datasets, and tools focused on **Reinforcement Learning (RL) in GUI Agents**. GUI agents are intelligent systems that perceive graphical interfaces visually and execute tasks through human-like inputs (click, swipe, type).

> 📄 **Based on the survey**: *[Reinforcement Learning in GUI Agents: A Survey](https://arxiv.org/abs/25xx.xxxxx)*

---

## 📋 Table of Contents
- [🔔 News](#-news)
- [🌟 Introduction](#-introduction)
- [🤝 Contributing](#-contributing)
- [🏗️ RL Methods](#%EF%B8%8F-rl-methods)
  - [Offline Reinforcement Learning](#offline-reinforcement-learning)
  - [Online Reinforcement Learning](#online-reinforcement-learning)
  - [Hybrid Strategies](#hybrid-strategies)
- [🎨 Key Dimensions](#-key-dimensions)
  - [Reward Engineering](#reward-engineering)
  - [Data Efficiency](#data-efficiency)
  - [Technical Innovations](#technical-innovations)
- [📊 Training Resources](#-training-resources)
  - [Datasets](#datasets)
  - [Interactive Environments](#interactive-environments)
  - [RL Infrastructure](#rl-infrastructure)
- [📝 Citation](#-citation)

<p align="center">
  <img src="pic/section.png" width="90%" alt="Survey Structure">
  <br>
  <em>Overview of the survey structure. We organize our analysis into three main pillars: RL Methods, Key Dimensions, and Training Resources.</em>
</p>

---

## 🔔 News
- **[2026-04-19]** 🚀 Repository created! Stay tuned for more updates on RL-based GUI Agents.
- **[2026-03]** 📑 Released the comprehensive survey on ***Reinforcement Learning in GUI Agents***.

---

## 🌟 Introduction

Reinforcement Learning for GUI agents addresses the core difficulties of GUI automation: long-horizon credit assignment under sparse rewards, distribution shift across evolving interfaces, and safe exploration. We organize the landscape into three methodological paradigms:

- **Offline RL:** Learning from static datasets without environment interaction.
- **Online RL:** Refinement through continuous trial and error in dynamic environments.
- **Hybrid Strategies:** Bridging pre-training and adaptation via semi-online methods and world models.

<p align="center">
  <img src="pic/overview.png" width="90%" alt="RL Training Pipeline">
  <br>
  <em>Overview of the RL training pipeline for GUI agents. The agent perceives the GUI environment through screenshots, reasons about the task, and executes actions. RL optimizes the policy through reward signals derived from task completion, visual grounding accuracy, and intermediate reasoning quality.</em>
</p>

<p align="center">
  <img src="pic/timeline.png" width="85%" alt="GUI Agent Timeline">
  <br>
  <em>Timeline of GUI Agent Development from rule-based systems to the multimodal LLM era.</em>
</p>

---

## 🤝 Contributing
Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 🏗️ RL Methods

<p align="center">
  <img src="pic/overview.png" width="90%" alt="RL Training Pipeline">
  <br>
  <em>Overview of the RL training pipeline for GUI agents. The agent perceives the GUI environment through screenshots, reasons about the task, and executes actions. RL optimizes the policy through reward signals derived from task completion, visual grounding accuracy, and intermediate reasoning quality.</em>
</p>

### Frontier Models

| Paper | Venue / Year |
| --- | --- |
| [Agent S: an Open Agentic Framework That Uses Computers Like a Human](https://arxiv.org/abs/2410.08164) | arXiv 2024 |
| [Agent S2: a Compositional Generalist-specialist Framework for Computer Use Agents](https://arxiv.org/abs/2504.00906) | arXiv 2025 |
| [Constitutional Ai: Harmlessness from Ai Feedback](https://arxiv.org/abs/2212.08073) | arXiv 2022 |
| Digirl: Training In-the-wild Device-control Agents with Autonomous Reinforcement Learning | NeurIPS 2024 |
| [Qwen3-vl Technical Report](https://arxiv.org/abs/2511.21631) | 2025 |
| [Gui-eyes: Tool-augmented Perception for Visual Grounding in Gui Agents](https://arxiv.org/abs/2601.09770) | arXiv 2026 |
| [Mano Technical Report](https://arxiv.org/abs/2509.17336) | arXiv 2025 |
| [Gui Exploration Lab: Enhancing Screen Navigation in Agents Via Multi-turn Reinforcement Learning](https://arxiv.org/abs/2512.02423) | 2025 |
| [Navigating the Digital World as Humans Do: Universal Visual Grounding for Gui Agents](https://arxiv.org/abs/2410.05243) | arXiv 2024 |
| [Seed1. 5-vl Technical Report](https://arxiv.org/abs/2505.07062) | arXiv 2025 |
| Cogagent: a Visual Language Model for Gui Agents | Proceedings of the IEEE/CVF CVPR 2024 |
| Clickagent: Enhancing Ui Location Capabilities of Autonomous Agents | Proceedings of the 26th Annual Meeting of the Special Interest Group on Discourse and Dialogue 2025 |
| Spiritsight Agent: Advanced Gui Agent with One Look | Proceedings of the computer vision and pattern recognition conference 2025 |
| [Efficient Multi-turn Rl for Gui Agents Via Decoupled Training and Adaptive Data Curation](https://arxiv.org/abs/2509.23866) | arXiv 2025 |
| Showui: One Vision-language-action Model for Gui Visual Agent | Proceedings of the Computer Vision and Pattern Recognition Conference 2025 |
| [Infigui-g1: Advancing Gui Grounding with Adaptive Exploration Policy Optimization](https://arxiv.org/abs/2508.05731) | Proceedings of the AAAI Conference on Artificial Intelligence 2026 |
| [Infiguiagent: a Multimodal Generalist Gui Agent with Native Reasoning and Reflection](https://arxiv.org/abs/2501.04575) | arXiv 2025 |
| Infigui-g1: Advancing Gui Grounding with Adaptive Exploration Policy Optimization | Proceedings of the AAAI Conference on Artificial Intelligence 2026 |
| [Ui-s1: Advancing Gui Automation Via Semi-online Reinforcement Learning](https://arxiv.org/abs/2509.11543) | arXiv 2025 |
| [Ui-r1: Enhancing Efficient Action Prediction of Gui Agents by Reinforcement Learning](https://arxiv.org/abs/2503.21620) | arXiv 2025 |
| [Gui-r1: a Generalist R1-style Vision-language Action Model for Gui Agents](https://arxiv.org/abs/2504.10458) | arXiv 2025 |
| Visual Test-time Scaling for Gui Agent Grounding | Proceedings of the IEEE/CVF International Conference on Computer Vision 2025 |
| [Computer-using Agent](https://openai.com/index/computer-using-agent/) | 2025 |
| [Ui-tars: Pioneering Automated Gui Interaction with Native Agents](https://arxiv.org/abs/2501.12326) | arXiv 2025 |
| [Falcon-ui: Understanding Gui Before Following User Instructions](https://arxiv.org/abs/2412.09362) | arXiv 2024 |
| [Coact-1: Computer-using Agents with Coding as Actions](https://arxiv.org/abs/2508.03923) | arXiv 2025 |
| [Gui-g$^2](https://arxiv.org/abs/2507.15846) | 2025 |
| [Magicgui: a Foundational Mobile Gui Agent with Scalable Data Pipeline and Reinforcement Fine-tuning](https://arxiv.org/abs/2508.03700) | arXiv 2025 |
| [Kimi-vl Technical Report](https://arxiv.org/abs/2504.07491) | arXiv 2025 |
| [Internvl3. 5: Advancing Open-source Multimodal Models in Versatility, Reasoning, and Efficiency](https://arxiv.org/abs/2508.18265) | arXiv 2025 |
| [Opencua: Open Foundations for Computer-use Agents](https://arxiv.org/abs/2508.09123) | arXiv 2025 |
| Ponder \& Press: Advancing Visual Gui Agent Towards General Computer Control | Findings of the Association for Computational Linguistics: ACL 2025 2025 |
| [Ui-tars-2 Technical Report: Advancing Gui Agent with Multi-turn Reinforcement Learning](https://arxiv.org/abs/2509.02544) | arXiv 2025 |
| [Os-copilot: Towards Generalist Computer Agents with Self-improvement](https://arxiv.org/abs/2402.07456) | arXiv 2024 |
| [Backtrackagent: Enhancing Gui Agent with Error Detection and Backtracking Mechanism](https://arxiv.org/abs/2505.20660) | arXiv 2025 |
| Vsc-rl: Advancing Autonomous Vision-language Agents with Variational Subgoal-conditioned Reinforcement Learning | arXiv 2025 |
| [Aguvis: Unified Pure Vision Agents for Autonomous Gui Interaction](https://arxiv.org/abs/2412.04454) | arXiv 2024 |
| [Step-gui Technical Report](https://arxiv.org/abs/2512.15431) | arXiv 2025 |
| [Step-gui Technical Report](https://arxiv.org/abs/2512.15431) | arXiv 2025 |
| Aria-ui: Visual Grounding for Gui Instructions | Findings of the Association for Computational Linguistics: ACL 2025 2025 |
| [Gta1: Gui Test-time Scaling Agent](https://arxiv.org/abs/2507.05791) | arXiv 2025 |
| [Mobile-agent-v3: Fundamental Agents for Gui Automation](https://arxiv.org/abs/2508.15144) | arXiv 2025 |
| Se-gui: Enhancing Visual Grounding for Gui Agents Via Self-evolutionary Reinforcement Learning | N/A |
| [Uitron: Foundational Gui Agent with Advanced Perception and Planning](https://arxiv.org/abs/2508.21767) | arXiv 2025 |
| Agentcpm-gui: Building Mobile-use Agents with Reinforcement Fine-tuning | Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing: System Demonstrations 2025 |
| [Phi-ground Tech Report: Advancing Perception in Gui Grounding](https://arxiv.org/abs/2507.23779) | arXiv 2025 |
| [Ufo2: the Desktop Agentos](https://arxiv.org/abs/2504.14603) | arXiv 2025 |
| [Omegause: Building a General-purpose Gui Agent for Autonomous Task Execution](https://arxiv.org/abs/2601.20380) | arXiv 2026 |
| [Mai-ui Technical Report: Real-world Centric Foundation Gui Agents](https://arxiv.org/abs/2512.22047) | arXiv 2025 |



### Reinforcement Learning Paradigms

#### Offline RFT Methods

| Paper | Venue / Year |
| --- | --- |
| Direct Preference Optimization: Your Language Model Is Secretly a Reward Model | NeurIPS 2023 |
| [Deepseekmath: Pushing the Limits of Mathematical Reasoning in Open Language Models](https://arxiv.org/abs/2402.03300) | arXiv 2024 |



#### Representative Methods

| Paper | Venue / Year |
| --- | --- |
| Digirl: Training In-the-wild Device-control Agents with Autonomous Reinforcement Learning | NeurIPS 2024 |
| [Dynaweb: Model-based Reinforcement Learning of Web Agents](https://arxiv.org/abs/2601.22149) | arXiv 2026 |
| [Ui-agile: Advancing Gui Agents with Effective Reinforcement Learning and Precise Inference-time Grounding](https://arxiv.org/abs/2507.22025) | arXiv 2025 |
| [Ui-s1: Advancing Gui Automation Via Semi-online Reinforcement Learning](https://arxiv.org/abs/2509.11543) | arXiv 2025 |
| [Hiper: Hierarchical Reinforcement Learning with Explicit Credit Assignment for Large Language Model Agents](https://arxiv.org/abs/2602.16165) | arXiv 2026 |
| [Probabilistic Subgoal Representations for Hierarchical Reinforcement Learning](https://arxiv.org/abs/2406.16707) | arXiv 2024 |
| [Hi-agent: Hierarchical Vision-language Agents for Mobile Device Control](https://arxiv.org/abs/2510.14388) | arXiv 2025 |
| [Ultracua: a Foundation Model for Computer Use Agents with Hybrid Action](https://arxiv.org/abs/2510.17790) | arXiv 2025 |



#### Emerging Directions

| Paper | Venue / Year |
| --- | --- |
| [Group-in-group Policy Optimization for Llm Agent Training](https://arxiv.org/abs/2505.10978) | arXiv 2025 |
| [Enhancing Cooperative Multi-agent Reinforcement Learning with State Modelling and Adversarial Exploration](https://arxiv.org/abs/2505.05262) | arXiv 2025 |
| Wcsac: Worst-case Soft Actor Critic for Safety-constrained Reinforcement Learning | Proceedings of the AAAI Conference on Artificial Intelligence 2021 |
| [Constrained Reinforcement Learning with Smoothed Log Barrier Function](https://arxiv.org/abs/2403.14508) | arXiv 2024 |



#### Algorithmic Advances: Exploration and Multi-Turn Optimization

| Paper | Venue / Year |
| --- | --- |
| [Agentic Entropy-balanced Policy Optimization](https://arxiv.org/abs/2510.14545) | arXiv 2025 |
| [Nested Browser-use Learning for Agentic Information Seeking](https://arxiv.org/abs/2512.23647) | arXiv 2025 |
| Infigui-g1: Advancing Gui Grounding with Adaptive Exploration Policy Optimization | Proceedings of the AAAI Conference on Artificial Intelligence 2026 |
| Webrl: Training Llm Web Agents Via Self-evolving Online Curriculum Reinforcement Learning | ICLR 2024 |
| [Gui-g$^2](https://arxiv.org/abs/2507.15846) | 2025 |



## 🎨 Key Dimensions

### Reward Engineering
The process of defining objective feedback signals for GUI tasks.

<p align="center">
  <img src="pic/reward.png" width="90%" alt="Reward Engineering Pyramid">
  <br>
  <em>The Reward Engineering Pyramid balances accuracy and generality for GUI Agents: rule-based rewards offer precision, while learned rewards and LLM-as-judge enable semantic depth.</em>
</p>


#### Reward Engineering

| Paper | Venue / Year |
| --- | --- |
| Gui Agents: a Survey | Findings of the Association for Computational Linguistics: ACL 2025 2025 |



#### Rule-Based Rewards

| Paper | Venue / Year |
| --- | --- |
| Mind2web: Towards a Generalist Agent for the Web | NeurIPS 2023 |
| Infigui-g1: Advancing Gui Grounding with Adaptive Exploration Policy Optimization | Proceedings of the AAAI Conference on Artificial Intelligence 2026 |
| [Ui-r1: Enhancing Efficient Action Prediction of Gui Agents by Reinforcement Learning](https://arxiv.org/abs/2503.21620) | arXiv 2025 |
| [Gui-g $\^](https://arxiv.org/abs/2507.15846) | 2025 |
| [Gui-g$^2](https://arxiv.org/abs/2507.15846) | 2025 |
| [Lpo: Towards Accurate Gui Agent Interaction Via Location Preference Optimization](https://arxiv.org/abs/2506.09373) | arXiv 2025 |
| [Btl-ui: Blink-think-link Reasoning Model for Gui Agent](https://arxiv.org/abs/2509.15566) | arXiv 2025 |



#### LLM-as-Judge Rewards

| Paper | Venue / Year |
| --- | --- |
| [Smartsnap: Proactive Evidence Seeking for Self-verifying Agents](https://arxiv.org/abs/2512.22322) | arXiv 2025 |
| [Prore: a Proactive Reward System for Gui Agents Via Reasoner--actor Collaboration](https://arxiv.org/abs/2509.21823) | arXiv 2025 |
| Webrl: Training Llm Web Agents Via Self-evolving Online Curriculum Reinforcement Learning | ICLR 2024 |
| [Zerogui: Automating Online Gui Learning at Zero Human Cost](https://arxiv.org/abs/2505.23762) | arXiv 2025 |



#### Learned Rewards

| Paper | Venue / Year |
| --- | --- |
| Infigui-g1: Advancing Gui Grounding with Adaptive Exploration Policy Optimization | Proceedings of the AAAI Conference on Artificial Intelligence 2026 |
| [Gui-g$^2](https://arxiv.org/abs/2507.15846) | 2025 |



### Data Efficiency

#### Synthetic Data via World Models

| Paper | Venue / Year |
| --- | --- |
| [Scaling Agent Learning Via Experience Synthesis](https://arxiv.org/abs/2511.03773) | arXiv 2025 |
| [Scaling Agent Learning Via Experience Synthesis](https://arxiv.org/abs/2511.03773) | arXiv 2025 |
| [Simura: a World-model-driven Simulative Reasoning Architecture for General Goal-oriented Agents](https://arxiv.org/abs/2507.23773) | arXiv 2025 |
| [Websynthesis: World-model-guided Mcts for Efficient Webui-trajectory Synthesis](https://arxiv.org/abs/2507.04370) | arXiv 2025 |
| [Llms as Scalable, General-purpose Simulators for Evolving Digital Agent Training](https://arxiv.org/abs/2510.14969) | arXiv 2025 |
| [Webworld: a Large-scale World Model for Web Agent Training](https://arxiv.org/abs/2602.14721) | arXiv 2026 |
| [Code2world: a Gui World Model Via Renderable Code Generation](https://arxiv.org/abs/2602.09856) | arXiv 2026 |



#### Enhancement of Human Demonstrations

| Paper | Venue / Year |
| --- | --- |
| [Gui-rewalk: Massive Data Generation for Gui Agent Via Stochastic Exploration and Intent-aware Reasoning](https://arxiv.org/abs/2509.15738) | arXiv 2025 |
| [Gui-rewalk: Massive Data Generation for Gui Agent Via Stochastic Exploration and Intent-aware Reasoning](https://arxiv.org/abs/2509.15738) | arXiv 2025 |
| Watch and Learn? Using Edpuzzle to Enhance the Use of Online Videos | Management Teaching Review 2019 |
| [Watch and Learn: Learning to Use Computers from Online Videos](https://arxiv.org/abs/2510.04673) | arXiv 2025 |
| [Watch and Learn: Learning to Use Computers from Online Videos](https://arxiv.org/abs/2510.04673) | arXiv 2025 |
| Os-genesis: Automating Gui Agent Trajectory Construction Via Reverse Task Synthesis | Proceedings of the 63rd ACL 2025 |
| [Agenttrek: Agent Trajectory Synthesis Via Guiding Replay with Web Tutorials](https://arxiv.org/abs/2412.09605) | arXiv 2024 |
| [Prune4web: Dom Tree Pruning Programming for Web Agent](https://arxiv.org/abs/2511.21398) | arXiv 2025 |



#### Iterative Self-Improvement

| Paper | Venue / Year |
| --- | --- |
| [Gui-r1: a Generalist R1-style Vision-language Action Model for Gui Agents](https://arxiv.org/abs/2504.10458) | arXiv 2025 |
| [Gui-r1: a Generalist R1-style Vision-language Action Model for Gui Agents](https://arxiv.org/abs/2504.10458) | arXiv 2025 |
| [Co-epg: a Framework for Co-evolution of Planning and Grounding in Autonomous Gui Agents](https://arxiv.org/abs/2511.10705) | arXiv 2025 |
| [Co-epg: a Framework for Co-evolution of Planning and Grounding in Autonomous Gui Agents](https://arxiv.org/abs/2511.10705) | arXiv 2025 |



### Technical Innovations

#### Multimodal Perception: Active and Adaptive Visual Grounding

| Paper | Venue / Year |
| --- | --- |
| [Gui-eyes: Tool-augmented Perception for Visual Grounding in Gui Agents](https://arxiv.org/abs/2601.09770) | arXiv 2026 |
| Infigui-g1: Advancing Gui Grounding with Adaptive Exploration Policy Optimization | Proceedings of the AAAI Conference on Artificial Intelligence 2026 |
| [Gui-g$^2](https://arxiv.org/abs/2507.15846) | 2025 |
| [Gui-actor: Coordinate-free Visual Grounding for Gui Agents](https://arxiv.org/abs/2506.03143) | arXiv 2025 |
| [Gui-aima: Aligning Intrinsic Multimodal Attention with a Context Anchor for Gui Grounding](https://arxiv.org/abs/2511.00810) | arXiv 2025 |



#### Memory and Planning: Sustaining Context over Long Horizons

| Paper | Venue / Year |
| --- | --- |
| [Mga: Memory-driven Gui Agent for Observation-centric Interaction](https://arxiv.org/abs/2510.24168) | arXiv 2025 |
| [Memr $\^](https://arxiv.org/abs/2512.20237) | 2025 |
| [Plan-and-act: Improving Planning of Agents for Long-horizon Tasks](https://arxiv.org/abs/2503.09572) | arXiv 2025 |
| [Magnet: Towards Adaptive Gui Agents with Memory-driven Knowledge Evolution](https://arxiv.org/abs/2601.19199) | arXiv 2026 |
| [Agentprog: Empowering Long-horizon Gui Agents with Program-guided Context Management](https://arxiv.org/abs/2512.10371) | arXiv 2025 |
| [History-aware Reasoning for Gui Agents](https://arxiv.org/abs/2511.09127) | arXiv 2025 |
| Webagent-r1: Training Web Agents Via End-to-end Multi-turn Reinforcement Learning | Proceedings of the Conference on Empirical Methods in Natural Language Processing (EMNLP) 2025 |
| [Auto-scaling Continuous Memory for Gui Agent](https://arxiv.org/abs/2510.09038) | arXiv 2025 |
| [Memsearcher: Training Llms to Reason, Search and Manage Memory Via End-to-end Reinforcement Learning](https://arxiv.org/abs/2511.02805) | arXiv 2025 |



## 📊 Training Resources

### Datasets

<p align="center">
  <img src="pic/data.png" width="90%" alt="Training Pipeline Pyramid">
  <br>
  <em>This pyramid depicts a four-stage data-training pipeline for agent capability, progressing from static data imitation to offline RL, synthetic simulation, and online RL.</em>
</p>


#### Demonstration and Trajectory Datasets

| Paper | Venue / Year |
| --- | --- |
| Mind2web: Towards a Generalist Agent for the Web | NeurIPS 2023 |
| Omniact: a Dataset and Benchmark for Enabling Multimodal Generalist Autonomous Agents for Desktop and Web | European Conference on Computer Vision 2024 |
| On the Effects of Data Scale on Ui Control Agents | NeurIPS 2024 |
| Androidinthewild: a Large-scale Dataset for Android Device Control | NeurIPS 2023 |



#### Perception and Grounding Datasets

| Paper | Venue / Year |
| --- | --- |
| Unveiling the Tricks: Automated Detection of Dark Patterns in Mobile Applications | Proceedings of the 36th Annual ACM Symposium on User Interface Software and Technology 2023 |
| Rico: a Mobile App Dataset for Building Data-driven Design Applications | Proceedings of the 30th annual ACM symposium on user interface software and technology 2017 |
| Widget Captioning: Generating Natural Language Description for Mobile User Interface Elements | Proceedings of the Conference on Empirical Methods in Natural Language Processing (EMNLP) 2020 |
| Ferret-ui 2: Mastering Universal User Interface Understanding Across Platforms | ICLR 2024 |
| Screenspot-pro: Gui Grounding for Professional High-resolution Computer Use | Proceedings of the 33rd ACM International Conference on Multimedia 2025 |
| Screen2words: Automatic Mobile Ui Summarization with Multimodal Learning | The 34th Annual ACM Symposium on User Interface Software and Technology 2021 |
| Ferret-ui: Grounded Mobile Ui Understanding with Multimodal Llms | European Conference on Computer Vision 2024 |



#### Synthetic and RL-Generated Corpora

| Paper | Venue / Year |
| --- | --- |
| [Agent-x: Evaluating Deep Multimodal Reasoning in Vision-centric Agentic Tasks](https://arxiv.org/abs/2505.24876) | arXiv 2025 |
| [Gui-bee: Align Gui Action Grounding to Novel Environments Via Autonomous Exploration](https://arxiv.org/abs/2501.13896) | arXiv 2025 |
| [End-to-end Navigation with Vision Language Models: Transforming Spatial Reasoning Into Question-answering](https://arxiv.org/abs/2411.05755) | arXiv 2024 |
| Visualwebarena: Evaluating Multimodal Agents on Realistic Visual Web Tasks | Proceedings of the 62nd ACL 2024 |
| Explorer: Scaling Exploration-driven Web Trajectory Synthesis for Multimodal Web Agents | Findings of the Association for Computational Linguistics: ACL 2025 2025 |
| [Webcanvas: Benchmarking Web Agents in Online Environments](https://arxiv.org/abs/2406.12373) | arXiv 2024 |
| [Ui-tars: Pioneering Automated Gui Interaction with Native Agents](https://arxiv.org/abs/2501.12326) | arXiv 2025 |
| [Scaling Synthetic Task Generation for Agents Via Exploration](https://arxiv.org/abs/2509.25047) | arXiv 2025 |
| Androidworld: a Dynamic Benchmarking Environment for Autonomous Agents | ICLR 2024 |
| [Bearcubs: a Benchmark for Computer-using Web Agents](https://arxiv.org/abs/2503.07919) | arXiv 2025 |
| Beyond Browsing: Api-based Web Agents | Findings of the Association for Computational Linguistics: ACL 2025 2025 |
| Webwalker: Benchmarking Llms in Web Traversal | Proceedings of the 63rd ACL 2025 |
| Osworld: Benchmarking Multimodal Agents for Open-ended Tasks in Real Computer Environments | NeurIPS 2024 |
| [Theagentcompany: Benchmarking Llm Agents on Consequential Real World Tasks](https://arxiv.org/abs/2412.14161) | arXiv 2024 |
| Appagent: Multimodal Agents as Smartphone Users | Proceedings of the 2025 CHI Conference on Human Factors in Computing Systems 2025 |
| Webarena: a Realistic Web Environment for Building Autonomous Agents | ICLR 2023 |



### Interactive Environments

#### Web and Browser Environments

| Paper | Venue / Year |
| --- | --- |
| [The Browsergym Ecosystem for Web Agent Research](https://arxiv.org/abs/2412.05467) | arXiv 2024 |
| Mind2web: Towards a Generalist Agent for the Web | NeurIPS 2023 |
| [A Data-driven Approach for Learning to Control Computers](https://arxiv.org/abs/2202.08137) | arXiv 2022 |
| Visualwebarena: Evaluating Multimodal Agents on Realistic Visual Web Tasks | Proceedings of the 62nd ACL 2024 |
| Reinforcement Learning on Web Interfaces Using Workflow-guided Exploration | ICLR 2018 |
| [Webchorearena: Evaluating Web Browsing Agents on Realistic Tedious Web Tasks](https://arxiv.org/abs/2506.01952) | arXiv 2025 |
| Webshop: Towards Scalable Real-world Web Interaction with Grounded Language Agents | NeurIPS 2022 |
| Webarena: a Realistic Web Environment for Building Autonomous Agents | ICLR 2023 |



#### Desktop and OS Environments

| Paper | Venue / Year |
| --- | --- |
| [Computerrl: Scaling End-to-end Online Reinforcement Learning for Computer Use Agents](https://arxiv.org/abs/2508.14040) | arXiv 2025 |
| Screenagent: a Vision Language Model-driven Computer Control Agent | International Joint Conference on Artificial Intelligence (IJCAI) 2024 |
| Osworld: Benchmarking Multimodal Agents for Open-ended Tasks in Real Computer Environments | NeurIPS 2024 |



#### Mobile Environments

| Paper | Venue / Year |
| --- | --- |
| Androidworld: a Dynamic Benchmarking Environment for Autonomous Agents | ICLR 2024 |
| [Mobilegui-rl: Advancing Mobile Gui Agent Through Reinforcement Learning in Online Environment](https://arxiv.org/abs/2507.05720) | arXiv 2025 |
| [Androidenv: a Reinforcement Learning Platform for Android](https://arxiv.org/abs/2105.13231) | arXiv 2021 |
| [Uisim: an Interactive Image-based Ui Simulator for Dynamic Mobile Environments](https://arxiv.org/abs/2509.21733) | arXiv 2025 |
| Mobile-env: a Universal Platform for Training and Evaluation of Mobile Interaction | CoRR 2023 |
| [Mai-ui Technical Report: Real-world Centric Foundation Gui Agents](https://arxiv.org/abs/2512.22047) | arXiv 2025 |



#### Cross-Platform Trends and Synthesis

| Paper | Venue / Year |
| --- | --- |
| [Osworld-mcp: Benchmarking Mcp Tool Invocation in Computer-use Agents](https://arxiv.org/abs/2510.24563) | arXiv 2025 |
| [Mcpworld: a Unified Benchmarking Testbed for Api, Gui, and Hybrid Computer Use Agents](https://arxiv.org/abs/2506.07672) | arXiv 2025 |



### RL Infrastructure

<p align="center">
  <img src="pic/distribute.png" width="90%" alt="Distributed RL Architecture">
  <br>
  <em>An asynchronous distributed architecture for GUI RL agent training, decoupling slow environment interaction from fast GPU learning.</em>
</p>


#### VLM-RL Algorithm Libraries and Framework Evolution

| Paper | Venue / Year |
| --- | --- |
| Openrlhf: an Easy-to-use, Scalable and High-performance Rlhf Framework | Proceedings of the Conference on Empirical Methods in Natural Language Processing: System Demonstrations (EMNLP) 2024 |
| Efficient Memory Management for Large Language Model Serving with Pagedattention | Proceedings of the 29th symposium on operating systems principles 2023 |
| Real: Efficient Rlhf Training of Large Language Models with Parameter Reallocation | Proceedings of Machine Learning and Systems 2025 |
| Hybridflow: a Flexible and Efficient Rlhf Framework | Proceedings of the Twentieth European Conference on Computer Systems 2025 |
| [Megatron-lm: Training Multi-billion Parameter Language Models Using Model Parallelism](https://arxiv.org/abs/1909.08053) | arXiv 2019 |
| [Rewarddance: Reward Scaling in Visual Generation](https://arxiv.org/abs/2509.08826) | arXiv 2025 |
| Pytorch Fsdp: Experiences on Scaling Fully Sharded Data Parallel | Proceedings of the VLDB Endowment 2023 |



#### Distributed Rollout and Training Architectures

| Paper | Venue / Year |
| --- | --- |
| [Areal: a Large-scale Asynchronous Reinforcement Learning System for Language Reasoning](https://arxiv.org/abs/2505.24298) | arXiv 2025 |
| [Distrl: an Asynchronous Distributed Reinforcement Learning Framework for On-device Control Agents](https://arxiv.org/abs/2410.14803) | arXiv 2024 |
| [Agent. Xpu: Efficient Scheduling of Agentic Llm Workloads on Heterogeneous Soc](https://arxiv.org/abs/2506.24045) | arXiv 2025 |
| [Hethub: a Distributed Training System with Heterogeneous Cluster for Large-scale Models](https://arxiv.org/abs/2405.16256) | arXiv 2024 |



#### Reward Engineering and Verification Systems

| Paper | Venue / Year |
| --- | --- |
| [Agentic Reward Modeling: Verifying Gui Agent Via Online Proactive Interaction](https://arxiv.org/abs/2602.00575) | arXiv 2026 |
| [Mano Technical Report](https://arxiv.org/abs/2509.17336) | arXiv 2025 |
| Infigui-g1: Advancing Gui Grounding with Adaptive Exploration Policy Optimization | Proceedings of the AAAI Conference on Artificial Intelligence 2026 |
| [Progrm: Build Better Gui Agents with Progress Rewards](https://arxiv.org/abs/2505.18121) | arXiv 2025 |



#### Memory Management and Long-Horizon Reasoning

| Paper | Venue / Year |
| --- | --- |
| [Mga: Memory-driven Gui Agent for Observation-centric Interaction](https://arxiv.org/abs/2510.24168) | arXiv 2025 |
| [Hi-agent: Hierarchical Vision-language Agents for Mobile Device Control](https://arxiv.org/abs/2510.14388) | arXiv 2025 |
| [Memory-r1: Enhancing Large Language Model Agents to Manage and Utilize Memories Via Reinforcement Learning](https://arxiv.org/abs/2508.19828) | arXiv 2025 |



#### Integration and Ecosystem Standardization

| Paper | Venue / Year |
| --- | --- |
| [The Browsergym Ecosystem for Web Agent Research](https://arxiv.org/abs/2412.05467) | arXiv 2024 |
| Openhands: an Open Platform for Ai Software Developers as Generalist Agents | ICLR 2024 |
| Autogen: Enabling Next-gen Llm Applications Via Multi-agent Conversations | First Conference on Language Modeling 2024 |



## 📝 Citation

If you find this repository or our survey useful, please consider citing:

```bibtex
@article{hu2026rl_gui_survey,
  title={Reinforcement Learning in GUI Agents: A Survey},
  author={Hu, Junan and Liu, Jian and Hu, Jiarui and Lai, Jingxiang and Sheng, Yiwei and Du, Dazhao and Guo, Song},
  journal={arXiv preprint arXiv:25xx.xxxxx},
  year={2026}
}
```
