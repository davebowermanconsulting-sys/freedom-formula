# Website Changes Report

## 1. Summary

This report covers the website work agreed at the latest meeting with the Saretta Art & Design team:

- **Finish the last two pages** in the main menu: *Event and Conference Experiences* and *Consulting and Workshops*.
- **Full website touch-up**, with the site laid out correctly on **desktop and mobile**.

**Where things stand (16 November 2026):** the live site has been reviewed on desktop and mobile, and every change below is specified section by section, ready to build in the Wix Editor. **No changes have been made to the live website yet.** All edits will be saved and previewed for Malang's approval before anything is published.

| Area | Main problems found | What we will change | Priority |
|---|---|---|---|
| Event and Conference Experiences | On phones, the enquiry form and footer show **above** the page heading; one paragraph is squeezed to about two words a line; a button label is cut off; two competing forms; service offerings are an image | Re-order the mobile layout, widen text, fix buttons, keep one enquiry form, rebuild offerings as editable text, add "How it works" | High |
| Consulting and Workshops | Still in the **old design**; very little copy; typos; no call to action per service; no footer block | Restyle to match the refreshed pages, three service cards with their own buttons, copy fixes, client logo row, footer | High |
| Homepage | Two cards share the same description; grammar errors; long centred paragraphs on mobile; inconsistent heading styles | Copy corrections, left-align body text on mobile, one heading style | Medium |
| Whole site | Mobile layouts not checked page by page; missing image descriptions (alt text) | Mobile pass on every page, alt text, spacing and button sizes | Medium |

**Information we need from Malang:** a 2–3 sentence description of Cultural Awareness Training; confirmation of the event service offerings; any second event case study (with an approved quote); the correct description for the "Exhibitions & community projects" homepage card; and approval of the draft copy marked *[NEW – DRAFT]*.

**How to read the specs:** *[KEEP]* is existing approved wording; *[NEW – DRAFT]* is proposed wording for Malang to approve; *[CONFIRM]* means Malang must supply or confirm the detail before it goes live. We will not invent client names, statistics or quotes.

**About the screenshots:** they were taken from the live public website on 16 November 2026. Photos and the custom fonts don't appear because of how the screenshots were captured. The site itself shows them normally. The screenshots show layout, order and text only.

## 2. Before: key issues at a glance

<div class="figs"><figure><img src="file:///home/user/freedom-formula/malang/evidence/figures/event-mobile-form-above-hero.jpg"><figcaption>Event page on a phone: the form and footer appear before the page heading</figcaption></figure><figure><img src="file:///home/user/freedom-formula/malang/evidence/figures/event-mobile-narrow-paragraph.jpg"><figcaption>Event page on a phone: intro paragraph squeezed into a narrow column</figcaption></figure><figure><img src="file:///home/user/freedom-formula/malang/evidence/figures/consulting-mobile-current.jpg"><figcaption>Consulting and Workshops on a phone: old design and thin copy</figcaption></figure></div>


<div class="figs"><figure><img src="file:///home/user/freedom-formula/malang/evidence/figures/consulting-desktop-current.jpg"><figcaption>Consulting and Workshops on desktop: old style, orange body text on pale blue</figcaption></figure><figure><img src="file:///home/user/freedom-formula/malang/evidence/figures/home-mobile-sections.jpg"><figcaption>Homepage on a phone: two cards share the same description</figcaption></figure></div>


<div class="pb"></div>

## 3. Event and Conference Experiences


- **Live URL:** https://www.malang.org.au/event-and-conference-experiences
- **Nav label:** Event and Conference Experiences (unchanged)
- **Status:** DRAFT for client review. Nothing changed in Wix yet.
- **Rule for the Wix session:** Save and Preview only. Never Publish. Show each section to the user before saving.

Legend:
- **[KEEP]** is existing live copy. Re-use it word for word.
- **[NEW – DRAFT]** is proposed copy that needs Malang approval.
- **[CONFIRM]** marks a fact that Malang must supply or confirm before the change goes live. Do not invent it.

