# 🚀 DEPLOYMENT CHECKLIST & COMMANDS

## ⚙️ Pre-Deployment Verification

### Content Updates (CRITICAL!)
- [ ] Phone number: Search & replace `+91 XXXXX XXXXX` with your actual phone
- [ ] Email: Search & replace `info@subharambh.com` with your email
- [ ] Location: Update `City/Region` and `Country` in contact.html
- [ ] WhatsApp: Update `https://wa.me/919999999999` with your WhatsApp number
- [ ] Social media: Update Facebook, Instagram, YouTube links in contact.html
- [ ] Company name: Update "Subharambh Decorations" if using different name
- [ ] Gallery: Add your actual images or remove placeholder items
- [ ] Testimonials: Update with real client quotes (or remove placeholder testimonials)
- [ ] Pricing: Verify pricing packages are correct
- [ ] About page: Update company story and team information

### Technical Verification
- [ ] All HTML files open without errors
- [ ] CSS loads correctly (check for styling)
- [ ] Links work (test all navigation)
- [ ] Forms display properly
- [ ] Gallery filters work
- [ ] Responsive design works on mobile
- [ ] No console errors in browser DevTools
- [ ] Images load (if you added any)

### Browser Testing
- [ ] Chrome browser - works ✓
- [ ] Firefox browser - works ✓
- [ ] Safari browser - works ✓
- [ ] Mobile device - works ✓
- [ ] Mobile landscape - works ✓

---

## 📋 GITHUB SETUP CHECKLIST

### Step 1: Prepare Your Computer
```bash
# Configure Git (one-time setup)
git config --global user.name "Your Full Name"
git config --global user.email "your.email@gmail.com"

# Verify configuration
git config --global --list
```

- [ ] Git installed on computer
- [ ] GitHub account created at github.com
- [ ] Email verified on GitHub
- [ ] Personal Access Token created (if using HTTPS authentication)

