# 🎨 Professional Portfolio Website - Bakr Sassi

A modern, responsive, and visually stunning portfolio website for showcasing your skills, projects, and achievements as a Business Computing student.

## 📋 Features

✨ **Modern Design**
- Clean, professional gradient-based color scheme
- Smooth animations and transitions
- Fully responsive (mobile, tablet, desktop)
- Interactive UI elements with hover effects

🎯 **Complete Sections**
1. **Hero/Cover** - Professional introduction with contact info
2. **Profile/About** - Compelling summary of skills and ambitions
3. **Skills** - Categorized technical skills, soft skills, and languages
4. **Projects** - 4 detailed project showcases with results
5. **Education** - Academic degrees and certifications
6. **Achievements** - Awards, volunteering, and side projects
7. **Contact** - Multiple ways to connect with you

## 🚀 How to Use

### Quick Start
1. Open `index.html` in any modern web browser
2. Navigate through sections using the top navigation bar
3. All links are functional and ready to use

### Customization Guide

#### 1. Personal Information (Already Set)
- ✅ Name: Bakr Sassi
- ✅ Email: SassiBakr@outlook.com
- ✅ Phone: +216 28 202 093
- ✅ LinkedIn: https://www.linkedin.com/in/bakrsassi/
- ✅ GitHub: https://github.com/SassiBakr

#### 2. Profile Section
Edit lines 48-64 in `index.html` to customize your profile text.

#### 3. Skills Section
- **Technical Skills** (lines 94-143): Update skill names and adjust progress bars
  - Change the `style="width: XX%"` to match your proficiency
- **Soft Skills** (lines 154-199): Modify descriptions to match your strengths
- **Languages** (lines 214-266): Adjust circle progress by changing `stroke-dashoffset`
  - Native (100%): offset = 0
  - Fluent (90%): offset = 32.7
  - Professional (80%): offset = 65.4

#### 4. Projects Section
Each project has placeholders for screenshots. Replace the visual placeholders:
```html
<div class="visual-placeholder">
    <!-- Replace with: -->
    <img src="path/to/your/screenshot.png" alt="Project Name" style="width: 100%; height: 100%; object-fit: cover; border-radius: 20px;">
</div>
```

Update project details (lines 284-532):
- Title, tags, context, role, technologies, and results
- Add your actual project information

#### 5. Education Section (lines 565-651)
**ACTION REQUIRED:** Fill in the bracketed placeholders:
- `[University Name]` - Your university
- `[Your GPA]` - Your current GPA or academic standing
- `[High School Name]` - Your high school
- `[Year]` - Certification years
- `[Platform Name]` - Course platforms (Coursera, Udemy, etc.)

#### 6. Achievements Section (lines 672-776)
Customize awards, volunteering experiences, and side projects.
Replace example content with your actual achievements.

#### 7. Download CV Button
Add your CV file:
1. Create a PDF of your CV named `Bakr_Sassi_CV.pdf`
2. Place it in the same folder as `index.html`
3. Update line 850 in `index.html`:
```html
<a href="Bakr_Sassi_CV.pdf" download class="btn btn-secondary">
```

## 🎨 Adding Screenshots & Images

### Project Screenshots
1. Take screenshots of your actual projects
2. Save them in a new `images` folder
3. Replace placeholders in HTML:
```html
<div class="project-visual">
    <img src="images/project1.png" alt="Customer Analytics Dashboard" style="width: 100%; border-radius: 20px;">
</div>
```

### Recommended Image Sizes
- Project screenshots: 800x600px or 16:9 ratio
- Keep file sizes under 500KB for fast loading
- Use .jpg for photos, .png for UI screenshots

## 🎯 Visual Enhancements You Can Add

### 1. Charts & Diagrams
- Add actual Power BI dashboard screenshots
- Include database schema diagrams
- Show data visualization examples

### 2. Canva Integration
To use in Canva:
1. Take screenshots of each section
2. Import into Canva as images
3. Use Canva to add:
   - Additional decorative elements
   - Custom icons
   - Brand-specific colors

### 3. PowerPoint Export
To convert to PowerPoint:
1. Open the website in Chrome
2. Right-click → Print → Save as PDF
3. Import PDF into PowerPoint
4. Split sections into individual slides
5. Add animations and transitions in PowerPoint

## 🌈 Color Scheme

The portfolio uses a professional gradient-based palette:
- **Primary**: Blue gradient (#667eea → #764ba2)
- **Secondary**: Blue (#2563eb → #3b82f6)
- **Accent**: Various complementary gradients
- **Text**: Dark slate (#1e293b) and light gray (#64748b)

### Changing Colors
Edit CSS variables in `styles.css` (lines 5-15):
```css
:root {
    --primary-color: #2563eb;  /* Change to your brand color */
    --secondary-color: #1e40af;
    /* ... */
}
```

## 📱 Responsive Design

The portfolio is fully responsive and tested on:
- ✅ Desktop (1920px+)
- ✅ Laptop (1366px - 1920px)
- ✅ Tablet (768px - 1024px)
- ✅ Mobile (320px - 767px)

## 🔧 Technical Stack

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with flexbox/grid
- **JavaScript** - Smooth animations and interactions
- **Font Awesome** - Professional icons

## 🚀 Deployment Options

### 1. GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Select main branch → Save
5. Your site will be live at `username.github.io/repo-name`

### 2. Netlify (Free)
1. Drag and drop your folder on netlify.com
2. Get instant live URL
3. Custom domain available

### 3. Vercel (Free)
1. Import from GitHub
2. Auto-deploy on updates

## ✅ Pre-Launch Checklist

Before sharing your portfolio:
- [ ] Replace all `[placeholder]` text in Education section
- [ ] Add your actual project screenshots
- [ ] Update project descriptions with your real projects
- [ ] Upload your CV PDF file
- [ ] Test all links (LinkedIn, GitHub, Email)
- [ ] Test on mobile device
- [ ] Check for typos and grammar
- [ ] Add your actual achievements
- [ ] Verify all contact information

## 📊 Analytics (Optional)

Add Google Analytics to track visitors:
1. Sign up at analytics.google.com
2. Get your tracking ID
3. Add before `</head>` in `index.html`:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-ID');
</script>
```

## 🎓 Tips for Recruiters

This portfolio is designed to:
- ✨ Make a strong first impression
- 📊 Showcase quantifiable results
- 💼 Demonstrate technical and soft skills
- 🎯 Highlight problem-solving abilities
- 🚀 Show continuous learning mindset

## 📞 Support

If you need to make modifications:
1. Edit `index.html` for content
2. Edit `styles.css` for design
3. Edit `script.js` for functionality

## 📝 License

This portfolio is created for personal use. Feel free to customize it completely!

---

**Created with passion and precision by Bakr Sassi** 🚀
*Ready to impress recruiters and land your dream role!*
