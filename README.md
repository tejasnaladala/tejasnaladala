<p align="center">
  <img src="./assets/header.svg" alt="Tejas Naladala — Hardware Engineer, AI Builder, Founder" width="100%"/>
</p>

<p align="center">
  <a href="https://tejasnaladala.com"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=21&pause=900&color=22D3EE&center=true&vCenter=true&width=820&lines=Hardware+engineer+%2B+AI+systems+builder;Founded+PlasmaX+at+16+%E2%80%94+plasma+reactors;Now%3A+autonomous+research+engines+%2B+AI+verification;Pre-register+the+hypothesis%2C+then+report+what+happened" alt="what I do"/></a>
</p>

<p align="center">
  <a href="https://tejasnaladala.com"><img src="https://img.shields.io/badge/Website-tejasnaladala.com-22d3ee?style=flat-square&logo=safari&logoColor=white&labelColor=0d1117"/></a>
  <a href="https://linkedin.com/in/tejasnaladala"><img src="https://img.shields.io/badge/LinkedIn-tejasnaladala-b15cff?style=flat-square&logo=linkedin&logoColor=white&labelColor=0d1117"/></a>
  <a href="mailto:naladala@uw.edu"><img src="https://img.shields.io/badge/Email-naladala@uw.edu-ff3d81?style=flat-square&logo=gmail&logoColor=white&labelColor=0d1117"/></a>
</p>

I build hardware and AI systems, and I care more than is healthy about whether they actually do what I claim they do.

Before college I shipped industrial plasma reactors and founded a company around them. Now I build autonomous research engines and verification pipelines, mostly pointed at one question: how do you tell a real result from a lucky one? ECE and Applied Math at the University of Washington.

## Selected work

The throughline across most of these is pre-registration: write the hypothesis and the pass/fail line before running anything, then report what happened, failures included.

[**delphi-quant**](https://github.com/tejasnaladala/delphi-quant) is a verification pipeline for systematic trading strategies. Strict backtester with transaction costs, slippage, walk-forward splits, and no look-ahead, plus Holm-Bonferroni correction so nothing passes on multiple-comparisons luck. Net of costs the baselines come in at 0.83 Sharpe for buy-and-hold, 0.77 for time-series momentum, and 0.26 for cross-sectional reversal, which is dead in this regime and the README says so.

[**maze-rl-baselines**](https://github.com/tejasnaladala/maze-rl-baselines) is a negative result I couldn't talk my way out of. On 9x9 procedural mazes a five-line wall-following heuristic solves 100% and a behavior-cloned MLP reaches about 97%, while hyperparameter-tuned modern RL (PPO, DQN, A2C across 70 runs) sits around 31%, statistically tied with a random walk. Roughly 3,500 runs, with regenerable data so you can check me.

[**connectome-bpu**](https://github.com/tejasnaladala/connectome-bpu) asks whether biological wiring diagrams make better network architectures than random graphs. Ten real connectomes frozen as fixed weight matrices, trained readout only, against four families of matched null graphs across six tasks. The answer is "sometimes, and here is exactly where," reported with the caveats intact.

[**agentbreed**](https://github.com/tejasnaladala/agentbreed) asks how much multi-agent LLM configuration actually buys you, under a timestamped protocol locked before any real-model run. Equivalence testing with TOST, Sobol sensitivity decomposition, and 509 unit and fuzz tests that surfaced 23 issues before data collection.

[**Forge**](https://github.com/tejasnaladala/Forge) is a provider-agnostic runtime for multi-agent LLM systems: declarative agents, routing across providers, pluggable memory, and the orchestration patterns you reach for in practice.

[**engram**](https://github.com/tejasnaladala/engram) is a framework for systems that learn from experience without backprop. Local Hebbian updates and neuromodulatory reward stand in for the optimizer, memory is persistent and both associative and episodic, and a safety kernel gates actions before they execute. Rust core, Python API.

[**mimic**](https://github.com/tejasnaladala/mimic) lets you teach a robot from a browser tab: WebRTC teleoperation into a simulated 7-DOF Franka arm, demo recording, training for an Action Chunking Transformer or a diffusion policy, and ONNX export.

Also public: [parameter-golf](https://github.com/tejasnaladala/parameter-golf) (a sweep-and-select harness for small-LM training competitions), [wireml](https://github.com/tejasnaladala/wireml) (a node-graph workbench for foundation models that runs in the browser on WebGPU), [knowledge-engine](https://github.com/tejasnaladala/knowledge-engine), and [icordion](https://github.com/tejasnaladala/icordion) (an iPhone turned into a playable accordion through its accelerometer).

## Before software

I founded PlasmaX at 16. It is a continuous industrial system that disinfects post-harvest produce with plasma-activated water, no chemicals, at roughly a quarter the cost of chlorine. I designed the 18 kV flyback driver and the STM32 control loop, and the first production unit sold to CSIR-CFTRI in India. The work produced three peer-reviewed papers on plasma-activated water (35 citations, h-index 3).

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=tejasnaladala&show_icons=true&hide_border=true&bg_color=0d1117&title_color=ff3d81&icon_color=22d3ee&text_color=c9d1d9&include_all_commits=true"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tejasnaladala&layout=compact&hide_border=true&langs_count=8&bg_color=0d1117&title_color=ff3d81&text_color=c9d1d9"/>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tejasnaladala/tejasnaladala/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tejasnaladala/tejasnaladala/output/github-snake.svg"/>
  <img alt="contribution snake" src="https://raw.githubusercontent.com/tejasnaladala/tejasnaladala/output/github-snake-dark.svg"/>
</picture>

## Elsewhere

[tejasnaladala.com](https://tejasnaladala.com) has the things a resume is too short for. Reach me at naladala@uw.edu.
