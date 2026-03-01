# Roby Ajith - Portfolio Website

A modern, responsive portfolio website showcasing professional experience, skills, and projects.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Clean and professional design with smooth animations
- **Easy Navigation**: Smooth scrolling and intuitive navigation menu
- **Sections**:
  - Hero section with introduction
  - About section with professional summary
  - Experience timeline
  - Skills showcase
  - Projects portfolio
  - Contact information

## Customization Guide

### 1. Update Personal Information

Open `index.html` and replace the placeholder content:

- **Hero Section**: Update your name, title, and description
- **About Section**: Add your professional summary and update statistics
- **Experience Section**: Fill in your work history with:
  - Job titles
  - Company names
  - Dates
  - Key responsibilities and achievements
- **Skills Section**: Add your specific skills in the three categories:
  - Technical Skills
  - Tools & Technologies
  - Soft Skills
- **Projects Section**: Add your projects with:
  - Project names
  - Descriptions
  - Technologies used
- **Contact Section**: Update your contact information:
  - Email (already set to roby.ajith@gmail.com)
  - LinkedIn (already set to your profile)
  - Phone number

### 2. Customize Colors

Open `styles.css` and modify the CSS variables in the `:root` section:

```css
:root {
    --primary-color: #3b82f6;      /* Main brand color */
    --secondary-color: #1e40af;    /* Secondary brand color */
    --accent-color: #8b5cf6;       /* Accent color */
    /* ... other colors */
}
```

### 3. Add Project Images

Replace the placeholder project images:
1. Add your project images to the `Roby` folder
2. Update the `.project-image` divs in `index.html` to use your images:
   ```html
   <div class="project-image" style="background-image: url('your-image.jpg');"></div>
   ```

### 4. Update Resume Link

The "Download Resume" button is already linked to your PDF file. Make sure `Roby Ajith Resume.pdf` is in the same folder.

## File Structure

```
Roby/
├── index.html           # Main HTML file
├── styles.css           # All styling
├── script.js            # Interactive features
├── README.md            # This file
└── Roby Ajith Resume.pdf  # Your resume
```

## How to Use

1. Open `index.html` in a web browser to view your portfolio
2. Customize the content as described above
3. Deploy to a web hosting service when ready (GitHub Pages, Netlify, Vercel, etc.)

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Deployment Options

### GitHub Pages
1. Create a GitHub repository
2. Upload all files
3. Enable GitHub Pages in repository settings

### Netlify
1. Drag and drop the `Roby` folder to Netlify
2. Your site will be live instantly

### Vercel
1. Import your project
2. Deploy with one click

## Tips

- Keep content concise and impactful
- Use high-quality images for projects
- Update regularly with new projects and skills
- Test on multiple devices before deploying
- Ensure all links work correctly

## Need Help?

If you need to add more sections or customize further, feel free to modify the HTML, CSS, and JavaScript files. The code is well-commented and organized for easy customization.
