# Sumit Suresh Madhav – Portfolio Website

A modern, JSON-driven portfolio showcasing Data Analytics experience, projects, and skills.

## Live

- Live: GitHub Pages (configure your repository Pages settings)

## Features

- **JSON-Driven Content**: All profile data stored in a single JSON file
- **Easy Customization**: Change content without touching HTML/CSS
- **Responsive Design**: Mobile-first approach with 6 breakpoints
- **Modern UI**: Clean design with smooth animations and gradients
- **GitHub Pages Ready**: Static site perfect for GitHub Pages hosting
- **No Build Tools**: Direct static file serving, no compilation needed

## Quick Start

1. **Clone/Download** this repository
2. **Edit** `data/profile.json` with your information (already set for Sumit)
3. **Deploy** to GitHub Pages or any static hosting service
4. **Done!** Your portfolio is live

## Project Structure

```
├── index.html              # Main HTML template (with placeholders)
├── data/
│   └── profile.json       # All your profile data
├── assets/
│   ├── css/              # Compiled stylesheets
│   ├── js/
│   │   ├── profile-loader.js  # Dynamic content loader
│   │   └── main.js           # UI interactions
│   ├── sass/             # Source stylesheets
│   └── webfonts/         # Icon fonts
└── images/               # Your images and media
```

## Customizing Your Profile

### 1. Edit Profile Information

Open `data/profile.json` and update the following sections:

#### Basic Profile
```json
"profile": {
  "name": "Your Name",
  "title": "Your Title",
  "organization": "Your Organization",
  "profileImage": "images/your-photo.jpg",
  "cvPath": "assets/Sumit_DA_Resume.pdf"
}
```

#### Bio Sections
```json
"bio": {
  "introduction": "Your introduction with <span class='highlight'>highlighted</span> text...",
  "background": "Your background and experience...",
  "researchFocus": "Your research interests..."
}
```

#### Contact & Social Links
```json
"contact": {
  "email": "your.email@example.com",
  "linkedin": "https://linkedin.com/in/yourprofile",
  "github": "https://github.com/yourusername",
  "googleScholar": "https://scholar.google.com/citations?user=YOUR_ID",
  "website": "https://yourwebsite.com"
}
```

#### Publications
```json
"publications": [
  {
    "id": "unique-id",
    "title": "Paper Title",
    "authors": "You et al",
    "venue": "Conference/Journal",
    "description": "Brief description of the work",
    "image": "images/paper-image.png",
    "links": {
      "paper": "https://link-to-paper.com",
      "github": "https://github.com/repo",
      "status": "Published" // or "In Review"
    }
  }
]
```

#### Projects
```json
"projects": [
  {
    "id": "project-id",
    "title": "Project Name",
    "year": "2024",
    "shortDescription": "Brief description for card front",
    "detailedDescription": "Detailed description for card back",
    "media": {
      "type": "video", // or "image"
      "src": "images/demo.mp4",
      "poster": "images/poster.jpg", // for videos
      "autoplay": true,
      "loop": true,
      "muted": true,
      "controls": false
    },
    "techStack": ["Python", "PyTorch", "React"],
    "links": {
      "website": "https://project-site.com",
      "github": "https://github.com/repo",
      "details": "#"
    }
  }
]
```

### 2. Add Your Images

1. Place your profile photo in the `images/` directory
2. Add project screenshots/videos
3. Add publication preview images
4. Update the paths in `profile.json`

### 3. Customize Colors (Optional)

Edit the theme colors in `profile.json`:

```json
"siteConfig": {
  "themeColors": {
    "primaryRed": "#C41230",
    "lightRed": "#e63946",
    "darkRed": "#a01828",
    "textDark": "#2b2d42",
    "textLight": "#6c757d",
    "bgLight": "#f8f9fa",
    "white": "#ffffff"
  }
}
```

## Deployment

GitHub Pages via Actions (no build step). See `README_DEPLOY.md` for step-by-step instructions and DNS records.

## Recent Updates

- ✅ **Complete Portfolio Transformation**: Migrated from previous client to Sumit's Data Analyst profile
- ✅ **Professional Headshot**: Integrated Sumit's professional photo
- ✅ **10 Comprehensive Projects**: Added detailed projects showcasing 8+ years of experience + personal development
- ✅ **Mobile-First Design**: Tested and optimized across all screen sizes
- ✅ **Production Ready**: Accessibility audited and cross-browser tested

## Portfolio Highlights

- **8+ Years Experience**: JPMorgan Chase, PNC Financial, Humana, Tenet Healthcare, Cybage Software
- **Technical Skills**: SQL, Python, R, VBA, Tableau, Power BI, AWS, Azure, Advanced Excel, Dimensional Modeling, Statistical Modeling, Signal Processing, Machine Learning
- **Quantified Achievements**: 12M+ daily transactions, 90% report reduction, 18% forecast accuracy improvement, advanced healthcare analytics, RFM customer segmentation, dimensional database design
- **10 Detailed Projects**: Professional experience + personal development projects showcasing full-stack data analytics capabilities, from database architecture to advanced ML applications
- **Industry Expertise**: Financial Services, Healthcare, Automotive, Personal Finance with cross-domain analytical skills

### Local Development

```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js
npx http-server

# Then visit http://localhost:8000
```

## Advanced Customization

### Adding New Sections

1. Add the section data to `profile.json`
2. Update `index.html` with placeholder elements
3. Extend `profile-loader.js` with a new render function

### Modifying Styles

- Edit SASS files in `assets/sass/`
- Or directly modify `assets/css/main.css`
- Custom styles can be added in `index.html` `<style>` section

### Adding Features

- Extend `profile-loader.js` for new functionality
- Add interactive features in `assets/js/main.js`
- Maintain responsive design principles

## Tips

- **Images**: Optimize images for web (use WebP/JPEG, compress)
- **Videos**: Keep videos short and compressed (MP4 H.264)
- **Content**: Use HTML in descriptions for formatting
- **Performance**: Lazy load images/videos for better performance
- **SEO**: Update meta tags in `index.html` for better search visibility

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Credits

- Base template: [Editorial by HTML5 UP](https://html5up.net)
- Icons: [Font Awesome](https://fontawesome.com)
- Fonts: Open Sans, Roboto Slab (Google Fonts)

## License

- Template: Creative Commons Attribution 3.0
- Your content: Your own copyright
- Modifications: Open source

## Support

For issues or questions:
1. Check existing GitHub issues
2. Review the documentation
3. Create a new issue with details

---

Made for Salesforce professionals and administrators# Personal_site
# Personal_site
