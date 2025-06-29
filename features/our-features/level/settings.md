---
icon: book-blank
---

# Settings

The list unter a header (General, Level Roles, ect.) shows what you can manage there.

### General

* XP Range: Manage the XP Range (minimum/maximum) for **Message** XP
* Starting Required XP: Required XP for at level 1 for level 2
* Voice Cooldown: Interval in which Voice XP are given
* Message Cooldown: Cooldown until a Message gains message XP again
* Formula: Custom formula for required XP (Use the placeholders {1} for level and {2} for old required xp)
* Gain Type: Can either be Per Message or Cooldown
* Reset: Reset all system settings
* Enable or disable the system and choose between Voice And Message X

### Level Roles

* Add/edit: Add a new level reward or edit an existing reward
* Debug: Debug if you have any issues
* Reset: Reset all rewards
* Remove a level reward: Removes a level reward

### Level Message

* Content: Provide custom message content. To be shown, the <mark style="color:purple;">Message Type</mark> must either be Both or Content.
* Embed: Choose a custom embed. To To be shown, the <mark style="color:purple;">Message Type</mark> must either be Both or Embed.
* Variables: View the variables useable within the message.
* Select a level up channel: Select a channel in which the bot will send the message. If none is provided, the current channel will be used.
* <mark style="color:purple;">Select a Message Type</mark>: Can either be Both, Embed, Content or None. If set to none, there will be no Level Up message.
* Reset: Reset the used embed, message content or channel.

### Excluded

{% hint style="info" %}
Excluded channels are channels, in which no XP can be gained.

If a user has an excluded role, they can not gain any XP.

Excluded users are users who can not gain XP in general.
{% endhint %}

* Reset: Reset all excluded channels, roles and users.
* \[+] Channel: Add an excluded channel.
* \[-] Channel: Remove an excluded channel.
* \[+] Role: Add an excluded role.
* \[-] Role: Remove an excluded role.
* \[+] User: Add an excluded user.
* \[-] User: Remove an excluded user.

### Multiplier

* Reset: Reset all multipliers
* \[+] Multiplier: Add a multiplier.
* \[-] Multiplier: Remove a multiplier.

### Logging

* Debug: Debug if you experience any issues
* Logging channel: This channel will be used as logging channel

### Live Leaderboard

{% hint style="info" %}
The Live Leaderboard is a leaderboard that will automatically update every hour.
{% endhint %}

* Embed: Select a custom embed. Note that the description of the embed will always be overwritten.
* Display Type: Can either be All or Still on Guild (only display members which are on the server)
* Amount: Amount of users shown on the live leaderboard.
* Send the live leaderboard: Sends the live leaderboard and invalidates all other sent live leaderboards.

### XP Drops

* XP Range: XP Range of the XP Drops
* <mark style="color:red;">Claimtype</mark>: Choose whether only one user or multiple users should be able to claim the XP Drop.
* Time until disable: Time until the XP Drop disables itself.
* Time until respawn: Provide the minimum and maximum time until a XP Drop can spawn again.
* Type: Enable or disable XP Drops here. If the type is set to Only selected channels, XP Drops will only be send in <mark style="color:green;">selected channels</mark>. If the type is set to Exclude selected channels, the bot can send a XP Drop in all channels except <mark style="color:green;">selected channels</mark>.
* \[+] Channel: Add a channel that is considered as a <mark style="color:green;">selected channel</mark>.
* \[-] Channel: Remove a channel that is considered as a <mark style="color:green;">selected channel</mark>.

### Voice Level

* XP Range: XP Range for Voice XP gaining
* Reset: Reset all Voice Level Settings

### Streaks

Streak Rewards are rewards given if a member reached a specific streak day.&#x20;

Streak Losses are settings which allow you to manage what happens after a user lost their streak. You can select specific days or use default settings which are set by setting the streak day to 0.

* Type: How users can extend their streak. Can either be Voice, Message, None (which means that streaks are disabled) or Both (which means they can join a voice channel or a send a message)
* Reset: Reset user streaks, streak losses or streak rewards.
