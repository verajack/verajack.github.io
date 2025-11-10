# Portfolio Website

A modern, responsive portfolio website to showcase your skills and experience to potential employers.

## 🚀 Quick Setup for GitHub Pages

### Step 1: Customize Your Content

1. **Add Your Photo**
   - Replace `profile-photo.jpg` with your actual photo file
   - In `styles.css`, uncomment these lines (around line 220):
   ```css
   .profile-photo {
       display: block;
   }
   .photo-placeholder {
       display: none;
   }
   ```

2. **Update Personal Information in `index.html`**
   - Replace "Your Name" with your actual name
   - Update the email address in the contact section
   - Add your GitHub and LinkedIn URLs
   - Customize the about section with your story
   - Update experience and timeline with your actual work history
   - Modify project descriptions to match your real projects

3. **Customize Skills**
   - Edit the skills section to reflect your actual technical skills
   - Add or remove skill categories as needed

### Step 2: Deploy to GitHub Pages

1. **Create a new GitHub repository**
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   ```

2. **Push to GitHub**
   ```bash
   git remote add origin https://github.com/yourusername/yourusername.github.io
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository settings
   - Scroll to "Pages" section
   - Select "main" branch as source
   - Your site will be live at `https://yourusername.github.io`

### Alternative: Use a custom repository name

If you don't want to use `yourusername.github.io`:
- Name your repo anything (e.g., `portfolio`)
- Your site will be at `https://yourusername.github.io/portfolio`

## 📝 Customization Tips

### Colors
Edit CSS variables in `styles.css` (lines 9-20) to change the color scheme:
```css
--primary-color: #2563eb;  /* Main accent color */
--secondary-color: #3b82f6;
--accent-color: #60a5fa;
```

### Sections
- Feel free to remove sections you don't need
- Reorder sections by moving the HTML blocks
- Add new sections following the same pattern

### Projects
- Link to your actual GitHub repositories
- Add live demo links if available
- Update tags to match the technologies used

## 🎨 Features

- ✅ Fully responsive design
- ✅ Modern, clean interface
- ✅ Smooth scrolling navigation
- ✅ Professional yet casual tone
- ✅ Ready for GitHub Pages
- ✅ No build process required
- ✅ Fast loading

## 📱 Mobile Friendly

The website is fully responsive and looks great on all devices - desktop, tablet, and mobile.

## 🔧 No Dependencies

Pure HTML and CSS - no frameworks or build tools needed. Just upload and go!

## 📄 License

This template is free to use for your personal portfolio.
