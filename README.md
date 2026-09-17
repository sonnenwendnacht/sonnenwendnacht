# Junzhe Zong

Selected research and course projects in language modeling, computer vision,
decision-making under uncertainty, and systems. Each project links to runnable
examples, tests, and evaluation records.

Main tools used here: Python, PyTorch, scikit-learn, XGBoost, NumPy, and NetworkX.

## Machine learning and AI

| Project | What it demonstrates |
| --- | --- |
| [Causal Transformer experiments](https://github.com/sonnenwendnacht/applied_ml_a3_transformers) | PyTorch language modeling and train-only byte-pair tokenization. [Three-seed evaluation](https://github.com/sonnenwendnacht/applied_ml_a3_transformers#recorded-follow-up-results). |
| [Hierarchical image classification](https://github.com/sonnenwendnacht/hierarchical-image-classification) | My `model2` contribution to a team project: ResNet18 with superclass gating and subclass experts. [Held-out evaluation and exact-pixel grouping](https://github.com/sonnenwendnacht/hierarchical-image-classification#recorded-held-out-evaluation). |
| [Cost-aware multi-armed bandits](https://github.com/sonnenwendnacht/research_multi_arm_bandit) | Student research on action costs and fixed quality thresholds. [Paired synthetic comparisons](https://github.com/sonnenwendnacht/research_multi_arm_bandit#recorded-demonstration) and separate tuning/evaluation seeds. |
| [XGBoost vs. MLP](https://github.com/sonnenwendnacht/applied_ml_a2_trees_to_nns) | Imbalanced classification with preprocessing fitted inside CV folds. [Repeated-seed training-budget study](https://github.com/sonnenwendnacht/applied_ml_a2_trees_to_nns#repeated-seed-training-budget-study). |

## Algorithms and systems

| Project | What it demonstrates |
| --- | --- |
| [Contraction hierarchy routing](https://github.com/sonnenwendnacht/contraction-hierarchy-routing) | Collaborative shortest-path project. [Preprocessing/query tradeoffs](https://github.com/sonnenwendnacht/contraction-hierarchy-routing/blob/main/docs/RESULTS.md) and independent distance-oracle checks. |
| [Reliable UDP transport](https://github.com/sonnenwendnacht/reliable-udp-transport) | Go-Back-N retransmission and flow control. [Deterministic fault and connection-lifecycle tests](https://github.com/sonnenwendnacht/reliable-udp-transport#validation) for the maintained coursework implementation. |

Each repository distinguishes the original work from September 2026 AI-assisted
maintenance and validation. Team contributions are credited; measured results
include their evaluation scope and limitations.
