# Collar AI — Landing Page

Landing page for [Collar AI](https://github.com/Sonra0/Collar_AI), an AI-powered Chrome extension that coaches your body language in real time during Google Meet calls.

**Live site:** [https://sonra0.github.io/collar-ai-website/](https://sonra0.github.io/collar-ai-website/)

## What is Collar AI?

Collar AI monitors your camera feed during Google Meet calls using AI vision (Claude / OpenAI) and delivers real-time coaching on posture, eye contact, facial expression, and engagement. After the call, you get a full summary report with scores and action items.

### Key Features

- **Real-Time Analysis** — AI vision analyzes your camera feed every 5 seconds
- **Live Coaching Feed** — Side panel streams coaching cues as they happen
- **Post-Meeting Summary** — Timeline charts, category scores, and ranked action items
- **Privacy-First** — Frames are processed and discarded instantly; your API key stays local

### Tech Stack

- Chrome Extension (Manifest V3)
- Anthropic Claude / OpenAI GPT-4o Vision APIs
- Vanilla JavaScript (ES6+)
- Webpack 5 + Chart.js

## About This Site

Single-page static site built with vanilla HTML, CSS, and JavaScript. No build step required.

### Sections

- Hero with demo video placeholder
- Problem / Solution breakdown
- Features showcase
- How It Works (3-step flow)
- Installation guide with step-by-step SVG illustrations
- Tech stack overview

### Run Locally

Just open `index.html` in a browser — no server needed.

### Deploy

Hosted on GitHub Pages from the `main` branch.

## DSOC 2026

This project is a submission for [Dev Season of Code 2026](https://devseasonofcode.com), a global hackathon focused on practical implementation and open innovation.

## License

MIT
