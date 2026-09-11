# Codex Usage as a Systems Problem

A practical, evidence-aware field guide to reducing avoidable Codex context and usage while preserving result quality.

## About

Codex usage is not controlled by model choice alone. It emerges from the entire working system: persistent instructions, conversation history, tool payloads, delegated-agent context, reasoning effort, retries, and provider-side accounting.

This project turns that system into an actionable operating model. It separates what can be observed locally from what remains a provider-side hypothesis, orders interventions by reversibility, and optimizes for the cost of a verified result rather than the apparent cost of one turn.

## Read the field guide

Open the [live Codex Usage as a Systems Problem field guide](https://az9713.github.io/gpt6-usage-as-system-problem/gpt-6-usage.html) for the complete standalone dark-mode report. The repository also contains the portable [HTML source](gpt-6-usage.html).

The guide covers:

- The difference between context, cumulative usage, and disk footprint
- Where avoidable context enters an agentic workflow
- Session handoffs and clean task boundaries
- Bounded subagent prompts and model routing
- Plugin, skill, and MCP inventory discipline
- Controlled experiments for caching and reasoning-effort claims
- A reversible action ladder that protects correctness

## Inspiration

This project was inspired by [Eric Michaud's YouTube video on getting more value from Codex usage](https://www.youtube.com/watch?v=G-FpN6_uoug&t=5s), particularly its emphasis on shorter sessions, deliberate model selection, and bounded subagent context.

The field guide extends those ideas with a stricter evidence framework: observable overhead is separated from practitioner inference, and uncertain claims are converted into matched experiments rather than treated as settled billing mechanics.

## Design

The report is a single dependency-free HTML file with:

- A dark, high-contrast responsive interface
- Keyboard-accessible navigation
- A separate light print and PDF palette
- No external scripts, fonts, analytics, or embedded private material
