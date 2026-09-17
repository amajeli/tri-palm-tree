# AI Strategy Landing Page

Single-page site for Amanda Jelinek's AI strategy consulting.

**Message:** AI isn't a strategy. Understand your processes, tools and people first. That determines where AI fits.

## Files

- `index.html`: the whole page (HTML and CSS in one file; fonts load from Google Fonts). Responsive for desktop, tablet and mobile.
- `amanda-headshot.jpg`: photo used in the About block. Keep it next to `index.html`.

## Before going live

- [ ] Replace the "Book with me" link with the Calendly URL. Search `index.html` for `BOOKING LINK`.
- [ ] Confirm the brand violet (`--violet: #7C3AED`) and fonts (Fraunces, DM Sans) against the brand templates. All colors are variables at the top of the `<style>` block.
- [ ] Confirm the call length in the About block (currently 30 minutes).
- [ ] Add a social preview image (`og:image`) for LinkedIn sharing.

## Hosting

Static file, no build step. Works with GitHub Pages, Netlify or Cloudflare Pages. Point the host at the repo root.
