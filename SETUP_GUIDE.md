# Setup Guide - How to Upload to GitHub

Follow these simple steps to upload your portfolio to GitHub.

## Step 1: Install Git (if not already installed)

Download and install Git from: https://git-scm.com/download/win

## Step 2: Create a GitHub Account

If you don't have one, create an account at: https://github.com

## Step 3: Create a New Repository on GitHub

1. Go to GitHub and click the "+" icon in the top right
2. Select "New repository"
3. Name it: `5th-sem-portfolio`
4. Keep it **Public** (so it shows in your profile)
5. **Do NOT** initialize with README (we already have one)
6. Click "Create repository"

## Step 4: Upload Your Portfolio

Open PowerShell in the `5th-sem-portfolio` folder and run these commands:

```powershell
# Initialize git repository
git init

# Add all files
git add .

# Create first commit
git commit -m "Initial commit: 5th semester portfolio"

# Add your GitHub repository (replace YOUR-USERNAME)
git remote add origin https://github.com/YOUR-USERNAME/5th-sem-portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Step 5: Update Your Portfolio

After adding new projects, use these commands:

```powershell
git add .
git commit -m "Add new project: [project name]"
git push
```

## Tips

- Replace placeholder text in README files with your actual information
- Add your real GitHub username, email, and LinkedIn in the main README
- Create project folders inside each subject folder as you complete projects
- Keep your README files updated with project descriptions

## Need Help?

- Git documentation: https://git-scm.com/doc
- GitHub guides: https://guides.github.com
