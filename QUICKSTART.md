# 🎉 Quick Start Guide - First Love Church Podcast Dashboard

## What You Have

A beautiful, interactive analytics dashboard featuring:
✨ Monthly download trends
✨ Global country distribution
✨ Platform analytics
✨ Real-time statistics
✨ Church-inspired elegant design

## 3 Ways to Use This Dashboard

### 🚀 Option 1: Instant Preview (No Setup Required)
**Perfect for**: Quick viewing, presentations, screenshots

1. Open `preview.html` in any web browser
2. Done! The dashboard is ready to view.

**Note**: This version has hardcoded data and is for preview only.

---

### 💻 Option 2: Full Next.js Dashboard (Recommended for Production)
**Perfect for**: Production deployment, automatic updates, professional hosting

**Requirements**: Node.js 18+ installed

#### Step-by-Step:

1. **Install dependencies** (first time only):
```bash
cd podcast-dashboard
npm install
```

2. **View locally**:
```bash
npm run dev
```
Open http://localhost:3000 in your browser

3. **Deploy to Vercel** (3 simple commands):
```bash
npm install -g vercel
cd podcast-dashboard
vercel
```

Follow the prompts, and you'll get a live URL like: `https://your-project.vercel.app`

---

### 🌐 Option 3: Deploy via GitHub
**Perfect for**: Team collaboration, version control

1. **Create a GitHub repository** and push the code:
```bash
cd podcast-dashboard
git init
git add .
git commit -m "First Love Church Podcast Dashboard"
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

2. **Connect to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Click "Deploy"

Vercel will automatically redeploy when you push updates!

---

## 📂 Project Structure

```
podcast-dashboard/
├── app/
│   ├── page.tsx          ← Main dashboard (interactive charts)
│   ├── layout.tsx        ← App wrapper
│   └── globals.css       ← Styles & animations
├── public/
│   └── data/             ← Your CSV data files
│       ├── Country-stats_2024-12-01_to_2025-11-30.csv
│       ├── downloads-stats-2024-12-01_2025-11-30.csv
│       └── Platforms-stats_2024-12-01_to_2025-11-30.csv
├── preview.html          ← Standalone preview (no setup needed!)
├── package.json          ← Dependencies
└── README.md             ← Full documentation
```

---

## 🎨 Design Features

- **Color Palette**: Burgundy & Gold (church-inspired elegance)
- **Typography**: Cinzel (display) & Crimson Text (body)
- **Effects**: Glass morphism, smooth animations, decorative elements
- **Responsive**: Works beautifully on desktop, tablet, and mobile

---

## 🔄 Updating Data

To update with new podcast statistics:

1. Replace the CSV files in `public/data/` with your updated data
2. Keep the same file names and format
3. If deployed to Vercel, push to GitHub or run `vercel --prod`

The dashboard will automatically refresh with new data!

---

## ⚡ Quick Commands Reference

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Deploy to Vercel
vercel

# Deploy to production (if already deployed)
vercel --prod
```

---

## 🎯 Next Steps

1. **Preview Now**: Open `preview.html` to see the dashboard
2. **Choose Deployment**: Pick Option 2 or 3 above
3. **Customize**: Update colors, fonts, or data as needed
4. **Share**: Send the live URL to your team!

---

## 📱 Mobile Optimized

The dashboard looks stunning on:
- 📱 Mobile phones
- 📱 Tablets
- 💻 Laptops
- 🖥️ Desktop monitors

---

## ❓ Need Help?

- Check `README.md` for detailed documentation
- See `DEPLOYMENT.md` for step-by-step deployment guide
- All files are well-commented and easy to customize

---

## 🎉 You're All Set!

Your professional podcast analytics dashboard is ready to go!

**Recommended first step**: Open `preview.html` to see what you've got!

---

Built with ❤️ for First Love Church
