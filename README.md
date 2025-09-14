# Modern BTech CSE Portfolio Template

A clean, modern, and fully responsive portfolio template designed specifically for BTech Computer Science Engineering students. Perfect for showcasing your projects, skills, and achievements in a professional manner.

## 🌟 Features

- **Modern Design**: Clean and professional layout with smooth animations
- **Fully Responsive**: Works perfectly on all devices (mobile, tablet, desktop)
- **Interactive Elements**: Typing animation, smooth scrolling, and hover effects
- **Easy Customization**: Simple to modify colors, content, and layout
- **Fast Loading**: Optimized for performance with minimal dependencies
- **Cross-browser Compatible**: Works on all modern browsers
- **Bootstrap 5**: Built with the latest Bootstrap framework
- **Font Awesome Icons**: Beautiful icons for enhanced visual appeal
- **Google Fonts**: Professional typography with Poppins font

## 🚀 Quick Start

1. **Download/Clone** this template
2. **Replace placeholder content** with your own information
3. **Add your profile picture** to `assets/images/profile.jpg`
4. **Add project images** to `assets/images/`
5. **Open `index.html`** in your browser

## 📁 Project Structure

```
Portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Custom CSS styles
├── js/
│   └── script.js      # JavaScript functionality
├── assets/
│   └── images/        # Your images go here
└── README.md          # This file
```

## 🎨 Customization Guide

### 1. Personal Information

#### Update Your Details in `index.html`:

**Line 7**: Update the page title
```html
<title>Your Name - BTech CSE Portfolio</title>
```

**Line 25**: Update navbar brand name
```html
<a class="navbar-brand fw-bold" href="#home">Your Name</a>
```

**Line 47-48**: Update your name and typing texts
```html
<h1 class="display-4 fw-bold mb-3">
    Hi, I'm <span class="text-primary">Your Name</span>
</h1>
```

**Line 53-56**: Update your description
```html
<p class="lead mb-4">
    Your personal description here...
</p>
```

#### Update Social Links (Lines 66-77):
```html
<a href="https://github.com/yourusername" class="social-link" target="_blank">
    <i class="fab fa-github"></i>
</a>
<a href="https://linkedin.com/in/yourusername" class="social-link" target="_blank">
    <i class="fab fa-linkedin"></i>
</a>
<!-- Add your actual URLs -->
```

### 2. About Section

#### Update Education Details (Lines 100-106):
```html
<p>BTech in Computer Science Engineering<br>
<strong>Your University Name</strong><br>
Year: 2021-2025<br>
CGPA: Your CGPA/10</p>
```

#### Update About Cards Content (Lines 95-130):
- Modify the content in each about card
- Change icons if needed (use Font Awesome classes)

### 3. Skills Section

#### Update Programming Languages (Lines 150-195):
```html
<div class="skill-item">
    <div class="skill-info d-flex justify-content-between">
        <span>Python</span>
        <span>90%</span> <!-- Update percentage -->
    </div>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 90%"></div> <!-- Update width -->
    </div>
</div>
```

#### Update Tech Stack (Lines 245-255):
```html
<div class="tech-stack text-center">
    <span class="tech-item">Your Technology</span>
    <!-- Add more technologies -->
</div>
```

### 4. Projects Section

#### Replace Project Content (Lines 275-350):

For each project card:
```html
<div class="project-card">
    <div class="project-image">
        <img src="assets/images/your-project.jpg" alt="Your Project Name" class="w-100">
        <div class="project-overlay">
            <div class="project-links">
                <a href="your-demo-link" class="btn btn-primary btn-sm" target="_blank">
                    <i class="fas fa-external-link-alt"></i> Live Demo
                </a>
                <a href="your-github-link" class="btn btn-outline-light btn-sm" target="_blank">
                    <i class="fab fa-github"></i> Code
                </a>
            </div>
        </div>
    </div>
    <div class="project-content">
        <h5>Your Project Name</h5>
        <p>Your project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
    </div>
</div>
```

