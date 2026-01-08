# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- ✨ Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Smooth animations and transitions
- 🚀 Fast loading and optimized
- ♿ Accessible navigation
- 📧 Contact form ready for integration

## Sections

1. **Hero Section** - Introduction with your name and professional title
2. **About** - Personal background and story
3. **Skills** - Technical skills organized by category
4. **Experience** - Work experience timeline
5. **Projects** - Portfolio of your projects
6. **Contact** - Contact information and form

## Getting Started

1. Open `index.html` in your web browser
2. Customize the content with your information (see Customization section below)
3. Deploy to your preferred hosting platform

## Customization Guide

### 1. Personal Information

**In `index.html`, update:**

- **Hero Section** (around line 30-40):
  - Replace "Your Name" with your actual name
  - Update "Your Professional Title / Role"
  - Write your introduction paragraph

- **Social Links** (around line 45):
  - Update the `href` attributes with your actual social media URLs
  - Remove any social links you don't use

- **About Section** (around line 70):
  - Replace placeholder text with your actual bio

### 2. Skills

**In `index.html`, update the Skills section** (around line 85):
- Modify the skill categories (Programming Languages, Frameworks, etc.)
- Update skill tags with your actual skills
- Add or remove skill categories as needed

### 3. Experience

**In `index.html`, update the Experience section** (around line 110):
- Replace each timeline item with your actual work experience:
  - Job Title
  - Company Name
  - Date range
  - Responsibilities/achievements (bullet points)
- Add or remove timeline items as needed

### 4. Projects

**In `index.html`, update the Projects section** (around line 140):
- For each project card:
  - Update project name
  - Write project description
  - Update technology tags
  - Add links to GitHub repository and live demo
- Duplicate project cards for additional projects

### 5. Contact Information

**In `index.html`, update the Contact section** (around line 200):
- Update email address
- Update phone number (or remove if not needed)
- Update location
- Customize the contact form message

### 6. Styling (Optional)

**In `styles.css`, you can customize:**

- **Colors** (in `:root` section at the top):
  - `--primary-color`: Main brand color
  - `--secondary-color`: Secondary accent color
  - Adjust other color variables as needed

- **Fonts**: Currently using Inter font from Google Fonts
- **Spacing**: Adjust padding and margins as needed

### 7. Footer

**In `index.html`, update the Footer** (around line 250):
- Update copyright year and name
- Update social media links

## Adding Your Resume

To add your resume:

1. Convert your resume to PDF
2. Save it as `resume.pdf` in the project folder
3. Add a download link in the Hero section or About section:

```html
<a href="resume.pdf" download class="btn btn-secondary">Download Resume</a>
```

## Contact Form Integration

The contact form currently shows an alert when submitted. To make it functional:

1. **Option 1: Use a form service** (e.g., Formspree, Netlify Forms)
   - Sign up for a form service
   - Update the form action URL
   - Update the JavaScript fetch URL

2. **Option 2: Backend integration**
   - Set up a backend API endpoint
   - Update the JavaScript fetch URL in `script.js`

Example with Formspree:
```javascript
fetch('https://formspree.io/f/YOUR_FORM_ID', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json',
    },
    body: JSON.stringify({ name, email, message })
})
```

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your branch and folder
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to Netlify
2. Or connect your GitHub repository
3. Your site will be live instantly

### Vercel
1. Import your GitHub repository
2. Deploy with default settings
3. Your site will be live instantly

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Feel free to use this template for your personal portfolio!

## Need Help?

If you need help customizing your portfolio, feel free to:
- Check the HTML comments in `index.html`
- Review the CSS variables in `styles.css`
- Modify the JavaScript in `script.js` for additional functionality

---

**Note:** Remember to replace all placeholder content with your actual information before deploying!

