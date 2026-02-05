# Invoice Generator

A beautiful, modern invoice generator web application built with vanilla HTML, CSS, and JavaScript.

## Features

- 📝 Create professional invoices with a live preview
- 🎨 Modern dark theme UI
- 📄 Download invoices as PDF
- 🖼️ Upload company logos
- 💰 Calculate totals with tax support
- 📱 Fully responsive design

## Deploy to Vercel

### Option 1: Deploy via Vercel CLI (Recommended)

1. **Install Vercel CLI** (if you haven't already):
   ```bash
   npm i -g vercel
   ```

2. **Login to Vercel**:
   ```bash
   vercel login
   ```

3. **Deploy your project**:
   ```bash
   vercel
   ```
   
   Follow the prompts:
   - Set up and deploy? **Yes**
   - Which scope? Select your account
   - Link to existing project? **No** (for first deployment)
   - Project name? Enter a name or press Enter for default
   - Directory? Press Enter (current directory)
   - Override settings? **No**

4. **Deploy to production**:
   ```bash
   vercel --prod
   ```

### Option 2: Deploy via GitHub

1. **Create a GitHub repository**:
   - Go to [GitHub](https://github.com) and create a new repository
   - Push your code to GitHub:
     ```bash
     git init
     git add .
     git commit -m "Initial commit"
     git branch -M main
     git remote add origin <your-github-repo-url>
     git push -u origin main
     ```

2. **Deploy on Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "Add New Project"
   - Import your GitHub repository
   - Vercel will automatically detect it's a static site
   - Click "Deploy"

### Option 3: Drag and Drop

1. Go to [vercel.com](https://vercel.com)
2. Sign in or create an account
3. Drag and drop your project folder onto the Vercel dashboard
4. Vercel will automatically deploy it

## Project Structure

```
invoice/
├── index.html      # Main application file
├── vercel.json     # Vercel configuration
└── README.md       # This file
```

## Notes

- The `index.html` file serves as the entry point for your application
- Vercel will automatically serve static files
- No build process is required - it's ready to deploy as-is!

## Custom Domain

After deployment, you can add a custom domain in your Vercel project settings.

https://geniv.vercel.app/
