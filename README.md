# garbi-landing

Public landing page + privacy policy for **Garbi**, a personal AI assistant.
Hosted on GitHub Pages so it can be linked from the Google Cloud OAuth consent
screen (Google needs a public homepage URL and a public privacy policy URL to
submit an app for verification).

## Files

- `index.html` — homepage (app name, what it does, contact)
- `privacy.html` — privacy policy (what data, why, who sees it, GDPR rights)
- `styles.css` — minimal styling, no JS, no tracking

## How it's deployed

GitHub Pages from the `main` branch, root folder.

After the repo is created on GitHub and Pages is enabled, the site will be
available at:

    https://<github-username>.github.io/garbi-landing/

## Local preview

    python3 -m http.server 8000

Then open <http://localhost:8000/>.

## Owner

Miquel Poch · <miquel.poch@gmail.com>
