# Fifth Raven Studios website

Static, responsive GitHub Pages website for `https://fifthraven-studios.github.io/`.

## Deploy

1. Open the **fifthraven-studios.github.io** repository under the `fifthraven-studios` GitHub account.
2. Upload all files and folders from this package to the **root** of its `main` branch (not the zip file itself, and not nested in `fifth-raven-site/`). Keep `assets/`, `games/`, and `privacy/` as folders.
3. Go to **Settings → Pages**, choose **Deploy from a branch → main → / (root)** and save. If already configured, uploading the files is enough to publish changes.
4. Check the URLs below in a browser, from both phone and desktop.

## URLs to test BEFORE changing Play Console

- https://fifthraven-studios.github.io/
- https://fifthraven-studios.github.io/games/malibu-cruiser/
- https://fifthraven-studios.github.io/app-ads.txt
- https://fifthraven-studios.github.io/privacy/malibu-cruiser/ (TEMPORARILY redirects to the original privacy policy)

## IMPORTANT — preserve privacy policy exact wording

This package **does not invent or replace** the existing privacy policy text. The current `privacy/malibu-cruiser/index.html` is a temporary redirect to the still-live existing privacy page (`https://vasilis65.github.io/malibu-cruiser-policy/`).

**Before setting the new privacy policy URL in Play Console**, replace this redirect with the exact policy HTML/text from the existing `malibu-cruiser-policy` repository. Review any substantive edits, and confirm its version/date and links. Then verify the new policy page renders all original sections correctly. Until that is done, leave Play Console's privacy policy URL pointing to the old site.

## IMPORTANT — AdMob

`app-ads.txt` sits at the root and contains the publisher line supplied by the studio in the conversation. **Confirm this still matches the publisher line shown in AdMob before switching the Play Store's developer website**. Keep the old file and old site live while the new domain is detected and verified. AdMob may need time to discover a changed Play developer website.

## Assets

- `assets/fifth-raven-logo.png`: authentic studio logo from previous project artwork.
- `assets/malibu-cover.jpg`: full Malibu Cruiser promotional artwork, not an in-game screenshot.
- `assets/malibu-scene.jpg`: sunset-and-car crop of original promotional art, avoiding clipped title text at mobile sizes.
- `assets/icon-192.png`, `assets/icon-32.png`: cropped site favicon based on studio logo.

Replace or supplement with actual game screenshots and video links when available. The design deliberately does **not** describe promotional art as captured gameplay.

## Social & product links embedded

- Instagram: https://www.instagram.com/fifthraven.studios/
- TikTok: https://www.tiktok.com/@fifth_raven_studios
- YouTube: https://www.youtube.com/@FifthRavenStudios
- Google Play: https://play.google.com/store/apps/details?id=com.fifthraven.malibucruiser
- Contact: fifthraven.studios@gmail.com

## Migration order

1. Upload website and test all links.
2. Copy original privacy policy into new URL and compare all sections.
3. Check new `app-ads.txt` matches AdMob's publisher entry and is plain text.
4. Update Google Play **developer website** URL.
5. Let AdMob recheck / confirm verification. Keep old hostname live in the meantime.
6. Update Google Play **privacy policy** URL and other old links only after new policy page works.
7. Update website link in social bios, YouTube, other developer listings, press pages and any email signatures.
8. Once everything has migrated and been verified, configure appropriate redirects or clear notices on the old GitHub Pages websites. Don't delete them immediately.
