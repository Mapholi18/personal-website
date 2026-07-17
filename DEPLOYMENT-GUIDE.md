# 🚀 Complete Deployment Guide

## Quick Start (Choose One Option)

### ✨ GitHub Pages (FREE, RECOMMENDED)
**Easiest option - your site will be live in 2 minutes**

1. Go to your repository: https://github.com/Mapholi18/personal-website
2. Click **Settings** (top right)
3. Scroll to **Pages** section (left sidebar)
4. Under "Source", select `main` branch
5. Click **Save**
6. Your site is now live at: **https://Mapholi18.github.io/personal-website/**

✅ Done! No additional setup needed.

---

### ⚡ Vercel (FREE, FASTEST)
**Automatic deployments, custom domains, best performance**

1. Go to https://vercel.com
2. Click **"Sign Up"** (or login if you have account)
3. Sign in with GitHub
4. Click **"Import Project"**
5. Select your `personal-website` repository
6. Click **"Deploy"**
7. Your site is live! You get a free `.vercel.app` domain

Optional: Add custom domain in Vercel dashboard

---

### 🌐 Netlify (FREE, EASY)
**Simple drag-and-drop, global CDN**

1. Go to https://netlify.com
2. Click **"Sign up"**
3. Choose **"Sign up with GitHub"**
4. Click **"New site from Git"**
5. Select your `personal-website` repository
6. Click **"Deploy"**
7. Your site is live at a Netlify domain

Optional: Connect custom domain

---

## Step-by-Step: GitHub Pages (Recommended)

### Prerequisites
- Your repository created and files pushed
- GitHub account

### Setup Instructions

**Step 1: Access Repository Settings**
```
1. Go to https://github.com/Mapholi18/personal-website
2. Click "Settings" tab at top
```

**Step 2: Navigate to Pages**
```
1. In left sidebar, click "Pages"
2. Look for "Build and deployment" section
```

**Step 3: Configure Source**
```
1. Under "Source", select "Deploy from a branch"
2. Select branch: "main"
3. Select folder: "/ (root)"
4. Click "Save"
```

**Step 4: Wait for Deployment**
```
- GitHub will automatically deploy your site
- This takes 1-2 minutes
- You'll see a link when complete
```

**Step 5: Access Your Site**
```
Your website is now live at:
https://Mapholi18.github.io/personal-website/
```

---

## Custom Domain Setup (Optional)

### For GitHub Pages

**Using GitHub Pages Custom Domain:**

1. Go to repository **Settings > Pages**
2. Under "Custom domain", enter your domain (e.g., `maryjanemapholi.com`)
3. Click **Save**
4. Update your domain's DNS settings:
   - Go to your domain registrar (GoDaddy, Namecheap, etc.)
   - Add CNAME record pointing to `Mapholi18.github.io`
   - Or use GitHub's provided IP addresses
5. Wait 24 hours for DNS propagation

**Where to Buy Domains:**
- Namecheap.com (cheap and reliable)
- GoDaddy.com (popular)
- Google Domains
- AWS Route 53

---

## Update Your Files

Your website is automatically updated when you push changes to GitHub:

```bash
# Make changes to your files
# Then commit and push:

git add .
git commit -m "Update website"
git push origin main
```

Changes appear on your live site within 2-5 minutes!

---

## File Structure

Make sure your repository has this structure:

```
personal-website/
├── index.html          ✓ Main page
├── styles.css          ✓ Styling
├── script.js           ✓ Interactivity
├── resume.html         ✓ Resume builder
├── README.md           ✓ Documentation
├── PROJECT-IDEAS.md    ✓ Project suggestions
├── SKILLS-DEVELOPMENT.md  ✓ Career roadmap
├── DEPLOYMENT-GUIDE.md    ✓ This file
├── .gitignore          ✓ Git configuration
└── assets/             (Create this folder)
    └── (your CV file when ready)
```

---

## Verify Your Deployment

### Check if your site is live:

1. **GitHub Pages**: https://Mapholi18.github.io/personal-website/
2. **Vercel**: Check your Vercel dashboard for URL
3. **Netlify**: Check your Netlify dashboard for URL

### Test on Different Devices

Visit your deployed site on:
- Desktop browser
- Tablet
- Mobile phone
- Different browsers (Chrome, Firefox, Safari, Edge)

### Check for Issues

- [ ] All images load correctly
- [ ] Navigation works smoothly
- [ ] Mobile menu appears on small screens
- [ ] Contact form works
- [ ] Links are clickable
- [ ] No console errors (F12 > Console tab)

---

## Troubleshooting

### Site not appearing?

