# 📈 Index Holdings Calculator

A modern web app that shows you exactly what stocks you own when investing in major market indices. Enter your investment amount and instantly see your proportional holdings, share quantities, and sector exposure.

**[Live Demo →](https://kerboler.github.io/StocksTracker/)**

![Dark themed trading terminal interface](https://img.shields.io/badge/theme-dark-1a2332) ![React](https://img.shields.io/badge/React-18.3-61dafb) ![Vite](https://img.shields.io/badge/Vite-5.4-646cff)

---

## Features

### 📊 Multiple Index Support
- **S&P 500** - Top 500 US companies
- **NASDAQ 100** - Tech-heavy index
- **Dow Jones** - 30 blue-chip stocks
- **MSCI World** - Global developed markets

### 💼 Combined Portfolio View
Invest in multiple indices and see your aggregated holdings across all of them. Overlapping stocks (like Apple in both S&P 500 and NASDAQ) are automatically combined.

### 📈 Performance Tracking
View stock performance across multiple timeframes:
- 1 Week
- 1 Month
- Year-to-Date
- 1 Year

### 🎯 Sector Exposure
Interactive donut chart showing your portfolio breakdown by sector (Technology, Healthcare, Financials, etc.)

### 🔍 Search & Sort
- Filter holdings by ticker or company name
- Sort by any column (weight, price, value, performance)

### 🌐 Multi-Language
Available in English, German, and Spanish.

### 💾 Persistent Settings
Your investment amounts and index preferences are saved locally.

---

## Tech Stack

- **React 18** - UI framework
- **Vite** - Build tool & dev server
- **CSS Variables** - Dark theme with custom properties
- **LocalStorage** - Preference persistence

---

## Getting Started

### Prerequisites
- Node.js 18+
- npm

### Installation

```bash
# Clone the repository
git clone https://github.com/kerboler/StocksTracker.git
cd StocksTracker

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:5173/StocksTracker/](http://localhost:5173/StocksTracker/) in your browser.

### Build for Production

```bash
npm run build
```

The built files will be in the `dist/` folder.

---

## Data Sources

Holdings data is sourced from [slickcharts.com](https://www.slickcharts.com). Stock prices and performance data are fetched via automated scripts.

---

## Project Structure

```
├── src/
│   ├── components/       # React components
│   ├── data/            # Index data & services
│   │   └── indices/     # JSON files for each index
│   ├── i18n/            # Translations
│   ├── App.jsx          # Main app component
│   └── index.css        # Styles
├── scripts/             # Python data update scripts
└── dist/                # Production build
```

---

## License

MIT

---

## Acknowledgments

- Index weightings from [SlickCharts](https://www.slickcharts.com)
- Fonts: [Outfit](https://fonts.google.com/specimen/Outfit) & [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)

---

## Built With

Developed using [Cursor](https://cursor.com) IDE with [Claude Opus 4.5](https://www.anthropic.com/claude) AI assistant.
