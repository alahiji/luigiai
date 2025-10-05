# Luigi AI Website

A modern, minimalistic website for Luigi AI - an AI consulting company helping businesses understand and implement artificial intelligence solutions.

## 🎨 Design Features

- **Color Scheme**: Inspired by the Luigi AI logo
  - Primary Dark Green: `#0A5C4A`
  - Primary Light Green: `#5CB85C`
  - Clean, minimalistic design with smooth gradients

- **Sections**:
  - Hero section with animated floating cards
  - Services showcase (6 core offerings)
  - About section with company stats
  - Consultation request form
  - Professional footer

- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices

## 🚀 Getting Started

### Option 1: Open Directly
Simply open `index.html` in your web browser by double-clicking the file.

### Option 2: Local Server (Recommended)
For the best experience, run a local server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Then visit: http://localhost:8000
```

**Using Node.js:**
```bash
# Install http-server globally
npm install -g http-server

# Run server
http-server

# Then visit: http://localhost:8080
```

**Using VS Code:**
- Install "Live Server" extension
- Right-click on `index.html`
- Select "Open with Live Server"

## 📁 File Structure

```
Luigi AI Website/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript functionality
├── static/
│   └── Luigi AI Logo.png
├── BUSINESS_ROADMAP.md # Complete business guide
└── README.md           # This file
```

## 🔧 Customization

### Update Contact Information
The form currently simulates submission. To connect it to a real backend:

1. **Option A: Use Formspree (Easiest)**
   - Sign up at [formspree.io](https://formspree.io)
   - Update the form action in `index.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

2. **Option B: Use EmailJS**
   - Sign up at [emailjs.com](https://www.emailjs.com)
   - Follow their integration guide
   - Update `script.js` with EmailJS code

3. **Option C: Build Custom Backend**
   - Create API endpoint (Node.js, Python Flask, etc.)
   - Update the fetch URL in `script.js`
   - Handle form data on your server

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-dark: #0A5C4A;
    --primary-light: #5CB85C;
    /* Add your colors here */
}
```

### Add Your Information
- Update company stats in the About section
- Add your email/phone in the footer
- Customize service descriptions
- Add social media links

## 📊 Form Integration Guide

The consultation form is ready to integrate with various services:

### Recommended Services:
1. **Formspree** - Free tier available, easy setup
2. **EmailJS** - Send emails directly from JavaScript
3. **Netlify Forms** - If hosting on Netlify
4. **Google Forms** - Embed or redirect
5. **Custom Backend** - Full control

### Current Form Fields:
- Full Name (required)
- Email Address (required)
- Company Name
- Industry (dropdown)
- Interest Area (required)
- Message/Needs (textarea)

## 🌐 Deployment Options

### Free Hosting:
1. **Netlify** (Recommended)
   - Drag and drop your folder
   - Automatic HTTPS
   - Custom domain support
   - Visit: [netlify.com](https://www.netlify.com)

2. **Vercel**
   - Similar to Netlify
   - Great performance
   - Visit: [vercel.com](https://vercel.com)

3. **GitHub Pages**
   - Free with GitHub account
   - Push code to repository
   - Enable Pages in settings

4. **Cloudflare Pages**
   - Fast global CDN
   - Free tier available
   - Visit: [pages.cloudflare.com](https://pages.cloudflare.com)

### Custom Domain:
- Purchase domain from Namecheap, GoDaddy, or Google Domains
- Point DNS to your hosting provider
- Most hosts provide step-by-step guides

## 📈 SEO Optimization

To improve search engine visibility:

1. **Add Meta Tags** (in `<head>` of index.html):
```html
<meta name="description" content="Luigi AI provides expert AI consulting to help businesses understand and implement artificial intelligence solutions.">
<meta name="keywords" content="AI consulting, artificial intelligence, business AI, AI strategy">
<meta property="og:title" content="Luigi AI - AI Consulting for Your Business">
<meta property="og:description" content="Expert AI consulting to transform your business">
<meta property="og:image" content="URL_TO_PREVIEW_IMAGE">
```

2. **Create sitemap.xml**
3. **Submit to Google Search Console**
4. **Set up Google Analytics**
5. **Create Google Business Profile**

## 🎯 Next Steps

1. **Immediate Actions:**
   - [ ] Test the website on different devices
   - [ ] Set up form submission (Formspree recommended)
   - [ ] Deploy to hosting platform
   - [ ] Connect custom domain
   - [ ] Set up Google Analytics

2. **Content Updates:**
   - [ ] Add real testimonials as you get clients
   - [ ] Create case studies
   - [ ] Add blog section (optional)
   - [ ] Update stats with real numbers

3. **Marketing:**
   - [ ] Share on LinkedIn
   - [ ] Add to email signature
   - [ ] Include in business cards
   - [ ] Use in proposals

## 📚 Business Resources

Check out `BUSINESS_ROADMAP.md` for:
- Complete guide to mastering AI consulting skills
- Step-by-step client acquisition strategies
- Service pricing recommendations
- Marketing and networking tactics
- Tools and resources
- Monthly revenue goals
- Common pitfalls to avoid

## 🛠️ Technical Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript** - No dependencies, fast loading
- **Google Fonts** - Inter font family
- **SVG Icons** - Scalable, crisp icons

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Support

For questions or issues:
- Review the code comments in each file
- Check the BUSINESS_ROADMAP.md for business guidance
- Test in different browsers if something looks off

## 📄 License

This website template is created for Luigi AI. Feel free to customize it for your business needs.

---

**Built with care for Luigi AI** 🚀

Good luck with your AI consulting business!
