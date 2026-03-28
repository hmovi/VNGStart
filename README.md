# Vera North Group - Homepage

A professional, Bain/McKinsey-inspired homepage for Vera North Group, a boutique management consulting firm connecting businesses across MENA, India, North America, and Europe.

![Vera North Group](https://img.shields.io/badge/Status-Production%20Ready-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🌍 Overview

This homepage showcases Vera North Group's comprehensive consulting services, global presence, and thought leadership. Designed with the sophistication and credibility of top-tier consulting firms like Bain & Company and McKinsey & Company.

**Live Demo**: Once deployed to GitHub Pages, your site will be accessible at:
```
https://[your-username].github.io/[repository-name]/
```

## ✨ Features

- **Professional Design**: Bain/McKinsey-inspired aesthetic with clean layouts and authoritative typography
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Subtle fade-in effects and interactive hover states
- **7+ Service Areas**: Comprehensive showcase of all consulting services
- **Global Presence**: 5 operational hubs across 3 continents
- **Integrated Insights**: Direct links to Medium blog articles
- **Performance Optimized**: Fast loading with clean, efficient code
- **SEO Ready**: Semantic HTML structure for search engine optimization

## 🚀 Quick Start

### Option 1: Direct Use
1. Download `vera-north-group-homepage.html`
2. Open the file in any modern web browser
3. That's it! The page is fully self-contained.

### Option 2: Deploy to GitHub Pages

1. **Create a new GitHub repository**
   ```bash
   # Create a new repository on GitHub
   # Name it something like: vera-north-group-website
   ```

2. **Clone your repository**
   ```bash
   git clone https://github.com/[your-username]/vera-north-group-website.git
   cd vera-north-group-website
   ```

3. **Add the homepage file**
   ```bash
   # Rename the file to index.html
   cp vera-north-group-homepage.html index.html
   
   # Add and commit
   git add index.html
   git commit -m "Initial commit: Add Vera North Group homepage"
   git push origin main
   ```

4. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click `Settings` → `Pages`
   - Under "Source", select `main` branch
   - Click `Save`
   - Your site will be live at: `https://[your-username].github.io/vera-north-group-website/`

## 📁 File Structure

```
vera-north-group-website/
│
├── index.html              # Main homepage file
├── README.md              # This file
│
└── assets/                # (Optional) For future expansion
    ├── images/
    ├── css/
    └── js/
```

## 🎨 Design Elements

### Color Palette
- **Primary Navy**: `#0A2540` - Main brand color
- **Secondary Navy**: `#1A3A5C` - Supporting color
- **Accent Blue**: `#2E5C8A` - Interactive elements
- **Gold**: `#B8956A` - Premium accents
- **Light Blue**: `#E8F1F8` - Backgrounds

### Typography
- **Headlines**: Playfair Display (Serif)
- **Body Text**: Inter (Sans-serif)

### Key Sections
1. **Navigation Bar** - Fixed header with smooth scroll
2. **Hero Section** - Bold value proposition with statistics
3. **Services Grid** - 9 service cards with hover effects
4. **Global Presence** - 5 operational hubs showcase
5. **Insights Section** - Latest Medium articles
6. **CTA Section** - Conversion-focused call-to-action
7. **Footer** - Comprehensive site navigation

## 🔧 Customization

### Update Contact Links
Replace the contact form URL throughout the file:
```html
<!-- Find and replace -->
https://contact.veranorthgroup.com
<!-- With your actual contact page URL -->
```

### Modify Services
To add/edit services, locate the `.services-grid` section:
```html
<div class="service-card">
    <div class="service-icon">🆕</div>
    <h3 class="service-title">New Service Title</h3>
    <p class="service-description">Service description here.</p>
</div>
```

### Update Insights
Replace Medium article links in the `.insights-grid` section:
```html
<div class="insight-card" onclick="window.open('YOUR_ARTICLE_URL', '_blank')">
    <!-- Card content -->
</div>
```

### Change Colors
All colors are defined in CSS variables at the top of the `<style>` section:
```css
:root {
    --primary-navy: #0A2540;
    --secondary-navy: #1A3A5C;
    /* Modify these values to match your brand */
}
```

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1024px
- **Mobile**: Below 768px

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 Future Enhancements

This homepage is designed for easy expansion:

- [ ] Add individual service pages
- [ ] Create case studies section
- [ ] Build team member profiles
- [ ] Integrate blog RSS feed
- [ ] Add contact form functionality
- [ ] Implement analytics tracking
- [ ] Create industry-specific landing pages
- [ ] Add client testimonials section

## 🔗 External Links

- **Main Website**: [veranorthgroup.com](https://veranorthgroup.com)
- **Medium Blog**: [@HosVNG](https://medium.com/@HosVNG)
- **Substack**: [@hosvng](https://substack.com/@hosvng)
- **Lavaberry Studios**: [lavaberry.veranorthgroup.com](http://lavaberry.veranorthgroup.com)
- **Contact Form**: [contact.veranorthgroup.com](https://contact.veranorthgroup.com)

## 📝 Content Strategy

The homepage content is sourced from:
- Existing Vera North Group website
- Medium blog articles by @HosVNG
- Company service descriptions
- Global operational footprint

### Featured Blog Articles
1. "Selling in North America & Europe" (3-part series)
2. "Vancouver: The Underrated Business Hub"
3. "Mexico: Winning the Trade Wars"
4. "Canada: The New Land of Opportunity"
5. "The New Era of Content Creation"
6. "Navigating the Canadian Job Market"

## 🛠 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **JavaScript** - Interactive functionality
- **Google Fonts** - Playfair Display & Inter

## 📞 Support

For questions or customization support, please contact:
- **Email**: contact@veranorthgroup.com
- **Medium**: [@HosVNG](https://medium.com/@HosVNG)

## 📄 License

© 2026 Vera North Group. All rights reserved.

## 🙏 Acknowledgments

- Design inspiration: Bain & Company, McKinsey & Company
- Typography: Google Fonts
- Content: Vera North Group & @HosVNG Medium articles

---

**Vera North Group** - Connecting Global Markets, Building Strategic Partnerships

*Vancouver · Zurich · Dubai · London · New York*
