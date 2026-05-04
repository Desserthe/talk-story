# Talk-Story

A Claude Code skill that turns a vague research idea into a publishable paper design — through Socratic dialogue, not lectures.

English | [中文](./README.zh-CN.md)

---

## What It Does

Most research ideas start as a fuzzy observation: *"I noticed that X seems to happen in China..."* or *"Is this publishable?"*

Talk-Story is a structured conversation partner that pushes back, exposes weak spots, and helps you discover whether your idea has real teeth. It works through 7 progressive stages:

| Stage | Goal |
|-------|------|
| 1. Clarify the Observation | Pin down exactly what you observed |
| 2. Identify the Puzzle | Find the theoretical tension |
| 3. Find the Contribution | What changes after your paper exists? |
| 4. Build the Mechanism | *Why* does the relationship exist? |
| 5. Engage the Literature | Where does this fit in active debates? |
| 6. Assess Feasibility | Data, methods, timeline |
| 7. Elevator Pitch | 3–4 sentence synthesis — the real test |

The session ends when you can deliver the Stage 7 pitch fluently and name a target journal.

---

## Installation

Requires [Claude Code](https://claude.ai/code) with the Superpowers plugin.

```bash
# Clone into your Claude skills directory
git clone https://github.com/Desserthe/talk-story ~/.claude/skills/talk-story
```

The skill is auto-discovered on next Claude Code session start.

---

## Usage

Trigger naturally — no slash command needed. Just tell Claude you have a research idea:

> "I have an idea about X, can this become a paper?"  
> "I want to write about Y, is it publishable?"  
> "我有个想法，帮我看看能不能做成论文"

Claude will open with:

> 好，把你的想法告诉我——一句话就好。不用完整，不用好听，就是你脑子里现在最原始的那个观察。

Then the conversation begins.

---

## Design Principles

- **One move at a time** — never more than 2 questions per turn
- **Named challenges** — when pushing back, always says *why* ("this is a contribution problem")
- **Bilingual** — responds in whatever language you use (Chinese, English, or mixed)
- **Entry point, not endpoint** — designed to hand off to `deep-research` or `academic-paper` when the idea is ready

---

## Handoffs

After Talk-Story, natural next steps:

- **`deep-research`** — systematic literature search to map the debates your paper enters
- **`academic-paper`** — draft the paper structure and write
- **Written research brief** — a shareable summary for collaborators

---

## Target Users

Graduate students and researchers in sociology, economics, and related social sciences who need a thinking partner before committing to a full research project.

---

## License

CC-BY-NC 4.0 — free to use and adapt for non-commercial purposes.
