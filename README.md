# jknight137.github.io

Personal portfolio website for John Knight - AI & Technology Leader

## 🌐 Live Site

Once deployed, this site will be available at: **https://jknight137.github.io**

## 📋 Overview

This is a professional portfolio website showcasing:
- Professional experience in AI/ML, DevOps, and Platform Engineering
- Technical skills and expertise
- Educational background and certifications
- Publications and thought leadership
- Contact information

## 🚀 Deployment Instructions

### Step 1: Create the GitHub Repository

1. Go to [GitHub](https://github.com) and sign in to your account
2. Click the **"+"** icon in the top right and select **"New repository"**
3. Name the repository: `jknight137.github.io`
   - ⚠️ **Important**: The repository name MUST be exactly `<your-username>.github.io`
4. Set the repository to **Public**
5. **DO NOT** initialize with README, .gitignore, or license (we already have files)
6. Click **"Create repository"**

### Step 2: Initialize and Push Your Code

Open a terminal in the `jknight137.github.io` folder and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit the files
git commit -m "Initial commit: Personal portfolio site"

# Add your GitHub repository as remote (replace with your actual repo URL)
git remote add origin https://github.com/jknight137/jknight137.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** tab
3. In the left sidebar, click **"Pages"**
4. Under **"Source"**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **"Save"**

### Step 4: Wait for Deployment

- GitHub Pages will automatically build and deploy your site
- This usually takes 1-2 minutes
- You'll see a message: **"Your site is published at https://jknight137.github.io"**
- Visit your site at: **https://jknight137.github.io**

## 📁 Project Structure

```
jknight137.github.io/
├── index.html       # Main HTML page with all content
├── styles.css       # CSS styling and responsive design
└── README.md        # This file
```

## 🎨 Features

- **Responsive Design**: Looks great on desktop, tablet, and mobile
- **Modern UI**: Clean, professional design with smooth animations
- **Easy Navigation**: Sticky header with smooth scrolling
- **Performance**: Optimized for fast loading
- **Accessible**: Semantic HTML and proper contrast ratios

## 🔧 Customization

### Updating Content

To update your information, edit `index.html`:

1. **Hero Section**: Lines 28-40 - Your title and tagline
2. **About Section**: Lines 43-65 - Your bio and credentials
3. **Experience**: Lines 68-175 - Your work history
4. **Skills**: Lines 178-235 - Your technical skills
5. **Education**: Lines 238-280 - Degrees and certifications
6. **Publications**: Lines 283-310 - Your books and papers
7. **Contact**: Lines 313-343 - Contact information

### Changing Colors

Edit `styles.css` variables at the top (lines 10-18):

```css
:root {
    --primary-color: #2563eb;     /* Main brand color */
    --secondary-color: #1e40af;   /* Secondary brand color */
    --accent-color: #3b82f6;      /* Accent highlights */
    /* ... other variables ... */
}
```

### Adding a Custom Domain

1. Buy a domain from any registrar (e.g., Namecheap, Google Domains)
2. In your repository settings → Pages → Custom domain
3. Enter your domain (e.g., `johnknight.com`)
4. Follow GitHub's DNS configuration instructions
5. Enable **"Enforce HTTPS"** after DNS propagates

## 🔄 Updating Your Site

After making changes:

```bash
git add .
git commit -m "Update: describe your changes"
git push
```

GitHub Pages will automatically rebuild and deploy your changes in 1-2 minutes.

## 📱 Testing Locally

To test before deploying, open `index.html` directly in your browser or use a local server:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (if you have npx)
npx http-server
```

Then visit: `http://localhost:8000`

## 🛠️ Troubleshooting

### Site not appearing?
- Check repository name is exactly `jknight137.github.io`
- Verify repository is set to Public
- Check Pages settings show source as `main` branch
- Wait 5-10 minutes for initial deployment

### Changes not showing?
- Hard refresh your browser (Ctrl+F5 or Cmd+Shift+R)
- Clear browser cache
- Check GitHub Actions tab for build status

### 404 Error?
- Ensure `index.html` is in the root directory
- Check file names are lowercase
- Verify all files were pushed to GitHub

## 📧 Support

For GitHub Pages issues, see: https://docs.github.com/en/pages

## 📄 License

© 2026 John Knight. All rights reserved.

---

Built with ❤️ using HTML, CSS, and GitHub Pages
