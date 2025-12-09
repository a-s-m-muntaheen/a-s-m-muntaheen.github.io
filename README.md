# Portfolio Website

A modern, responsive portfolio website template.

## Customization Guide

### 1. Replace Placeholders
Open `index.html` and replace these placeholders:

- `[YOUR NAME]` → Your full name
- `[YOUR PROFESSION]` → Your job title
- `[YOUR-GITHUB]` → Your GitHub username
- `[YOUR-LINKEDIN]` → Your LinkedIn username
- `[YOUR-TWITTER]` → Your Twitter username
- `[YOUR-EMAIL]` → Your email address
- `[YOUR LOCATION]` → Your city/country
- `[YOUR CITY, COUNTRY]` → Your location for contact section

### 2. Add Your Profile Photo
1. Add your photo as `profile.jpg` in the `assets/` folder
2. Make sure it's square (1:1 ratio) for best results

### 3. Update Projects
In `index.html`, update the project cards with:
- Your actual project names and descriptions
- Real GitHub repository links
- Live demo links (if available)
- Correct technologies used

### 4. Customize Colors
In `style.css`, modify these variables at the top:
- `--primary-color` → Main accent color
- `--dark-color` → Background color
- Other colors as needed

## Deployment Instructions

### Option 1: Deploy to GitHub Pages (Free)

1. **Create GitHub Repository**
   - Go to [GitHub](https://github.com)
   - Click "+" → "New repository"
   - Name: `yourusername.github.io` (replace with your GitHub username)
   - Set to Public
   - Click "Create repository"

2. **Upload Files**
   ```bash
   # Initialize git
   git init
   git add .
   git commit -m "Initial portfolio commit"
   
   # Connect to GitHub
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git branch -M main
   git push -u origin main