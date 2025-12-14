# First Love Church Podcast Analytics Dashboard

A beautiful, interactive analytics dashboard for tracking the First Love Church Podcast's global reach and impact.

## Features

✨ **Interactive Visualizations**
- Monthly download trends with animated line charts
- Platform distribution with pie charts
- Top 15 countries by downloads with horizontal bar charts
- Real-time statistics cards

🎨 **Distinctive Design**
- Church-inspired color palette (burgundy and gold)
- Elegant serif typography (Cinzel & Crimson Text)
- Smooth animations and transitions
- Glass morphism effects
- Decorative elements and ornaments

📊 **Data Insights**
- Total downloads tracking
- Average monthly downloads
- Geographic distribution analysis
- Platform usage breakdown

## Tech Stack

- **Framework**: Next.js 14 (React 18)
- **Styling**: Tailwind CSS
- **Charts**: Recharts
- **Icons**: Lucide React
- **Language**: TypeScript

## Getting Started

### Prerequisites

- Node.js 18+ installed on your machine
- npm or yarn package manager

### Installation

1. Clone or download this repository

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
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
