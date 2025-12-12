# Running AI/ML workloads on NAISS systems 

**Time**: 9:00 - 12:00

This session will introduce you to what is different when doing machine
learning on a compute cluster. Performance considerations and best practices.

Code examples will focus on PyTorch and TensorFlow as framework, but also other
utilities.

The main relevant NAISS resources is Alvis this first time and later Arrhenius
GPU partition when that is in place.

!!! note

    Click the Home (at the top) to see the date.

## Prerequisites

To be able to follow along you should have a basic understanding of machine
learning and know how to:

- [Connect](connecting.md) to an HPC cluster
- Use software on an HPC cluster with [modules](modules.md) and/or Apptainer containers
- [Run jobs on a cluster](slurm.md)
- Program in Python

### Topics
!!! note
    These topics are currently preliminary and may be subject to change.

<!-- At some point cover the specifics for Alvis: -->
<!--    - C3SE_quota, where-are-my-files -->
<!--    - job-killing -->
<!--    - job_stats.py -->
- How you run on GPUs with PyTorch and TensorFlow
<!--    - Software recap -->
<!--    - SLURM recap and allocating GPUs on NAISS SLURM clusters -->
<!--    - Basic checkpointing for long running jobs (Do I want PyTorch lightning?) -->
- Floating point precision and GPU performance
<!--    - Explain GPU-parallelism -->
<!--    - Table for NVIDIA GPUs on all NAISS systems (optionally AMD table for Dardel) -->
<!--    - Mixed precision and how to select precision in PyTorch and TensorFlow -->
<!--    - GPU monitoring (nvtop, job_stats.py (Alvis only)) -->
- Performance considerations for data loading on parallel filesystems
<!--    - Explain parallel filesystems or at least talk about FileIO -->
<!--    - What to show? Arrow, Zip -->
- Profiling your ML workload
<!--    - Print statements with timestamps? -->
<!--    - Figure out how PyTorchs new replacement work and get something useful from that -->
<!--    - TensorFlow + TensorBoard -->
<!--    - Scalene? Others? -->
- Multi-GPU parallelism
    - Conceptual overview
    - Data Parallellism
    - Fully Sharded Data Parallel
    - Basic LLM inference with model parallelism
<!--- Basics on HTC and random parameter search with job-arrays if time permits -->
