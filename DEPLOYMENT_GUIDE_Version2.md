# 🚀 Deployment Guide - AASRA Laundry

## Option 1: GitHub Pages (FREE & EASY)

### Step 1: Create Repository
1. Go to https://github.com/new
2. Name: `aasra-laundry`
3. Description: `Professional Hotel Linen Solutions - Quotation & Bill Generator`
4. Choose Public or Private
5. Click "Create repository"

### Step 2: Upload Files
1. In your repository, click "Add file" → "Upload files"
2. Upload these files:
   - `index.html`
   - `img1.png` (your logo)
   - `README.md`
   - `.gitignore`

### Step 3: Enable GitHub Pages
1. Go to Settings → Pages
2. Source: Deploy from a branch
3. Branch: `main`
4. Folder: `/ (root)`
5. Click "Save"

### Step 4: Access Your App
- Wait 1-2 minutes for deployment
- Access at: `https://deka19.github.io/aasra-laundry/`

---

## Option 2: Netlify (Alternative)

### Step 1: Connect GitHub
1. Go to https://netlify.com
2. Click "New site from Git"
3. Choose GitHub
4. Select `aasra-laundry` repository

### Step 2: Configure
- Build command: (leave empty)
- Publish directory: `/`
- Click "Deploy"

### Step 3: Access
- Get your Netlify URL
- Customize domain if desired

---

## Option 3: Vercel (Alternative)

### Step 1: Import Repository
1. Go to https://vercel.com
2. Click "New Project"
3. Import your GitHub repository

### Step 2: Deploy
- Framework: Other (Static)
- Click "Deploy"

---

## Option 4: Local Testing

### With Python (Python 3+)
```bash
cd aasra-laundry
python -m http.server 8000
# Open http://localhost:8000
```

### With Node.js
```bash
npx http-server
# Open http://localhost:8080
```

### With PHP
```bash
cd aasra-laundry
php -S localhost:8000
# Open http://localhost:8000
```

---

## Custom Domain Setup

### For GitHub Pages
1. Go to Settings → Pages
2. Under "Custom domain", enter your domain
3. Update DNS records at your domain provider:
   ```
   CNAME record: your-domain.com → deka19.github.io
   ```
4. Wait for DNS propagation (5-30 minutes)

---

## Domain Examples

- `aasralaundry.com`
- `quotes.aasralaundry.com`
- `billing.aasralaundry.com`

---

## Troubleshooting

### Images Not Loading
- Ensure `img1.png` is in the same directory as `index.html`
- Check file name capitalization (Linux/Mac are case-sensitive)

### GitHub Pages Not Publishing
- Check repository is Public
- Ensure `index.html` is in the root directory
- Wait 2-5 minutes for initial deployment

### PDF Download Not Working
- Try a different browser (Chrome recommended)
- Ensure JavaScript is enabled
- Check browser's print dialog appears

---

## Updates & Maintenance

### Update Pricing
1. Edit `index.html`
2. Modify `ITEMS` array
3. Commit and push to GitHub
4. Changes live in 1-2 minutes

### Update Logo
1. Replace `img1.png` with new file
2. Commit and push
3. Hard refresh browser (Ctrl+Shift+R)

---

## Monitoring

### GitHub Analytics
- Go to repository "Insights"
- View traffic and clone counts

### Browser Console
- No errors should appear in DevTools
- Check Network tab for 404s

---

## Security Checklist

✅ No external API calls  
✅ No database connections  
✅ All processing client-side  
✅ No user data stored  
✅ No tracking scripts  
✅ HTTPS enabled (automatic on GitHub Pages)

---

## Support

Contact: venturestechno@gmail.com
Phone: +91 95314 68479
