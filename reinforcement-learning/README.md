# Reinforcement Learning

[Back to index](../README.md)

| Paper | Summary |
|-------|---------|
| [Proximal Policy Optimization Algorithms](https://arxiv.org/abs/1707.06347) | Clips the surrogate objective to prevent large policy updates. Simpler than TRPO while achieving comparable or better performance — the de facto standard on-policy RL baseline. |
| [Soft Actor-Critic](https://arxiv.org/abs/1801.01290) | Off-policy actor-critic that maximizes both reward and entropy. The entropy term encourages exploration and leads to more robust, sample-efficient policies in continuous action spaces. |
| [Decision Transformer](https://arxiv.org/abs/2106.01345) | Casts offline RL as sequence modeling. A GPT-style transformer conditioned on return-to-go, state, and actions is trained with supervised learning — no Bellman backups needed. |
