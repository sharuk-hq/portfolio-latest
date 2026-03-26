# Sharuk Khan — Portfolio Website

A clean, dark-themed personal portfolio website built with pure HTML, CSS, and JavaScript. Designed for GitHub Pages deployment.

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click **"New repository"**
3. Name it exactly: `<your-username>.github.io`
   - Example: if your username is `sharuk-khan`, name it `sharuk-khan.github.io`
4. Set it to **Public**
5. Click **"Create repository"**

### Step 2 — Upload the File
1. Open your new repository
2. Click **"Add file" → "Upload files"**
3. Upload `index.html`
4. Scroll down and click **"Commit changes"**

### Step 3 — Enable GitHub Pages
1. Go to **Settings** (top tab of your repository)
2. Scroll to **"Pages"** in the left sidebar
3. Under **"Source"**, select **"Deploy from a branch"**
4. Choose branch: `main`, folder: `/ (root)`
5. Click **Save**

### Step 4 — Your Site is Live!
After 1–2 minutes, your portfolio will be live at:
```
https://<your-username>.github.io
```

---

## 🛠 Personalising the Portfolio

Open `index.html` in any text editor (Notepad, VS Code, etc.) and update:

| What to change | Where to find it |
|---|---|
| LinkedIn URL | Search for `href="https://www.linkedin.com/in/"` |
| Email address | Search for `href="mailto:"` |
| Footer year/text | Search for `© 2025 Sharuk Khan` |
| Stats (followers, connections) | Search for `stat-num` class entries |

---

## 📁 File Structure

```
your-repo/
└── index.html       ← entire site (single file, no dependencies)
```

No build tools, no npm, no frameworks required. Just one HTML file.

---

## ✨ Features

- Fully responsive (mobile + desktop)
- Dark theme with green accent palette
- Smooth scroll + fade-in animations
- Sections: Hero, About, Experience, Education, Publications, Certifications, Languages, Contact
- Zero external dependencies (fonts loaded from Google Fonts CDN)
