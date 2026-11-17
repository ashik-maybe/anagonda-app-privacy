# Ana Gonda Calculator — Privacy Policy

Self-contained, bilingual (বাংলা / English) privacy policy page for the
Ana Gonda Calculator mobile app (Android & iOS).

- **Live URL:** https://ashik-maybe.github.io/anagonda-app-privacy/
- **No external requests** — inline CSS, system fonts, inline SVG favicon. Nothing is fetched from a CDN, so the page is consistent with the app's "zero network" claim.
- **No JavaScript** — both languages are rendered on one page with anchor navigation.

## Local preview

```bash
cd ~/Documents/projects/anagonda-app-privacy
python3 -m http.server 8000
# open http://localhost:8000/
```

## Before submitting to the stores

Replace the two placeholders in `index.html`:

- `[developer-email]` (appears in the contact mailto and footer)
- `[Developer name or organisation]` (publisher line)

Then commit and push — the same URL stays valid forever.

## Store console checklist

- Google Play Console → App content → Privacy policy → paste the URL above.
- Google Play Data Safety: no data collected, no data shared, no encryption question, deletion = uninstall.
- App Store Connect → App Privacy → "Data Not Collected"; Privacy Policy URL = same URL.
- Content rating: no ads, no in-app purchases, no user-generated content.
