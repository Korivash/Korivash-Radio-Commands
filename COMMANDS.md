<div align="center">

# Korivash Radio — Chat Commands

**All commands work in Twitch chat · Responses posted by [@Korivash_Radio](https://twitch.tv/korivash)**

[![Twitch](https://img.shields.io/badge/Watch_Live-twitch.tv%2Fkorivash-9146FF?style=for-the-badge&logo=twitch&logoColor=white)](https://twitch.tv/korivash)
[![Listen](https://img.shields.io/badge/Listen_Live-music.korivash.com-FF2BB8?style=for-the-badge&logo=headphones&logoColor=white)](https://music.korivash.com)
[![Discord](https://img.shields.io/badge/Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/VhAj8K4C6F)

</div>

---

## 🎵 Music

| Command | What it does |
|---|---|
| `!np` | Current song — pulses the Now Playing bar on stream |
| `!nowplaying` | Same as `!np` |
| `!song` | Same as `!np` |
| `!queue` | Next 5 tracks coming up |

---

## 📡 Channel Info

| Command | What it does |
|---|---|
| `!discord` | Discord invite link |
| `!website` | music.korivash.com — listen live in your browser |
| `!socials` | Discord + website in one message |
| `!uptime` | How long the stream has been live |
| `!lore` | A random piece of Korivash Radio lore |
| `!commands` | Post this command list in chat |

---

## 💰 Phonk Points

Earn points just by hanging out. Spend them to affect the live stream.

| How to earn | Amount |
|---|---|
| Chat activity (automatic) | **+10 pts** every 5 minutes |
| `!claim` — daily bonus | **+50 pts** once per day |
| `!lurk` | **+5 pts** |
| `!hype` | **+2 pts** per use |

### Ranks

| Rank | Points needed |
|---|---|
| Listener | 0 |
| Night Rider | 100 |
| Phonk Drifter | 500 |
| Neon Ghost | 1,500 |
| Phonk God | 5,000 |

### Points Commands

| Command | What it does |
|---|---|
| `!points` | Check your balance |
| `!rank` | Your rank + pts to next tier |
| `!leaderboard` | Top 5 point holders |
| `!claim` | Claim your daily 50pt bonus |
| `!give @user amount` | Gift points to another viewer |

---

## 🎲 Gambling

> Risk your Phonk Points for a chance to multiply them. 10s per-user cooldown.

### `!gamble [amount]`
Coin flip — **Win = 2×** your bet · Lose = gone

### `!slots [amount]`
3-reel slot machine · Symbols: 🎵 🔥 💀 ⚡ 🌙 👾

| Result | Payout |
|---|---|
| 3 matching symbols | **5× — Jackpot!** |
| 2 matching symbols | **2×** |
| No match | **0 — lose bet** |

---

## 🔥 Engagement

| Command | What it does |
|---|---|
| `!hype` | +1 to the hype meter. At **15 votes** the overlay flashes. Earns **+2 pts**. |
| `!fire` | Vote the current track 🔥 fire |
| `!mid` | Vote the current track 😐 mid |
| `!trash` | Vote the current track 💀 trash |
| `!rate [1-10]` | Give the current track a numeric score — running average shown in chat |
| `!lurk` | Acknowledge your lurk + earn **+5 pts** |

> `!fire` / `!mid` / `!trash` — once per track per viewer · resets when the song changes
> `!rate` — 30s per-user cooldown · resets when the song changes
> `!hype` — 60s per-user cooldown · meter resets 3s after hitting 15

---

## 🌙 Vibe Commands

Bot replies with a random on-brand line. 15s global cooldown (30s for `!scene`).

| Command | Vibe |
|---|---|
| `!vibe` | General phonk atmosphere |
| `!bass` | Bass-focused energy |
| `!nightdrive` | Night drive mode |
| `!anime` | Anime arc energy |
| `!rage` | Full send mode |
| `!chill` | Low tempo, high feeling |
| `!scene` | Cinematic one-liner |

---

## 💥 Overlay Effects

Spend Phonk Points to affect the live stream visually. 120s per-user cooldown.

| Command | Cost | Effect |
|---|---|---|
| `!glitch` | **100 pts** | Scanline glitch overlay for 3 seconds |
| `!rain` | **50 pts** | Neon rain on screen for 30 seconds |

---

## 📱 Socials

| Command | What it does |
|---|---|
| `!discord` | Discord invite |
| `!website` | music.korivash.com |
| `!socials` | Discord + website |
| `!youtube` | YouTube channel link |
| `!tiktok` | TikTok link |
| `!spotify` | Spotify link |

---

## 🤖 AI Chat

| Command | Cooldown | What it does |
|---|---|---|
| `@Korivash_Radio [question]` | 30s global | Ask the bot anything — answers in Korivash Radio style |
| `!ask [question]` | 30s global | Same as @mentioning the bot |

> Powered by Gemini 2.5 Flash. The bot has full personality context — ask about the music, phonk culture, or anything stream-related.

---

## 🛡️ Moderation

The bot auto-moderates chat 24/7. **Mods, VIPs, and subs are fully exempt from all filters.**

### Auto-Filters

| Filter | Trigger |
|---|---|
| Link filter | Any URL not on the approved whitelist — catches `https://`, `www.`, and bare domains like `example.com` |
| Caps filter | Message >70% capital letters (12+ chars) |
| Symbol/emoji spam | Message >50% symbols or emojis |
| Long message | Over 300 characters |
| Repeat spam | Near-duplicate message (>80% word overlap with last 3 messages) |
| Banned words | Runtime-configurable blocked phrases |
| Rate limiting | >5 messages/60s → soft warning · >8 messages/60s → moderation action |
| Zalgo / Unicode abuse | Excessive combining characters (>5) — catches zalgo text and Unicode spam |
| First-message link | Brand-new viewer's very first message containing a link → instant 5-minute timeout (skips warning step) |

**Approved domains (always allowed for everyone):**
`twitch.tv` · `discord.gg` · `music.korivash.com` · `korivash.com` · `youtube.com` · `youtu.be` · `imgur.com` · `clips.twitch.tv`

### Escalating Punishments

| Strike | Action |
|---|---|
| 1st | ⚠️ Warning in chat — message deleted |
| 2nd | ⏱️ **5-minute** timeout — message deleted |
| 3rd | ⏱️ **1-hour** timeout — message deleted |
| 4th | 🔨 Permanent ban |

> **First-message link exception:** A brand-new viewer posting a link on their very first message skips Strike 1 and goes directly to Strike 2 (5-minute timeout). This targets raid bots that always post links on their first message.

### Mod Commands

| Command | Who | What it does |
|---|---|---|
| `!permit @user` | Mods | Allow a user to post one link freely for 60 seconds |
| `!resetoffenses @user` | Mods | Clear a user's strike count |
| `!offenses @user` | Mods | Check a user's strike count without resetting it |
| `!addbanword <phrase>` | Mods | Add a word or phrase to the live banned-word list |
| `!removebanword <phrase>` | Mods | Remove a word or phrase from the banned-word list |
| `!banwords` | Mods | List all currently active banned words |
| `!timeout @user [s]` | Mods | Timeout a user (default 600s) |
| `!ban @user [reason]` | Mods | Permanently ban a user |
| `!unban @user` | Mods | Remove a ban |
| `!slow [seconds]` | Mods | Enable slow mode (default 30s) |
| `!slowoff` | Mods | Disable slow mode |
| `!subonly` | Mods | Subscriber-only mode on |
| `!subnonly` | Mods | Subscriber-only mode off |
| `!emoteonly` | Mods | Emote-only mode on |
| `!emoteonlyoff` | Mods | Emote-only mode off |
| `!clear` | Mods | Delete all messages in chat |
| `!shoutout @user` | Mods | Shoutout another streamer with their channel link |
| `!so @user` | Mods | Shorthand for `!shoutout` |

> Banned words persist in localStorage across browser sessions. They reset only if the OBS browser source is fully cleared.

---

## ⚙️ Automatic Features

These run on their own — no commands needed.

| Feature | How it works |
|---|---|
| **Auto now-playing** | Bot posts the current song name in chat each time the track changes |
| **Hype messages** | Random phonk hype line posted every 5–8 minutes |
| **Chat questions** | Random engagement question posted every 10–15 minutes |
| **Soft promo** | Rotating Discord/website mention every 20–30 minutes |
| **Auto-announcements** | Hourly message rotating through: Discord · website · support info |
| **Raid alerts** | Overlay banner + welcome message for incoming raids |
| **Sub & cheer alerts** | On-screen banner; name added to the live supporter strip |
| **Passive points** | +10 pts every 5 minutes for active chatters |

---

## 📝 Glossary

| Term | Meaning |
|---|---|
| **Global cooldown** | One person triggers it for the whole chat |
| **Per-user cooldown** | Each viewer has their own independent timer |
| **Sub exempt** | Subs bypass all auto-filters and can post links from the whitelist freely |

- Phonk Points persist across streams but reset if the OBS browser source is cleared
- Strike counts are in-memory — they reset on OBS browser source reload
- `!fire` / `!mid` / `!trash` / `!rate` votes all reset when the track changes
- The hype meter resets 3 seconds after reaching 15

---

## 🚧 Coming Soon

Features in development — not yet live.

| Feature | Status |
|---|---|
| `!duel @user amount` — viewer vs viewer Phonk Points battle | In progress |
| `!giveaway start/pick/end` + `!enter` — mod-run giveaways | In progress |
| `!addquote` / `!quote` — save and recall memorable moments | Planned |
| `!request [track]` — request a song from the playlist | Planned |
| `!watchtime` — see how long you've been watching | Planned |
| `!streak` — daily login streak with bonus points | Planned |
| YouTube chat commands | Pending YouTube API review |

---

<div align="center">

*24/7 Night Drive Radio · DMCA-Free · All music by Korivash*

**[twitch.tv/korivash](https://twitch.tv/korivash) · [music.korivash.com](https://music.korivash.com) · [discord.gg/VhAj8K4C6F](https://discord.gg/VhAj8K4C6F)**

</div>
