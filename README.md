# Share Analyzer

A transparent, weight-based research tool for Indian shares and IPOs.

> **Testing phase.** "Share Analyzer" is a working name and will change.
> Views are a weighted combination of scores and do not claim to be 100% correct.
> **Not investment advice.**

## What it does
Search any listed Indian share or IPO by name. The app reads global, national
and company news, then checks growth, results, valuation, market mood and
chart levels, and ends with a BUY / HOLD / SELL view for the short, mid and
long term.

## Features
- **Share analysis:** 43 factors in 10 groups, each scored -10 to +10
- **Adjustable weights and bias:** 7 personas plus your own custom layer
- **Three horizons:** short (1-2 weeks), mid (1-6 months), long (6+ months)
- **IPO analysis:** main board and SME, GMP, subscription, listing-day and long-term views
- **Share search:** screener with nearly 100 filters across 5,526 shares, plus near-miss results
- **ASM / GSM lists:** current exchange surveillance lists in plain language
- **Portfolio:** live prices, daily gain/loss, broker file import, capital-gains tax estimate
- **Weather and season factor:** only for weather-sensitive businesses
- **Offline news models:** FinBERT and MiniLM (optional), with a word-list fallback

## How the view is calculated
Safeguards: market factors are capped at 30% of the weight used, a share
with too little data gets "WATCH" rather than a call, and red flags cap the
view at HOLD.

## Privacy and safety
- Runs on your own computer; no account or sign-up
- Never connects to a broker or asks for credentials
- Cannot place, change or cancel orders
- Portfolios and history stay in the app's own folder

## Getting started
1. Download or copy the project folder (it includes its own Python).
2. Double-click `start.bat` on Windows.
3. Type a company name or IPO name and press Enter.

## Screenshots and report
See the `/screenshots` folder and the full HTML report in `/docs`.

## Roadmap
Track record and hit rate, learned weights with calibrated probabilities,
watchlist alerts, side-by-side comparison, PDF export, risk-profile questionnaire.

## Author
**Armaan Pachar**, B.Tech (Biotechnology) student and independent developer
[LinkedIn](https://linkedin.com/in/armaan-pachar-b42b64261) · [GitHub](https://github.com/armaan2197) · armaancsir@gmail.com

## Disclaimer
Research and education tool only. Not registered with SEBI as an investment
adviser or research analyst. Grey-market premiums are unofficial. Verify all
information independently and consult a registered adviser before investing.
