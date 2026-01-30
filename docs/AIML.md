# Running AI/ML workloads on NAISS systems 

**Time**: 9:00 - 12:00

This session will introduce you to what is different when doing machine
learning on a compute cluster. Performance considerations and best practices.

Code examples will focus on PyTorch and TensorFlow as frameworks, but also other
utilities.

The main relevant NAISS resources is Alvis this first time and later Arrhenius
GPU partition when that is in place.

!!! note

    Click the Home (at the top) to see the date.

## Prerequisites

To be able to follow along you should have a basic understanding of machine
learning and know how to:

- [Connect](connecting.md) to an HPC cluster
- Use software on an HPC cluster with [modules](modules.md) and Apptainer containers
- [Run jobs on a cluster](slurm.md)
- Code in Python (preferably also PyTorch or TensorFlow)

## Topics

- Intro to NAISS AI/ML resources
- Running PyTorch and TensorFlow on GPUs
- Performance considerations
  - Mixed precision and GPUs
  - Filesystem performance
  - Profiling
- Multi-GPU parallelism
  - Task Parallelism
  - Data Parallelism
  - Flavours of Model Parallelism
- Very Brief Intro to LLM Inference

!!! note
    Link to the course material: [Running AI/ML Workloads on NAISS Systems](https://naiss-training.github.io/ai-intro/)
