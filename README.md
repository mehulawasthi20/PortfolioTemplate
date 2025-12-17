# Professional Portfolio Website Template

A clean, modern, and professional portfolio website template perfect for software engineers, developers, and tech professionals. Features smooth animations, and a mobile-responsive design.

## ✨ Features

- 🎨 **Modern Black & White Design** - Sleek, professional aesthetic.
- 📱 **Fully Responsive** - Looks great on all devices (mobile, tablet, desktop).
- 🚀 **Full-Screen Hero Section** - Makes a strong first impression.
- ⚡ **Smooth Animations** - Hover effects and transitions throughout.
- 🎯 **Easy to Customize** - Simple HTML structure, no build tools required.
- 🔤 **Roboto Font** - Clean, professional typography.
- 📊 **Skills Grid Layout** - Organized display of your technical skills.
- 📅 **Timeline Experience Section** - Visual representation of your career progression.
- 🌐 **Single File** - Everything in one `index.html` file for easy deployment.

## 🎯 Perfect For

- Software Engineers.
- Web Developers.
- Data Scientists.
- Product Managers.
- Tech Professionals seeking new opportunities.

## 🚀 Quick Start

### 1. Download the Template
- Download `index.html` from this repository
- Save it to your computer

### 2. Customize Your Content
Open `index.html` in any text editor and replace the placeholder content:

#### **Header Section** (Lines ~73-83)
```html
<h1>Your Name</h1>
<p class="subtitle">Professional Title | Industry Expert</p>
```
Replace "Your Name" with your actual name and update your professional title.

#### **About Section** (Lines ~95-100)
Replace the three paragraphs with your own professional summary. Focus on:
- Your experience and expertise.
- Key achievements and impact.
- What drives you professionally.

#### **Skills Section** (Lines ~104-137)
Update each skill card with your actual skills:
```html
<div class="skill-card">
    <h3>Programming Languages</h3>
    <p>Java, Python, SQL, C#</p>
</div>
```
You can add or remove skill cards as needed.

#### **Experience Section** (Lines ~141-186)
For each job, update:
- Job title: `<h3>Your Job Title</h3>`
- Company and location: `<div class="company">Company Name - Location</div>`
- Dates: `<div class="date">Month Year - Month Year</div>`
- Description and bullet points

**To add more jobs:** Copy an entire `<div class="experience-item">...</div>` block and paste it within the timeline.

**To remove a job:** Delete the entire `<div class="experience-item">...</div>` block.

#### **Contact Section** (Lines ~190-198)
Update your social media links:
```html
<a href="https://linkedin.com/in/yourprofile" class="contact-btn">LinkedIn</a>
<a href="https://github.com/yourprofile" class="contact-btn">GitHub</a>
```

### 3. Preview Locally
- Double-click `index.html` to open it in your web browser.
- Check that all your information displays correctly.
- Test the navigation links and buttons.

### 4. Deploy Your Site

#### **Option A: Netlify (Recommended - Easiest)**
1. Go to [netlify.com](https://www.netlify.com).
2. Sign up for a free account.
3. Drag and drop your `index.html` file onto the Netlify dashboard.
4. Your site is live instantly at `your-site-name.netlify.app`.
5. Customize your site name in Settings → Site details.

#### **Option B: GitHub Pages**
1. Create a GitHub account.
2. Create a new repository named `yourusername.github.io`.
3. Upload `index.html` to the repository.
4. Go to Settings → Pages.
5. Your site will be live at `https://yourusername.github.io`.

#### **Option C: Vercel**
1. Go to [vercel.com](https://vercel.com).
2. Sign up for free.
3. Import your project or drag and drop your file.
4. Deploy instantly.

## 📝 Customization Guide

### Changing Colors

The template uses a black and gray color scheme. To change colors, find and replace these color codes in the CSS section:

- **Primary Black:** `#000000` - Used for headers, buttons, and accents.
- **Dark Gray:** `#2d3748` - Used for gradients and secondary elements.
- **Background:** `#f8f9fa` - Light gray background.

**Example:** To change to blue, replace `#000000` with `#1e40af` (dark blue)

### Changing Fonts

The template uses the Roboto font. To change it:

1. Find this line in the `<head>` section:
```html
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
```

2. Replace with your desired Google Font. Visit [Google Fonts](https://fonts.google.com/) to browse options.

3. Update the font-family in CSS:
```css
body {
    font-family: 'Your-Font-Name', sans-serif;
}
```

### Adding More Sections

To add a new section (like Projects, Certifications, etc.):

1. Add a navigation link:
```html
<li><a href="#newsection">New Section</a></li>
```

2. Add the section content before the Contact section:
```html
<section id="newsection">
    <h2>New Section Title</h2>
    <div class="about-content">
        <p>Your content here...</p>
    </div>
</section>
```

### Removing Sections

To remove a section:
1. Delete the navigation link from the `<nav>` section
2. Delete the entire `<section>...</section>` block

## 🎨 Design Elements

### Navigation Bar
- Sticky navigation that stays at the top while scrolling.
- Smooth scroll-to-section functionality.
- Hover effects on all links.

### Skills Grid
- Auto-responsive grid layout.
- Cards adjust to fit different screen sizes.
- Hover effects for interactivity.

### Experience Timeline
- Visual timeline with connecting line.
- Chronological display of your career.
- Expandable content areas.

### Contact Section
- Clean call-to-action.
- Social media links.
- Professional contact options.

## 🤝 Contributing

Found a bug or have a suggestion? Feel free to:
- Open an issue.
- Submit a pull request.
- Share your improvements.

## 🌟 Showcase

Built something awesome with this template? Share it! I'd love to see how you've customized it.
---

## ✅ Quick Checklist Before Deploying

- [ ] Replaced "Your Name" with your actual name.
- [ ] Updated professional title.
- [ ] Customized About Me section.
- [ ] Added all your skills.
- [ ] Updated work experience with real companies and dates.
- [ ] Updated LinkedIn and GitHub links.
- [ ] Tested all navigation links.
- [ ] Previewed on mobile device (or browser mobile view).
- [ ] Proofread all content for typos.
- [ ] Tested site in browser before deploying.

---