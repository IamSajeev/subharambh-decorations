# Subharambh Decorations - Website

A lightweight, responsive static website for Subharambh Decorations, designed to showcase decoration services and be easily deployable on GitHub Pages.

## Features

✨ **Lightweight & Fast** - Pure HTML, CSS, no heavy frameworks or dependencies
📱 **Fully Responsive** - Works perfectly on all devices (mobile, tablet, desktop)
🎨 **Professional Design** - Beautiful, modern aesthetic with elegant color scheme
⚡ **Auto-Deploy** - Automatic deployment via GitHub Actions on every push
🔍 **SEO Ready** - Proper meta tags and semantic HTML
📄 **Easy to Customize** - Simple structure, easy to modify content and styling

## Pages Included

- **Home** (`index.html`) - Hero section with key features and services preview
- **Services** (`services.html`) - Detailed description of decoration services
- **Gallery** (`gallery.html`) - Portfolio showcase of past projects
- **Contact** (`contact.html`) - Contact form and business information
- **404** (`404.html`) - Custom error page

## Quick Start

### 1. Clone/Create the Repository

```bash
git clone <your-repo-url>
cd subharambh-decorations-website
```

### 2. Local Preview (Optional)

You can preview the site locally by opening `index.html` in a browser, or use a simple HTTP server:

```bash
# Using Python 3
python -m http.server 8000

# Or using Python 2
python -m SimpleHTTPServer 8000
```

Then open `http://localhost:8000` in your browser.

### 3. Deploy to GitHub Pages

#### Step A: Create a GitHub Repository
1. Go to [GitHub](https://github.com) and create a new repository
2. Name it (e.g., `subharambh-decorations`)
3. Do NOT initialize with README (we already have one)

#### Step B: Push Code to Repository

```bash
git init
git add .
git commit -m "Initial commit: Subharambh Decorations website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

#### Step C: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Build and deployment":
   - Select **Deploy from a branch**
   - Select **main** branch
   - Select **/ (root)** folder
4. Click **Save**

Your site will be live at: `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME`

## File Structure

```
├── index.html                 # Home page
├── about.html                 # About page (optional)
├── services.html              # Services page
├── gallery.html               # Gallery/Portfolio page
├── contact.html               # Contact page
├── 404.html                   # Error page
├── assets/
│   └── css/
│       └── style.css          # Main stylesheet (responsive, no dependencies)
├── .github/
│   └── workflows/
│       └── pages.yml          # GitHub Actions workflow
├── .gitignore                 # Git ignore rules
├── LICENSE                    # MIT License
└── README.md                  # This file
```

## Customization Guide

### Update Company Information

Edit the following files to add your actual contact details:

**contact.html**
```html
<p>+91 XXXXX XXXXX</p>  <!-- Replace with your phone -->
<p>info@subharambh.com</p>  <!-- Replace with your email -->
<p>City/Region<br>Country</p>  <!-- Replace with your location -->
```

### Add Gallery Images

Replace placeholder text in `gallery.html` with actual images:

```html
<!-- From this: -->
<div class="gallery-placeholder">
    <span>Wedding Decoration</span>
</div>

<!-- To this: -->
<img src="assets/images/wedding-1.jpg" alt="Wedding decoration">
```

### Change Colors

Modify the color variables in `assets/css/style.css`:

```css
:root {
    --primary: #c4a965;        /* Gold/accent color */
    --primary-dark: #a88c4c;   /* Darker accent */
    --text-dark: #2c2c2c;      /* Text color */
    --bg-light: #f9f7f4;       /* Light background */
}
```

### Update Navigation Menu

Edit the `<nav>` section in any HTML file to add/remove menu items.

## Performance

- **Zero External Dependencies** - No CDNs, frameworks, or external libraries
- **Fast Load Times** - Optimized CSS, no JavaScript bloat
- **Mobile-First Design** - Responsive breakpoints at 768px and 480px
- **SEO Optimized** - Proper heading hierarchy and meta descriptions

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

This project is licensed under the MIT License. See `LICENSE` file for details.

## Support & Questions

For issues or customizations:
1. Check the file structure and comments in the code
2. Review the CSS for styling modifications
3. Ensure all file paths are correct when adding new assets

## Tips for Success

✅ **Replace placeholder content** with your actual services and photos
✅ **Update contact information** with real details
✅ **Add your gallery images** to showcase your work
✅ **Test on mobile devices** before going live
✅ **Use a custom domain** (optional, add CNAME file)
✅ **Keep it updated** with new projects and services

---

**Built for simplicity. Designed for impact. Ready to deploy.**
