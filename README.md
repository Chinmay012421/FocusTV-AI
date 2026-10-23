# FocusTV AI — TV-first discovery prototype

A React + Vite prototype for a TV-friendly entertainment discovery companion. Includes service shortcuts, a local sample catalogue, keyword-based discovery, local watchlist, and shared-interest demo.

## Run locally (Windows PowerShell)
```powershell
npm.cmd install
npm.cmd run dev
```
Open the local URL printed by Vite, usually `http://localhost:5173/`.

Build check:
```powershell
npm.cmd run build
```

## Important current limitations
- This is a web prototype, not a verified or packaged Fire TV app.
- Search uses local keyword matching, not a real AI model.
- Catalogue entries are illustrative; live service availability is not verified.
- App cards open websites; native app launching requires platform-specific integration and device testing.
- Watchlist is stored in browser localStorage.
- No database, login system, or AI provider is connected yet.

## Next development milestones
1. Verify target Fire TV OS and current Amazon app submission requirements.
2. Test remote navigation and screen layouts on a TV/device.
3. Connect a server-side AI provider (keep API keys out of frontend and GitHub).
4. Add an attributed catalogue and supported provider integrations.
5. Add Supabase authentication and data persistence, then test row-level security.
6. Prepare a documented demo and test results.

FocusTV is an independent concept and is not affiliated with YouTube, Prime Video, Netflix, Spotify, or Twitch.


## Keyboard / remote-style navigation update
- Use the arrow keys to move focus between visible controls and cards.
- Press Enter or Space to activate the focused button.
- Press Escape to close a content detail modal.
- Focus outlines make the selected control easier to see from a distance.
- Arrow navigation is intended for browser testing; test on an actual Fire TV device before claiming native remote compatibility.
