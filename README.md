# JR Landscaping LLC — spec-site preview

- **Suggested slug:** `jrlandscaping`
- **Target host (not live, do not claim it is):** jrlandscaping.capitalreconsulting.com
- **Current public site:** https://www.jrlandscapesllc.com/
- **Site path:** `/workspace/previews/jrlandscaping/index.html`
- **One-line note (Outreach):** Replaced the Mobile OPZ brochure with a Denver dusk-yard site for Gustavo Gallegos — Bryant Street, click-to-call 720-603-6785, Brandy on About, and their own backyard photo.

This folder is a static preview only. Do not deploy. Do not treat the target host as live.

## What changed vs their current site

Stripped the dated Duda / Mobile OPZ chrome, empty Reviews page, and gallery dump. Rebuilt a mobile-first four-page shop in pine / clay / limestone taken from their twilight backyard photo (Fraunces + Manrope), with click-to-call, mailto, a sticky mobile call bar, and JSON-LD limited to facts printed on their pages or their own Google Maps embed.

Their homepage title typo is kept only as a quoted line: “No Job to Big”. The hero headline is written correctly.

## Facts used (with sources)

| Fact | Source |
| --- | --- |
| Brand **JR Landscaping LLC** / **JR Landscapes** | Header/footer on every live page; logo wordmark |
| Owner **Gustavo Gallegos** — Owner \| Founder \| Contractor | https://www.jrlandscapesllc.com/about |
| Office manager **Brandy Carmona** + her process quote | /about |
| Phone **720-603-6785** / `tel:+17206036785` | Header/footer every page |
| Email **Jrlandscapesllc3@gmail.com** | Header/footer every page |
| Address **5750 Bryant St, Denver, CO 80221** | Header/footer every page |
| Values **Knowledge, Honesty & Service** · quality work at affordable prices | Homepage |
| Homepage title **No Job to Big or Small** (typo kept as a quote) | Homepage `<title>` / H1 area |
| Services: landscaping, concrete (stamped & colored), fencing (wood, PVC, stain/waterproof) | Home + https://www.jrlandscapesllc.com/services |
| Landscaping list: outdoor kitchens, fire pits, water features, retaining walls, sprinkler systems, lighting, planters | /services |
| Concrete: demo, sidewalks, driveways, patios; specialty stamped/colored | /services |
| Fencing: new install or repair; wood, PVC, other; **over 10 years’** experience; stain & waterproof | /services |
| Year-round Denver metro; “We do it All”; free estimate if a project isn’t listed | /services and home |
| Gustavo personally guides planning, designing, constructing | /about |
| Contact pitch: call or fill out the form to get the ball rolling | https://www.jrlandscapesllc.com/contact |
| Form fields Name, Phone, Email, Message | /contact |
| Facebook `profile.php?id=100083057974969` | Homepage social hub |
| Google Maps pin 39.8009664, −105.0181736 | Homepage maps embed / `g.page/JRlLandscapesLLC` |
| Hero photo: twilight backyard (fire pit, pavers, waterfall, uplit pines) | Homepage `Homepage-Main-JR Landscaping` |
| Footer credit **Dev by: Mobile OPZ** (reason this site exists) | Every live page |

## Facts deliberately omitted

- **Reviews** — live /reviews page is empty; Angi 5.0 / 4 reviews and BBB copy were not used.
- **Hours** — not printed on their pages (Angi lists Mon–Sat hours; omitted).
- **Founding date 07/03/2018** and extra BBB service list — BBB schema only; not on their site.
- **“18 years of experience”** — Angi only; their site says “years of experience” and “over 10 years” for fencing.
- **Fully-insured / BBB badge images** — template badges on the Duda page with no supporting sentence; no license or insured claim in body copy.
- **Gallery dump** — they have a full /gallery; this preview uses **one** compressed homepage photo (`assets/yard.jpg`, 1200×800, ~188 KB).
- **About headshots** of Gustavo and Brandy — exist on /about; unused because of the one-photo rule.
- **Clip-art lime/cyan logo** — black-box PNG; header uses a type mark instead.
- **“Keep on touch!”** contact typo — not repeated.
- **Google review button / GTM IDs / share-by Twitter** — chrome, not copy.
- **Any claim this preview is live** at jrlandscaping.capitalreconsulting.com.

## Pages

- `index.html` — dusk hero, corrected headline + quoted typo, three trades, Gustavo, estimate ticket
- `services.html` — landscaping list, concrete specialties, fencing (10+ years)
- `about.html` — Gustavo bio; Brandy Carmona + her published quote
- `contact.html` — click-to-call, mailto, Bryant St, Facebook, Maps, estimate form (mailto)

Quote form opens a mail draft to Jrlandscapesllc3@gmail.com. It does not post to the Mobile OPZ site.

## Images

One photo: `assets/yard.jpg` (their homepage hero, compressed to 1200×800 JPEG, 187 KB). Favicon is SVG type. No 1MB+ originals kept.

## Blockers

- Reviews page is empty.
- Hours, insurance, and license are not printed as copy on the live pages.
- Gallery exists but was not reused beyond the single homepage frame.
