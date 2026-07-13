# WhalePulse 3D — Viral Growth Roadmap for X.com

The core insight: **every whale transaction is a natural tweet moment.** The app's job
is to turn each of those moments into something a viewer can post in one click, and to
give people a reason to keep the tab open (and screen-record it) while they wait.

## ✅ Shipped (in `index.html`)

1. **One-click "Share on 𝕏" button** — appears on every whale/mega-whale alert with a
   pre-filled hype tweet (amount, USD value, hashtags). This is the viral loop: every
   whale event becomes a potential tweet, written for the user.
2. **Downloadable Whale Card** — a 1200×675 (X-optimized 16:9) PNG generated on canvas:
   big BTC amount, USD value, txid, timestamp, WhalePulse branding. Screenshot-quality
   content with zero effort.
3. **"Since last whale" ticker** — anticipation/FOMO. People keep the tab open, streamers
   leave it on screen, viewers screen-record the moment the timer resets.
4. **Sonar ping audio** (WebAudio, no assets, off by default) — deeper ping for mega
   whales. Makes screen recordings dramatically more shareable.
5. **Open Graph / Twitter Card meta tags** — the link unfurls as a proper card when
   shared on X instead of a bare URL.

## 🔜 High-leverage next steps (no backend needed)

6. **Session records + "you witnessed" framing** — "Largest whale you've witnessed:
   1,204 BTC" with its own share button. Bragging rights are the oldest viral mechanic.
7. **Replay mode / GIF moment** — after a mega whale, offer "replay the beam" so people
   can screen-record the exact 4-second money shot.
8. **Milestone toasts** — "🔥 10th whale this hour — the ocean is boiling" with share
   button. Turns aggregate activity into narrative.
9. **?tx= deep links** — sharing a whale links back to the app with that whale's card
   pre-loaded, so every share is also an acquisition funnel.
10. **Streamer mode** — hide HUD chrome, giant alert overlays, for crypto streamers and
    24/7 "whale watch" YouTube/X live streams. One big streamer = thousands of installs.

## 🔭 Bigger bets (need a tiny backend or bot)

11. **@WhalePulse3D alert bot on X** — auto-posts mega whale cards in real time. The bot
    account *is* the marketing channel; the site is the landing page.
12. **Live viewer count** — "🔴 2,431 watching the mempool right now" (needs a
    websocket presence server). Social proof + event feeling.
13. **Daily "Whale Report" auto-thread** — top 5 whales of the day as a card thread,
    posted at a fixed time so people expect it.
14. **Prediction mini-game** — "will a 500+ BTC whale surface in the next 10 minutes?"
    Tap to vote, share your streak. Zero-money gamification, huge retention.
