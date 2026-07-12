# SPARKCOmmunity OS - Website Handoff

This is a static HTML/CSS/JS landing page for SPARKCOmmunity OS.

## How to preview

Open:

`index.html`

in a browser.

## How to publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload all files and folders from this package.
3. Go to repository Settings → Pages.
4. Choose the main branch and root folder.
5. Save. GitHub will provide a public URL.

## Main files

- `index.html` - the full website in one file.
- `assets/` - images used by the website.

## Image replacement points

You can replace these files directly while keeping the same names:

- `assets/hero-club-hall.png`  
  Main hero image.

- `assets/circle-room.png`  
  Product proof image for presence / circle room.

- `assets/spark-match.png`  
  Spark Match image.  
  This is the best place to later use a real screenshot from inside the Sparkco space.

## Logo / brand note

The current header uses a CSS/HTML wordmark for Sparkco with a custom K-spark idea.

A designer can later replace this with a proper SVG logo.

Recommended final asset:

- `assets/logo-sparkco.svg`

Then update the header block in `index.html`.

## Spark Match K-spark note

The K-spark is currently coded as CSS lines inside the word "Spark".  
This is a concept direction, not final brand artwork.

Recommended design task:
Create a clean SVG version of the Sparkco wordmark where the K subtly functions as a spark.

## Animation note

The site includes subtle CSS animations:

- Spark Match: two avatar circles meet.
- Model / Impact: small community circles move toward each other.

Animations respect `prefers-reduced-motion`.

## Buttons and links to update

Search inside `index.html` for:

- `#demo`
- `#contact`
- `mailto:hello@sparkco.ai`
- `#performance`
- `#sparki`

Replace them with real URLs when ready.

## Content positioning

Do not change the core message structure without a strategic review:

1. Community already exists → give it a live place.
2. Missing layer: most communities have content, few have a living place.
3. Live club layer: rooms, events, Spark Match, circles, workshops, dashboard.
4. Product proof: presence and connection.
5. From audience to participatory community.
6. Participation model.
7. Human scale: 150 as a design principle.
8. Small social dream / impact layer.
9. Sparkco broader vision / Performance Layer / Sparki.
10. Final CTA.

## Recommended next design tasks

1. Replace placeholder/product images with real Sparkco screenshots where possible.
2. Create final SVG logo and K-spark brand mark.
3. Do a full mobile QA pass.
4. Add final real URLs.
5. Consider adding subtle circle connection animations in the Hero, but only if it remains clean.


## v34 update
- Hero now uses the real workshop / club hall screenshot.
- The proof section now uses the real circle room screenshot.
- Spark Match now uses the in-space Spark Match screenshot.
- The community leader dashboard is now shown as a small supporting proof card instead of a dominant large visual.


## v35 GitHub-ready link setup

Final links added:

- Demo club: https://app.sparkco.space/s/community?room=qSfM25ddz4DJa3TsdVB7
- Conversation / WhatsApp: https://wa.me/972544753064
- Email: info@sparkco.space
- Sparkco main site / Performance Layer / Sparki: https://www.sparkco.space

Privacy and terms are not ready yet. Footer links currently open an email request to info@sparkco.space.


## v37 Flat GitHub upload

This version is prepared for GitHub's browser uploader when it does not preserve folders.

Upload all files to the repository root, exactly like this:

- index.html
- README.md
- ASSET_CHECKLIST.md
- hero-club-hall.png
- circle-room.png
- spark-match.png
- dashboard-preview.png
- logo-sparkco-green.png

For this version, do not use an assets folder.


## v38 final visual polish

Changes:
- Header uses the real Sparkco logo on a dark background.
- Spark Match branding is now text-only.
- Spark Match meeting animation uses two realistic portrait avatars.
- Circular-avatar language block uses a real room/avatar visual with subtle motion.
- Flat root upload structure is preserved.

## v40 copy polish
Removed long em/en dashes from the visible copy so the text feels more human and less AI-generated.

## v47 stable repair

This version was rebuilt from the last stable page base to avoid layout breakage.
Included:
- Stable original layout restored.
- WhatsApp CTA links.
- Purple favicon.
- Charismatic male presenter room image.
- Bold recurring revenue sentence.
- Header wordmark fixed so it does not appear tiny.
- Flat root structure for GitHub Pages.
