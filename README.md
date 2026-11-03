# spicetify-shion-theme

A personal Spicetify theme: custom colors plus a custom background image.
Made to work both with desktop Spicetify and with the Spicetify Android
patches (Morphe), whose Marketplace applies a theme's background image
when its `user.css` or scripts name one.

## Files

- `color.ini` — the color scheme (`Base`).
- `user.css` — draws `background.jpg` behind Spotify's main view.
- `theme.js` — names the same image as `defImage` (Galaxy-style), the
  other form the Android patches read.
- `background.jpg` — the background image itself. **Replace this file
  (keeping the name) to change the background.** A brighter image with
  the subject near the center works best: the Android patches darken
  the image by half for readability and center-crop it to the screen.

## Notes

- To appear in the in-app Spicetify Marketplace, this theme also needs
  to be added to the desktop Spicetify Marketplace listing
  (spicetify/marketplace).
- Colors can be tuned by editing `color.ini`.
