# Thomas Chisica

![spectral-cognitive-labor CI](https://img.shields.io/github/actions/workflow/status/Thom-320/spectral-cognitive-labor/ci.yml?branch=main&label=spectral%20CI)
![HeliOS CI](https://img.shields.io/github/actions/workflow/status/Thom-320/HeliOS/build.yml?branch=main&label=HeliOS%20CI)

Undergraduate in **Applied Mathematics & Computer Science** at Universidad del Rosario (Bogotá, Colombia), on a national merit scholarship. I am working toward a research career in **NeuroAI** and **computational neuroscience** — at the intersection of **reinforcement learning**, **collective behavior**, and **computational models of coordination under uncertainty**, with current work moving toward the **Free Energy Principle / Active Inference**.

My work sits between mathematics, machine learning, and the study of how agents — biological or artificial — coordinate and adapt under uncertainty. I try to keep what I build reproducible, honestly scoped, and grounded in theory.

## Research

- **Collective behavior & multi-agent coordination** with Prof. Edgar Andrade-Lotero (Universidad del Rosario / UC Davis) — behavioral experiments built on PsyNet, and a spectral / graph-theoretic reanalysis of self-organized division of cognitive labor. A geometric signal computed from the first five shared rounds predicts later axial specialization (**AUC_LOOCV = 0.86** when combined with early behavioral metrics; see [spectral-cognitive-labor](https://github.com/Thom-320/spectral-cognitive-labor)).
- **Supply-chain resilience as a learned capability** with Prof. Alexander Garrido (Universidad del Rosario) — PPO-based reinforcement learning over discrete-event simulations of disruption. PPO outperforms the best static policy under severe + stochastic disruption (**500k timesteps × 5 seeds**, frozen benchmark backbone; manuscript in preparation — see [scres-ia](https://github.com/Thom-320/scres-ia)).
- **Computational neuroscience** — **Neuromatch Academy 2026** (Computational Neuroscience track, in progress): a motor-cortex RNN connectivity project with paired held-out evaluation ([nma-motor-rnn-connectivity](https://github.com/Thom-320/nma-motor-rnn-connectivity)).

## Selected projects

| Project | Summary |
| --- | --- |
| [**scres-ia**](https://github.com/Thom-320/scres-ia) | Discrete-event simulation + reinforcement-learning framework for supply-chain resilience. PPO beats the best static policy under severe + stochastic disruption (500k timesteps × 5 seeds, frozen defaults). |
| [**spectral-cognitive-labor**](https://github.com/Thom-320/spectral-cognitive-labor) | Symmetry-aware spectral graph reanalysis of a division-of-cognitive-labor experiment; an early geometric signal predicts later specialization (AUC_LOOCV = 0.86). |
| [**nma-motor-rnn-connectivity**](https://github.com/Thom-320/nma-motor-rnn-connectivity) | Neuromatch Academy project: connectivity structure of motor-cortex RNNs with paired held-out evaluation. |
| [**HeliOS**](https://github.com/Thom-320/HeliOS) | Educational RISC-V 64 kernel (~1,900 lines C + assembly): QEMU boot, scheduling, timer interrupts, synchronization, and CI smoke tests. |
| [**secop-risk-alerts-co**](https://github.com/Thom-320/secop-risk-alerts-co) | Explainable risk prioritization over Colombian public-procurement open data; FastAPI + Dash, deployed on Render. |

## Technical background

Python · PyTorch · Gymnasium / Stable-Baselines3 · NumPy / SciPy · SimPy · NetworkX · C · LaTeX · reproducible pipelines (Make, pytest, CI)

## Contact

- Bogotá, Colombia
- Academic: [thomas.chisica@urosario.edu.co](mailto:thomas.chisica@urosario.edu.co)
- Personal: [chisicathomas@gmail.com](mailto:chisicathomas@gmail.com)
