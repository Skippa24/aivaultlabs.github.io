# 🚀 AIVault Labs Website Setup Guide

This guide walks you through deploying your **AIVault Labs** website using **GitHub Pages** and the included assets.

---

## 📁 Folder Structure
```
aivaultlabs.github.io/
│
├── index.html                # Main website file
├── assets/
│   ├── logo.png
│   ├── hero.png
│   └── AIVaultLabs_Whitepaper_Light.pdf
└── README.md                 # This guide
```

---

## 🌐 Step 1: Create Your GitHub Repository

1. Log into GitHub and create a new **public** repository named:
   ```
   aivaultlabs.github.io
   ```

2. Upload your files from this package:
   - `index.html`
   - The entire `assets/` folder
   - (Optional) This `README.md` file

3. Commit and push the files to the **main** branch.

---

## ⚙️ Step 2: Enable GitHub Pages

1. Go to your repository → **Settings → Pages**  
2. Under “Source,” choose **Deploy from branch**.  
3. Set:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**.

✅ Your site will publish at:
```
https://aivaultlabs.github.io
```

---

## 🌍 Step 3: Connect Custom Domain (Optional)

If you own **aivaultlabs.com**, connect it by:

1. Creating a file in your repo named:
   ```
   CNAME
   ```
   and adding this inside:
   ```
   aivaultlabs.com
   ```

2. In your **domain DNS settings** (Squarespace, GoDaddy, etc.), add:

   | Type | Host | Value |
   |------|------|--------|
   | A | @ | 185.199.108.153 |
   | A | @ | 185.199.109.153 |
   | A | @ | 185.199.110.153 |
   | A | @ | 185.199.111.153 |
   | CNAME | www | aivaultlabs.github.io |

3. Wait up to **24 hours** for propagation.

---

## 🔒 Step 4: Enable HTTPS

Once your domain is active:

- Go back to **Settings → Pages**.  
- Enable **“Enforce HTTPS”**.

This ensures your site runs securely at:
```
https://aivaultlabs.com
```

---

## 📄 Step 5: Customize Content

You can edit your `index.html` using any text editor or code editor (VS Code recommended).  
All text is clearly commented for easy customization.

Key sections you can edit:
- **Mission / Problem / Solution**
- **Treasury Structure**
- **Token Utility**
- **Roadmap**
- **Governance**
- **Contact / Socials**

---

## 🧠 Optional Enhancements

- Add Google Analytics or Plausible for metrics.  
- Use Mailchimp/Beehiiv for email subscriptions.  
- Replace placeholder links with your real **X (Twitter)**, **Discord**, and **Telegram** URLs.

---

## 📅 Generated

This README was generated on **November 07, 2025**  
by ChatGPT (AIVault Labs setup assistant).

