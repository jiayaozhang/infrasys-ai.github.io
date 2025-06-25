---
title: "AI 系统 "
# date: 2025-06-25
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



{{< button href="https://infrasys-ai.github.io/aisystem-docs/" label="全书链接" external=true >}}


希望各位看官喜欢！

## 课程背景

这个开源课程英文名字叫做AI System(AISys)，中文名字叫做AI系统。

本开源课程主要是跟大家一起探讨和学习人工智能、深度学习的系统设计，而整个系统是围绕着 ZOMI 在工作当中所积累、梳理、构建 AI 系统全栈的内容。希望跟所有关注 AI 开源课程的好朋友一起探讨研究，共同促进学习讨论。


## 课程内容大纲

课程主要包括以下五大模块：

| 教程内容  | 简介   | 
| ------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| AI 系统全栈概述  | AI 基础知识和 AI 系统的全栈概述的AI 系统概述，以及深度学习系统的系统性设计和方法论，主要是整体了解 AI 训练和推理全栈的体系结构内容。 | 
| AI 芯片与体系架构   | 作为 AI 的硬件体系架构主要是指 AI 芯片，这里就很硬核了，从CPU、GPU 的芯片基础到 AI 芯片的原理、设计和应用场景范围，AI 芯片的设计不仅仅考虑针对 AI 计算的加速，还需要充分考虑到AI 的应用算法、AI 框架等中间件，而不是停留在天天喊着吊打英伟达和 CUDA，实际上芯片难以用起来。 |
| AI 编程与计算架构  | 进阶篇介绍 AI 编程与计算架构，将站在系统设计的角度，思考在设计现代机器学习系统中需要考虑的编译器问题，特别是中间表达乃至后端优化。 | 
| AI 推理系统与引擎  | 实际应用推理系统与引擎，讲了太多原理身体太虚容易消化不良，还是得回归到业务本质，让行业、企业能够真正应用起来，而推理系统涉及一些核心算法和注意的事情也分享下。 
| AI 框架核心技术  | 介绍 AI 框架核心技术，首先介绍任何一个 AI 框架都离不开的自动微分，通过自动微分功能后就会产生表示神经网络的图和算子，然后介绍 AI 框架前端的优化，还有最近很火的大模型分布式训练在 AI 框架中的关键技术。  | 

## 课程设立目的

本课程主要为本科生高年级、硕博研究生、AI 系统从业者设计，帮助大家：

1. 完整了解 AI 的计算机系统架构，并通过实际问题和案例，来了解 AI 完整生命周期下的系统设计。

2. 介绍前沿系统架构和 AI 相结合的研究工作，了解主流框架、平台和工具来了解 AI 系统。

## 课程部分

### **一. AI 系统概述**

| 编号  | 名称       | 具体内容      |
|:---:|:----- |:--- |
| 1      | AI 系统 | 算法、框架、体系结构的结合，形成 AI 系统  |

### **二. AI 芯片体系结构**

| 编号  | 名称       | 具体内容      |
|:---:|:----- |:--- |
| 1      | AI 计算体系 | 神经网络等 AI 技术的计算模式和计算体系架构  |
| 2      | AI 芯片基础   | CPU、GPU、NPU 等芯片体系架构基础原理       |
| 3      | 图形处理器 GPU | GPU 的基本原理，英伟达 GPU 的架构发展  |
| 4      | 英伟达 GPU 详解 | 英伟达 GPU 的 Tensor Core、NVLink 深度剖析 |
| 5      | 国外 AI 处理器  | 谷歌、特斯拉等专用 AI 处理器核心原理  |
| 6      | 国内 AI 处理器  | 寒武纪、燧原科技等专用 AI 处理器核心原理  |
| 7      | AI 芯片黄金 10 年  | 对 AI 芯片的编程模式和发展进行总结  |

### **三. AI 编译原理**

| 编号  | 名称       | 具体内容      |
|:---:|:----- |:--- |
| 1      | 传统编译器 | 传统编译器 GCC 与 LLVM，LLVM 详细架构  |
| 2      | AI 编译器 | AI 编译器发展与架构定义，未来挑战与思考   |
| 3      | 前端优化    | AI 编译器的前端优化(算子融合、内存优化等)  |
| 4      | 后端优化    | AI 编译器的后端优化(Kernel 优化、AutoTuning) |
| 5      | 多面体      | 待更 ing...      |
| 6      | PyTorch2.0 | PyTorch2.0 最重要的新特性：编译技术栈  |

### **四. AI 推理系统**

| 编号  | 名称       | 具体内容      |
|:---:|:----- |:--- |
| 1      | 推理系统  | 推理系统整体介绍，推理引擎架构梳理  |
| 2      | 轻量网络  | 轻量化主干网络，MobileNet 等 SOTA 模型介绍 |
| 3      | 模型压缩  | 模型压缩 4 件套，量化、蒸馏、剪枝和二值化       |
| 4      | 转换&优化 | AI 框架训练后模型进行转换，并对计算图优化      |
| 5      | Kernel 优化 | Kernel 层、算子层优化，对算子、内存、调度优化  |

### **五. AI 框架核心技术**

| 编号  | 名称       | 具体内容      |
|:---:|:----- |:--- |
| 1   | AI 框架基础 | AI 框架的作用、发展、编程范式    |
| 2   | 自动微分    | 自动微分的实现方式和原理       |
| 3   | 计算图   | 计算图的概念，图优化、图执行、控制流表达  |