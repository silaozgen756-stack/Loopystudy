# Loopy Study 🐰🥕

> A spaced repetition study app with a carrot garden, a hopping rabbit, and a quiet corner to actually learn things.

**Designed by me. Built with AI assistance.**

Loopy Study is my first app, created around a simple idea: studying the right thing at the right time is better than cramming.

I designed the concept, visual style, user experience, features, and product decisions. I used **Claude as an AI coding assistant** to help turn my ideas into working code.

## Features

- Add subjects with notes and custom tags
- Spaced repetition with **1 → 3 → 5 → 10 → 17 → 30 day** intervals
- Study timer with minimize support
- Focus mode for distraction-free studying
- Daily streak tracking
- Carrot garden that grows as you review
- Harvest mastered subjects
- Hopping rabbit animations
- Confetti when a topic is mastered
- Eye comfort mode and dark mode
- English, Turkish, German, French, Spanish, Japanese and Korean
- Responsive design for phone, tablet and desktop
- Optional browser reminders

## Tech Stack

- **React 18**
- **Babel Standalone**
- **CSS / CSS Custom Properties**
- **localStorage**
- **Service Worker / PWA**
- **Baloo 2**

The app intentionally has **no build step or bundler**. The main application lives in a single `index.html` file with a few PWA assets.

## Data & Privacy

All study data is stored locally on the device using `localStorage`.

There is no backend or external database, so the app does not send study data to a server.

## Run Locally

Clone the repository and open the app in your browser:

```bash
git clone https://github.com/yourusername/loopy-study.git
cd loopy-study
```

For full PWA functionality, run it through a local server:

```bash
python3 -m http.server 8080
```

Then open:

`http://localhost:8080`

## About the Development

This is a solo project designed by me and developed with AI assistance.

I made the product and design decisions — including the study system, garden concept, visual style, user experience, and feature set. Claude was used as a coding assistant during implementation.

## What's Next

- [ ] Export / import study data
- [ ] Better study statistics
- [ ] Subject sharing
- [ ] Weekly leaderboard

---

Made with 🥕 and a lot of late-night study sessions.
