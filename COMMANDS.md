<div align="center">

# 📻 Korivash Radio — Chat Commands

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
| `!request [keyword]` | Find a track matching a keyword — e.g. `!request dark` |
| `!songlist` | All track names + link to site |
| `!playlist` | Same as `!songlist` |

---

## 📡 Channel Info

| Command | What it does |
|---|---|
| `!discord` | Discord invite link |
| `!website` | music.korivash.com — listen live in your browser |
| `!socials` | Discord + website in one message |
| `!uptime` | How long the stream has been live |
| `!lore` | A random piece of Korivash Radio lore |
| `!commands` | Posts a link to this page |

---

## 💰 Phonk Points

Earn points just by hanging out. Spend them to affect the live stream.

| How to earn | Amount |
|---|---|
| Chat activity (automatic) | **+10 pts** every 5 minutes |
| `!claim` — daily bonus | **+50 pts** once per day |
| `!lurk` | **+5 pts** |
| `!hype` | **+2 pts** per use |

### 🏆 Ranks

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

> Risk your Phonk Points for a chance to multiply them. 10s cooldown per user.

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

## ⚔️ Duel

Challenge another viewer to a Phonk Points battle.

| Command | What it does |
|---|---|
| `!duel @user amount` | Challenge someone — they have 60s to respond |
| `!accept` | Accept the duel — coin flip decides winner |
| `!decline` | Turn down the duel |

> Winner takes the full pot. One pending duel at a time.

---

## 🎉 Giveaway

| Command | Who | What it does |
|---|---|---|
| `!giveaway start` | Mods | Opens the giveaway |
| `!giveaway pick` | Mods | Picks a random winner |
| `!giveaway end` | Mods | Closes without picking |
| `!enter` | Everyone | Enter the active giveaway |

---

## 🔥 Engagement

| Command | What it does |
|---|---|
| `!hype` | +1 to the hype meter. At **15 votes** the overlay flashes. Earns **+2 pts**. |
| `!vibe` | Posts a random phonk atmosphere line |
| `!fire` | Vote the current track 🔥 fire — tally shown in chat |
| `!trash` | Vote the current track 💀 trash — tally shown in chat |
| `!lurk` | Acknowledge your lurk + earn **+5 pts** |

> `!fire` / `!trash` — once per track per viewer · resets when the song changes  
> `!hype` — 60s cooldown per user · meter resets 3s after hitting 15

---

## 📖 Quotes

| Command | Who | What it does |
|---|---|---|
| `!addquote [text]` | Mods | Save a quote to the library |
| `!quote` | Everyone | Pull a random quote |
| `!quote [id]` | Everyone | Pull a specific quote by number |
| `!delquote [id]` | Mods | Delete a quote |

---

## 🎵 Track Rating

Vote on the current track. One vote / one rating per user per song — resets when the track changes.

| Command | Cooldown | What it does |
|---|---|---|
| `!fire` | once per track | Vote 🔥 fire |
| `!mid` | once per track | Vote 😐 mid |
| `!trash` | once per track | Vote 💀 trash |
| `!rate [1-10]` | 30s per user | Give a numeric score — running average shown in chat |

---

## 🌙 Vibe Commands

Bot replies with a random on-brand line from each category. 15s global cooldown each.

| Command | Vibe |
|---|---|
| `!vibe` | General atmosphere |
| `!bass` | Bass-focused |
| `!nightdrive` | Night drive mode |
| `!anime` | Anime arc energy |
| `!rage` | Full send mode |
| `!chill` | Low tempo, high feeling |
| `!scene` | Cinematic one-liner (30s cooldown) |

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

## 💥 Overlay Effects

Spend Phonk Points to affect the live stream visually. 120s cooldown per user.

| Command | Cost | Effect |
|---|---|---|
| `!glitch` | **100 pts** | Scanline glitch for 3 seconds |
| `!rain` | **50 pts** | Neon rain on screen for 30 seconds |

