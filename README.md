# 🚀 Web Developer Portfolio - Bahattin Tok

Modern, responsive, and interactive web developer portfolio. Built with HTML5, CSS3, JavaScript, and Bootstrap. Highlights include an **Animated Orbit Skills section** and **Project Video Player**.

## ✨ Key Features

- **🎯 Orbit Skills Animation**: Technology logos orbit around with smooth motion
- **🎬 Video Player Modals**: Play project demo videos inside modals
- **📱 Responsive Design**: Looks great on all devices
- **🎨 Modern UI/UX**: Gradients, shadows, and modern typography
- **⚡ Smooth Animations**: Powered by AOS (Animate On Scroll)
- **🔗 Project Modals**: Detailed project information via modals
- **📊 Interactive Elements**: Hovers, smooth scrolling, and dynamic content
- **🔍 SEO Optimized**: Semantic HTML structure
- **⚙️ Performance Optimized**: Clean code and lazy loading

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup
- **CSS3**: Modern styling, CSS Grid, Flexbox, Keyframe Animations
- **JavaScript**: ES6+, DOM manipulation, custom animations
- **Bootstrap 5**: Responsive framework

### Libraries & Tools
- **Font Awesome**: Icons
- **Google Fonts**: Poppins, Inter, Lato, Rubik
- **AOS**: Scroll animations
- **Typed.js**: Typing animations

## 📁 Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── style.css               # CSS styles and animations
├── script.js               # JavaScript functions
├── img/                    # Project images
│   ├── main_photo.jpg
│   ├── e-commerce-home.png
│   ├── organic-foodd.png
│   └── weather-app.png
├── videos/                 # Project demo videos
│   ├── e-commerce-demo-video.mp4
│   ├── organic-food-demo-video.mp4
│   └── weather-app-demo-video.mp4
└── README.md               # Project documentation
```

## 🎨 Design Features

### Color Palette
- **Primary**: #007bff (Blue)
- **Secondary**: #6c757d (Gray)
- **Gradient Primary**: Linear-gradient(135deg, #667eea 0%, #764ba2 100%)
- **Dark**: #343a40 (Dark gray)
- **Success**: #28a745 (Green)
- **Warning**: #ffc107 (Yellow)

### Fonts
- **Primary**: Poppins (Headings)
- **Secondary**: Inter (Body)
- **Code**: Courier New (Code blocks)

### Animations
- **Orbit Animation**: Circular motion of technology logos
- **Counter-rotation**: Logos stay upright via reverse spin
- **Fade in/out**: Section transitions
- **Slide animations**: Horizontal slide effects
- **Hover transformations**: Interactive hover effects
- **Typing animation**: Typewriter effect
- **Progress bar animations**: Progress indicators

## 🌟 Special Features

### 1. Orbit Skills Animation
```css
/* Separate orbit animations for Frontend and Backend */
#frontend-orbit-container, #backend-orbit-container {
    animation: spin-right 30s linear infinite;
}

.inner-orbit-circles, .outer-orbit-circles {
    animation: counter-rotate 30s linear infinite;
}

.middle-orbit-circles {
    animation: counter-rotate-reverse 30s linear infinite;
}
```

### 2. Video Player Modals
- Bootstrap modal system
- Auto video pause/play
- Responsive video container
- Multiple video support

### 3. Project Detail Modals
- Detailed project descriptions
- Technology lists
- GitHub and live demo links
- Integrated video player

## 📱 Responsive Breakpoints

- **Mobile**: < 576px
- **Tablet**: 576px – 768px
- **Desktop**: > 768px

## 🚀 Setup

1. Clone the project:
```bash
git clone https://github.com/BT-maker/portfolio.git
cd portfolio
```

2. Serve the files on a web server or simply open `index.html` in your browser.

3. Make necessary updates:
   - Update your personal information
   - Add your projects
   - Update social media links
   - Add your photos

## 📝 Customization

### Update Personal Information

Update these areas in `index.html`:

```html
<!-- Hero Section -->
<h1 class="hero-title">
    Hello, I'm <span class="highlight">Bahattin Tok</span>
