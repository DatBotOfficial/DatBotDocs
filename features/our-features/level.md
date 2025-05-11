---
icon: circle-chevron-up
---

# Level

### How does it work?

* A message is evaluated every 60 seconds. This message receives between 1 and 25 XP.
* You cannot change ranks or XP.
* You can add rewards (level roles

### Commands

* `/level levelupchannel set <channel>`
  * The level-up message is sent in this channel.
  * Argument \<channel>
    * The level-up messages are sent in this channel.
* `/level levelupchannel reset`
  * Resets the Level Up Channel.
* `/level levelupchannel view`
  * View the Level Up Channel.
* `/level ignore channel [channel]`
  * Messages will not get XP in these channels.
  * Argument \[channel]
    * No more XP will be awarded in this channel.
* `/level ignore list`
  * This command returns a list of ignored channels.
* `/level ignore remove [channel]`
  * Remove an ignored channel.
  * Argument \[channel]
    * The channel to be removed from the database.
* `/level leaderboard <entriesperpage>`
  * See the users with the most XP on the server. 10 users are displayed per page, but you can switch between the pages.
  * Argument \<entriesperpage>
    * How many entries shown per page
* `/level levelupmessage set`&#x20;
  * Customize the level-up message.
* `/level levelupmessage reset`
  * Resets the Level Up Message.
* /`level levelupmessage view`
  * View the Level Up Message.
* `/level noxprole set <role>`
  * If a user has this role, they won't get XP
  * Argument \<role>
    * The No-XP role is set to this role.
* `/level levelupmessage reset`
  * Resets the Level Up Message.
* `/level levelupmessage view`
  * View the Level Up Message.
* `/level rank <user>`
  * See the rank of a user with this command.
  * Argument \<user>
    * The rank is viewed by this user.
    * If no user has been specified, your statistics will be displayed.
* `/level roles add [role] [level]`
  * Add a roll as a reward. When level \[level] is reached, the role \[role] is awarded.
  * Argument \[role]
    * This role is assigned when level \[level] is reached.
  * Argument \[level]
    * When someone reaches this level, the role \[role] is assigned.
* `/level roles deleteall`
  * Remove all level roles. This cannot be undone.
* `/level roles list`
  * This shows you all level roles.
* `/level roles remove [role]`
  * Remove the level role that is assigned at level \[level].
  * Argument \[role]
    * This role is to be removed.
* `/level roles sync`
  * Sync the rewards.
  * If you added a reward, for exmaple for level 5, a member with level 5 or a higher level will get the reward when leveling up the next time. You can give them the role by using this command.
* `/level roles debug`
  * Check for errors and common issues with the system.
* `/level debug`
  * If there are problems, use this command. Frequent sources of problems are checked here.
* `/level toggle`
  * Deactivate the level system on the server on which the command is executed.
