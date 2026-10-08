<h1 align="center">Thomas Chisica Londoño</h1>

<p align="center">
  Applied Mathematics &amp; Computer Science · Universidad del Rosario · Bogotá, Colombia
</p>

<p align="center">
  <a href="PROJECTS.md">Project guide</a> ·
  Updated CV: coming ·
  <a href="mailto:thomas.chisica@urosario.edu.co">Email</a>
</p>

## What I work on

I build simulations and learning experiments, then test what their comparisons
actually establish: strong baselines, held-out evaluation and explicit controls.

My research question is whether automated judges and monitors measure what they
claim to measure. Public work so far is on reinforcement learning, recurrent
networks and human-coordination data. Next, I want to apply the same measurement
tests to LLM judges and monitors in post-training and multi-agent systems.
That last sentence is a plan, not a result.

**Status:** expected graduation 2028 (date to confirm). No publications yet; one
manuscript is in preparation and has not been submitted.

## Research

| Project | What I did |
| --- | --- |
| **[SCRES](https://github.com/Thom-320/scres-ia)**<br>reinforcement learning · simulation | Supervised project: supply-chain simulation and Gymnasium/PPO experiments judged against a same-contract static comparator. The learned policy was ahead in only 2 of 10 checkpoint means and 2 of 60 held-out streams; the earlier advantage claim was withdrawn.<br>Start with the [same-contract verdict](https://github.com/Thom-320/scres-ia/blob/main/docs/TRACK_B_SAME_CONTRACT_CHALLENGE_VERDICT_2026-07-10.md). |
| **[Motor-RNN connectivity](https://github.com/Thom-320/nma-motor-rnn-connectivity)**<br>computational neuroscience | Neuromatch team project, then my independent equal-plasticity control, which holds the number of trainable recurrent edges equal across densities. Under that control the density ordering from the team's primary run reversed: the error of the sparsest network minus the mean of the denser ones changed sign in 8 of 8 seeds (95% bootstrap interval −0.113 to −0.068; exploratory, one architecture).<br>Start with the [control note](https://github.com/Thom-320/nma-motor-rnn-connectivity/blob/main/docs/EQUAL_PLASTICITY_CONTROL.md). |
| **[Spectral analysis of cognitive labor](https://github.com/Thom-320/spectral-cognitive-labor)**<br>human coordination | My reanalysis of Andrade-Lotero and Goldstone's human-search experiment (the data belong to the original authors), with a past-only temporal audit. Predictive advantage is not established.<br>Start with the [temporal audit](https://github.com/Thom-320/spectral-cognitive-labor/blob/main/docs/TEMPORAL_REPAIR.md). |

## What did not hold up

- **SCRES:** the PPO advantage over a strong same-contract static policy did not survive the comparison, so the earlier claim was withdrawn.
- **Spectral:** early-prediction AUCs of 0.804 and 0.860 used overlapping time windows and are not validated. No predictive or spectral advantage is established.
- **Motor-RNN:** the primary density ordering reversed under equal trainable edges (8 of 8 seeds; exploratory, one architecture; see the control note).

## Software

- **[HeliOS](https://github.com/Thom-320/HeliOS)**: a collaborative educational RISC-V kernel in C. I am a contributor, not the sole author. Architecture notes and QEMU smoke tests; smoke tests are not formal verification.
- **[ContratIA Abierta](https://github.com/Thom-320/secop-risk-alerts-co)**: open-procurement data pipelines, FastAPI services and traceable signals for human review, not automated allegations. Human validation is still pending.
- **[ChaosLab](https://github.com/Thom-320/chaoslab-double-pendulum)**: double-pendulum dynamics with numerical checks and an interactive presentation. A physics course project, not an ML result.

## Outside my repositories

- Merged pull request: [ForagersEnv.step() simulation pipeline](https://github.com/EAndrade-Lotero/foragers_and_manager_sim_RL/pull/1), in another group's repository (merged 2026-02-28).

## Coming (not yet public)

- A short note on judge calibration.
- A two-page reanalysis note on the spectral experiment.

## Private work

Described in the CV and not published: a retrieval-augmented support prototype
with heuristic answer/escalation routing (synthetic data); numerical-analysis
coursework; and a computational audit of a marmot social-network model, done
with a collaborator whose name is withheld until they agree.

## How to read my repositories

Read the question and the stated limitations, inspect a saved result and its
method, then follow the documented test path. The existing evidence can be
inspected without refitting any model.

**Tools:** Python · PyTorch · NumPy/SciPy · NetworkX · SimPy · Gymnasium · C · SQL · FastAPI · Git · pytest
