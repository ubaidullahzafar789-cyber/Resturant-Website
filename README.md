# Saveur — Fine Dining Restaurant Website

A professional, modern, fully responsive **restaurant website** built as a portfolio
project for a Software Engineering student's GitHub and LinkedIn showcase. The site
is 100% original, production-quality, and ready for GitHub Pages deployment.

> **Live Demo:** [View Website](https://ubaidullahzafar789-cyber.github.io/Resturant-Website/)
>
**Repository:** [GitHub Repository](https://github.com/ubaidullahzafar789-cyber/Resturant-Website)

---

## Description

**Saveur** is a fictional fine-dining restaurant. This project presents a complete
multi-page marketing website for the brand — covering a hero landing page, an about
story, a categorized menu, a visual gallery, and a contact/reservation page.

The goal was to demonstrate clean, semantic HTML5; a well-organized CSS3 architecture
with custom properties and reusable components; and confident use of the Bootstrap 5
framework — without relying on any custom JavaScript beyond Bootstrap's required
bundle and a few tiny progressive-enhancement snippets.

---

## Features

- **Fully responsive** — mobile, tablet, and desktop friendly
- **Five complete pages** — Home, About, Menu, Gallery, Contact
- **Sticky responsive navbar** with active-page highlighting
- **Hero banner** with call-to-action buttons
- **Featured dishes** section with price tags and hover effects
- **Why-choose-us** feature cards
- **Customer testimonials** with star ratings
- **Reservation CTA** band
- **Newsletter signup** (UI only)
- **About page** — story, mission & vision, chef profile, team, statistics, awards
- **Menu page** — five categories (Breakfast, Lunch, Dinner, Desserts, Drinks)
- **Gallery page** — responsive image grid with hover overlays
- **Contact page** — info cards, reservation form (UI only), business hours,
  embedded map, and social links
- **Accessible** — semantic landmarks, skip link, ARIA labels, focus styles,
  `prefers-reduced-motion` support
- **SEO-friendly** — meta tags, Open Graph tags, descriptive titles
- **Smooth scrolling**, scroll-aware navbar, back-to-top button
- **CSS variables**, a professional color palette, Google Fonts, hover & card
  animations — all in a single organized stylesheet

---

## Technologies Used

| Technology        | Purpose                                  |
| ----------------- | ---------------------------------------- |
| HTML5             | Semantic page structure                  |
| CSS3              | Custom styling, animations, variables     |
| Bootstrap 5.3     | Grid, components, responsive utilities   |
| Bootstrap Icons   | Iconography                              |
| Google Fonts      | Playfair Display + Poppins typography     |
| Pexels            | Royalty-free placeholder photography      |

> **No** React, Vue, Angular, Tailwind, jQuery, or backend technology is used.
> Only Bootstrap's required JS Bundle plus a few lines of vanilla JS for
> progressive enhancements (navbar shadow, back-to-top, footer year, form
> validation styling).

---

## Folder Structure

```
restaurant-website/
├── index.html          # Home page
├── about.html          # About page
├── menu.html           # Menu page
├── gallery.html        # Gallery page
├── contact.html        # Contact page
├── css/
│   └── style.css       # All custom styles
├── assets/
│   ├── images/         # Placeholder image download info (see IMAGES.md)
│   └── icons/          # Favicon / icon placeholders
├── README.md           # This file
├── LICENSE             # MIT License
└── IMAGES.md           # Image attribution & download links
```

> Images are loaded directly from Pexels CDN URLs, so no local image files are
> required to run the project. See **[IMAGES.md](IMAGES.md)** for the full list
> of source links and credits, plus instructions for replacing them with your own.

---

## Installation

This is a static site — no build step or dependencies required.

1. **Download / clone the repository:**
   ```bash
  https://github.com/ubaidullahzafar789-cyber/Resturant-Website
   cd restaurant-website
   ```
2. **Open `index.html`** in your browser — that's it.

   Or serve locally (optional, recommended so all paths resolve cleanly):
   ```bash
   # Python 3
   python -m http.server 8000
   # then visit http://localhost:8000
   ```

---

## Screenshots

<!-- Add screenshots of each page here once deployed. Recommended: -->
<!-- ![Home](screenshots/home.png) -->
<!-- ![About](screenshots/about.png) -->
<!-- ![Menu](screenshots/menu.png) -->
<!-- ![Gallery](screenshots/gallery.png) -->
<!-- ![Contact](screenshots/contact.png) -->

_Screenshots coming soon._

---

## Live Demo

Once deployed to GitHub Pages, your live site will be available at:

```
https://ubaidullahzafar789-cyber.github.io/Resturant-Website/
```

---

## Replacing Placeholder Images

Images are referenced from Pexels CDN URLs inside each HTML file's `<img>` tags
and in `css/style.css` (for hero backgrounds). To use your own:

1. Drop your image files into `assets/images/`.
2. Find the relevant `<img src="https://images.pexels.com/…">` and replace the
   `src` with a relative path, e.g. `assets/images/hero.jpg`.
3. For hero/page background images in `style.css`, replace the `url(...)` value
   in the `.hero`, `.page-hero`, `.reservation-cta`, and `.stats-band` rules.
4. Keep the same aspect ratio where possible, or adjust heights in `style.css`.

See **[IMAGES.md](IMAGES.md)** for the full image list, source links, and credits.

---

## GitHub Pages Deployment

1. Push this project to a public GitHub repository
   (e.g. `restaurant-website`).
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose the **`main`** branch and the **`/ (root)`** folder.
5. Click **Save**. Your site goes live within a minute or two at
   `https://<your-username>.github.io/restaurant-website/`.

> Because this is a static site with no build step, GitHub Pages serves the files
> exactly as they are — no GitHub Actions workflow required.

---

## Future Improvements

- Add a working reservation backend (e.g. a serverless function or form service)
- Lightbox modal for gallery images
- Filtering tabs on the menu page (animated, no full reload)
- Real Open Graph / social-share preview images
- Dark/light theme toggle
- Internationalization / multi-language support
- Lighthouse and accessibility audit pass with documented scores

---

## Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [Your Name](https://www.linkedin.com/in/your-profile)

_Built as a portfolio project to demonstrate frontend development skills._

---

## License

This project is licensed under the **MIT License** — see the
[LICENSE](LICENSE) file for details.

The placeholder photography is sourced from [Pexels](https://www.pexels.com)
under the [Pexels License](https://www.pexels.com/license/) (free to use, no
attribution required, though appreciated). See [IMAGES.md](IMAGES.md) for credits.
