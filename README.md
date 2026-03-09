# TON Bug Triage

`ton-bug-triage` is a TON local-network triage skill designed for AI coding agents like Codex and Claude Code. It explains the details of the `tontester` tool for reproducing validator-level bugs in TON Blockchain with the assistance of AI.

This skill is intended for use within a cloned [ton-blockchain/ton](https://github.com/ton-blockchain/ton) repository.

## Install

Use the [Skills](https://skills.sh) CLI:

```sh
npx skills add https://github.com/ton-blockchain/ton-triage-skill --skill ton-bug-triage
```

## Use

Once the skill is installed, run your favorite coding agent, explain the bug you need to triage, and tell it to use the `ton-bug-triage` skill. The agent will autonomously run tests and try to reproduce the bug, then report the results.
