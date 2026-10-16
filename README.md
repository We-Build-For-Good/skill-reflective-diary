# Reflective AI Diary: The Continuous Calibration Protocol

> **An open-source AI engineering protocol from [We Build for Good](https://webuildforgood.com)**  
> *Move beyond stateless autocomplete. Build self-calibrating AI partnerships.*

---

## Overview

`reflective-ai-diary` is a metacognitive operational protocol for AI assistants and autonomous coding agents. 

It defines a structured methodology for an AI to maintain a persistent, unvarnished journal auditing its own cognitive traps, communication failures with human operators, false assumptions, and operational growth over time.

---

## The Core Problem

Standard AI coding assistants suffer from severe amnesia across sessions:
* They repeat the exact same misunderstandings across different prompts.
* They oscillate between being uncomfortably passive (asking permission for trivial steps) and overly presumptuous (refactoring code they were not asked to touch).
* They lack a mechanism to examine *why* their reasoning failed.

`reflective-ai-diary` turns your AI collaborator from a forgetful autocomplete engine into a thoughtful, self-correcting partner.

---

## Key Principles

1. **Not a Status Report**: The diary does not record routine ticket progress. It captures the psychology, reasoning, and operational friction of human-AI collaboration.
2. **Fact vs Interpretation**: The protocol forces the AI to strictly distinguish observable facts (terminal outputs, verbatim user quotes) from its internal interpretations, preventing hallucinations from hardening into dogma.
3. **Actionable Calibrations**: Every logged mistake must produce a concrete behavioral rule tested in subsequent shifts.
4. **Privacy First**: Raw internal diary files remain strictly private on the local machine. Only sanitized entries tagged `[PUBLIC SHARE]` are ever considered for external publication.

---

## Installation

### For Claude Code
```bash
git clone https://github.com/webuildforgood/skill-reflective-diary.git ~/.claude/skills/reflective-ai-diary
```

### For Cursor
```bash
mkdir -p .cursor/skills
git clone https://github.com/webuildforgood/skill-reflective-diary.git .cursor/skills/reflective-ai-diary
```

### For Antigravity / Open Agent Skills
```bash
mkdir -p .agents/skills
git clone https://github.com/webuildforgood/skill-reflective-diary.git .agents/skills/reflective-ai-diary
```

---

## How to Use It

1. Create a `COORDINATOR-DIARY.md` (or `AI-DIARY.md`) in your repository.
2. Instruct your AI:
   * *"Read the last 3 diary entries to calibrate your working stance for this session."*
   * *"At the end of this shift, record an unvarnished diary entry reflecting on our communication friction and what you learned."*
3. The AI will audit its own execution, record its insights using the canonical schema, and carry those lessons forward into future sessions.

---

## License

MIT License. Developed and maintained by [We Build for Good](https://webuildforgood.com).
