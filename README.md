# deepankarsrigyan1.github.io — responsive rebuild

This folder contains the rebuilt responsive versions of:

- `index.html`
- `about.html`
- `research.html`
- `publications.html`
- `contact.html`

## Deployment

Replace the matching HTML files in the GitHub Pages repository and keep the existing `assets/` directory in the repository root. The contact page now looks first for icons in `assets/icons/` and automatically falls back to the previous `assets/assets/assets/icons/` paths if needed.

`utility.html` is still linked in the navigation, but it was not included in the supplied files, so it was not rewritten.

## Main improvements

- Responsive mobile/tablet/desktop layouts with no fixed desktop-only page widths.
- Accessible hamburger navigation on narrower screens.
- Fluid typography and spacing with `clamp()`.
- Better image containment and aspect-ratio handling.
- Responsive research cards, project layouts, publication cards, and contact grid.
- Publication search/filter.
- Improved focus visibility, touch targets, external-link safety, and reduced-motion support.
- Safe-area padding for modern phones.
- More semantic headings and landmarks.

## Recommended asset layout

```text
assets/
  profile.jpg
  quantum-bg.png
  bg-template.png
  logo-bu.png
  logo-uw.PNG
  logo-iitbhu.png
  icons/
    gmail.png
    outlook.png
    linkedin.png
    researchgate.png
    x.png
    facebook.png
    instagram.png
  research/
    ...existing research images...
```
