# How it works: the playbook

This is the operating rhythm of Amplify: who does what, when, and what "good" looks like at each step.

**The one rule:** AI never publishes. It drafts, sorts, and suggests. A human decides.

---

## Roles

| Role | Responsibility | Time per week |
|---|---|---|
| **Content lead** (usually marketing) | Runs the system, curates quotes, prepares drafts | 2–4 hours |
| **Leader** (CEO, CRO, etc.) | Adds their story, approves posts | 15–20 minutes |
| **AI assistant** | Extracts quotes, drafts posts, suggests variations | Minutes |

The system is designed so the leader's time goes *only* where it matters most: their own stories and their final call.

---

## Step 1: Collect

**Goal:** Know what content you already have.

- Gather webinars, podcasts, keynotes, blogs, reports, internal all-hands talks, and customer interviews.
- Long-form, spoken content (transcripts) is the richest source. People say things out loud they'd never write.
- Log each piece with a short name, date, and which leaders appear in it.

**Good looks like:** a list of 5–10 source pieces, each with a transcript or text version.

## Step 2: Extract

**Goal:** Find the lines worth repeating.

- Run each source through the [extract prompt](../prompts/01-extract-quotes.md).
- AI returns candidate quotes, each tagged with the speaker and a theme.
- **Human step:** the content lead reads every candidate and keeps only the ones that are true, specific, and sound like the person who said them. Expect to keep about one in three.

**Good looks like:** quotes that make you nod, or make you want to argue. Cut anything that sounds like a slogan.

## Step 3: Bank

**Goal:** Build a reusable library, so nothing good is used once and lost.

- Add approved quotes to the [quote bank](../quote-bank/quotes.csv).
- Tag every quote with its leader, source, theme, and status.
- See the [quote bank guide](../quote-bank/README.md) for the tagging rules.

**Good looks like:** at least 4 approved quotes per leader per month of planned posting.

## Step 4: Draft

**Goal:** Give the leader a strong starting point, not a finished post.

- Pick a quote marked **Approved**.
- Run it through the [draft prompt](../prompts/02-draft-post.md) with that leader's [voice profile](../voice-profiles/).
- The draft deliberately includes a **[STORY GAP]**: a marked spot where only the leader can add a real moment.

**Good looks like:** a draft that sounds like the leader on a good day, with an obvious place for their story.

## Step 5: Humanize

**Goal:** Make it theirs. This is the step that matters most.

- Send the leader the draft plus 2–3 questions from the [story prompts](../prompts/03-story-questions.md). For example: *"When did you last see this happen with a customer?"*
- The leader answers in a quick voice note, a chat message, or a 10-minute call. They don't have to write anything.
- The content lead works their answer into the draft, then runs the [human edit checklist](../checklists/human-edit-checklist.md).

**Good looks like:** a post with a detail no AI could have invented.

## Step 6: Approve & post

**Goal:** The leader signs off, every time.

- The leader reviews the final post using the [approval checklist](../checklists/leader-approval-checklist.md).
- They post it themselves, or approve scheduling.
- The content lead updates the quote's status to **Used** and notes where it was used.

**Good looks like:** the leader says "yes, that's me," and means it.

---

## Weekly rhythm

| Day | What happens |
|---|---|
| **Monday** | Content lead picks next week's quotes and drafts posts (Step 4) |
| **Tuesday** | Story questions go to leaders (Step 5) |
| **Wednesday–Thursday** | Leaders reply; content lead finalizes (Step 5) |
| **Friday** | Leaders approve; posts are scheduled (Step 6) |
| **Monthly** | New source content is collected and extracted (Steps 1–3) |

---

## What to measure

- **Posting consistency:** posts per leader per month
- **Engagement quality:** comments and conversations, not just likes
- **Reuse rate:** how many posts each source piece produced
- **Leader time:** minutes per post (keep it low)
- **Edit depth:** how much the human changed the AI draft (more is a good sign)
