# recrd Landing Page

Static landing page for recrd.io

## Structure

```
recrd-landing/
├── index.html          # Main page
├── css/
│   └── styles.css      # Extracted styles
├── assets/
│   ├── images/         # Product screenshots, logos, etc.
│   └── fonts/          # Custom fonts (if self-hosting)
└── README.md
```

## Deployment (Render)

1. Push to GitHub
2. Render → New Static Site → Connect repo
3. Build command: (leave blank)
4. Publish directory: `.`
5. Add custom domain in Settings

## Fonts

Currently using Google Fonts:
- **Fraunces** (display/headlines)
- **Inter** (body text)

To use custom fonts, add files to `assets/fonts/` and update `css/styles.css` with `@font-face` declarations.

## Images

Add images to `assets/images/` and reference in HTML/CSS as:
```html
<img src="assets/images/filename.png" alt="...">
```
```css
background-image: url('../assets/images/filename.png');
```
