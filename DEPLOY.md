# Deploy MeltItDown to GitHub Pages

## What you need

- A GitHub account (free) → [github.com](https://github.com)
- The file `index.html` (rename from `meltitdown.html`)
- 5 minutes

---

## Step-by-step

### 1. Create a GitHub account (skip if you already have one)

1. Go to [github.com/signup](https://github.com/signup)
2. Enter email, password, and username
3. Verify your email

---

### 2. Create a new repository

1. Go to [github.com/new](https://github.com/new)
2. Fill in:
   - **Repository name:** `meltitdown`
   - **Description:** *(optional)* File to Markdown converter
   - **Visibility:** ✅ Public *(required for free GitHub Pages)*
   - Leave all other options as default
3. Click **Create repository**

---

### 3. Upload your file

1. On the new repo page, click **"uploading an existing file"** (or drag & drop)
2. Rename `meltitdown.html` → **`index.html`** before uploading
3. Also upload `README.md`
4. Scroll down to **Commit changes**
5. Leave the default message or write `Initial release`
6. Click **Commit changes**

---

### 4. Enable GitHub Pages

1. In your repo, click **Settings** (top tab)
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**
5. Wait ~60 seconds

---

### 5. Your app is live

GitHub will show:

```
Your site is live at https://your-username.github.io/meltitdown
```

Open that URL. Done.

---

## Update the app in the future

1. Go to your repo on GitHub
2. Click on `index.html`
3. Click the **pencil icon** (Edit)  
   *— or —*  
   Click **"Add file" → "Upload files"** and upload the new version
4. Commit changes
5. GitHub Pages updates automatically in ~30 seconds

---

## Update the README link

After your site is live, open `README.md` and replace:

```
https://your-username.github.io/meltitdown
```

with your actual URL.

---

## Troubleshooting

| Problem | Solution |
|---|---|
| Page shows 404 | Wait 2 minutes, then hard refresh (Ctrl+Shift+R) |
| Page shows raw HTML | Make sure the file is named exactly `index.html` |
| GitHub Pages option missing | Repository must be **Public** |
| Images not converting | Enter your AI provider API key in the app |

---

## Custom domain (optional)

If you have a domain like `meltitdown.com`:

1. In repo **Settings → Pages → Custom domain**
2. Enter your domain
3. Add a CNAME record in your DNS pointing to `your-username.github.io`

---

## Cost

| Service | Cost |
|---|---|
| GitHub Pages hosting | **Free** |
| PDF / DOCX / XLSX conversion | **Free** (runs locally) |
| Image conversion (AI) | Pay-per-use to your AI provider |

Anthropic, OpenAI, and Gemini all offer free tiers sufficient for occasional use.

