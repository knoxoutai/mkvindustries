# MKV Industries — mkvindustries.com

Static marketing site for MKV Industries LLC. Plain HTML/CSS, no build step.

| Page | Purpose |
|---|---|
| `index.html` | Home: approach, experience, engagement, contact form |
| `thank-you.html` | Form confirmation page (GoHighLevel redirect target) |
| `terms.html` | Terms & Conditions |
| `privacy.html` | Privacy Policy |

## Deploy
Any static host works (Vercel, Netlify, GitHub Pages). Point the host at the repo root; there is no build command and no output directory.

## Contact form
The form is a GoHighLevel embed (Form 2, `DvuwYqJ1ZB27nOcnUA9F`). In GHL, set **On Submit → Open URL → `https://mkvindustries.com/thank-you.html`**, and point the form's Terms & Conditions checkbox at `https://mkvindustries.com/terms.html` and `https://mkvindustries.com/privacy.html`.

## Before launch
- Replace the `[contact email]` placeholders in `terms.html` and `privacy.html`.
- Replace the AI-generated prototype images in `img/` with owned photography, then remove the prototype note in `index.html`.
- Have counsel review the Terms and Privacy Policy.