</h1>

<!-- About Section -->
<h3 class="about-title">Passionate Web Developer</h3>

<!-- Contact Section -->
<p>your-email@example.com</p>
<p>+90 555 123 4567</p>
```

### Add New Technologies to Orbit

You can add new technologies to the orbit section in `index.html`:

```html
<div class="inner-orbit-circles">
    <i class="fab fa-new-technology"></i>
</div>
```

### Add Projects

Add new project cards to the Projects section:

```html
<div class="col-lg-4 col-md-6 mb-4" data-aos="fade-up" data-aos-delay="400">
    <div class="project-card">
        <div class="project-image">
            <img src="project-image.jpg" alt="Project Name">
            <div class="project-overlay">
                <div class="project-links">
                    <a href="#" class="project-link" data-bs-toggle="modal" data-bs-target="#projectModal">
                        <i class="fas fa-external-link-alt"></i>
                    </a>
                    <a href="#" class="project-link">
                        <i class="fab fa-github"></i>
                    </a>
                </div>
            </div>
        </div>
        <div class="project-content">
            <h4 class="project-title">Project Name</h4>
            <p class="project-description">Project description</p>
            <div class="project-tech">
                <span class="tech-tag">HTML</span>
                <span class="tech-tag">CSS</span>
                <span class="tech-tag">JavaScript</span>
            </div>
        </div>
    </div>
}</div>
```

### Change Colors

Update CSS variables in `style.css`:

```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    --gradient-primary: linear-gradient(135deg, #color1 0%, #color2 100%);
}
```

## 🎯 Feature Details

### 1. Navigation
- Sticky navbar with blur effect
- Smooth scroll navigation
- Active link highlighting
- Mobile responsive hamburger menu

### 2. Hero Section
- Gradient background with grid pattern
- Typing animation for titles
- Code animation block
- Social media links with hover effects
- Call-to-action buttons

### 3. About Section
- Personal information with statistics
- Counter animation for stats
- Downloadable CV button
- Professional photo with frame effect

### 4. Skills Section
- **Static Skills List**: Categorized technology lists
- **Orbit Animation**: Animated technology logos
- **Frontend/Backend Separation**: Two distinct orbit sections
- **Responsive Design**: Mobile-optimized animations

### 5. Projects Section
- Project cards with hover effects
- Image overlays with action buttons
- Technology tags with brand colors
- External links and modal triggers
- **Video Player Integration**: Demo video playback

### 6. Contact Section
- Horizontal contact information layout
- Icon wrappers with gradient backgrounds
- Social media links
- Responsive design

### 7. Additional Features
- Back to top button with smooth scroll
- Scroll progress indicator
- Preloader animation
- Notification system
- Lazy loading for images
- **Central Divider**: Visual separation in skills section

## 🔧 JavaScript Features

- **AOS Animations**: Scroll-based animations
- **Orbit Animation Control**: Custom orbit and counter-rotation
- **Video Player Management**: Modal video control
- **Form Validation**: Email and form validation
- **Smooth Scrolling**: Soft page transitions
- **Counter Animation**: Statistics counters
- **Notification System**: User notifications
- **Parallax Effect**: Hero section parallax
- **Lazy Loading**: Image lazy loading

## 📊 Performance Optimizations

- CSS and JavaScript optimization
- Image optimization and lazy loading
- Debounced scroll events
- Efficient DOM queries
- Animation performance tuning
- **3D Transform Optimization**: Hardware acceleration

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+


## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Create a Pull Request

## 📞 Contact

- **GitHub**: [@BT-maker](https://github.com/BT-maker)

## 🙏 Credits

- [Bootstrap](https://getbootstrap.com/) - CSS Framework
- [Font Awesome](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Typography
- [AOS](https://michalsnik.github.io/aos/) - Scroll Animations

## 🎉 Highlights

- **Orbit Animation**: Perfect synchronization of technology logos
- **Video Integration**: Seamless video player experience
- **Responsive Design**: Excellent performance on all devices
- **Performance**: Optimized animations and smooth interactions

---

⭐ If you like this project, don't forget to star it!

