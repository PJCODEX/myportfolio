# 🎨 Customization Guide

This guide will help you customize the portfolio to match your personal brand and preferences.

## 🎯 Quick Customization Checklist

### Essential Changes (Do First!)
- [ ] Update personal information in Hero section
- [ ] Replace profile images with your photos
- [ ] Update About section with your story
- [ ] Add your skills in Skills section
- [ ] Update Experience timeline with your work history
- [ ] Add your projects to Projects section
- [ ] Update Education with your degrees
- [ ] Add your certifications
- [ ] Update contact information
- [ ] Change social media links

### Optional Customizations
- [ ] Change color scheme
- [ ] Modify fonts
- [ ] Add/remove sections
- [ ] Customize animations
- [ ] Add new features

---

## 📝 Content Customization

### 1. Hero Section

**Location:** `index.html` (lines ~50-110)

```html
<!-- Update Your Name -->
<h1 class="hero-name">Your Name</h1>

<!-- Update Roles in JavaScript -->
<!-- File: js/main.js (lines 10-17) -->
const titles = [
    'Your Title 1',
    'Your Title 2',
    'Your Title 3',
    // Add more titles
];

<!-- Update Description -->
<p class="hero-description">
    Your personal introduction and what you do...
</p>

<!-- Update Social Links -->
<a href="https://www.linkedin.com/in/YOUR_USERNAME" target="_blank">
<a href="https://github.com/YOUR_USERNAME" target="_blank">
```

### 2. About Section

**Location:** `index.html` (lines ~120-200)

```html
<!-- Update Your Story -->
<h3>Hi, I'm Your Name</h3>
<p>Your background and interests...</p>

<!-- Update Highlights -->
<div class="highlight-item">
    <i class="fas fa-your-icon"></i>
    <h4>Your Strength</h4>
    <p>Description</p>
</div>

<!-- Update Statistics -->
<div class="stat-item">
    <h4>X+</h4>
    <p>Your Metric</p>
</div>
```

### 3. Skills Section

**Location:** `index.html` (lines ~210-300)

```html
<!-- Add/Remove Skills -->
<div class="skill-item">
    <i class="fab fa-technology-icon"></i>
    <span>Technology Name</span>
</div>

<!-- For learning skills, add "learning" class -->
<div class="skill-item learning">
    <i class="fas fa-icon"></i>
    <span>Skill Name</span>
</div>
```

