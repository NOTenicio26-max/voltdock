# VoltDock — EV Battery Swap Frontend Prototype

A self-contained HTML/CSS/JavaScript website for a tech-fest demonstration.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. No build step or package installation is required.

## Deploy
### Netlify
- Open Netlify and choose **Add new site → Deploy manually**.
- Drag the extracted `voltdock` folder (or its contents) into the deploy area.

### Vercel
- Create a new project and upload/push this folder to a Git repository.
- Framework preset: **Other**.
- Build command: leave blank.
- Output directory: `.`

### GitHub Pages
- Upload `index.html` to a repository.
- Enable Pages for the branch and root folder.

## Included interactions
- 10-slot station inventory visualization
- Battery swap simulator with a simulated fee
- Original-battery PIN reservation flow
- ETA-based battery booking, simulated check-in and cancellation
- Resettable station state
- Selectable replacement battery options (100%, 92%, 80%)
- Nearby kiosk explorer with nearest/farthest sorting, filters, and local demo bookings

## Important limitations
All data and actions are local to the browser. Nearby kiosk names, distances, ETAs, and availability are illustrative demo data, not live GPS or verified station results. This is a demonstration prototype, not a live battery station:
- No real payment processing
- No secure server-side PIN storage or authentication
- No cross-device inventory synchronization or true timer/automatic expiry
- No physical kiosk, door lock, battery-management system, or charging control connected

Before any real-world use, add a backend/database, authentication, payment provider, secure kiosk-controller API, validated battery compatibility and telemetry, and professionally engineered electrical/thermal/mechanical safety controls.
