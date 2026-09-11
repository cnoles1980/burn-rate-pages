# Burn Rate public pages

Public source for the `cnoles1980/burn-rate-pages` GitHub Pages site. The
repository and Pages deployment were created on 2026-09-10. The first Pages
workflow completed successfully, and all three pages were fetched over HTTPS.

Verified public URLs:

- Marketing: `https://cnoles1980.github.io/burn-rate-pages/`
- Support: `https://cnoles1980.github.io/burn-rate-pages/support.html`
- Privacy: `https://cnoles1980.github.io/burn-rate-pages/privacy.html`

The shared publisher file at `https://cnoles1980.github.io/app-ads.txt` also
returned HTTP 200 and contains the exact publisher line:

`google.com, pub-5676028087805239, DIRECT, f08c47fec0942fa0`

`ads-control.json` is the production rewarded-ad release switch. It is checked
on app launch and foreground entry. The checked-in public configuration must
remain fail-closed until the App Store listing is live, AdMob is linked to that
listing, the production binary has passed consent/reward QA, and enabling ads
has received a separate explicit approval. Enable both the global switch and
each intended placement; malformed, missing, or unreachable configuration is
treated as off by the app.

The AdMob European regulations message was verified as Published on September
10, 2026. The remote control remains entirely off; publishing this repository
does not authorize or activate production ad traffic.
