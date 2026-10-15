# Ethio Amharic Keyboard: website

Promo, install guide and FAQ for Ethio Amharic Keyboard for Mac. Plain static HTML/CSS, no build step.

- `index.html` promo and download, `guide.html` install and use guide, `faq.html` FAQ
- Deployed on Vercel (`vercel.json` enables clean URLs). Framework preset: **Other**, no build command, output directory: the repo root.
- The download button points to the latest GitHub Release asset `Ethio-Amharic-Keyboard.dmg` in this repo.

## Publishing a new version
1. Build the notarized dmg in the Mac repo (`Scripts/release.sh`).
2. `gh release create vX.Y.Z "path/Ethio-Amharic-Keyboard-X.Y.Z.dmg#Ethio-Amharic-Keyboard.dmg" --repo Henok-tasissa/ethio-keyboard-site --title "vX.Y.Z" --notes "..."`
3. Update the version text in `index.html` ("Version X.Y.Z" in the download section).
