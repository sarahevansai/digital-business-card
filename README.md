# 📱 Digital Business Card Generator

> Turn your phone lock screen into a networking machine — in 60 seconds.

A free, open-source tool that generates a complete digital business card system: lock screen wallpaper with QR code, branded contact card page, vCard file, and everything packaged as a downloadable zip.

**No sign-up. No account. No tracking. Just your info → your card.**

## 🔗 Try It

👉 **[Generate Your Card](https://sarahevansai.github.io/digital-business-card/)**

## How It Works

```
Fill in your info → Preview live → Download everything
```

1. **Enter your details** — name, title, company, email, links
2. **Pick an accent color** — purple, teal, pink, orange, green, or white
3. **Preview in real-time** — see your lock screen update as you type
4. **Download** — lock screen image, contact card page, vCard, or everything as a zip

### What You Get

| File | What It Does |
|------|-------------|
| `lockscreen.png` | Phone wallpaper with your name + QR code |
| `card.html` | Contact card page — deploy anywhere |
| `.vcf` | vCard file — "Save Contact" in one tap |
| `README.md` | Setup instructions |

## 📱 The Flow

```
Someone sees your lock screen
    → Scans the QR code
        → Lands on your contact card
            → Saves your info or emails you
```

## 🛠️ Self-Host / Customize

```bash
git clone https://github.com/sarahevansai/digital-business-card.git
cd digital-business-card
# Open index.html in a browser — that's it
```

No dependencies. No build step. No framework. Just HTML + vanilla JS.

### Deploy Your Contact Card

The generated `card.html` works on any static host:

```bash
# Vercel
vercel --prod

# Netlify
netlify deploy --prod

# GitHub Pages
# Just push card.html to a repo with Pages enabled
```

## Tech

- **Vanilla JS** — zero dependencies for the generator
- **Canvas API** — real-time lock screen preview + image export
- **QRCode.js** — QR generation with high error correction
- **JSZip** — client-side zip packaging
- All processing happens **in your browser** — nothing is sent to any server

## License

MIT — do whatever you want with it.

---

Built by [Sarah Evans](https://asksarah.ai) — AI Visibility Architect, Partner & Head of PR at [Zen Media](https://zenmedia.com)
