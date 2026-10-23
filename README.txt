MotoCare PWA Prototype 0.3

Files:
- index.html: app interface and features
- manifest.json: installable app metadata
- sw.js: service worker for caching the app shell for offline loading
- icon.svg: app icon

How to publish from an Android phone:
1. Sign in to GitHub in your browser and create a new public repository named motocare.
2. Use Add file > Upload files and upload all four files from this ZIP. Ensure index.html is at the repository root.
3. In repository Settings > Pages, choose Deploy from a branch, branch main, folder /(root), then Save.
4. Wait for GitHub Pages to publish. Open the provided https://...github.io/... site in Chrome.
5. Open the site once while online. In Chrome's menu, use Install app or Add to Home screen if offered.
6. Test by reopening the installed app and temporarily turning off connectivity.

Notes:
- The PWA service worker requires HTTPS or localhost; opening index.html as a downloaded local file will not enable it.
- Local records are stored in browser storage on that device. This is not cloud sync. Export backups regularly.
- Test the site on your own device before sharing it. PWA install prompts vary by browser/version.
- The app is a prototype, not a certified maintenance guide. Verify all records and any maintenance advice with the vehicle manual or qualified service provider.
