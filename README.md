# DIVA 2.0 – ADHD Diagnostic Interview (English)

Interactive web app for administering the DIVA 2.0 structured interview.  
Built with React + Vite. Session data persists in `localStorage`.

> ⚠️ This tool is a clinical aid and does not replace the judgment of a qualified healthcare professional. ADHD diagnosis must be made by a trained clinician.  
> Based on Kooij & Francken, 2010 — DIVA Foundation.

---

## Deploy on Vercel (recommended)

### Option A — Via Vercel dashboard (no CLI needed)

1. Push this repository to GitHub
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import your GitHub repository
4. Vercel auto-detects Vite — leave all settings as default
5. Click **Deploy** → your app is live in ~30 seconds

### Option B — Via Vercel CLI

```bash
npm install -g vercel
vercel        # follow the prompts
```

---

## Local development

```bash
npm install
npm run dev
```

Then open [http://localhost:5173](http://localhost:5173).

## Build for production

```bash
npm run build
# Output is in /dist — ready to deploy anywhere
```
