# HPC Distributed Systems Labs

This repository gathers a set of practical reports completed during my M2 High Performance Computing studies.  
The work focuses on distributed computing environments, MPI communication, SLURM job scheduling, Docker-based clusters, monitoring, XMP/OpenMP parallelism, and performance analysis.

The goal of this repository is to showcase hands-on experience with HPC infrastructure and distributed execution environments.

## Contents

| Report | Topic | Main Skills |
|---|---|---|
| [TP1 - MPI, Docker Swarm and OSU Benchmarks](./reports/TP1_MPI_Docker_Swarm_OSU_Benchmarks.pdf) | Deployment of an MPI environment using Docker Swarm, validation with C/Python MPI programs, and OSU communication benchmarks | MPI, Docker Swarm, OpenMPI, OSU Micro-Benchmarks, latency, bandwidth |
| [TP2 - ANSSI Sensitive System Architecture](./reports/TP2_ANSSI_Sensitive_System_Architecture.pdf) | PlantUML architecture based on ANSSI recommendations for sensitive systems | Security architecture, PlantUML, technical documentation |
| [TP3 - SLURM, Docker, MPI and Telemetry](./reports/TP3_SLURM_Docker_MPI_Telemetry.pdf) | Docker Compose mini-cluster with SLURM, MPI job execution, and telemetry using StatsD, InfluxDB and Chronograf | SLURM, Docker Compose, MPI, monitoring, telemetry |
| [TP4 - XMP, SLURM and OpenMP Comparison](./reports/TP4_XMP_SLURM_OpenMP_Comparison.pdf) | Distributed histogram computation using XcalableMP on a SLURM mini-cluster, compared with OpenMP | XMP, MPI, SLURM, OpenMP, scalability analysis |
| [TP5 - Project Cost Estimation](./reports/TP5_Project_Cost_Estimation.pdf) | Software project cost estimation based on functional scope, LOC, workload, planning and margin | Software engineering, estimation, planning |

## Topics Covered

- MPI execution across Docker containers
- Docker Swarm and Docker Compose environments
- SLURM job scheduling and multi-node execution
- OSU Micro-Benchmarks for latency and bandwidth evaluation
- XcalableMP distributed programming
- OpenMP shared-memory parallelism
- Distributed vs shared-memory performance comparison
- Monitoring with StatsD, InfluxDB and Chronograf
- PlantUML and C4-style architecture documentation
- Software project estimation and planning

## Highlights

### MPI and Communication Benchmarks

The first report validates a distributed MPI environment using Docker Swarm. It includes MPI tests in C and Python, process mapping across containers, and OSU Micro-Benchmarks for communication latency and bidirectional bandwidth.

### SLURM Mini-Cluster and Telemetry

The third report presents a Docker Compose mini-cluster with a SLURM controller and multiple compute nodes. It demonstrates job submission with `sbatch` and `srun`, MPI execution across allocated nodes, and telemetry visualization with StatsD, InfluxDB and Chronograf.

### XMP and OpenMP Performance Comparison

The fourth report compares a distributed XMP/MPI implementation with an OpenMP shared-memory version for histogram computation. It includes correctness validation, reduction, timing, scalability analysis and interpretation of overheads.

### Architecture and Software Engineering

The repository also includes architecture modeling using PlantUML and a project cost estimation report, showing technical documentation and software engineering methodology.

## Skills Demonstrated

- HPC environment setup
- Distributed computing
- MPI programming and execution
- SLURM job scheduling
- Docker-based cluster deployment
- Performance benchmarking
- Latency and bandwidth analysis
- Parallel programming with XMP and OpenMP
- Monitoring and telemetry
- Technical reporting
- Architecture modeling
- Software project estimation

## Repository Structure

```text
.
├── README.md
└── reports/
    ├── TP1_MPI_Docker_Swarm_OSU_Benchmarks.pdf
    ├── TP2_ANSSI_Sensitive_System_Architecture.pdf
    ├── TP3_SLURM_Docker_MPI_Telemetry.pdf
    ├── TP4_XMP_SLURM_OpenMP_Comparison.pdf
    └── TP5_Project_Cost_Estimation.pdf
