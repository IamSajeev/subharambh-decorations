# Quick Customization Reference

## 🔴 REQUIRED CHANGES (Do These First!)

Replace these in **ALL HTML files**:

```
OLD → NEW
+91 XXXXX XXXXX → Your phone number
info@subharambh.com → Your email
City/Region → Your city/region
Country → Your country
https://wa.me/919999999999 → Your WhatsApp link (format: https://wa.me/YOUR_PHONE_NUMBER)
Subharambh Decorations → Your company name (if different)
```

### Files to Update:
- ✅ index.html
- ✅ about.html
- ✅ services.html
- ✅ gallery.html
- ✅ contact.html
- ✅ 404.html

---

## 🟡 RECOMMENDED CHANGES

### 1. **Add Gallery Images**
In `gallery.html`, find and replace:
```html
<div class="gallery-placeholder">
    <span>✨ Elegant Wedding Setup</span>
</div>
```

With:
```html
<img src="images/your-image.jpg" alt="Elegant Wedding Setup" style="width:100%; height:250px; object-fit:cover;">
```

### 2. **Update Testimonials**
In `index.html`, find the testimonials section:
```html
<p>"Subharambh Decorations transformed our wedding into a dream!"</p>
<div class="testimonial-author">- Priya & Rahul</div>
```

Change to your actual client testimonials.

### 3. **Update About Page**
In `about.html`, customize:
- Company story (history section)
- Team information
- Service highlights in "Why Choose Us"

### 4. **Adjust Pricing**
In `services.html`, update:
```html
<div class="price">₹10,000 - ₹25,000</div>
```

And the features lists for each package.

### 5. **Add Social Media Links**
In `contact.html`, update:
```html
<a href="https://facebook.com/your-page" target="_blank" title="Facebook">f</a>
<a href="https://instagram.com/your-page" target="_blank" title="Instagram">📷</a>
<a href="https://youtube.com/@your-channel" target="_blank" title="YouTube">▶</a>
```

---

## 🟢 OPTIONAL CUSTOMIZATIONS

### Change Color Scheme
In `assets/css/style.css`, find `:root {` and change:
```css
--primary: #c4a965;      /* Golden - change this color */
--primary-dark: #a88c4c; /* Darker shade */
```

**Color ideas:**
- Pink: `#e85d75`
- Purple: `#9b6ba8`
- Blue: `#1e3a8a`
- Green: `#059669`

### Update Statistics
In `index.html`, find stats section:
```html
<div class="stat-number">500+</div> <!-- Change this -->
<p>Events Decorated</p>
```

### Add Logo
Replace:
```html
<div class="logo">Subharambh Decorations</div>
```

With:
```html
<img src="assets/images/logo.png" alt="Logo" style="height: 40px;">
```

---

## 📍 Find & Replace Locations

| What | Where | Line |
|------|-------|------|
| Phone | All HTML files | Header/Footer |
| Email | All HTML files | Header/Footer/Contact |
| Location | contact.html | Contact Info Block |
| WhatsApp | contact.html | WhatsApp Section |
| Gallery Items | gallery.html | Gallery Grid |
| Testimonials | index.html | Testimonials Section |
| Pricing | services.html | Pricing Cards |
| Social Links | contact.html | Social Links Section |
| About Info | about.html | All content areas |

---

## 🎯 Step-by-Step Customization

### Step 1: Contact Information (15 minutes)
1. Open `index.html` in text editor
2. Find and replace phone number
3. Find and replace email
4. Repeat for all 6 HTML files

### Step 2: Location Details (5 minutes)
1. Open `contact.html`
2. Update city/region
3. Update country
4. Update working hours if different

### Step 3: WhatsApp Link (2 minutes)
1. In `contact.html`, find WhatsApp section
2. Replace phone in: `https://wa.me/919999999999`
3. Use your number like: `https://wa.me/919876543210`

### Step 4: Gallery Images (20 minutes)
1. Create folder: `images/`
2. Add your decoration photos
3. Update `gallery.html` with image paths
4. Delete or replace placeholder items

