MY PERSONAL AI — ANDROID PWA (FREE STARTER)

Files:
- index.html: app interface and Gemini API client
- manifest.json: installable PWA metadata
- sw.js: basic static asset caching
- icon-192.png / icon-512.png: app icons

To publish for phone installation at zero hosting cost:
1. Create a GitHub account and a new PUBLIC repository (example: my-personal-ai).
2. Upload all five files to the repository root.
3. In repository Settings > Pages, choose Deploy from a branch, select main and /(root), Save.
4. Wait for the Pages URL, typically https://USERNAME.github.io/REPOSITORY/.
5. Open that HTTPS URL in Android Chrome. Tap ⋮ > Add to Home screen / Install app.
6. In the app, create a Gemini API key at https://aistudio.google.com/apikey and paste it into the key field.

IMPORTANT SECURITY:
This is a personal prototype. The key is stored in this browser and sent to Google's Gemini API directly. Anyone with access to this browser/device may inspect it. Do not commit your key into GitHub, do not share this app as a public service, and do not use a key with billing enabled. Check current free-tier quota and terms. Free tiers can change.
The app's Search web button opens Google Search; it does not fetch/ground web results into the AI answer.
Speech recognition varies by Android browser and may use an online service. The app requires internet for AI chat. Chat/memory are stored in browser localStorage and may be lost if site data is cleared.
