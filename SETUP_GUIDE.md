# Subharambh Decorations - Professional Static Website

A modern, responsive static website for a decoration company offering services for weddings, corporate events, birthdays, and other occasions.

## 🌟 Features

### ✨ Modern Design
- Clean, professional aesthetic with golden color scheme
- Fully responsive design (mobile, tablet, desktop)
- Smooth animations and transitions
- Professional typography and spacing

### 📄 Comprehensive Pages
- **Home** - Hero section with features, services preview, testimonials, and statistics
- **About** - Company story, mission, values, and team information
- **Services** - Detailed service descriptions with three pricing packages
- **Gallery** - Interactive gallery with category filters (Weddings, Birthdays, Corporate, Other Events)
- **Contact** - Contact form, business information, social media links, and WhatsApp integration
- **404** - Custom error page

### 📱 Interactive Features
- Gallery filtering by event type
- Responsive contact form with event type and budget selection
- Social media integration (Facebook, Instagram, YouTube)
- WhatsApp direct messaging link
- Smooth scroll behavior
- Hover effects and animations

### 💼 Business Information
- Client testimonials with ratings
- Company statistics (500+ events, 98% satisfaction, 8+ years experience)
- Three service packages with clear pricing
- Working hours and availability information
- Service feature highlights

## 📁 Project Structure

```
subharambh-decorations/
├── index.html              # Home page with hero, features, testimonials, stats
├── about.html              # About company, mission, values, team
├── services.html           # Services with detailed descriptions and pricing
├── gallery.html            # Interactive gallery with category filters
├── contact.html            # Contact form and business information
├── 404.html               # Custom error page
├── assets/
│   └── css/
│       └── style.css       # Complete responsive stylesheet (600+ lines)
└── README.md              # Documentation
```

## 🚀 Quick Start

1. **Download or Clone** the repository
2. **Open index.html** in your web browser
3. **Navigate** using the top menu to explore all pages
4. **Customize** (see below for instructions)

No server, database, or dependencies required - this is a fully static website!

## 🎨 Customization Guide

### 1. Update Company Information (IMPORTANT!)

Edit these placeholders in **ALL HTML files**:
- `+91 XXXXX XXXXX` → Your phone number
- `info@subharambh.com` → Your email address
- `City/Region` → Your city/region
- `Country` → Your country
- `https://wa.me/919999999999` → Your WhatsApp number (keep the link format)

**Quick Find & Replace Checklist:**
- [ ] Phone number in header/footer
- [ ] Email address in header/footer
- [ ] WhatsApp link in contact.html
- [ ] Location details in contact.html
- [ ] Social media links in contact.html

### 2. Add Your Logo

To replace the text "Subharambh Decorations" with a logo:
1. Add your logo image file in `assets/images/` folder
2. Replace `<div class="logo">Subharambh Decorations</div>` with:
```html
<a href="index.html" class="logo">
    <img src="assets/images/logo.png" alt="Subharambh Decorations" style="height: 40px;">
</a>
```

### 3. Add Gallery Images

In `gallery.html`, replace placeholder divs with actual images:

**Before:**
```html
<div class="gallery-item" data-category="wedding">
    <div class="gallery-placeholder">
        <span>✨ Elegant Wedding Setup</span>
    </div>
    <p>Floral arrangements with golden drapes</p>
</div>
```

**After:**
```html
<div class="gallery-item" data-category="wedding">
    <img src="images/wedding-1.jpg" alt="Elegant Wedding Setup">
    <p>Floral arrangements with golden drapes</p>
</div>
```

### 4. Update Testimonials

In `index.html`, modify the testimonial cards:
```html
<div class="testimonial-card">
    <div class="stars">⭐⭐⭐⭐⭐</div>
    <p>"Amazing work! They transformed our wedding beautifully."</p>
    <div class="testimonial-author">- Priya & Rahul</div>
</div>
```

### 5. Customize Pricing

In `services.html`, update the pricing cards:
```html
<div class="pricing-card">
    <h3>Basic Package</h3>
    <div class="price">₹10,000 - ₹25,000</div>
    <ul class="list">
        <li>4-6 hours setup time</li>
        <li>Basic color scheme</li>
        <li>Standard lighting</li>
    </ul>
</div>
```

### 6. Change Color Scheme

In `assets/css/style.css`, update the CSS variables at the top:
```css
:root {
    --primary: #c4a965;           /* Golden - change this */
    --primary-dark: #a88c4c;      /* Darker shade */
    --text-dark: #2c2c2c;         /* Text color */
    --text-light: #666;           /* Light text */
    --bg-light: #f9f7f4;          /* Background */
    --border: #e5e0da;            /* Borders */
    --white: #ffffff;
}
```

**Popular color combinations:**
- Pink/Rose: `#e85d75` (wedding theme)
- Purple/Lavender: `#9b6ba8` (elegant theme)
- Blue/Navy: `#1e3a8a` (corporate theme)
- Green/Emerald: `#059669` (nature theme)

### 7. Update Service Descriptions

In `services.html`, modify the detailed descriptions under each service section.

### 8. Add Social Media Links

In `contact.html`, update the social links:
```html
<div class="social-links">
    <a href="https://facebook.com/your-page" target="_blank" title="Facebook">f</a>
    <a href="https://instagram.com/your-page" target="_blank" title="Instagram">📷</a>
    <a href="https://youtube.com/your-channel" target="_blank" title="YouTube">▶</a>
</div>
```

