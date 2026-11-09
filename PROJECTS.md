# Project guide

Pick a question, then read the evidence before you run anything. Each project links to the document that makes its main comparison.

| Interest | Start with | Read first |
|---|---|---|
| AI evaluation and LLM judges | [Petri judge stability](https://github.com/Thom-320/petri-judge-stability) | [Pilot findings](https://github.com/Thom-320/petri-judge-stability#what-the-pilot-found-and-why-it-is-weak-evidence) · [Pre-registration draft](https://github.com/Thom-320/petri-judge-stability/blob/main/docs/PREREGISTRATION.md) |
| Measurement validity of AI benchmarks | [METR horizon anchors](https://github.com/Thom-320/metr-horizon-anchors) | [Pilot memo](https://github.com/Thom-320/metr-horizon-anchors/blob/main/PILOT-MEMO.md) · [Anchor-split figure](https://github.com/Thom-320/metr-horizon-anchors/blob/main/figures/fig2_anchor_split.png) |
| RL and policy evaluation | [SCRES](https://github.com/Thom-320/scres-ia) | [Same-contract verdict](https://github.com/Thom-320/scres-ia/blob/main/docs/TRACK_B_SAME_CONTRACT_CHALLENGE_VERDICT_2026-07-10.md) · [Program Q status](https://github.com/Thom-320/scres-ia/blob/main/docs/PROGRAM_Q_CANONICAL_EVIDENCE_STATUS_2026-08-25.md) |
| Computational neuroscience and experimental controls | [Motor-RNN connectivity](https://github.com/Thom-320/nma-motor-rnn-connectivity) | [Equal-plasticity control](https://github.com/Thom-320/nma-motor-rnn-connectivity/blob/main/docs/EQUAL_PLASTICITY_CONTROL.md) · [Robustness note (16 seeds)](https://github.com/Thom-320/nma-motor-rnn-connectivity/blob/robustness-2026-10/paper/NOTE.md) |
| Representations of human coordination | [Spectral cognitive labor](https://github.com/Thom-320/spectral-cognitive-labor) | [Temporal audit](https://github.com/Thom-320/spectral-cognitive-labor/blob/main/docs/TEMPORAL_REPAIR.md) |
| Data engineering and interpretable review | [ContratIA Abierta](https://github.com/Thom-320/secop-risk-alerts-co) | [Model card](https://github.com/Thom-320/secop-risk-alerts-co/blob/main/docs/model-card.md) · [Validation scope](https://github.com/Thom-320/secop-risk-alerts-co/blob/main/docs/validation-summary.md) |
| Systems programming | [HeliOS](https://github.com/Thom-320/HeliOS) | [Architecture](https://github.com/Thom-320/HeliOS/blob/main/docs/architecture.md) · [Smoke test](https://github.com/Thom-320/HeliOS/blob/main/scripts/smoke.sh) |
| Numerical dynamics | [ChaosLab](https://github.com/Thom-320/chaoslab-double-pendulum) | [Physics implementation](https://github.com/Thom-320/chaoslab-double-pendulum/blob/main/src/chaoslab/physics.py) · [Live demo](https://thom-320.github.io/chaoslab-double-pendulum/) |

## Software

- [**ContratIA Abierta**](https://github.com/Thom-320/secop-risk-alerts-co): Colombian public-procurement pipelines, FastAPI services and traceable risk signals for human review.
- [**HeliOS**](https://github.com/Thom-320/HeliOS): a collaborative educational RISC-V kernel in C, with QEMU smoke tests.
- [**ChaosLab**](https://github.com/Thom-320/chaoslab-double-pendulum): double-pendulum dynamics with numerical checks and an [interactive explainer](https://thom-320.github.io/chaoslab-double-pendulum/).
- [**Foragers & Manager simulation**](https://github.com/EAndrade-Lotero/foragers_and_manager_sim_RL/pull/1): the Gymnasium `step()` pipeline (simulation, reward, 30 tests) for the agent-based version of the foraging experiment, in Edgar Andrade-Lotero's repository.

**Tools:** Python, PyTorch, NumPy/SciPy, Gymnasium, SimPy, NetworkX, R, C, SQL, FastAPI, pytest, Git.

## Suggested routes

- **AI evaluation:** [judge-decision-stability](https://github.com/Thom-320/judge-decision-stability) (φ, G/D-study, ICC, paired bootstrap; 39 tests) → [petri-judge-stability](https://github.com/Thom-320/petri-judge-stability) (the Petri pilot, batch runners for the follow-up and its pre-registration draft) → [metr-horizon-anchors](https://github.com/Thom-320/metr-horizon-anchors) (exact replication of METR's Time Horizon 1.1, then a refit on measured human times only).
- **Evaluation methods:** SCRES (matched comparators) → Motor-RNN (capacity-controlled comparison) → Spectral (temporal leakage audit).
- **Learning dynamics and NeuroAI:** Motor-RNN's NumPy FORCE/RLS implementation → ChaosLab → Spectral's invariant representations.
- **Research software:** ContratIA (pipelines, APIs, traceable review) → HeliOS (collaborative systems code).

[Back to profile](README.md)
