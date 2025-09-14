# Cletus Mangu - Cloud Computing Portfolio

A responsive portfolio website showcasing cloud computing skills and professional development journey. Built with modern web technologies and deployed on Netlify.

##  Live Demo

**[View Live Site](https://cletus-mangu-portfolio.netlify.app)**

---

##  Project Structure

```
portfolio-website/
├── index.html          # Main HTML file with semantic structure
├── style.css           # Custom CSS with responsive design
├── cletus.jpg          # Professional profile image
└── README.md           # Project documentation
```

---

##  Features

### Core Functionality
- **Responsive Design**: Mobile-first approach using CSS Grid and Flexbox
- **Interactive Elements**: JavaScript-powered skill cards with click events
- **Professional Layout**: Clean, minimalistic design with consistent color scheme
- **Semantic HTML**: Accessible markup following web standards

### Technical Implementation
- **CSS Grid Layout**: Modern layout system for responsive sections
- **Custom CSS Variables**: Consistent theming and easy maintenance
- **Vanilla JavaScript**: No external dependencies for lightweight performance
- **Cross-browser Compatibility**: Tested on modern browsers

---

##  Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic markup and structure |
| **CSS3** | Styling, responsive design, animations |
| **JavaScript (ES6)** | Interactive functionality |
| **Netlify** | Hosting and continuous deployment |

---

##  Quick Start

### Prerequisites
- Modern web browser
- Text editor (VS Code recommended)
- Git installed on your system

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mangucletus/portfolio-website-McTech.git
   ```

2. **Navigate to project directory**
   ```bash
   cd portfolio-website
   ```

3. **Open in browser**
   ```bash
   # Option 1: Direct file opening
   open index.html
   
   # Option 2: Using Python HTTP server
   python3 -m http.server 8000
   # Then visit http://localhost:8000
   ```

---

##  Responsive Breakpoints

| Device | Breakpoint | Layout |
|--------|------------|---------|
| Mobile | `< 768px` | Single column, stacked sections |
| Tablet | `768px - 1024px` | Two-column grid for skills |
| Desktop | `> 1024px` | Multi-column layout with sidebar |

---

##  Color Palette

```css
:root {
  --primary-blue: #2a5298;
  --accent-orange: #ff6b35;
  --background-light: #f8f9fa;
  --text-dark: #333333;
  --border-light: #e9ecef;
}
```

---

##  Sections

### 1. Header
- Professional profile image
- Name and title
- Contact information

### 2. About Me
- Professional summary
- Career objectives
- Personal interests

### 3. Skills
- Technical skills with interactive cards
- Cloud computing competencies
- Development tools proficiency

### 4. Projects (Future)
- Portfolio projects showcase
- GitHub integration
- Live demo links

---

##  Customization

### Adding New Skills
```html
<div class="skill-card">
    <h3>New Skill</h3>
    <p>Description of your proficiency</p>
</div>
```

### Updating Profile Information
Edit the following in `index.html`:
- Personal information in the header section
- About me content in the main section
- Contact details in the footer

### Modifying Styles
Key CSS classes to customize:
- `.skill-card` - Individual skill styling
- `.container` - Main layout container
- `header` - Top section styling

---

##  Performance Metrics

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **Load Time**: < 2 seconds on 3G connection
- **Bundle Size**: < 50KB total (HTML, CSS, JS, images)

---

##  Deployment

### Netlify Deployment (Recommended)

1. **Connect to Netlify**
   - Link GitHub repository to Netlify
   - Configure build settings (if needed)

2. **Automatic Deployment**
   ```bash
   # Any push to main branch triggers deployment
   git add .
   git commit -m "Update portfolio content"
   git push origin main
   ```

### Alternative Hosting Options
- **GitHub Pages**: Enable in repository settings
- **Vercel**: Import repository directly
- **Firebase Hosting**: Use Firebase CLI

