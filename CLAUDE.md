# Crew Voice Website

## Overview
Single-page marketing website for **Crew Voice**, a service that provides monthly bilingual employee interviews and retention intelligence reports for service businesses. Primary focus: lawn care and landscaping. Feedback is shared with the business owner (not confidential).

## Tech Stack
- **Static HTML** — single `index.html` file, no framework or build tools
- **Inline CSS** — all styles are in a `<style>` block in the `<head>`
- **Google Font** — Inter (400, 600, 700 weights)
- **JavaScript** — copyright year + AJAX form submission via Web3Forms API
- **No package manager** — no `node_modules`, no `package.json`

## External Services
- **Web3Forms** — contact form submission (API key in the form's hidden input)
- **MailerLite** — email marketing / lead magnet form (account ID: `2061887`, form ID: `Vy5Xxk`)

## Project Structure
```
index.html                 — the entire website
images/logo.png            — logo image
images/hero.jpg            — hero background photo (Unsplash, free commercial use)
images/favicon.svg         — SVG favicon (green circle with "CV")
.render_temp_index.html    — temp file (likely from Render hosting)
Crew_Voice_Business_Plan_February_2026.md — full business plan
```

## Key Details
- **Pricing**: $299/month for teams of 5-8 crew members, $30/additional member
- **Bilingual**: English & Spanish support is a core feature
- **Target audience**: Small to mid-size field service teams (3-25 crew members)
- **Contact**: (864) 334-6982 / luke@mycrewvoice.com
- **Domain**: mycrewvoice.com (hosted on Netlify, domain on GoDaddy)

## Style Notes — Landscaping-Focused Green Palette
- **Dark forest** `#1B3A26` — header, contact section, authority color
- **Footer dark** `#142B1D` — deeper shade for footer
- **Vibrant green** `#4CAF50` — step numbers, step borders, badges, next-step circles
- **Professional green** `#2E7D32` — industry tags, price text, solution box, lead magnet bg
- **Light green** `#6DBF5B` — logo text, footer headings, hover accents
- **Hero/Pricing gradient** `#1B5E20` → `#2E7D32` → `#33691E` (deep forest gradient)
- **Golden amber CTA** `#D4930D` — all call-to-action buttons, guarantee accents, savings highlights
- **Amber hover** `#B87E0B` — CTA hover state
- **Light sage backgrounds** `#EEF2EA` (how-it-works), `#F3F7EF` (feature cards, step examples)
- **Warm cream** `#FFF8E7` — cost items, guarantee box, savings box
- **Red (warnings only)** `#C62828` — pain point text, retention risk labels, total cost
- Font: Inter (Google Fonts) with system fallback (`Segoe UI`, Tahoma, Geneva, Verdana, sans-serif)
- Responsive with breakpoints at 900px and 768px
- Sticky header navigation

## Working With This Project
- All changes happen in `index.html` — there is no build step
- To preview, open `index.html` in a browser
- Be careful with the Web3Forms access key and MailerLite account ID when editing
