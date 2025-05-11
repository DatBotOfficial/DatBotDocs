---
description: >-
  The system was released on February 26, 2024 and has been in the open beta
  phase since March 5, 2024. Manage your own temporary voice channels. Secure,
  modern, with many features.
icon: volume-high
---

# TempVoice



{% hint style="info" %}
The system is in open beta! Try it out with `/tempvoice setup`.
{% endhint %}

###

### Permissions

* **Admin**: Users on the server who have the permission Administrator
  * Manage the server settings: ✅
  * Manage a temporary voice channel: ✅
* **Server Mods**: Users with the moderation role (a role you can set so members with this role can manage temporary voice channels, but do not need actual permissions like Administrator)
  * Manage the server settings: ❌
  * Manage a temporary voice channel: ✅
    * _Note: They can not add or remove moderators, but can take over the channel to do t_
* **TempVoice Owner**: The owner of a temporary voice channel
  * Manage the server settings: ❌
  * Manage a temporary voice channel: ✅
* **TempVoice Mods:** The tempvoice owner can select moderators
  * Manage the server settings: ❌
  * Manage a temporary voice channel: 🔵
    * Kick users ✅
    * Lock and unlock the channel ✅
    * Change the name ✅
    * Change the user limit ✅
    * Invite users ✅
    * Remove invitations ✅
    * Everything else: ❌

<table><thead><tr><th width="223">Permission</th><th width="81">Admin</th><th width="96">Server Mods</th><th width="244">TempVoice Owner</th></tr></thead><tbody><tr><td>Manage the system settings (server)</td><td>✅</td><td>❌</td><td>❌</td></tr><tr><td>Manage the temporary voice channel</td><td>✅</td><td>✅</td><td>✅</td></tr></tbody></table>

### Restrictions

#### Server ban

<figure><img src="../../.gitbook/assets/Screenshot 2024-03-07 161635.png" alt=""><figcaption><p>This is how the error message looks if you have been banned.</p></figcaption></figure>

* This error appears if you have been banned from the system by a server moderator.&#x20;
* This ban is not global.
* This means that you can no longer create or manage temporary voice channels.

#### How to remove a server ban

_<mark style="color:yellow;">Note: To be unbanned, you must ask a server moderator to unban you.</mark>_&#x20;

1. The moderator has to use `/tempvoice settings`
2.  &#x20;

    <figure><img src="../../.gitbook/assets/Screenshot 2024-03-07 162229.png" alt=""><figcaption><p>Click on the emoji for Moderation settings</p></figcaption></figure>
3.

    <figure><img src="../../.gitbook/assets/Screenshot 2024-03-07 162446.png" alt=""><figcaption><p>Click on the emoji to remove a block</p></figcaption></figure>
4.

    <figure><img src="../../.gitbook/assets/Screenshot 2024-03-07 162705.png" alt=""><figcaption><p>Select the user who has been blocked with the select menu. If the user is not showing up, search with the username or the ID.</p></figcaption></figure>


5.  If everything worked, you should see a message like the one below this text. The user is not able to use the system again.&#x20;

    <figure><img src="../../.gitbook/assets/Screenshot 2024-03-07 162929.png" alt=""><figcaption><p>The bot responds with this message if the user has been unbanned.</p></figcaption></figure>



### Functions

* Moderation
  * Blocking users: You can block users. They cannot create and manage temporary voice channels while they are blocked.
  * Logging: It works in principle like the Discord Audit Log, but is for temporary voice channels. All actions, for example renaming the channel, are logged.
  * Moderation Role: By default, you must have the permission Administrator to be able to manage the system. People who have this role can manage the temporary voice channels, but not the system settings themselves. See also: [#permissions](tempvoice.md#permissions "mention")
* Channel customization
  * You can manage the temporary voice channel with the interface.
  * You can manage privacy, users and the channel.
  * Privacy
    * Lock the channel
    * Unlock the channel
    * Make the channel visible
    * Make the channel invisible
  * Channel
    * Set bit rate
    * Set name
    * Set status (As of March 07, 2024, this is not working yet)
    * Set region
    * Set userlimit
    * Set NSFW
    * Set video quality
    * Delete channel
  * Users
    * Invite user
    * Remove invitation
    * Ban user
    * Unban user
    * Kick user
    * Transfer ownership
    * Add moderator
    * Remove moderator

### Set-Up

1. Use /tempvoice setup and click in the "Continue" button.
2.  Select the type.

    Quick: If you choose this option,  the bot creates a category, a text channel, in which it sends the interface and creates a voice channel, which is functioning as the creator channel.

    Manual: Set the creator channel and send the interface manually

<figure><img src="../../.gitbook/assets/Screenshot 2024-03-07 170134.png" alt=""><figcaption><p>You have to click on the select menu to select a type.</p></figcaption></figure>

3. If you chose "Quick", the bot will create everything for you. If you want to change settings, use `/tempvoice settings`
4. If you chose Manual, you first have to choose, which voice channel the creator channel should be.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2024-03-07 170418.png" alt=""><figcaption><p>Click on the select menu to choose a voice channel. If it does not show up, type in the name of the voice channel.</p></figcaption></figure>

5. After doing so, you have to send the Interface. Choose a channel and the bot will send the interface in this channel.

<figure><img src="../../.gitbook/assets/Screenshot 2024-03-07 170637.png" alt=""><figcaption><p>Click on the select menu to choose a channel. The bot sends the Interface in this channel.</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot 2024-03-07 170845.png" alt=""><figcaption><p>The Interface as of March 07, 2024</p></figcaption></figure>
