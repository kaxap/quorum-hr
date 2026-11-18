# Quorum

A single-page heart-rate app for the Bluefy browser on iOS. It reads five Bluetooth heart-rate sensors at once (Whoop, Coros arm band, Wahoo Trackr, Garmin strap, Powerbeats Pro 2) and shows their median, with a free workout mode and a guided 4×4 Norwegian interval mode.

Open https://kaxap.github.io/quorum-hr/ in Bluefy.

- Everything is in `index.html`. No server, no network requests, no tracking.
- Personal numbers (weight, height, age, max heart rate, zones) are entered on first use and stay in the browser.
- Speed and distance from the phone's GPS are optional: a switch on the start sheet of each workout, off by default. Positions stay on the phone.
- Add `#demo` to the address to try it with simulated sensors.

Current build: 8. The same number is shown at the bottom of the app's Settings.
