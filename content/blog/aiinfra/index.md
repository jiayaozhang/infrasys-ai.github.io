---
title: "AI Infrastructure"
# date: 2024-11-28T00:00:03+08:00
weight: 1
# aliases: ["/first"]
# tags: ["Research"]
# draft: true
# comments: false
# description: "Desc Text."
# disable_share: false
# hide_meta: false
# hide_summary: false # to hide summary in list
# hide_footer: false
math: true
# search_hidden: false # to hide from search page
show_reading_time: false
show_bread_crumbs: true
show_post_nav_links: false # the prev/next after the content
show_code_copy_buttons: true
show_word_count: false
# use_hugo_toc: true
# show_toc: true
# toc_open: true # default expand all
# cover:
#     image: "path"
#     # can also paste direct link from external site
#     # ex. https://i.ibb.co/K0HVPBd/paper-mod-profilemode.png
#     alt: "<alt text>"
#     caption: "<text>"
#     relative: true # To use relative path for cover image, used in hugo Page-bundles
#     responsive_images: true
#     hidden: false
# header:
#   background: "" # background css value
#   background_image: ""
#   gradient: false
#   blur: false
---



{{< button href="https://infrasys-ai.github.io/aiinfra-docs" label="Full book Links" external=true >}}

## Course Background

This open-source project is officially named "AIInfra" in English and "AI Infrastructure" in Chinese. Large models rely on full-stack hardware/software optimizations across AI clusters - from individual AI chips composing clusters, compilers enabling upper-layer frameworks, to distributed parallel training requiring cluster communication algorithms. Recent advancements include agent technologies in the large model domain.

This course explores system design for AI and deep learning, focusing on foundational hardware/software stacks for large model systems accumulated through ZOMI's professional experience. We aim to collaborate with AI enthusiasts to promote knowledge sharing in following areas:
- Distributed clusters/architectures
- Distributed training
- Large model algorithms

## Curriculum Outline

