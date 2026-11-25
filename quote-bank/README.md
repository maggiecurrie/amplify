# Quote bank

The quote bank is the heart of the system: a library of approved lines from existing content, ready to become posts.

👉 **[Open the quote bank](quotes.csv)** (GitHub shows it as a searchable table)

## Columns

| Column | What goes in it | Example |
|---|---|---|
| `id` | A short label, so the team can refer to quotes easily | `Q002` |
| `quote` | The exact line, in quotation marks | "Every late invoice is…" |
| `leader` | Who said it | Maya Chen |
| `source` | Where it came from | Webinar: Cash Flow Is a Story |
| `theme` | The topic, used to balance the posting mix | Customer reality |
| `status` | Where it is in the process (see below) | Approved |
| `used_in` | Where and when it was posted | Post 2026-11-03 |

## Statuses

| Status | Meaning | Who sets it |
|---|---|---|
| **Draft** | Pulled by AI, waiting for a human review | AI / content lead |
| **Approved** | A human confirmed it's true, specific, and on-voice | Content lead |
| **Used** | Published; don't reuse without a fresh angle | Content lead |

## Rules for a good quote

Keep a quote only if it passes all three:

1. **True:** the leader actually said it and still believes it.
2. **Specific:** it has a detail, image, or opinion, not a slogan.
3. **Sounds like them:** read it aloud. Would their team recognize the voice?

## Themes in use

Keep the mix balanced so each leader's feed tells a full story, not one note on repeat.

- Why we exist · Origin story · Customer reality · Customer value
- Sales and growth · Trust and security · Responsible finance

## Adding a quote

1. Open [`quotes.csv`](quotes.csv) and click the pencil ✏️ to edit.
2. Add a new line at the bottom, following the same pattern.
3. Wrap the quote in quotation marks (this keeps any commas inside it safe).
4. Commit with a message like `Add 3 quotes from Q4 webinar`.
