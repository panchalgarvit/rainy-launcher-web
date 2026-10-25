# 🌧️ Rainy Launcher Website

Official landing & download website for **Rainy Launcher v1.0**.

---

## 🚀 How to Deploy on Vercel (2-Minute Guide)

### Option A: Using GitHub (Recommended)
1. **Create a new repository** on [GitHub](https://github.com/new) (e.g. `rainy-launcher-website`).
2. **Upload all the files** from this folder into the repository:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `vercel.json`
   - `Rainy_Launcher_v1.apk`
   - `assets/logo.png`
3. Go to [Vercel](https://vercel.com/) and click **"Add New..." → "Project"**.
4. Import your new GitHub repository.
5. Click **"Deploy"** (Vercel automatically recognizes this static site with zero configuration!).
6. Your website is now live with a free `*.vercel.app` URL and direct APK downloads!

---

### Option B: Deploy Directly with Vercel CLI
If you have Node.js / Vercel CLI installed:
```bash
cd rainy-launcher-website
npx vercel
```
Follow the quick prompts and your site is live immediately!

---

## 📦 What's Included:
- **`index.html`**: Responsive landing page with SKLauncher dark aesthetics, feature grid, interactive UI preview, installation guide, and FAQ. Links directly to your GitHub Release for fast global CDN downloads.
- **`styles.css`**: Modern glassmorphism styling, gradients, and responsive breakpoints.
- **`script.js`**: Interactive accordion and download toast alerts.
- **`assets/logo.png`**: High-resolution branding logo.
- **`vercel.json`**: Routing configuration for Vercel.
