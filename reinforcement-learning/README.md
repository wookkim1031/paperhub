# Reinforcement Learning

Papers on policy optimization, model-based RL, exploration, and multi-agent systems.

[Back to index](../README.md)

---

## Papers

| Title | Authors | Year |
|-------|---------|------|
| [Proximal Policy Optimization Algorithms](#proximal-policy-optimization-algorithms) | Schulman et al. | 2017 |
| [Soft Actor-Critic](#soft-actor-critic-off-policy-maximum-entropy-deep-rl) | Haarnoja et al. | 2018 |
| [Decision Transformer](#decision-transformer-reinforcement-learning-via-sequence-modeling) | Chen et al. | 2021 |

---

### [Proximal Policy Optimization Algorithms](https://arxiv.org/abs/1707.06347)
**Authors:** Schulman et al. (OpenAI) · **Year:** 2017

**Summary:**
Proposes PPO, a policy gradient method that clips the surrogate objective to
prevent destructively large policy updates. Simpler than TRPO while achieving
comparable or better performance across a wide range of tasks.

**Key Ideas:**
- Clipped surrogate objective to constrain update size
- Multiple epochs of minibatch SGD per data collection round
- No second-order optimization needed (unlike TRPO)

**Relevance:** De facto standard baseline for on-policy deep RL.

---

### [Soft Actor-Critic: Off-Policy Maximum Entropy Deep RL](https://arxiv.org/abs/1801.01290)
**Authors:** Haarnoja et al. (UC Berkeley) · **Year:** 2018

**Summary:**
An off-policy actor-critic algorithm that maximizes a trade-off between
expected reward and entropy. The entropy term encourages exploration and
leads to more robust, sample-efficient policies in continuous action spaces.

**Key Ideas:**
- Maximum entropy objective: reward + temperature × entropy
- Off-policy updates for sample efficiency
- Automatic temperature tuning via dual gradient descent

**Relevance:** Go-to algorithm for continuous control; strong sample efficiency baseline.

---

### [Decision Transformer: Reinforcement Learning via Sequence Modeling](https://arxiv.org/abs/2106.01345)
**Authors:** Chen et al. · **Year:** 2021

**Summary:**
Casts offline RL as a sequence modeling problem. A GPT-style transformer is
conditioned on return-to-go, state, and action sequences, then trained with
supervised learning on offline data — no Bellman backups required.

**Key Ideas:**
- Return-conditioned autoregressive policy
- Offline RL without temporal difference learning
- Naturally handles sparse rewards via return-to-go tokens

**Relevance:** Bridges large language model architectures and sequential decision-making.

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
