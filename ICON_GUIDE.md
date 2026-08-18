# Icon Guide

Add icons to `assets/images/icons/`. Prefer SVG for UI icons.

### Recommended names
`unified-communications.svg`
`ict-infrastructure.svg`
`chronic-care.svg`
`professional-development.svg`

### Replace an expertise icon
Open `index.html`, find the desired `.expertise-icon`, and replace its text/SVG with:

```html
<img src="assets/images/icons/unified-communications.svg" alt="">
```

The CSS constrains the icon area so different source sizes stay consistent.

### Company logos
Put company logos in `assets/images/logos/`. Transparent PNG/SVG is preferred. The site applies grayscale, sizing and hover color automatically.

### Signature and profile
Signature: `assets/images/signature.png`
Profile: `assets/images/profile.png`
