# Deploy to Cloudflare Pages (Free)

Your landing page is ready! Here's how to deploy it:

## Option 1: Deploy via GitHub (Recommended - Auto-Deploy)

### Step 1: Push to GitHub
```bash
# Initialize git repo (if not already done)
git init
git add .
git commit -m "Initial landing page"
git remote add origin https://github.com/YOUR_USERNAME/landing-page.git
git branch -M main
git push -u origin main
```

### Step 2: Connect to Cloudflare Pages
1. Go to [dash.cloudflare.com](https://dash.cloudflare.com)
2. Sign up for free (if you don't have an account)
3. Click **Pages** in the left sidebar
4. Click **Create a project** → **Connect to Git**
5. Authorize GitHub and select your repository
6. Leave build settings empty (no build step needed)
7. Click **Save and Deploy**

**Done!** Your site will be live at `your-repo-name.pages.dev`

---

## Option 2: Direct Upload (Quick Test)

### Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com) and create a free account
2. Create a new public repository named `landing-page`

### Step 2: Upload Files
```bash
# Clone the empty repo
git clone https://github.com/YOUR_USERNAME/landing-page.git
cd landing-page

# Copy your files (index.html, styles.css, script.js) into this folder
# Then push:
git add .
git commit -m "Initial landing page"
git push -u origin main
```

### Step 3: Deploy on Cloudflare
- Follow the "Connect to Cloudflare Pages" steps above

---

## Option 3: Drag & Drop (Simplest - No Git)

1. Go to [dash.cloudflare.com](https://dash.cloudflare.com)
2. Click **Pages** → **Create a project** → **Direct upload**
3. Drag and drop your `index.html`, `styles.css`, and `script.js` files
4. Click **Deploy site**

**Done!** Your site will be live instantly on a free `*.pages.dev` URL

---

## Connect Custom Domain (Optional)

Once deployed, you can add your own domain:

1. Go to **Pages** → Your project → **Custom domains**
2. Click **Setup custom domain**
3. Follow the DNS setup instructions

---

## What You Get (Free Forever)

✅ Unlimited bandwidth
✅ Free SSL/TLS certificate
✅ Global CDN
✅ Automatic deployments (if using GitHub)
✅ Fast page loads everywhere
✅ No credit card required
✅ Up to 500 deployments/month

---

## Files in This Project

- `index.html` - Landing page structure
- `styles.css` - Modern responsive design
- `script.js` - Interactivity and smooth scrolling
- `CLOUDFLARE_DEPLOYMENT.md` - This file

---

## Tips

- The site is fully responsive (works on mobile, tablet, desktop)
- All features (smooth scrolling, form validation) work out of the box
- No dependencies or build step required
- Edit HTML/CSS/JS and push to GitHub to auto-update your live site

**Start with Option 3 (Drag & Drop) if you want the fastest result!**
