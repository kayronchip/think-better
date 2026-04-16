# think-better

think-better is a Claude skill developed as part of [Think With AI](https://modularthinking.io), a newsletter that ships a companion skill with every issue.

It turns AI into a structured thinking partner for decisions and problems.

Instead of asking AI for answers, think-better runs you through the **TPS framework**: Triage, Probe, Synthesize — keeping the thinking yours and the judgment where it belongs.

---

## The Problem

Every time you ask AI "what should I do?", you hand over the most important part of the process. AI can process information. It cannot feel consequences, weigh what's actually at stake, or know what you're not saying. When you ask it to decide, you get an answer. You lose the thinking.

The sharpest people use AI as a thinking tool, not an answering machine.

---

## How It Works

think-better runs three steps:

**1. Triage** — Before anything else, understand what kind of decision you're holding. Is it reversible? What happens if you get it wrong? Two or three exchanges and you know whether this needs ten minutes or three days.

**2. Probe** — Use what triage surfaced to challenge your thinking. AI asks questions one at a time — pushing on assumptions, surfacing blind spots, exploring how the decision could fail. The thinking stays yours. AI does the probing.

**3. Synthesize** — Close with a summary of what you decided, the key reasons, what you ruled out, and where the reasoning is still weak.

---

## Activation

Say any of the following in Claude:

- `/think-better`
- `think through [problem]`
- `help me decide [decision]`

---

## Installation

1. Install the [Claude Code CLI](https://claude.ai/code)
2. Add the marketplace and install the plugin:

```bash
/plugin marketplace add https://github.com/kayronchip/think-better
/plugin install think-better
```

Or load it locally during development:

```bash
claude --plugin-dir ./think-better
```

---

## The Thinking Behind It

This skill was built alongside the newsletter [Think With AI](https://modularthinking.io) — a weekly read for knowledge workers who use AI daily and want to use it better.

The first issue explores the exact problem this skill solves: why asking AI for answers is the wrong move, and what to ask instead.

---

## Author
Built by [Kayron Chip](https://modularthinking.io)
License: MIT
