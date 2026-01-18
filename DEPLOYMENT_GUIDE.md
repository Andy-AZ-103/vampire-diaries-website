# How to Deploy Your Vampire Diaries Website

## Option 1: GitHub Pages (Free & Easy)

### Step 1: Create a GitHub Account
1. Go to https://github.com
2. Sign up for a free account

### Step 2: Create a New Repository
1. Click the "+" icon in the top right
2. Select "New repository"
3. Name it (e.g., "vampire-diaries-website")
4. Make it **Public** (required for free GitHub Pages)
5. Click "Create repository"

### Step 3: Upload Your Files
1. Click "uploading an existing file"
2. Drag and drop all your files:
   - `vampire_diaries.html`
   - `characters.html`
   - `elena-gilbert.html`
   - `damon-salvatore.html`
   - `stefan-salvatore.html`
   - `caroline-forbes.html`
   - `bonnie-bennett.html`
   - `jeremy-gilbert.html`
   - `styles.css`
   - `script.js`
   - `images/` folder (with all images)
3. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to your repository settings
2. Scroll to "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Your site will be live at: `https://yourusername.github.io/vampire-diaries-website/`

## Option 2: Netlify (Free & Very Easy)

### Step 1: Prepare Your Files
1. Make sure all your files are in one folder

### Step 2: Deploy
1. Go to https://www.netlify.com
2. Sign up for free
3. Drag and drop your entire website folder onto the Netlify dashboard
4. Your site will be live instantly with a random URL
5. You can customize the URL in site settings

## Option 3: Vercel (Free)

### Step 1: Create Account
1. Go to https://vercel.com
2. Sign up with GitHub

### Step 2: Deploy
1. Click "New Project"
2. Import your GitHub repository (or upload files)
3. Click "Deploy"
4. Your site will be live in seconds

## Option 4: Traditional Web Hosting

### Step 1: Buy a Domain
- Namecheap.com
- GoDaddy.com
- Google Domains

### Step 2: Choose a Host
- Bluehost
- HostGator
- SiteGround

### Step 3: Upload Files
- Use FTP (FileZilla) or cPanel File Manager
- Upload all your files to the `public_html` folder

## Important Notes Before Deploying

1. **Test Locally First**: Open `vampire_diaries.html` in your browser to make sure everything works
2. **Check File Paths**: Make sure all image paths are correct (relative paths work best)
3. **Update Links**: If needed, update any absolute paths to relative paths
4. **Add a README**: Consider adding a README.md file explaining your project

## Quick Checklist

- [ ] All HTML files are in the root directory
- [ ] CSS file (`styles.css`) is linked correctly
- [ ] JavaScript file (`script.js`) is linked correctly
- [ ] Images folder exists with all images
- [ ] All internal links work (test navigation)
- [ ] No broken image links

## Recommended: GitHub Pages

**Why GitHub Pages?**
- Completely free
- Easy to update (just push changes)
- Reliable hosting
- Can add a custom domain later
- Version control built-in

Your website will be accessible to anyone with the URL!
