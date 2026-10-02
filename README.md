# Wade "Weet-Bix" Hammond — Personal Site

Static one-page site. No build step.

## Deploy to GitHub Pages

```bash
# 1. Create a repo on GitHub (e.g. wade-hammond)
# 2. Push from this folder:
cd wade-hammond
git init
git add -A
git commit -m "Initial site"
git branch -M main
git remote add origin git@github.com:YOUR_USERNAME/wade-hammond.git
git push -u origin main
```

3. Go to **Settings → Pages** in the GitHub repo.
4. Under **Source**, select **Deploy from a branch**.
5. Choose **main** branch, **/ (root)** folder.
6. Click **Save**. The site will be live at `https://YOUR_USERNAME.github.io/wade-hammond/` within a minute.

## Images

Place these in `/assets`:
- `hero.jpg` — hero background (compress to <300 KB)
- `coaching.jpg` — coaching section photo
- `wks.jpg` — WKS Africa section photo
- `og.jpg` — Open Graph image, 1200×630

## TODOs

See the TODO list in the main conversation.
