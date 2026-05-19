# Sentiment Dashboard

Paste multiple texts and get instant AI-powered sentiment analysis with interactive charts — powered by Groq API.

## Features

- **Batch analysis** — paste many texts at once, all analyzed in a single API call
- **Sentiment scoring** — each text scored from -100 (very negative) to +100 (very positive)
- **Overall sentiment** — Positive / Negative / Neutral / Mixed with confidence rating
- **Emotion breakdown** — joy, anger, fear, sadness, surprise, disgust visualized as animated bars
- **Donut chart** — sentiment distribution across all texts drawn with Canvas API
- **Keyword cloud** — emotionally charged words sized by frequency, colored by sentiment
- **Sortable results table** — browse text-by-text with sentiment badges, score bars, and emotion chips
- **Export to JSON** — download full analysis results
- **History** — last 3 analyses saved in localStorage with timestamps
- **Single text mode** — analyze one long text paragraph by paragraph
- **Language auto-detection** — no need to specify the language

## How to Use

1. Get a free Groq API key at [console.groq.com](https://console.groq.com)
2. Open `index.html` in any modern browser
3. Enter your Groq API key (saved locally in your browser)
4. Paste texts — one per line, or separated by blank lines
5. Click **Analyze Sentiment**

## Tech Stack

- Vanilla JavaScript (ES6+)
- HTML5 & CSS3
- Canvas API (charts drawn from scratch — no Chart.js or other libs)
- [Groq API](https://groq.com) — `llama-3.3-70b-versatile` model
- No frameworks, no build tools, no npm — single `index.html` file

## License

MIT
