# AI Council (LLM Council TR)

## English
**Purpose**  
AI Council (LLM Council TR) sends a decision, idea, or strategy through five specialist adviser roles that debate, anonymously review, and score the proposal out of 100.

**Verified Features**  
- Five adviser roles: Skeptic, First‑Principles Adviser, Growth Adviser, Independent Reviewer, and Operator  
- A 0–100 feasibility score  
- Anonymous cross‑review between advisers  
- A chairperson synthesis of agreements, disagreements, and blind spots  
- Automatically generated visual HTML reports  
- Markdown transcripts for every session  

**Setup / Usage**  
```bash
git clone https://github.com/emirhankaya-AFK/llm-konseyi-tr ~/.claude/skills/llm-konseyi
```
Alternatively, create `~/.claude/skills/llm-konseyi/` and copy `SKILL.md` into it.  

Ask the AI environment with a supported Turkish trigger, for example:  
> `konsey topla: Which of my two YouTube channels should receive more of my time?`  

Each session produces a visual HTML report and a complete Markdown transcript in the configured decisions directory.

**Limitations**  
- Requires a Turkish‑language trigger phrase (`konsey topla:`).  
- Depends on an AI environment that can load and execute the skill from `~/.claude/skills/`.  
- Reports are generated locally; no external service or API keys are involved.  

**License**  
MIT  

## Türkçe
The Turkish version of this document is available in `README_TR.md`.

## Deutsch
A German translation is not currently available.