---

### 1. What is wrong today (captured 16 Nov 2026)

Evidence: `evidence/2026-11-16-current-live/event-and-conference-experiences-{desktop,mobile}.png`

Note: images show as blank boxes in these captures because the capture machine could not reach Wix's image server. That is a limitation of the capture, not a site fault.

| # | Issue | Where | Severity |
|---|---|---|---|
| E1 | On mobile, the closing CTA, the event enquiry form, the "Get in Touch" footer and its contact form all render **above** the hero. A phone visitor lands on a form before they know what the page is. | Mobile | High |
| E2 | The intro paragraph ("Malang partners with organisations…") is squeezed into a very narrow column on mobile, about two words per line. | Mobile | High |
| E3 | The "Enquire About Your Event" button label overflows the button edge on mobile. | Mobile | Medium |
| E4 | There are two forms on one page: the event enquiry form and the site-wide footer contact form. Visitors can't tell which one to use, and enquiries are split. | Desktop + mobile | Medium |
| E5 | "Our signature experiences" appears to be a single image (`Malang_Event_Service_Offerings`). Text inside an image can't be read by Google or screen readers, can't be edited, and is unreadable at phone width. | Desktop + mobile | Medium |
| E6 | The hero heading text is duplicated in the page structure (likely a hidden desktop/mobile copy). Keep exactly one H1. | SEO | Low |
| E7 | There are empty text boxes containing only zero-width characters (stray spacing blocks). | Desktop + mobile | Low |
| E8 | There is only one case study (WESNET). The page relies on a single proof point. | Content | Medium – needs client input |

---

### 2. Target layout (desktop, top to bottom)

#### S1 Hero (full-width strip, image background with dark overlay at 40–50% so white text passes contrast)
- H1 [KEEP]: **Aboriginal Cultural Experiences for Events & Conferences**
- Sub-heading [KEEP]: Connecting artists, culture and events through meaningful experiences
- Supporting line [KEEP]: Malang works with Aboriginal artists across Australia, enabling scalable delivery for events of all sizes.
- Primary button [KEEP label]: **Enquire About Your Event**. Anchor-link it to S7 (the enquiry form) on the same page.
- Image: keep the current hero image (`54788667339_2d4ef4508c_o_edited.jpg`). Alt text [NEW – DRAFT]: "Aboriginal artwork and cultural activation at an event delivered by Malang" [CONFIRM it describes the photo].

#### S2 Intro (single centred text block, max width about 760px)
[KEEP] Malang partners with organisations to deliver authentic Aboriginal cultural experiences for events, bringing together artists, storytelling, design, and products into a seamless and impactful offering.

[KEEP] With extensive experience in event production and project delivery, Malang ensures seamless delivery across design, product, and on-site activation.

#### S3 Our signature experiences (native text, 3-column cards on desktop, 1 column on mobile)
Intro line [KEEP]: Our signature experiences are designed to engage audiences, create memorable moments, and extend the impact of your event.

Rebuild the content of the `Malang_Event_Service_Offerings` image as **native, editable Wix text cards**. The Wix session must open that image in the editor and transcribe its wording exactly. If the image wording differs from the draft cards below, the image wording wins.

Draft cards, based only on services already described elsewhere on malang.org.au:

1. **Cultural event branding & artwork** [NEW – DRAFT]
   Original artwork and design by Aboriginal artists for your event identity: stage, screens, signage, programs and digital assets.
   *(Evidence: WESNET case study, "Cultural event branding & artwork".)*
2. **Delegate gifts & event products** [NEW – DRAFT]
   Commemorative and corporate gifts, uniforms, signage and promotional products featuring artwork by Artists Together artists.
   *(Evidence: homepage deliverables list and the Promotional Products page.)*
3. **Live art & cultural workshops** [NEW – DRAFT]
   Interactive art workshops and artist-led activations that give delegates a hands-on cultural experience.
   *(Evidence: the Consulting and Workshops page lists art workshops led by Saretta Fielding and Artists Together artists.)* [CONFIRM workshops are offered at events.]

