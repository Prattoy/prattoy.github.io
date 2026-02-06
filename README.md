# Portfolio Website - Prattoy Majumder

A modern, responsive portfolio website showcasing my experience, projects, and publications.

## 🚀 Quick Start

### Prerequisites
- A GitHub account
- Git installed on your computer

### Deployment Steps

#### Step 1: Create GitHub Repository
1. Go to [GitHub](https://github.com)
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name it: `your-username.github.io` (replace `your-username` with your actual GitHub username)
    - Example: If your username is `prattoy`, name it `prattoy.github.io`
5. Make it **Public**
6. Click "Create repository"

#### Step 2: Clone and Upload Files

**Option A: Using Git Command Line**

```bash
# Clone the repository
git clone https://github.com/your-username/your-username.github.io.git
cd your-username.github.io

# Copy all website files (index.html, style.css, script.js) to this folder

# Add files to git
git add .

# Commit changes
git commit -m "Initial portfolio website"

# Push to GitHub
git push origin main
```

**Option B: Using GitHub Web Interface**

1. Go to your repository page
2. Click "Add file" → "Upload files"
3. Drag and drop all files (index.html, style.css, script.js)
4. Click "Commit changes"

#### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" (gear icon)
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait 2-5 minutes for deployment

#### Step 4: Access Your Website
Your website will be live at: `https://your-username.github.io`

## 📝 Customization

### Update Your Information

Open `index.html` and update:

1. **Social Links** (Line ~30-32):
```html
<a href="https://linkedin.com/in/YOUR-PROFILE" target="_blank">
<a href="https://github.com/YOUR-GITHUB" target="_blank">
<a href="https://scholar.google.com/YOUR-PROFILE" target="_blank">
```

2. **Project Links**: Add your actual GitHub project URLs in the "View Project" links

3. **Publication Links**: Add your paper URLs in the "Read Paper" links

4. **Email & Phone** (Line ~250-260): Already set from your CV, but you can update if needed

### Add Custom Domain (Optional)

1. Buy a domain (e.g., from Namecheap, GoDaddy)
2. In your repository, create a file named `CNAME`
3. Add your domain name: `www.yourname.com`
4. Configure DNS settings at your domain provider:
    - Type: CNAME
    - Name: www
    - Value: your-username.github.io

## 🎨 Color Customization

Edit `style.css` and modify the CSS variables:

```css
:root {
    --primary-color: #2563eb;    /* Main blue color */
    --secondary-color: #1e40af;  /* Dark blue */
    --accent-color: #3b82f6;     /* Light blue */
}
```

## 📱 Features

- ✅ Fully Responsive (Mobile, Tablet, Desktop)
- ✅ Smooth Scrolling Navigation
- ✅ Animated Sections
- ✅ Modern Design
- ✅ SEO Friendly
- ✅ Fast Loading
- ✅ Contact Form
- ✅ Mobile Menu

## 🛠️ Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Font Awesome Icons

## 📧 Contact Form Setup

The current form shows an alert. To make it functional:

**Option 1: Use Formspree (Free)**
1. Go to [Formspree](https://formspree.io/)
2. Sign up and create a form
3. Replace the form in `index.html`:
```html
<form action="https://formspree.io/f/YOUR-FORM-ID" method="POST">
```

**Option 2: Use EmailJS (Free)**
1. Go to [EmailJS](https://www.emailjs.com/)
2. Follow their setup guide
3. Add their JavaScript library and configuration

## 🔧 Troubleshooting

**Website not showing?**
- Wait 5-10 minutes after pushing to GitHub
- Check that repository is public
- Verify GitHub Pages is enabled
- Clear browser cache (Ctrl+Shift+R)

**Changes not appearing?**
- Wait a few minutes for GitHub Pages to rebuild
- Hard refresh (Ctrl+Shift+R)
- Check you pushed to the correct branch (main)

**Mobile menu not working?**
- Make sure `script.js` is properly linked
- Check browser console for errors (F12)

## 📸 Screenshots

Your portfolio includes:
- Hero section with introduction
- About section with education and skills
- Experience timeline
- Projects showcase
- Publications list
- Contact section

## 🚀 Performance Tips

- Images: Optimize before uploading (use WebP format)
- Keep file sizes small
- Test on mobile devices
- Use browser developer tools to check responsiveness

## 📄 License

Feel free to use this template for your own portfolio!

## ✨ Credits

Created by Prattoy Majumder