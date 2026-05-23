# Kasula Vasanth — Portfolio
> IBM-certified Data Scientist & AI/ML Engineer · Hyderabad, India

🌐 **Live site:** https://vasanthkasula.github.io/vasanth-portfolio

---

## Files in this repo

| File | Purpose |
|------|---------|
| `index.html` | **Entire portfolio** (single self-contained file) |
| `_config.yml` | GitHub Pages configuration |
| `.nojekyll` | Tells GitHub Pages to skip Jekyll processing |
| `README.md` | This file |

---

## How to deploy on GitHub Pages

### Option A — Upload via GitHub website (easiest)
1. Go to **github.com/vasanthkasula/vasanth-portfolio**
2. Click **Add file → Upload files**
3. Drag and drop all 4 files from this ZIP
4. Click **Commit changes**
5. Go to **Settings → Pages**
6. Under **Source** → select **Deploy from a branch**
7. Branch: **main** | Folder: **/ (root)** → click **Save**
8. Wait ~60 seconds → site is live!

### Option B — Git command line
```bash
git clone https://github.com/vasanthkasula/vasanth-portfolio
cd vasanth-portfolio
# copy all 4 files here, then:
git add .
git commit -m "Deploy portfolio"
git push
```

---

## What auto-updates (no code changes ever needed)

Every time someone visits your portfolio, the site **automatically fetches from GitHub API**:

- ✅ Your **avatar photo**
- ✅ **Follower / following** counts  
- ✅ **Repo count** (KPI card)
- ✅ **All your public repos** — names, descriptions, languages, stars, forks, last updated
- ✅ Filter repos by Python / HTML / Jupyter / Starred

**Push a new repo → it appears on your portfolio automatically.**

---

## How to add a new featured project

Open `index.html`, find `<!-- FEATURED PROJECTS -->` and paste a new card block:

```html
<a class="pj" href="YOUR_GITHUB_OR_LIVE_LINK" target="_blank" style="--ca:#05d490">
  <div class="pj-accent"></div>
  <div class="pj-top">
    <div class="pj-ico">🔬</div>
    <div class="tag-row2">
      <span class="ptag live">Live</span>
      <span class="ptag ml">ML</span>
    </div>
  </div>
  <div class="pj-title">Your Project Title</div>
  <div class="pj-desc">Short description of what it does and why it matters.</div>
  <div class="pj-chips">
    <span class="pj-chip">Key metric</span>
    <span class="pj-chip">Another stat</span>
  </div>
  <div class="pj-ft">
    <div class="pj-stack">
      <span class="pj-stag">Python</span>
      <span class="pj-stag">TensorFlow</span>
    </div>
    <span class="pj-date" style="color:#05d490">MM/YYYY</span>
  </div>
</a>
```

**Badge classes:** `live` `ml` `gen` `rag` `web`  
**Card accent color:** change `--ca:#05d490` to any hex  

---

## Keyboard shortcut

Press **← →** arrow keys to switch between tabs on the portfolio.

---

© 2026 Kasula Vasanth — kasulavasanth55@gmail.com
