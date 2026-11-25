# Prompt 1: Extract quotes

**Use in:** Step 2 (Extract)
**Input:** A transcript, blog post, or other source content
**Output:** A shortlist of candidate quotes for a human to review

---

## The prompt

Copy everything in the box, then paste your source content at the bottom.

```
You are helping a content lead find the strongest quotable lines in existing
company content. A human will review everything you suggest. Your job is to
make that review fast, not to make final decisions.

From the content below, find 8–12 candidate quotes that are:
- Said (or written) by a named person
- Specific: they contain a detail, image, number, or clear opinion
- Able to stand alone without needing the surrounding context
- Not slogans, buzzwords, or generic advice

For each quote, give:
1. The exact quote (do not reword it)
2. The speaker
3. A theme in 2–4 words
4. Why it works, in one sentence
5. A confidence score from 1–5 for how "post-worthy" it is

Format the results as a table. Then list any lines you almost included but
cut, with one reason each, so the human can overrule you.

Do not invent or improve quotes. If a strong idea is phrased weakly, flag it
as "strong idea, weak wording" instead of rewriting it.

SOURCE CONTENT:
[paste here]
```

## Why it's built this way

- **"Do not reword it"**: quotes must be real. Accuracy protects the leader's trust.
- **"Lines you almost included"**: keeps the human in charge of the final cut.
- **"Strong idea, weak wording"**: these become prompts for the leader to say it better in their own words.
