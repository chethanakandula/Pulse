# Pulse — AI × Design, distilled weekly.

## Deploy (5 minutes)

1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → New Project → Import your repo
3. Deploy (no build step needed — it's all static HTML)
4. Optional: point a custom domain (e.g. `pulse.design`)

## File structure

```
pulse/
├── index.html              ← Latest issue (homepage)
├── info.html               ← Sources + how we find signal
├── archive/
│   ├── index.html          ← Archive listing
│   └── 14/index.html       ← Issue #14
├── CLAUDE_PROJECT_PROMPT.md ← Paste into Claude Project for weekly automation
└── README.md
```

## Weekly workflow

1. **Sunday**: Open your Claude Project, type "write issue 15"
2. **Monday morning**: Review, edit, paste HTML into a new `archive/15/index.html`
3. **Update** `index.html` with the new issue content
4. **Add** a line to `archive/index.html`
5. **Push** to GitHub → auto-deploys

## Theme

- **Light mode** (default): Soft Signal — warm off-white, sage green accent
- **Dark mode**: Midnight Lime — near-black, lime green accent
- Toggle in the nav next to the Pulse logo
