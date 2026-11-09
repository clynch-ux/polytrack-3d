# Lowpoly Lap and Skylight Weather

This repository includes a 3D low-poly time-trial racing game and a separate weather dashboard.

## Weather dashboard

Open [`weather.html`](weather.html) in a browser, or serve this folder locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/weather.html`. Search for a city or use the location button. The dashboard shows current conditions, the next 12 hours, a 7-day forecast, temperature units, wind, humidity, precipitation, and sunrise/sunset. It fetches live data from the public [Open-Meteo API](https://open-meteo.com/) and does not require an API key. Browser geolocation requires permission and a secure context (localhost or HTTPS).

## 3D racing game

Open [`index.html`](index.html) in a browser. If your browser blocks ES modules from `file://`, run the local server above and visit `http://localhost:8000/`.

Controls: W / Up to accelerate, S / Down to brake, A / D or Left / Right to steer, Space to boost/drift, and R to restart.

The game and weather page can each be published via GitHub Pages from the repository root.
