# AI Infrastructure & GPU Inference Experiments

## Overview

Alongside application-level AI projects, I have experimented with the infrastructure side of generative AI: provisioning cloud GPU environments, configuring storage, loading workflows, troubleshooting model/runtime compatibility, and monitoring inference workloads.

## Environment

The private technical archive includes work with:

- RunPod GPU pods,
- RTX Pro-class GPUs,
- persistent/network volumes,
- ComfyUI,
- Wan 2.x image/video workflows,
- CLIP Vision nodes,
- environment variables and model downloads,
- VRAM/GPU utilization monitoring,
- file-browser tooling,
- and CUDA/template compatibility checks.

## Typical workflow

1. select a GPU based on VRAM, cost, and availability,
2. attach persistent/network storage,
3. deploy a compatible template,
4. configure model/runtime variables,
5. load or modify a ComfyUI workflow,
6. resolve missing-node/model/CUDA issues,
7. monitor VRAM and GPU utilization,
8. run inference and inspect outputs.

## Examples of issues handled

The archive includes troubleshooting around:

- CUDA-version mismatch warnings,
- storage persistence,
- model/component availability,
- CLIP Vision wiring,
- queued/running ComfyUI jobs,
- server/file-browser access,
- and high-VRAM inference workloads.

## Scope

This is **deployment and inference experimentation**, not a claim that I trained the underlying foundation models.

## What this demonstrates

**cloud GPU deployment · AI tooling · inference workflows · technical troubleshooting · ComfyUI · RunPod · model/runtime compatibility · practical experimentation**
