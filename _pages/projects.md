---
permalink: /projects/
title: "Projects"
excerpt: "Selected Projects"
author_profile: false
---

# 🚀 Projects

Here are some of my selected projects. More details coming soon!

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

## APSFuzz (Contributor)

<a href="https://github.com/JSGforever/APSFuzz" class="project-link github-link" target="_blank">🔗GitHub</a>

*2024*

Developed a fuzzing-based framework to automatically discover critical parking scenarios for autonomous parking systems. Extended the simulator with custom UE5 parking maps (diverse layouts, obstacles, and boundary conditions) to increase scenario coverage and enable systematic stress-testing of planning and control under safety-critical corner cases.

**Technologies**: Fuzzing, Unreal Engine 5, Python, Carla



*More projects will be added soon!*
