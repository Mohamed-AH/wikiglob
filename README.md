# TerraPulse 3D — Earth's Live Vital Signs

A single-file, no-backend, real-time planetary monitor rendered on a 3D globe in
the browser. Every marker on the globe is real data — no simulated demo traffic.

## What it shows

- **Live earthquakes** — streamed from the [USGS earthquake feed](https://earthquake.usgs.gov/earthquakes/feed/)
  (no API key required). The last 24 hours load on open, then the feed is polled
  every minute for new events, plotted at their true latitude/longitude.
  - Ripple + marker for every quake
  - Amber alert for M4.5+, with a shareable card and "since last M4.5+" timer
  - Vertical beam + camera lock + screen shake for M6+
  - Red "MAJOR" styling for M7+
- **Live ISS telemetry** — position, altitude, and speed from
  [wheretheiss.at](https://wheretheiss.at/), updated every 5 seconds, with an
  orbit trail.
- **Humanity's vital counters** — births/deaths/net growth today and estimated
  world population, computed from UN birth/death rate estimates (clearly
  labeled as estimates; the seismic and ISS data above are real).

## Sharing

Every M4.5+ earthquake surfaces a share row:

- **Share on 𝕏** — opens a pre-filled tweet with the magnitude, location, and a
  link to the official USGS event page.
- **Save Card** — downloads a 1200×675 PNG summary card (magnitude, location,
  depth, timestamp, seismogram-style trace) suitable for posting anywhere.

## Running it

It's a static HTML file with no build step and no server-side code.

```
open index.html
```

or serve it with any static file server:

```
python3 -m http.server 8000
```

All data comes from free, public, CORS-enabled APIs called directly from the
browser:

| Source | Used for |
|---|---|
| `earthquake.usgs.gov` | Live + backfill earthquake feed |
| `api.wheretheiss.at` | ISS position, altitude, velocity |
| `cdn.tailwindcss.com`, Google Fonts, Font Awesome, three.js (via CDN) | UI/rendering |

## Roadmap

See [`VIRAL_ROADMAP.md`](./VIRAL_ROADMAP.md) for shipped growth features and
next bets (deep links, a "how close was this quake to you" localizer, an
auto-posting bot account, streamer mode, additional live layers like
wildfires/volcanoes).
