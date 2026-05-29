---
permalink: /projects/
title: "Projects"
excerpt: "Selected Projects"
author_profile: false
---

# 🚀 Projects

Here are some of my selected projects. More details coming soon!

## AgentGuard: Access Control Framework for LLM Agents (Primary Contributor)

<a href="https://github.com/WhitzardAgent/AgentGuard" class="project-link github-link" target="_blank">🔗GitHub</a> | <a href="https://arxiv.org/pdf/2605.28071" class="project-link paper-link" target="_blank">📄Paper</a>

*2026*

AgentGuard is an attribute-based access control (ABAC) framework designed specifically for tool-use LLM-based agents. As autonomous agents increasingly interact with external tools and APIs, ensuring secure and fine-grained permission management becomes critical. AgentGuard dynamically evaluates agent identities, tool requirements, and environmental contexts to enforce strict access policies. It effectively mitigates security risks such as unauthorized tool execution, privilege escalation, and sensitive data leakage, providing a robust, plug-and-play security layer for modern agentic workflows.

**Technologies**: Python, LLM Agents, Attribute-Based Access Control (ABAC), AI Security

## xLLM: High-Performance LLM Inference Framework (Contributor)

*2025*

A more efficient large language model inference framework that outperforms vLLM and SGLang on latency and throughput under the same hardware budget. Focused on optimized attention scheduling, paged KV cache management, and heterogeneous pipeline parallelism. Interestingly, to tackle deployment constraints on H20 and 4090D GPUs(God knows what happened), we further integrated [TeraPipe](https://proceedings.mlr.press/v139/li21y/li21y.pdf) for token-level batch splitting during the prefilling stage, enabling fine-grained parallelization across heterogeneous SM clusters. Moreover, leveraging Ray Plasma for decoding-phase shared-memory optimization significantly reduced inter-process communication overhead, improving multi-instance GPU utilization and inference stability under high concurrency.

Deployed internally at ByteDance to serve commercial workloads (not open-sourced，😞).

**Technologies**: C++, Python, CUDA, Ray

## Ark Simulation Inference System

*2025*

A modular simulation engine for multi-scenario inference (three-graph, dual-graph, and PD-separation pipelines) used for fault injection and resilience testing of production systems. Enhanced online model registration, health probing, and zero-downtime deployment via K8s HPA and custom metrics. 

Deployed internally at ByteDance to serve commercial workloads (not open-sourced, 😞).

**Technologies**: Kubernetes, gRPC, Python, Go, Ray

## Instaworld

<a href="https://github.com/alexps9/InstaWorld" class="project-link github-link" target="_blank">🔗GitHub</a>

*2024*

Built a procedural content generation (PCG) toolchain in Unreal Engine 5 to rapidly assemble 3D game scenes. Integrated LLMs for text-driven scene planning and vector retrieval to search and select suitable assets (meshes/materials/props) from an asset library, enabling fast scene prototyping and iterative refinement.

**Technologies**: Unreal Engine 5, Python, PCG, LLMs, Vector Retrieval (Embeddings)



*More projects will be added soon!*
