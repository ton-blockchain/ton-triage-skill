# TON Triage Skills

This repository contains TON triage skills designed for AI coding agents like Codex and Claude Code.

These skills are intended for use within a cloned [ton-blockchain/ton](https://github.com/ton-blockchain/ton) repository.

## Skills

- `ton-bug-triage`
  Reproduce TON bugs on a local `tontester` network, including contract-triggered repros and mixed-validator experiments.

- `tvm-fift-hypothesis-proving`
  Prove or reject TVM opcode, crash, gas-accounting, memory, CPU, and `RUNVM`/`RUNVMX` resource hypotheses with small Fift probes.

## Install

Use the [Skills](https://skills.sh) CLI:

```sh
npx skills add https://github.com/ton-blockchain/ton-triage-skill --skill ton-bug-triage
npx skills add https://github.com/ton-blockchain/ton-triage-skill --skill tvm-fift-hypothesis-proving
```

## Use

Once a skill is installed, run your favorite coding agent, explain the bug or hypothesis you need to triage, and tell it which skill to use.
