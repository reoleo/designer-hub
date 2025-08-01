# Designer Hub Website

A modern, responsive website for showcasing designers and their work. Built with HTML, CSS, and JavaScript.

## Features

- 🎨 Modern and responsive design
- 📱 Mobile-friendly navigation
- 👥 Designer profiles and portfolios
- 🚀 Project showcases
- 📧 Contact form with validation
- ✨ Smooth animations and interactions
- 🔍 SEO optimized

## File Structure

```
designer-hub/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Getting Started

1. **Download the files** to your local machine
2. **Open `index.html`** in your web browser to view the website
3. **Customize the content** by editing the HTML file
4. **Modify styles** by editing the CSS file
5. **Add functionality** by editing the JavaScript file

## Customization

### Changing Colors
The main color scheme uses blue (`#2563eb`). You can change this by updating the CSS variables in `styles.css`.

### Adding Designers
To add more designers, copy the designer card structure in the HTML:

```html
<div class="designer-card">
    <div class="designer-avatar">
        <img src="path-to-image" alt="Designer Name">
    </div>
    <h3>Designer Name</h3>
    <p class="designer-role">Role</p>
    <p class="designer-bio">Bio description</p>
    <div class="designer-skills">
        <span class="skill-tag">Skill 1</span>
        <span class="skill-tag">Skill 2</span>
    </div>
</div>
```

### Adding Projects
To add more projects, copy the project card structure:

```html
<div class="project-card">
    <div class="project-image">
        <img src="path-to-image" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description</p>
        <div class="project-tags">
            <span class="tag">Tag 1</span>
            <span class="tag">Tag 2</span>
        </div>
    </div>
</div>
```

## Deployment Options

### 1. GitHub Pages (Free)
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### 2. Netlify (Free)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Your site will be deployed instantly
4. You can connect a custom domain

### 3. Vercel (Free)
1. Go to [vercel.com](https://vercel.com)
2. Import your project from GitHub
3. Deploy automatically
4. Connect your custom domain

### 4. Traditional Web Hosting
1. Upload all files to your web hosting provider
2. Make sure `index.html` is in the root directory
3. Your site will be available at your domain

## Custom Domain Setup

1. **Purchase a domain** from a domain registrar (GoDaddy, Namecheap, etc.)
2. **Configure DNS settings**:
   - For GitHub Pages: Add CNAME record pointing to `username.github.io`
   - For Netlify: Add CNAME record pointing to your Netlify URL
   - For Vercel: Add CNAME record pointing to your Vercel URL
3. **Wait for DNS propagation** (can take up to 48 hours)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

1. **Optimize images** before uploading
2. **Use WebP format** for better compression
3. **Minify CSS and JavaScript** for production
4. **Enable gzip compression** on your server
5. **Use a CDN** for faster loading

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help with deployment or customization, please open an issue on GitHub or contact us through the website's contact form. 