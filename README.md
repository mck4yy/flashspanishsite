# FlashSpanish Landing Page

This repository contains the landing page for the FlashSpanish Chrome Extension. The site is optimized to clearly communicate the value proposition, convert visitors to users, and provide an SEO-friendly structure complete with Schema.org FAQ markup for LLM citation.ø

## Setup & Deployment

1. **Add Assets**: Replace the placeholder text in `index.html` with your actual screenshots. Place your images inside the `assets/` directory. Be sure to uncomment the proper `<img>` tags and remove the placeholder `<div class="image-placeholder">` elements.
2. **Update Content Fields**: Look for comments in `index.html` to update the Chrome Web Store extension link (currently `#` in `.cta-button`). Update the testimonial placeholders with genuine reviews.
3. **Commit & Push**: Push this repository to GitHub.
4. **Deploy via GitHub Pages**:
   - Go to your repository **Settings** on GitHub.
   - Navigate to **Pages** in the left sidebar under Code and automation.
   - Under **Build and deployment**, select `Deploy from a branch`.
   - Choose the `main` branch and the `/(root)` directory, then click **Save**.
   - Your site will be live within a few minutes at `https://[your-username].github.io/[repo-name]/`.

## Technical Information

- **Architecture**: Single-page static HTML template (HTML5).
- **Styling**: Vanilla CSS. Responsive design matching modern aesthetic principles emphasizing white space, typography, and clear visual hierarchy.
- **Animations**: Uses lightweight vanilla Javascript (`IntersectionObserver`) to provide `fade-in-section` animations as you scroll down the page, enhancing the premium feel without impacting performance.
- **SEO & Search**: Includes standard Open Graph metadata, semantic HTML markup, and JSON-LD schema specifically tailored to answer common user intents around Spanish learning while browsing.
