PITL — PUSH IT TO THE LIMITS
============================

PITL is a mobile-friendly, installable progressive web app (PWA).
It generates HIIT sessions matched to fitness level, location, and available equipment.

FEATURES
- Beginner: 30s work / 30s rest
- Intermediate: 40s work / 20s rest
- Challenging: 45s work / 15s rest
- 12-, 20-, 30-, and 40-minute sessions
- Full body, upper body, lower body, core, and cardio
- Commercial gym, home gym, limited equipment, and no equipment
- 14 equipment choices, plus custom equipment notes / common aliases
- A randomized exercise lineup, exercise explanations, and swap alternatives
- Guided timer, warmup, cooldown, sounds, pause, and skipping
- Add Apple Music song / album / playlist share links (paste from iPhone)
- Listen in PITL through official Apple Music embeddable player
- Choose a saved Apple Music pick to show alongside HIIT interval timer
- Open selected links in Apple Music for normal full playback
- Add, shuffle, and remove personal song titles, artists, and links
- Training history and statistics (stored locally on your device)
- Offline support after first load when installed from an HTTPS host

FAST PREVIEW
Open index.html in a modern web browser. PITL-Open-App.html is an
identical single-file version of the app, included separately for convenience.

INSTALL ON IPHONE LIKE AN APP
1. Upload the contents of pitl-app/ to a static HTTPS host (for example,
   GitHub Pages or Netlify). Keep index.html, manifest.webmanifest,
   service-worker.js, and icon files together in one folder.
2. Visit your hosted URL with Safari on your iPhone.
3. Tap Share, then Add to Home Screen.
4. Open PITL from your Home Screen. After its first load, the app works
   offline for generating workouts and viewing saved tracks and history.

IMPORTANT NOTES
- PITL does not store account data on a server. Training settings,
  your song list, and your history stay in this browser's local storage.
  Clearing site data removes them. Different devices do not sync.
- Apple Music audio is supplied by Apple’s official iframe player, not hosted by PITL.
  Non-subscribers may only hear previews. Full playback may require an active
  Apple Music subscription and Apple sign-in; use Open in Apple Music if preferred.
- PITL does not log into Apple Music, import your private library or control
  native Apple Music playback. Those features require a separate MusicKit setup.
- Apple Music embeds require a network connection, even when workouts run offline.
- You can also save other song links for Spotify / YouTube and open them externally.
- Equipment not recognized by the generator can be saved as custom notes,
  but exercises will only be matched to selected recognized equipment.
- If a workout makes you faint or dizzy, stop. Adjust pace and weights to
  your fitness and comfort; follow medical guidance where appropriate.

PITL v1.1 — Apple Music support — 2026

UPDATING AN EXISTING NETLIFY SITE
1. Log in to Netlify and open the site you already created for PITL.
2. Deploy this new ZIP to the same site (Deploys -> deploy manually / drag and drop).
3. Refresh the PITL tab in Safari. If using Home Screen app, close and reopen it.
4. Use the PITL playlist tab to paste links copied from Apple Music.
   Your saved training and links should remain if the same site address is used.
   A brand-new hosting address has separate device storage.
