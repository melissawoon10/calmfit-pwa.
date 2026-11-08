# CalmFit — React PWA

A mobile-first fitness tracker, built with React and Vite. Features: personalized rule-based workout templates, workout logging, rest timer, strength progress, and manual nutrition tracking.

## Run locally (computer)
1. Install Node.js LTS from https://nodejs.org
2. Open a terminal in this folder.
3. Run `npm install` and then `npm run dev`.
4. Open the address printed in your terminal.

## Put it on your iPhone without Xcode (recommended: GitHub + Netlify)
1. Create a free GitHub account at https://github.com and a new repository called `calmfit-pwa`.
2. Upload the **contents** of this unzipped folder into the repository, preserving the `src` and `public` directories. You can use GitHub's **Add file > Upload files** option.
3. Sign in at https://app.netlify.com with GitHub. Choose **Add new project > Import an existing project** and select your repository.
4. Set build command to `npm run build` and publish directory to `dist`. Deploy. Netlify gives you an HTTPS URL.
5. On iPhone, open the URL in Safari. Tap Share > Add to Home Screen > Add. Open CalmFit from its icon.

Changes: edit the source files in GitHub and Netlify will redeploy after a commit. For a visual development experience, import the repo into Replit.

## Data and privacy
Workout and meal data are saved only in your browser's localStorage. This is **not synced** between devices or browsers. Clearing website data, changing domains, or deleting the home-screen app may remove your data. Historical workout samples are included as editable seed data in `src/main.jsx` and are not verified comprehensive records. Do not use the app for medical guidance. Timer notifications are best-effort while the app is open; iOS may suspend background tabs.

## AI disclaimer
Workout generation in this MVP is rule-based, not connected to an AI model. To add true AI generation, use a server-side API with secure key storage; never embed an AI provider API key in client-side React code.

## Check build
`npm run build`
