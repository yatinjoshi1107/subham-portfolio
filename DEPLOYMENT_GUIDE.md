# 🚀 Portfolio Deployment Guide

## Quick Options to Host Your Portfolio

### Option 1: Netlify (EASIEST - Recommended) ⭐
**No technical knowledge needed!**

1. Go to https://www.netlify.com
2. Sign up for free (can use GitHub, email, etc.)
3. Drag and drop your entire project folder onto the Netlify dashboard
4. Your site will be live in 30 seconds!
5. You'll get a URL like: `https://random-name-123.netlify.app`
6. You can customize the name later in Site Settings > Domain Settings

**Advantages:**
- ✅ Easiest method
- ✅ Instant deployment
- ✅ Free custom domain
- ✅ HTTPS automatically
- ✅ No git required

---

### Option 2: GitHub Pages (FREE)
**Best if you already use GitHub**

#### Step 1: Create GitHub Repository
1. Go to https://github.com and sign in (create account if needed)
2. Click the "+" icon → "New repository"
3. Name it: `portfolio` (or any name you like)
4. Make it **Public**
5. Don't initialize with README
6. Click "Create repository"

#### Step 2: Upload Your Files
**Method A - Using Git (Recommended):**
```bash
# In your project folder, run these commands:
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main
```
(Replace YOUR_USERNAME with your GitHub username)

**Method B - Using GitHub Web Interface:**
1. On your new repository page, click "uploading an existing file"
2. Drag and drop all your files (index.html, styles.css, script.js, README.md)
3. Click "Commit changes"

#### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click "Save"
7. Wait 1-2 minutes
8. Your site will be live at: `https://YOUR_USERNAME.github.io/portfolio/`

---

### Option 3: Vercel (FREE)
**Great for developers**

1. Go to https://vercel.com
2. Sign up with GitHub (or email)
3. Click "Add New Project"
4. Import your GitHub repository (or drag and drop)
5. Click "Deploy"
6. Your site will be live instantly!

**Advantages:**
- ✅ Very fast
- ✅ Great performance
- ✅ Free custom domain
- ✅ Auto-deploys on updates

---

## 📝 Customizing Your Domain Name

### Netlify:
1. Go to Site Settings → Domain Settings
2. Click "Add custom domain" or "Options" → "Edit site name"
3. Change to something like: `shubham-portfolio.netlify.app`

### GitHub Pages:
1. Go to Repository Settings → Pages
2. The default is: `YOUR_USERNAME.github.io/portfolio`
3. To get `YOUR_USERNAME.github.io` (cleaner URL):
   - Rename repository to: `YOUR_USERNAME.github.io`
   - Wait a few minutes
   - Site will be at: `https://YOUR_USERNAME.github.io`

---

## 🔗 Sharing Your Portfolio

Once deployed, you'll get a URL. Share this with recruiters:

**Example:**
- ✅ `https://shubham-portfolio.netlify.app`
- ✅ `https://shubham-rajput.github.io/portfolio`
- ✅ `https://shubham-portfolio.vercel.app`

**Pro Tips:**
1. Add the URL to your resume
2. Add it to your LinkedIn profile
3. Add it to your email signature
4. Add it to your Behance profile

---

## 📧 Adding Resume Download

To add a downloadable resume:

1. Save your resume as `resume.pdf` in the project folder
2. Add this button to your Hero section in `index.html`:
```html
<a href="resume.pdf" download class="btn btn-primary">Download Resume</a>
```

---

## 🎨 Making Updates

After deploying:

### Netlify:
- Just drag and drop the folder again
- Or connect to Git for auto-deploy

### GitHub Pages:
- Make changes locally
- Commit and push:
  ```bash
  git add .
  git commit -m "Update portfolio"
  git push
  ```
- Changes go live in 1-2 minutes

---

## 💡 Recommendation

**For beginners:** Use **Netlify** - it's the easiest!

**For professionals:** Use **GitHub Pages** or **Vercel** - more control

---

Need help? Let me know which option you prefer and I'll guide you through it!
