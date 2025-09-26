# Sanyam's Professional Portfolio Website

A clean, modern, and responsive portfolio website for Research Scholar specializing in Computational Molecular Design of Highly Efficient OLEDs.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Fast Loading**: Optimized CSS and JavaScript for quick load times
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Print Friendly**: Optimized for printing/PDF generation
- **Accessibility**: Follows web accessibility guidelines

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
├── script.js           # Interactive functionality
├── README.md           # This file
└── placeholder-photo.jpg # Your profile photo (to be added)
```

## 🚀 How to Deploy to GitHub Pages

### Method 1: Direct Upload to GitHub

1. **Create a GitHub Repository**
   - Go to [GitHub.com](https://github.com) and sign in
   - Click "New" repository
   - Name it `your-username.github.io` (replace with your GitHub username)
   - Make it Public
   - Click "Create repository"

2. **Upload Your Files**
   - Click "uploading an existing file"
   - Drag and drop all files: `index.html`, `styles.css`, `script.js`
   - Add your profile photo as `placeholder-photo.jpg`
   - Commit changes

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll down to "Pages" section
   - Source: "Deploy from a branch"
   - Branch: "main" or "master"
   - Folder: "/ (root)"
   - Click "Save"

4. **Access Your Website**
   - Your site will be available at: `https://your-username.github.io`
   - It may take a few minutes to go live

### Method 2: Using Git (Command Line)

```bash
# Clone your repository
git clone https://github.com/your-username/your-username.github.io.git
cd your-username.github.io

# Copy your portfolio files
cp /path/to/portfolio/* .

# Add and commit
git add .
git commit -m "Add portfolio website"
git push origin main
```

## 📸 Adding Your Profile Photo

1. **Prepare Your Photo**
   - Use a high-quality, professional photo
   - Recommended size: 500x500 pixels or larger
   - Formats: JPG, PNG, or WebP
   - Square aspect ratio works best

2. **Add the Photo**
   - Name your photo file: `placeholder-photo.jpg`
   - Upload it to the same folder as your HTML file
   - The website will automatically display it

3. **Alternative: Use Different Filename**
   - If you want to use a different filename, edit `index.html`
   - Find `<img src="placeholder-photo.jpg"` and change the filename

## 🎨 Customization

### Colors
To change the color scheme, modify these CSS variables in `styles.css`:

```css
:root {
  --primary-color: #1e40af;    /* Main blue color */
  --primary-dark: #1e3a8a;     /* Darker blue for hover effects */
  --text-primary: #1e293b;     /* Dark text */
  --text-secondary: #475569;   /* Medium text */
  --text-light: #64748b;       /* Light text */
  --background: #ffffff;       /* White background */
  --background-alt: #f8fafc;   /* Light gray background */
}
```

### Content
- Edit `index.html` to update your information
- All content is clearly organized in sections
- Update contact information, education, publications, etc.

### Styling
- Modify `styles.css` for design changes
- The CSS is well-organized with comments
- Responsive design breakpoints are clearly marked

## 📱 Sections Included

1. **Navigation Bar** - Smooth scrolling navigation
2. **Hero Section** - Profile photo, name, title, and call-to-action buttons
3. **About Me** - Research interests and current focus
4. **Education** - Timeline of academic achievements
5. **Research & Achievements** - Fellowships, awards, and conferences
6. **Publications** - List of research publications
7. **Technical Skills** - Categorized skill sets
8. **Contact** - Email, phone, and institutional information
9. **Footer** - Copyright and professional summary

## 🔧 Technical Features

- **Smooth Scrolling**: Navigation links smoothly scroll to sections
- **Mobile Menu**: Hamburger menu for mobile devices
- **Scroll Animations**: Elements animate as you scroll
- **Active Navigation**: Current section highlighted in navigation
- **Scroll-to-Top Button**: Quick return to top of page
- **Print Optimization**: Clean printing/PDF generation
- **Loading Animations**: Typing effect for name in hero section

## 🌐 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📊 Performance

- **Fast Loading**: Optimized CSS and JavaScript
- **Lightweight**: No heavy frameworks or libraries
- **CDN Resources**: Fonts and icons loaded from CDN
- **Responsive Images**: Optimized for different screen sizes

## 🔒 Privacy & Security

- No tracking scripts
- No external dependencies except fonts and icons
- All code is static HTML/CSS/JavaScript
- Contact information displayed as per your preference

## 📝 License

This portfolio template is free to use and modify for personal and professional purposes.

## 💡 Tips for Success

1. **Keep Content Updated**: Regularly update your publications and achievements
2. **Professional Photo**: Use a high-quality, professional headshot
3. **Mobile Testing**: Always test on mobile devices
4. **Fast Loading**: Optimize images for web use
5. **SEO**: Update meta descriptions and titles as needed
6. **Backup**: Keep a backup of your files

## 🚨 Troubleshooting

**Photo Not Showing?**
- Check filename matches exactly: `placeholder-photo.jpg`
- Ensure photo is in the same folder as `index.html`
- Try refreshing the browser cache

**Site Not Loading on GitHub Pages?**
- Wait 5-10 minutes after initial deployment
- Check that repository is public
- Verify GitHub Pages settings in repository

**Mobile Menu Not Working?**
- Ensure `script.js` is loaded properly
- Check browser console for JavaScript errors

## 📧 Support

If you need help with deployment or customization, feel free to reach out!

---

**Ready to deploy? Follow the deployment steps above and your professional portfolio will be live in minutes!**
