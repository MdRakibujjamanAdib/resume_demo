# Md Rakibujjaman Adib - Personal Portfolio

A professional, dark-themed single-page portfolio website built with pure HTML, CSS, and JavaScript.

## 🚀 Features

- **Single File Design**: All HTML, CSS, and JavaScript in one `index.html` file
- **Dark Theme**: Sleek dark design with subtle glow effects
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Scroll-triggered fade-in animations and smooth scrolling
- **Modern UI**: Glassmorphism effects with backdrop blur
- **Sections Included**:
  - Sticky navigation header
  - Hero section with introduction
  - Portfolio/Projects showcase
  - About Me section
  - Skills grid
  - Contact footer with social links

## 📁 Files

- `index.html` - The complete standalone website
- `README.md` - Project information
- `DEPLOYMENT.md` - This deployment guide

## 🌐 Deploy to GitHub Pages

### Step 1: Push to GitHub

1. Create a new repository on GitHub or use an existing one
2. Push your files:
   ```powershell
   git init
   git add index.html README.md DEPLOYMENT.md
   git commit -m "Add standalone portfolio website"
   git branch -M main
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git push -u origin main
   ```

### Step 2: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** → **Pages** (in the left sidebar)
3. Under "Source", select the branch you want to deploy (usually `main`)
4. Click **Save**
5. Your site will be live at: `https://yourusername.github.io/your-repo-name/`

## 🎨 Customization

### Update Personal Information

Open `index.html` and modify:

1. **Header Logo** (line ~476): Change "ADIB." to your preferred logo
2. **Hero Section** (line ~490-494):
   - Change your name in `<h1>`
   - Update title/roles in `<h2>`
   - Modify description in `<p>`
3. **Projects** (lines ~500-525):
   - Update project images (replace Unsplash URLs)
   - Change project titles and categories
4. **About Section** (lines ~530-540):
   - Replace profile image URL
   - Update your bio paragraphs
5. **Skills** (lines ~546-558):
   - Add or remove skills as needed
6. **Contact Section** (lines ~563-567):
   - Update email address
   - Update social media links (LinkedIn, Instagram, Behance)

### Update Images

Replace the placeholder Unsplash images with your own:
- Upload images to your repository or use external hosting
- Replace URLs in the `src` attributes
- Recommended dimensions: 800x533px for project images

### Update Colors

Modify CSS variables at the top of the `<style>` section (lines ~14-20):
```css
:root {
  --bg-color: #050505;              /* Main background */
  --primary-text: rgba(255, 255, 255, 0.9);   /* Main text */
  --secondary-text: rgba(255, 255, 255, 0.6); /* Secondary text */
  --card-bg: rgba(26, 26, 26, 0.5); /* Card backgrounds */
  --card-border: rgba(255, 255, 255, 0.1);    /* Card borders */
}
```

### Add Custom Font

The site uses Inter font from Google Fonts. To change:
1. Find the font link (line ~11-12)
2. Replace with your preferred Google Font
3. Update `font-family` in the body CSS (line ~36)

## 📧 Contact Form Setup

The current contact section is display-only. To add a working contact form:

**Option 1: Use Formspree (Recommended)**
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  <input type="text" name="name" placeholder="Your Name" required>
  <input type="email" name="email" placeholder="Your Email" required>
  <textarea name="message" placeholder="Your Message" required></textarea>
  <button type="submit">Send Message</button>
</form>
```

**Option 2: Use Netlify Forms** (if hosting on Netlify)
Add `netlify` attribute to your form tag:
```html
<form name="contact" method="POST" data-netlify="true">
```

**Option 3: Use your own backend** with a custom API endpoint

## 🔗 Social Media Links

Update social links in the footer (around line 567):
- **LinkedIn**: Replace `#` with your LinkedIn profile URL
- **Instagram**: Replace `#` with your Instagram profile URL
- **Behance**: Replace `#` with your Behance profile URL

Example:
```html
<a href="https://linkedin.com/in/yourprofile">...</a>
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Performance Tips

1. **Optimize Images**: Compress images before uploading (use TinyPNG or similar)
2. **Use WebP Format**: Convert images to WebP for better compression
3. **Enable Caching**: GitHub Pages automatically handles this
4. **Minify Code**: For production, consider minifying your HTML/CSS/JS

## 📄 License

© 2025 Md Rakibujjaman Adib. All rights reserved.

---

**Questions?** Open an issue on GitHub or contact via the website!
