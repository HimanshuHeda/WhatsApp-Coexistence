# GitHub Pages Deployment Instructions

Your WhatsApp Coexistence Setup page is now ready for deployment to GitHub Pages! Follow these steps:

## Prerequisites
- A GitHub account
- Git installed on your computer
- Your project files (already prepared)

## Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., `whatsapp-coexistence` or `octodo-whatsapp-setup`)
4. Make sure it's set to **Public** (required for free GitHub Pages)
5. **Don't** initialize with README, .gitignore, or license (we already have these)
6. Click "Create repository"

## Step 2: Upload Your Files

Navigate to your project folder in terminal/command prompt:

```bash
cd "d:\WhatsApp Coexistence"
```

Initialize Git and add your files:

```bash
git init
git add .
git commit -m "Initial commit: WhatsApp Coexistence Setup page"
```

Connect to your GitHub repository (replace `YOUR_USERNAME` and `YOUR_REPO_NAME`):

```bash
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on the "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "GitHub Actions"
5. The deployment will start automatically

## Step 4: Access Your Live Site

After a few minutes, your site will be available at:
```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
```

## Automatic Deployment

Every time you push changes to the `main` branch, GitHub Actions will automatically redeploy your site.

## Important Notes

⚠️ **HTTPS Required**: Your site will automatically use HTTPS, which is required for the Facebook SDK to work properly.

🔒 **Domain**: Your site will be accessible at `YOUR_USERNAME.github.io/YOUR_REPO_NAME`

🔄 **Updates**: Any changes you make and push to GitHub will automatically update your live site.

## Troubleshooting

If deployment fails:
1. Check the "Actions" tab in your GitHub repository for error logs
2. Ensure your repository is public
3. Make sure the `index.html` file exists in the root directory
4. Wait a few minutes - initial deployment can take time

## Custom Domain (Optional)

If you have your own domain, you can:
1. Add a `CNAME` file with your domain name
2. Configure DNS settings in your domain provider
3. Enable HTTPS in repository settings

Your WhatsApp Coexistence Setup page is now ready for the web! 🚀