### Step 2: Create Repository on GitHub
1. Go to [github.com/new](https://github.com/new)
2. Fill in:
   - Repository name: `subharambh-decorations`
   - Description: `Professional decoration company website`
   - Public: ✓ (required for free GitHub Pages)
3. Click "Create repository"

- [ ] Repository created
- [ ] Repository is PUBLIC
- [ ] Copy the remote URL

---

## 🔧 DEPLOYMENT COMMANDS

### Copy-Paste These Commands (One by One)

**Important**: Replace `YOUR_USERNAME` with your GitHub username!

#### Command 1: Navigate to Project
```bash
cd c:\Users\sajee\subharambh-decorations
```

#### Command 2: Set Main Branch
```bash
git branch -M main
```

#### Command 3: Add GitHub Remote
```bash
git remote add origin https://github.com/YOUR_USERNAME/subharambh-decorations.git
```

#### Command 4: Verify Remote
```bash
git remote -v
```

#### Command 5: Add All Files
```bash
git add .
```

#### Command 6: Create Initial Commit
```bash
git commit -m "Initial commit - Subharambh Decorations professional website"
```

#### Command 7: Push to GitHub (First Time)
```bash
git push -u origin main
```

#### Command 8: Verify Push Success
```bash
git log --oneline -n 5
```

---

## ✅ POST-PUSH CHECKLIST

After running the push command:

### On GitHub Website:
1. Go to your repository: `github.com/YOUR_USERNAME/subharambh-decorations`
2. Verify files are there:
   - [ ] Verify 7 HTML files visible
   - [ ] Verify assets/ folder visible
   - [ ] Verify documentation files visible
   - [ ] Verify .github/ folder (workflow) exists

### Enable GitHub Pages:
1. Click **Settings** (top menu)
2. Click **Pages** (left sidebar)
3. Under "Source":
   - [ ] Branch: select **main**
   - [ ] Folder: select **/ (root)**
4. Click **Save**
5. Wait for message: "Your site is published at..."

- [ ] GitHub Pages enabled
- [ ] Source set to main branch
- [ ] Deployment URL visible

### Check Deployment Status:
1. Click **Actions** (top menu)
2. See workflow "Deploy to GitHub Pages"
3. Watch for green checkmark ✅
4. Takes 1-2 minutes usually

- [ ] Workflow completed successfully
- [ ] Green checkmark visible
- [ ] Site deployed message shown

---

## 🌐 YOUR LIVE WEBSITE

### After Deployment:

**Your website is live at:**
```
https://YOUR_USERNAME.github.io/subharambh-decorations/
```

**Example URLs** (replace YOUR_USERNAME):
```
https://YOUR_USERNAME.github.io/subharambh-decorations/
https://YOUR_USERNAME.github.io/subharambh-decorations/about.html
https://YOUR_USERNAME.github.io/subharambh-decorations/services.html
https://YOUR_USERNAME.github.io/subharambh-decorations/gallery.html
https://YOUR_USERNAME.github.io/subharambh-decorations/contact.html
```

- [ ] Website is live
- [ ] Home page loads
- [ ] All pages accessible
- [ ] Navigation works
- [ ] Styling displays correctly
- [ ] Forms display properly
- [ ] Gallery filters work
- [ ] Contact links work

---

## 🔄 UPDATING YOUR WEBSITE

After initial deployment, updating is easy:

```bash
# 1. Make changes to your files locally
#    (Edit HTML, CSS, add images, etc.)

# 2. Check what changed
git status

# 3. Add changes
git add .

# 4. Commit with message
git commit -m "Updated gallery with wedding photos"

# 5. Push to GitHub
git push

# 6. Website automatically updates in 1-2 minutes!
```

---

## 📊 COMMON UPDATES

### Adding Gallery Images:
1. Create `images/` folder in project
2. Add your decoration photos
3. Update gallery.html with image paths
4. Push changes
5. Website updates automatically

### Updating Contact Info:
1. Edit contact.html
2. Update phone, email, WhatsApp
3. Push changes
4. Website updates automatically

### Changing Colors:
1. Edit assets/css/style.css
2. Change CSS variables in `:root`
3. Push changes
4. Website updates automatically

### Adding New Gallery Items:
1. Edit gallery.html
2. Add new gallery-item divs
3. Push changes
4. Website updates automatically

---

## 🆘 TROUBLESHOOTING

### "Repository not found" error:
- [ ] Check GitHub username spelling
- [ ] Verify repository exists on GitHub
- [ ] Verify you're in correct folder
- [ ] Verify remote URL: `git remote -v`

### Website not showing after push:
- [ ] Check Actions tab - make sure workflow succeeded
- [ ] Check Settings → Pages - verify source is set
- [ ] Wait 2-3 minutes (first deployment takes longer)
- [ ] Hard refresh browser: `Ctrl+Shift+Del`

### Links not working:
- [ ] Verify file paths are relative: `contact.html` (not `/contact.html`)
- [ ] Check file names match exactly (case-sensitive)
- [ ] Verify all HTML files exist

### Images not showing:
- [ ] Verify images are in `images/` folder
- [ ] Check file names exactly (case-sensitive)
- [ ] Use relative paths: `images/photo.jpg`
- [ ] Try clearing browser cache

### Styles not loading:
- [ ] Verify style.css path in HTML: `href="assets/css/style.css"`
- [ ] Check assets/css/style.css file exists
- [ ] Try clearing browser cache: `Ctrl+Shift+Del`

---

## 📞 COMMAND SUMMARY TABLE

| Task | Command |
|------|---------|
| Navigate to folder | `cd c:\Users\sajee\subharambh-decorations` |
| Check status | `git status` |
| Add all files | `git add .` |
| Commit changes | `git commit -m "message"` |
| Push to GitHub | `git push` |
| View history | `git log --oneline` |
| Check remote | `git remote -v` |
| First push | `git push -u origin main` |

---

## 🎯 SUCCESS CRITERIA

Your deployment is successful when:

✅ Repository created on GitHub
✅ All files pushed to GitHub
✅ GitHub Pages enabled in Settings
✅ Deployment workflow completed (green checkmark)
✅ Website accessible at GitHub Pages URL
✅ All pages load correctly
✅ Navigation works
✅ Styling displays properly
✅ Gallery filters work
✅ Contact form displays
✅ No console errors
✅ Mobile view works
✅ All links are functional

---

## 📋 FINAL CHECKLIST

### Before Pushing:
```
Content Checklist:
☐ Phone number updated
☐ Email updated
☐ Location updated
☐ WhatsApp link updated
☐ Social media links updated
☐ Company info updated
☐ No placeholder text remaining

Technical Checklist:
☐ All files in project folder
☐ .git folder exists
☐ .github/workflows/pages.yml exists
☐ style.css in assets/css/
☐ HTML files in root folder
```

### During Deployment:
```
GitHub Setup:
☐ GitHub account created
☐ Repository created
☐ Repository is PUBLIC
☐ Local folder initialized with git
☐ Remote URL added
☐ Files committed locally
```

### After Deployment:
```
Verification:
☐ Files visible on GitHub
☐ GitHub Pages enabled
☐ Deployment workflow succeeded
☐ Website is live
☐ All pages load
☐ Styling works
☐ Links work
☐ Mobile view works
```

---

## 🚀 YOU'RE READY!

Your website is professionally built and GitHub is configured for automatic deployment.

**Next steps:**
1. Complete all checklist items
2. Run the deployment commands
3. Wait for website to go live
4. Share your URL with clients!

---

**Questions?** See these files:
- GITHUB_PAGES_SETUP.md - Detailed deployment guide
- QUICK_START.md - Quick customization reference
- SETUP_GUIDE.md - Comprehensive setup guide

---

**Version**: 2.0
**Status**: ✅ Ready for Deployment
**Last Updated**: December 2024

---

## 💡 Final Tips

1. **Username in URL**: Your GitHub username becomes part of the URL
2. **Custom Domain**: You can add a custom domain later (costs money)
3. **HTTPS**: Free HTTPS automatically enabled
4. **Performance**: Website loads very fast on GitHub Pages
5. **Reliability**: 99.9% uptime guaranteed by GitHub
6. **Scalability**: Can handle millions of visitors

**You have a professional, fast, reliable website hosting! 🎉**
