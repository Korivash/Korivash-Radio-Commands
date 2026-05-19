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

## How the system works

Korivash Radio is a fully self-contained broadcast and web stack running on a dedicated Windows server. Here is how everything fits together from top to bottom.

### Music source

All tracks are original MP3 files produced by Korivash. A background file watcher monitors the music folder around the clock. When a new MP3 is dropped in, the watcher automatically strips any embedded album art (so it never surfaces in browser media overlays), copies the clean file to the web server, and rebuilds the track manifest — all within a few seconds. No manual steps required.

### OBS broadcast

OBS runs on the same server and handles the entire broadcast pipeline. A custom Lua script manages the shuffle playlist directly inside OBS — it loads all MP3s at startup, performs a Fisher-Yates shuffle, plays each track through OBS's internal audio engine, and writes a small JSON file to the web server every time the song changes. This JSON file (`now-playing.json`) is the heartbeat of the whole system: every other component reads from it.

Audio goes: MP3 file → OBS internal audio → FFmpeg encoder → RTMP. No Windows audio service is involved, which means the stream works reliably on a headless server with no sound card.

### Multistream

Instead of streaming directly to one platform, OBS sends its output to a local FFmpeg relay running on the same machine. The relay duplicates the single stream and forwards it to both Twitch and YouTube simultaneously. This means OBS only encodes once and the relay handles the fan-out, keeping CPU usage lower than encoding twice.

### Web player

The public website at [music.korivash.com](https://music.korivash.com) is a static single-page app built with React 18, served over HTTPS. It polls `now-playing.json` every 3 seconds to stay in sync with what OBS is actually playing — same song, same position in the track. Visitors can listen directly in their browser without installing anything. The page is fully functional even while OBS is mid-stream.

### Visual scenes

The stream overlay uses 23 distinct visual scenes, each with its own colour palette, background art, and branding (BL00D MOON, V01D WALKER, G0LD CHA1N, etc.). A scene rotator reads `now-playing.json` and advances to the next scene on every track change, cycling through all 23 in order before repeating any. The current scene position is persisted across browser source reloads so OBS refreshes never reset the cycle mid-rotation.

### Chat bot

The Twitch bot (`@Korivash_Radio`) runs entirely inside the OBS browser source — it connects to Twitch IRC over a WebSocket, reads every chat message, and handles all commands and auto-moderation in real time. No separate bot server is needed. The bot's OAuth token is refreshed automatically by a Node.js health monitor process before it expires, so the bot stays connected indefinitely without manual re-authentication.

### Phonk Points economy

Point balances are stored in a MariaDB database, accessed through a lightweight Node.js API server running in the background. The browser source reads and writes to this API for every points transaction — earning, spending, gambling, and the leaderboard. This means point balances survive OBS restarts and browser source reloads.

### AI responses

When a viewer @mentions the bot or uses `!ask`, the message is sent to Google's Gemini API with a full personality prompt that defines the Korivash Radio voice, brand knowledge, and response style. The reply comes back in under a second and is posted to Twitch chat by the bot account. The AI has no access to the server or stream controls — it is purely a conversational layer.

### Health monitoring

A background Node.js monitor runs checks every 60 seconds: it validates the bot's OAuth token and refreshes it if it is about to expire, confirms the music watcher is still running and restarts it if not, and checks that the multistream relay process is alive and restarts it if it has crashed. This keeps the full system running unattended across reboots and unexpected failures.


---

<div align="center">

*Sleep · Study · Drive · Relax*

**[twitch.tv/korivash](https://twitch.tv/korivash) · [music.korivash.com](https://music.korivash.com) · [discord.gg/VhAj8K4C6F](https://discord.gg/VhAj8K4C6F)**

</div>
