# Crypto Tracker

## Introduction

Crypto Tracker is a comprehensive web application designed to monitor cryptocurrency market data in real-time. This application provides users with up-to-date information on cryptocurrency prices, market capitalization, trading volume, and price changes over various time periods. Built with React and leveraging the power of the CoinGecko API, Crypto Tracker delivers a seamless experience for cryptocurrency enthusiasts, investors, and traders.

## Features

- **Real-time Market Data**: Access current prices, market capitalization, and trading volumes for hundreds of cryptocurrencies
- **Price Change Tracking**: Monitor price fluctuations over 24-hour, 7-day, and 30-day periods
- **Search Functionality**: Easily find specific cryptocurrencies through the integrated search feature
- **Pagination**: Navigate through the extensive list of cryptocurrencies with an intuitive pagination system
- **Responsive Design**: Enjoy a consistent user experience across desktop and mobile devices
- **Currency Conversion**: View prices in multiple fiat currencies including USD and INR

## Technology Stack

- **Frontend Framework**: React.js
- **State Management**: React Context API
- **Routing**: React Router
- **UI Components**: Material-UI
- **API Integration**: CoinGecko API
- **Styling**: CSS3 with responsive design principles
- **HTTP Client**: Axios

## Installation

To set up a local development environment:

1. Clone the repository
   ```
   git clone https://github.com/Prajwal675/Crypto_Tracker.git
   ```

2. Navigate to the project directory
   ```
   cd Crypto_Tracker
   ```

3. Install dependencies
   ```
   npm install
   ```

4. Start the development server
   ```
   npm start
   ```

5. Open your browser and navigate to `http://localhost:3000`

## Usage Guide

### Homepage

The landing page displays a table of cryptocurrencies sorted by market capitalization. Each entry includes:
- Cryptocurrency name and symbol
- Current price
- 24-hour price change percentage
- Market capitalization

Users can navigate through the list using the pagination controls at the bottom of the page.

### Search

Utilize the search bar at the top of the page to filter cryptocurrencies by name or symbol. The results update dynamically as you type.

### Currency Conversion

Select your preferred fiat currency (USD or INR) from the dropdown menu located in the header. All cryptocurrency prices will update to reflect the selected currency.

## API Integration

This application leverages the CoinGecko API to fetch cryptocurrency data. The integration includes:

- Market overview data
- Individual cryptocurrency details
- Historical price data
- Currency conversion rates

No API key is required for basic functionality, as the application uses the public endpoints provided by CoinGecko.

## Deployment

The application is configured for easy deployment to platforms such as Netlify, Vercel, or GitHub Pages. To deploy:

1. Build the production-ready application
   ```
   npm run build
   ```

2. Deploy the contents of the `build` directory to your preferred hosting platform
