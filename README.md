# Amplify

**Human, story-led content at scale, with AI-enabled systems.**

🌐 **[Visit the website](https://maggiecurrie.github.io/amplify/)**

Every company is sitting on great content: webinars, blogs, keynotes, reports. And every leader *should* be showing up on LinkedIn. Amplify connects the two. It turns content a company already has into LinkedIn posts that leaders genuinely make their own.

> **AI does the heavy lifting. Leaders bring the story.**
> No post goes live until a human has added something only they could add.

---

## The problem

- Great content gets published once, then forgotten.
- Leaders know they should post, but don't have the time or a starting point.
- Ghostwritten and AI-written posts often sound generic, and generic erodes trust.

## The result

**One webinar → 15+ LinkedIn posts → across multiple leaders → each in their own voice → each approved by them.**

---

## How it works

| # | Step | Who leads | What happens |
|---|---|---|---|
| 1 | **Collect** | Human | Gather existing content: webinars, blogs, podcasts, keynotes, reports. |
| 2 | **Extract** | AI + Human | AI surfaces the strongest quotes and ideas. A human picks the keepers. |
| 3 | **Bank** | Human | Approved quotes go into the [quote bank](quote-bank/quotes.csv), tagged by leader, theme, and source. |
| 4 | **Draft** | AI | AI turns a quote into a post using that leader's [voice profile](voice-profiles/). |
| 5 | **Humanize** | Human | The leader adds a personal story, opinion, or detail. This is what makes it theirs. |
| 6 | **Approve & post** | Human | The leader signs off. The quote is marked as used. |

The full playbook is in **[How it works](docs/how-it-works.md)**.

## Human-led, AI-powered

| Humans lead | AI powers |
|---|---|
| Deciding what matters | Pulling quotes from long content |
| Real stories, opinions, and lived detail | First drafts in each leader's voice |
| Judgment on tone, truth, and timing | Variations and repurposing |
| The final call | Speed and volume |

---

## What's inside

| Folder | What it is |
|---|---|
| [`docs/`](docs/) | The playbook: how the system runs, week to week |
| [`quote-bank/`](quote-bank/) | The database of approved quotes, and how to use it |
| [`voice-profiles/`](voice-profiles/) | How each leader sounds, plus a blank template |
| [`prompts/`](prompts/) | Tested AI prompts for each step |
| [`checklists/`](checklists/) | The human edit and leader approval checklists |
| [`example/ledgerly/`](example/ledgerly/) | A full worked example, from webinar to published post |

## See the human difference

The [Human Edit showcase](example/ledgerly/posts/) shows an AI first draft next to the version the leader actually published, and explains every change. Open the file's **History** to see the side-by-side, red-and-green comparison.

## Try it yourself

1. Copy this repository (click **Use this template** or **Fork**).
2. Fill in a [voice profile](voice-profiles/_template.md) for each leader.
3. Drop a piece of existing content into the [extract prompt](prompts/01-extract-quotes.md).
4. Follow the six steps.

Want to submit new content for repurposing? Open an [issue](https://github.com/maggiecurrie/amplify/issues/new/choose) using the **New source content** form.

---

## Example company: Ledgerly (fictional)

This repository uses a **fictional fintech company**, Ledgerly, which helps small businesses manage cash flow and get paid faster. It has three made-up leaders:

- **Maya Chen**, CEO: visionary and warm
- **David Okafor**, Chief Revenue Officer: direct and practical
- **Priya Shah**, Chief Risk & Compliance Officer: thoughtful and steady

---

*Originally designed for a real company. This is an open, generic version with a fictional example. All names, quotes, and content here are invented.*

Built by **Mary Anne Margaret Currie (Maggie)** · [LinkedIn](https://www.linkedin.com/in/mary-anne-maggie-currie/)
*Human, story-led content at scale with AI-enabled systems.*
