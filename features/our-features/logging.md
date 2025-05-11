---
icon: book-copy
---

# Logging

### Information

*   The logs include the following

    * Add or remove bots
    * Ban, kick and unban users
    * Create, edit, delete webhooks
    * Create, delete and edit automoderation rules
    * Create, delete and edit threads
    * Create, delete and edit channels
    * Create, delete and edit roles
    * Create, delete and edit stickers
    * Create, delete and edit emojis
    * Create, delete and edit channel permissions
    * Create, delete and edit sounds
    * Create, delete and edit events
    * Create, delete and edit stages
    * Create and delete invitations
    * Edit server
    * Edit the user roles
    * Edit the application command permissions
    * Editing the Verification Bypass, Nickname, Timeout, Server Mute or Server Deafen of a member
    * Delete, bulkdelete & edit messages
    * Pin and Unpin messages
    * Remove Reactions & Remove All Reactions
    * Edit Server Guide
    * Edit Default Channels
    * Edit Onboarding


* Missing logging types
  * Edit Server Web Page
  * Edit Discovery
  * Edit Monetization

### Overlap

* For Welcome and Goodbye see [welcome-and-leave.md](welcome-and-leave.md "mention")

### Commands

* `/logs channel [type] [channel]`
  * Set the channel in which the logs are sent.
  * If the system has not yet been deactivated manually, the system is deactivated automatically.
  * Argument \[type]
    * Choose the type of logging. The messages related to this type will be sent in \[channel].
  * Argument \[channel]
    * The logs are sent in this channel.
    * The bot needs the "Manage Webhooks" permission in the \[channel]
* `/logs toggle`
  * Activate or deactivate the logs. If they are deactivated, they will not be sent.
* `/logs delete [type]`
  * Removed the channel for a logging type.&#x20;
  * If you have used a specific channel (All types except "All Logging Types") and a channel for the other logging (Type: All) and you delete the specific channel, it will use the all channel.
  * Argument \[type]
    * The type of logging.