[CONFIRM] Any other offerings (for example, artist talks, live painting, installations). Do **not** add Welcome to Country or Smoking Ceremony unless Malang confirms how these are arranged with Traditional Owners. Malang should not appear to offer them itself.

#### S4 Case study: WESNET (keep the existing coloured band and slideshow)
- Title [KEEP]: Case Study: WESNET
- Sub [KEEP]: Global Network of Women's Shelters
- Tag [KEEP]: Cultural event branding & artwork
- Quote [KEEP, verbatim, never shorten]: "Her work is not only visually stunning but deeply meaningful, bringing layers of cultural storytelling that truly enhanced the experience for our audience." — Natalie, Event Coordinator, WESNET
- [CONFIRM] Event name, year and location for one context line, for example "[Event name], [City], [Year]". Leave it out if not supplied.
- [CONFIRM] Add a second case study if Malang has one with an approved quote and images. Use the same card design.

#### S5 Artists (2-column: image left, text right)
[KEEP] Malang works with leading Aboriginal artists across Australia, including Saretta Fielding, delivering cultural experiences from concept through to completion.

Secondary button [NEW – DRAFT]: **Meet our artists**, linking to /artist-together.

#### S6 How it works (4 numbered steps, horizontal on desktop, stacked on mobile) [NEW – DRAFT]
1. **Tell us about your event.** Share your date, audience size and goals.
2. **Concept & artist match.** We connect you with the right artist and shape a concept with you.
3. **Design & production.** Artwork, products and activations are developed and approved.
4. **Delivery on the day.** Malang coordinates delivery and on-site activation.

[KEEP] We recommend engaging early to align artwork, products and event timelines.

#### S7 Enquiry (anchor target for all "Enquire" buttons)
- Heading [KEEP]: Let's create a culturally rich and meaningful experience for your next event
- Form heading [KEEP]: Tell us about your event
- Keep the **existing** form exactly as it is (Name, Organisation, Email, Phone, Event Type, Event Date, Message, Submit).
- **Do not** change the form's settings, recipients, automations or submission destination. Layout and position only.

#### S8 Footer
- On **this page only**, hide the site-wide footer contact form (First/Last Name, Email, Message, Phone, Send) so there is a single enquiry route. Keep the "Get in Touch" address block and ABN line.
- If the footer form is a master/global element, do not delete it. Ask the user whether to hide it on this page or leave it.

---

### 3. Mobile-editor pass (required, separate from desktop)

Do this in the Wix **mobile editor** after desktop is approved.

1. **Re-order sections** to match the desktop order: S1 Hero → S2 → S3 → S4 → S5 → S6 → S7 form → S8 footer. *(Fixes E1.)*
2. Set every text box to **full width minus 20px side margins** (about 280px on the 320px mobile canvas). *(Fixes E2.)*
3. Widen buttons to at least 260px, or reduce the label font size, so "Enquire About Your Event" fits on one line. *(Fixes E3.)*
4. Font sizes: H1 28–32px, H2 22–24px, body 15–16px, line height about 1.5. Body text left-aligned (centred only for one-line headings).
5. S3 cards stack into one column. S6 steps stack vertically.
6. Hero: make sure the overlay keeps the white text readable over the image.
7. Delete empty spacer/text boxes (E7). Keep about 40px of vertical padding between sections.
8. Check the hamburger menu opens and the page title is visible under the header.
9. Preview on a narrow phone width and confirm there is no horizontal scrolling.

---

### 4. SEO & accessibility
- Page SEO title [NEW – DRAFT]: Aboriginal Cultural Experiences for Events & Conferences | Malang
- Meta description [NEW – DRAFT]: Malang works with Aboriginal artists across Australia to deliver cultural event branding, artwork, products and on-site experiences for events and conferences of all sizes.
- One H1 only (S1). Section headings as H2.
- Every image needs alt text describing what is shown. Logos: "[Organisation] logo". Purely decorative images: mark them decorative.

