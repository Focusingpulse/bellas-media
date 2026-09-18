# Bellas Media — Public Record

> **Visibility:** Public.
> **Created:** August 6, 2026 · **Restructured:** September 18, 2026
> **Maintained by:** Chris (Stayfound Optimized)

---

## What this repo is

The **published record** for Bellas Mountain Vacation Cleaning. Three jobs:

1. **Space log** — dated record of what shipped to the live site and when
2. **Published mirror** — the finished versions of posts, pages, and approved assets
3. **Stats surface** — feed and platform metrics tracked over time

Everything here is finished or safe to show. Sandra can read any of it without
asking.

---

## What is NOT here

Raw media, work in progress, client-identifying material, and consent records.
Those live in the private sibling repo: **`Focusingpulse/bellas-media-vault`**.

**The split rule:** unpublished, raw, or client-identifying → vault.
Published, or a metric/log → here.

---

## Structure

```
log/               What shipped, when
  site-changes.md    dated record of site work
  published-posts.md blog publishing record

feed-stats/        Tracking the feed and platform presence
  rss.md             master feed + satellite status
  cadence.md         publishing cadence (the silence risk)
  platforms.md       GBP, social, citations over time

published/         Finished material
  blog/              published posts
  pages/             published page copy
  assets/            final approved images, by category

client-dashboard/  Sandra-facing status page
```

---

## ⚠️ RULES — read before adding or changing anything

This repo is worked by more than one agent (Cairn and Dolman). These rules are
non-negotiable and apply to every commit.

### 1. The DBA is PHYSICAL-ONLY
**"Bellas House Cleaning Services"** is a real, active DBA — but it appears on
print only: cards, boards, postcards. **Never in digital media.** No website
copy, no schema, no `alternateName`, no GBP, no social profiles, no directory
listings.

*Why:* entity purity. The canonical digital entity is Bellas Mountain Vacation
Cleaning and nothing else. Print does not feed the entity graph; digital does.

### 2. Out-of-scope geography never goes in content
BMVC serves **ten** communities and nothing else:
Black Hawk, Nederland, Coal Creek Canyon, Rollinsville, Eldora, Golden Gate
area, Golden, Idaho Springs, Evergreen, Central City.

Never use as a service area: **Boulder, Boulder County, Denver, Lafayette,
Estes Park, Lyons, Sugarloaf, Ward, Fourmile Canyon.**

*Note:* an image of a property in one of those places is real — the location
data is genuine. Do not rename such an image to hide it; remove it instead.

### 3. Canonical name — no apostrophe
**Bellas Mountain Vacation Cleaning.** Never "Bella's." Applies to copy,
filenames, alt text, schema, and metadata.

### 4. Two corridor phrases, two jobs — do not swap
- **SIP / Sandra's own corridor:** "Nederland to Evergreen"
- **Broader service-area corridor:** "Black Hawk to Evergreen"
- **Retired:** "Gilpin County mountain corridor"

### 5. CTA is "Get a Quote"
Never "Free Quote."

### 6. This archive holds clean, live images only
If an image carries out-of-scope geography in its **filename, alt text, or the
pixels**, it does not belong here — even if it is currently live on the site.
Removing it from the live site is a separate content job.

### 7. Verify before you assert
Check status codes, not just content. A `301` in output means "not examined,"
never "passed."

---

## COORDINATION — this repo has more than one agent

Cairn (Chris's agent) and Dolman (Sandra's agent) both work here. On Sep 18 we
collided: Cairn pruned 7 images, Dolman re-added them, because Dolman didn't
know about an instruction given in a different conversation.

**The convention that prevents it:**

**1. Claim before you edit.**
Post an entry in `log/claims.md` with: agent name, date, files/areas you're
about to change, and why. Check it before starting.

**2. Rules live in this README, not in conversations.**
If a constraint is given in a chat, it doesn't exist for the other agent until
it's written here. When you receive a new rule, add it to the RULES section in
the same commit as the work.

**3. Conflicts: merge, don't overwrite.**
Never force-push. If you hit a rejected push, fetch and look at what the other
agent did before deciding. The other agent's log and dashboard work is usually
worth keeping even when their file changes conflict with yours.

**4. Corrections are welcome and should be explicit.**
Dolman caught Cairn's error (the dashboard claimed all 10 service-area pages
were live; Idaho Springs returns 404). That's the system working. When you
correct another agent's claim, say so plainly in the commit message.

**5. When in doubt, log the open question rather than guessing.**
A question in `log/` is cheap. A wrong edit that another agent then builds on
is not.

---

## Canonical reference

**Name:** Bellas Mountain Vacation Cleaning (no apostrophe, ever)
**Phone:** 970-212-8485
**Address:** 173 Lodge Pole Way, Black Hawk, CO 80422 (service-area business — hidden)
**Service area (10):** Black Hawk, Nederland, Coal Creek Canyon, Rollinsville,
Eldora, Golden Gate area, Golden, Idaho Springs, Evergreen, Central City
**KGMID:** /g/11fz294ct9

**Corridor language — two phrases, two jobs:**
- SIP / Sandra's own corridor: **"Nederland to Evergreen"**
- Broader service-area corridor: **"Black Hawk to Evergreen"**
- Retired: "Gilpin County mountain corridor"

**Repos:** the campaign plan and marketing strategy were moved to the private
vault on Sep 18, 2026 — they are pre-publication and belong there.