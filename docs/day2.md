# Day 2 

On day 2 there are two separate modules.  In the morning we will be discussing the module system, which it is required and how it is used to select the software you require.  In the afternoon, we will be discussing how to actually run jobs on a NAISS system, using the job scheduler.   As part of the afternoon module we also discuss the basic architecture of a typical HPC cluster.

- **Date**: 
- **Time**: 9:00 - 11:30 and 13:00 - 16:00 

## Selecting software modules 

**Time**: 9:00 - 11:30 

The course will show you how to find and access your require software on NAISS systems.  For NAISS systems, utilised by several hundret users simultanously, organising software in a module system is essential.  This ensures that every user can get access to their required software, including the desired version.  The module system also ensures that there are no conflicts between the software titles and the software requirements of other users.  

While the modules may be somewhat differently named on the individual systems, the procedure and commands are the same. 

### Prerequisites 

- Basic knowledge of Linux, like in the "Linux Command Line 101" module

### Topics 

- What is the module system?
- Why do I want to use the module system?
- What happens when I load/unload modules?
    - paths
    - environment variables
    - more?
- Useful commands
- Load examples
- Compiler toolchains

!!! note 

    Link to the course material: <a href="https://hpc2n.github.io/selecting-modules/" target="_blank">Selecting software modules</a>. 

## Running jobs on clusters 

**Time**: 13:00 - 16:00 

This module explains key features of a contemporary HPC cluster, such as deployed within NAISS and a number of Swedish universities.  It will explain the principles behind the job scheduler and how the scheduler can be used to accomplish your computational work in an efficient manner.  The examples will utilise the SLURM scheduler, which is deployed on the NAISS resources and many university resources.

The module is organised as an online event.  The event addresses users who have recently started using HPC systems and prospective users considering using an HPC system in the near future. 

### Prerequisites 

- An account at an HPC centre
   - If you do not have an account, you can still listen to the presentations.
- Knowledge of logging in to your chosen HPC centre (Like in the "Connecting and File transfers" module for instance) 
   - We have listed login info for several Swedish HPC centres
- Very basic Linux knowledge
   - You can find the material and recordings from the most recent NAISS Linux introduction course here: <a href="https://hpc2n.github.io/linux-command-line-101/" target="_blank">Linux intro material</a> and <a href="https://youtube.com/playlist?list=PL6jMHLEmPVLxLh5h2JTe6fFZ0rJx0uO1a&si=Ui_6y24Odaez_drt" target="_blank">Recordings from the Linux intro course</a>
- Basic knowledge about the software modules system used at the NAISS centres
   - You can find the material and the recordings from the most recent NAISS selecting software modules course here: <a href="https://hpc2n.github.io/selecting-modules/" target="_blank">Selecting software modules</a> and <a href="https://youtube.com/playlist?list=PL6jMHLEmPVLwHWwa0Wg1dq_nkKTFLnp7_&si=3NLCsp6cdJp3E3IC" target="_blank">Recordings from the Selecting software modules course</a>

### Topics 

- Cluster architecture
- sbatch options for CPU job scripts
- Writing submission scripts for:
    - I/O intensive jobs
    - OpenMP and MPI jobs
    - Job arrays and simple task farms
    - Jobs with more memory per task
- Running jobs on GPUs
- Monitoring jobs and their efficiency

!!! note 

    Link to the course material: <a href="https://uppmax.github.io/NAISS_Slurm/" target="_blank">Running jobs on clusters</a> 

