# 🚀 Deployment Guide for Vercel

## Quick Start (3 Steps to Deploy)

### Method 1: Deploy with Vercel CLI (Recommended)

1. **Install Vercel CLI**
```bash
npm install -g vercel
```

2. **Navigate to your project**
```bash
cd podcast-dashboard
```

3. **Deploy!**
```bash
vercel
```

That's it! Follow the prompts and your dashboard will be live in seconds.

---

## Method 2: Deploy via GitHub + Vercel Dashboard

### Step 1: Push to GitHub

1. Create a new repository on GitHub
2. Initialize git in your project:
```bash
cd podcast-dashboard
git init
git add .
git commit -m "Initial commit: First Love Church Podcast Dashboard"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

### Step 2: Connect to Vercel

1. Go to [vercel.com](https://vercel.com) and sign up/login
2. Click "Add New Project"
3. Import your GitHub repository
4. Vercel will auto-detect Next.js settings
5. Click "Deploy"

Your dashboard will be live at: `https://your-project-name.vercel.app`

---

## Method 3: Quick Preview with HTML Version

If you just want to see the dashboard immediately without any setup:

1. Open the `preview.html` file in any web browser
2. That's it! No installation needed.

Note: This is a static preview with hardcoded data. For the full dynamic dashboard, use Method 1 or 2.

---

## Environment Setup

### Prerequisites
- Node.js 18+ ([Download here](https://nodejs.org/))
- npm (comes with Node.js)
- Git ([Download here](https://git-scm.com/))

### Local Development

1. **Install dependencies**
```bash
cd podcast-dashboard
npm install
```

2. **Run development server**
```bash
npm run dev
```

3. **Open in browser**
Navigate to [http://localhost:3000](http://localhost:3000)

### Build for Production

```bash
npm run build
```

This creates an optimized static export in the `out` directory.

---

## Vercel Configuration

The project includes optimal Vercel configuration:

### `vercel.json`
```json
{
  "buildCommand": "next build",
  "outputDirectory": "out",
  "framework": "nextjs",
  "regions": ["iad1"]
}
```

### `next.config.js`
```javascript
const nextConfig = {
  output: 'export',  // Static export for optimal performance
  images: {
    unoptimized: true,
  },
}
```

---

## Custom Domain Setup

### After deploying to Vercel:

1. Go to your project dashboard on Vercel
2. Click "Settings" → "Domains"
3. Add your custom domain (e.g., `analytics.firstlovecenter.com`)
4. Update your DNS settings as instructed by Vercel
5. Wait for SSL certificate to be provisioned (automatic)

---

## Updating Data

To update the dashboard with new data:

1. Replace the CSV files in `public/data/`:
   - `Country-stats_2024-12-01_to_2025-11-30.csv`
   - `downloads-stats-2024-12-01_2025-11-30.csv`
   - `Platforms-stats_2024-12-01_to_2025-11-30.csv`

2. If using Git + Vercel:
```bash
git add public/data/
git commit -m "Update dashboard data"
git push
```
Vercel will automatically redeploy!

3. If using Vercel CLI:
```bash
vercel --prod
```

---

## Performance Features

✅ **Static Export** - Pre-rendered at build time for instant loading
✅ **Optimized Assets** - Automatic compression and optimization
✅ **Global CDN** - Content served from the nearest edge location
✅ **Automatic HTTPS** - SSL certificate included
✅ **Zero Configuration** - Works out of the box

---

## Troubleshooting

### Build fails on Vercel?

Check that:
- All dependencies are in `package.json`
- CSV files are in `public/data/`
- No syntax errors in TypeScript files

### Local development not working?

```bash
# Clear cache and reinstall
rm -rf node_modules package-lock.json .next
npm install
npm run dev
```

### Charts not showing?

- Check browser console for errors
- Ensure CSV files are properly formatted
- Verify data files are in `public/data/` directory

---

## Support

For issues or questions:
1. Check the [Next.js documentation](https://nextjs.org/docs)
2. Visit [Vercel documentation](https://vercel.com/docs)
3. Contact First Love Church technical team

---

## Live URL

After deployment, your dashboard will be accessible at:
- **Vercel URL**: `https://your-project-name.vercel.app`
- **Custom Domain**: `https://your-custom-domain.com` (if configured)

Share this URL with your team and congregation to track the podcast's global impact!

---

Built with ❤️ for the Kingdom of God
