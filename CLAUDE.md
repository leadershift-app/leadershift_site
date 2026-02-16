# LeaderShift Marketing Site

Static marketing and legal site for the LeaderShift iOS app (AI leadership coaching for public safety professionals). Hosted on GitHub Pages at leadershift.app.

## Key Info

- **Entity**: LeaderShift, LLC (Wyoming)
- **Address**: 30 North Gould Street, Ste N, Sheridan, WY 82801
- **Support email**: support@leadershift.app
- **Privacy email**: privacy@leadershift.app
- **Domain**: leadershift.app (GoDaddy DNS, GitHub Pages hosting)

## Structure

- `index.html` - Landing page
- `terms.html` - Terms of Service (required for App Store)
- `privacy.html` - Privacy Policy (required for App Store)
- `404.html` - Custom error page
- `CNAME` - GitHub Pages custom domain config
- `images/` - OG image, favicon variants, app screenshots

## Deployment

Push to `main` branch. GitHub Pages deploys automatically. No build step.

## Design System

- **Fonts**: Cormorant Garamond (headings), Outfit (body) via Google Fonts
- **Colors**: CSS custom properties in `:root` of each file. Key tokens: `--deep-slate-dark` (bg), `--warm-bronze` (accent), `--off-white` (text)
- **Style**: Dark, premium, trust-focused. Short declarative sentences. No emojis.
- All CSS is inline per file (no shared stylesheet)

## Conventions

- All pages are self-contained HTML with inline CSS. No build tools, no shared CSS file.
- New pages must include: meta description, OG tags, Twitter Card tags, favicon links, and the same nav/footer pattern.
- OG image path: `https://leadershift.app/images/og-image.png` (1200x630)
- Favicon: `images/favicon-32x32.png` (32x32), `images/apple-touch-icon.png` (180x180)
- Legal pages link back to home with `← Back to Home` nav pattern.
- Footer on legal pages: logo + copyright only. Footer on index: logo, tagline, legal links, copyright.

## Brand Voice

- Audience: senior public safety professionals (Sergeants through Chiefs)
- Tone: confident, direct, understated. Trust and privacy are central themes.
- Use public safety cultural language where appropriate (ride-along, roster, shift)
- Never use em dashes. Use commas, periods, or restructure sentences instead.

## Planned Pages

- Support/FAQ page
- About/Team page
- Blog/Content section
- App Store redirect page
