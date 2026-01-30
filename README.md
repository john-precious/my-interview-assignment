# Dr. Maya Reynolds, PsyD - Therapy Website

A modern, professional website for Dr. Maya Reynolds, a Licensed Clinical Psychologist specializing in anxiety therapy, trauma treatment (EMDR), and burnout recovery for high-achieving adults in Santa Monica, California.

## 🎯 Project Overview

This is a fully responsive, single-page website designed for a clinical psychologist's practice. The site features:

- **SEO-optimized content** for Santa Monica, California
- **Mobile-first responsive design** with hamburger menu
- **Premium animations** throughout all sections
- **Professional color palette** (Navy, Sage Green, Warm Beige)
- **Evidence-based service offerings**
- **Interactive FAQ accordion**
- **Smooth scroll navigation**

---

## 📋 Table of Contents

1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Page Sections](#page-sections)
4. [Installation](#installation)
5. [Customization Guide](#customization-guide)
6. [SEO Keywords](#seo-keywords)
7. [Responsive Breakpoints](#responsive-breakpoints)
8. [Browser Support](#browser-support)
9. [Performance](#performance)
10. [Credits](#credits)

---

## ✨ Features

### Design & User Experience
- ✅ Clean, professional aesthetic tailored for mental health services
- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Hamburger menu for mobile devices
- ✅ Smooth scroll animations and transitions
- ✅ Interactive hover effects
- ✅ Scroll progress bar
- ✅ Accessibility-friendly color contrast

### Animations
- ✅ Hero section with floating gradient background
- ✅ Staggered fade-up animations for text elements
- ✅ Service cards with zoom and lift effects
- ✅ Image hover effects with scale transformations
- ✅ FAQ accordion with smooth expand/collapse
- ✅ Parallax scrolling on hero image
- ✅ Intersection Observer for scroll-triggered animations

### Functionality
- ✅ Mobile hamburger menu with smooth transitions
- ✅ Sticky navigation header
- ✅ FAQ accordion with single-item open functionality
- ✅ Smooth scroll to section anchors
- ✅ Email contact integration
- ✅ Auto-closing mobile menu on link click

### SEO Optimization
- ✅ Meta descriptions and keywords
- ✅ Semantic HTML5 structure
- ✅ Location-based keywords (Santa Monica, CA)
- ✅ Service-specific keywords (anxiety therapy, EMDR, trauma therapy)
- ✅ Alt text for all images
- ✅ Proper heading hierarchy (H1, H2, H3)

---

## 🛠 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid, Flexbox, Custom Properties
- **Vanilla JavaScript** - No dependencies
- **Google Fonts** - Playfair Display & Source Sans 3
- **Unsplash** - High-quality stock images

---

## 📄 Page Sections

### 1. Navigation
- Sticky header with logo and menu links
- Hamburger menu for mobile devices
- Smooth scroll to sections

### 2. Hero Section
- Large H1 headline with SEO keywords
- Subtitle showing credentials
- Location information
- Primary CTA button
- Professional hero image

### 3. Intro Section
- Brief overview of services
- Target audience description
- Welcoming message

### 4. Services Section
Three detailed service cards:
1. **Anxiety & Panic Therapy** - CBT techniques
2. **Trauma & EMDR Therapy** - EMDR processing
3. **Burnout & Professional Stress** - Work-life balance

Each card includes:
- Service image
- Service title
- Detailed description
- Bullet points with specific offerings

### 5. Approach Section
- Therapeutic philosophy
- Treatment modalities (CBT, EMDR, trauma-informed)
- Evidence-based approach description
- Secondary CTA button

### 6. About Section
- Professional biography
- Education and credentials
- Practice locations (in-person + telehealth)
- Professional background box

### 7. FAQs Section
Six common questions:
1. Insurance acceptance
2. Session rates
3. Availability
4. Telehealth options
5. First session expectations
6. Therapy duration

### 8. CTA Section
- Final call-to-action
- Contact button (email)
- Encouraging message

### 9. Footer
- Contact information
- Quick links
- Office hours
- Copyright information

---

## 🚀 Installation

### Option 1: Direct Use
1. Download the `dr-maya-reynolds-updated.html` file
2. Open it in any modern web browser
3. No server required - it's a static HTML file

### Option 2: Web Hosting
1. Upload the HTML file to your web host (via FTP, cPanel, etc.)
2. Rename to `index.html` if you want it as your homepage
3. Access via your domain name

### Option 3: Local Development
```bash
# Clone or download the file
# Navigate to the directory
cd /path/to/website

# Option A: Open directly
open dr-maya-reynolds-updated.html

# Option B: Use a local server (recommended)
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Then open: http://localhost:8000
```

---

## 🎨 Customization Guide

### Changing Colors

Find the `:root` CSS variables at the top of the `<style>` section:

```css
:root {
    --navy: #1A3A52;          /* Primary dark color */
    --sage-green: #7A9B8E;    /* Accent color */
    --warm-beige: #F4EFE6;    /* Background color */
    --cream: #FDFBF7;         /* Light background */
    --terracotta: #C17C5E;    /* Optional accent */
    --charcoal: #2D2D2D;      /* Text color */
    --soft-grey: #6B6B6B;     /* Secondary text */
}
```

Replace the hex codes with your brand colors.

### Changing Fonts

Currently using:
- **Headings**: Playfair Display (serif)
- **Body**: Source Sans 3 (sans-serif)

To change fonts:
1. Replace the Google Fonts link in `<head>`:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@400;500;600&display=swap" rel="stylesheet">
```

2. Update the font-family in CSS:
```css
h1, h2, h3 {
    font-family: 'YourFont', serif;
}
body {
    font-family: 'YourBodyFont', sans-serif;
}
```

### Replacing Images

All images use Unsplash URLs. Replace them with your own:

```html
<!-- Find these img tags and replace the src -->
<img src="YOUR_IMAGE_URL.jpg" alt="Descriptive alt text">
```

**Recommended Image Sizes:**
- Hero image: 1200x1200px or larger
- Service cards: 800x600px
- Approach section: 1200x1200px
- About section: 800x1000px

### Updating Content

#### Contact Information
Search for these and update:
- Email: `contact@drmayareynolds.com`
- Phone: `(310) 555-0123`
- Address: `123th Street 45 W, Santa Monica, CA 90401`

#### Service Descriptions
Find the `.service-card` sections and update:
- Service titles (`<h3>`)
- Descriptions (`<p>`)
- Bullet points (`<li>`)

#### FAQs
Locate `.faq-item` sections and modify:
- Questions (`<h3>` in `.faq-question`)
- Answers (`<p>` in `.faq-answer`)

#### About Section
Update the `.about-content` text with actual biography and credentials.

---

## 🔍 SEO Keywords

### Primary Keywords
- therapist Santa Monica
- psychologist Santa Monica CA
- Santa Monica therapy
- anxiety therapy Santa Monica
- trauma therapy Santa Monica

### Secondary Keywords
- EMDR therapy
- burnout treatment
- therapy for professionals
- California psychologist
- high-achieving professionals therapy

### Location Modifiers
- Santa Monica, CA 90401
- California
- Southern California

---

## 📱 Responsive Breakpoints

### Desktop (1025px and above)
- Full navigation menu visible
- Two-column layouts
- Three-column service grid
- Hamburger menu hidden

### Tablet (768px - 1024px)
- Hamburger menu appears
- Two-column layouts collapse to single column
- Three-column service grid becomes single column
- Adjusted padding and font sizes

### Mobile (767px and below)
- Full mobile menu overlay
- All sections stack vertically
- Reduced font sizes
- Touch-friendly buttons and spacing

---

## 🌐 Browser Support

### Fully Supported
- ✅ Chrome (last 2 versions)
- ✅ Firefox (last 2 versions)
- ✅ Safari (last 2 versions)
- ✅ Edge (last 2 versions)
- ✅ Mobile Safari (iOS 12+)
- ✅ Chrome Mobile (Android 8+)

### Features Used
- CSS Grid
- CSS Flexbox
- CSS Custom Properties (variables)
- Intersection Observer API
- CSS Transforms & Transitions
- Smooth Scrolling

---

## ⚡ Performance

### Optimization Features
- **No external dependencies** - Pure HTML/CSS/JS
- **No JavaScript frameworks** - Lightweight vanilla JS
- **Efficient animations** - CSS transforms (GPU-accelerated)
- **Lazy loading ready** - Can add native lazy loading to images
- **Minimal HTTP requests** - Single file, Google Fonts, and images

### Performance Tips
1. **Compress images** before deployment (use TinyPNG, ImageOptim)
2. **Enable GZIP** compression on your server
3. **Add caching headers** for static assets
4. **Consider CDN** for image hosting
5. **Minify HTML/CSS** for production (optional)

### Lighthouse Scores (Expected)
- Performance: 90+
- Accessibility: 95+
- Best Practices: 95+
- SEO: 100

---

## 📝 File Structure

```
dr-maya-reynolds-updated.html    # Main website file (complete)
README.md                        # This documentation file
```

The website is contained in a **single HTML file** for easy deployment and maintenance.

---

## 🎯 Usage Scenarios

### For Therapists
- Replace Dr. Maya Reynolds' information with your own
- Update services to match your specialties
- Change images to your professional photos
- Adjust colors to match your brand

### For Web Designers
- Use as a template for mental health professionals
- Customize for other service-based businesses
- Adapt the layout and sections as needed

### For Developers
- Fork and enhance with additional features
- Integrate with booking systems (Calendly, SimplePractice)
- Add contact forms with backend processing
- Connect to CMS for content management

---

## 🔧 Advanced Customizations

### Adding a Contact Form

Replace the email link with a form:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <input type="email" name="email" placeholder="Your email" required>
    <textarea name="message" placeholder="Your message" required></textarea>
    <button type="submit">Send Message</button>
</form>
```

### Adding Google Analytics

Add before closing `</head>` tag:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### Adding a Booking System

Integrate Calendly or similar:

```html
<!-- Calendly inline widget begin -->
<div class="calendly-inline-widget" 
     data-url="https://calendly.com/your-username" 
     style="min-width:320px;height:630px;">
</div>
<script src="https://assets.calendly.com/assets/external/widget.js"></script>
```

---

## 🐛 Troubleshooting

### Navigation links not showing on desktop
- Clear browser cache
- Check that screen width is > 1024px
- Verify CSS media queries are not being overridden

### Animations not working
- Check browser compatibility
- Ensure JavaScript is enabled
- Try hard refresh (Ctrl+Shift+R or Cmd+Shift+R)

### Images not loading
- Check image URLs are accessible
- Verify internet connection
- Replace with local images if needed

### Mobile menu not closing
- Check JavaScript console for errors
- Verify all script code is present
- Test in different browsers

---

## 📞 Support & Contact

### Getting Help
- Check the code comments in the HTML file
- Review this README thoroughly
- Test in different browsers
- Validate HTML at https://validator.w3.org/

### Reporting Issues
If you find bugs or have suggestions:
1. Document the issue clearly
2. Include browser and device information
3. Provide steps to reproduce

---

## 📜 License

This website template is provided as-is for use in creating professional therapy websites.

**Allowed:**
- ✅ Personal use
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution (with credit)

**Not Allowed:**
- ❌ Selling as a template
- ❌ Removing attribution (in footer)
- ❌ Claiming original authorship

---

## 🙏 Credits

### Design & Development
- Template created for Dr. Maya Reynolds, PsyD
- Responsive design and animations
- SEO optimization

### Resources Used
- **Fonts**: Google Fonts (Playfair Display, Source Sans 3)
- **Images**: Unsplash (stock photography)
- **Icons**: Unicode characters (no icon font needed)

---

## 📈 Future Enhancements

### Potential Additions
- [ ] Blog section for mental health articles
- [ ] Client testimonials carousel
- [ ] Insurance verification tool
- [ ] Online booking integration
- [ ] Live chat widget
- [ ] Multi-language support
- [ ] Dark mode toggle
- [ ] Resource library/downloads
- [ ] Newsletter signup
- [ ] Video introduction

---

## 🎓 Learning Resources

### If you want to learn more:
- **HTML/CSS**: MDN Web Docs, W3Schools
- **JavaScript**: JavaScript.info, freeCodeCamp
- **Responsive Design**: Google Web Fundamentals
- **SEO**: Moz Beginner's Guide, Google Search Central
- **Web Accessibility**: WebAIM, A11y Project

---

## 📅 Version History

### Version 1.0 (Current)
- Initial release
- Full responsive design
- Hamburger menu implementation
- Advanced animations
- SEO optimization
- FAQ accordion
- Scroll progress bar

---

## ✅ Pre-Launch Checklist

Before going live:
- [ ] Replace all placeholder text with real content
- [ ] Update contact information (email, phone, address)
- [ ] Replace stock images with professional photos
- [ ] Test all links and buttons
- [ ] Verify contact email works
- [ ] Test on multiple devices and browsers
- [ ] Check page load speed
- [ ] Validate HTML
- [ ] Review SEO meta tags
- [ ] Set up Google Analytics
- [ ] Submit sitemap to Google Search Console
- [ ] Enable SSL certificate (HTTPS)

---

## 🌟 Best Practices

### Content
- Keep paragraphs concise and scannable
- Use clear, jargon-free language
- Update content regularly
- Include clear calls-to-action
- Add testimonials when available

### Images
- Use high-quality, professional photos
- Optimize file sizes (< 200KB per image)
- Include descriptive alt text
- Use consistent image styling

### SEO
- Target local keywords
- Update meta descriptions
- Create quality content
- Get listed in local directories
- Encourage client reviews

### Accessibility
- Maintain color contrast ratios
- Use semantic HTML
- Add ARIA labels where needed
- Test with screen readers
- Ensure keyboard navigation works

---

## 📞 Quick Reference

### Key Files
- **Main File**: `dr-maya-reynolds-updated.html`
- **Documentation**: `README.md`

### Important Sections to Customize
1. Line ~8: Page title and meta description
2. Line ~19-27: Color variables
3. Line ~670-680: Contact information
4. Line ~690-850: Service descriptions
5. Line ~900-950: About section biography
6. Line ~970-1100: FAQ content

### Color Palette
```
Navy:        #1A3A52
Sage Green:  #7A9B8E
Warm Beige:  #F4EFE6
Cream:       #FDFBF7
Terracotta:  #C17C5E
Charcoal:    #2D2D2D
Soft Grey:   #6B6B6B
```

---

**Made with ❤️ for mental health professionals**

*Last Updated: January 2026*
