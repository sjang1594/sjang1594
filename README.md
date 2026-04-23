### Hi there 👋

# Seungho Jang

**Computer Graphics · 3D Vision · GPU Systems Engineer**
> Bridging physically-grounded simulation and neural scene understanding — from sensor physics to rendering pipelines to real-time engines.

---

## About
Simulation software engineer with 4+ years of industry experience building real-time rendering engines, and synthetic data generation systems for autonomous driving perception. Alumni of **MORAI** and **Hyundai AutoEver**, where I shipped production-grade Vulkan/DX12 renderers and sensor simulation stacks used in AV development workflows.

Currently focused on the intersection of **GPU-accelerated rendering**, **neural scene representations**, and **sim-to-real robustness** — with ongoing CUDA portfolio work targeting deep learning infrastructure, novel view synthesis, and physically-based atmospheric simulation.

---

## Current Projects

### 🔧 Luna Engine
*Backend-agnostic real-time renderer — DirectX 12 / Vulkan*

A from-scratch rendering engine designed for portability across modern graphics APIs. Built with an eye toward open-source release as a lower-cost alternative to proprietary simulation environments (Isaac SIM, etc.).

- Explicit GPU memory management and resource barriers
- Render graph abstraction over DX12 and Vulkan backends
- Targeting extensibility for sensor simulation integration
---

### ⚡ CUDA Portfolio
Three parallel workstreams targeting distinct audiences:

| Project | Focus | Audience |
|---|---|---|
| **Custom Flash Attention** | Memory-efficient attention kernel, tiling + online softmax | DL systems / NVIDIA |
| **GPU Gaussian Splatting Rasterizer** | Forward rasterization + α-compositing, gradient flow through Gaussian params | Neural rendering / PhD research |

---
### 📡 Sensor Simulation

Prior and ongoing work across radar, LiDAR, and EO/IR modalities:

**FMCW Radar**
- MIMO Array beam pattern modeling
- Range-Doppler map generation
- End-to-end FMCW radar system design

**LiDAR**
- Motion distortion correction
- Realistic noise and return modeling
- Integration with ASAM OpenSCENARIO scenario runner

---

## Past Work

- **Scenario Runner** — ASAM OpenSCENARIO-based desktop simulation application; ported to Unreal Engine 5.3
- **Realistic Radar & LiDAR Sensor Simulation** — physics-grounded sensor modeling for synthetic data pipelines
- **GameEngineWDirectX11** — DirectX 11 game engine built for pedagogical clarity and API understanding [GameEngineWDirectX11](https://github.com/sjang1594/GameEngineWDirectX11)

---

## Research Interests
- **Neural scene representations** — 3D Gaussian Splatting, NeRF, neural radiance fields
- **Sim-to-real gap** — physically grounded synthetic data, domain randomization, sensor realism
- **3D reconstruction** — multi-view geometry, dense SLAM, point cloud processing
- **Robotics & embodied AI** — perception pipelines, VR/AR simulation environments
- **Diffusion models** — generative priors for scene understanding and data augmentation

---

## Currently Studying
- **Multiview Geometry in Computer Vision** — epipolar geometry, bundle adjustment, SfM
- **3DGS training pipeline mechanics** — gradient flow through Gaussian parameters, densification heuristics, custom CUDA rasterizer rationale

---

## Study Group

**3D Point Cloud Analysis Study Group** — reading group covering traditional, deep learning, and explainable ML methods for point cloud processing.

📖 *3D Point Cloud Analysis: Traditional, Deep Learning, and Explainable Machine Learning Methods*
▶ [YouTube]([YouTube](https://www.youtube.com/watch?v=hgBlCaCIV10&list=PLubUquiqNQdN83-fPBzzViEEqohpdlwk2&index=5))

---

## Tech Stack

**Graphics APIs** — Vulkan · DirectX 12 · DirectX 11 · OpenGL  
**GPU / Compute** — CUDA · compute shaders · custom kernel development  
**Simulation** — Unreal Engine 5 · Isaac SIM · ASAM OpenSCENARIO  
**Languages** — C++ · Python · HLSL · GLSL  
**ML / Vision** — PyTorch · 3DGS · NeRF · diffusion models  
**Sensor domains** — EO/IR · FMCW Radar · LiDAR  

---

## Contact

Feel free to reach out regarding graphics engineering, sensor simulation, neural rendering research, or collaboration on open-source GPU projects.

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=sjang1594)](https://github.com/sjang1594/github-readme-stats)

<div align=center>
  
[![Personal Blog Badge](http://img.shields.io/badge/-Tech%20blog-black?style=flat-square&logo=github&link=https://sjang1594.github.io/)](https://sjang1594.github.io/)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://https:www.linkedin.com/in/seungho-jang-41b3b9145/)](https://www.linkedin.com/in/seungho-jang-41b3b9145/) 
[![Gmail Badge](https://img.shields.io/badge/-Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=mailto:snugyun01@gmail.com)](mailto:sjang1594@gmail.com)
[![Facebook Badge](https://img.shields.io/badge/facebook-1877f2?style=flat-square&logo=facebook&logoColor=white&link=https://www.facebook.com/sjang1594)](https://www.facebook.com/sjang1594)

</div>
