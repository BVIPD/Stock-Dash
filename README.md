# Stock-Dash
Stock Dash
Your Personal AI-Powered Stock Consultant

Project Description
The stock market can be intimidating for beginners. Existing apps often show complex prices without providing guidance, leading new traders to make decisions based on unreliable advice from friends or social media.
Stock Dash is a cross-platform application that acts as a personal stock consultant for new investors. It leverages the Finnhub live market API to translate complex financial data into simple, actionable guidance. The app is built as a Progressive Web App (PWA), making it accessible on both desktop and mobile devices.

Key Features
Global Portfolio Management: Users can add stocks from any worldwide exchange by entering the ticker symbol, number of shares, and purchase price.
Real-Time Data: The app provides live prices and daily change percentages sourced directly from the Finnhub API.
Risk Insights: Each stock holding is tagged with a risk level (low, medium, or high) based on volatility and trend analysis.
Actionable Advice: The app automatically generates recommendations, such as "Reduce exposure to high-beta IT stocks" or "Add defensive sectors to diversify".
Portfolio Comparison: Interactive graphs allow users to visually compare the performance of multiple portfolios.
Usage Tracking & Billing: The application is integrated with Flexprice to track and display usage, such as the number of portfolio analyses or advice reports generated.
Technology Stack
Frontend: Next.js, Tailwind CSS, React, PWA manifest, and service worker.
Backend: Node.js (Express) or serverless functions.
Data Source: Finnhub API (for quotes, profiles, and symbol lookup).
Visuals: Recharts or Chart.js for rendering portfolio comparison graphs.
Billing: Flexprice SDK/webhook for usage tracking and billing.


Getting Started
To get a local copy up and running, follow these simple steps.
Prerequisites:
Node.js installed
An API key from Finnhub
Installation:
Clone the repository: git clone [repository_url]
Navigate to the project directory: cd stock-dash
Install dependencies: npm install
Create a .env file and add your Finnhub API key: FINNHUB_API_KEY=your_api_key
Run the application: npm run dev
