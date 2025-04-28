# Modern Frontend Developer Portfolio

A modern, eye-catching portfolio website for frontend developers with smooth animations, interactive project cards, and elegant scroll effects. This portfolio showcases a developer's skills, projects, and contact information in a visually appealing and interactive way.

## Features

- **Modern Design**: Clean, minimal yet bold design with vibrant accents and soft shadows
- **Responsive Layout**: Fully responsive design that works on all devices
- **Smooth Animations**: Scroll-triggered animations and transitions for a dynamic user experience
- **Interactive Project Cards**: Hover effects and filtering functionality for project showcase
- **Elegant Scroll Effects**: Smooth scrolling and reveal animations
- **Contact Form**: Styled contact form with validation
- **Mobile-Friendly Navigation**: Responsive navigation menu with toggle for mobile devices

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- JavaScript (Vanilla)
- ScrollReveal.js for scroll animations
- Font Awesome for icons
- Google Fonts (Poppins)

## Project Structure

```
portfolio-website/
├── index.html              # Main HTML file
├── css/
│   ├── styles.css          # Main stylesheet
│   ├── styles2.css         # Additional styles
│   └── animations.css      # Animation-specific styles
├── js/
│   └── main.js             # JavaScript functionality
├── assets/                 # Images and other assets
└── devfile.yaml            # Development environment configuration
```

## Getting Started

### Standard Method
1. Clone the repository
2. Open `index.html` in your browser
3. Customize the content to match your personal information and projects

### Using Devfile
This project includes a devfile for containerized development:

1. Install a devfile-compatible IDE or tool (like Eclipse Che, OpenShift Dev Spaces, or VS Code with the appropriate extension)
2. Open the project with your devfile-compatible tool
3. Run the following commands:
   - `install`: Installs HTML validation tools
   - `build`: Validates HTML files
   - `test`: Runs HTML linting and checks CSS files

## Customization

### Changing Colors

The color scheme can be easily modified by changing the CSS variables in the `:root` selector in `styles.css`:

```css
:root {
    --primary-color: #6c63ff;
    --secondary-color: #4db5ff;
    /* other variables */
}
```

### Adding Projects

To add a new project, copy the project card structure in the HTML and update the content:

```html
<div class="project-card" data-category="your-category">
    <div class="project-image">
        <img src="assets/your-project-image.jpg" alt="Project Name">
        <div class="project-overlay">
            <div class="project-links">
                <a href="#" class="project-link"><i class="fas fa-link"></i></a>
                <a href="#" class="project-link"><i class="fab fa-github"></i></a>
            </div>
        </div>
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Project description goes here.</p>
        <div class="project-tags">
            <span class="tag">HTML</span>
            <span class="tag">CSS</span>
            <span class="tag">JavaScript</span>
        </div>
    </div>
</div>
```

### Adding Skills

To add a new skill, add a new skill card to the skills section:

```html
<div class="skill-card">
    <div class="skill-icon">
        <i class="fab fa-your-skill-icon"></i>
    </div>
    <h4>Skill Name</h4>
    <div class="skill-level">
        <div class="skill-bar" data-level="85%"></div>
    </div>
</div>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## License

This project is open source and available under the [MIT License](LICENSE).



