# LUXARA - A Feature-Rich Discord Bot

Welcome to **LUXARA**, a powerful, multi-purpose Discord bot designed to bring your server to life with a comprehensive economy, robust moderation, and engaging entertainment features. Built with modern discord.js and a robust database, LUXARA provides a polished and seamless experience for both administrators and community members.

[**➕ Invite LUXARA**](https://discord.com/api/oauth2/authorize?client_id=967589433828311080&permissions=8&scope=bot%20applications.commands) • [**💬 Join Support Server**](https://discord.gg/asRaJG9zCc)

---

## ✨ Features at a Glance

- **💸 Deep Economy System:** Earn, save, trade, and compete on leaderboards.
- **🛍️ Rotating Item Shop:** Weekly and permanent items with passive or active effects.
- **🎮 Fun Mini-Games:** Blackjack, Coinflip, Slots, and more.
- **🛡️ Powerful Moderation Tools:** Ban, mute, warn, purge, and full logging.
- **⚙️ Server Utilities:** AutoMod control, welcome messages, tickets, polls, announcements.

---

## 🚀 AutoMod Quick Start

Set up Discord’s AutoMod using LUXARA’s commands:

1. **Set a Mod Log Channel:**

   ```bash
   /config-logs set-channel channel:#mod-log
   ```

2. **Enable Rules & Actions:**
   - **Block words:**  
     ```bash
     /automod keyword add word:badword1,badword2
     ```
   - **Enable preset (e.g., profanity):**
     ```bash
     /automod preset toggle rule:Profanity enabled:true
     ```
   - **Timeout on rule break:**
     ```bash
     /automod set-timeout rule:Keyword duration:5
     ```

---

## 📚 Command Overview

> **Legend:**  
> `<argument>` = Required • `[argument]` = Optional  
> 🛠 = Admin/Mod only • 🧪 = Developer only  

---

### 💸 Economy

| Command | Description | Usage |
|--------|-------------|-------|
| `/balance` | View user balance | `/balance [user]` |
| `/daily` | Claim daily reward | `/daily` |
| `/deposit` | Deposit to bank | `/deposit <amount>` |
| `/gift` | Gift item to user | `/gift <user> <item> <quantity>` |
| `/inventory` | View inventory | `/inventory [user]` |
| `/leaderboard` | View server top users | `/leaderboard` |
| `/pay` | Pay another user | `/pay <user> <amount>` |
| `/profile` | Show profile card | `/profile [user]` |
| `/shop` | View and buy items | `/shop` |
| `/use` | Use an item | `/use <item>` |
| `/withdraw` | Withdraw from bank | `/withdraw <amount>` |
| `/work` | Work for rewards | `/work` |
| `/crime` | Attempt a risky crime | `/crime` |
| `/rob` | Steal from another user | `/rob <target>` |

---

### 🎮 Fun & Games

| Command | Description | Usage |
|--------|-------------|-------|
| `/8ball` | Ask the magic 8-ball | `/8ball <question>` |
| `/avatar` | Show user avatar | `/avatar [user]` |
| `/blackjack` | Play blackjack | `/blackjack <bet>` |
| `/coinflip` | Flip a coin | `/coinflip <bet> <choice>` |
| `/joke` | Get a random joke | `/joke` |
| `/meme` | Fetch a meme from Reddit | `/meme` |
| `/slots` | Spin the slot machine | `/slots <bet>` |

---

### 🛡️ Moderation 🛠

| Command | Description | Usage | Required Permission |
|--------|-------------|-------|---------------------|
| `/ban` | Ban a user | `/ban <target> [reason]` | Ban Members |
| `/kick` | Kick a user | `/kick <target> [reason]` | Kick Members |
| `/mute` | Timeout a user | `/mute <target> <duration> [reason]` | Moderate Members |
| `/purge` | Delete messages | `/purge <amount> [user]` | Manage Messages |
| `/unmute` | Remove timeout | `/unmute <target>` | Moderate Members |
| `/warn` | Warn a user | `/warn <target> <reason>` | Manage Messages |
| `/warned` | View user warnings | `/warned [user]` | Manage Messages |

---

### ⚙️ Admin & Utility 🛠

| Command | Description | Usage | Required Permission |
|--------|-------------|-------|---------------------|
| `/announcement` | Send a styled announcement | `/announcement <title> <message> [channel] [mention]` | Manage Guild |
| `/automod` | Manage AutoMod rules | See subcommands | Manage Guild |
| `/config-events` | Setup welcome/goodbye messages | `/config-events <welcome/goodbye> <set/disable>` | Administrator |
| `/config-logs` | Set mod log channel | `/config-logs <set-channel/disable>` | Administrator |
| `/help` | Show all commands | `/help` | None |
| `/poll` | Create a poll | `/poll <topic> <option1> <option2>...` | Manage Messages |
| `/say` | Make the bot say something | `/say <message> [channel]` | Manage Messages |
| `/serverinfo` | Show server info | `/serverinfo` | None |
| `/ticket-setup` | Configure ticket system | `/ticket-setup <config/panel>` | Administrator |
| `/translate-config` | Manage auto-translation | `/translate-config <subcommand>` | Manage Guild |
| `/userinfo` | Show user info | `/userinfo [user]` | None |

---

### 🧪 Developer-Only Commands

| Command | Description | Usage | Required Permission |
|--------|-------------|-------|---------------------|
| `/adjust-balance` | Modify user currency | `/adjust-balance <user> <type> <action> <amount>` | Administrator |
| `/adjust-items` | Add/remove user items | `/adjust-items <user> <action> <item> <quantity>` | Administrator |
| `/adjust-stats` | Modify user XP/level | `/adjust-stats <user> <stat> <value>` | Administrator |
| `/giveaway` | Start a giveaway | `/giveaway <duration> <prize> [winners]` | Manage Guild |

> ⚠️ These commands are intended for bot developers and may be restricted to dev environments.

---

## ⚖️ Legal

By using **LUXARA**, you agree to our [Terms of Service](https://github.com/OreOliciouZ/MSBot/blob/main/ToS.md) and [Privacy Policy](https://github.com/OreOliciouZ/MSBot/blob/main/PP.md).

---

**Made with ❤️ by [`oreoliciouz`](https://github.com/OreOliciouZ)**
