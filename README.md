# Nourish

**Nourish** is a private, single-page **pregnancy nutrition companion**—meal logging, trimester-aware ideas, and gentle tracking with **no backend, no login, and no database**.

## Contents of this folder

| File | Purpose |
|------|---------|
| `index.html` | The full app (includes embedded offline fonts). |
| `nourish-icon.png` | Bookmark / home-screen icon. |
| `buyer-setup-guide.md` | Setup, privacy, backup, troubleshooting. |

## Static hosting (GitHub Pages)

1. Upload **everything** in this folder to a new repo **root**.
2. **Settings → Pages** → deploy **main** branch, **`/ (root)`**.
3. Distribute the published HTTPS URL to buyers.

### Local preview

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080/`.

## Privacy & data

**Private web app. No login, no subscription.** Your data stays **in browser storage** on the device you use.

**If you clear browser data or switch devices, export a backup first.**

## Icon

Replace **nourish-icon.png** or update `<link rel="icon">` / `apple-touch-icon` in **index.html** if you rename assets.
