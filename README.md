# Prayer

A lightweight Arabic prayer tracking web app for recording daily prayers using either GPS mosque verification or AI-based video analysis.

## Features
- Track five daily prayers: Fajr, Dhuhr, Asr, Maghrib, and Isha
- Verify attendance using live GPS location near a saved mosque
- Verify attendance using uploaded prayer video and PoseNet-based analysis
- Save progress in localStorage for the current day
- View detailed verification info and media for each prayer

## Run locally
1. Open `index.html` in a browser.
2. Allow browser access to geolocation if using GPS verification.
3. Click the prayer card you want to verify and choose a verification method.

## Notes
- This app is a static front-end project and does not require a backend.
- The AI verification path uses TensorFlow.js and PoseNet in-browser.
