# Defense

This page collects papers on defense, mitigation, and control mechanisms for resource consumption risks in large-model systems.

## Included Scope

- Abuse prevention
- Resource isolation and admission control
- Cost-aware inference control
- Monitoring, throttling, and scheduling defenses

## Paper List

| Published | First Author Institution | Venue | Title | Keywords |
|:--|:--|:--|:--|:--|
| 2026-04 | University of Maryland | arXiv | [Early Stopping for Large Reasoning Models via Confidence Dynamics](https://arxiv.org/abs/2604.04930) | RLLM & Overthinking & Early Stopping & Confidence Dynamics |
| 2026-02 | King Abdullah University of Science and Technology | arXiv | [PACE: Prefix-Protected and Difficulty-Aware Compression for Efficient Reasoning](https://arxiv.org/abs/2602.11639) | RLLM & Overthinking & Prefix Protection & Difficulty-Aware Compression |
| 2026-01 | University of Moratuwa | arXiv | [SHIELD: An Auto-Healing Agentic Defense Framework for LLM Resource Exhaustion Attacks](https://arxiv.org/abs/2601.19174) | Agent & Unbounded Drift & Auto-Healing Defense & Resource Monitoring |
| 2026-01 | Chung-Ang University | arXiv | [Mitigating Cognitive Inertia in Large Reasoning Models via Latent Spike Steering](https://arxiv.org/abs/2601.22484) | RLLM & Overthinking & Latent Spike Steering & Cognitive Inertia |
| 2025-11 | Beijing University of Posts and Telecommunications | Findings of EMNLP 2025 | [PD3F: A Pluggable and Dynamic DoS-Defense Framework Against Resource Consumption Attacks Targeting Large Language Models](https://aclanthology.org/2025.findings-emnlp.195/) | LLM & Unbounded Drift & DoS Defense & Adaptive Suppression |
| 2025-10 | The University of Hong Kong | arXiv | [Breaking the Loop: Detecting and Mitigating Denial-of-Service Vulnerabilities in Large Language Models](https://arxiv.org/abs/2510.01157) | LLM & Unbounded Drift & DoS Mitigation & Loop Detection |
| 2025-09 | Independent Researcher | arXiv | [MeVe: A Modular System for Memory Verification and Effective Context Control in Language Models](https://arxiv.org/abs/2509.01514) | LLM & Unbounded Drift & Memory Verification & Context Control |
| 2025-09 | Tsinghua University | NeurIPS 2025 | [Mitigating Overthinking in Large Reasoning Models via Manifold Steering](https://arxiv.org/abs/2505.22411) | RLLM & Overthinking & Manifold Steering & Mechanistic Interpretability |
| 2025-08 | Peking University | arXiv | [Efficient reasoning for large reasoning language models via certainty-guided reflection suppression](https://arxiv.org/abs/2508.05337) | RLLM & Overthinking & Reflection Suppression & Certainty Guidance |
| 2025-07 | Zhejiang University | arXiv | [LAPO: Internalizing Reasoning Efficiency via Length-Adaptive Policy Optimization](https://arxiv.org/abs/2507.15758) | RLLM & Overthinking & Policy Optimization & Length Adaptation |
| 2025-07 | Fudan University | ACL 2025 | [CoT-Valve: Length-Compressible Chain-of-Thought Tuning](https://aclanthology.org/2025.acl-long.334/) | RLLM & Overthinking & CoT Compression & Efficient Tuning |
| 2025-06 | National University of Singapore | arXiv | [SafeChain: Safety of Language Models with Long Chain-of-Thought Reasoning Capabilities](https://arxiv.org/abs/2506.12345) | RLLM & Overthinking & Safe Reasoning & Long CoT |
| 2025-06 | University of Waterloo | arXiv | [Concise Thoughts: Impact of Output Length on LLM Reasoning and Cost](https://arxiv.org/abs/2506.02167) | RLLM & Overthinking & Output Length & Cost Control |
| 2025-05 | Tianjin University | Preprint | [NMRet: A Memory-Augmented Retrieval Framework for Large Language Models](https://sentic.net/memory-augmented-retrieval-for-large-language-models.pdf) | LLM & Unbounded Drift & Memory-Augmented Retrieval & Context Compression |
| 2025-03 | Nanyang Technological University | arXiv | [Prolonged Reasoning Is Not All You Need: Certainty-Based Adaptive Routing for Efficient LLM/MLLM Reasoning](https://arxiv.org/abs/2503.09462) | RLLM & Overthinking & Adaptive Routing & Certainty Guidance |
| 2025-03 | National University of Singapore | arXiv | [Response Length Perception and Sequence Scheduling: An LLM-Empowered LLM Inference Pipeline](https://arxiv.org/abs/2503.18779) | LLM & Overthinking & Sequence Scheduling & Inference Pipeline |
| 2025-02 | The Chinese University of Hong Kong, Shenzhen | arXiv | [To Think or Not to Think: Exploring the Unthinking Vulnerability in Large Reasoning Models](https://arxiv.org/abs/2502.12202) | RLLM & Unbounded Drift & Delimiter Tokens & Thought Monitoring |
| 2025-02 | Chinese Academy of Sciences | arXiv | [Understanding and Controlling Repetition Neurons and Induction Heads in In-Context Learning](https://arxiv.org/abs/2502.17480) | LLM & Unbounded Drift & Repetition Control & Induction Heads |
| 2025-02 | Google DeepMind | arXiv | [Learning to Ponder: Adaptive Reasoning in Latent Space](https://arxiv.org/abs/2502.17416) | RLLM & Overthinking & Latent Space & Adaptive Reasoning |
| 2025-01 | Shanghai AI Laboratory | arXiv | [Controlling Thinking Speed in Reasoning Models](https://arxiv.org/abs/2501.19388) | RLLM & Overthinking & Thinking Speed & Inference Control |
| 2024-12 | Monash University | arXiv | [Sponge Attacks on Sensing AI: Energy-Latency Vulnerabilities and Defense via Model Pruning](https://arxiv.org/abs/2412.07445) | Vision ML & Unbounded Drift & Model Pruning & Sponge Defense |
| 2024-12 | Nanjing University | arXiv | [Token-Budget-Aware LLM Reasoning](https://arxiv.org/abs/2412.18547) | RLLM & Overthinking & Token Budget & Reasoning Control |
| 2024-11 | Beijing Institute of Technology | ACL 2025 Findings | [Make Every Penny Count: Difficulty-Adaptive Self-Consistency for Cost-Efficient Reasoning](https://aclanthology.org/2025.findings-acl.153/) | RLLM & Overthinking & Adaptive Self-Consistency & Cost-Efficient Reasoning |
| 2024-10 | Microsoft Research | EMNLP 2024 | [Learning to Break the Loop: Analyzing and Mitigating Repetitions for Neural Text Generation](https://aclanthology.org/2024.emnlp-main.287/) | LLM & Unbounded Drift & Repetition Mitigation & Decoding Control |
| 2024-10 | Google DeepMind | arXiv | [Enhancing Latent Computation in Transformers with Latent Tokens](https://arxiv.org/abs/2410.23658) | LLM & Overthinking & Latent Tokens & Efficient Reasoning |
| 2024-09 | Nanjing University | arXiv | [Mitigating the Language Mismatch and Repetition Issues in LLM-based Machine Translation via Model Editing](https://arxiv.org/abs/2409.19791) | Translation LLM & Unbounded Drift & Model Editing & Repetition Mitigation |
| 2023-10 | Microsoft Research | ICML 2024 | [Guiding Language Model Reasoning with Planning Tokens](https://arxiv.org/abs/2310.05707) | LLM & Overthinking & Planning Tokens & Reasoning Guidance |
| 2021-06 | Nanyang Technological University | ICML 2021 | [Straight to the Gradient: Learning to Use Novel Tokens for Neural Text Generation](https://proceedings.mlr.press/v139/lin21b.html) | LLM & Unbounded Drift & ScaleGrad & Novel Tokens |
| 2019-10 | Facebook AI Research | ICLR 2020 | [Neural Text Generation with Unlikelihood Training](https://arxiv.org/abs/1908.04319) | LLM & Unbounded Drift & Unlikelihood Training & Degeneration Mitigation |

## Backlinks

- [Topic Index](../README.md)
- [Project Entry](../../README.md)
