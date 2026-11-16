# Site-wide touch-up: desktop & mobile audit

- **Captured:** 16 Nov 2026, from the **live published** site (public view, no login).
- **Viewports:** desktop 1440×900. Mobile at iPhone-class width, which Wix renders on its 320px mobile canvas.
- **Evidence:** `../evidence/2026-11-16-current-live/`

**Capture limitation:** the capture machine could not reach Wix's image/font servers. Images therefore show as blank boxes and fonts fall back to a default serif. Findings below are limited to **layout order, text, spacing and structure**. Image cropping, artwork proportions and real fonts **must be re-checked in Wix Preview** during the Chrome session.

Pages audited so far: Home, Event and Conference Experiences, Consulting and Workshops. The Artists Together, Community Projects, About and Promotional Products captures timed out and need a re-run in the Chrome session.

---

## Home (`/`)

| # | Issue | View | Fix |
|---|---|---|---|
| H1 | The "Exhibitions & community projects" and "Consulting & partnerships" cards share the **same description**: "Cultural and art workshops and artist mentoring". One of them is a copy-paste error. | Both | [CONFIRM] the correct line for "Exhibitions & community projects". Suggested draft: "Exhibitions, public art and community projects with Aboriginal artists." |
| H2 | "Indigenous Promotional Products featuring artist from Artist Together" has a grammar error and the wrong program name. | Both | "Indigenous promotional products featuring artwork by Artists Together artists." |
| H3 | The "Engaging over 100 artists since 2016" heading looks clipped or overlapped by the image box on mobile. | Mobile | Move the text box fully inside its strip and re-check in Preview. |
| H4 | The "Connecting you to Aboriginal Artist on Country…" block has grammar errors and a run-on heading. | Both | Heading: "Connecting you to Aboriginal artists on Country". Sub: "Local artists · Local stories · Supporting Aboriginal people & communities". Body: "…to connect you with Aboriginal artists who can bring authentic Aboriginal artwork and stories to your project or product." "Deliverable include" → "Deliverables include". "go on to established" → "go on to establish". |
| H5 | Long body paragraphs are **centre-aligned** on mobile, which is hard to read. | Mobile | Left-align paragraphs longer than two lines. |
| H6 | Section headings mix cases: "artist development" (lowercase), "ARTISTS TOGETHER" (caps), "projects and artist outcomes" (lowercase). | Both | Use one heading style throughout (sentence case or Title Case). |
| H7 | The homepage has a footer contact form *and* "Get in Touch", and the raffle section sits just above them, so the end of the page is crowded. | Both | Optional: shorten the footer form to Name, Email, Message. Do not change form settings. |
| H8 | Three images have no alt text (10 images in total). | Both | Add descriptive alt text. |

## Event and Conference Experiences
See `event-and-conference-experiences.md` §1. The key mobile defects are that the form and footer render **above the hero**, the intro paragraph is squeezed into a narrow column, and a button label overflows.

## Consulting and Workshops
See `consulting-and-workshops.md` §1. The page still uses the old style, the copy is thin and has typos, and it has no footer block.

## Global (all pages)
| # | Item | Fix |
|---|---|---|
| G1 | The header logo image area is very large on mobile relative to the 320px canvas. | Re-check in Preview. Keep the logo at about 120–150px wide on mobile. |
| G2 | "Promotional Products", "Mission Statement" and "Values" pages exist but aren't in the main menu (they may be in sub-menus). | [CONFIRM] Intentional? Leave as is unless Malang asks. |
| G3 | The copyright/ABN line appears twice in the footer on some pages. | Keep one. |
| G4 | Mobile check for every page: section order matches desktop, no text box narrower than about 260px, buttons ≥44px tall with labels fitting, no horizontal scroll, no overlapping text. | Run in the Chrome session on each page. |

## Out of scope / do not touch
Domains, billing, apps, CMS data and schema, forms' settings and automations, analytics, the raffle ticket integration, Publish.
