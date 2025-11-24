# Ray Summit 2025专业演讲-没有字幕-提取视频描述

## Ray: Last Year’s Progress and the Road Ahead | Ray Summit 2025

[https://www.youtube.com/watch?v=w4S7iGETV5s ](https://www.youtube.com/watch?v=w4S7iGETV5s%20)  
视频描述：在2025年Ray峰会上，Anyscale公司的Ed Oakes和姚佳俊分享了过去一年为提升Ray在尖端大规模应用中的性能、韧性与可观测性所取得的重大进展。

他们详细介绍了Ray Core运行时的关键改进，包括：

- Ray直接传输技术：新一代通信层，显著优化加速器间的数据传输
- 基于cgroups的原生资源隔离：实现更强的工作负载分离与更可预测的性能表现
- 增强的网络故障韧性：确保长期运行的分布式任务在真实环境中保持稳定
- 显著提升的可观测性：提供集群规模下系统行为的深度洞察

Ed和佳俊还首次展望了Ray Core 2026年路线图，规划了旨在支持日益复杂、性能关键的分布式工作负载的新一轮功能特性与架构升级。

与会者将清晰了解Ray如何持续演进以满足下一代AI系统需求，并掌握平台在未来一年的发展方向。

## How Ray Data Powers Scalable AI Workloads | Ray Summit 2025

[https://www.youtube.com/watch?v=xUM8ZSyDdwE ](https://www.youtube.com/watch?v=xUM8ZSyDdwE%20)  
视频描述：在2025年Ray峰会上，Anyscale公司的Balaji Veeramani分享了Ray Data如何发展成为Ray生态系统中使用最广泛的库之一——专为新一代AI工作负载而构建。

与传统的数据处理引擎不同，Ray Data从设计之初就专注于多模态、加速器原生且以AI为核心的流水线。在本次演讲中，讲者概述了Ray Data的核心能力，并重点介绍了过去一年中新增的主要功能，以支持：

跨GPU和集群的大规模批量推理

面向海量模型的分布式训练数据准备与读取

涵盖图像、视频、文本等的高性能多模态数据处理

无论您正在构建LLM流水线、多模态训练工作流，还是高吞吐量推理系统，本次分享都将清晰展示Ray Data如何为规模化现代AI提供核心动力。

## How to Get Started with Distributed Training at Scale | Ray Summit 2025

[https://www.youtube.com/watch?v=1TfJVNoMAgc ](https://www.youtube.com/watch?v=1TfJVNoMAgc%20)  
视频描述：在2025年Ray峰会上，Anyscale公司的Suman Debnath和Linda Haviv分享了如何掌握分布式训练策略，这些策略对于高效扩展当今深度学习模型至关重要。

他们首先解析了三大核心技术——数据并行、模型并行和流水线并行，并阐述了随着模型和数据集的增长，每种方法最适合的应用场景。本次讲座涵盖了分片训练和ZeRO等高级方法，以及实际大规模集群环境中出现的权衡取舍。

Suman和Linda还探讨了分布式训练中最棘手的挑战，包括通信开销、容错性、可复现性以及异构计算资源管理。随后他们演示了如何将PyTorch与Ray结合使用，以最少的代码改动实现这些策略，从而更轻松地从原型阶段扩展到生产环境。

您将学习到：

- 数据并行、模型并行和流水线并行的原理及适用场景
- 如何克服通信开销和系统故障等可扩展性瓶颈
- 如何运用Ray与PyTorch启动、编排和监控大规模分布式训练任务

## MLOps with Ray on Anyscale | Ray Summit 2025

[https://www.youtube.com/watch?v=pMTyrlExdlk](https://www.youtube.com/watch?v=pMTyrlExdlk)  
视频描述：在集群上无缝扩展训练与推理

提升机器学习工作流的可观测性、可复现性与治理能力

在降低运维开销的同时加速迭代周期

参会者将学习如何基于Anyscale平台的Ray框架构建健壮的生产级机器学习系统——为任意规模的团队实现高效可扩展的MLOps能力。

## Maximizing Compute Efficiency on Anyscale | Ray Summit 2025

[https://www.youtube.com/watch?v=O-SH2AkUKnA ](https://www.youtube.com/watch?v=O-SH2AkUKnA%20)  
视频描述：在2025年Ray峰会上，Anyscale公司的Janet Li和Simran Mhatre分享了Ray可观测性的最新进展——这些工具旨在帮助开发者更清晰地调试、优化和理解分布式AI工作负载。

她们首先解释了为什么情境化可观测性至关重要。随着Ray成为分布式AI应用的标准框架，用户越来越多地遇到大型多节点系统固有的复杂性。专门构建的可观测性工具对于诊断资源瓶颈、任务失败和内存压力等问题至关重要。

Janet和Simran随后介绍了Anyscale平台在可观测性方面的重大改进，包括为Ray Core、Ray Train和Ray Data提供的可扩展持久化仪表盘视图。她们深入解析了支撑这些仪表盘的架构，并演示如何在保证所有数据留存于客户云环境的前提下安全运行。

演讲者还发布了开源的Ray Export API，该接口允许用户将Ray仪表盘中显示的相同事件持久化存储、分析并集成到自己的监控分析系统中。

通过现场演示，她们展现了如何使用这些工具调试现实场景中的问题——从内存溢出错误到低效资源利用率——使得Ray工作负载比以往任何时候都更加透明、可靠且易于优化。

## RLlib: Lessons from the V2 Stack and Road Ahead | Ray Summit 2025

[https://www.youtube.com/watch?v=yC_Pp13EZo8 ](https://www.youtube.com/watch?v=yC_Pp13EZo8%20)  
视频描述：在Ray Summit 2025大会上，Anyscale公司的Artur Niederfahrenhorst和Simon Lars Zehnders分享了RLlib v2技术栈发布背后的重要里程碑——该版本现已正式可用，并针对新一代大规模强化学习工作负载进行了重新设计。

他们深入解析了塑造全新RLlib v2架构的关键经验，详细介绍了提升可扩展性、可靠性和可扩展性的工程改进。本次分享重点展示了RLlib实现万级环境运行器和百级学习器规模的核心增强能力，可支持高吞吐量的大规模分布式强化学习训练。

Artur和Simon还展望了RLlib的发展路线图，包括与各类模拟器的深度集成，以及针对复杂模拟密集型强化学习应用的扩展能力。

无论您正在构建大规模强化学习系统、加速研究流程，还是将强化学习投入生产环境，本场分享都将清晰展现RLlib的未来发展蓝图，以及它如何持续演进以满足现代人工智能的需求。

## Ray Observability Upgrades: Debug, Optimize, and Scale Faster | Ray Summit 2025

[https://www.youtube.com/watch?v=YODsR3G3pVY ](https://www.youtube.com/watch?v=YODsR3G3pVY%20)  
随后，演讲者重点介绍了Anyscale平台在可观测性方面的重大升级，包括为Ray Core、Ray Train和Ray Data提供的可扩展持久化仪表盘视图。他们深入解析了这些仪表盘的底层架构，并阐释了如何在确保所有数据留存于客户云环境的前提下实现安全运维。

Nikita与Mengjin还正式发布了开源工具Ray Export API，该接口支持用户将Ray仪表盘中展示的各类事件持久化存储、分析并集成至自有监控或分析系统中。

通过现场演示，他们生动展现了如何运用这些工具诊断现实场景中的问题——从内存溢出异常到资源利用效率低下等各类状况。这些新功能使得Ray工作负载变得前所未有的透明可靠，优化工作也变得更加轻松高效。

## Building Fault-Tolerant Massive Ray Clusters on Anyscale | Ray Summit 2025

[https://www.youtube.com/watch?v=6OuAus_cOoo ](https://www.youtube.com/watch?v=6OuAus_cOoo%20)  
视频描述：在2025年Ray峰会上，Anyscale公司的Dhyey Shah与Ibrahim Rabbani分享了Ray如何通过工程化设计经受住大规模AI工作负载的严苛考验，以及如何在超过1万个节点的集群上稳定运行的实践之道。

演讲者首先阐述了极端规模下必然出现的挑战：网络波动、抢占式实例中断、硬件故障、资源争用以及不可预测的基础设施行为。他们解析了Ray分布式运行时如何优雅应对这些故障，在持续动荡中保持工作负载持续运行，并维持强大的可靠性。

随后，Dhyey和Ibrahim深入探讨了在超大规模环境下构建和运营Ray所获得的关键工程经验，包括容错策略、状态管理、恢复机制、弹性伸缩以及感知工作负载的调度方案。

最后他们展望了Ray的发展方向——重点介绍了为支撑下一代AI应用而即将推出的可扩展性、可靠性与性能优化方案。

无论您正在运行大规模模型训练、分布式推理、强化学习还是多模态流水线，本场分享都将带您深入探究：当其他系统纷纷崩溃时，Ray如何始终保持坚不可摧。

## How KubeRay Is Evolving for Massive AI Workloads  | Ray Summit 2025

[https://www.youtube.com/watch?v=NKUjSDkNmgQ](https://www.youtube.com/watch?v=NKUjSDkNmgQ)  
视频描述：在Ray Summit 2025大会上，来自谷歌的Aaron Liang和Anyscale的Jui-An Huang分享了KubeRay的最新进展，旨在显著提升团队在Kubernetes上运行Ray的用户体验。

他们介绍了一系列重大RayJob增强功能，旨在简化并强化端到端工作负载生命周期管理，包括：

- 可预测且可控的清理删除策略
- 支持周期性及自动化Ray工作负载的定时调度功能
- 便于与周边服务及工具集成的边车模式
- 提升可靠性并降低运维负担的后台状态检查机制

这些升级共同使得Kubernetes上的Ray任务编排对开发者和运维人员而言更加直观、易管理且稳定可靠。

参会者将通过实际案例深入了解这些新功能如何优化生产环境中的Ray工作负载流程，并洞察KubeRay如何持续演进，使大规模分布式计算变得比以往更加轻松便捷。

## Ray Data for Structured Workloads: Deep Dive | Ray Summit 2025

[https://www.youtube.com/watch?v=cQkZDs6V2zI  ](https://www.youtube.com/watch?v=cQkZDs6V2zI%20%20)  
原视频描述有误
