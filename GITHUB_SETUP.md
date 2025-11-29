# GitHub Pages Setup Instructions

## Step 1: Create a GitHub Repository

1. Go to https://github.com/new
2. Repository name: `personal-website` (or any name you prefer)
3. Description: "Personal website and resume"
4. Choose **Public** (required for free GitHub Pages)
5. **DO NOT** initialize with README, .gitignore, or license (we already have these)
6. Click "Create repository"

## Step 2: Push Your Code to GitHub

Open PowerShell or Command Prompt in the `personal-website` folder and run:

```powershell
# Navigate to your project folder
cd C:\Users\jjarb\personal-website

# Add all files
git add .

# Commit the files
git commit -m "Initial commit: Personal website with resume"

# Add your GitHub repository as remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/personal-website.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**Note:** Replace `YOUR_USERNAME` with your actual GitHub username (jjarbrough).

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub: `https://github.com/jjarbrough/personal-website`
2. Click on **Settings** (top menu)
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait a few minutes for GitHub to build your site
7. Your website will be available at: `https://jjarbrough.github.io/personal-website/`

## Optional: Custom Domain

If you want to use a custom domain later, you can add it in the Pages settings.