**Available Icon Classes:**
- `fab fa-html5` - HTML5
- `fab fa-css3-alt` - CSS3
- `fab fa-js` - JavaScript
- `fab fa-react` - React
- `fab fa-node-js` - Node.js
- `fab fa-python` - Python
- `fab fa-java` - Java
- `fas fa-database` - Database
- Find more at: [fontawesome.com/icons](https://fontawesome.com/icons)

### 4. Experience Section

**Location:** `index.html` (lines ~310-450)

```html
<!-- Add New Experience -->
<div class="timeline-item">
    <div class="timeline-content">
        <div class="timeline-icon">
            <img src="company-logo-url" alt="Company">
        </div>
        <div class="timeline-info">
            <span class="timeline-date">Start Date - End Date</span>
            <h3>Your Position</h3>
            <h4>Company Name</h4>
            <p>Description of your role and achievements...</p>
            <ul>
                <li><strong>Project:</strong> Details</li>
            </ul>
            <div class="tech-tags">
                <span class="tech-tag">Technology</span>
            </div>
        </div>
    </div>
</div>
```

### 5. Projects Section

**Location:** `index.html` (lines ~460-650)

```html
<!-- Add New Project -->
<div class="project-card">
    <div class="project-image">
        <img src="project-screenshot-url" alt="Project Name">
        <div class="project-overlay">
            <div class="project-links">
                <a href="live-demo-url" class="project-link">
                    <i class="fas fa-external-link-alt"></i>
                </a>
                <a href="github-url" class="project-link">
                    <i class="fab fa-github"></i>
                </a>
            </div>
        </div>
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-tags">
            <span class="tag">Technology</span>
        </div>
    </div>
</div>
```

**Free Project Images:**
- [Unsplash](https://unsplash.com) - High-quality free images
- [Pexels](https://pexels.com) - Free stock photos
- Take screenshots of your actual projects

### 6. Education Section

**Location:** `index.html` (lines ~660-750)

```html
<!-- Add Education -->
<div class="education-card">
    <div class="education-icon">
        <i class="fas fa-graduation-cap"></i>
    </div>
    <div class="education-info">
        <h3>Degree Name</h3>
        <h4>Institution Name</h4>
        <p class="education-field">Field of Study</p>
        <p class="education-date">Start Date - End Date</p>
        <p class="education-grade">GPA: X.XX</p>
    </div>
</div>
```

### 7. Certifications

**Location:** `index.html` (lines ~760-850)

```html
<!-- Add Certification -->
<div class="cert-card">
    <div class="cert-icon">
        <i class="fas fa-certificate"></i>
    </div>
    <h4>Certification Name</h4>
    <p>Issuing Organization</p>
    <span class="cert-date">Issue Date</span>
</div>
```

### 8. Contact Information

**Location:** `index.html` (lines ~860-950)

```html
<!-- Update Location -->
<div class="contact-item">
    <i class="fas fa-map-marker-alt"></i>
    <div>
        <h4>Location</h4>
        <p>Your City, State, Country</p>
    </div>
</div>

<!-- Update Email (if you add it) -->
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h4>Email</h4>
        <p>your.email@example.com</p>
    </div>
</div>
```

---

## 🎨 Visual Customization

### 1. Color Scheme

**Location:** `css/style.css` (lines 1-20)

```css
:root {
    /* Primary Colors - Change these! */
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #8b5cf6;    /* Secondary brand color */
    --accent-color: #ec4899;       /* Accent/highlight color */
    
    /* Background Colors */
    --dark-bg: #0f172a;            /* Main background */
    --dark-secondary: #1e293b;     /* Section backgrounds */
    --dark-tertiary: #334155;      /* Card backgrounds */
    
    /* Text Colors */
    --light-text: #f8fafc;         /* Primary text */
    --gray-text: #cbd5e1;          /* Secondary text */
    
    /* Other Colors */
    --success-color: #10b981;      /* Success messages */
}
```

**Popular Color Schemes:**

```css
/* Blue Professional */
--primary-color: #2563eb;
--secondary-color: #3b82f6;
--accent-color: #60a5fa;

/* Green Tech */
--primary-color: #059669;
--secondary-color: #10b981;
--accent-color: #34d399;

/* Orange Creative */
--primary-color: #ea580c;
--secondary-color: #f97316;
--accent-color: #fb923c;

/* Purple Modern */
--primary-color: #7c3aed;
--secondary-color: #8b5cf6;
--accent-color: #a78bfa;

/* Pink Vibrant */
--primary-color: #db2777;
--secondary-color: #ec4899;
--accent-color: #f472b6;
```

**Color Tools:**
- [Coolors.co](https://coolors.co) - Color scheme generator
- [Adobe Color](https://color.adobe.com) - Color wheel
- [ColorHunt](https://colorhunt.co) - Color palettes

### 2. Typography

**Location:** `index.html` (lines 10-12)

```html
<!-- Change Fonts -->
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

**Update CSS:** `css/style.css` (lines 18-19)

```css
:root {
    --font-primary: 'Your Font', sans-serif;
    --font-display: 'Display Font', serif;
}
```

**Recommended Google Fonts:**
- **Sans-Serif:**
  - Inter
  - Montserrat
  - Raleway
  - Space Grotesk
  - Work Sans
  
- **Serif:**
  - Playfair Display (current)
  - Merriweather
  - Lora
  - Crimson Text

**Font Pairing Resources:**
- [FontPair](https://fontpair.co)
- [Google Fonts](https://fonts.google.com)

### 3. Gradient Customization

**Location:** `css/style.css`

```css
/* Custom Gradients */
--gradient-1: linear-gradient(135deg, #color1 0%, #color2 100%);
--gradient-2: linear-gradient(135deg, #color3 0%, #color4 100%);
--gradient-primary: linear-gradient(135deg, var(--primary-color) 0%, var(--secondary-color) 100%);

/* Radial Gradients */
background: radial-gradient(circle, #color1 0%, #color2 70%);

/* Animated Gradients */
background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
background-size: 400% 400%;
animation: gradient 15s ease infinite;
```

### 4. Image Customization

**Replace Profile Images:**

1. **Prepare Your Images:**
   - Size: 400x400px to 800x800px
   - Format: JPG or PNG
   - Optimize: Use [TinyPNG](https://tinypng.com)

2. **Update Image URLs:**
   ```html
   <!-- Hero Section -->
   <img src="path/to/your/photo.jpg" alt="Your Name">
   
   <!-- About Section -->
   <img src="path/to/your/photo.jpg" alt="Your Name">
   ```

3. **Image Hosting Options:**
   - In project folder: `images/profile.jpg`
   - GitHub: Use raw GitHub URL
   - Imgur: Free image hosting
   - Cloudinary: Professional hosting

---

## ⚙️ Feature Customization

### 1. Add New Section

**Steps:**

1. **Add HTML Structure:**
   ```html
   <section id="your-section" class="your-section section">
       <div class="container">
           <div class="section-header">
               <h2 class="section-title">Section Title</h2>
               <p class="section-subtitle">Section subtitle</p>
           </div>
           <!-- Your content here -->
       </div>
   </section>
   ```

2. **Add Navigation Link:**
   ```html
   <li><a href="#your-section" class="nav-link">Section Name</a></li>
   ```

3. **Add CSS Styling:**
   ```css
   .your-section {
       background: var(--dark-secondary);
       /* Your styles */
   }
   ```

### 2. Modify Animations

**Location:** `css/style.css`

```css
/* Change Animation Speed */
transition: all 0.5s ease; /* Change 0.5s to your preference */

/* Disable Animations */
* {
    animation: none !important;
    transition: none !important;
}

/* Custom Animation */
@keyframes yourAnimation {
    from {
        /* Start state */
    }
    to {
        /* End state */
    }
}

.element {
    animation: yourAnimation 2s ease infinite;
}
```

### 3. Modify Typing Effect

**Location:** `js/main.js` (lines 10-17)

```javascript
// Add/Edit Titles
const titles = [
    'Your Title 1',
    'Your Title 2',
    'Your Title 3',
];

// Change Speed
let typingSpeed = 100; // Milliseconds per character
```

### 4. Contact Form Integration

**For Real Email Functionality:**

**Option 1: Formspree (Easiest)**
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <!-- Keep existing form fields -->
</form>
```

**Option 2: Netlify Forms (if hosting on Netlify)**
```html
<form name="contact" method="POST" data-netlify="true">
    <!-- Keep existing form fields -->
</form>
```

**Option 3: EmailJS**
- Sign up at [emailjs.com](https://emailjs.com)
- Get your API keys
- Add EmailJS script and configure

---

## 🎭 Advanced Customization

### 1. Add Dark/Light Theme Toggle

Add this JavaScript:
```javascript
// Toggle theme
function toggleTheme() {
    document.body.classList.toggle('light-theme');
    localStorage.setItem('theme', 
        document.body.classList.contains('light-theme') ? 'light' : 'dark'
    );
}

// Load saved theme
if (localStorage.getItem('theme') === 'light') {
    document.body.classList.add('light-theme');
}
```

Add CSS for light theme:
```css
body.light-theme {
    --dark-bg: #ffffff;
    --dark-secondary: #f8fafc;
    --dark-tertiary: #e2e8f0;
    --light-text: #0f172a;
    --gray-text: #475569;
}
```

### 2. Add Loading Screen

```html
<!-- Add before closing </body> -->
<div class="loader">
    <div class="spinner"></div>
</div>

<script>
window.addEventListener('load', () => {
    document.querySelector('.loader').style.display = 'none';
});
</script>
```

### 3. Add Particle Background

Use [particles.js](https://vincentgarreau.com/particles.js/):
```html
<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
```

---

## 🧪 Testing Your Changes

### 1. Browser Testing
- Chrome DevTools (F12)
- Firefox Developer Tools
- Safari Web Inspector

### 2. Responsive Testing
- Chrome Device Mode (Ctrl+Shift+M)
- Responsively App
- Real devices

### 3. Performance Testing
- Lighthouse (in Chrome DevTools)
- PageSpeed Insights
- GTmetrix

---

## 💾 Save Your Changes

```bash
# After making changes
git add .
git commit -m "Customize: description of changes"
git push origin main
```

---

## 🆘 Need Help?

- 📧 Check browser console for errors (F12)
- 🔍 Search for CSS properties on [MDN Web Docs](https://developer.mozilla.org)
- 💬 Ask on [Stack Overflow](https://stackoverflow.com)
- 📚 Review [W3Schools](https://w3schools.com) tutorials

---

**Happy Customizing! Make it yours! 🎨✨**