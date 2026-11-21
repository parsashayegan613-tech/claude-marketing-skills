# Audit & fix

The goal is not a 40-point report. It's the five to ten changes most likely to bring more calls,
in order, with the replacement text written for each one.

## What to gather

- The profile as it is now: name, primary and secondary categories, description, services,
  service area, hours, website link, photo count and the date of the latest photo, the latest
  post, rating, review count, the date of the latest review, and the share of reviews with an
  owner reply. Take these from screenshots, exports or what the user pasted. Fill in public parts
  from search if you can.
- **Competitors**: the two or three businesses that show in the map pack for "[main service]
  [city]". For each: primary category, rating, review count, how recent their reviews are. This
  is the benchmark. "You have 38 reviews" means nothing; "the three businesses above you have
  210, 160 and 95, and you get about 2 a month" tells the owner what to do.
- The website: does it agree with the profile (name, phone, hours, services, areas)? Is there a
  page for each main service?

If you couldn't see something, say so in the report rather than guessing.

## Check, in roughly this order of impact

1. **Primary category.** Is it the most specific category for the service that brings the most
   money? What do the top competitors use? A duct cleaning business listed as "HVAC contractor"
   competes with every furnace installer in town. This is often the single biggest fix.
2. **Policy risks.** Keyword-stuffed name, a service area far beyond about 2 hours' drive, an
   address that's a virtual office, services they don't offer, offers or prices or links in the
   description. Fix these before anything else: a suspension wipes out everything.
3. **Reviews.** Count, rating and recency against competitors, plus the reply rate. Unanswered
   reviews (especially negative ones) are both a trust problem and an easy fix. If the review gap
   is large, the review request process (`reviews.md`) is the real fix and belongs high on the
   list.
4. **Secondary categories.** Add the real ones competitors use; remove any that are keywords or
   things the business only *has*.
5. **Services list.** Every real service listed, each with a short description in plain words.
   Remove ones they don't offer.
6. **Description.** Rewrite it if it breaks the rules or is vague. 750 characters max; the first
   ~250 do the work. Say what they do, for whom, where, and what's different. No prices, offers,
   URLs or keyword lists.
7. **Service area / hours.** Realistic area. Hours correct, special hours set for upcoming
   holidays.
8. **Photos.** When was the last one added? Ask for real recent ones: the team, the van, jobs in
   progress, before/after. Suggest a simple habit (a few photos from jobs each week).
9. **Posts.** If the last post is months old, recommend a simple rhythm (weekly or every other
   week) and offer to write the first month (`posts.md`).
10. **Website match / Ask Maps.** Profile and site say the same things. Answers to common
    questions (areas served, what they don't do, booking) are on both. Link the service or
    location page, not just the homepage, when that's more relevant.

## Report format

```markdown
# GBP audit: [Business] — [date]

## Summary
[3–4 sentences: where they stand against competitors and the 3 changes that matter most]

## What we looked at
[Sources: screenshots / public listing / website / competitor listings. What we couldn't see.]

## Competitor snapshot
| Business | Primary category | Rating | Reviews | Latest review |
|---|---|---|---|---|

## Fixes, in priority order
### 1. [Change] — [impact: high/medium/low] · [effort: minutes/hours/ongoing]
- **Now**: [what it is]
- **Change to**: [exact new value, paste-ready]
- **Why**: [one or two lines]

[repeat]

## Paste-ready text
- **Description** ([n]/750 characters): ...
- **Services**: ...

## Questions for the owner (max 6)
1. ...

## Assumptions
- ...
```

Count characters for the description with a script (`wc -m` or Python `len`) rather than by eye.
