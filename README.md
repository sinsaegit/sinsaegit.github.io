# Sindre Saeter - Portfolio Website

Welcome to my personal portfolio website! This site showcases my CV and fun web projects, hosted on GitHub Pages.

## 🌐 Live Site

Visit the live website at: [https://sinsaegit.github.io](https://sinsaegit.github.io)

## 🚀 Features

- **Responsive Design**: Works beautifully on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **CV Section**: Professional experience, education, skills, and achievements
- **Projects Showcase**: Gallery of fun websites and projects
- **Interactive Elements**: Smooth scrolling, mobile navigation, and hover effects
- **GitHub Pages Ready**: Optimized for GitHub Pages hosting

## 📁 Project Structure

```
sinsaegit.github.io/
├── index.html          # Main homepage
├── style.css           # All styling and responsive design
├── script.js           # Interactive functionality
├── _config.yml         # Jekyll/GitHub Pages configuration
├── README.md           # This file
├── LICENSE             # MIT License
└── .gitignore          # Files to ignore in version control
```

## 🛠️ Setup Instructions

### For GitHub Pages (Automatic)

1. **Enable GitHub Pages**:
   - Go to your repository settings on GitHub
   - Scroll down to "Pages" section
   - Set source to "Deploy from a branch"
   - Select "main" branch and "/ (root)"
   - Click Save

2. **Your site will be available at**: `https://sinsaegit.github.io`

### For Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sinsaegit/sinsaegit.github.io.git
   cd sinsaegit.github.io
   ```

2. **Serve locally** (choose one method):
   
   **Option A: Using Python**:
   ```bash
   python -m http.server 8000
   # Visit http://localhost:8000
   ```
   
   **Option B: Using Node.js**:
   ```bash
   npx serve .
   # Visit http://localhost:3000
   ```
   
   **Option C: Using Jekyll** (if you have Ruby installed):
   ```bash
   gem install jekyll bundler
   jekyll serve
   # Visit http://localhost:4000
   ```

## ✏️ Customization Guide

### 1. Update Personal Information

**In `index.html`**:
- Replace "Sindre Saeter" with your name
- Update the hero section description
- Fill in your actual CV information:
  - Education details
  - Work experience
  - Skills (replace the skill tags)
  - Projects and achievements

**In `_config.yml`**:
- Update title, description, and author fields
- Add your social media links

### 2. Add Your Projects

Replace the placeholder projects in the "Fun Projects" section:

```html
<!-- Replace this block for each project -->
<div class="project-card">
    <div class="project-image">
        <!-- Add a screenshot or keep the emoji -->
        <img src="path/to/your/project-image.jpg" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Your Project Name</h3>
        <p>Description of your project...</p>
        <div class="project-tags">
            <span class="tag">Technology1</span>
            <span class="tag">Technology2</span>
        </div>
        <a href="https://your-project-url.com" class="project-link">View Project →</a>
    </div>
</div>
```

### 3. Update Contact Information

**In `index.html`**, update the contact section:
- Replace email link with your actual email
- Update GitHub link to your profile
- Add your LinkedIn or other social profiles

### 4. Customize Colors and Styling

**In `style.css`**, you can customize:
- Primary color: Search for `#2563eb` and replace with your preferred color
- Fonts: Update the Google Fonts import and font-family declarations
- Spacing and layout: Modify padding, margins, and grid layouts

### 5. Add Your CV PDF

1. Add your CV PDF file to the repository
2. Update the download link in `index.html`:
   ```html
   <a href="path/to/your-cv.pdf" class="btn btn-outline" download>Download PDF CV</a>
   ```

## 📱 Mobile-First Design

The site is built with mobile-first responsive design:
- Hamburger menu for mobile navigation
- Flexible grid layouts that adapt to screen size
- Touch-friendly buttons and interactions
- Optimized typography for different screen sizes

## 🎨 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 Performance Features

- Optimized CSS with minimal external dependencies
- Vanilla JavaScript (no heavy frameworks)
- Responsive images support
- Smooth scrolling and animations
- Lazy loading ready

## 🤝 Contributing

Feel free to fork this repository and customize it for your own portfolio! If you make improvements that could benefit others, pull requests are welcome.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Troubleshooting

### Common Issues

1. **Site not loading on GitHub Pages**:
   - Check that GitHub Pages is enabled in repository settings
   - Ensure `index.html` is in the root directory
   - Wait a few minutes for deployment to complete

2. **Styling not loading**:
   - Verify `style.css` path in `index.html`
   - Check browser console for any errors

3. **Interactive features not working**:
   - Ensure `script.js` is linked correctly
   - Check browser console for JavaScript errors

### Need Help?

- Open an issue in this repository
- Check GitHub Pages documentation
- Verify all file paths are correct

---

Built with ❤️ and hosted on GitHub Pages