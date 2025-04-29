>>>># Real-Time Crypto Market Tracker

A lightweight web application that tracks live cryptocurrency prices in real-time.  
Built with React.js and powered by the free CoinGecko API, this dashboard fetches and displays updated prices for major cryptocurrencies every minute.

>## Features

- Real-time updates of Bitcoin, Ethereum, and more.
- Fully responsive and mobile-friendly UI.
- Optional mini chart integration (future improvement).
- Fetches data from CoinGecko public API without the need for an API key.
- Clean and modern design.

>## Tech Stack

- **Frontend:** Next.js
- **API Source:** [CoinGecko API](https://www.coingecko.com/en/api)
- **Optional Styling:** TailwindCSS (highly recommended)

>## Getting Started

> ### Prerequisites
- Node.js 
- npm

> ### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/real-time-crypto-market-tracker.git
   cd real-time-crypto-market-tracker

2. Install dependencies:

npm install

3. Start the development server:

npm run dev

4. Open http://localhost:3000 to view the dashboard in your browser.

>## Project Structure

crypto-dashboard/
├── components/
│   ├── PriceCard.jsx      # Displays individual cryptocurrency data
│   └── PriceChart.jsx     # (Optional) Displays live chart
├── services/
│   └── cryptoApi.js       # Handles API calls to CoinGecko
├── pages/
│   └── index.jsx          # Main dashboard page
├── public/
│   └── favicon.ico
├── package.json
└── README.md


>>## API Reference
Base URL: https://api.coingecko.com/api/v3/

Example Endpoint:

/simple/price?ids=bitcoin,ethereum&vs_currencies=usd
No authentication required for basic price data.

>## Roadmap
 Real-time cryptocurrency price updates

 Add support for multiple currencies (e.g., EUR, GBP)

 Implement sparkline mini-charts for price movement

 Deploy to Vercel or Netlify

>## License
This project is licensed under the MIT License.
Feel free to use, modify, and share it!

Author
Developed by Diego Gonzalez
