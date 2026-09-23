# Offline Flight Tracker

This is a self-contained offline version of the Flight Tracker.

Important:
- The tracker calculates distance/bearing locally.
- GPS location comes from the phone's location hardware.
- After the page has been installed/cached once, the app assets do not require internet.
- Airplane Mode can be used for GPS tracking if Location Services remain enabled on the phone.
- iPhone Safari generally requires a secure web context for Service Workers and reliable browser geolocation, so the recommended installation method is to serve this folder once over HTTPS and add it to the Home Screen.
