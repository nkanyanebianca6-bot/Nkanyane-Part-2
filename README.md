# Masingitas Travel and Tours Website
## Project
Academic HTML5 website for Masingitas Travel and Tours, a South African travel and tourism business.
## Pages
1. `index.html` – Home
2. `about.html` – About Us
3. `contact.html` – Contact
4. `enquiry.html` – Travel Enquiry
5. `menu.html` – Services
6. `destinations.html` – Destinations
## Technologies
- HTML5 semantic elements
- CSS3
- Responsive layout
- Accessible labels and navigation
## Website purpose
The website promotes holiday packages, accommodation, group tours, corporate travel packages, car rentals, shuttles, flights, touring sites, getaways, and cultural/sightseeing tours.
## Navigation
Every page contains a consistent navigation menu linking to all six pages.
## Forms
The enquiry form is a front-end demonstration. A server-side or email-processing action should be connected before using it for real customer submissions.
## GitHub submission guidance
Use descriptive commits such as:
- `Initial HTML5 website structure`
- `Add responsive navigation and CSS`
- `Create About, Services and Destinations pages`
- `Add enquiry and contact forms`
- `Improve accessibility and semantic structure`
- `Add README and CHANGELOG`
## Source
The website content is based on the supplied “WEBSITE BUSINESS PROPOSAL” for Masingitas Travel and Tours.
# Masingitas Travel and Tours - Web Application (Part 2 Solution)

## Project Overview
This repository contains the complete responsive HTML5 and CSS3 solution for **Masingitas Travel and Tours**, a premier South African travel agency. Part 2 introduces an external stylesheet architecture, responsive grid/flexbox layouts, responsive typography, custom UI styling, and multi-device media query support.

---

## Technical Architecture & Design Decisions

### 1. External Stylesheet Structure
- **File Path:** `css/style.css`
- **Implementation:** Linked centrally across all project pages (`index.html`, `pages/aboutus.html`, `pages/contact.html`, `pages/enquiry.html`, `pages/events.html`, `pages/menu.html`, `pages/service.html`).
- **CSS Architecture:** Organized into modular logical blocks (Reset, Custom Properties, Typography, Navigation, Layout Grids, Forms, Pseudo-classes, and Media Queries).

### 2. Design System & CSS Variables
- **Primary Navy (`#1b365d`):** Represents corporate trust, heritage, and professionalism.
- **Warm Gold (`#d4af37`):** Represents African luxury, safari adventures, and top-tier hospitality.
- **Deep Teal (`#008080`):** Provides a coastal and nature accent color.
- **Typography:** Uses fluid typography via `clamp()` with system font fallbacks (`Montserrat` for headings, `Open Sans` for readable body text).

---

## Responsive Breakpoints & Multi-Device Testing

The layout adapts across three core device tiers:
1. **Desktop (> 1024px):** Multi-column CSS Grid layouts, horizontal flex navigation bar, fixed element alignment.
2. **Tablet (768px – 1024px):** 2-Column responsive grid, adjusted element margins, scaled heading sizes.
3. **Mobile (< 768px):** Single-column stacked layout, touch-friendly vertical navigation menu, full-width touch targets for form inputs and buttons.

### Screenshot Evidence Placeholders
*(Include these image files in your repository under `/docs/screenshots/`)*
- `docs/screenshots/desktop-view.png` - Desktop view (1440px wide) displaying navigation and CSS grid layout.
- `docs/screenshots/tablet-view.png` - iPad/Tablet view (768px wide) showing 2-column package card adaptation.
- `docs/screenshots/mobile-view.png` - Mobile portrait view (375px wide) demonstrating stacked navigation and mobile forms.

---

## References & Citations

1. **ASATA (2026)** *Association of South African Travel Agents Code of Conduct*. Available at: https://www.asata.co.za [Accessed 18 Sep. 2026].
2. **MDN Web Docs (2026)** *CSS Grid Layout: Getting Started*. Mozilla Developer Network. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout [Accessed 18 Sep. 2026].
3. **MDN Web Docs (2026)** *Responsive design & Media queries*. Mozilla Developer Network. Available at: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design [Accessed 18 Sep. 2026].
4. **W3C (2023)** *HTML5 and CSS3 Accessibility Guidelines (WCAG 2.1)*. World Wide Web Consortium. Available at: https://www.w3.org/TR/WCAG21/ [Accessed 18 Sep. 2026].
