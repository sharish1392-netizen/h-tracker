# Harish Personal Habit & Health Tracker

A zero-build, static PWA (HTML + Tailwind CDN + Vanilla JS) backed by **Google Sheets** (`Harish_Personal_Habit_Health_DB`) via **Google Apps Script**.

## Quick Deploy to GitHub & Vercel

1. **Create a new GitHub repository** (e.g., `personal-health-tracker`) and upload these 3 files (`index.html`, `manifest.json`, `vercel.json`).
2. **Import into Vercel**:
   - Go to [vercel.com/new](https://vercel.com/new), select your `personal-health-tracker` repo, leave Framework Preset as **Other** (no build step needed — zero build errors!), and click **Deploy**.
3. **Connect Your Google Sheet**:
   - Open your deployed Vercel URL, tap the **Insights** tab, paste your Google Apps Script Web App URL + `HARISH_TRACKER_2026`, and hit **Save & Sync Now**.
4. **Install on Mobile**:
   - Open the Vercel URL in Chrome (Android) or Safari (iOS) and select **Add to Home Screen**.
