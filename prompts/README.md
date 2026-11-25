# Prompts

Tested AI prompts for each step of Amplify. They work with any capable AI assistant (Claude, ChatGPT, Gemini, etc.).

| # | Prompt | Step | What it does |
|---|---|---|---|
| 1 | [Extract quotes](01-extract-quotes.md) | Extract | Finds candidate quotes in long content |
| 2 | [Draft a post](02-draft-post.md) | Draft | Writes a first draft with a **[STORY GAP]** for the leader |
| 3 | [Story questions](03-story-questions.md) | Humanize | Turns the story gap into 3 quick questions for the leader |
| 4 | [Repurpose](04-repurpose.md) | After posting | Spins a published post into other formats |

## Design principles

Every prompt here follows the same three rules:

1. **AI suggests, humans decide.** Every output is a shortlist or a draft, never a final answer.
2. **Never invent.** No made-up facts, quotes, customers, or experiences.
3. **Leave room for the human.** The best parts of a post must come from a real person.

## Improving a prompt

When you change a prompt, write a commit message that explains *why*, for example `Draft prompt: ban question hooks, they underperformed`. Over time, the commit history becomes a record of what you've learned.
