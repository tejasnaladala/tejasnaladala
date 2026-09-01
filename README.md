<p align="center">
  <img src="./assets/binary-boot-color.gif" alt="Amber binary portrait of Tejas Naladala booting into view" width="272" />
</p>

<h1 align="center">Tejas Naladala</h1>

<p align="center"><strong>I build and research full-time.</strong></p>

<p align="center">
  <a href="https://tejasnaladala.com">website</a>
  &nbsp;&middot;&nbsp;
  <a href="https://tejasnaladala.com/work">work</a>
  &nbsp;&middot;&nbsp;
  <a href="https://tejasnaladala.com/research">research</a>
  &nbsp;&middot;&nbsp;
  <a href="https://tejasnaladala.com/blog">"Un"Supervised</a>
  &nbsp;&middot;&nbsp;
  <a href="https://scholar.google.com/citations?user=7901XFQAAAAJ">Google Scholar</a>
</p>

I'm 19.

I grew up around a family farm in a small coastal village in South India, where crops, chemicals, machines, and money were never abstract. Now I study Engineering at the [University of Washington](https://www.washington.edu/).

## Answers I found

### [MTEB-Gym](https://github.com/embeddings-benchmark/MTEB-gym-v2)

*Can you choose an embedding model for a corpus that has no human relevance labels?*

MTEB-Gym turns a corpus into synthetic queries, compares retrieved results in both presentation orders, and fits a Bradley-Terry ranking with bootstrap intervals. Across 16 retrieval datasets, the harder problem was not producing a ranking; it was knowing when the judge and the generated task were trustworthy. Weak queries and task-definition mismatch did more damage than the rating model.

I co-developed the reliability study and contributed [nine merged changes](https://github.com/embeddings-benchmark/MTEB-gym-v2/pulls?q=is%3Apr+author%3Atejasnaladala+is%3Amerged) spanning validation, uncertainty estimation, caching, deterministic parallelism, and failure handling.

### [AgentBreed](https://github.com/tejasnaladala/agentbreed)

*When optimizing an agent, does the search operator matter more than the space it is allowed to search?*

In a preregistered deterministic pilot, 700 evaluations across three domains found that multi-component search beat prompt-only search by a wide margin. Within that richer space, evolution, mutation-only, crossover-only, random search, and Bayesian optimization were statistically indistinguishable after correction.

The repository includes the tested optimization library, all reproduction paths, and the locked design for a real-LLM replication. The current answer applies to the synthetic pilot; the real-model study remains to be run.

### [Procedural-Maze RL Baselines](https://github.com/tejasnaladala/maze-rl-baselines)

*Why can a five-line policy solve a maze that reward-driven agents cannot?*

On unseen 9x9 mazes, an egocentric wall follower reached 100% success and behavior cloning reached 97.2%. PPO, DQN, and A2C did not reliably discover the same policy; even a DQN initialized from the cloned policy fell back toward scratch performance during fine-tuning.

The result is backed by 4,200+ raw run records, 20+ seeds per headline cell, code hashes, a SHA-256-pinned manifest, and a verifier that recomputes every reported number.

### [Connectome Architecture Benchmark](https://github.com/tejasnaladala/connectome-bpu)

*Does biological wiring still help a neural network after the obvious graph confounds are controlled?*

My first answer was wrong. An audit found that the original benchmark trained components meant to remain fixed, mismatched control density, included synthetic stand-ins, omitted immutable data provenance, and evaluated CartPole on training episodes.

The repository preserves all 757 invalidated rows, marks them unusable, and refuses to report them without an explicit forensic override. The corrected readout-only, density-matched protocol is implemented and tested. It has not yet produced a full replacement result.

## Still asking

### [VISIONS '26 / Ocean CV](https://interactiveoceans.washington.edu/07/2026/tejas-naladala/naladala_tejas_v26/)

*Can video and sonar be fused into provenance-aware estimates of underwater methane-bubble flux?*

This began during fifteen days aboard R/V *Roger Revelle*, across 18 ROV Jason dives at Axial Seamount and Southern Hydrate Ridge. I am building the computer-vision, acoustic-alignment, calibration, and held-out validation pipeline.

## Other systems

[**Mimic**](https://github.com/tejasnaladala/mimic) - browser teleoperation and imitation learning for a simulated Franka arm.

[**Engram**](https://github.com/tejasnaladala/engram) - online learning with local plasticity, persistent memory, and safety gates.

[**Forge**](https://github.com/tejasnaladala/Forge) - provider-agnostic agents with tools, memory, budgets, and observability.

[**WireML**](https://github.com/tejasnaladala/wireml) - a terminal workbench for CLIP/DINOv2 features, lightweight heads, held-out evaluation, and linear-head ONNX export.

[**delphi-quant**](https://github.com/tejasnaladala/delphi-quant) - a verification harness for systematic strategies and legible rejection.

## Published work

Three peer-reviewed plasma-engineering papers, 57 citations, and an h-index of 3. The papers and current manuscripts live on [Google Scholar](https://scholar.google.com/citations?user=7901XFQAAAAJ); the machines, fieldwork, and less GitHub-shaped parts live on [my website](https://tejasnaladala.com/work).

For the person behind all of it, read [about](https://tejasnaladala.com/about). For questionable decisions, read ["Un"Supervised](https://tejasnaladala.com/blog).

<p align="right">
  <a href="https://www.linkedin.com/in/tejasnaladala">LinkedIn</a>
  &nbsp;&middot;&nbsp;
  <a href="mailto:naladala@uw.edu">naladala@uw.edu</a>
</p>
