---
icon: twitch
---

# Twitch

### Commands

* `/twitch notification add [channel_name] <channel> <message> <mention> <delete_message_when_stream_ended>`
  * Add a stream notification for a Twitch channel.
  * Argument \[channel\_name]
    * This is the channel name, for example `dat_gamet`.
  * Argument \<channel>
    * The notification is sent in this Discord channel.
  * Argument \<message>
    * Edit the message of the notification.
  * Argument \<mention>
    * Add a mention to the message.
  * Argument \<delete\_message\_when\_stream\_ended>
    * Decide whether the bot should delete the message after the stream ended.
* `/twitch notification list`
  * Responds with a list of Twotch notifications.
* `/twitch notification remove [channel_name]`
  * Remove a Twitch stream notification.
  * Argument \[channel\_name]
    * The notification for this stream is removed.
* `/twitch notification reset`
  * Remove all twitch notifications.
