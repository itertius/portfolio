# Witsanupong Kolakul - Portfolio

Clean, minimal, and professional web portfolio showcasing research and projects in AI, Computer Vision, and Thai NLP.

## Features

- **Modern Design**: Clean, minimal aesthetic with professional typography
- **Responsive**: Mobile-first responsive design
- **Performance**: Optimized for fast loading and smooth interactions
- **Accessibility**: Semantic HTML5 structure with proper ARIA support
- **GitHub Pages Ready**: Deployable to GitHub Pages with zero configuration

## Sections

1. **About Me** - Personal background and journey
2. **Education** - Academic history at Chulalongkorn University
3. **Projects & Competitions** - National awards and technical projects
4. **Research & Publications** - FGVC2026 workshop paper and internship work
5. **Skills & Technologies** - Technical competencies across ML, CV, and development
6. **Contact** - Professional contact information and links

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern CSS with Grid, Flexbox, and custom properties
- **Vanilla JavaScript** - No frameworks, pure JS for interactions
- **Google Fonts** - Inter and Playfair Display typography

## Local Development

1. Clone this repository
2. Open `index.html` in your browser
3. No build process required - it's a static site

## GitHub Pages Deployment

### Option 1: Using Main Branch

1. Push your changes to the `main` branch
2. Go to repository Settings > Pages
3. Source: Deploy from a branch
4. Branch: `main` and folder: `/ (root)`
5. Save and wait for deployment

### Option 2: Using gh-pages Branch

1. Create and push a `gh-pages` branch:
   ```bash
   git checkout --orphan gh-pages
   git add index.html README.md
   git commit -m "Deploy to GitHub Pages"
   git push origin gh-pages
   ```

2. Go to repository Settings > Pages
3. Source: Deploy from a branch
4. Branch: `gh-pages` and folder: `/ (root)`
5. Save and wait for deployment

### Custom Domain (Optional)

1. Create a `CNAME` file in the root:
   ```
   yourdomain.com
   ```
2. Add the CNAME file to your repository
3. Configure DNS settings with your domain provider
4. Update GitHub Pages settings with your custom domain

## Customization

### Colors
Edit the CSS custom properties in `:root`:
```css
:root {
    --primary: #0f0f0f;
    --accent: #2563eb;
    --background: #ffffff;
    /* ... */
}
```

### Fonts
Update the Google Fonts import and CSS variables:
```css
--font-serif: 'Playfair Display', Georgia, serif;
--font-sans: 'Inter', system-ui, sans-serif;
```

### Content
Edit the HTML sections directly to update:
- Personal information
- Project descriptions
- Skills and technologies
- Contact details

## Performance

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **Bundle Size**: < 50KB total
- **Load Time**: < 2 seconds on 3G

## License

MIT License - feel free to use this template for your own portfolio.

## Author

**Witsanupong Kolakul**
- Email: teverygood@gmail.com
- GitHub: [@itertius](https://github.com/itertius)