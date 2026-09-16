# Astro — legal pages

The Privacy Policy and Terms of Use for the Astro iPhone app, in Turkish and English, served with
GitHub Pages. This repository is public because App Store Connect and the app itself need reachable
URLs. It holds nothing else: no app code, no keys, no user data.

| Page | URL |
|---|---|
| Index | `/` |
| Gizlilik Politikası | `/privacy-tr.html` |
| Privacy Policy | `/privacy-en.html` |
| Kullanım Koşulları | `/terms-tr.html` |
| Terms of Use | `/terms-en.html` |

## Before publishing, fill in the placeholders

Each appears as `[... — DOLDURULACAK]` / `[... — TO BE COMPLETED]`:

- the legal entity's name and address (all four pages);
- the governing law and courts (both Terms pages).

## Keeping this true

The privacy policy describes how the app actually behaves today: everything on the device, no
account, no server copy, no analytics, no third-party SDKs, and only Apple Maps place search
leaving the phone. **If the app changes so that any of that stops being true, these pages change in
the same commit as the app.**

The app enforces the same rule from its side: `PrivacyPromise` in the app repository decides which
sentence the Sen tab shows, and its test fails when the flag and the sentence disagree.

The app also bundles a Turkish copy of the privacy policy (`App/Resources/Legal/privacy-policy-tr.md`)
which it shows when no URL is configured. Update it together with `privacy-tr.html`.

## Contact

velalabss@gmail.com
