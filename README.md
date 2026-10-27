# 🏏 MATCHDAY — Live Cricket Scorecard & Scorer

MATCHDAY is a modern, responsive, and feature-rich live cricket scoring web app. Designed with a bold, sporty red-and-charcoal visual identity, it supports full ball-by-ball scoring, custom rules, squad management, analytics, and official PDF scorecard exports.

![Matchday App](https://images.unsplash.com/photo-1531415074968-036ba1b575da?w=1200&q=80)

---

## 🌟 Key Features

- **🎯 Chase Mode & Full Match**: Enter the opponent's score directly to start chasing right away, or score both innings from ball one.
- **⚡ Accurate Cricket Rules Engine**:
  - Legal & non-legal delivery tracking (6 balls/over).
  - Strike rotation on odd runs & change of ends.
  - **No-Balls**: Credit 0 to 6 runs directly to the batsman, or record No-Ball + Byes / Leg Byes.
  - **Free Hit**: Automatic Free Hit enforcement following any No-Ball.
  - **Byes & Leg Byes**: 1 to 6 runs without penalizing bowler figures.
  - **Wide Balls**: 1 to 5 runs recorded to team extras and charged to bowler.
  - **Wicket Dismissals**: Bowled, Caught, LBW, Run Out, Stumped, Hit Wicket with next batsman selector.
  - **Bowler Restrictions**: Cannot bowl consecutive overs; per-bowler quota checks.
- **📄 Official PDF Scorecard Export**:
  - One-click print/download of publication-ready match reports formatted for A4 portrait.
  - Includes full batting scorecard, bowling figures, extras breakdown, fall of wickets (FOW), and partnerships.
- **📊 Real-time Stats & Analytics**:
  - Runs by phase donut chart (Powerplay 1-6, Middle 7-15, Death 16+).
  - Extras breakdown bar charts.
  - Dynamic partnership progress tracking.
- **💾 100% Offline & Local Persistence**:
  - Complete state and ball-by-ball history stored in `localStorage` — never lose match progress on refresh.
- **📱 Mobile-First PWA Ready**:
  - Responsive layout that can be added to the mobile home screen for a full-screen native app experience.

---

## 🚀 Live Demo & Deployment

This project is completely self-contained in a single file (`index.html`) with no build steps or external package dependencies required.

### Deploying to GitHub Pages:
1. Push this repository to GitHub.
2. In your repository, go to **Settings** → **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose `main` branch and `/ (root)` folder, then click **Save**.
5. Your live app will be published at `https://<username>.github.io/<repo-name>/`.

---

## 🛠️ Built With

- **HTML5 / CSS3**: Custom responsive grid layout, SVG charts, and print media queries.
- **Vanilla JavaScript**: Pure zero-dependency reactive scoring engine with deep state snapshots (undo support).
- **Typography**: Google Fonts ([Oswald](https://fonts.google.com/specimen/Oswald) & [Inter](https://fonts.google.com/specimen/Inter)).

---

## 📄 License

MIT License. Free to use and customize for local cricket clubs, tournaments, and personal games.
