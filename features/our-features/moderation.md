---
icon: gavel
---

# Moderation

## Commands

### `/copycategory [category] <name> <amount> <change_role_permissions> <role>`

* Clones a category. This is working like the feature from Discord.
* Argument \[category]
  * This category is going to be cloned.
* Argument \<name>
  * The name of the new category.
* Argument \<amount>
  * The category will be cloned this amount of times.
* Argument \<change\_role\_permissions>
  * Changes the roles permissions with another role. The role \<role> gets the permissions from this role.
* Argument \<role>
  * This role will get the permissions.

### `/moderation ban [user] <notify_about_punishment> <reason> <delete_messages>`

* Permanently bans a user from the server.
* Argument \[user]
  * This user is permanently banned.
* Argument \<notify\_about\_punishment>
  * Decide whether the user should be informed of the ban by private message. There is no mention of who banned the user.
* Argument \<reason>
  * Add a reason that is displayed in the audit log.
*   Argument \<delete\_messages>

    * Delete all messages between a certain time period. This must be between 1 second and 7 days. Specify this with s, m, h and d.



`/moderation banreason`<mark style="color:purple;">`[ids]`</mark><mark style="color:green;">`<reason>`</mark><mark style="color:blue;">`<delete_messages>`</mark>

* Permanently bans users from the server. Requires the Administrator permission.
* Argument <mark style="color:purple;">\[ids]</mark>
  * <mark style="color:purple;">The IDs of the members who should be banned.</mark>&#x20;
* Argument <mark style="color:green;">\<reason></mark>
  * <mark style="color:green;">Add a reason that is displayed in the audit log.</mark>
* Argument <mark style="color:blue;">\<delete\_messages></mark>
  * <mark style="color:blue;">Delete all messages between a certain time period. This must be between 1 second and 7 days. Specify this with s, m, h and d.</mark>

### `/moderation banreason [ban] [new_reason]`

* Change the reason for a ban.
* Argument \[ban]
  * Specify the ban here. This option supports autocomplete, so search for the ban by username or enter an ID here.
* Argument \[new\_reason]
  * Enter the new reason here.

### `/moderation clear [number] <user> <channel>`

* Delete a certain number of messages.
* Argument \[number]
  * Enter the number of messages to be deleted here.
  * The number must be between 1 and 100.
* Argument \<user>
  * The messages are only deleted by this user.
* Argument \<channel>
  * The messages are deleted in this channel.

### `/moderation kick [user] <reason> <notify_about_punishment>`

* Kick a user from the server.
* Argument \[user]
  * This user will be kicked.
* Argument \<reason>
  * Add a reason that is displayed in the audit log.
* Argument \<notify\_about\_punishment>
  * Decide whether the user should be informed of the kick by private message. There is no mention of who kicked the user.

### `/moderation lock <reason> <channel> <time>`

* Remove the permissions for the role `@everyone` to send messages in the channel .
* Argument \<reason>
  * Add a reason that is displayed in the audit log.
* Argument \<channel>
  * This channel will be locked.
* Argument \<time>
  * Specify how long the channel should be blocked. Enter the time with s, m, h and d.

### `/moderation mute [user] [time] <reason>`

* Timeout a user with the Discord function
* Argument \[user]
  * This user will be timed out.
* Argument \[time]
  * Specify how long the user should be timed. Specify the time with s, m, h and d.
* Argument \<reason>
  * Add a reason that is displayed in the audit log.

### `/moderation nickname reset [user]`

* Reset the nickname of a user.
* Argument \[user]
  * The nickname of this user is reset.

### `/moderation nickname set [user] [nick]`

* Change the nickname of a user.
* Argument \[user]
  * The nickname is changed for this user.
* Argument \[nick]
  * This is the user's new nickname.

### `/moderation unban [user] <reason>`

* Unban a user with their ID.
* Argument \[user]
  * Specify the user to be unbanned
* Argument \<reason>
  * Add a reason that is displayed in the audit log.

### `/moderation unlock <channel>`

* Give the role `@everyone` the authorization to send messages to a channel.
* Argument \<channel>
  * Specify the Discord channel here.

### `/moderation unmute [user]`

* Remove the timeout of a user.
* Argument \[user]
  * The timeout is removed from this user.\


`/moderation voice channelinfo`<mark style="color:blue;">`<channel>`</mark>

* Gets information about a <mark style="color:blue;">voice channel</mark>.
* Argument <mark style="color:blue;">\<channel></mark>
  * The channel to get information from.

`/moderation voice memberinfo`<mark style="color:blue;">`<member>`</mark>&#x20;

* Gets voice channel information about a <mark style="color:blue;">member</mark>.
* Argument <mark style="color:blue;">`<member>`</mark>
  * The member to get information from.

`/moderation voice moveall`<mark style="color:green;">`<old_channel>`</mark><mark style="color:blue;">`<new_channel>`</mark>&#x20;

* Moves all members from the <mark style="color:green;">old channel</mark> to the <mark style="color:blue;">new channel</mark>.
* Argument <mark style="color:green;">`<old_channel>`</mark>
  * The old channel where members are moved from
* Argument <mark style="color:blue;">`<new_channel>`</mark>
  * The members will be moved in this channel

`/moderation voice disconnectall`<mark style="color:green;">`<channel>`</mark>

* Disconnects all members from the <mark style="color:green;">channel</mark>.
* Argument <mark style="color:green;">`<channel>`</mark>
  * The channel where users are disconnected from.

`/moderation voice toggleserverdeafen`<mark style="color:blue;">`<user>`</mark>&#x20;

* Deafens or Undeafens the <mark style="color:blue;">member</mark>, based on the current deaf status.
* Argument <mark style="color:blue;">`<user>`</mark>&#x20;
  * The user to deafen or undeafen

`/moderation voice toggleservermute`<mark style="color:blue;">`<user>`</mark>&#x20;

* Mutes or Unmutes the <mark style="color:blue;">member</mark>, based on the current mute status.
* Argument <mark style="color:blue;">`<user>`</mark>&#x20;
  * The user to mute or unmute
