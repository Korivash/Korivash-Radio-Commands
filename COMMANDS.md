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
| Link filter | Any URL not on the approved whitelist |
| Caps filter | Message >70% caps (12+ chars) |
| Symbol/emoji spam | Message >50% symbols or emojis |
| Long message | Over 300 characters |
| Repeat spam | Same message sent twice in a row |
| Banned words | Configurable blocked phrases |

**Approved domains (always allowed):**
`twitch.tv` · `discord.gg` · `music.korivash.com` · `korivash.com` · `youtube.com` · `youtu.be` · `imgur.com` · `clips.twitch.tv`

### Escalating Punishments

| Strike | Action |
|---|---|
| 1st | ⚠️ Warning in chat — message deleted |
| 2nd | ⏱️ 60-second timeout — message deleted |
| 3rd | ⏱️ 10-minute timeout — message deleted |
| 4th | 🔨 Permanent ban |

### Mod Commands

| Command | What it does |
|---|---|
| `!permit @user` | Allow a user to post one link for 60 seconds |
| `!resetoffenses @user` | Clear a user's strike count |
| `!timeout @user [s]` | Timeout a user (default 600s) |
| `!ban @user [reason]` | Permanently ban a user |
| `!unban @user` | Remove a ban |
| `!slow [seconds]` | Enable slow mode (default 30s) |
| `!slowoff` | Disable slow mode |
| `!subonly` | Subscriber-only mode on |
| `!subnonly` | Subscriber-only mode off |
| `!emoteonly` | Emote-only mode on |
| `!emoteonlyoff` | Emote-only mode off |
| `!clear` | Delete all messages in chat |
| `!shoutout @user` | Shoutout another streamer with their link |
| `!so @user` | Shorthand for `!shoutout` |

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
- Strike counts reset with each browser session (OBS restart)
- Duel expires after 60 seconds if the challenged user doesn't respond

---

<div align="center">

*24/7 Night Drive Radio · DMCA-Free · All music by Korivash*

**[twitch.tv/korivash](https://twitch.tv/korivash) · [music.korivash.com](https://music.korivash.com) · [discord.gg/VhAj8K4C6F](https://discord.gg/VhAj8K4C6F)**

</div>
