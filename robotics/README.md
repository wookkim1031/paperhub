# Robotics

Papers on robot learning, motion planning, manipulation, and locomotion.

[Back to index](../README.md)

---

## Papers

### [Learning Dexterous In-Hand Manipulation](https://arxiv.org/abs/1808.00177)
**Authors:** OpenAI, Andrychowicz et al. · **Year:** 2019

**Summary:**
Trains a simulated robot hand to solve a Rubik's cube using reinforcement learning
with domain randomization. The policy trained purely in simulation transfers to a
real robot hand without any real-world training data.

**Key Ideas:**
- Automatic Domain Randomization (ADR) to bridge sim-to-real gap
- LSTM policy to handle partial observability and varying dynamics
- Reward shaping for long-horizon dexterous tasks

**Relevance:** Foundational work on sim-to-real transfer for dexterous manipulation.

---

### [RT-2: Vision-Language-Action Models](https://arxiv.org/abs/2307.15818)
**Authors:** Brohan et al. (Google DeepMind) · **Year:** 2023

**Summary:**
Fine-tunes a large vision-language model (VLM) to directly output robot actions
as tokens. Inherits emergent reasoning abilities from web-scale pretraining,
enabling robots to follow novel instructions and generalize to unseen objects.

**Key Ideas:**
- Represents robot actions as text tokens
- Co-fine-tunes on robot data + web data jointly
- Chain-of-thought reasoning transfers from language to robot tasks

**Relevance:** Shows that internet-scale pretraining can bootstrap robot generalization.

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
