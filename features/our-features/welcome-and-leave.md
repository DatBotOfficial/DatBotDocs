---
icon: hand-wave
---

# Welcome & Leave

{% hint style="info" %}
The structures of Welcome & Leave are very similar.
{% endhint %}

{% hint style="warning" %}
The system is getting reworked and will change very soon.

Last updated: Dec. 31, 2024
{% endhint %}





<div align="left"><figure><img src="../../.gitbook/assets/Screenshot 2024-02-10 010848.png" alt=""><figcaption><p>This is what the message that greets users looks like. Recorded on February 10, 2024.</p></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot 2024-02-10 011129.png" alt=""><figcaption><p>This is what the message looks like when someone leaves. Recorded on February 10, 2024.</p></figcaption></figure></div>

### Overlap

* For the other logging see [logging.md](logging.md "mention")

### Commands

* `/leave channel [channel]` & `/welcome channel [channel]`
  * Set the channel in which the messages are sent.
  * Argument \[channel]
    * The messages are sent in this channel.
    * The bot needs the View Channel, Send Messages and Embed Links permission in this channel
* `/leave mention [type] <role>` & `/welcome mention [type] <role>`
  * Set a mention when the message is sent.
  * Argument \[type]
    * Mention the member who is leaving/joining: Mention the user leaving/joining the server.
      * Mention a specific role: Mention a role when a user leaves/joins.
      * Mention nobody: Remove the mentioning
  * Argument \<role>
    * This argument is only used if you have previously selected "Mention a specific role".&#x20;
      * This role is mentioned when a user joins.
* `/leave message` & `/welcome message`
  * This message is displayed when a user joins/leaves.
* `/leave settings` & `/welcome settings`
  * View and manage the settings.&#x20;
* `/leave test` & `/welcome test`
  * If the messages are not sent, use this command. Frequent sources of issues are checked here.
* `/leave toggle` & `/welcome toggle`
  * Activate or deactivate the system. If the system is deactivated, the messages will not be sent.

