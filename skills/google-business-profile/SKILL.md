---
name: google-business-profile
description: >
  Manage a local business's Google Business Profile (GBP, formerly Google My Business) the way
  a good local SEO would: audit and fix the profile (name, categories, description, services,
  service area, hours, photos), write a month of paste-ready posts, reply to reviews (including
  angry and fake-looking ones), and set up a compliant way to ask customers for reviews. Built
  for local service businesses (trades, home services, cleaning, grooming, clinics, salons) and
  current with the 2025–2026 changes (Q&A removed, Ask Maps, stricter review rules). Use this
  whenever the user mentions a Google Business Profile, GBP, Google My Business, GMB, the Google
  Maps listing, the map pack, Google reviews, review replies, asking for reviews, or Google
  posts for a business, even if they only say "our Google listing" or "help with reviews".
---

# Google Business Profile

For a local service business, the Google Business Profile is often the first thing a customer
sees and the thing that decides whether they call. It is also where most small businesses leave
the easiest wins on the table: the wrong primary category, a description full of things Google
doesn't allow, half the reviews unanswered, no photos since last year.

This skill covers four jobs. Work out which one the user wants (it may be more than one) and
go straight to it:

| Job | The user says something like | Read |
|---|---|---|
| **Audit & fix** | "audit our profile", "why aren't we in the map pack", "optimize our listing" | `references/audit-checklist.md` |
| **Posts** | "write our Google posts", "posts for December", "keep the profile active" | `references/posts.md` |
| **Review replies** | "reply to these reviews", "someone left a 1-star", "is this review fake" | `references/reviews.md` |
| **Getting reviews** | "how do we get more reviews", "write a review request text" | `references/reviews.md` |

Always read `references/rules.md` too. Google's rules decide what can go in each field, and
breaking them can get a profile suspended, which is far worse than any ranking problem. The
rules also changed a lot in 2025–2026, so don't rely on older habits (seeding Q&A, review
kiosks, discounts for reviews).

## 1. Load context

Look for a client profile before asking anything: a path the user gave, `client-profile.md` or
`clients/<name>/client-profile.md` in the working directory, or `.marketing/client-profile.md`.
Treat what it says as answered: services, prices, real offers, service area, voice, and words to
avoid. Words to avoid apply to everything you write, including variants ("cheap" bans
"cheaper").

Also use whatever the user provided: screenshots or exports of the profile, a list of reviews,
the website. If you can search the web, look up the business and two or three competitors that
show in the map pack for its main service + city. Public results usually show the rating,
review count, primary category, hours and recent photos; they don't show secondary categories,
the services list, or the dashboard. Say which parts you saw and which you couldn't.

If there's no client profile and this looks like ongoing work for the business, offer at the end
to save one using `references/client-profile-template.md`. Don't hold up the current job for it.

## 2. Do the job

Follow the matching reference file. The principles that apply to all four:

- **Paste-ready.** Whatever you write (a description, a post, a reply, a review request) should
  be ready to copy into Google or a text message as-is, with the character count shown where
  Google has a limit. The owner shouldn't have to edit it to make it usable.
- **Specific beats generic.** Real services, real neighbourhoods, the actual problem the customer
  had. "Thanks for the kind words!" on every review, or a post that says "We offer quality
  service", does nothing for customers or for Google.
- **Never invent.** No made-up offers, prices, guarantees, years in business, certifications or
  facts about a customer's visit. If a post would need an offer and none exists, write it as an
  Update instead, or ask. If a reply needs a fact you don't have, leave a clearly marked blank.
- **Policy before ranking.** If a tactic would help rankings but breaks Google's rules (keywords
  in the business name, incentives for reviews, a fake address), say no, explain the risk in one
  line, and give the compliant alternative.
- **Plain about Google's changes.** In anything the client or owner will read, say what's true
  now ("Google removed Q&A from profiles") without stacking up dates and announcements you
  can't point to. Precise dates belong only where they matter, like a deadline.
- **Prioritise.** Owners do the top three things on a list and stop. Put the change most likely
  to bring calls first, and say why.

## 3. Owner questions: few and specific

Some things only the owner knows: whether they really offer a service, what happened with an
angry customer, whether an offer is real. Keep these to **at most 6 questions** in one numbered
list, written so it could be pasted into a single text. If you were told to make the calls
yourself, make them and list them under "Assumptions" instead of asking.

## 4. Save and summarise

Save the work as markdown: `gbp/<business-slug>-<job>.md` in the working directory (for example
`gbp/riverbend-plumbing-posts-2026-12.md`), or wherever the user asked. Then give a short summary
in chat: the top changes or the content produced, anything you refused and why, and the owner
questions ready to paste.

## Related

If the business also has a blog, every good post can become a GBP post (one useful point + link
to the article). If a blog outline or post exists, use it as raw material for posts.
