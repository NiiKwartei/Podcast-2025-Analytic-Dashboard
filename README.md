# First Love Church Podcast - Analytics Dashboard

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/NiiKwartei/Podcast-2025-Analytic-Dashboard)

A beautiful, modern analytics dashboard tracking the global reach and impact of the First Love Church Podcast.

## 🚀 Features

- **Interactive Global Map**: Visualize downloads across 15+ countries with custom markers
- **Real-time Statistics**: Track total downloads, monthly averages, and platform distribution
- **Modern Dark Theme**: Sleek purple and blue color scheme with glass morphism effects
- **Responsive Design**: Optimized for desktop viewing with proper chart sizing
- **Platform Analytics**: Detailed breakdown of iOS, Android, and other platform usage

📊 **Analytics Overview**
- Total Downloads: 155,798
- Monthly Average: 12,983
- Top Country: United Kingdom (62,058 downloads)
- Top Platform: iOS (124,120 downloads)

🎨 **Distinctive Design**
- Modern dark theme with purple and blue accents
- Glass morphism effects
- Elegant serif typography (Cinzel & Crimson Text)
- Smooth animations and transitions
- Interactive Leaflet.js map with custom markers

## 🛠️ Tech Stack

- **HTML5** - Structure
- **Tailwind CSS** - Styling and responsive design
- **Chart.js** - Interactive charts and graphs
- **Leaflet.js** - Interactive map visualization
- **Custom CSS** - Glass morphism and animations

## 💻 Getting Started

### Local Development

To run locally, simply serve the static files:

**Using Python:**
```bash
python3 -m http.server 8000
# Open http://localhost:8000
```

**Using Node.js:**
```bash
npx http-server
# Open http://localhost:8080
```

**Using PHP:**
```bash
php -S localhost:8000
# Open http://localhost:8000
```

No build process required - just open `index.html` in your browser!

## 🌐 Deploy to Vercel

This project is Vercel-ready! Deploy with one click:

1. Click the "Deploy with Vercel" button above
2. Connect your GitHub account
3. Deploy!

Or manually deploy using Vercel CLI:
Or manually deploy using Vercel CLI:

```bash
# Install Vercel CLI
npm i -g vercel

# Navigate to project
cd "/Users/winstonquartey/Downloads/Podcast 2025 Analytic Dashboard"

# Deploy
vercel

# Deploy to production
vercel --prod
```

See [DEPLOYMENT.md](./DEPLOYMENT.md) for detailed deployment instructions.

## 📁 Project Structure

```
.
├── index.html          # Main dashboard file (static HTML)
├── vercel.json         # Vercel configuration
├── .vercelignore       # Files to ignore during deployment
├── package.json        # Project metadata
├── README.md           # This file
├── DEPLOYMENT.md       # Detailed deployment guide
└── QUICKSTART.md       # Quick start guide
```

## 🎨 Customization

### Update Analytics Data

Edit the data arrays in `index.html` (around line 280-310):

**Monthly Downloads:**
```javascript
const monthlyData = {
  labels: ['Dec 24', 'Jan 25', ...],
  datasets: [{
    data: [8942, 8492, ...]
  }]
};
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

### Build for Production

```bash
npm run build
```

The output will be a static export in the `out` directory.

## Deploying to Vercel

### Option 1: Deploy via Vercel CLI

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Deploy:
```bash
vercel
```

3. Follow the prompts to link your project

### Option 2: Deploy via Vercel Dashboard

1. Push your code to GitHub, GitLab, or Bitbucket

2. Go to [vercel.com](https://vercel.com)

3. Click "Add New Project"

4. Import your repository

5. Vercel will automatically detect Next.js and configure the build settings

6. Click "Deploy"

### Option 3: Deploy with Git Integration

1. Connect your Git repository to Vercel

2. Every push to your main branch will trigger an automatic deployment

## Customization

### Colors

Edit the colors in `tailwind.config.js`:
```javascript
colors: {
  burgundy: { /* your colors */ },
  gold: { /* your colors */ },
  cream: { /* your colors */ }
}
```

### Fonts

Change fonts in `tailwind.config.js` and update the import in `app/globals.css`

### Data Sources

Place your CSV files in `public/data/`:
- `Country-stats_2024-12-01_to_2025-11-30.csv`
- `downloads-stats-2024-12-01_2025-11-30.csv`
- `Platforms-stats_2024-12-01_to_2025-11-30.csv`

## Project Structure

```
podcast-dashboard/
├── app/
│   ├── globals.css          # Global styles and animations
│   ├── layout.tsx            # Root layout
│   └── page.tsx              # Main dashboard page
├── public/
│   └── data/                 # CSV data files
├── next.config.js            # Next.js configuration
├── tailwind.config.js        # Tailwind CSS configuration
├── tsconfig.json             # TypeScript configuration
└── package.json              # Dependencies and scripts
```

## Performance

- Static export for optimal loading speed
- Lazy loading of charts
- Optimized animations
- Responsive design for all devices

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Copyright © 2024 First Love Church. All rights reserved.

## Support

For questions or support, please contact First Love Church.

---

Built with ❤️ for the Kingdom of God
