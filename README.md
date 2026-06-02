# Paddy Walsh — MES Engineer CV

Online CV portfolio for **Paddy Walsh**, MES Engineer and POMSnet Aquila SME.

---

## File Structure

```
/
├── index.html              ← Portfolio CV (GitHub Pages entry point)
├── styles.css              ← Portfolio stylesheet
├── ats-cv.html             ← ATS-optimised Word-style CV (print to PDF)
├── assets/
│   ├── favicon.svg         ← Site icon
│   ├── Paddy_Walsh_CV.pdf  ← Add your exported PDF here (see below)
│   └── PLACE_PDF_HERE.txt  ← Instructions for PDF placement
└── README.md               ← This file
```

---

## How to Export the PDF

1. Open `ats-cv.html` in **Chrome or Edge**
2. Click **Print / Save as PDF**
3. Set Destination: **Save as PDF**
4. Set Margins: **None**
5. Enable **Background graphics** (checkbox in More settings)
6. Save as `Paddy_Walsh_CV.pdf` into the `assets/` folder
7. The **Download PDF CV** button in `index.html` will now work

---

## GitHub Pages Deployment

### Step 1 — Create the repository

1. Go to [github.com](https://github.com) → click **New repository**
2. Name it `cv` or `paddy-walsh-cv` (or any name you prefer)
3. Set visibility to **Public**
4. Leave "Add a README" unchecked (you already have one)
5. Click **Create repository**

### Step 2 — Push your files

Open a terminal in the `D:\My_CV` folder and run:

```bash
git init
git add .
git commit -m "Initial CV deployment"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

Replace `YOUR-USERNAME` and `YOUR-REPO` with your GitHub username and repository name.

### Step 3 — Enable GitHub Pages

1. Open your repository on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Set Branch to `main` / `/ (root)`
5. Click **Save**

GitHub will show a banner: *"Your site is live at..."*

Allow 1–2 minutes for the first deployment.

### Step 4 — Update social links

Edit `index.html` and replace the `href="#"` placeholders:

```html
<!-- LinkedIn -->
<a href="https://www.linkedin.com/in/YOUR-PROFILE" ...>LinkedIn</a>

<!-- GitHub -->
<a href="https://github.com/YOUR-USERNAME" ...>GitHub</a>
```

---

## Your URLs

After deployment:

| Page | URL |
|------|-----|
| Portfolio CV | `https://YOUR-USERNAME.github.io/YOUR-REPO/` |
| ATS CV (print) | `https://YOUR-USERNAME.github.io/YOUR-REPO/ats-cv.html` |
| PDF download | `https://YOUR-USERNAME.github.io/YOUR-REPO/assets/Paddy_Walsh_CV.pdf` |

---

## Local Preview

Open `index.html` directly in Chrome/Edge to preview. No server required — all paths are relative.

---

## Notes

- `index.html` is the **online profile only** — not the official CV
- `ats-cv.html` is the **ATS-optimised version** — use this to print the PDF
- The PDF in `assets/` is what the **Download** button serves
- Social links (LinkedIn, GitHub) are placeholders — update `index.html` with real URLs
- `favicon.svg` works in all modern browsers; for legacy `.ico` support, add a `favicon.ico` to the root
