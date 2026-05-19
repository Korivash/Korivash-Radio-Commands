<div align="center">

# Korivash Radio — Chat Commands

**All commands work in Twitch chat · Responses posted by [@Korivash_Radio](https://twitch.tv/korivash)**

[![Twitch](https://img.shields.io/badge/Watch_Live-twitch.tv%2Fkorivash-9146FF?style=for-the-badge&logo=twitch&logoColor=white)](https://twitch.tv/korivash)
[![Listen](https://img.shields.io/badge/Listen_Live-music.korivash.com-FF2BB8?style=for-the-badge&logo=headphones&logoColor=white)](https://music.korivash.com)
[![Discord](https://img.shields.io/badge/Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/VhAj8K4C6F)

</div>

---

## 🎵 Music

| Command | Cooldown | What it does |
|---|---|---|
| `!np` | 30s global | Current song — pulses the Now Playing bar on stream |
| `!nowplaying` | 30s global | Same as `!np` |
| `!song` | 30s global | Same as `!np` |
| `!queue` | 30s global | Next 5 tracks in the OBS shuffle queue |
| `!tracks` | 30s global | How many tracks are in the current rotation |
| `!songlist` | 30s global | Full track list posted in chat |
| `!playlist` | 30s global | Same as `!songlist` |

---

## 🎧 Song Requests

Viewers can request a specific track from the playlist. Costs 200 points.

| Command | What it does |
|---|---|
| `!tracks` | Shows how many tracks are available and how to request |
| `!sr [number]` | Request a track by its position number (e.g. `!sr 4`) |
| `!request [number]` | Same as `!sr` |

> Tracks are numbered in the order shown by `!songlist`. Requests go into a queue and play after the current track.

---

## 📡 Channel Info

| Command | Cooldown | What it does |
|---|---|---|
| `!discord` | 30s global | Discord invite link |
| `!website` | 30s global | music.korivash.com — listen live in your browser |
| `!socials` | 30s global | Discord + website in one message |
| `!youtube` | 30s global | YouTube channel link |
| `!tiktok` | 30s global | TikTok link |
| `!spotify` | 30s global | Spotify link |
| `!uptime` | 30s global | How long the stream has been live this session |
| `!lore` | 15s global | A random piece of Korivash Radio lore |
| `!commands` | 30s global | Quick command list posted in chat |

---

## 💰 Phonk Points

Earn points just by hanging out. Spend them to affect the live stream.

### How to earn

| Method | Amount |
|---|---|
| Be active in chat | **+10 pts** automatically every 5 minutes |
| `!claim` — daily bonus | **+50 pts** once per day |
| `!lurk` | **+5 pts** |
| `!hype` | **+2 pts** per use |
| Win a `!gamble` or `!slots` bet | Depends on amount |
| Win a `!duel` | Depends on stake |

### Ranks

| Rank | Points needed |
|---|---|
| Listener | 0 |
| Night Rider | 100 |
| Phonk Drifter | 500 |
| Neon Ghost | 1,500 |
| Phonk God | 5,000 |

### Points Commands

| Command | Cooldown | What it does |
|---|---|---|
| `!points` | 10s global | Check your balance |
| `!rank` | 10s global | Your rank + pts needed for the next tier |
| `!leaderboard` | 60s global | Top 5 point holders |
| `!top` | 60s global | Same as `!leaderboard` |
| `!claim` | per-user 24hr | Daily 50pt bonus |
| `!give @user amount` | 30s per-user | Gift points to another viewer |
| `!dedicate @user` | 30s per-user | Spend **75 pts** to dedicate the current song to someone |
| `!watchtime` | 10s global | How long you've been active in chat this session |
| `!streak` | 10s global | Your daily login streak + bonus milestones |

---

## 🎲 Gambling

Risk your Phonk Points for a chance to multiply them.

### `!gamble [amount]`
Coin flip. **Win = 2×** your bet. Lose = gone. · 10s per-user cooldown.

### `!slots [amount]`
3-reel slot machine. Symbols: 🎵 🔥 💀 ⚡ 🌙 👾 · 10s per-user cooldown.

| Result | Payout |
|---|---|
| 3 matching symbols | **5× — Jackpot!** |
| 2 matching symbols | **2×** |
| No match | **0 — bet lost** |

### `!duel @user [amount]`
Challenge another viewer to a direct Phonk Points battle. The target has 60 seconds to respond.

| Command | What it does |
|---|---|
| `!duel @user amount` | Challenge someone — locks your stake |
| `!accept` | Accept the challenge — coin flip decides the winner |
| `!decline` | Turn down the challenge |

> Both players must have enough points. Only one duel can be active at a time. Winner takes the full pot.

---

## 🔥 Engagement

| Command | Cooldown | What it does |
|---|---|---|
| `!hype` | 60s per-user | +1 to the hype meter. At **15 votes** the overlay flashes. Earns **+2 pts**. |
| `!fire` | once per track | Vote the current track 🔥 fire |
| `!mid` | once per track | Vote the current track 😐 mid |
| `!trash` | once per track | Vote the current track 💀 trash |
| `!rate [1-10]` | 30s per-user | Give the current track a numeric score — running average shown |
| `!lurk` | 1hr per-user | Go lurk + earn **+5 pts** |
| `!8ball [question]` | 10s global | Ask the magic 8-ball anything |

> `!fire` / `!mid` / `!trash` / `!rate` all reset when the track changes.
> Hype meter resets 3s after hitting 15.

---

## 🌙 Vibe Commands

Bot replies with a random on-brand line.

| Command | Cooldown | Vibe |
|---|---|---|
| `!vibe` | 15s global | General phonk atmosphere |
| `!bass` | 15s global | Bass-focused energy |
| `!nightdrive` | 15s global | Night drive mode |
| `!anime` | 15s global | Anime arc energy |
| `!rage` | 15s global | Full send mode |
| `!chill` | 15s global | Low tempo, high feeling |
| `!scene` | 30s global | Cinematic one-liner |

---

## 💥 Overlay Effects

Spend Phonk Points to affect the live stream visually. 120s per-user cooldown.

| Command | Cost | Effect | Duration |
|---|---|---|---|
| `!glitch` | **100 pts** | Scanline glitch overlay | 3 seconds |
| `!rain` | **50 pts** | Neon rain on stream | 30 seconds |
| `!dedicate @user` | **75 pts** | Dedicates the current song in chat | Instant |

---

## 🧠 Trivia

| Command | Who | What it does |
|---|---|---|
| `!trivia` | Mods (or auto-fires every 20–30 min) | Start a phonk/music trivia question in chat |
| `A` / `B` / `C` / `D` | Everyone | Answer the active trivia question |
| `!triviastop` | Mods | Cancel the current trivia question |

> Correct answers earn Phonk Points: easy = 50pts · medium = 100pts · hard = 150pts.
> Trivia also fires automatically every 20–30 minutes when the bot is connected.

---

## 🎉 Giveaway

Mod-run giveaways, random winner drawn from entries.

| Command | Who | What it does |
|---|---|---|
| `!giveaway start [prize]` | Mods only | Opens the giveaway and announces the prize |
| `!enter` | Everyone | Enter the active giveaway |
| `!giveaway pick` | Mods only | Randomly selects a winner from all entries |
| `!giveaway end` | Mods only | Closes the giveaway without picking a winner |

---

## 📝 Quotes

Save and recall memorable chat moments.

| Command | Who | What it does |
|---|---|---|
| `!addquote [text]` | Mods only | Save a quote |
| `!quote` | Everyone | Display a random saved quote |
| `!quote [number]` | Everyone | Display a specific quote by ID |
| `!delquote [number]` | Mods only | Delete a quote |

---

## ⚙️ Custom Commands

Mods can create simple text-response commands on the fly.

| Command | Who | What it does |
|---|---|---|
| `!addcom !name response` | Mods only | Create a new command (supports `{user}` variable) |
| `!editcom !name response` | Mods only | Update an existing command's response |
| `!delcom !name` | Mods only | Delete a custom command |

---

## 🤖 AI Chat

| Command | Cooldown | What it does |
|---|---|---|
| `@Korivash_Radio [question]` | 30s global | Ask the bot anything — answers in Korivash Radio voice |
| `!ask [question]` | 30s global | Same as @mentioning the bot |

> The bot has full personality context — ask about the music, phonk culture, or anything stream-related.

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
| Zalgo / Unicode abuse | Excessive combining characters — catches zalgo text and Unicode spam |
| First-message link | Brand-new viewer's very first message containing a link → instant 5-minute timeout |

**Approved domains (always allowed):**
`twitch.tv` · `discord.gg` · `music.korivash.com` · `korivash.com` · `youtube.com` · `youtu.be` · `imgur.com` · `clips.twitch.tv`

### Escalating Punishments

| Strike | Action |
|---|---|
| 1st | ⚠️ Warning in chat — message deleted |
| 2nd | ⏱️ **5-minute** timeout |
| 3rd | ⏱️ **1-hour** timeout |
| 4th | 🔨 Permanent ban |

> First-message links skip Strike 1 and go straight to Strike 2 — targets raid bots.

### Mod Commands

| Command | What it does |
|---|---|
| `!permit @user` | Allow a user to post one link freely for 60 seconds |
| `!timeout @user [seconds]` | Timeout a user (default 600s) |
| `!ban @user [reason]` | Permanently ban a user |
| `!unban @user` | Remove a ban |
| `!resetoffenses @user` | Clear a user's strike count |
| `!offenses @user` | Check a user's strike count without resetting it |
| `!addbanword <phrase>` | Add a word or phrase to the live banned-word list |
| `!removebanword <phrase>` | Remove a word or phrase from the banned-word list |
| `!banwords` | List all currently active banned words |
| `!slow [seconds]` | Enable slow mode (default 30s) |
| `!slowoff` | Disable slow mode |
| `!subonly` | Subscriber-only mode on |
| `!subnonly` | Subscriber-only mode off |
| `!emoteonly` | Emote-only mode on |
| `!emoteonlyoff` | Emote-only mode off |
| `!clear` | Delete all messages in chat |
| `!shoutout @user` / `!so @user` | Shoutout another streamer with their channel link |

---

## ⚙️ Automatic Features

These run on their own — no commands needed.

| Feature | Behavior |
|---|---|
| **Auto now-playing** | Bot posts the current track in chat on every song change |
| **Now Playing card** | Center-screen card shows the track name + mood description for 5 seconds on each change |
| **Hype messages** | Random phonk line posted every 5–8 minutes |
| **Chat questions** | Engagement question posted every 10–15 minutes |
| **Soft promo** | Rotating Discord/website mention every 20–30 minutes |
| **Hourly announcements** | Rotating: Discord · website · support info |
| **Auto-trivia** | Trivia question fires every 20–30 minutes when no question is active |
| **Follow alerts** | On-screen banner when someone new follows |
| **Raid alerts** | Overlay banner + welcome message in chat for incoming raids |
| **Sub & cheer alerts** | On-screen banner; name added to the live supporter strip |
| **Passive points** | +10 pts every 5 minutes for active chatters |

---

## 📝 Glossary

| Term | Meaning |
|---|---|
| **Global cooldown** | One person triggers it for the whole chat |
| **Per-user cooldown** | Each viewer has their own independent timer |
| **Sub exempt** | Subs bypass all auto-filters |

**Notes:**
- Phonk Points persist across streams but reset if the OBS browser source is fully cleared
- Strike counts reset on OBS browser source reload (in-memory only)
- `!fire` / `!mid` / `!trash` / `!rate` votes all reset when the track changes
- Hype meter resets 3 seconds after reaching 15
- Custom commands and banned words persist in localStorage

---

<div align="center">

*24/7 Night Drive Radio · DMCA-Free · All music by Korivash*

**[twitch.tv/korivash](https://twitch.tv/korivash) · [music.korivash.com](https://music.korivash.com) · [discord.gg/VhAj8K4C6F](https://discord.gg/VhAj8K4C6F)**

</div>
