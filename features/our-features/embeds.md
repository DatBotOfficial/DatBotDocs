---
description: Create your own embeds, manage the embeds and more.
icon: bars
---

# Embeds

{% hint style="warning" %}
All old `/embeds create` interactions are unavailable due to the new update. You can still edit old embeds.
{% endhint %}

### Information

* You can create your own embed completely by yourself.
* It is possible to export the embed, import it, edit it further (`/embeds edit`) and send the embed several times as well as with a webhook
* You can save your embeds internally and reuse it on different servers.

<figure><img src="../../.gitbook/assets/Screenshot 2025-05-28 171135.png" alt=""><figcaption><p>The new <code>/embeds create</code> command.</p></figcaption></figure>

### General

* Use Now Timestamp: If you edit or send the embed, it will automatically update the Embed's Timestamp to the current time. You can toggle it with the "Use Now Timestamp" Button.
* Save: You can now save Embed Templates for yourself. You can save up to 25 by default.
* The attached embed.json file is the file that contains all the embed data. Some websites and bots allow the import of Embeds via .json, therefore you can access it directly.

### Variables

* \{{serverid\}} Server ID
* \{{userid\}} Your user ID
* \{{username\}} Your username
* \{{servername\}} Server Name
* \{{servericon\}} Server Icon
* \{{usericon\}} User Avatar
* \{{serverbanner\}} Server Banner
* \{{userbanner\}} User Banner

### Commands

* `/embeds create <embed_id>`
  * Create your own embed.
  * Argument \<embed\_id>
    * if you saved an embed with `/embeds save`, you can use it again to create another embed.
* `/embeds edit <message_link> <embed_id>`&#x20;
  * Edit an embed that already exists. One of the two arguments is required.
  * Argument \<message\_link>
    * This is the message link of the embed.
  * Argument \<embed\_id>
    * Embed an existing Database Embed.
* `/embeds copybymessagelink [message_link]`
  * Copy an existing embed, this does not have to be from Dat Bot.
  * &#x20;This allows you to send it on or change it without editing the original.
  * Argument \[message\_link]
    * This is the message link of the embed.
* `/embeds copybyid [embed_id] [name]`
  * Copy an existing embed with the embed id \[embed\_id] and save it in the database with the new \[name].
  * &#x20;This allows you to send it on or change it without editing the original.
* `/embeds delete [embed_id]`
  * Delete an embed template created by you.
  * Argument \[embed\_id]
    * The embed template to delete
* `/embeds save [message_link] [name]`
  * Export an embed. Uses the internal database.
  * Argument \[message\_link]
    * This is the message link of the embed.
  * Argument \[name]
    * Provide a name to find the template easier.
