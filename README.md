# EcoLearn — Smart Sustainability Learning Platform

A responsive React + TypeScript sustainability-learning MVP built with Vite, Tailwind CSS, Lucide icons, and browser LocalStorage.

## Features

- Student dashboard with eco-points, level, streak, lesson progress, and recommendations.
- Six sustainability lesson topics mapped to UN SDGs.
- Interactive knowledge check with automatic scoring, explanations, and topic recommendations.
- Five daily eco-challenges with points and duplicate same-day reward prevention.
- Activity history and SDG explorer.
- Personal progress analytics and a fictional demo leaderboard.
- Responsive desktop sidebar and mobile navigation.
- LocalStorage persistence and reset-demo action.
- GitHub Actions workflow for GitHub Pages deployment.

## Run locally

Requirements: Node.js 20+ and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite, usually http://localhost:5173.

Build and preview:

```bash
npm run build
npm run preview
```

## Deploy to GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **GitHub Actions** as the source.
3. Pushes to `main` trigger the included `.github/workflows/deploy.yml` workflow.
4. When the workflow succeeds, your project site should be available at https://sajeel588.github.io/ecolearn/.

The Vite config uses `base: '/ecolearn/'`, which matches this repository's project-site URL.

## Demo data and transparency

- The sample learner profile is fictional. Progress is stored locally in the current browser.
- Quiz scores guide simple rule-based learning recommendations; no live AI API is connected.
- Educator analytics and leaderboard examples are fictional demo data, not institutional measurements.
- Challenge completions are self-reported. The app counts activities but does not fabricate or claim verified carbon, water, or waste savings.
- There is no remote database or authentication service connected.

## Future production work

For production, add server-side identity and storage, automated tests, educator permissions, privacy/consent controls, and verified measurement methods before collecting institutional analytics.
