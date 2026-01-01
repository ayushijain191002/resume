# Ayushi Jain - Product Designer Portfolio

A modern, responsive portfolio website showcasing product design work and case studies.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Portfolio Showcase**: Dedicated section for displaying your Figma designs and case studies
- **Contact Form**: Interactive contact form for potential clients
- **Fast Loading**: Optimized for performance and SEO

## Customization Guide

### Adding Your Images

1. **Create an images folder**: 
   ```bash
   mkdir images
   ```

2. **Add your Figma design screenshots**: 
   - Save your designs as JPG/PNG files (recommended size: 600x400px)
   - Name them descriptively (e.g., `ecommerce-app.jpg`, `dashboard-design.png`)

3. **Update the HTML**:
   Replace the image placeholders in `index.html`:
   ```html
   <!-- Replace this -->
   <div class="image-placeholder">
       <i class="fas fa-image"></i>
       <p>Add your Figma design here</p>
   </div>
   
   <!-- With this -->
   <img src="images/your-design.jpg" alt="Project Name">
   ```

### Personal Information

Update the following sections in `index.html`:

1. **Contact Information** (lines 180-190):
   - Replace `ayushi.jain@email.com` with your actual email
   - Add your phone number
   - Update LinkedIn URL

2. **About Me Text** (lines 70-85):
   - Customize the description to match your experience
   - Update skills and tools as needed

3. **Portfolio Projects** (lines 95-170):
   - Replace project titles and descriptions
   - Update tags to match your work
   - Add links to your case studies

## Deployment on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `ayushi-jain-portfolio` or `your-username.github.io`
3. Make sure it's set to **Public**

### Step 2: Upload Your Files

1. Upload all files to your repository:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
   - `images/` folder with your design screenshots

### Step 3: Enable GitHub Pages

1. Go to your repository **Settings**
2. Scroll down to **Pages** section
3. Under **Source**, select "Deploy from a branch"
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**

### Step 4: Access Your Website

Your portfolio will be available at:
- If named `your-username.github.io`: `https://your-username.github.io`
- If named differently: `https://your-username.github.io/repository-name`

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── images/             # Your design images
│   ├── project1.jpg
│   ├── project2.jpg
│   └── profile.jpg
└── README.md           # This file
```

## Customization Tips

### Colors
Update these CSS variables in `styles.css` to match your brand:
```css
:root {
    --primary-color: #6366f1;    /* Main brand color */
    --accent-color: #fbbf24;     /* Accent/highlight color */
    --text-color: #1f2937;       /* Main text color */
}
```

### Fonts
Change the Google Fonts import in `index.html` (line 7):
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

### Adding Case Study Pages

1. Create separate HTML files for each case study:
   ```
   case-study-ecommerce.html
   case-study-dashboard.html
   ```

2. Update the portfolio links in `index.html`:
   ```html
   <a href="case-study-ecommerce.html" class="portfolio-link">View Case Study</a>
   ```

## Local Development

To preview your website locally:

1. **Using Python** (if installed):
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`

2. **Using Node.js** (if installed):
   ```bash
   npx serve .
   ```

3. **Using VS Code**: Install the "Live Server" extension and right-click on `index.html`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Next Steps

1. **Add your actual content**: Replace all placeholder text and images
2. **Create case study pages**: Detailed pages for each project
3. **Add analytics**: Consider adding Google Analytics
4. **SEO optimization**: Add meta descriptions and optimize images
5. **Performance**: Optimize images and consider lazy loading

## License

This template is free to use for personal portfolios.

---

**Need help?** Feel free to customize this portfolio to match your personal brand and showcase your amazing design work!
