# Thomas Chisica Londoño

Applied Mathematics & Computer Science at **Universidad del Rosario**, Bogotá · minors in Advanced Mathematics and AI.

I work on **evaluation**: does a result measure what it claims to measure?
In reinforcement learning, neural network models and human-behaviour data,
I build the controls that test a comparison (matched baselines,
equal-capacity comparisons, past-only features) and report what the control shows.
I now apply the same tests to the automated judges and monitors used to evaluate
LLMs: how often does a pass/fail or ranking decision change when the judge changes?

[Project guide](PROJECTS.md) · [thomas.chisica@urosario.edu.co](mailto:thomas.chisica@urosario.edu.co) · CV on request

## Now

- **Decision stability of LLM judges.** A small Python package that measures how often a pass/fail or ranking decision flips when the judge, the rubric wording or the resample changes. Pilots on Anthropic's Petri alignment audits (public CC-BY corpus) and on tutoring feedback. In progress, to be released with its first report.
- **What METR's time horizons depend on.** A pilot that refits METR's Time Horizon 1.1 with METR's own code and asks how much the horizons move between measured human baselines and researcher estimates. In progress.
- **Collective foraging and fairness:** an online behavioural experiment (PsyNet) with Edgar Andrade-Lotero. In development.

## Evaluation work: start here

| Project | What I built | What the control showed |
|---|---|---|
| [**SCRES**](https://github.com/Thom-320/scres-ia): RL for supply-chain resilience (supervised project) | SimPy + Gymnasium simulator, PPO pipeline, and a same-contract comparator that holds constraints fixed across policies | Against a strong static policy under the same contract, the static policy does slightly better than PPO (95% CI below zero); PPO leads in only 2 of 10 checkpoints and 2 of 60 held-out streams. [Verdict](https://github.com/Thom-320/scres-ia/blob/main/docs/TRACK_B_SAME_CONTRACT_CHALLENGE_VERDICT_2026-07-10.md) |
| [**Motor-RNN connectivity**](https://github.com/Thom-320/nma-motor-rnn-connectivity): Neuromatch Computational Neuroscience | Team FORCE/RLS project, then my independent equal-plasticity control and a 16-seed robustness study | Denser networks do better only because they have more trainable connections. With an equal trainable budget the advantage drops by 0.231 (95% CI 0.193 to 0.267, all 16 seeds), and this holds under spectral-radius matching, random subsets and N = 400. [Robustness note](https://github.com/Thom-320/nma-motor-rnn-connectivity/blob/robustness-2026-10/paper/NOTE.md) (draft) |
| [**Spectral analysis of cognitive labor**](https://github.com/Thom-320/spectral-cognitive-labor): reanalysis of Andrade-Lotero & Goldstone | Spectral vs. coordinate representations of collective search; a temporal audit that rebuilds past-only features for 45 dyads | Found overlapping time windows in an earlier early-prediction pipeline and rebuilt it without them. [Temporal audit](https://github.com/Thom-320/spectral-cognitive-labor/blob/main/docs/TEMPORAL_REPAIR.md) |

## Software

- [**ContratIA Abierta**](https://github.com/Thom-320/secop-risk-alerts-co): Colombian public-procurement pipelines, FastAPI services and traceable risk signals for human review.
- [**HeliOS**](https://github.com/Thom-320/HeliOS): a collaborative educational RISC-V kernel in C, with QEMU smoke tests.
- [**ChaosLab**](https://github.com/Thom-320/chaoslab-double-pendulum): double-pendulum dynamics with numerical checks and an [interactive explainer](https://thom-320.github.io/chaoslab-double-pendulum/).
- Contributed the `ForagersEnv.step()` simulation pipeline to [another group's RL repository](https://github.com/EAndrade-Lotero/foragers_and_manager_sim_RL/pull/1) (merged).

**Tools:** Python, PyTorch, NumPy/SciPy, Gymnasium, SimPy, NetworkX, R, C, SQL, FastAPI, pytest, Git.

I use AI coding assistants (Claude, Codex) and check every reported number against saved outputs.