### 5. Acceptance checks for this page
- [ ] Desktop order matches section 2.
- [ ] Mobile order matches desktop (form is not above the hero).
- [ ] No text column narrower than about 260px on mobile.
- [ ] Button labels fit inside their buttons on mobile.
- [ ] Exactly one enquiry form on the page.
- [ ] Offerings are native text, not an image.
- [ ] WESNET quote is verbatim.
- [ ] Form settings and automations unchanged.
- [ ] Saved, not published. The live site is unchanged.

<div class="pb"></div>

## 4. Consulting and Workshops


- **Live URL:** https://www.malang.org.au/clients (page slug is `clients`; nav label is "Consulting and Workshops")
- **Status:** DRAFT for client review. Nothing changed in Wix yet.
- **Rule for the Wix session:** Save and Preview only. Never Publish. Show each section to the user before saving. Do **not** change the URL slug. Changing it breaks existing links and SEO. A slug change plus 301 redirect can be a later, separate decision.

Legend:
- **[KEEP]** is existing live copy (typos corrected where noted).
- **[NEW – DRAFT]** is proposed copy that needs Malang approval.
- **[CONFIRM]** marks a fact Malang must supply. Do not invent it.

---

### 1. What is wrong today (captured 16 Nov 2026)

Evidence: `evidence/2026-11-16-current-live/clients-{desktop,mobile}.png`

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

### 2. Target layout (desktop): match the Event page design system

Use the same fonts, colours, button style and section spacing as the refreshed Event and Conference Experiences page, so the two new pages look like a pair.

#### S1 Hero (image strip with overlay, same treatment as the Event page hero)
- H1 [KEEP]: **Consulting and Workshops**
- Sub [NEW – DRAFT, built from the existing intro]: Tailored art workshops, Reconciliation Action Plan consultancy and cultural awareness training, led by Aboriginal artists and Malang's Artists Together program.
- Button [NEW – DRAFT]: **Enquire Now**, anchor-linked to S6.
- Image: existing `School workshop with students`. Alt text: "Students taking part in a Malang art workshop" [CONFIRM].

#### S2 Intro
[KEEP] Malang offers a wide range of consulting and workshops, each tailored to meet your requirements.

#### S3 Three service cards (3 columns on desktop, stacked on mobile). Each card has an image, heading, copy, "Who it's for" and a button.

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

#### S4 Organisations we've worked with (single logo row, greyscale, hover to colour)
- Heading [NEW – DRAFT]: Organisations we've worked with
- Logos [KEEP]: Winc Australia, Arcadis, GrainCorp.
- This replaces the separate "Previous clients include" and "Current clients include" labels (C7). [CONFIRM] Malang is happy to merge them, and whether to add logos from other pages (for example WESNET).
- Alt text: "Winc Australia logo", "Arcadis logo", "GrainCorp logo".

#### S5 Testimonial (optional)
[CONFIRM] Use only an approved quote from a workshop, RAP or training client. If none is supplied, leave this section out. Do not reuse the WESNET quote here.

#### S6 Enquiry
- Heading [NEW – DRAFT]: Let's tailor a workshop or program for you
- Sub [NEW – DRAFT]: Tell us a little about your group and what you'd like to achieve, and we'll be in touch.
- Keep the **existing form** and its fields (Name, Email, Phone, Subject, Message). Restyle it only to match the Event page form (light fields, dark text, outlined button).
- **Do not** change form settings, recipients, automations or connected data.

#### S7 Footer
Add the same "Get in Touch" footer block the other pages use (C6). If that block is a global footer element that is hidden on this page, unhide it. Don't duplicate it.

---

### 3. Mobile-editor pass (required, separate from desktop)

1. Section order: Hero → Intro → Card 1 → Card 2 → Card 3 → Logos → Enquiry → Footer.
2. Each card stacks image → heading → copy → button. Image at full width with about a 4:3 crop. Don't stretch or distort artwork or photos.
3. Text boxes are full width minus 20px margins. Body 15–16px, left-aligned.
4. Logos go 2 per row (or 3 small), centred.
5. Buttons are at least 44px tall and the label fits on one line.
6. No horizontal scrolling. Remove empty spacer boxes.