| No. | Content | Description | Link |
|-------|-----------------------|------------------------------------------------------------------------------------------------|---------------------------|
| 00 | [Large Model System Overview](#00-overview-of-large-models) | Covers key technologies: Scaling Law applications, training/inference stacks, system comparisons | |
| 01 | [AI Computing Clusters](#01-ai-computing-clusters) | Cluster O&M, performance optimization, training-inference integration | |
| 02 | [Communication & Storage](#02-communication-storage) | Network principles, high-speed interconnects, MPI/NCCL/HCCL libraries, storage solutions | |
| 03 | [Cloud Native & Containers](#03-cloud-native) | Container/K8S fundamentals, AI deployment, resource scheduling | |
| 04 | [Distributed Training](#04-distributed-training) | Parallel strategies, Megatron/DeepSeed architectures, MoE optimization | |
| 05 | [Distributed Inference](#05-distributed-inference) | KV caching, operator optimization, vLLM/SGLang frameworks | |
| 06 | [Algorithms & Data](#06-algorithms-data) | Transformer evolution, MoE implementations, multimodal architectures | |
| 07 | [Applications](#07-applications) | AI Agents, RAG, autonomous driving, privacy computing | |

## Course Objectives

Designed for senior undergraduates, graduate students, and AI practitioners, this course helps:
1. Understand complete AI system architecture through real-world cases
2. Explore cutting-edge system architectures integrated with AI

## Core Modules

### **00. Large Model Systems**
| No. | Topic | Content |
|---|-----------------------|-----------------------------------|
|1|Scaling Law Applications| Cross-scenario implementations |
|2|Full Training-Inference Pipeline| Hardware/software co-optimization |
|3|System Comparisons| Differences in resource allocation and software stacks |

### **01. AI Computing Clusters**  
| No. | Topic | Content |
|---|-----------------------|-----------------------------------|
|1|HPC Evolution| 10K-card cluster construction challenges |
|2|Cluster Networking| Ascend cluster networking solutions |
|3|Performance Analysis| Metrics modeling and troubleshooting |

### **02. Communication & Storage**
| No. | Topic | Content |
|---|-----------------------|-----------------------------------|
|1|Network Topologies| High-speed interconnect architectures |
|2|Collective Communication| MPI/NCCL/HCCL algorithm principles |
|3|Storage Solutions| Checkpointing and gradient storage |

### **03. Cluster Containers & Cloud Native**

AI cluster cloud-native architecture: container technology, K8S orchestration, AI cloud platforms and task scheduling to enhance cluster resource management and application deployment efficiency.

| No.  | Name       | Details      |
|:---:|:--- |:--- |
| 1      | Container Era | Container technology fundamentals and cloud-native architecture analysis, combined with distributed training application practices  |
| 2      | Container First Experience | Docker and K8S basic principles and hands-on practice, covering container technology and cluster management architecture analysis  |
| 3      | Deep Dive into K8S |  In-depth analysis of K8S core mechanisms: orchestration, storage, networking, scheduling and monitoring practices |
| 4      | AI Cloud Platform |  AI cloud platform evolution and cloud-native architecture analysis, covering continuous delivery and intelligent operations practices  |


### **04. Distributed Training**

Complete guide to large model training: parallel strategies, acceleration algorithms, fine-tuning and evaluation, covering the entire process from training to optimization.

| No.  | Name       | Details      |
|:---:|:--- |:--- |
| 1      | Distributed Parallel Fundamentals | Distributed parallel strategy classification, model adaptation and hardware resource optimization comparison  |
| 2      | Large Model Parallel Advanced | Megatron, DeepSpeed architecture analysis, MoE scaling and efficient training strategies |
| 3      | Large Model Training Acceleration | Large model training acceleration in algorithm optimization, memory management and computing convergence strategy analysis  |
| 4      | Post-training & Reinforcement Learning |  Post-training and reinforcement learning algorithm comparison, framework analysis and engineering practices  |
| 5      | Large Model Fine-tuning SFT |  Large model fine-tuning algorithm principles, variant optimization and multimodal practices  |
| 6      | Large Model Validation & Evaluation | Large model evaluation, benchmarking and unified framework analysis   |


### **05. Distributed Inference**

Complete guide to large model inference: acceleration techniques, architecture optimization, long sequence processing and compression solutions, covering the full inference pipeline and practical implementation.

| No.  | Name       | Details      |
|:---:|:--- |:--- |
| 1      | Basic Concepts |  Large model inference pipeline, framework comparison and performance metrics analysis |
| 2      | Large Model Inference Acceleration | KV cache optimization, operator improvements and efficient engine analysis in large model inference acceleration |
| 3      | Architecture Scheduling Acceleration | Cache optimization, batch processing and distributed system scheduling analysis in architecture scheduling acceleration |
| 4      | Long Sequence Inference | Long sequence inference algorithm optimization, parallel strategies and efficient generation methods analysis |
| 5      | Output Sampling | Basic methods, acceleration strategies and MoE inference optimization for inference output sampling |
| 6      | Large Model Compression | Low-precision quantization, knowledge distillation and efficient inference optimization analysis |
| 7      | Inference Framework Architecture | Core technologies and deployment practices of mainstream inference frameworks like vLLM, SGLang |
| 8      | DeepSeek Open Source | DeepSeek inference FlashMLA, DeepEP and efficient operator acceleration analysis |


### **06. Large Model Algorithms & Data**

Comprehensive overview of large model algorithms and data: Transformer architecture, MoE innovations, multimodal models and complete data engineering pipeline practices.

| No.  | Name       | Details      |
|:---:|:--- |:--- |
| 1      | Transformer Architecture | In-depth introduction to Transformer architecture principles |
| 2      | MoE Architecture | MoE (Mixture of Experts) model architecture principles and detailed implementation |
| 3      | Innovative Architectures | New large model structures like SSM, MAMBA, RWKV, Linear Transformer, JEPA |
| 4      | Image-Text Generation & Understanding | Multimodal alignment, generation, understanding and unified multimodal architecture analysis  |
| 5      | Video Large Models | Video multimodal understanding and generation method evolution and Flow Matching applications |
| 6      | Audio Large Models | Speech multimodal recognition, synthesis and end-to-end model evolution and inference applications  |
| 7      | Data Engineering | Data engineering, Prompt Engineering and related technologies |


### **07. Large Model Applications**

Large model applications: AI Agent technology, RAG retrieval-augmented generation and GraphRAG, driving intelligent agents and knowledge-enhanced application deployment.

| No.  | Name       | Details      |
|:---:|:--- |:--- |
| 00     | Large Model Trends  |  Technical insights from OpenAI, WWDC, GTC and other conferences   |
| 01     | Agent Basic Concepts  | AI Agent principles and architecture   |
| 02     | Agent Core Technologies  | Deep dive into AI Agent principles and core technologies   |
| 03     | Retrieval-Augmented Generation (RAG)  |  Introduction to retrieval-augmented generation technology  |
| 04     | Autonomous Driving  |  End-to-end autonomous driving technology principles analysis, changes brought by Robotaxi to the industry  |
| 05     | Embodied Intelligence  |  Technical principles, embodied architecture and industry thoughts on embodied intelligence  |
| 06     | Generative Recommendation  |  Revolutionary development in recommendation field, new growth brought by large model generative recommendation  |
| 07     | AI Security  |  Privacy computing development process, future development of privacy computing  |
| 08     | AI History Decade  |  Review of major AI events in the past decade, 2012-2025 development in models, algorithms, and chip hardware  |