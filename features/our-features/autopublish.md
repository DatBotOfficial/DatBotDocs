---
description: Autopublish is used to publish messages automatically.
icon: bullhorn
---

# Autopublish

<figure><img src="../../.gitbook/assets/Screenshot 2023-11-01 101543.png" alt=""><figcaption><p>The available commands for the feature.</p></figcaption></figure>

## Commands

* `/autopublish add [channel]`
  * Add a channel in which all messages are published immediately.
  * Argument \[channel]
    * This channel will be added
    * The bot needs the View Channel and Manage Messages permission
    * The channel needs to be an Announcement Channel ([https://support.discord.com/hc/en-us/articles/360032008192-Announcement-Channels](https://support.discord.com/hc/en-us/articles/360032008192-Announcement-Channels))
* `/autopublish list`
  * This command will return a list on all autopublish channels.
* `/autopublish remove [channel]`
  * Remove an autopublish channel. No more messages will be published in this channel.
  * Argument \[channel]
    * This channel must already be an Autopublish channel.
* `/autopublish test`
  * If there are problems, you can use this command. Frequent sources of problems are checked here.
* `/autopublish toggle`
  * Deactivate the system. If the system is deactivated, no more messages will be published automatically.