---

### 4. Style fixes (C1 / C5)
- Body text uses the dark brand text colour on light backgrounds (not orange). Orange/terracotta only for headings, accents and buttons, where the contrast passes.
- Headings use the same font as the Event page and homepage refresh.
- Background: white or the light neutral used on refreshed pages, not the old pale blue full-page fill.

### 5. SEO & accessibility
- SEO title [NEW – DRAFT]: Aboriginal Art Workshops, RAP Consultancy & Cultural Awareness Training | Malang
- Meta description [NEW – DRAFT]: Tailored Aboriginal art workshops, Reconciliation Action Plan consultancy and cultural awareness training for schools, workplaces and community groups, led by Malang and the Artists Together program.
- One H1. Service names as H2.

### 6. Acceptance checks
- [ ] Visual style matches the Event page (fonts, colours, buttons, spacing).
- [ ] All typos in C3 corrected.
- [ ] No invented details. Every [CONFIRM] is either supplied or left out.
- [ ] Each service card has its own button that scrolls to the form.
- [ ] Mobile order correct, no narrow columns, no horizontal scroll.
- [ ] Form settings and automations unchanged.
- [ ] URL slug unchanged.
- [ ] Saved, not published.

<div class="pb"></div>

## 5. Full website touch-up: desktop & mobile


- **Captured:** 16 Nov 2026, from the **live published** site (public view, no login).
- **Viewports:** desktop 1440×900. Mobile at iPhone-class width, which Wix renders on its 320px mobile canvas.
- **Evidence:** `evidence/2026-11-16-current-live/`

**Capture limitation:** the capture machine could not reach Wix's image/font servers. Images therefore show as blank boxes and fonts fall back to a default serif. Findings below are limited to **layout order, text, spacing and structure**. Image cropping, artwork proportions and real fonts **must be re-checked in Wix Preview** during the Chrome session.

Pages audited so far: Home, Event and Conference Experiences, Consulting and Workshops. The Artists Together, Community Projects, About and Promotional Products captures timed out and need a re-run in the Chrome session.

---

### Home (`/`)

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

### Event and Conference Experiences
See `event-and-conference-experiences.md` §1. The key mobile defects are that the form and footer render **above the hero**, the intro paragraph is squeezed into a narrow column, and a button label overflows.

### Consulting and Workshops
See `consulting-and-workshops.md` §1. The page still uses the old style, the copy is thin and has typos, and it has no footer block.

### Global (all pages)
| # | Item | Fix |
|---|---|---|
| G1 | The header logo image area is very large on mobile relative to the 320px canvas. | Re-check in Preview. Keep the logo at about 120–150px wide on mobile. |
| G2 | "Promotional Products", "Mission Statement" and "Values" pages exist but aren't in the main menu (they may be in sub-menus). | [CONFIRM] Intentional? Leave as is unless Malang asks. |
| G3 | The copyright/ABN line appears twice in the footer on some pages. | Keep one. |
| G4 | Mobile check for every page: section order matches desktop, no text box narrower than about 260px, buttons ≥44px tall with labels fitting, no horizontal scroll, no overlapping text. | Run in the Chrome session on each page. |

### Out of scope / do not touch
Domains, billing, apps, CMS data and schema, forms' settings and automations, analytics, the raffle ticket integration, Publish.

<div class="pb"></div>

## 6. Next steps

1. **Malang reviews this report** and supplies the items marked *[CONFIRM]*.
2. **We build the changes in the Wix Editor**, one page at a time: desktop first, then a separate mobile-editor pass.
3. **Save and Preview only.** Malang reviews the preview on desktop and phone.
4. **Malang approves**, then the changes are published.
5. **Final check** on the live site on desktop and mobile, with before/after screenshots.

**What we won't touch:** domains, billing, apps, form back-end settings and automations, CMS data, analytics, and the raffle integration.
