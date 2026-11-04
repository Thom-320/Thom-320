# Thomas Chisica Londoño

BSc in Applied Mathematics & Computer Science at **Universidad del Rosario**, Bogotá (2024–2028 · GPA 4.11/5.00 · full-tuition merit scholarship). I work on **evaluation**: does a result measure what it claims to measure? I build the controls that test a comparison (matched baselines, equal-capacity comparisons, past-only features), and I now apply them to the LLM judges and monitors used to evaluate AI systems.

[Project guide](PROJECTS.md) · [thomas.chisica@urosario.edu.co](mailto:thomas.chisica@urosario.edu.co) · CV on request

## Now

- [**Decision stability of LLM judges**](https://github.com/Thom-320/judge-decision-stability): how often a pass/fail or ranking decision flips when the judge, the rubric or the resample changes, on Anthropic's Petri alignment audits and on tutoring feedback. The analysis package is public; the pilot reports come next.
- **METR time horizons:** how much the horizons move between measured human baselines and researcher estimates, refit with METR's own code. In progress.
- [**Collective foraging and fairness**](https://github.com/EAndrade-Lotero/foraging_trucks): a two-player PsyNet experiment with Edgar Andrade-Lotero; I build most of the participant side (tutorials, game board, contract screens). In development.

## Evaluation work

| Project | What the control showed |
|---|---|
| [**SCRES**](https://github.com/Thom-320/scres-ia): RL for supply-chain resilience | Against a strong static policy under the same contract, PPO's advantage disappears: the static policy does slightly better (95% CI below zero). [Verdict](https://github.com/Thom-320/scres-ia/blob/main/docs/TRACK_B_SAME_CONTRACT_CHALLENGE_VERDICT_2026-07-10.md) |
| [**Motor-RNN connectivity**](https://github.com/Thom-320/nma-motor-rnn-connectivity): Neuromatch | Denser networks win only because they have more trainable connections. With an equal trainable budget the advantage drops by 0.231 (95% CI 0.193 to 0.267, all 16 seeds). [Robustness note](https://github.com/Thom-320/nma-motor-rnn-connectivity/blob/robustness-2026-10/paper/NOTE.md) |
| [**Spectral cognitive labor**](https://github.com/Thom-320/spectral-cognitive-labor): reanalysis of Andrade-Lotero & Goldstone | Found overlapping time windows in an early-prediction pipeline and rebuilt it with past-only features for 45 dyads. [Temporal audit](https://github.com/Thom-320/spectral-cognitive-labor/blob/main/docs/TEMPORAL_REPAIR.md) |

Software (ContratIA, HeliOS, ChaosLab) and reading routes are in the [project guide](PROJECTS.md).
