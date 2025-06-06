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

### Available Permissions

* 🔴 Admin: Includes all other permissions
* 🟡 Only One Mode Bypass: If enabled, the user with the role still won't be affected by the only one mode. What the Only One Mode is: [#only-one-mode](concepts.md#only-one-mode "mention")
* 🟡 Block: Block users for this category. The user won't be able to create new tickets for this category. To block users globally, check [commands.md](commands.md "mention").
* 🟡 Delete: Delete the ticket.
* 🔵 Claim: Claim and Unclaim the ticket. This permission is required to use Autoclaim. What Autoclaim is: [#autoclaim](concepts.md#autoclaim "mention")
* 🔵 Open: Open the Ticket
* 🔵 Close: Close the Ticket
* 🔵 Close Request: Send a Close Request to the user.
* 🔵 View: View the ticket and Read Message History.&#x20;
* 🔵 Info: View ticket information by using the command or clicking on the "Info" button in the Ticket.
* 🔵 Transcript: Generate a Transcript.

### Creating Settings

Create settings with `/ticket settings create` . The \[name] is the display name of the settings.

<figure><img src="../../../.gitbook/assets/grafik (9).png" alt=""><figcaption></figcaption></figure>

### Changing the name

The name is the display name of the settings. Change it by clcking on "Name".

### Permissions

Dat Bot uses a custom permission system.&#x20;

To view the permissions, click on "View", to reset all permissions, click on "Reset". Reset only resets the permissions for the server you are editing the settings on.

These custom permissions are attached to a role. Select a role in the select menu to add permissions:

<figure><img src="../../../.gitbook/assets/grafik (10).png" alt=""><figcaption></figcaption></figure>

After selecting a role, you can choose permissions ([#available-permissions](settings.md#available-permissions "mention")) by selecting choices in the select menu.&#x20;

<figure><img src="../../../.gitbook/assets/grafik (11).png" alt=""><figcaption></figcaption></figure>

After selecting permissions, click on "Save" to save the settings. Click on "Reset" to reset your selection.



### Transfers

{% hint style="info" %}
Read more here: [transfers.md](transfers.md "mention")
{% endhint %}

{% hint style="warning" %}
Even tho Settings are usable globally, Transfers are server-specific.
{% endhint %}

<figure><img src="../../../.gitbook/assets/grafik (13).png" alt=""><figcaption></figcaption></figure>

Click on "View" to view the current transfers used in the settings. Click on "Reset" to reset the used Transfers.

Select Transfers down below. They will be usable in a created ticket by clicking on "Choose a tool"..-

<figure><img src="../../../.gitbook/assets/grafik (14).png" alt=""><figcaption></figcaption></figure>

&#x20;... and "Transfer".

<figure><img src="../../../.gitbook/assets/grafik (15).png" alt=""><figcaption></figcaption></figure>

Then choose a transfer and the bot will transfer the ticket.

<figure><img src="../../../.gitbook/assets/grafik (16).png" alt=""><figcaption></figcaption></figure>

### Modal

{% hint style="info" %}
Information about about Modals here: [#modal](concepts.md#modal "mention")
{% endhint %}

Click on "Modal" to manage the modal.

<figure><img src="../../../.gitbook/assets/grafik (17).png" alt=""><figcaption></figcaption></figure>

* Click on "Add" to add a modal field.&#x20;
* Click on "View" to view the modal.
* Click on "Title" to edit the Modal Title.
* Click on "Reset" to reset the modal.
* To remove a modal field, select a field by using "Remove a modal field".



### Adding a Modal Field

{% hint style="info" %}
How to access a modal field value: [#how-do-i-access-a-modal-field-value-within-the-opening-embed](general-faq.md#how-do-i-access-a-modal-field-value-within-the-opening-embed "mention")
{% endhint %}

<figure><img src="../../../.gitbook/assets/grafik (18).png" alt=""><figcaption></figcaption></figure>

* Custom ID: This is basically the identifier of the modal field. Used in the embed placeholder to access the value.
* Label: [#modal](concepts.md#modal "mention")
* Placeholder: [#modal](concepts.md#modal "mention")
* Required: Whether the input of the user is required or not. If nothing is input, "No data" will be returned.

### Categories

Click on "Categories" to manage the categories.&#x20;

The "Standard category" is the category used upon creation. To reset the category click on the first "Reset" button.\
The "Closed category" is the category used upon closing. To reset the category, click on the second "Reset" button.

<figure><img src="../../../.gitbook/assets/grafik (19).png" alt=""><figcaption></figcaption></figure>

### Manage Settings

Click on "Settings" to manage the settings.

<figure><img src="../../../.gitbook/assets/grafik (20).png" alt=""><figcaption></figcaption></figure>

* Maximum tickets: Maximum amount of tickets per user for this category
* Emoji: Emoji used to display in a select menu
* Opening Embed: Works exactly like [#embed](panels.md#embed "mention"). This embed is used in the first message written in the newly created ticket.
* Required Roles: Roles required to open a ticket.
* Ticket name: Name of the ticket
* Channel type: Can either be thread or text channel
* Autoclaim: Enable or disable Autoclaim ([#autoclaim](concepts.md#autoclaim "mention"))
* Only One Mode: Enable or disable Only One Mode ([#only-one-mode](concepts.md#only-one-mode "mention"))
* Feedback: Enable or disable feedback: ([#feedback](concepts.md#feedback "mention"))
* Blocking: Edit the blocks of the category
* "Choose roles to mention...": Choose roles to mention upon ticket creation
* "Log Channel": Log all actions in this channel.
* "Transcript Channel": Send transcripts automatically in this channel
* "Thread Creator Channel": If the channel type is set to thread, a thread will be created with this parent channel.

### Required Roles

Click on Settings > Required Roles to manage the required roles.

<figure><img src="../../../.gitbook/assets/grafik (21).png" alt=""><figcaption></figcaption></figure>

* Type: Set whether all required roles or one required role is required to open a ticket
* View: View the type and the required roles
* Reset: Reset the required roles and the Required Type
* "Required Roles": Select your required roles

### Blocking

Click on Settings > Blocks to manage the blocks.

<figure><img src="../../../.gitbook/assets/grafik (22).png" alt=""><figcaption></figcaption></figure>

* View: Click on "View" to view all blocked users for this server.
* Reset: Click on "Reset" to reset all blocked users for this server.
* "Block a user": Block a user for this category on this server
* "Unblock a user": Remove a block of the provided user for this server
