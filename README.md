<p align="center">
  <img src="./assets/binary-boot-color.gif" alt="Amber binary portrait of Tejas Naladala booting into view" width="272" />
</p>

<h1 align="center">Tejas Naladala</h1>

<p align="center"><strong>I build and research full-time.</strong></p>

<p align="center">
  <a href="https://tejasnaladala.com">website</a>
  &nbsp;&middot;&nbsp;
  <a href="https://scholar.google.com/citations?user=7901XFQAAAAJ">Google Scholar</a>
  &nbsp;&middot;&nbsp;
  <a href="https://www.linkedin.com/in/tejasnaladala">LinkedIn</a>
  &nbsp;&middot;&nbsp;
  <a href="mailto:naladala@uw.edu">email</a>
</p>

I study Engineering at the [University of Washington](https://www.washington.edu/). This GitHub holds the code and result records behind my research. The machines, fieldwork, and less repository-shaped work live on [my website](https://tejasnaladala.com/work).

## Answers I found

**[MTEB-Gym](https://github.com/embeddings-benchmark/MTEB-gym-v2) - label-free embedding evaluation.** *When can label-free evaluation produce a trustworthy model ranking?* I co-developed a framework for ranking embedding models on corpora without human relevance annotations. My [nine merged upstream changes](https://github.com/embeddings-benchmark/MTEB-gym-v2/pulls?q=is%3Apr+author%3Atejasnaladala+is%3Amerged) cover bidirectional judging, validation, uncertainty estimates, caching, deterministic parallelism, and failure handling. The active reliability study still needs a public result artifact.

**[AgentBreed](https://github.com/tejasnaladala/agentbreed) - agent configuration search.** *How much performance comes from the configuration space, and how much from the search operator?* The preregistered synthetic pilot ran 700 reproducible evaluations across three domains in a deterministic simulator. Pairwise differences among the tested search operators did not reach Holm-corrected significance; this does not establish equivalence. The real-LLM replication is preregistered and pending, and the current sensitivity-analysis output is excluded from inference.

**[Procedural-Maze RL Baselines](https://github.com/tejasnaladala/maze-rl-baselines) - reproducible reinforcement-learning benchmark.** *Why did modern reward-driven RL miss a policy a five-line heuristic could see?* I benchmarked PPO, DQN, and A2C on procedurally generated mazes against simple heuristics and behavior cloning. The policy class can express strong maze-solving behavior, while reward-driven training struggled to reach it consistently. The repository includes code, run records, manifests, and a result verifier. Later runs outgrew the pinned manifest, so artifact reconciliation is underway before final reporting.

**[Connectome Architecture Benchmark](https://github.com/tejasnaladala/connectome-bpu) - controlled architecture benchmark.** *Does biological wiring still help after density, weights, graph realizations, and trainable components are controlled?* An audit invalidated the original 757-row pilot after finding control-density, provenance, optimizer, and evaluation failures. CAB v2 uses digest-bound measured connectomes, readout-only optimization, and nulls matched on exact edge count and weight distribution. The corrected protocol is implemented and tested; the full run is pending.

**[Ocean CV / RR2607](https://interactiveoceans.washington.edu/about-visions-26/) - in progress.** *Can methane-bubble flux be estimated while the experiment is 2,900 meters underwater?* I am building a field-to-analysis system across ROV video, sonar, hydrophone, CTD, and navigation data. Its provenance layer keeps shipboard sources read-only and traces derived artifacts to source paths, hashes, and code versions. Current work covers computer vision, acoustic alignment, calibration, and held-out validation. The project is still in progress.

## Technical notes

**[VLM Inference Optimization](https://tejasnaladala.com/assets/research/alphaevolve-charxiv-note.pdf).** [Professor Zhuang Liu](https://www.cs.princeton.edu/~zhuangl/), Princeton University. An AlphaEvolve-style search produced a best single-prompt Qwen3-VL configuration at 63.25% held-out CharXiv accuracy versus 60.5% for the manual prompt (p = .42). A separately designed per-question router reached 73.0% against a 29.5% naive baseline (paired p = 2.4e-6), with inspectable lineage for every accepted mutation.

**[Single-GPU Model Serving](https://tejasnaladala.com/assets/research/qwen-glm-serving-benchmark.pdf).** [Professor Juncheng Yang](https://seas.harvard.edu/person/juncheng-yang), Harvard University. An 80-point vLLM matrix compared dense and mixture-of-experts models across prompt length, generation length, concurrency, and serving configuration on one H100. The measured throughput crossover appeared near concurrency three; a hardware audit also caught PCIe throttling before publication.

## Other systems

[**Mimic**](https://github.com/tejasnaladala/mimic), browser teleoperation and imitation learning for a simulated Franka arm; [**Engram**](https://github.com/tejasnaladala/engram), experimental online learning with local plasticity and persistent memory; [**Forge**](https://github.com/tejasnaladala/Forge), a provider-agnostic agent runtime with tools, memory, budgets, and observability; [**WireML**](https://github.com/tejasnaladala/wireml), a terminal workbench for lightweight heads on foundation-model embeddings; [**delphi-quant**](https://github.com/tejasnaladala/delphi-quant), a retrospective verification harness for systematic strategies and legible rejection.

## Publications

Three peer-reviewed plasma-engineering papers: [*Design of systems for plasma activated water for agri-food applications*](https://doi.org/10.1088/1361-6463/ad77de), [*Design of a continuous PAW disinfection system for fresh produce industry*](https://doi.org/10.1016/j.ifset.2024.103845), and [*Design and construction of continuous industrial-scale cold plasma equipment for fresh produce industry*](https://doi.org/10.1016/j.ifset.2024.103840). [Google Scholar](https://scholar.google.com/citations?user=7901XFQAAAAJ) records 57 citations and an h-index of 3 as of Sep 2026.
