# Site Change Log — Bellas Mountain Vacation Cleaning

Newest first. Each entry: what changed, where, and verification status.

---

## September 18, 2026

**Full-site link and source verification pass (Dolman)**

29 URLs checked with cache-busted curl, status asserted on every one. Two
findings, both for Chris.

**1. Idaho Springs has no service-area page.** Nine of the ten towns resolve at
`/service-areas/{town}/`. `/service-areas/idaho-springs/` returns 404. The town
is in the service area, it appears in every service list the site publishes,
and any page linking to it is pointing at a dead URL. It is also the only town
in the corridor where no competitor holds a local address advantage.

**2. `/get-a-quote/` does not exist, and should not.** The Get a Quote button
resolves to `/contact-us/`. That is correct and consistent site-wide. Recorded
so a duplicate quote page is not built later.

Also confirmed canonical: `/about/` 301s to `/bellas-cleaning/about-us/`,
`/blog/` 301s to `/bellas-cleaning/blog/`, and every root-level town URL 301s
to its `/service-areas/` page. Copy should use the canonical targets.

**Source check on the two Dolman blog drafts.** One dead citation found and
retired. The winter post had been citing `energy.gov/energysaver/thermostats`
for a 55 degree recommendation. That page returns 404 and the Department of
Energy does not publish that figure. The claim was reassigned to CSU Extension,
which does publish it. Five other claims corrected against their sources.

**Veracity blip — Legacy Anchor corrected on 7 pages**
The blip's Legacy Anchor field now carries the KGMID (`/g/11fz294ct9`) instead
of the predecessor business name.

Pages fixed: `/residential-services/weekly-bi-weekly-monthly-cleaning/`,
`/service-areas/rollinsville/`, `/residential-services/mothers-helper/`,
`/service-areas/eldora/`, `/residential-services/deep-cleaning/`,
`/service-areas/black-hawk/`, `/service-areas/golden/`.

Verified: full-site audit, 29 pages + 12 posts, zero remaining instances.

**Note:** `/entity-notary-log/` retains the historical business name in its
timeline. That is a historical record, not a blip. Correct as-is.

---

## September 17, 2026

**Google Search Console — unparsable structured data fixed**
Root cause: a duplicate `"url": "url":` key in the homepage schema's Person
node (copy-paste artifact). The malformed JSON caused Google to discard the
entire block — the LocalBusiness entity, Person node, service-area Places,
service offers, and AggregateRating were all unread.

Fixed and verified: all 5 homepage JSON-LD blocks parse clean.
**Google validation requested** — pending re-crawl confirmation.

**Facebook URL updated site-wide**
`facebook.com/BMVC2022` → `facebook.com/BellasMountainVacationCleaning`
Two locations: the schema `sameAs` field AND the Rank Math Social Meta
setting (which drives `article:publisher` on every page and post).

**About Us FAQ answer updated**
"Based in Gilpin County, Black Hawk" → "Based in Black Hawk, Colorado" plus
corridor phrasing. Updated in both the visible accordion and the FAQPage schema.

**STR Turnover schema**
"across the Boulder County mountain corridor" → "across the Colorado mountain
corridor".

**Consumer guide headline**
"Notes from fifteen Years of Cleaning Houses in Boulder County" →
"Notes from Over 15 Years of Cleaning Houses in Colorado".
Corrected in three places across two pages (blog schema ×2, guide page schema).

**About Us signed off by Sandra** — see `published/pages/`.

**GBP toggles set** — Bookings and inquiries ON; keep-profile-updated OFF;
post-on-your-behalf OFF.

**Homepage FAQ + intro** — corridor phrasing ("Black Hawk to Evergreen"),
replacing the retired "Gilpin County mountain corridor".

**Free Quote → Get a Quote** — homepage meta description and a global
Elementor button present on 21 pages.

**Site-wide schema snippet** — `knowsAbout` strings moved to corridor phrasing;
review count updated.

---

## September 12, 2026

**Site-wide schema scope swap (loop O)**
Global `#business` graph rebuilt from the Aug 29 canonical scope. Boulder
County references removed from `areaServed`, `description`, and `knowsAbout`.
Sandra approved. Verified clean.

**Blog cleanup** — 5 low-value Boulder-targeted posts 301'd to pillar content.

**Homepage we→I sweep** — 4 instances rewritten.

---

## Earlier

For Aug 6 – Sep 12, see the engagement log maintained by Cairn
(`bmvc-engagement-log.md`).