---

## 🔧 Custom Commands

Mods can build custom bot responses on the fly. Supports `{user}` to mention the person who typed the command.

| Command | What it does |
|---|---|
| `!addcom !name response` | Create a new command |
| `!editcom !name new response` | Update an existing command |
| `!delcom !name` | Delete a command |

---

## 🛡️ Moderation

The bot auto-moderates chat 24/7. **Mods, VIPs, and subs are fully exempt.**

### Auto-Filters

| Filter | Trigger |
|---|---|
| Link filter | Any URL not on the approved whitelist — catches bare domains (`example.com`) and `www.` prefixes in addition to `https://` |
| Caps filter | Message >70% caps (12+ chars) |
| Symbol/emoji spam | Message >50% symbols or emojis |
| Long message | Over 300 characters |
| Repeat spam | Same or near-duplicate message (>80% word overlap with last 3 messages) |
| Banned words | Configurable blocked phrases — managed at runtime via `!addbanword` / `!removebanword` |
| Rate limiting | >5 messages/60s → soft warning · >8 messages/60s → timeout |
| Zalgo / Unicode abuse | Excessive combining characters (>5) — detects zalgo text and Unicode spam |
| First-message link | New viewer's very first message containing a link → instant 5-minute timeout (skips warning) |

**Approved domains (always allowed):**
`twitch.tv` · `discord.gg` · `music.korivash.com` · `korivash.com` · `youtube.com` · `youtu.be` · `imgur.com` · `clips.twitch.tv`

### Escalating Punishments

| Strike | Action |
|---|---|
| 1st | ⚠️ Warning in chat — message deleted |
| 2nd | ⏱️ **5-minute** timeout — message deleted |
| 3rd | ⏱️ **1-hour** timeout — message deleted |
| 4th | 🔨 Permanent ban |

> **First-message link exception:** A brand-new viewer posting a link on their very first message goes directly to Strike 2 (5-minute timeout), bypassing the warning.

### Mod Commands

| Command | Who | What it does |
|---|---|---|
| `!permit @user` | Mods | Allow a user to post one link for 60 seconds |
| `!resetoffenses @user` | Mods | Clear a user's strike count |
| `!offenses @user` | Mods | Check a user's current strike count without resetting |
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
| `!shoutout @user` | Mods | Shoutout another streamer with their link |
| `!so @user` | Mods | Shorthand for `!shoutout` |

> **Banned words persist** in localStorage across browser sessions. They are lost only if the OBS browser source is cleared or reset.

---

## ⚙️ Automatic Features

- **Auto-announcements** — Rotating message every hour: Discord · website · support info
- **Raid alerts** — Overlay banner + welcome message for incoming raids
- **Sub & cheer alerts** — On-screen banner; name added to the live supporter strip
- **Passive points** — 10 pts every 5 minutes for active chatters
- **Auto-moderation** — Filters run 24/7, no mod input required

---

## 📝 Notes

| Term | Meaning |
|---|---|
| **Global cooldown** | One person triggers it for everyone |
| **Per user cooldown** | Each viewer has their own independent timer |
| **Sub exempt** | Subs bypass all auto-filters and can post whitelisted links freely |

- Phonk Points persist across streams but reset if the browser source is cleared
- Strike counts persist in localStorage and survive OBS restarts (reset only if browser source is cleared)
- Banned words persist in localStorage — use `!banwords` to see the current active list
- Duel expires after 60 seconds if the challenged user doesn't respond
- Rate limit windows are rolling 60-second windows, not per-minute buckets

---

<div align="center">

*24/7 Night Drive Radio · DMCA-Free · All music by Korivash*

**[twitch.tv/korivash](https://twitch.tv/korivash) · [music.korivash.com](https://music.korivash.com) · [discord.gg/VhAj8K4C6F](https://discord.gg/VhAj8K4C6F)**

</div>
