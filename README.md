# LUXARA - A Feature-Rich Discord Bot

Welcome to **LUXARA**, a powerful, multi-purpose Discord bot designed to bring your server to life with a comprehensive economy, robust moderation, and engaging entertainment features. Built with modern discord.js and a robust database, LUXARA provides a polished and seamless experience for both administrators and community members.

[**Invite LUXARA to Your Server**](https://discord.com/api/oauth2/authorize?client_id=967589433828311080&permissions=8&scope=bot%20applications.commands) | [**Join the Support Server**](https://discord.gg/asRaJG9zCc)

---

## ✨ Key Features

LUXARA is packed with features to create an engaging and well-managed server experience:

*   **💸 Deep Economy System:** Earn currency, level up, manage your bank, climb the leaderboards, and trade with other users.
*   **🛒 Dynamic Item Shop:** A shop with permanent and weekly rotating items that grant passive boosts or usable effects.
*   **🎲 Engaging Games:** Test your luck with Blackjack, Coinflip, and Slots to multiply your fortune.
*   **🛡️ Powerful Moderation Suite:** Includes a full suite of moderation tools and a comprehensive logging system.
*   **🤖 Advanced AutoMod Control:** A dedicated command to manage Discord's built-in AutoMod, from custom keyword filters to presets like spam and profanity blockers.
*   **⚙️ Server Utilities:** Fully configurable welcome messages, announcements, a professional ticketing system, and much more.

---

## 🚀 AutoMod Quick Start Guide

LUXARA allows you to control Discord's AutoMod feature directly with commands. Here's how to set it up:

1.  **Set a Log Channel:** You must first tell the bot where to send moderation alerts. This is a one-time setup.
    *   `/config-logs set-channel channel:#your-mod-log-channel`

2.  **Configure Your Rules:** Now you can use the `/automod` command group to manage your filters.
    *   **Block custom words:** `/automod keyword add word:badword1,badword2`
    *   **Enable a preset:** `/automod preset toggle rule:Profanity enabled:True`
    *   **Add a timeout penalty:** `/automod set-timeout rule:Keyword duration:5` (Adds a 5-minute timeout for anyone who uses a custom keyword).

---

## 📖 Command Reference

Below is a complete list of commands available in LUXARA.
*   `<argument>` denotes a **required** option.
*   `[argument]` denotes an **optional** option.

### 💸 Economy Commands

| Command | Description | Usage | Permissions |
|---|---|---|---|
| `/balance` | View your or another user's financial overview. | `/balance [user]` | None |
| `/daily` | Claim your daily currency and XP reward. | `/daily` | None |
| `/deposit` | Deposit money from your wallet into your bank. | `/deposit <amount>` | None |
| `/gift` | Gift an item from your inventory to another user. | `/gift <user> <item> <quantity>` | None |
| `/inventory`| Check your or another user's owned items. | `/inventory [user]` | None |
| `/leaderboard`| Shows the server's wealth and level leaderboards. | `/leaderboard` | None |
| `/pay` | Pay another user from your wallet. | `/pay <user> <amount>` | None |
| `/profile` | Displays your stylish user profile card. | `/profile [user]` | None |
| `/shop` | View the item shop and purchase items. | `/shop` | None |
| `/use` | Use a consumable item from your inventory. | `/use <item>` | None |
| `/withdraw` | Withdraw money from your bank to your wallet. | `/withdraw <amount>` | None |
| `/work` | Do a hard day's work to earn cash and XP. | `/work` | None |
| `/crime` | Attempt a risky crime for a bigger reward. | `/crime` | None |
| `/rob` | Attempt to steal money from another user's wallet. | `/rob <target>` | None |

### 🎲 Fun & Games Commands

| Command | Description | Usage | Permissions |
|---|---|---|---|
| `/8ball` | Asks the magic 8-ball a question. | `/8ball <question>` | None |
| `/avatar` | Displays a user's avatar. | `/avatar [user]` | None |
| `/blackjack`| Play a game of blackjack against the dealer. | `/blackjack <bet>` | None |
| `/coinflip`| Flip a coin for a chance to double your bet. | `/coinflip <bet> <choice>` | None |
| `/joke` | Tells a random joke. | `/joke` | None |
| `/meme` | Fetches a random meme from Reddit. | `/meme` | None |
| `/slots` | Spin the slot machine for a chance to win big. | `/slots <bet>` | None |

### 🛡️ Moderation Commands

| Command | Description | Usage | Permissions |
|---|---|---|---|
| `/ban` | Bans a user from the server. | `/ban <target> [reason]` | Ban Members |
| `/kick` | Kicks a user from the server. | `/kick <target> [reason]` | Kick Members |
| `/mute` | Mutes a user by timing them out. | `/mute <target> <duration> [reason]`| Moderate Members |
| `/purge` | Deletes a specified number of messages. | `/purge <amount> [user]` | Manage Messages|
| `/unmute` | Removes a mute (timeout) from a user. | `/unmute <target>` | Moderate Members|
| `/warn` | Warns a user and logs it to the database. | `/warn <target> <reason>` | Manage Messages|
| `/warned` | Views the warning history for a user. | `/warned [user]` | Manage Messages|

### ⚙️ Admin & Utility Commands

| Command | Description | Usage & Subcommands | Permissions |
|---|---|---|---|
| `/adjust-balance`| Adjust a user's wallet or bank balance. | `/adjust-balance <user> <type> <action> <amount>` | Administrator |
| `/adjust-items`| Give or take items from a user. | `/adjust-items <user> <action> <item> <quantity>` | Administrator |
| `/adjust-stats`| Set a user's level or XP. | `/adjust-stats <user> <stat> <value>` | Administrator |
| `/announcement`| Creates and sends a formatted announcement. | `/announcement <title> <message> [channel] [mention]`| Manage Guild |
| `/automod` | Manages the server's AutoMod rules. | See subcommands (`/automod keyword`, `/automod preset`, etc.) | Manage Guild |
| `/config-events`| Configures server welcome and goodbye messages. | `/config-events <welcome/goodbye> <set/disable>` | Administrator |
| `/config-logs`| Configures the moderation audit log channel. | `/config-logs <set-channel/disable>` | Administrator |
| `/giveaway` | Starts a giveaway. | `/giveaway <duration> <prize> [winners]` | Manage Guild |
| `/help` | Shows the interactive list of available commands. | `/help` | None |
| `/poll` | Creates a poll with up to 10 choices. | `/poll <topic> <option1> <option2>...` | Manage Messages |
| `/say` | Makes the bot say something in a channel. | `/say <message> [channel]` | Manage Messages |
| `/serverinfo` | Displays detailed information about the server. | `/serverinfo` | None |
| `/ticket-setup`| Manages the ticket system configuration. | `/ticket-setup <config/panel>` | Administrator |
| `/translate-config`| Manages the auto-translation feature. | `/translate-config <subcommand>` | Manage Guild |
| `/userinfo` | Displays detailed information about a user. | `/userinfo [user]` | None |


---

## ⚖️ Legal

By using **LUXARA**, you agree to our [Terms of Service](https://github.com/OreOliciouZ/MSBot/blob/main/ToS.md) and [Privacy Policy](https://github.com/OreOliciouZ/MSBot/blob/main/PP.md). Please read them carefully.

---
*Created with ❤️ by `oreoliciouz`*
