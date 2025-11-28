# ASN Technologies Website

A modern, responsive creative agency website built with HTML, CSS, and JavaScript.

## 🚀 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Portfolio Showcase**: Display your best projects with multiple layout options
- **Contact Form**: Integrated with Formspree for easy form submissions
- **Newsletter Subscription**: Collect email subscribers via Formspree
- **Smooth Animations**: GSAP-powered animations for a premium feel
- **SEO Optimized**: Proper meta tags, sitemap, and robots.txt included

## 📁 Project Structure

```
ashley/
├── css/                    # Stylesheets
│   ├── style.css          # Main styles
│   └── plugins/           # Third-party CSS
├── js/                     # JavaScript files
│   ├── main.js            # Main functionality
│   └── plugins/           # Third-party JS libraries
├── img/                    # Images and assets
│   ├── works/             # Portfolio project images
│   ├── blog/              # Blog images
│   └── faces/             # Team member photos
├── home-1.html            # Homepage
├── portfolio-2.html       # Portfolio grid
├── portfolio-3.html       # Portfolio slider
├── contact.html           # Contact page
├── services.html          # Services page
├── blog.html              # Blog listing
└── sitemap.xml            # SEO sitemap
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with animations
- **JavaScript**: Interactive functionality
- **GSAP**: Animation library
- **Swiper.js**: Touch slider
- **Formspree**: Form handling

## 📦 Deployment

### Quick Deploy to Netlify (Recommended)

1. Go to [netlify.com](https://netlify.com)
2. Sign up or log in
3. Drag and drop the `ashley` folder
4. Your site is live!

### Deploy to GitHub Pages

1. Create a new repository on GitHub
2. Push all files to the repository
3. Go to Settings > Pages
4. Select main branch as source
5. Your site will be live at `username.github.io/repo-name`

### Deploy to Vercel

1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Click Deploy
4. Done!

## 🔧 Configuration

### Update Contact Form Email

The contact form is connected to Formspree. To receive emails:

1. Go to [formspree.io](https://formspree.io)
2. Create an account
3. Create a new form
4. Replace the form action URL in `contact.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

### Update Newsletter Form

Newsletter forms use the same Formspree endpoint. Update all instances of:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Update Domain in Sitemap

Edit `sitemap.xml` and replace `asntechnologies.com` with your actual domain.

## 📝 Customization

### Update Portfolio Projects

1. Add project images to `img/works/`
2. Edit portfolio pages (`portfolio-2.html`, `portfolio-3.html`)
3. Update project detail pages (`project-1.html`, etc.)

### Update Team Members

1. Add team photos to `img/faces/`
2. Edit `home-1.html` and `team.html`
3. Update social media links

### Update Services

1. Edit `services.html` for the services list
2. Update individual service pages (`service-branding.html`, etc.)

## 🎨 Color Scheme

- **Primary**: Orange (#FF6B35)
- **Dark Background**: #0A0A0A
- **Light Text**: #FFFFFF
- **Muted Text**: #999999

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

© 2025 ASN Technologies. All Rights Reserved.

## 🤝 Support

For support, email asncreativeagency@gmail.com

## 🌟 Credits

- Template Design: Custom
- Icons: Font Awesome
- Animations: GSAP
- Slider: Swiper.js
