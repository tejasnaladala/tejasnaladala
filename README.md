# Tejas Naladala

I build hardware and AI systems, and I care more than is healthy about whether they actually do what I claim they do.

Before college I shipped industrial plasma reactors and founded a company around them. Now I build autonomous research engines and verification pipelines, mostly pointed at one question: how do you tell a real result from a lucky one? ECE and Applied Math at the University of Washington.

[tejasnaladala.com](https://tejasnaladala.com) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/tejasnaladala) &nbsp;·&nbsp; naladala@uw.edu

## Selected work

The throughline across most of these is pre-registration: write the hypothesis and the pass/fail line before running anything, then report what happened, failures included.

[**delphi-quant**](https://github.com/tejasnaladala/delphi-quant) is a verification pipeline for systematic trading strategies. Strict backtester with transaction costs, slippage, walk-forward splits, and no look-ahead, plus Holm-Bonferroni correction so nothing passes on multiple-comparisons luck. Net of costs the baselines land at 0.83 Sharpe for buy-and-hold, 0.77 for time-series momentum, and 0.26 for cross-sectional reversal, which is dead in this regime and the README says so plainly.

[**maze-rl-baselines**](https://github.com/tejasnaladala/maze-rl-baselines) is a negative result I couldn't talk my way out of. On 9x9 procedural mazes a five-line wall-following heuristic solves 100% and a behavior-cloned MLP reaches about 97%, while hyperparameter-tuned modern RL (PPO, DQN, A2C across 70 runs) sits around 31%, statistically tied with a random walk. Warm-starting DQN from the cloned policy makes it worse, not better. Roughly 3,500 runs, with regenerable data so you can check me.

[**agentbreed**](https://github.com/tejasnaladala/agentbreed) asks how much multi-agent LLM configuration actually buys you, under a timestamped protocol locked before any real-model run. Equivalence testing with TOST, Sobol sensitivity decomposition, and 509 unit and fuzz tests that surfaced 23 issues before data collection. When the pilot tripped its own consistency check, I published the deviation instead of burying it.

[**Forge**](https://github.com/tejasnaladala/Forge) is a provider-agnostic runtime for multi-agent LLM systems: declarative agents, routing across providers, pluggable memory, and the sequential, parallel, and supervisor patterns you reach for in practice.

[**engram**](https://github.com/tejasnaladala/engram) is a framework for systems that learn from experience without backprop. Local Hebbian updates and neuromodulatory reward stand in for the optimizer, memory is persistent and both associative and episodic, and a safety kernel gates actions before they execute. Rust core, Python API.

[**mimic**](https://github.com/tejasnaladala/mimic) lets you teach a robot from a browser tab: WebRTC teleoperation into a simulated 7-DOF Franka arm, demo recording, training for either an Action Chunking Transformer or a diffusion policy, and ONNX export.

[**parameter-golf**](https://github.com/tejasnaladala/parameter-golf) is the search-and-decide layer for small language-model training competitions. It runs factorial sweeps over the config space, picks a winner with a Welch t-test on bits-per-byte once seed noise is accounted for, and kills diverging runs before they waste the clock.

Also public: [wireml](https://github.com/tejasnaladala/wireml) (a node-graph workbench for foundation models that runs in the browser on WebGPU), [knowledge-engine](https://github.com/tejasnaladala/knowledge-engine) (saved content into a queryable knowledge graph), [icordion](https://github.com/tejasnaladala/icordion) (an iPhone turned into a playable accordion through its accelerometer), and [claude-nexus](https://github.com/tejasnaladala/claude-nexus) (coordination across multiple coding-agent instances).

## Before software

I founded PlasmaX at 16. It is a continuous industrial system that disinfects post-harvest produce with plasma-activated water, no chemicals, at roughly a quarter the cost of chlorine. I designed the 18 kV flyback driver and the STM32 control loop, and the first production unit sold to CSIR-CFTRI in India. The work produced three peer-reviewed papers on plasma-activated water (35 citations, h-index 3).

## Elsewhere

[tejasnaladala.com](https://tejasnaladala.com) has the things a resume is too short for. Reach me at naladala@uw.edu.
