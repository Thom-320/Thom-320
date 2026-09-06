# Thomas Chisica Londoño

**Applied Mathematics & Computer Science · Universidad del Rosario · Bogotá, Colombia**

[![Academic CV](https://img.shields.io/badge/Academic_CV-PDF-1f6feb?style=flat-square&logo=readthedocs&logoColor=white)](https://github.com/Thom-320/Thom-320/blob/main/Thomas_Chisica_CV.pdf)
[![Email](https://img.shields.io/badge/Email-Contact-334155?style=flat-square&logo=minutemailer&logoColor=white)](mailto:thomas.chisica@urosario.edu.co)
[![GitHub repositories](https://img.shields.io/badge/GitHub-Repositories-334155?style=flat-square&logo=github&logoColor=white)](https://github.com/Thom-320?tab=repositories)

I'm an undergraduate studying how people and learning systems adapt, coordinate,
and make decisions. I work with reinforcement learning and mathematical models
in computational neuroscience and simulation. I'm also interested in the
reliability of LLM-based systems.

I build simulations and compare methods to test whether a model works.
When a result changes under stronger controls, I investigate why.

## Selected research

| Project | Research focus |
| :--- | :--- |
| [**SCRES**](https://github.com/Thom-320/scres-ia) | Supply-chain simulation and control. Learned policies, structured baselines, and reproducible comparisons. |
| [**Spectral Cognitive Labor**](https://github.com/Thom-320/spectral-cognitive-labor) | Human collective search. Spectral graph methods, task symmetries, and division of the search space. |
| [**Motor RNNs**](https://github.com/Thom-320/nma-motor-rnn-connectivity) | Recurrent connectivity and learning. A Neuromatch team project with an independent fixed-plasticity follow-up. |

<details>
<summary><strong>My contributions and what the experiments showed</strong></summary>

### [SCRES · Supply-chain simulation and control](https://github.com/Thom-320/scres-ia)

With **Alexander Garrido**, I test whether learned control improves supply-chain
resilience under disruptions. I reconstructed a thirteen-operation model in
SimPy and built Gymnasium environments and PyTorch/PPO experiments.

I gave static comparators the same decision options as PPO, separating calibration
from held-out evaluation. Across 60 test runs and 10 PPO checkpoints, the stronger
static comparator overturned the apparent learning advantage. I also tested
retained-versus-reset online adaptation and maintain automated tests,
source-model checks, and reproducible experiment records.

*Python · SimPy · Gymnasium · PyTorch · reproducible experiments*

### [Spectral Cognitive Labor · Collective search](https://github.com/Thom-320/spectral-cognitive-labor)

This is my **independent reanalysis** of public human collective-search data,
not a contribution to the original experiment. I identified a degenerate
Fiedler eigenspace and compared human partitions with symmetry-aware references.
Early predictors were evaluated with leave-one-out cross-validation on 29 dyads
(exploratory AUC: 0.804 geometric; 0.860 combined). The repository includes
reproducible code, result tables, figures, and methodological limitations.

*Spectral graph theory · NetworkX · statistical analysis*

### [Motor RNNs · Connectivity and learning](https://github.com/Thom-320/nma-motor-rnn-connectivity)

This began as a **Neuromatch Academy Computational Neuroscience** team project.
I examined recurrent connectivity using paired seeds and held-out evaluation,
then continued with an independent follow-up. Increasing density also increased
the number of trainable weights. When I held that number fixed, the original
density trend did not recur.

*Recurrent networks · PyTorch · experimental controls*

</details>

## More projects

| Project | What I worked on |
| :--- | :--- |
| [HeliOS](https://github.com/Thom-320/HeliOS) | Contributions to a collaborative educational RISC-V kernel in C. |
| [ChaosLab](https://github.com/Thom-320/chaoslab-double-pendulum) | Python/Streamlit double-pendulum simulation with energy checks, phase-space trajectories, and flip-time maps. |

[![Spectral Cognitive Labor CI](https://img.shields.io/github/actions/workflow/status/Thom-320/spectral-cognitive-labor/ci.yml?branch=main&label=Spectral%20CI&style=flat-square)](https://github.com/Thom-320/spectral-cognitive-labor/actions)
[![HeliOS CI](https://img.shields.io/github/actions/workflow/status/Thom-320/HeliOS/build.yml?branch=main&label=HeliOS%20CI&style=flat-square)](https://github.com/Thom-320/HeliOS/actions)

## Research & experience

With **Edgar Andrade-Lotero** at Universidad del Rosario, in a UC Davis
collaboration, I contribute to **Foragers**: research on resource-sharing rules,
fairness, and collective outcomes, including group survival under scarcity.
I implemented the Gymnasium simulation's investment, allocation, harvest, and
redistribution pipeline, with a wealth-minus-inequality reward and tests of
rewards, state bounds, termination, and full episodes.

With **Adriana Maldonado-Chaparro**, I audit models of marmot social networks.
I traced agent–string comparisons that collapsed distinct homophily conditions,
using a Python reference implementation and NetLogo 5.2 smoke tests across
240 model-condition runs. I also built provisional dyadic tables linking
interactions, eligibility, and observation effort. Annual group membership alone
does not establish simultaneous availability or partner preference.

As **Lead in Emerging Technologies at Digital Business Ventures** (June–December
2025), I built Witty's support-email knowledge pipeline and an LLM-based chatbot
using FastAPI, FAISS, and multi-provider embeddings, with heuristic
answer-or-escalate routing. The code remains private.

I also served as a **Calculus I teaching assistant** at Universidad del Rosario
from July 2024 to July 2025.

## Tools I use

**Modelling & analysis:** Python, PyTorch, NumPy, SciPy, NetworkX, SimPy, Gymnasium, R.

**Software:** C, SQL, FastAPI, Git, pytest, Linux, LaTeX.

---

I'm looking for research internships and collaborations in learning systems,
computational neuroscience, and reliable AI. [Email me](mailto:thomas.chisica@urosario.edu.co).
You can also reach me at [chisicathomas@gmail.com](mailto:chisicathomas@gmail.com).
