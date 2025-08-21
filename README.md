# Modern Professional Portfolio Website

A clean, modern, and responsive personal portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your professional experience, skills, projects, and achievements.

## ✨ Features

- **Modern Design**: Clean, minimalistic design with soft shadows and rounded corners
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Smooth Animations**: CSS animations and JavaScript interactions
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Professional Sections**: All essential portfolio sections included
- **Contact Form**: Functional contact form with validation
- **Download CV**: Easy CV download functionality
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Loading Animation**: Professional loading screen
- **SEO Optimized**: Proper meta tags and semantic HTML

## 📋 Sections Included

1. **Header/Hero Section** - Name, title, tagline, and professional photo
2. **About Me** - Professional bio with statistics
3. **Skills** - Technical and soft skills with progress bars
4. **Experience** - Timeline of work experience
5. **Education** - Academic background
6. **Projects/Portfolio** - Project showcase with images and tech stack
7. **Achievements/Certifications** - Awards and certifications
8. **Contact Section** - Contact form and social links
9. **Download CV** - PDF download functionality

## 🚀 Quick Start

1. **Clone or Download** the files to your local machine
2. **Open `index.html`** in your web browser
3. **Customize** the content to match your information
4. **Deploy** to your preferred hosting service

## 🛠️ Customization Guide

### Personal Information

Edit the following in `index.html`:

```html
<!-- Hero Section -->
<h1 class="hero-title">Your Name</h1>
<h2 class="hero-subtitle">Your Professional Title</h2>
<p class="hero-tagline">Your Professional Tagline</p>

<!-- Profile Image -->
<img src="your-photo-url.jpg" alt="Your Name">

<!-- Contact Information -->
<p>your.email@example.com</p>
<p>+1 (555) 123-4567</p>
<p>Your Location</p>
```

### Skills Section

Update your skills in the skills section:

```html
<div class="skill-item">
    <div class="skill-info">
        <span>Your Skill</span>
        <span>90%</span>
    </div>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 90%"></div>
    </div>
</div>
```

### Experience Timeline

Add your work experience:

```html
<div class="timeline-item">
    <div class="timeline-content">
        <div class="timeline-header">
            <h3>Your Job Title</h3>
            <span class="company">Company Name</span>
            <span class="period">2020 - Present</span>
        </div>
        <p>Job description and responsibilities...</p>
        <ul>
            <li>Key achievement 1</li>
            <li>Key achievement 2</li>
        </ul>
    </div>
</div>
```

### Projects

Add your projects:

```html
<div class="project-card">
    <div class="project-image">
        <img src="project-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="github-link" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="live-link" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
        </div>
    </div>
</div>
```

### Color Scheme

Customize the color scheme in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    --text-color: #1e293b;
    --text-light: #64748b;
    --background-light: #f8fafc;
    --white: #ffffff;
}
```

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── cv.pdf             # Your CV (add this file)
```

## 🎨 Design Features

- **Grid-based Layout**: Modern CSS Grid and Flexbox
- **Soft Shadows**: Subtle box-shadows for depth
- **Rounded Corners**: Modern border-radius styling
- **Smooth Animations**: CSS transitions and keyframes
- **Gradient Backgrounds**: Beautiful gradient effects
- **Typography**: Clean, readable Inter font
- **Icons**: Font Awesome icons throughout

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints for:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🔧 Technical Features

- **Vanilla JavaScript**: No frameworks required
- **CSS3**: Modern CSS features and animations
- **HTML5**: Semantic HTML structure
- **Font Awesome**: Professional icons
- **Google Fonts**: Inter font family
- **Intersection Observer**: Scroll-based animations
- **Form Validation**: Client-side validation
- **Smooth Scrolling**: Native smooth scroll behavior

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📧 Contact Form

The contact form includes:
- Name, email, subject, and message fields
- Client-side validation
- Success/error notifications
- Form submission simulation

To make it functional, replace the form submission logic in `script.js` with your preferred backend solution.

## 📄 CV Download

Add your CV as `cv.pdf` in the root directory. The download button will automatically work.

## 🚀 Deployment

### Vercel (Recommended)
1. **Install Vercel CLI**: `npm i -g vercel`
2. **Login to Vercel**: `vercel login`
3. **Deploy**: `vercel` (in the project directory)
4. **Follow prompts** to configure your deployment
5. **Your portfolio will be live** at the provided URL!

### Alternative: Deploy via GitHub
1. **Push your code** to a GitHub repository
2. **Go to [vercel.com](https://vercel.com)**
3. **Import your GitHub repository**
4. **Vercel will automatically deploy** your portfolio

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be deployed instantly
3. Get a custom domain if needed

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them back!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Unsplash for placeholder images
- Modern CSS techniques and best practices

## 📞 Support

If you need help customizing your portfolio or have questions, feel free to reach out!

---

**Happy coding! 🎉**
