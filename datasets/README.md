# Datasets

Papers introducing benchmark datasets, data collection pipelines, and evaluation protocols.

[Back to index](../README.md)

---

## Papers

### [Open X-Embodiment: Robotic Learning Datasets and RT-X Models](https://arxiv.org/abs/2310.08864)
**Authors:** Open X-Embodiment Collaboration · **Year:** 2023

**Summary:**
Aggregates robot demonstration data from 22 different robot embodiments across
21 institutions into a single large dataset. Training on this diverse data
(RT-X) significantly improves generalization over single-robot datasets.

**Key Ideas:**
- 1M+ real-robot trajectories across arms, quadrupeds, mobile manipulators
- Standardized data format (RLDS) for cross-embodiment training
- Shows positive transfer across embodiments and tasks

**Relevance:** Largest open robotic manipulation dataset; key reference for generalist robot policies.

---

### [D4RL: Datasets for Deep Data-Driven Reinforcement Learning](https://arxiv.org/abs/2004.07219)
**Authors:** Fu et al. (UC Berkeley) · **Year:** 2020

**Summary:**
Introduces a standardized benchmark suite for offline RL, providing datasets of
varying quality (random, medium, expert) for locomotion, navigation, and
manipulation tasks. Aims to make offline RL research reproducible and comparable.

**Key Ideas:**
- Datasets collected with random, medium, and expert policies
- Coverage of MuJoCo locomotion, AntMaze navigation, Adroit hand manipulation
- Widely adopted as the standard offline RL benchmark

**Relevance:** Essential reference for any offline RL or imitation learning work.

---

<!-- Add new papers above this line using the template below

### [Paper Title](link)
**Authors:** Author et al. · **Year:** YYYY

**Summary:**
One to three sentences explaining what the paper does and why it matters.

**Key Ideas:**
- Point 1
- Point 2
- Point 3

**Relevance:** Why you read this / how it connects to your work.

---
-->
