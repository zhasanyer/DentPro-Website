# DentPro — Dental Clinic Website

**Project Topic:** A 4-page responsive website for a fictional dental clinic, built with semantic HTML5 and hand-written CSS (no frameworks).

**Deployed URL:** [https://dentproasik3.netlify.app/](https://dentprowebtasik3.netlify.app/](https://dentprowebtasik3.netlify.app/)

## Team Members & Page Ownership

| Team Member | Primary Page |
|---|---|
| Sanzhar Zhagiparov | Home (`index.html`) |
| Alikhan Tanatov | Services (`services.html`) |
| Kemal Urazmukhambet | Information (`about.html`) |
| Ramazan Ashirbay | Booking (`contact.html`) |

## Project Structure


```
dentpro/
├── index.html        # Home page
├── services.html      # Services page
├── about.html          # Information page (about, team, hours)
├── contact.html        # Booking page (form + contact info)
├── css/
│   ├── style.css        # Variables, base styles, components
│   └── responsive.css     # Media queries (tablet & phone)
├── images/               # SVG icons and hero illustration
└── README.md
```

## Pages

- **Home** — hero banner, trust stats, "why choose us" feature grid, featured services, testimonial, CTA.
- **Services** — full service gallery (8 treatments), step-by-step process, CTA.
- **Information** — clinic story, mission/vision/values, team profiles, facilities, opening hours.
- **Booking** — appointment request form, contact details, opening hours, map placeholder, FAQ.

## Layout Techniques

- **Flexbox** is used for the main navigation, hero content/media, button groups, stat rows, service card rows, team member rows, contact info lists and the footer bottom bar — demonstrating `flex-direction`, `justify-content`, `align-items`, `gap`, `flex-wrap`, `flex` and `order`.
- **CSS Grid** is used for the "why choose us" feature grid (6 items), the services gallery (8 items, `auto-fit`/`minmax`), the process steps, the mission/vision/values layout (named grid areas), the footer columns, and the booking page's two-column form/contact layout.
- **Responsive design** is handled with two breakpoints (tablet ≤900px, phone ≤600px) that reduce grid columns, stack the navigation and hero, and reflow flex rows to prevent overlap or horizontal scrolling.

## How to View

Open `index.html` in any modern browser. No build step or server is required.
