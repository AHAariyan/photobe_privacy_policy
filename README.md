# Photobe — Privacy Policy

The privacy policy for **Photobe** (`com.aariyan.photoeditor`), published on Google Play by
Agonized Soul.

Live at: **https://photobe.privacypolicy.matrabhed.com/**

That URL is the one to paste into:

- Play Console → **Store presence → Main store listing → Privacy policy**
- Play Console → **Policy → App content → Data safety** (privacy policy field)

## Files

| File | Purpose |
|---|---|
| `index.html` | The policy itself. Self-contained — no build step, no dependencies, no external requests. |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is rather than running Jekyll. |
| `CNAME` | Written by GitHub when the custom domain is set. Change it in Settings → Pages, not by hand. |

## Hosting

Served by GitHub Pages from `main` at the repository root, on the custom domain above.

Set the domain in **Settings → Pages → Custom domain** rather than committing a `CNAME` by hand —
doing both leaves two sources of truth that drift.

**Enforce HTTPS must stay ticked.** Play fetches this URL during review, and a certificate warning
or a plain-HTTP response reads as an inaccessible privacy policy.

## Keeping it accurate

This policy must match the **Data safety** declaration in Play Console. A mismatch between the two
is itself a Play policy violation, so if either one changes, change both in the same sitting.

What the policy currently declares as collected:

- App interactions (Firebase Analytics)
- Crash logs and diagnostics (Firebase Crashlytics)
- A device identifier (Firebase app-instance ID)
- Purchase events — product, amount, currency (Firebase Analytics)

And declares as **not** collected — the important one — **photos and videos**, because every edit
runs on the device.

Update the "Last updated" date in `index.html` whenever the substance changes.
