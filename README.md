# Claude Marketing Skills

Agent skills for digital marketing work with Claude.

## Skills

| Skill | What it does |
|---|---|
| [blog-outliner](skills/blog-outliner/SKILL.md) | Builds blog post outlines researched against what ranks and what AI answers cite, anchored in what only the business can say (real prices, job stories, local conditions). Picks an angle, writes answer-first sections, keeps owner questions to 8, and plans social and Google Business Profile posts. Tuned for local service businesses; works for e-commerce too. |

## Install

```bash
npx skills add parsashayegan613-tech/claude-marketing-skills@blog-outliner -g -y
```

Restart Claude after installing. Then ask for a blog outline as usual, for example: "Outline a post on furnace cleaning cost in Edmonton for our client."

Tip: keep a `client-profile.md` in your working folder (template in `skills/blog-outliner/references/client-profile-template.md`) so the skill uses the client's real prices, offers and voice.
