# LeaderShift Marketing Site

Static marketing and legal site for the LeaderShift iOS app (AI-powered peer support and professional development for public safety professionals). Hosted on GitHub Pages at leadershift.app.

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

## Language: Legal Terminology (Critical)

**Never use "coaching" to describe what LeaderShift does.** The product operates under legally protected frameworks of peer-to-peer counseling and professional development, not coaching. This distinction has legal standing and must be maintained across all copy, marketing, legal pages, and code comments.

**Approved terms** (use these consistently):
- Peer support / peer-to-peer support
- Peer counseling / peer-to-peer counseling
- Professional development support / professional development partner
- Digital peer support partner
- Privileged communication / professional counseling
- Peer-to-peer discussion
- Expert-trained peer support

**Never use:**
- "Coaching" or "coach" in any context describing LeaderShift's service
- "AI coach" or "leadership coach"
- "Coaching session" or "coaching platform"
- "AI chat" or "chatbot" (use "conversational AI tool", "digital partner", or similar)
- "Always on" (use "always available" instead)
- "Companion" as a standalone descriptor (use "digital partner")

**Personification rules:**
- Never refer to the app as a person or use "who" when describing LeaderShift. Use "that" instead.
- Never use "Someone" or "advisor" to describe the app. It is a tool, not a person.
- Always call it "digital partner", never just "partner" alone.

**Identity and positioning:**
- Always emphasize: built BY public safety professionals, FOR public safety leaders.
- Emphasize personal ownership. The app is "yours alone", "outside of department control".
- Use "No department access" sparingly. Prefer "outside of department control" to emphasize user ownership over institutional exclusion.

When describing the app, frame it as a peer support and professional development tool, not a coaching product. The peer counseling and privileged communication framing carries stronger legal protections.

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
