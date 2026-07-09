# ODL PM Dashboard (password-protected)

**Site:** https://nd-learning.github.io/PMdashboard-site/ — enter the ODL team
password (ask your PM). Your browser remembers it for 30 days.

This repo only ever holds the **encrypted** dashboard (`index.html`,
StatiCrypt AES-256). It refreshes nightly from the builder pipeline via the
`encrypt-and-publish` workflow. To rotate the password: Settings → Secrets →
Actions → `STATICRYPT_PASSWORD`, then Actions → encrypt-and-publish → Run
workflow. Dashboard source: `ND-Learning/PMdashboard` (private).