### 5. Contact Information

#### Update Contact Details (Lines 390-415):
```html
<div class="contact-details">
    <h5>Email</h5>
    <p>your.email@example.com</p> <!-- Update with your email -->
</div>
```

### 6. Adding Images

#### Profile Picture:
- Add your profile picture as `assets/images/profile.jpg`
- Recommended size: 400x400px (square format)
- Format: JPG or PNG

#### Project Images:
- Add project screenshots to `assets/images/`
- Name them: `project1.jpg`, `project2.jpg`, etc.
- Recommended size: 600x400px (landscape format)
- Update the src attributes in HTML accordingly

### 7. Color Customization

#### Update Colors in `css/style.css` (Lines 3-12):
```css
:root {
    --primary-color: #007bff;      /* Main theme color */
    --secondary-color: #6c757d;    /* Secondary color */
    --accent-color: #28a745;       /* Accent color */
    /* Update these values with your preferred colors */
}
```

### 8. Typing Animation

#### Update Typing Texts in `js/script.js` (Lines 11-17):
```javascript
const typedTexts = [
    'Your Role 1',
    'Your Role 2',
    'Your Role 3',
    'Your Role 4'
];
```

## 🎯 Workshop Instructions

### For Workshop Demonstration:

1. **Preparation** (5 minutes):
   - Open the template in a code editor
   - Show the file structure
   - Explain the technologies used

2. **Live Customization** (15 minutes):
   - Change the name and title
   - Update one skill percentage
   - Modify a project description
   - Change the primary color

3. **Preview** (5 minutes):
   - Open in browser
   - Demonstrate responsiveness
   - Show animations and interactions

### Student Exercise:
After the demonstration, students can:
1. Download the template
2. Customize with their own information
3. Add their own projects
4. Upload to GitHub Pages for hosting

## 📱 Responsive Breakpoints

- **Mobile**: 576px and below
- **Tablet**: 768px and below
- **Desktop**: 992px and above

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Bootstrap 5.3**: Responsive framework
- **Font Awesome 6.4**: Icon library
- **Google Fonts**: Poppins font family

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 Tips for Students

### Content Writing:
1. **Keep descriptions concise** but informative
2. **Use action words** in project descriptions
3. **Quantify achievements** where possible
4. **Proofread everything** before publishing

### Technical Skills:
1. **Be honest** about skill levels
2. **Focus on relevant technologies** for your field
3. **Include both frontend and backend** skills
4. **Add soft skills** in the about section

### Projects:
1. **Showcase variety** in your projects
2. **Include live demos** whenever possible
3. **Provide GitHub links** for code review
4. **Explain your role** in team projects

## 🚀 Deployment Options

### GitHub Pages (Free):
1. Create a new repository
2. Upload your files
3. Enable GitHub Pages in settings
4. Your portfolio will be live at `username.github.io/repository-name`

### Netlify (Free):
1. Create account on Netlify
2. Drag and drop your folder
3. Get instant live URL

### Vercel (Free):
1. Create account on Vercel
2. Connect your GitHub repository
3. Automatic deployment on every commit

## 🔧 Advanced Customizations

### Adding New Sections:
1. Add HTML structure
2. Update navigation menu
3. Add CSS styles
4. Update JavaScript for smooth scrolling

### Adding Animations:
1. Use CSS animations or transitions
2. Consider libraries like AOS (Animate On Scroll)
3. Keep animations subtle and purposeful

### Performance Optimization:
1. Compress images before uploading
2. Minify CSS and JavaScript for production
3. Use CDN links for external libraries

## 📞 Support

For workshop support or questions:
- Check the code comments for guidance
- Use browser developer tools for debugging
- Refer to Bootstrap and Font Awesome documentation

## 📄 License

This template is free to use for educational and personal purposes. Perfect for BTech CSE students to create their first professional portfolio.

---

**Happy Coding! 🚀**

*Make sure to customize this template to reflect your unique personality and skills. Your portfolio is often the first impression you make on potential employers or collaborators.*