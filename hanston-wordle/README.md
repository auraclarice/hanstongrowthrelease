# Hanston Wordle — GROWTH Reveal

A branded Wordle game for Hanston Properties' new core value reveal.
The answer is **GROWTH** — 6 letters, 6 tries.

---

## Deploy to Vercel (3 steps)

### Option A — Vercel Dashboard (easiest, no CLI needed)

1. Go to [vercel.com](https://vercel.com) and log in (or sign up free)
2. Click **"Add New Project"** → **"Deploy"**
3. Drag and drop this entire folder (`hanston-wordle`) into the upload area
4. Click **Deploy** — done! You'll get a live URL in ~30 seconds.

### Option B — Vercel CLI

```bash
# Install Vercel CLI (one-time)
npm install -g vercel

# From inside the hanston-wordle folder
cd hanston-wordle
vercel

# Follow prompts — deploy to production:
vercel --prod
```

---

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire game — all HTML, CSS, JS in one file |
| `vercel.json` | Tells Vercel this is a static site |
| `README.md` | This file |

---

## Branding Applied

- **Colors:** Navy `#19315B` + Gold `#C9A84C` (Hanston brand palette)
- **Fonts:** DM Serif Display + DM Sans (loaded from Google Fonts)
- **Voice:** Grounded, confident — no hype, no emojis
- **EVP tagline** on win modal: *"Built to Last, Crafted by Hanston"*
- **EVP quote** on win modal: *"Here at Hanston, careers are built to last — grounded in clear, honest, and respectful work."*

---

## Customization

To change the answer (if needed for future reveals), find this line in `index.html`:

```js
const ANSWER = 'GROWTH';
const WORD_LENGTH = 6;
```

Change both values to match the new word. Also update the `VALID_WORDS` set if the word isn't already there.

---

*Hanston Properties · People & Culture · 2026*
