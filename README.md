# SEO Meta Writer — custom GPT

A focused ChatGPT custom GPT that writes SEO-optimized **meta titles** and **meta
descriptions** — within length limits, with 3 variants each, in the user's language.
Paste a page topic, content, keyword, or URL and get ready-to-use meta tags with character
counts.

## What it does

- 3 meta **title** options, 50–60 characters, with live character counts
- 3 meta **description** options, 140–155 characters, with character counts
- Reads a pasted URL (web browsing on) to ground suggestions in the real page
- Writes in the same language as the input
- Stays on task — meta tags only, no fabricated facts or clickbait

## Repository contents

| Path | Purpose |
|------|---------|
| `gpt-config.md` | Full GPT configuration: name, description, instructions, conversation starters, capabilities, and the OpenAI submission answers |
| `store/icon.png` | 512×512 GPT icon (SERP-snippet motif) |
| `store/privacy.html` | Privacy policy (no data collected) |
| `store/terms.html` | Terms of service (free, as-is) |
| `store/scenes/icon.html` | Source scene used to render the icon |

## Privacy

The GPT collects **no** personal data. It only reads the text you type into the
conversation to generate meta tags, runs no custom Actions, and calls no third-party APIs of
its own. Conversations are processed by OpenAI under OpenAI's own privacy policy.

- Privacy policy: https://bartoszkoplin.pl/seo-meta-writer-privacy/
- Terms of service: https://bartoszkoplin.pl/seo-meta-writer-terms/

## Author

Built by [Bartosz Koplin](https://bartoszkoplin.pl/). Contact: kontakt@bartoszkoplin.pl
