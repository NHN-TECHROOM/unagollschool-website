# Unagolla School Website

This is a static bilingual school website for Unagolla School, designed for Cloudflare Pages and GitHub Pages.

## Structure

- `index.html` — homepage
- `styles.css` — site styling
- `assets/logo/` — place your school logo here
- `assets/images/` — place your background or gallery images here

## Upload to Cloudflare Pages

1. Push this folder to a GitHub repository.
2. In Cloudflare Pages, create a project and connect the repository.
3. Set:
   - Framework preset: None
   - Build command: leave empty
   - Output directory: `.`
4. Deploy.

## Replace images

Add your files here:

- `assets/logo/logo.png`
- `assets/images/hero.jpg`
- `assets/images/gallery-1.jpg`
- `assets/images/gallery-2.jpg`

Then update the image paths in `index.html` if needed.

## Notes

The site is static HTML/CSS and does not require a build step, which keeps it compatible with Cloudflare.
