# MKV Industries — mkvindustries.com

Static marketing site for MKV Industries LLC. Plain HTML/CSS, no build step.

| Page | Purpose |
|---|---|
| `index.html` | Home: approach, experience, engagement, contact form |
| `foxhole/index.html` | Operation Foxhole draft (`/foxhole` and `/foxhole/`). `noindex`. Not in the main nav; a small footer link on the home page points here. |
| `thank-you.html` | Form confirmation page (GoHighLevel redirect target) |
| `terms.html` | Terms & Conditions |
| `privacy.html` | Privacy Policy |

## Deploy
Hosted on GitHub Pages from `main` / root, with the custom domain `mkvindustries.com` (see `CNAME`). There is no build step; `.nojekyll` tells Pages to serve the files as-is.

## Contact
General and privacy requests: support@mkv-ind.com

## Contact form
The form is a GoHighLevel embed (Form 2, `DvuwYqJ1ZB27nOcnUA9F`). In GHL, set **On Submit → Open URL → `https://mkvindustries.com/thank-you.html`**, and point the form's Terms & Conditions checkbox at `https://mkvindustries.com/terms.html` and `https://mkvindustries.com/privacy.html`.

## Before launch
- Replace the AI-generated prototype images in `img/` with owned photography, then remove the prototype note in `index.html`.
- Have counsel review the Terms and Privacy Policy.

## Operation Foxhole
Draft only, at `/foxhole/` (`foxhole/index.html`). GitHub Pages redirects `/foxhole` to `/foxhole/`. The page is `noindex, nofollow` and is not linked from the main navigation. Before it is published, replace `[PHONE NUMBER]`, confirm the amber `[CONFIRM]` notes in the page source, and replace `img/foxhole-*.jpg` with owned photography. Image credits are in `IMAGE-CREDITS.txt`.
