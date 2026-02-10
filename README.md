# Reggie Casanova-Perez Personal Website

A clean, colorful, and professional personal academic website showcasing your research, projects, and publications.

## 🎨 Design Philosophy

This website embodies "simple but colorful" — a clean white background with strategic pops of vibrant color that reflect your personality and the political nature of your research. The color palette uses gradients of purple, pink, teal, and indigo to create a modern, welcoming aesthetic.

## 📁 File Structure

```
your-website/
├── index.html          # Main website file
├── images/
│   └── reggie-profile.jpg    # Your profile photo
└── README.md          # This file
```

## 🚀 Getting Started

### Option 1: Quick Preview
1. Double-click `index.html` to open it in your default browser
2. You'll see the website with all sections

### Option 2: Deploy to GitHub Pages (Recommended)
1. Create a new repository on GitHub (e.g., `reggiecp.github.io`)
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select "main" branch as source
5. Your site will be live at `https://reggiecp.github.io`

### Option 3: Deploy to Your Domain (reggiecp.info)
1. Upload files to your web hosting provider via FTP or their control panel
2. Place all files in your public_html or www directory
3. Your site will be live at `https://www.reggiecp.info`

## ✨ Features

### Sections Included:
- **Hero/About**: Introduction with photo and pronouns
- **Research Frameworks**: Four key theoretical/methodological approaches
- **Projects**: UnBIASED, CLAD, and Dissertation Research
- **Publications**: Selected key papers with proper attribution
- **Experience**: Education and work history
- **Connect**: Contact information and social links

### Design Features:
- Smooth scrolling navigation
- Responsive design (works on phones, tablets, desktops)
- Color-coded sections for visual interest
- Gradient text effects
- Hover animations
- Fixed navigation header
- Clean, modern typography using Inter font

## 🎨 Customization Guide

### Updating Social Links
Find the social links sections and update the URLs as needed:

```html
<!-- Hero section -->
<a href="https://www.linkedin.com/in/recasanova/" target="_blank">in</a>
<a href="https://scholar.google.com/citations?user=yLPHD20AAAAJ&hl=es" target="_blank">📚</a>

<!-- Connect section -->
<div class="connect-card">
    <h3>Email</h3>
    <p>reggiecp [ at ] uw [dot] edu</p>
</div>
```

### Changing Colors
The color scheme is defined at the top of the CSS (lines 18-24):

```css
:root {
    --primary-color: #6366f1;      /* Purple */
    --secondary-color: #ec4899;    /* Pink */
    --accent-teal: #14b8a6;        /* Teal */
    --accent-purple: #a855f7;      /* Light Purple */
}
```

You can replace these hex codes with any colors you prefer!

### Adding More Publications
Copy this template in the Publications section:

```html
<div class="pub-card">
    <div class="pub-title">Paper Title Here</div>
    <div class="pub-authors">
        Authors here (<strong>R Casanova-Perez</strong> for your name)
    </div>
    <div class="pub-venue">
        Conference or Journal Name, Year
    </div>
</div>
```

### Adding New Projects
Copy this template in the Projects section:

```html
<div class="project-card">
    <h3>Project Name</h3>
    <p class="project-role">Your Role | Dates</p>
    <p>Project description here</p>
    <ul class="project-highlights">
        <li>Key contribution 1</li>
        <li>Key contribution 2</li>
        <li>Key contribution 3</li>
    </ul>
</div>
```

### Changing Your Photo
1. Replace `images/reggie-profile.jpg` with your preferred photo
2. Keep the same filename, or update line ~311 in the HTML:
   ```html
   <img src="images/YOUR_NEW_PHOTO.jpg" alt="Description">
   ```

### Updating Text Content
All text can be edited directly in the HTML file. Look for the relevant section and update the content between the tags.

## 🎯 What Makes This Website Special

1. **Identity-Centered**: Your pronouns are prominently displayed, and the language emphasizes your identity as a queer, trans Latino researcher

2. **Research Frameworks**: The four framework cards highlight your theoretical approaches (intersectionality, feminist/queer theory, HCD, CBPR) — similar to the "research pillars" concept you liked

3. **Political Context**: The language explicitly states your research is "deeply political" and "motivated by lived experience"

4. **Visual Hierarchy**: Color-coded projects and clear sections make it easy for visitors to find what they're looking for

5. **Professional Polish**: Clean design that would work for academic job applications, conference bios, or networking

## 📱 Responsive Design

The website automatically adapts to different screen sizes:
- **Desktop**: Two-column hero layout with side-by-side content
- **Tablet**: Slightly condensed with adjusted spacing
- **Mobile**: Single-column layout with hidden navigation menu

## 🔧 Technical Details

- **No Dependencies**: Pure HTML, CSS, and vanilla JavaScript — no frameworks needed
- **Fast Loading**: Minimal external resources (only Google Fonts)
- **SEO-Friendly**: Proper HTML5 semantic structure
- **Accessible**: Good color contrast and semantic markup

## 💡 Tips for Success

1. **Keep It Updated**: Regularly add new publications and projects
2. **Optimize Images**: Compress your photos for faster loading (aim for under 500KB)
3. **Test Links**: Regularly check that all your social and publication links work
4. **Get Feedback**: Share with colleagues and ask for their impressions
5. **Analytics**: Consider adding Google Analytics to see who visits

## 🆘 Need Help?

If you want to make changes but aren't sure how:
1. The HTML file has comments to help you locate different sections
2. Colors are all defined in the CSS variables at the top
3. Each section has a clear structure you can copy/modify
4. Feel free to reach out if you need assistance!

## 🎉 You're All Set!

Your website is ready to showcase your important work at the intersection of health informatics, equity, and social justice. Good luck with your research and your job market! 🌈✨
