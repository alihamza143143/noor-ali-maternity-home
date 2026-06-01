# Noor Ali Maternity Home — Website Design Spec

**Date:** 2026-06-02
**Status:** Approved

## Goal

A professional, fast, mobile-first website so patients can find Noor Ali Clinic
and Maternity Home, trust it, and contact the clinic instantly. Primary success
metric: easy discovery (Google) + one-tap Call/WhatsApp contact on a phone.

## Scope

- Single-page static website. No backend, no build step.
- Language: English only.
- Contact: prominent click-to-call and WhatsApp buttons (no form).

## Clinic Facts

- **Name:** Noor Ali Clinic & Maternity Home
- **Doctor:** Dr. Noor Ali — Gynecologist
- **Location:** Sardar Market, Kallar Syedan Road, Pakistan
- **Phone & WhatsApp:** 0304 9312622 (international: +92 304 9312622)
- **Email:** fnoor6176@gmail.com
- **Hours:** Open 24/7 for emergency services
- **Services:** Maternity & antenatal care, normal deliveries, gynecology
  consultation, family planning, newborn (baby) care, 24/7 emergency care.
  C-section is NOT performed and is simply omitted.

## Design Direction

- **Style A — Warm & Nurturing.** Soft rose + deep maroon palette
  (`#7d2b4e`, `#c96d8c`, `#f6d9e2`, `#fbeef1`), WhatsApp green `#25D366`.
- Rounded cards, generous whitespace, gentle and compassionate tone.
- Custom inline **SVG logo**: stylized mother cradling a child in a soft circle,
  with "Noor Ali Maternity Home" wordmark. Reused as favicon.

## Page Structure (single page, anchor-scroll nav)

1. **Sticky header** — logo + name, Call + WhatsApp buttons, mobile menu.
2. **Hero** — name, tagline "Caring for Mother & Child, Day and Night",
   24/7 Emergency badge, Call + WhatsApp CTAs, location line.
3. **Welcome / About** — intro to the maternity home and Dr. Noor Ali.
4. **Services** — six cards (see services list above).
5. **Why Choose Us** — 24/7 availability, experienced female gynecologist,
   caring & private environment, trusted locally.
6. **Visit Us** — address, embedded Google Map, hours (24/7).
7. **Contact** — large Call & WhatsApp buttons + email.
8. **Footer** — name, quick links, copyright.

Plus: floating WhatsApp button on mobile; SEO meta (title, description,
local keywords, Open Graph); smooth scrolling; subtle scroll reveal animations.

## Files

- `index.html` — markup + inline SVG logo
- `style.css` — palette, layout, responsive rules
- `script.js` — mobile menu, smooth scroll, scroll-reveal
- `assets/` — favicon / og image if needed

## Out of Scope (YAGNI)

Online booking, patient portal, blog/CMS, multi-language, analytics backend.
Can be added later if the clinic grows.
