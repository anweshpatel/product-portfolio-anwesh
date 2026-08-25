ANWESH PATEL — PORTFOLIO · DEPLOY BUNDLE
========================================

FILES
  index.html      The site (self-contained: CSS, JS, and photo are inline).
  og-image.jpg    1200x630 social-share preview.
  photo.webp      Optimised headshot (51KB). Optional — the photo is already
                  embedded in index.html; use this only if you switch the hero
                  <img> to an external file to trim page weight.

GO LIVE (2 minutes)
  Option A — Vercel:   install the CLI, run  vercel --prod  in this folder.
  Option B — Netlify:  drag this folder onto app.netlify.com/drop.
  Option C — any host: upload the folder; index.html is the entry point.

BEFORE YOU DEPLOY
  1. Add your résumé PDFs to this folder (filenames the buttons expect):
       resume.pdf                  (hero "Download résumé")
       resume-ai-pm.pdf            (contact card)
       resume-product-strategy.pdf (contact card)
       resume-general.pdf          (contact card)
     Until these exist the résumé buttons will 404.
  2. In index.html, replace every  https://anweshpatel.com  with your real
     domain (og:url, og:image, twitter:image, canonical) — 4 spots.
  3. The deploy checklist is repeated as a comment at the top of index.html;
     delete it before launch.

CONTACT FORM
  Posts to your Formspree endpoint (f/xzepqqbg) with a mailto fallback.
  It cannot submit from a local file:// preview or inside a sandbox, but works
  once the site is on a real https host. Verify the endpoint in Formspree first.
