# Astro Boilerplate

A clean, minimal landing page boilerplate for web agency projects. Built with Astro and Tailwind CSS v4.

---

## Stack

| Tool                                                                      | Version | Purpose                     |
| ------------------------------------------------------------------------- | ------- | --------------------------- |
| [Astro](https://astro.build)                                              | ^6.0    | Static site framework       |
| [Tailwind CSS](https://tailwindcss.com)                                   | ^4.2    | Utility-first styling       |
| [@tailwindcss/vite](https://tailwindcss.com/docs/installation/using-vite) | ^4.2    | Vite plugin for Tailwind v4 |
| Node.js                                                                   | ≥22.12  | Runtime                     |

---

## Project Structure

```
src/
├── components/
│   ├── NavBar.astro
│   ├── Hero.astro
│   ├── TrustBar.astro
│   ├── ValueStrip.astro
│   ├── About.astro
│   ├── Services.astro
│   ├── WhyChooseUs.astro
│   ├── Testimonials.astro
│   ├── Process.astro
│   ├── FAQ.astro
│   ├── ServiceAreas.astro
│   ├── Contact.astro
│   └── Footer.astro
├── layouts/
│   └── Layout.astro
├── pages/
│   └── index.astro
└── styles/
    └── global.css
```

---

## Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

---

## Customization

- **Colors & fonts** — edit `src/styles/global.css`. Tailwind v4 uses `@theme {}` for custom tokens instead of `tailwind.config.js`.
- **Site content** — all sections are individual `.astro` components in `src/components/`. Edit each one directly.
- **Layout / meta** — update `src/layouts/Layout.astro` for the HTML shell, title, and any global head tags.
- **Pages** — `src/pages/index.astro` assembles all components in order. Add or remove sections here.

---

## Sections Included

1. **NavBar** — Logo, nav links, CTA button
2. **Hero** — Full-width dark hero with headline and CTA
3. **TrustBar** — Key stats / social proof bar
4. **ValueStrip** — Icon + text value propositions
5. **About** — Two-column about section with image placeholder
6. **Services** — Card grid of service offerings
7. **WhyChooseUs** — Differentiators list
8. **Testimonials** — 3-column testimonial cards
9. **Process** — Numbered step-by-step process
10. **FAQ** — Accordion with accessible expand/collapse
11. **ServiceAreas** — Pill tags for geographic service areas
12. **Contact** — Dark contact section with form
13. **Footer** — Links, social icons, copyright

---

## Notes

- Tailwind v4 drops `tailwind.config.js` — configuration lives in CSS via `@import 'tailwindcss'` and `@theme {}`.
- All placeholder text is Lorem Ipsum. Replace copy, images, and contact details before deploying.
- No animations or third-party UI libraries — intentionally minimal for easy customization.
