<div align="center">

# 📻 Korivash Radio

### 24/7 Night Drive · Phonk · Lo-Fi · DMCA-Free

*All music produced by Korivash · Stream freely, no mutes, no takedowns*

<br>

[![Watch Live](https://img.shields.io/badge/Watch_Live-twitch.tv%2Fkorivash-9146FF?style=for-the-badge&logo=twitch&logoColor=white)](https://twitch.tv/korivash)
[![Listen in Browser](https://img.shields.io/badge/Listen_Live-music.korivash.com-FF2BB8?style=for-the-badge&logo=headphones&logoColor=white)](https://music.korivash.com)
[![Join Discord](https://img.shields.io/badge/Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/VhAj8K4C6F)

</div>

---

## What is Korivash Radio?

Korivash Radio is a live 24/7 phonk and night drive radio stream on Twitch. Every track is original music produced by Korivash — fully DMCA-free. Play it in the background while you stream, study, drive, or sleep.

- 🎵 **Original music only** — no copyright claims, no mutes, ever
- 🌐 **Listen anywhere** — full browser player at [music.korivash.com](https://music.korivash.com)
- 💬 **Interactive chat** — earn points, vote on tracks, trigger live stream effects
- 🛡️ **Fully moderated** — automated filters keep chat clean around the clock
- 📡 **Always on** — 24/7 shuffle playlist, no gaps, no restarts

---

## Chat Commands

All commands work in [Twitch chat](https://twitch.tv/korivash). The bot account **@Korivash_Radio** handles all responses.

---

### 🎵 Music

| Command | What it does |
|---|---|
| `!np` | Current song name — also pulses the Now Playing bar on stream |
| `!nowplaying` | Same as `!np` |
| `!queue` | Next 5 tracks coming up in the queue |

---

### 📡 Channel Info

| Command | What it does |
|---|---|
| `!discord` | Posts the Discord invite link |
| `!website` | Posts music.korivash.com — listen live in your browser |
| `!socials` | Discord + website in one message |
| `!uptime` | How long the stream has been live |
| `!lore` | A random piece of Korivash Radio lore |
| `!commands` | Posts a link to this full command list |

---

### 💰 Phonk Points

Earn points just by being here. Spend them to affect the live stream.

| How to earn | Amount |
|---|---|
| Chat activity (passive, automatic) | **+10 pts** every 5 minutes |
| `!claim` — daily login bonus | **+50 pts** once per day |
| `!lurk` — go lurk mode | **+5 pts** |
| `!hype` — hype the stream | **+2 pts** per use |

#### 🏆 Ranks

Ranks are purely cosmetic — shown when you use `!rank`.

| Rank | Points needed |
|---|---|
| Listener | 0 |
| Night Rider | 100 |
| Phonk Drifter | 500 |
| Neon Ghost | 1,500 |
| Phonk God | 5,000 |

#### Points Commands

| Command | What it does |
|---|---|
| `!points` | Check your current Phonk Points balance |
| `!rank` | Your current rank + how many pts to the next tier |
| `!leaderboard` | Top 5 point holders in chat |
| `!claim` | Claim your daily 50pt bonus (resets each day) |
| `!give @user amount` | Gift some of your points to another viewer |

---

### 🎲 Gambling

> Put your Phonk Points on the line. Win big or lose it all.

#### `!gamble [amount]`

Coin flip. **Win = 2× your bet.** Lose = gone. *(10s cooldown per user)*

#### `!slots [amount]`

Spin 3 reels. Symbols: 🎵 🔥 💀 ⚡ 🌙 👾 *(10s cooldown per user)*

| Result | Payout |
|---|---|
| 3 matching symbols | **5× — Jackpot!** |
| 2 matching symbols | **2×** |
| No match | **0 — lose bet** |

---

### ⚔️ Duel

Challenge another viewer to a Phonk Points battle.

| Command | What it does |
|---|---|
| `!duel @user amount` | Challenge someone — they have 60s to respond |
| `!accept` | Accept the incoming duel — coin flip decides the winner |
| `!decline` | Decline the incoming duel |

> Winner takes the full pot. Both players must have enough points to enter. Only one duel can be pending at a time.

---

### 🎉 Giveaway

Mods run giveaways, anyone can enter.

| Command | Who | What it does |
|---|---|---|
| `!giveaway start` | Mods only | Opens the giveaway — chat can now !enter |
| `!giveaway pick` | Mods only | Picks a random winner from all entries |
| `!giveaway end` | Mods only | Closes giveaway without picking a winner |
| `!enter` | Everyone | Enter the active giveaway |

---

### 🔥 Engagement

| Command | What it does |
|---|---|
| `!hype` | Adds 1 to the hype meter on stream. At **15 votes** the overlay flashes and chat gets a shoutout. Earns **+2 pts**. |
| `!vibe` | Posts a random phonk atmosphere line |
| `!fire` | Vote the current track as 🔥 fire — running tally shown in chat |
| `!trash` | Vote the current track as 💀 trash — running tally shown in chat |
| `!lurk` | Go lurk — acknowledged in chat and earns **+5 pts** |

> `!fire` / `!trash` — once per track per viewer. Tally resets when the song changes.  
> `!hype` — 60s cooldown per user. Meter resets 3 seconds after hitting 15.

---

### 📖 Quotes

A library of memorable stream moments.

| Command | Who | What it does |
|---|---|---|
| `!addquote [text]` | Mods only | Save a quote to the library |
| `!quote` | Everyone | Pull up a random quote |
| `!quote [id]` | Everyone | Pull up a specific quote by number |
| `!delquote [id]` | Mods only | Delete a quote by its number |

---

### 💥 Overlay Effects

Spend Phonk Points to visually affect the live stream in real time.

| Command | Cost | Effect | Cooldown |
|---|---|---|---|
| `!glitch` | **100 pts** | Scanline glitch overlay for 3 seconds | 120s per user |
| `!rain` | **50 pts** | Forces neon rain on screen for 30 seconds | 120s per user |

---

### 🔧 Custom Commands

Mods can create, edit, and delete custom bot responses on the fly.

| Command | What it does |
|---|---|
| `!addcom !name response` | Create a new command — supports `{user}` variable |
| `!editcom !name new response` | Update an existing custom command |
| `!delcom !name` | Delete a custom command |

> Example: `!addcom !rules No spam, no links, keep it chill {user}!`  
> When a viewer types `!rules`, the bot replies with their name filled in.

---

### 🛡️ Moderation

The bot automatically moderates chat 24/7. **Mods, VIPs, and subscribers are fully exempt** from all filters.

#### Auto-Filters

| Filter | What triggers it |
|---|---|
| **Link filter** | Any URL not on the approved whitelist |
| **Caps filter** | Message >70% capital letters (12+ chars) |
| **Symbol/emoji spam** | Message >50% symbols or emojis |
| **Long message** | Message over 300 characters |
| **Repeat spam** | Exact same message sent twice in a row |
| **Banned words** | Configurable list of blocked phrases |

#### Approved Link Whitelist

Links to these domains are always allowed for everyone:

`twitch.tv` · `discord.gg` · `music.korivash.com` · `korivash.com` · `youtube.com` · `youtu.be` · `imgur.com` · `clips.twitch.tv`

#### Escalating Punishments

Each filter violation adds a strike. Strikes are tracked per user across the stream session.

| Strike | Punishment |
|---|---|
| 1st offense | ⚠️ Warning in chat + message deleted |
| 2nd offense | ⏱️ 60-second timeout + message deleted |
| 3rd offense | ⏱️ 10-minute timeout + message deleted |
| 4th offense | 🔨 Permanent ban |

#### Mod Commands

| Command | What it does |
|---|---|
| `!permit @user` | Allows a user to post one link freely for 60 seconds |
| `!resetoffenses @user` | Clears a user's strike count |
| `!timeout @user [seconds]` | Manually timeout a user (default 600s) |
| `!ban @user [reason]` | Permanently ban a user |
| `!unban @user` | Remove a ban |
| `!slow [seconds]` | Enable slow mode (default 30s between messages) |
| `!slowoff` | Disable slow mode |
| `!subonly` | Enable subscriber-only chat mode |
| `!subnonly` | Disable subscriber-only chat mode |
| `!emoteonly` | Enable emote-only chat mode |
| `!emoteonlyoff` | Disable emote-only chat mode |
| `!clear` | Delete all messages in chat |
| `!shoutout @user` | Post a shoutout with a link to another streamer |
| `!so @user` | Shorthand for `!shoutout` |

---

## ⚙️ Automatic Features

- **Auto-announcements** — Bot posts a rotating message every hour:
  1. Discord invite link
  2. [music.korivash.com](https://music.korivash.com) listen link
  3. DM Korivash on Discord for any stream issues
- **Raid alerts** — Incoming raids trigger an on-screen overlay banner + welcome message in chat
- **Sub & cheer alerts** — On-screen banner for new subs and bit cheers; supporter name added to the live scrolling strip
- **Passive points** — 10 pts awarded automatically every 5 minutes to active chatters
- **Auto-moderation** — Link, spam, and caps filters run continuously with no mod input required

---

## 📝 Notes

| Term | Meaning |
|---|---|
| **Global cooldown** | One person triggers the cooldown for the whole chat |
| **Per user cooldown** | Each viewer has their own independent timer |
| **Mod exempt** | Mods and broadcasters bypass all filters and restrictions |
| **Sub exempt** | Subscribers are trusted users — exempt from all auto-filters |

- Phonk Points are stored in the browser and persist across streams, but reset if the browser source is cleared
- Strike counts reset with the browser session (OBS restart)
- The `!fire` / `!trash` vote resets automatically when the track changes
- The hype meter resets 3 seconds after reaching 15 votes
- Only one duel can be pending at a time — it expires after 60 seconds if not accepted

---

<div align="center">

*Sleep · Study · Drive · Relax*

**[twitch.tv/korivash](https://twitch.tv/korivash) · [music.korivash.com](https://music.korivash.com) · [discord.gg/VhAj8K4C6F](https://discord.gg/VhAj8K4C6F)**

</div>
