Scrimba AI Engineer Path Project

Dodgy Dave's Stock Predictions. Uses OpenAI API and Polygon API for generating dodgy advice for user selected stock tickers (eg AMZN for Amazon, TSLA for Tesla, etc).

- Uses Cloudflare workers to handle API requests securely (not exposing API keys)
- Shifts API requests from the client side to the server side
  - Enabled CORS (cross origin resource sharing) to prevent unauthorised use from unknown domains
- Uses a Cloudflare AI Gateway to make the app more robust
  - Real time logs
  - Caching responses
  - Rate limiting
- Cloudflare Pages for automated project deployments
- Custom domains with Cloudflare

Live demo [here](https://stocks.hijamie.com)
