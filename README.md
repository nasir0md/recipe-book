# My Recipe Book

A personal recipe site hosted on GitHub Pages.

## File structure

```
my-recipe-book/
├── index.html              ← Home page (recipe listing)
└── recipes/
    ├── moong-jackfruit-dal.html
    └── your-next-recipe.html   ← add new recipes here
```

---

## 🚀 How to get this live on GitHub Pages

### Step 1 — Create a GitHub account
If you don't have one: https://github.com/signup

### Step 2 — Create a new repository
1. Go to https://github.com/new
2. Name it `recipe-book` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the files
1. On your new repo page, click **"uploading an existing file"**
2. Drag and drop the entire contents of this folder:
   - `index.html`
   - the `recipes/` folder and everything inside it
3. Scroll down, click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repo **Settings** (top tab)
2. Click **Pages** in the left sidebar
3. Under "Branch", select `main` and `/ (root)` — click **Save**
4. Wait ~60 seconds, then your site is live at:
   **`https://YOUR-USERNAME.github.io/recipe-book/`**

---

## ➕ Adding a new recipe later

1. Get Claude to generate a new recipe HTML (same style as the existing ones)
2. Save it in the `recipes/` folder — e.g. `recipes/chicken-curry.html`
3. Open `index.html` and copy the recipe card block, update the link, title, description and tags
4. Upload both files to GitHub (drag & drop into the repo, same as Step 3)
5. Done — the site updates in ~30 seconds

---

## 🔗 Custom domain (optional, later)

If you ever want `myrecipes.com` instead of `github.io`:
1. Buy a domain (Cloudflare Registrar is cheap)
2. In GitHub Pages settings, enter your domain under "Custom domain"
3. Follow the DNS instructions shown