### Step 5: Testimonials (10 minutes)
1. Open `index.html`
2. Find testimonials section
3. Replace client names and quotes
4. Keep the 5-star rating format

### Step 6: Pricing & Services (15 minutes)
1. Open `services.html`
2. Update package prices if needed
3. Update service features
4. Update descriptions

### Step 7: Social Media (5 minutes)
1. Open `contact.html`
2. Update Facebook, Instagram, YouTube links
3. Keep the emoji and link format

### Step 8: About Page (15 minutes)
1. Open `about.html`
2. Update company story
3. Update mission statement
4. Update team information

### Step 9: Test (10 minutes)
1. Open each page in browser
2. Check all links work
3. Test on mobile phone
4. Verify contact form displays

### Step 10: Deploy! (5 minutes)
1. Choose hosting (GitHub Pages, Netlify, etc.)
2. Upload all files
3. Share your website!

---

## 🔍 Find Exact Text to Replace

### Phone Number (Appears 12 times)
```
+91 XXXXX XXXXX
```

### Email (Appears 8 times)
```
info@subharambh.com
```

### Location (Appears 2 times in contact.html)
```
City/Region
Country
```

### WhatsApp (Appears 1 time)
```
https://wa.me/919999999999
```

---

## ✅ Verification Checklist

After customization, verify:
- [ ] Phone number updated everywhere
- [ ] Email updated everywhere
- [ ] Location updated
- [ ] WhatsApp link works
- [ ] Gallery images display
- [ ] Testimonials are yours
- [ ] Pricing is correct
- [ ] Social links work
- [ ] All pages accessible
- [ ] Website works on mobile
- [ ] No placeholder text remains

---

## 🚀 Deployment Instructions

### GitHub Pages (Free)
1. Create GitHub account
2. Create new repository
3. Upload all files
4. Go to Settings → Pages
5. Select main branch
6. Site live at: github.com/yourusername/repo-name

### Netlify (Free)
1. Go to netlify.com
2. Drag and drop folder
3. Site live instantly!

### Regular Hosting
1. Buy domain (godaddy.com, namecheap.com, etc.)
2. Get hosting (bluehost.com, hostinger.com, etc.)
3. Upload files via FTP
4. Point domain to hosting

---

## 💡 Tips & Tricks

**Tip 1**: Use Ctrl+H (Find & Replace) in your text editor to replace phone numbers quickly across all files.

**Tip 2**: Before uploading, test locally by opening `index.html` directly in your browser.

**Tip 3**: Use free image compression (tinypng.com) to reduce image file sizes.

**Tip 4**: Check website on mobile phone before deploying using ngrok or local IP.

**Tip 5**: Add Google Analytics for tracking visitors (optional).

---

## 🆘 Common Issues & Fixes

### Images Not Showing
- Check file path is correct
- Use relative paths like: `images/photo.jpg`
- Verify image files exist in that folder

### Links Not Working
- Use correct relative paths
- Use `.html` extension: `contact.html`
- No spaces in filenames

### Styling Looks Wrong
- Clear browser cache (Ctrl+Shift+Del)
- Check CSS file path in HTML
- Verify style.css exists in assets/css/

### Form Doesn't Submit
- Form is currently static (no backend)
- To make it functional, use Formspree or Netlify Forms
- See SETUP_GUIDE.md for form integration

---

## 📞 Quick Reference

**Your Contact Info:**
- Phone: ___________________
- Email: ___________________
- WhatsApp: ___________________
- City: ___________________
- Country: ___________________
- Website Color (optional): ___________________

---

## 📚 For More Details

See these files for complete information:
- **SETUP_GUIDE.md** - Detailed customization guide
- **IMPROVEMENTS.md** - List of all enhancements
- **README.md** - Original project information

---

## 🎉 You're Ready!

Your website is professionally designed and ready for customization.
Simply follow this guide, update your information, and deploy!

**Good luck with your decoration business! ✨**

---

**Last Updated**: December 2024
**Version**: 2.0
