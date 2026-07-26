[README.md](https://github.com/user-attachments/files/30386114/README.md)# Moto-Bike-Landing-Page
Easy to copy, landing page for motorbike dealers

A single-file, self-contained landing page template for vintage motorcycle dealers — sales, rentals, restoration. Dark charcoal / oxblood / brass palette, Fraunces + Inter + IBM Plex Mono type system, no build step, no dependencies beyond Google Fonts.

**Live in one file:** `index.html`. Open it in a browser, or deploy it anywhere that serves static HTML.

## What's inside

- Sticky nav with mobile menu
- Full-height hero
- "On the floor" ticker strip (today's inventory highlights)
- Inventory grid — 6 spec-plate style bike cards
- Services section (Sales / Rentals / Restoration)
- Story / about section with stat callouts
- Testimonials
- Visit section: hours, address, contact form (mailto-based, no backend required)
- Footer

## How to customize it

Every piece of dealer-specific content is wrapped in `{{DOUBLE_BRACES}}`. Open `index.html` in any text editor and use **Find & Replace** to swap each token for real content:

| Token | Replace with |
|---|---|
| `{{DEALERSHIP_NAME}}` | Your shop's name |
| `{{CITY}}`, `{{COUNTRY}}`, `{{STREET_ADDRESS}}` | Your location |
| `{{YEAR_FOUNDED}}` | Year you opened |
| `{{PHONE_NUMBER}}`, `{{EMAIL_ADDRESS}}`, `{{INSTAGRAM_URL}}` | Contact details |
| `{{OPENING_HOURS}}` | e.g. "Tue–Sat, 10:00–18:00" |
| `{{BIKE_MODEL_1..6}}`, `{{YEAR_1..6}}`, `{{ENGINE_SPEC_1..6}}`, `{{MILEAGE_1..6}}`, `{{PRICE_1..6}}` | Your inventory. Add or remove `.plate-card` blocks to change the count. |
| `{{FOUNDER_STORY_PARAGRAPH...}}` | 2–3 sentences on the shop's story |
| `{{BIKES_RESTORED}}`, `{{YEARS_OPEN}}`, `{{RIDERS_HOSTED}}` | Small stat numbers in the Story section |
| `{{TESTIMONIAL_QUOTE_1..3}}`, `{{TESTIMONIAL_NAME_1..3}}` | Customer quotes |

**Photos:** every image slot is currently a styled placeholder block that tells you its expected size (e.g. "1600×1200"). Replace each `.plate-photo` / `.story-photo` div's content with your own `<img>` tag once you have real photos.

**Contact form:** the form submits via `mailto:` so it works with zero backend — clicking "Send Message" opens the visitor's email client with the message pre-filled. For a proper in-page submission (no email client required), swap the `<form>` action for a service like Formspree, or wire it into your own backend.

## Deploying it

Any static host works. A few free options:

- **GitHub Pages:** in this repo, go to *Settings → Pages*, set the source to the `main` branch, and it'll be live at `https://<username>.github.io/<repo-name>/` within a minute.
- **Netlify / Vercel:** drag-and-drop the folder onto their dashboard, or connect this repo for automatic deploys.

## Notes

- Built as a template — no analytics, tracking, or third-party scripts beyond the Google Fonts stylesheet.
- Respects `prefers-reduced-motion` and has visible keyboard focus states.
- Responsive down to mobile, with a slide-in nav below 640px.
EADME.md…]()
