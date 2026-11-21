# Claude Marketing Skills

Agent skills for digital marketing work with Claude.

## Skills

| Skill | What it does |
|---|---|
| [blog-outliner](skills/blog-outliner/SKILL.md) | Builds blog post outlines researched against what ranks and what AI answers cite, anchored in what only the business can say (real prices, job stories, local conditions). Picks an angle, writes answer-first sections, keeps owner questions to 8, and plans social and Google Business Profile posts. Tuned for local service businesses; works for e-commerce too. |
| [google-business-profile](skills/google-business-profile/SKILL.md) | Audits and fixes a Google Business Profile (name, categories, description, services, service area) against the map-pack competitors, writes a month of paste-ready posts, replies to reviews (including angry and fake-looking ones), and sets up a compliant way to ask for reviews. Current with the 2025–2026 changes: Q&A removed, Ask Maps, stricter review rules. |

## Install

```bash
npx skills add parsashayegan613-tech/claude-marketing-skills@blog-outliner -g -y
npx skills add parsashayegan613-tech/claude-marketing-skills@google-business-profile -g -y
```

Restart Claude after installing. Then ask as usual, for example: "Outline a post on furnace cleaning cost in Edmonton for our client" or "Audit our client's Google Business Profile and reply to this week's reviews."

Tip: keep a `client-profile.md` in your working folder (template in `skills/blog-outliner/references/client-profile-template.md`). Both skills read the same file, so they use the client's real prices, offers and voice.