**GitHub Pages:**
1. Check Settings > Pages
2. Verify source is set to "main" branch
3. Wait 2-5 minutes
4. Hard refresh (Ctrl+Shift+R)
5. Check for error messages in Actions tab

**Vercel:**
1. Check Vercel dashboard for build errors
2. Verify GitHub account is connected
3. Re-deploy by pushing a commit

**Netlify:**
1. Check Netlify dashboard > Deploys
2. Look for build errors
3. Ensure all files are in repository

### CSS/JavaScript not loading?

1. Check file paths are correct
2. Verify files are in repository root
3. Check browser console for 404 errors
4. Hard refresh your browser (Ctrl+Shift+R)

### Images not showing?

1. Use relative paths: `./images/photo.jpg`
2. Not absolute paths: `/images/photo.jpg`
3. Check file actually exists in repository

---

## Performance Optimization

### To make your site faster:

1. **Compress images**
   - Use TinyPNG.com
   - Reduces file size significantly

2. **Minify CSS/JavaScript**
   - Use MinifyCode.com
   - Reduces load time

3. **Enable caching**
   - Already enabled by default on Vercel/Netlify

4. **Use CDN** (Content Delivery Network)
   - Vercel and Netlify use automatic CDN
   - Ensures fast loading worldwide

---

## Adding Resume/CV PDF

### Steps:

1. **Create your CV as PDF**
   - Use resume.html to print as PDF
   - Or create in Word/Google Docs and export
   - Name it: `Mary-Jane-Mapholi-CV.pdf`

2. **Add to repository**
   - Create `assets` folder
   - Upload PDF to assets folder
   - Push to GitHub

3. **Update HTML link**
   - In `index.html`, update:
   ```html
   <a href="./assets/Mary-Jane-Mapholi-CV.pdf" download class="btn btn-secondary">Download CV</a>
   ```

---

## Monitoring Your Site

### Analytics (Optional but Recommended)

Add Google Analytics to track visitors:

1. Go to https://analytics.google.com
2. Click "Start measuring"
3. Enter your website URL
4. Copy the tracking code
5. Paste in `<head>` of index.html

This shows:
- Number of visitors
- Where they come from
- Which pages they visit
- Time spent on site

---

## SSL Certificate (HTTPS)

✅ **Already included!**
- GitHub Pages: Automatic HTTPS
- Vercel: Automatic HTTPS
- Netlify: Automatic HTTPS

Your site uses secure connection (🔒 in browser)

---

## SEO Optimization

To improve search engine visibility:

### Update Meta Tags in `index.html`

```html
<meta name="description" content="Mary-Jane Mapholi - AI Specialist and Recent Graduate">
<meta name="keywords" content="AI, portfolio, graduate, technology">
<meta name="author" content="Mary-Jane Mapholi">
```

### Submit to Search Engines

1. **Google**
   - Go to Google Search Console
   - Add your website
   - Submit sitemap

2. **Bing**
   - Go to Bing Webmaster Tools
   - Submit your website

---

## Maintenance Checklist

### Monthly
- [ ] Check analytics
- [ ] Update content if needed
- [ ] Test all links work
- [ ] Check for broken images

### Quarterly
- [ ] Add new projects
- [ ] Update skills section
- [ ] Refresh certifications
- [ ] Update CV

### Annually
- [ ] Redesign if needed
- [ ] Update layout
- [ ] Review and update all content
- [ ] Check dependencies

---

## Next Steps After Deployment

1. ✅ Share your site on LinkedIn
   - Post link in your profile
   - Share in headline

2. ✅ Share on social media
   - Twitter/X
   - Facebook
   - WhatsApp
   - Instagram

3. ✅ Email to contacts
   - Recruiters
   - Friends
   - Family

4. ✅ Add to job applications
   - Include link in CV
   - Mention in cover letters
   - Add to LinkedIn

---

## Resources

- **GitHub Pages Help**: https://docs.github.com/en/pages
- **Vercel Documentation**: https://vercel.com/docs
- **Netlify Documentation**: https://docs.netlify.com
- **Domain Registrars**: Namecheap, GoDaddy
- **DNS Help**: mxtoolbox.com

---

## Support

If you need help:

1. **GitHub Issues**: Create an issue in your repository
2. **Stack Overflow**: Ask questions with relevant tags
3. **Community Forums**: r/webdev, Dev.to
4. **Documentation**: Official docs of platform you choose

---

## Congratulations! 🎉

Your professional website is now live and accessible to the world!

**Next:** Start building projects and updating your portfolio to showcase your skills!

---

**Last Updated:** 2025
**Status:** ✅ Ready for Deployment
