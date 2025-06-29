# Rent-a-NPC Landing Page

A static landing page for Rent-a-NPC, a service that deploys improv actors as in-game NPCs for brand activations, events, and viral experiences.

## Features

- 🎮 Retro gaming aesthetic with neon green and purple color scheme
- 📱 Fully responsive design (mobile-first)
- 🎨 Custom typography using Press Start 2P and Roboto fonts
- 🔗 QR code integration for easy mobile access
- 📝 Google Forms integration for lead capture
- ♿ Accessibility compliant (WCAG AA standards)

## Setup Instructions

### 1. Google Forms Integration

Replace the placeholder form URL in `index.html`:

```html
<!-- Line 47: Replace YOUR_FORM_ID with your actual Google Form ID -->
src="https://docs.google.com/forms/d/e/YOUR_FORM_ID/viewform?embedded=true"
```

### 2. QR Code

Replace `assets/qr-code.png` with your actual QR code image that links to your landing page.

### 3. Custom Domain (Optional)

The `CNAME` file is already configured for `rent-a-npc.com`. Configure your DNS settings:

- **A Record**: Point to GitHub Pages IP (185.199.108.153)
- **CNAME Record**: Point to `yourusername.github.io`

### 4. GitHub Pages Deployment

1. Push code to GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Set custom domain if using `rent-a-npc.com`

## File Structure

```
/
├── index.html          # Main landing page
├── styles.css          # Stylesheet with CSS variables
├── CNAME              # Custom domain configuration
├── assets/
│   ├── logo.svg       # Primary logo
│   ├── logo.png       # PNG version
│   ├── qr-code.png    # QR code image
│   ├── npc-icon.svg   # Footer icon
│   └── favicon.ico    # Browser icon
└── fonts/
    ├── PressStart2P-Regular.woff2
    └── Roboto-Regular.woff2
```

## Color Palette

- **Primary Green**: `#00FF99`
- **Accent Teal**: `#33FFD6`
- **Deep Purple**: `#2B003A`
- **Off White**: `#F2F2F2`

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Performance

- Optimized web fonts with `font-display: swap`
- Compressed images and assets
- Minimal JavaScript (vanilla HTML/CSS)
- Fast loading times

## Accessibility

- WCAG AA compliant color contrast
- Proper heading hierarchy
- Alt text for all images
- Keyboard navigation support
- Screen reader friendly

## License

© 2025 Rent-a-NPC. All rights reserved. 