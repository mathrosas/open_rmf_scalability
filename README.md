# Open-RMF Scalability Experiment

## Overview

This project investigates the scalability of Open-RMF using
the official Airport Terminal simulation environment.

The experiment evaluates multi-fleet coordination, task
execution, traffic management, and computational performance
as the number of simulated robots increases.

## Objectives

- Establish a reproducible official simulation baseline.
- Investigate Open-RMF multi-fleet coordination.
- Evaluate performance as robot count increases.
- Identify scheduling, communication, and simulation bottlenecks.
- Distinguish Open-RMF limitations from Gazebo and hardware limitations.
- Develop reproducible experimental methods.

## Technology Stack

| Component | Technology |
|-----------|------------|
| Operating system | Ubuntu 24.04 LTS |
| Robotics middleware | ROS 2 Jazzy |
| Simulator | Gazebo Harmonic |
| Fleet coordination | Open-RMF |
| Simulation environment | RMF Demos - Airport Terminal |
| Containerization | Docker and Docker Compose |
| Development | VS Code |
| Version control | Git and GitHub |

## Experimental Hardware

| Component | Specification |
|-----------|---------------|
| CPU | AMD Ryzen 5 7600 |
| GPU | NVIDIA RTX 3060 12 GB |
| RAM | 32 GB DDR5 5600 |
| Storage | 1 TB NVMe SSD |
| Architecture | x86_64 |

## Proposed Experimental Scenarios

| Scenario | Autonomous robots |
|----------|-------------------|
| Baseline | 10 |
| Experiment 1 | 11 |
| Experiment 2 | 12 |
| Experiment 3 | 15 |
| Experiment 4 | 20 |

## Official Baseline

The official Airport Terminal configuration contains four
controllable robot fleets.

| Fleet | Robot count |
|-------|-------------|
| tinyRobot | 4 |
| deliveryRobot | 3 |
| cleanerBotA | 1 |
| cleanerBotE | 2 |
| Total | 10 |

## Experimental Principles

- Preserve the official navigation architecture.
- Establish a validated baseline before making modifications.
- Introduce changes incrementally.
- Control experimental variables.
- Use repeatable workloads.
- Document software versions and configurations.
- Distinguish measured results from inferred conclusions.

## Project Status

Under development.

## References

- [Open-RMF](https://github.com/open-rmf/rmf)
- [RMF Demos](https://github.com/open-rmf/rmf_demos)
- [ROS 2 Jazzy](https://docs.ros.org/en/jazzy/)
- [Gazebo Harmonic](https://gazebosim.org/docs/harmonic/)