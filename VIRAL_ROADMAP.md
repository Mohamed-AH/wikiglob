# TerraPulse 3D — a new idea: Earth's live vital signs

The pivot: from tracking one asset (BTC whales) to tracking **the planet itself**.
TerraPulse is a real-time planetary monitor — every earthquake on Earth as it happens
(live USGS feed, plotted at true coordinates), the ISS orbiting live, and humanity's
vital counters ticking. No API keys, no backend, one HTML file.

## Why this can go viral on X

- **Earthquakes are organic viral moments.** Every M5.5+ quake trends within minutes.
  TerraPulse gives people the "I watched it hit live" post, pre-written, with a link to
  the official USGS event page for credibility.
- **It's real.** Every marker is a genuine USGS event at its true location. Real data
  screenshots get quote-tweeted; fake globes get ratioed.
- **It's a leave-it-open spectacle.** Live ISS orbit + births/deaths counters + a
  ticking "since last M4.5+" timer keep the tab open and make screen recordings
  interesting even between quakes.

## The candidate ideas that were considered

1. **TerraPulse — live planetary monitor** ← built (real data + organic news moments)
2. **Daily reflex game with a Wordle-style emoji share grid** — the most proven viral
   mechanic, but zero utility and a crowded genre.
3. **Bluesky firehose visualizer** — spectacular live data, but promoting a rival
   network's firehose on X is an awkward pitch.
4. **Space-weather / aurora alert radar** — great during solar storms, dead in between.
5. **"Your life in weeks" mortality visualizer** — one strong share, no reason to return.

## Shipped in `index.html`

1. **Live USGS earthquake feed** — 24h backfill on load, then minute-by-minute polling;
   ripples, magnitude-scaled beams, camera lock + screen shake on M6+.
2. **Live ISS telemetry** — position, altitude, speed, orbit trail (wheretheiss.at).
3. **Humanity vitals** — births/deaths/net growth today + est. world population
   (clearly labeled as UN-rate estimates; the seismic/ISS data is real).
4. **One-click "Share on 𝕏"** — pre-filled quake tweet including the official USGS
   event URL.
5. **Downloadable quake card** — 1200×675 PNG with a seismogram-style trace.
6. **Seismic audio pings** — deeper rumble for bigger quakes (WebAudio, toggle, off by
   default).
7. **Real night-lights Earth texture** with a procedural holographic fallback.

## Next growth bets

- **?quake=<id> deep links** — a shared quake links back to its card. Every share
  becomes an acquisition funnel.
- **"You felt it?" localizer** — geolocate (opt-in) and show distance to the epicenter:
  "This quake was 214 km from you." Instantly personal, instantly shareable.
- **@TerraPulse3D bot on X** — auto-posts quake cards for M5.5+ events (needs a tiny
  worker). The bot account becomes the marketing channel; the site is the landing page.
- **More vital signs** — live wildfires (NASA FIRMS), volcano advisories, hurricane
  tracks in season. Each layer is another audience.
- **Streamer mode** — chrome-free fullscreen for 24/7 "Earth watch" live streams.
