# Page build spec: Consulting and Workshops

- **Live URL:** https://www.malang.org.au/clients (page slug is `clients`; nav label is "Consulting and Workshops")
- **Status:** DRAFT for client review. Nothing changed in Wix yet.
- **Rule for the Wix session:** Save and Preview only. Never Publish. Show each section to the user before saving. Do **not** change the URL slug. Changing it breaks existing links and SEO. A slug change plus 301 redirect can be a later, separate decision.

Legend:
- **[KEEP]** is existing live copy (typos corrected where noted).
- **[NEW – DRAFT]** is proposed copy that needs Malang approval.
- **[CONFIRM]** marks a fact Malang must supply. Do not invent it.

---

## 1. What is wrong today (captured 16 Nov 2026)

Evidence: `../evidence/2026-11-16-current-live/clients-{desktop,mobile}.png`

| # | Issue | Severity |
|---|---|---|
| C1 | The page still uses the **old site style** (pale blue background, orange body text, Times-style headings, navy form). It looks unfinished next to the refreshed pages. | High |
| C2 | The copy is very thin. "Cultural Awareness Training" has one sentence: "Malang offers cultural awareness training." | High |
| C3 | Typos and grammar: "lead by" → "led by"; "artist from Malang Artist Together" → "artists from Malang's Artists Together program"; "cultural enthusiast" → "cultural enthusiasts"; "tailored made" → "tailor-made". | Medium |
| C4 | There's no clear call to action per service, just one generic form at the bottom with no heading. | Medium |
| C5 | Orange body text on pale blue is likely to fail WCAG AA contrast for small text. | Medium |
| C6 | The page has no "Get in Touch" footer block, unlike the other pages, so the site is inconsistent. | Low |
| C7 | Client logos (Winc Australia, Arcadis, GrainCorp) sit under labels "Previous clients include:" / "Current clients include:", and the "Current" wording will go stale. | Low |

---

## 2. Target layout (desktop): match the Event page design system

Use the same fonts, colours, button style and section spacing as the refreshed Event and Conference Experiences page, so the two new pages look like a pair.

### S1 Hero (image strip with overlay, same treatment as the Event page hero)
- H1 [KEEP]: **Consulting and Workshops**
- Sub [NEW – DRAFT, built from the existing intro]: Tailored art workshops, Reconciliation Action Plan consultancy and cultural awareness training, led by Aboriginal artists and Malang's Artists Together program.
- Button [NEW – DRAFT]: **Enquire Now**, anchor-linked to S6.
- Image: existing `School workshop with students`. Alt text: "Students taking part in a Malang art workshop" [CONFIRM].

### S2 Intro
[KEEP] Malang offers a wide range of consulting and workshops, each tailored to meet your requirements.

### S3 Three service cards (3 columns on desktop, stacked on mobile). Each card has an image, heading, copy, "Who it's for" and a button.

**Card 1: Art Workshops**
[KEEP, typos corrected] Malang offers art workshops led by Indigenous artist Saretta Fielding and artists from Malang's Artists Together program. Schools, workplaces, community groups, art lovers and cultural enthusiasts will enjoy each tailor-made workshop.
- Who it's for [KEEP]: Schools · Workplaces · Community groups
- [CONFIRM] Format details if Malang wants them shown: duration, group size, on-site/online, materials supplied.
- Button: **Book a workshop**, linking to S6.
- Image: existing `Winc Australia Workshop`.

**Card 2: Art and Reconciliation Action Plan Consultancy**
[KEEP] Malang offers art and reconciliation action plan consultancy and support for individuals, groups, organisations and community.
- [NEW – DRAFT] Including the commissioning of original artwork to tell your organisation's reconciliation story.
  *(Basis: the homepage says Malang connects organisations with Aboriginal artists for authentic artwork. [CONFIRM] Malang is happy to describe RAP artwork this way.)*
- Button: **Discuss your RAP**, linking to S6.
- Image: existing `corporate art workshop`.

**Card 3: Cultural Awareness Training**
[KEEP] Malang offers cultural awareness training.
- [CONFIRM – required] Malang to supply 2–3 sentences: who delivers it, format (in person / online), typical length, and who it suits. **Do not publish invented detail.** Until it's supplied, the card shows the one approved sentence plus the button.
- Button: **Enquire about training**, linking to S6.
- Image: currently the Malang logo. [CONFIRM] Replace it with a training photo if one is available.

### S4 Organisations we've worked with (single logo row, greyscale, hover to colour)
- Heading [NEW – DRAFT]: Organisations we've worked with
- Logos [KEEP]: Winc Australia, Arcadis, GrainCorp.
- This replaces the separate "Previous clients include" and "Current clients include" labels (C7). [CONFIRM] Malang is happy to merge them, and whether to add logos from other pages (for example WESNET).
- Alt text: "Winc Australia logo", "Arcadis logo", "GrainCorp logo".

### S5 Testimonial (optional)
[CONFIRM] Use only an approved quote from a workshop, RAP or training client. If none is supplied, leave this section out. Do not reuse the WESNET quote here.

### S6 Enquiry
- Heading [NEW – DRAFT]: Let's tailor a workshop or program for you
- Sub [NEW – DRAFT]: Tell us a little about your group and what you'd like to achieve, and we'll be in touch.
- Keep the **existing form** and its fields (Name, Email, Phone, Subject, Message). Restyle it only to match the Event page form (light fields, dark text, outlined button).
- **Do not** change form settings, recipients, automations or connected data.

### S7 Footer
Add the same "Get in Touch" footer block the other pages use (C6). If that block is a global footer element that is hidden on this page, unhide it. Don't duplicate it.

---

## 3. Mobile-editor pass (required, separate from desktop)

1. Section order: Hero → Intro → Card 1 → Card 2 → Card 3 → Logos → Enquiry → Footer.
2. Each card stacks image → heading → copy → button. Image at full width with about a 4:3 crop. Don't stretch or distort artwork or photos.
3. Text boxes are full width minus 20px margins. Body 15–16px, left-aligned.
4. Logos go 2 per row (or 3 small), centred.
5. Buttons are at least 44px tall and the label fits on one line.
6. No horizontal scrolling. Remove empty spacer boxes.

---

## 4. Style fixes (C1 / C5)
- Body text uses the dark brand text colour on light backgrounds (not orange). Orange/terracotta only for headings, accents and buttons, where the contrast passes.
- Headings use the same font as the Event page and homepage refresh.
- Background: white or the light neutral used on refreshed pages, not the old pale blue full-page fill.

## 5. SEO & accessibility
- SEO title [NEW – DRAFT]: Aboriginal Art Workshops, RAP Consultancy & Cultural Awareness Training | Malang
- Meta description [NEW – DRAFT]: Tailored Aboriginal art workshops, Reconciliation Action Plan consultancy and cultural awareness training for schools, workplaces and community groups, led by Malang and the Artists Together program.
- One H1. Service names as H2.

## 6. Acceptance checks
- [ ] Visual style matches the Event page (fonts, colours, buttons, spacing).
- [ ] All typos in C3 corrected.
- [ ] No invented details. Every [CONFIRM] is either supplied or left out.
- [ ] Each service card has its own button that scrolls to the form.
- [ ] Mobile order correct, no narrow columns, no horizontal scroll.
- [ ] Form settings and automations unchanged.
- [ ] URL slug unchanged.
- [ ] Saved, not published.
