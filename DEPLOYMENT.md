# Deployment Instructions

## ✅ GitHub Repository Created

Your project is now live on GitHub:
**https://github.com/jg0fox/tone-of-voice-engine**

---

## 🚀 Deploy to Vercel

### Option 1: Deploy via Vercel Dashboard (Recommended)

1. **Visit Vercel**: Go to https://vercel.com/new

2. **Import Git Repository**:
   - Click "Add New..." → "Project"
   - Select "Import Git Repository"
   - Choose "jg0fox/tone-of-voice-engine" from your repositories
   - Click "Import"

3. **Configure Project**:
   - **Framework Preset**: Other (or leave as detected)
   - **Root Directory**: ./
   - **Build Command**: Leave empty (static site)
   - **Output Directory**: Leave empty (static site)

4. **Deploy**:
   - Click "Deploy"
   - Wait 30-60 seconds for deployment to complete
   - You'll get a URL like: `https://tone-of-voice-engine.vercel.app`

### Option 2: Deploy via Vercel CLI (Alternative)

If you want to use the CLI:

```bash
# Install Vercel CLI
npm install -g vercel

# Navigate to project
cd "/Users/jfox/Desktop/Tone tool"

# Login to Vercel
vercel login

# Deploy
vercel --prod
```

---

## 🌐 Custom Domain (Optional)

Once deployed, you can add a custom domain:

1. Go to your project in Vercel dashboard
2. Click "Settings" → "Domains"
3. Add your custom domain
4. Follow DNS configuration instructions

---

## 🔄 Automatic Deployments

Vercel will automatically deploy when you push to GitHub:

- **Production**: Pushes to `main` branch → Production URL
- **Preview**: Pull requests → Preview URLs

To push updates:

```bash
cd "/Users/jfox/Desktop/Tone tool"
git add .
git commit -m "Your update message"
git push
```

---

## 📦 What's Deployed

- **Main Tool**: `/` (redirects to Tone_tool.html)
- **Walkthrough**: `/walkthrough.html`
- **Schema Documentation**: `/standard_schema.md`
- **Examples**: `/Tone_standard_v2_example.md`
- **Changelog**: `/CHANGELOG.md`

---

## ✨ Features

Your deployed tool includes:
- ✅ 5 interactive tone spectrums
- ✅ 4 sub-dimensions per spectrum
- ✅ 50+ linguistic devices with examples
- ✅ Content standard generator (v2.0)
- ✅ Schema viewer with copy functionality
- ✅ Anti-pattern detection
- ✅ Mobile-responsive design
- ✅ No server required (fully static)

---

## 🐛 Troubleshooting

**Issue**: Home page doesn't load
- **Solution**: Check that `vercel.json` is in the repository root

**Issue**: Assets not loading
- **Solution**: Ensure all files are committed and pushed to GitHub

**Issue**: 404 errors
- **Solution**: All HTML files should be accessed with `.html` extension (except root)

---

**GitHub Repository**: https://github.com/jg0fox/tone-of-voice-engine
**Next Step**: Visit https://vercel.com/new to deploy!
