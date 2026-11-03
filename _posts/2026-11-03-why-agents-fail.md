---
layout: post
title: template post — to be deleted later
summary: a short demo of what a post looks like
tags: [meta]
---

This file lives at `_posts/2026-11-03-sample-post.md`. Delete it once you have
something real to publish — the writing list on the home page builds itself
from whatever is in that folder.

## How a post works

The block at the top between the `---` lines is called front matter. It is the
only part you have to get right:

```yaml
---
layout: post
title: Why agents are bad at triage
summary: one line shown under the title in the list
tags: [appsec, agents]
---
```

The filename matters too. It must be `YYYY-MM-DD-something.md`, and the
`something` part becomes the URL — so `2026-11-15-why-agents-fail.md` ends up at
`/writing/why-agents-fail/`.

## Writing in Markdown

Everything below the front matter is ordinary Markdown. You get headings,
**bold**, *italics*, `inline code`, and lists without touching any HTML:

- bullet one
- bullet two
  - nested
- bullet three

1. numbered
2. steps
3. work too

> Blockquotes render with a green rule down the left side, like this.

Code blocks are styled for the dark background:

```bash
bundle exec jekyll serve
```

## Where things live

| What | Where |
| --- | --- |
| The posts | `_posts/` |
| Page shells | `_layouts/` |
| Colours and type | `assets/css/main.css` |
| Site title, URL, author | `_config.yml` |

That's the whole system. Replace this file with your own writing.
