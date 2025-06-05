---
icon: ticket
---

# Settings

### General

Settings / Setting Models are connected to a Panel. If the user creates a ticket, the settings are used to decide on permissions, ticket properties, ect. Setting Models are usable globally. Those are attached to Panels ([panels.md](panels.md "mention")) and used to dertermine the ticket settings, for example the ticket name, ect.

You can use settings across multiple servers. You will have to set server-specific data like ticket transcript channel or the opening category in every server you are using newly, but global settings like the ticket limit per user or ticket name don't have to be newly applied.

### Global and Server-specific data

{% tabs %}
{% tab title="Server-specific" %}
* Custom Permissions
* Transfers
* Open Category
* Closed Category
* Required Roles
* Roles to mention
* Log Channel
* Transcript Channel
* Thread Creator Channel
{% endtab %}

{% tab title="Global" %}
* Name
* Modal
* Maximum tickets
* Emoji
* Opening Embed
* Ticket name
* Channel type
* Auto Claim
* Only One Mode
* Feedback
* Blocking
{% endtab %}
{% endtabs %}
