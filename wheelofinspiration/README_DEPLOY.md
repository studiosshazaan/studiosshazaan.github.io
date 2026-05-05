# Wheel of Inspiration website - fixed path version

This version uses root-relative image paths such as:

`/wheelofinspiration/assets/images/hero-wide.jpg`

That is safer for the GitHub Pages URL:

https://studiosshazaan.github.io/wheelofinspiration/

## Upload instructions

Upload the **contents** of this folder into this repository path:

`studiosshazaan.github.io/wheelofinspiration/`

Required structure:

```text
wheelofinspiration/
  index.html
  404.html
  favicon.png
  asset-check.html
  assets/
    images/
      hero-wide.jpg
      app-icon.jpg
      ...
```

## Test after GitHub Pages deploys

Open:

https://studiosshazaan.github.io/wheelofinspiration/asset-check.html

Then test direct image:

https://studiosshazaan.github.io/wheelofinspiration/assets/images/hero-wide.jpg

If the direct image works but the website does not, refresh with Ctrl+F5 or clear browser cache.

## Live Play Store button

https://play.google.com/store/apps/details?id=com.wheelofinspiration&hl=en


## Interactive update added

This version adds:
- click/tap image lightbox previews;
- keyboard lightbox navigation: Escape, Left, Right;
- a daily spark quote shuffler;
- copy quote button;
- scroll progress bar;
- back-to-top button;
- premium hover/tap micro-interactions.

No external JavaScript libraries are required.


## Lightbox fix update

This version removes the Daily Spark quote card and fixes the lightbox script order.

After upload:
1. Wait for GitHub Pages to deploy.
2. Hard refresh the page with Ctrl + F5.
3. Click any main image/poster.
4. Test keyboard controls: Escape, Left, Right.

If the cursor changes but nothing opens, the browser is probably still caching the older JavaScript. Open:
`https://studiosshazaan.github.io/wheelofinspiration/lightbox-check.html`
then hard refresh the main page.
