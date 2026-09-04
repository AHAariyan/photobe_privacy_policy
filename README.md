# Photobe — Privacy Policy

The privacy policy for **Photobe** (`com.aariyan.photoeditor`), published on Google Play by
Agonized Soul.

Live at: **https://ahaariyan.github.io/photobe_privacy_policy/**

That URL is the one to paste into:

- Play Console → **Store presence → Main store listing → Privacy policy**
- Play Console → **Policy → App content → Data safety** (privacy policy field)

## Files

| File | Purpose |
|---|---|
| `index.html` | The policy itself. Self-contained — no build step, no dependencies, no external requests. |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is rather than running Jekyll. |

## Enabling GitHub Pages

Repository → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → Save.

The site is live a minute or two later.

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
