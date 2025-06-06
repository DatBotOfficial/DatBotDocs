---
icon: ticket
---

# Transfers

### General

Transfers: Within the Ticket, as long as it is a text channel, you have the possibility to transfer a Ticket. This is made for specific use cases, for example Unban Support. In this fictional example, the Unban Support is used if a user is banned on Twitch or Discord. If the staff member is not able to help, they can transfer the Ticket to the Twitch Unban Staff of the Discord Server. Transfers are linked to a Settings Model and only usable on the Guild they were created on. You are able to link them to multipe Setting Models.



### Creating Transfers

Use `/ticket transfers create` to create a Transfer. Use `ticket transfers edit` to edit an existing Transfer.

<figure><img src="../../../.gitbook/assets/grafik (12).png" alt=""><figcaption></figcaption></figure>

### Name

Change the display name of the Transfer model.&#x20;

### Permissions

{% hint style="warning" %}
These permissions overwrite the existing ticket permissions.
{% endhint %}

Works exactly like the Settings permissions. Read more here:

* &#x20;[#available-permissions](settings.md#available-permissions "mention")
* [#permissions](settings.md#permissions "mention")

### Transfer Category

Upon Transfer, the ticket will be moved to this category.&#x20;

### Ping Roles

Upon Transfer, these roles will be pinged in the ticket. You can select up to 25 ping roles.