### 9. Update Site Favicon

The current favicon is a golden emoji. To change it:
1. Create a 32x32 PNG image of your logo
2. Place it in `assets/images/favicon.png`
3. In all HTML files, update: `<link rel="icon" href="assets/images/favicon.png">`

## 📊 Editing Statistics Section

In `index.html`, customize the stats:
```html
<div class="stat-card">
    <div class="stat-number">500+</div>  <!-- Change this number -->
    <p>Events Decorated</p>
</div>
```

## 🔍 SEO Optimization

Update the meta descriptions in each HTML file:
```html
<meta name="description" content="Subharambh Decorations - Professional decoration services for weddings, events, and celebrations">
```

## 📱 Responsive Breakpoints

The website is optimized for:
- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px
- **Small Mobile**: 480px and below

## 🎯 Page Features Breakdown

### Home Page
- Hero section with CTA button
- Four feature cards
- Service preview with three main services
- Client testimonials section
- Company statistics
- Call-to-action section

### About Page
- Company story
- Mission statement
- Core values (4 cards)
- Team information
- Why choose us list

### Services Page
- Three detailed service sections
- Features lists for each service
- Three pricing packages with features
- "Why Our Services Stand Out" section

### Gallery Page
- Category filter buttons (All, Weddings, Birthdays, Corporate, Other)
- 16 gallery items categorized
- Interactive filtering with JavaScript
- Hover effects on items

### Contact Page
- Contact information display
- Phone, Email, WhatsApp links
- Working hours
- Social media links
- Contact form with fields:
  - Full Name
  - Email
  - Phone
  - Event Type (dropdown)
  - Event Date
  - Budget Range
  - Message

## 🌐 Browser Support

- ✅ Chrome (latest versions)
- ✅ Firefox (latest versions)
- ✅ Safari (latest versions)
- ✅ Edge (latest versions)
- ✅ Mobile browsers (iOS Safari, Chrome Android)

## 📦 File Sizes

- **Total Size**: ~15KB (very lightweight)
- **HTML Files**: ~5KB combined
- **CSS File**: ~10KB
- **Zero JavaScript dependencies**

## 🚀 Deployment Options

### GitHub Pages (Free)
1. Create GitHub repository
2. Push files to main branch
3. Go to Settings → Pages → Enable GitHub Pages
4. Site will be live at: `https://yourusername.github.io/repo-name`

### Netlify (Free)
1. Connect GitHub repository to Netlify
2. Automatic deployment on push
3. Free custom domain support

### Traditional Web Hosting
1. Upload all files via FTP/SFTP
2. No special server configuration needed
3. Works on any web hosting

## ✅ Customization Checklist

- [ ] Update phone numbers in all files
- [ ] Update email addresses
- [ ] Update location information
- [ ] Update WhatsApp link
- [ ] Add company logo
- [ ] Add gallery images
- [ ] Update testimonials
- [ ] Update pricing
- [ ] Add social media links
- [ ] Update About page content
- [ ] Update service descriptions
- [ ] Change color scheme (optional)
- [ ] Update meta descriptions
- [ ] Test on mobile devices
- [ ] Deploy to hosting

## 🛠️ Advanced Customization

### Adding More Sections
The website uses a modular structure. You can duplicate existing cards and modify them:

1. **Card Component** - Copy `.card` div and customize
2. **Service Details** - Copy entire service-detail section
3. **Gallery Items** - Add new items with `data-category` attribute

### Adding More Pages
1. Create new `.html` file
2. Copy header and footer from existing pages
3. Update navigation links in all files
4. Update footer quick links

### Contact Form Submission
The current form is static. To make it functional:
- Use **Formspree** (free): `action="https://formspree.io/f/YOUR_FORM_ID"`
- Use **Netlify Forms**: Just need to add `netlify` attribute
- Use **Email service**: EmailJS, Basin, etc.

## 📞 Quick Customization Template

```
PHONE: [Your Phone Number]
EMAIL: [Your Email]
WHATSAPP: [Your WhatsApp Link]
LOCATION: [Your City, Country]
YEARS: [Your Experience]
EVENTS: [Number of Events]
SATISFACTION: [Your Percentage]
PRICE_LOW: [Lowest Package Price]
PRICE_MID: [Mid Package Price]
PRICE_HIGH: [Highest Package Price]
```

## 🎨 What's New in Version 2.0

✅ Added comprehensive About Us page
✅ Added client testimonials with ratings
✅ Added company statistics section
✅ Enhanced gallery with interactive filtering
✅ Added pricing packages to services page
✅ Improved social media integration
✅ WhatsApp integration for quick contact
✅ Better responsive design
✅ Smooth animations throughout
✅ Enhanced contact page with more options
✅ Better navigation structure
✅ Professional visual hierarchy

## 📝 Notes

- All HTML files use UTF-8 encoding
- CSS uses CSS variables for easy customization
- No external CDNs or dependencies
- All features work offline
- Images are placeholder images - replace with your own

## 🤝 Support

For questions or customization help:
1. Check the CSS comments for guidance
2. Review HTML structure for understanding
3. Test changes locally before deploying
4. Use browser DevTools to inspect elements

## 📄 License

This project is provided as-is for your decoration business website.

---

**Version**: 2.0 (Enhanced & Professional)
**Last Updated**: December 2024
**Built for**: Subharambh Decorations

---

**Ready to go live?** Customize the contact information and deploy! Your professional decoration website is ready. ✨
