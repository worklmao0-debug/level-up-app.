LEVEL UP — ULTIMATE EDITION
============================

Files:
- index.html: the complete app, styles and JavaScript
- manifest.json: installable web app metadata
- sw.js: service worker that caches the app shell for offline launch
- icon.svg: app icon

INSTALL ON IPHONE (recommended)
1. Download and unzip the bundle.
2. Upload all four files to the root of a GitHub repository.
3. In the repository, open Settings > Pages.
4. Under Build and deployment, select "Deploy from a branch", branch "main", folder "/ (root)", then Save.
5. Wait until GitHub Pages shows a website URL.
6. Open that HTTPS URL in Safari while online. Leave the app open briefly to let the service worker install and cache the files.
7. Use Safari Share > Add to Home Screen. If offered, enable "Open as Web App".
8. Launch the Home Screen icon while online once, then test offline using Airplane Mode.

FEATURES
- Responsive desktop/mobile interface with dashboard and multiple sections
- Achievement log with categories, effort-based XP, editing/deleting
- XP progression with scaling level requirements
- Prestige at level 50; each prestige grants a permanent +10% future XP multiplier
- Daily step tracking with configurable XP rate; XP calculated from total steps to avoid repeated-save double counting
- Daily habits with one completion reward per habit per date
- Goals with progress, rewards and archive
- Daily reflection journal and quick notes
- Streaks, activity days, category breakdown and XP charts
- Unlockable achievement badges
- Skill tree levels based on relevant logged categories
- Themes, accent colors, display name, motto, daily target, motion/celebration settings
- Local JSON export/import backup

DATA & XP NOTES
- Data is stored in localStorage on this device/browser; no account or cloud sync.
- Export JSON backups regularly. Clearing browser website data can delete local data.
- Achievement edits/deletes do not reverse already-earned lifetime XP. Unchecking a habit does not claw back XP.
- Step XP is calculated from the daily step total and awarded when the steps are saved. If you later lower your step count, previously earned XP is not automatically removed.
- The app is designed as a self-improvement aid, not a medical or fitness device.
