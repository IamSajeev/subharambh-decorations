# Deploy Subharambh Decorations to GitHub Pages

## ✅ Current Status

Your repository is **already configured for GitHub Pages deployment**! 🎉

### What's Already Set Up:
- ✅ `.git` repository initialized
- ✅ GitHub Actions workflow configured (`.github/workflows/pages.yml`)
- ✅ `.gitignore` file in place
- ✅ Auto-deploy on push enabled

---

## 🚀 Step-by-Step Deployment Guide

### Step 1: Create a GitHub Account (if you don't have one)
1. Go to [github.com](https://github.com)
2. Sign up for a free account
3. Verify your email

### Step 2: Create a New Repository on GitHub

1. Log in to GitHub
2. Click **+** icon in top right → **New repository**
3. Fill in details:
   - **Repository name**: `subharambh-decorations`
   - **Description**: "Professional decoration company website"
   - **Public**: ✅ (required for free GitHub Pages)
   - **Add .gitignore**: No (already have one)
   - **Add LICENSE**: No (already have one)
4. Click **Create repository**

### Step 3: Connect Your Local Repository

Copy the commands shown on GitHub after creating the repo. It will look like:

```bash
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/subharambh-decorations.git
git push -u origin main
```

**Run these commands in your terminal** (in the project folder):

```bash
# Navigate to your project folder
cd c:\Users\sajee\subharambh-decorations

# Set main branch (if needed)
git branch -M main

# Add remote (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/subharambh-decorations.git

# Push to GitHub
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Click **Pages** (left sidebar under "Code and automation")
4. Under **Source**, select:
   - Branch: **main**
   - Folder: **/ (root)**
5. Click **Save**

### Step 5: Wait for Deployment

1. GitHub Actions will automatically run
2. Go to **Actions** tab to see deployment status
3. Workflow should complete in 1-2 minutes
4. You'll see a green checkmark ✅ when done

### Step 6: Access Your Website

Your site will be live at:
```
https://YOUR_USERNAME.github.io/subharambh-decorations/
```

**Example**: If your GitHub username is "john-smith", your URL would be:
```
https://john-smith.github.io/subharambh-decorations/
```

---

## 🔧 Required Setup Checklist

### Before First Push:
- [ ] GitHub account created
- [ ] Repository created on GitHub
- [ ] Local git configured

### First Time Setup (One Time):
```bash
# Configure git (replace with your info)
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Optional: Setup SSH (more secure than HTTPS)
# Follow GitHub's SSH setup guide
```

### First Push:
```bash
# Check status
git status

# Add all files
git add .

# Commit changes
git commit -m "Initial commit - Subharambh Decorations website"

# Push to GitHub
git push -u origin main
```

### Future Updates:
```bash
# Make your changes locally
# Then:
git add .
git commit -m "Updated gallery images"
git push
```

---

## 📋 Pre-Deployment Checklist

Before pushing to GitHub, verify:

- [ ] All placeholder text replaced with real contact info
- [ ] Phone number updated in all files
- [ ] Email address updated in all files
- [ ] Location information updated
- [ ] WhatsApp link updated
- [ ] Gallery images added (or placeholder text removed)
- [ ] Testimonials updated
- [ ] Links tested locally
- [ ] Website works in browser
- [ ] Responsive design checked on mobile

**⚠️ Important**: Update your contact information BEFORE pushing!

---

## 🌐 GitHub Pages URL Structure

### Your URL Format:
```
https://github-username.github.io/repository-name/
```

### Your Website Pages:
- Home: `https://github-username.github.io/subharambh-decorations/`
- About: `https://github-username.github.io/subharambh-decorations/about.html`
- Services: `https://github-username.github.io/subharambh-decorations/services.html`
- Gallery: `https://github-username.github.io/subharambh-decorations/gallery.html`
- Contact: `https://github-username.github.io/subharambh-decorations/contact.html`

---

## 🎯 GitHub Actions Workflow Explained

Your `.github/workflows/pages.yml` file automatically:

1. **Triggers** on every push to `main` branch
2. **Checks out** your code
3. **Uploads** all files as GitHub Pages artifact
4. **Deploys** to GitHub Pages servers
5. **Updates** your live website

**Status**: Check **Actions** tab in your GitHub repository to see deployment history.

---

## 🔄 Making Updates

After initial deployment, updating is simple:

```bash
# 1. Make changes to your files locally
# (e.g., update gallery.html, contact info, etc.)

# 2. Commit and push changes
git add .
git commit -m "Updated gallery with new photos"
git push

# 3. GitHub Actions automatically deploys
# 4. Your live site updates within 1-2 minutes
```

---

## ⚡ Quick Commands Reference

```bash
# Check git status
git status

# Add files for commit
git add .
git add filename.html          # Single file

# Commit with message
git commit -m "Your message here"

# Push to GitHub
git push

# View commit history
git log

# Check remote URLs
git remote -v
```

---

## 🆘 Troubleshooting

### Issue: "fatal: not a git repository"
**Solution**: Make sure you're in the correct folder:
```bash
cd c:\Users\sajee\subharambh-decorations
```

### Issue: "fatal: Could not read Username for 'https://github.com'"
**Solution**: One of these methods:
1. Use GitHub token instead of password
2. Set up SSH key authentication
3. Use GitHub Desktop GUI (easier)

### Issue: Site not showing up after push
**Solution**: 
1. Check **Actions** tab - make sure workflow completed
2. Check **Settings** → **Pages** - verify source is set
3. Wait 2-3 minutes for GitHub to publish
4. Clear browser cache (Ctrl+Shift+Del)

### Issue: Links not working on GitHub Pages
**Solution**: Use relative paths, not absolute:
- ✅ Correct: `href="contact.html"`
- ❌ Wrong: `href="/contact.html"`
- ✅ Correct: `href="assets/css/style.css"`
- ❌ Wrong: `href="/assets/css/style.css"`

---

## 💡 GitHub Desktop Alternative

If command line is difficult, use GitHub Desktop:

1. Download [GitHub Desktop](https://desktop.github.com)
2. Sign in with GitHub account
3. Click **Clone a repository** → your repo
4. Make changes locally
5. Click **Commit to main**
6. Click **Push origin**
7. Watch it deploy automatically!

---

## 🎯 Pro Tips

### 1. **Custom Domain** (Optional, costs ~$10/year)
After deploying to GitHub Pages, you can add a custom domain:
- Buy domain from Namecheap, GoDaddy, etc.
- Go to **Settings** → **Pages** → **Custom domain**
- Add your domain
- Update DNS records (instructions provided by GitHub)

### 2. **HTTPS Security** (Free & Automatic)
GitHub Pages provides free HTTPS automatically. Your site will be secure! 🔒

### 3. **Updating Contact Info Easily**
Keep a list of all replacements needed:
```
Phone: +91 9876543210
Email: myemail@example.com
WhatsApp: https://wa.me/919876543210
Location: Bangalore, Karnataka, India
```

### 4. **Keeping Repository Private**
If you want to keep code private but still deploy:
- Use **GitHub Pro** ($4/month) - includes private repos with Pages
- Or use a different hosting service

### 5. **Multiple Repositories**
You can host multiple websites:
- `username.github.io` - Personal/main site (homepage)
- `username.github.io/project1` - Project 1
- `username.github.io/project2` - Project 2

---

## 📊 Current Repository Status

```
Repository Name: subharambh-decorations
Repository Type: Public (for free GitHub Pages)
Branch: main
Deployment: Automatic (on push)
Status: Ready for deployment

Files:
├── 7 HTML pages
├── 1 CSS file
├── 4 Documentation files
├── GitHub Actions workflow
└── .gitignore + License
```

---

## 🚀 Quick Start (TL;DR)

1. Create GitHub account: [github.com](https://github.com)
2. Create repository named `subharambh-decorations`
3. Run these commands:
   ```bash
   cd c:\Users\sajee\subharambh-decorations
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/subharambh-decorations.git
   git push -u origin main
   ```
4. Go to **Settings** → **Pages** → Select `main` branch → **Save**
5. Wait 1-2 minutes
6. Visit: `https://YOUR_USERNAME.github.io/subharambh-decorations/`

---

## ✅ Next Steps

1. **Create GitHub account** (if needed)
2. **Create repository** on GitHub
3. **Push your code** using provided commands
4. **Enable GitHub Pages** in Settings
5. **Share your URL** with clients!

---

## 📞 Support

For detailed GitHub documentation, visit:
- [GitHub Pages Documentation](https://docs.github.com/pages)
- [GitHub Actions Workflow Documentation](https://docs.github.com/actions)
- [Troubleshooting GitHub Pages](https://docs.github.com/pages/getting-started-with-github-pages/troubleshooting-publication-of-your-github-pages-site)

---

**Your website is ready to go live! 🚀**

**Questions? Check SETUP_GUIDE.md or QUICK_START.md for more details.**

---

**Version**: 2.0
**Date**: December 2024
**Status**: ✅ Ready for GitHub Pages Deployment
