# AI Council (LLM Council TR)

[English](README.md) | [Türkçe](README_TR.md)

Do not rely on the first answer from a single model. AI Council sends a decision, idea, or strategy through five specialist adviser roles that debate, anonymously review, and score the proposal out of 100.

## Highlights

- Five adviser roles: Skeptic, First-Principles Adviser, Growth Adviser, Independent Reviewer, and Operator
- A 0–100 feasibility score
- Anonymous cross-review between advisers
- A chairperson synthesis of agreements, disagreements, and blind spots
- Automatically generated visual HTML reports
- Markdown transcripts for every session

## Install

```bash
git clone https://github.com/emirhankaya-AFK/llm-konseyi-tr ~/.claude/skills/llm-konseyi
```

Alternatively, create `~/.claude/skills/llm-konseyi/` and copy `SKILL.md` into it.

## Use

Ask the AI environment with a supported Turkish trigger, for example:

> `konsey topla: Which of my two YouTube channels should receive more of my time?`

The skill evaluates growth potential, automation, revenue, competition, sustainability, and other criteria relevant to the prompt.

## Output

Each session produces a visual HTML report and a complete Markdown transcript in the configured decisions directory.

## License

MIT

