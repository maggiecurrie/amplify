# Adding content to the library

The library is a living thing. Every time your team publishes something (a video, a blog, a report, a post), add it here so the whole company can share it.

**Everything lives in one file: [`content.json`](content.json).** Each piece of content is one entry. Add an entry and the website updates automatically within a minute or two.

---

## How to add a piece (about 5 minutes)

1. Open [`content.json`](content.json) and click the pencil ✏️ to edit.
2. Find the line `"items": [`. Right below it, paste the template from the bottom of this page. New items go at the top.
3. Fill in each field (see the guide below).
4. Make sure there's a **comma** after your new entry's closing `}`, because it separates it from the next one.
5. Click **Commit changes**, with a message like `Add: customer video, Northfield Rowing`.

If you'd like someone to review it first, choose **Create a new branch and start a pull request** when you commit. That's the "human approves" step.

## What each field means

| Field | What to put | Example |
|---|---|---|
| `id` | A short, unique name with no spaces (used in kit links) | `northfield-rowing` |
| `title` | The content's title | `Northfield Rowing: training smarter for the national final` |
| `type` | One type, used for the filter buttons | `Customer story`, `Report`, `Webinar`, `Guide`, `Event`, `Product update`, `Culture`, `Podcast`, `Thought leadership` |
| `format` | What it is and how long | `Video · 3 min` |
| `date` | Publish date, as year-month-day | `2026-09-24` |
| `themes` | 1–3 topics, used for search and the theme filter | `["Team performance", "Athlete stories"]` |
| `headline` | 2–5 punchy words for the card | `Fastest final ever` |
| `summary` | The story in 2–3 sentences | |
| `link` | Link to the original content (or leave `""`) | |
| `quotes` | 2–3 exact quotes. Never reword them. | |
| `quoteBy` | Who said the quotes | `Mei Tanaka, Head Coach, Northfield Rowing Club` |
| `graphics` | Ready-made images, or leave `[]` and the site will make quote cards automatically | |
| `captions` | A starting caption for each role. Include at least `Anyone`. | |
| `makeItYours` | 3 quick questions that help people add their own story | |

## The one rule for captions

Every caption must include a **`[YOUR STORY: …]`** gap: a short prompt telling the person what kind of real sentence to add. The site highlights it, so nobody posts the same words as everyone else.

Use `\n` for a line break inside a caption, and `\"` for a quotation mark.

## Template

Copy everything below, including the comma at the end:

```json
    {
      "id": "short-name-here",
      "title": "Title of the content",
      "type": "Customer story",
      "format": "Video · 2 min",
      "date": "2026-12-01",
      "themes": ["Theme one", "Theme two"],
      "headline": "Punchy headline",
      "summary": "Two or three sentences: who, what happened, why it matters.",
      "link": "",
      "quotes": [
        "First exact quote.",
        "Second exact quote."
      ],
      "quoteBy": "Name, Role, Company",
      "graphics": [],
      "captions": {
        "Sales": "Hook line.\n\n[YOUR STORY: one sentence about a customer you've talked to who felt the same way.]\n\nThe point, and a link in the comments.",
        "Leadership": "Hook line.\n\n[YOUR STORY: one sentence on why this matters to you.]\n\nThe bigger point.",
        "Customer Success": "Hook line.\n\n[YOUR STORY: one sentence about a customer you've supported.]",
        "Anyone": "Simple, proud intro.\n\n[YOUR STORY: one sentence on why this made you proud.]"
      },
      "makeItYours": [
        "Question one?",
        "Question two?",
        "Question three?"
      ]
    },
```

## Adding your own graphics

1. Upload the image to the [`assets/`](assets/) folder (**Add file** → **Upload files**). Use 1080 × 1080 PNGs for LinkedIn.
2. In the entry, list it under `graphics`:

```json
      "graphics": [
        {"file": "assets/your-image.png", "label": "Short label"}
      ],
```

## Something broke?

If the library shows "couldn't load," there's usually a missing comma or quotation mark in `content.json`. Open the file's history, compare it with the last version that worked, and look for the typo. Or paste the file into Claude and ask it to find the mistake.
