# Pranav Regmi — Personal Portfolio (V1)

**Brand:** Athristt.
**Live (Vercel):** https://athristt-personal.vercel.app/
**Domain:** www.pranavregmi.com.np

Personal portfolio and professional identity site for Pranav Regmi — Growth Strategist, Project Coordinator, and EdTech Builder based in Kathmandu, Nepal. Built as a single self-contained HTML file to avoid any broken asset paths across environments.

---

## Overview

A single-page site covering:

- **Hero** — animated rotating role titles, profile photo, CV download
- **About** — dual framing for recruiters/HR and for business/partnership audiences
- **Moments carousel** — "Life at Skill Shikshya" and "Global Disability Summit — Berlin" photo galleries, auto-advancing every 5s, pauses on hover, manual prev/next + dots
- **Experience** — scroll-tracked timeline with clickable company links, plus separate "Freelance & Independent Work" and "Volunteering" sub-sections
- **Education**
- **Skills** — Technical, Tools & Design, Soft & Specialized, Languages
- **A little more about me** — flip cards (Born, Roots, and a hidden "Secret" easter egg)
- **Contact** — working contact form (EmailJS) with a branded notification email to Pranav and an auto-reply to the visitor
- **Restricted area** — a lock icon in the nav (desktop + mobile) that, on correct password, redirects to the personal finance dashboard

## Tech stack

- Plain HTML/CSS/JS — no build step, no framework
- Fonts: **Bricolage Grotesque** (headings) + **Outfit** (body), via Google Fonts
- Email: [EmailJS](https://www.emailjs.com) (client-side, no backend required)
- All images and the CV are embedded directly in the HTML as base64 data URIs, so the file works standalone with zero broken links regardless of how it's opened or hosted

## Color palette

| Role | Swatch |
|---|---|
| Jade (primary) | `#35AC80` |
| Coral (CTA/accent) | `#E15A33` |
| Golden (highlight) | `#E8A81E` |
| Stone (neutral) | warm greys, `#FAFAF8` → `#2A2723` |

## Deployment

Hosted on **Vercel**, connected to the custom domain **pranavregmi.com.np**. Since everything (images, CV, styles, scripts) lives in the one HTML file, deployment is just serving `index.html` — no build configuration needed.


## Status

**V1** — first full public version. Known next steps: swap the base64-embedded assets for normal file references for faster load once deployment is finalized, add more photo sets to the moments carousel, and embed the finance dashboard directly rather than redirecting to it.
