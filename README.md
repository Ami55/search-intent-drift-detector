# Search Intent Drift Detector

Vercel-ready application for comparing controlled SERP observations and identifying evidence-bounded intent shifts.

## App deployment

Upload all files from the app ZIP to a new GitHub repository and import it into Vercel. No app environment variables are needed.

## Gemini Proxy 3

Upload `intent-drift.js` from the proxy ZIP into the `api` folder of `gemini-proxy-3`. Confirm that Proxy 3 has `GEMINI_API_KEY`.

The app calls `https://gemini-proxy-3.vercel.app/api/intent-drift`.

Use the same query, locale, language, device and collection method for both snapshots. One comparison cannot prove a permanent intent change; repeat observations before making large site changes.
