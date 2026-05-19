<div align="center">

# Korivash Radio

### 24/7 Dark Phonk · Night Drive · DMCA-Free

*All music produced by Korivash · Stream freely, no mutes, no takedowns*

<br>

[![Watch Live](https://img.shields.io/badge/Watch_Live-twitch.tv%2Fkorivash-9146FF?style=for-the-badge&logo=twitch&logoColor=white)](https://twitch.tv/korivash)
[![Listen in Browser](https://img.shields.io/badge/Listen_Live-music.korivash.com-FF2BB8?style=for-the-badge&logo=headphones&logoColor=white)](https://music.korivash.com)
[![Join Discord](https://img.shields.io/badge/Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/VhAj8K4C6F)

</div>

---

## What is Korivash Radio?

Korivash Radio is a live 24/7 dark phonk and night drive radio stream on Twitch. Every track is original music produced by Korivash — fully DMCA-free. Play it in the background while you stream, study, drive, or sleep.

- **Original music only** — no copyright claims, no mutes, ever
- **Listen anywhere** — full browser player at [music.korivash.com](https://music.korivash.com)
- **Interactive chat** — earn points, vote on tracks, trigger live stream effects
- **Fully moderated** — automated filters keep chat clean around the clock
- **Always on** — 24/7 shuffle playlist, multiple visual scenes, no gaps, no restarts

---

## Quick Links

| | Link |
|---|---|
| Watch live | [twitch.tv/korivash](https://twitch.tv/korivash) |
| Listen in browser | [music.korivash.com](https://music.korivash.com) |
| Full command list | [COMMANDS.md](./COMMANDS.md) |
| Viewer guide (non-tech) | [VIEWER-GUIDE.md](./VIEWER-GUIDE.md) |
| Discord | [discord.gg/VhAj8K4C6F](https://discord.gg/VhAj8K4C6F) |

---

## Chat Bot — Korivash_Radio

The bot account **@Korivash_Radio** handles all chat responses, moderation, and interactive features. It runs 24/7 alongside the stream.

### What the bot does

- Responds to commands from any viewer
- Auto-moderates chat (link filter, caps, spam, zalgo, rate limiting)
- Runs the Phonk Points economy (earn, spend, gamble, leaderboard)
- Posts automatic messages (now-playing announcements, hype lines, promo)
- Handles raid welcomes, sub alerts, and cheer alerts
- Uses Gemini AI to answer questions in the Korivash Radio voice

### Key commands

| Command | What it does |
|---|---|
| `!np` | Current song name |
| `!queue` | Next 5 tracks |
| `!points` | Your Phonk Points balance |
| `!claim` | Daily 50pt bonus |
| `!hype` | Hype the stream |
| `!gamble [amount]` | Coin flip bet |
| `!slots [amount]` | Slot machine |
| `!glitch` | 100pts — scanline effect on stream |
| `!rain` | 50pts — neon rain on stream |
| `@Korivash_Radio` | Ask the AI anything |

**[→ Full command list](./COMMANDS.md)**

---

## Phonk Points

Everyone earns points automatically just by being in chat. Spend them on stream effects or gamble them.

| How to earn | Amount |
|---|---|
| Be active in chat | +10 pts every 5 minutes |
| `!claim` daily bonus | +50 pts once per day |
| `!lurk` | +5 pts |
| `!hype` | +2 pts |

### Ranks

| Rank | Points |
|---|---|
| Listener | 0 |
| Night Rider | 100 |
| Phonk Drifter | 500 |
| Neon Ghost | 1,500 |
| Phonk God | 5,000 |

---

## Auto-Moderation

The bot moderates 24/7. **Mods, VIPs, and subs are fully exempt.**

### Filters

- **Link filter** — blocks URLs not on the approved whitelist
- **Caps filter** — messages >70% capital letters
- **Spam filter** — repeat messages, symbol spam, emoji spam
- **Rate limiter** — flags users sending 5+ messages per minute, actions at 8+
- **Zalgo / Unicode abuse** — detects text manipulation
- **Banned words** — runtime-configurable via `!addbanword`
- **First-message links** — new viewer posting a link on their very first message → instant 5-minute timeout

### Punishment ladder

| Strike | Action |
|---|---|
| 1st | Warning + message deleted |
| 2nd | 5-minute timeout |
| 3rd | 1-hour timeout |
| 4th | Permanent ban |

### Approved domains (always allowed)

`twitch.tv` · `discord.gg` · `music.korivash.com` · `korivash.com` · `youtube.com` · `youtu.be` · `imgur.com` · `clips.twitch.tv`

---

## Automatic Features

All of these run with no input required.

| Feature | Behavior |
|---|---|
| Auto now-playing | Posts current song name in chat on every track change |
| Hype messages | Random phonk hype line every 5–8 minutes |
| Chat questions | Engagement question every 10–15 minutes |
| Soft promo | Discord/website mention every 20–30 minutes |
| Hourly announcements | Rotating: Discord · website · support info |
| Raid welcome | Overlay banner + chat message for incoming raids |
| Sub/cheer alerts | On-screen banner + name added to supporter strip |
| Passive points | +10 pts to active chatters every 5 minutes |

---

## Architecture (for developers)

- **No build step** — React 18 + Babel Standalone loaded from CDN, JSX transpiled in-browser
- **IIS static site** — `C:\inetpub\music.korivash.com\`
- **Source files** — `C:\Users\Administrator\Desktop\Twitch Scenes\`
- **Audio** — OBS Media Source (ffmpeg) → Twitch RTMP. Browser audio only on the public website.
- **Bot** — Twitch IRC via WebSocket inside the OBS browser source (app.jsx)
- **Points API** — Node.js + MariaDB, PM2 process `points-api`
- **Bot monitor** — Node.js, PM2 process `bot-monitor` (token refresh, watcher health, relay health)
- **Multistream** — FFmpeg RTMP relay → Twitch + YouTube simultaneously
- **Scene rotation** — `scene-rotator.js` polls `now-playing.json` every 3s, cycles through 23 visual scenes
- **Music watcher** — `phonk-watcher.ps1` strips album art and syncs MP3s to IIS automatically


---

<div align="center">

*Sleep · Study · Drive · Relax*

**[twitch.tv/korivash](https://twitch.tv/korivash) · [music.korivash.com](https://music.korivash.com) · [discord.gg/VhAj8K4C6F](https://discord.gg/VhAj8K4C6F)**

</div>
