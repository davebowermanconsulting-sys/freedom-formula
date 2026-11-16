# Page build spec: Event and Conference Experiences

- **Live URL:** https://www.malang.org.au/event-and-conference-experiences
- **Nav label:** Event and Conference Experiences (unchanged)
- **Status:** DRAFT for client review. Nothing changed in Wix yet.
- **Rule for the Wix session:** Save and Preview only. Never Publish. Show each section to the user before saving.

Legend:
- **[KEEP]** is existing live copy. Re-use it word for word.
- **[NEW – DRAFT]** is proposed copy that needs Malang approval.
- **[CONFIRM]** marks a fact that Malang must supply or confirm before the change goes live. Do not invent it.

---

## 1. What is wrong today (captured 16 Nov 2026)

Evidence: `../evidence/2026-11-16-current-live/event-and-conference-experiences-{desktop,mobile}.png`

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

## 2. Target layout (desktop, top to bottom)

### S1 Hero (full-width strip, image background with dark overlay at 40–50% so white text passes contrast)
- H1 [KEEP]: **Aboriginal Cultural Experiences for Events & Conferences**
- Sub-heading [KEEP]: Connecting artists, culture and events through meaningful experiences
- Supporting line [KEEP]: Malang works with Aboriginal artists across Australia, enabling scalable delivery for events of all sizes.
- Primary button [KEEP label]: **Enquire About Your Event**. Anchor-link it to S7 (the enquiry form) on the same page.
- Image: keep the current hero image (`54788667339_2d4ef4508c_o_edited.jpg`). Alt text [NEW – DRAFT]: "Aboriginal artwork and cultural activation at an event delivered by Malang" [CONFIRM it describes the photo].

### S2 Intro (single centred text block, max width about 760px)
[KEEP] Malang partners with organisations to deliver authentic Aboriginal cultural experiences for events, bringing together artists, storytelling, design, and products into a seamless and impactful offering.

[KEEP] With extensive experience in event production and project delivery, Malang ensures seamless delivery across design, product, and on-site activation.

### S3 Our signature experiences (native text, 3-column cards on desktop, 1 column on mobile)
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

### S4 Case study: WESNET (keep the existing coloured band and slideshow)
- Title [KEEP]: Case Study: WESNET
- Sub [KEEP]: Global Network of Women's Shelters
- Tag [KEEP]: Cultural event branding & artwork
- Quote [KEEP, verbatim, never shorten]: "Her work is not only visually stunning but deeply meaningful, bringing layers of cultural storytelling that truly enhanced the experience for our audience." — Natalie, Event Coordinator, WESNET
- [CONFIRM] Event name, year and location for one context line, for example "[Event name], [City], [Year]". Leave it out if not supplied.
- [CONFIRM] Add a second case study if Malang has one with an approved quote and images. Use the same card design.

### S5 Artists (2-column: image left, text right)
[KEEP] Malang works with leading Aboriginal artists across Australia, including Saretta Fielding, delivering cultural experiences from concept through to completion.

Secondary button [NEW – DRAFT]: **Meet our artists**, linking to /artist-together.

### S6 How it works (4 numbered steps, horizontal on desktop, stacked on mobile) [NEW – DRAFT]
1. **Tell us about your event.** Share your date, audience size and goals.
2. **Concept & artist match.** We connect you with the right artist and shape a concept with you.
3. **Design & production.** Artwork, products and activations are developed and approved.
4. **Delivery on the day.** Malang coordinates delivery and on-site activation.

[KEEP] We recommend engaging early to align artwork, products and event timelines.

### S7 Enquiry (anchor target for all "Enquire" buttons)
- Heading [KEEP]: Let's create a culturally rich and meaningful experience for your next event
- Form heading [KEEP]: Tell us about your event
- Keep the **existing** form exactly as it is (Name, Organisation, Email, Phone, Event Type, Event Date, Message, Submit).
- **Do not** change the form's settings, recipients, automations or submission destination. Layout and position only.

### S8 Footer
- On **this page only**, hide the site-wide footer contact form (First/Last Name, Email, Message, Phone, Send) so there is a single enquiry route. Keep the "Get in Touch" address block and ABN line.
- If the footer form is a master/global element, do not delete it. Ask the user whether to hide it on this page or leave it.

---

## 3. Mobile-editor pass (required, separate from desktop)

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

## 4. SEO & accessibility
- Page SEO title [NEW – DRAFT]: Aboriginal Cultural Experiences for Events & Conferences | Malang
- Meta description [NEW – DRAFT]: Malang works with Aboriginal artists across Australia to deliver cultural event branding, artwork, products and on-site experiences for events and conferences of all sizes.
- One H1 only (S1). Section headings as H2.
- Every image needs alt text describing what is shown. Logos: "[Organisation] logo". Purely decorative images: mark them decorative.

## 5. Acceptance checks for this page
- [ ] Desktop order matches section 2.
- [ ] Mobile order matches desktop (form is not above the hero).
- [ ] No text column narrower than about 260px on mobile.
- [ ] Button labels fit inside their buttons on mobile.
- [ ] Exactly one enquiry form on the page.
- [ ] Offerings are native text, not an image.
- [ ] WESNET quote is verbatim.
- [ ] Form settings and automations unchanged.
- [ ] Saved, not published. The live site is unchanged.
