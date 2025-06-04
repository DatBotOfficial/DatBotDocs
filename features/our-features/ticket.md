---
hidden: true
icon: ticket
---

# Ticket

{% hint style="danger" %}
This documentation page is not done yet and will be completed within the next few days.
{% endhint %}

### General

The Dat Bot Ticket system allows you many customization options to give you many possibilites to use.&#x20;

### <mark style="color:red;">Namings</mark>

This page often refers to Panels, Settings / Setting(s) Models and Transfers.&#x20;

* <mark style="color:red;">Panels</mark>: Those are the <mark style="color:red;">visual representations</mark> / the ticket message. The Ticket Panel is used to give users the possibility to create a ticket. <mark style="color:blue;">Panels are usable globally</mark>.
* <mark style="color:red;">Settings / Setting Models</mark> are connected to a Panel. If the user creates a ticket, the settings are <mark style="color:red;">used to decide on permissions, ticket properties, ect.</mark> Setting Models are usable globally.
* <mark style="color:red;">Transfers</mark>: Within the Ticket, as long as it is a text channel, you have the possibility to <mark style="color:yellow;">transfer a Ticket</mark>. This is made for specific use cases, <mark style="color:blue;">for example Unban Support</mark>. In this <mark style="color:green;">fictional</mark> example, the Unban Support is used if a user is banned on <mark style="color:purple;">Twitch</mark> or <mark style="color:blue;">Discord</mark>. If the staff member is <mark style="color:red;">not</mark> able to help, they can <mark style="color:red;">transfer</mark> the Ticket to the <mark style="color:red;">Twitch Unban Staff of the Discord Server</mark>. Transfers are linked to a Settings Model and only usable on the Guild they were created on. You are able to link them to multipe Setting Models.

### From the Setup to the Ticket

### Panels

You can create a panel with the command `/ticket panel create [name]`. Provide the name to find it easier.

<div align="center"><figure><img src="../../.gitbook/assets/grafik (2).png" alt=""><figcaption></figcaption></figure></div>

* Name: Edit the name of the panel.
* Components: Configure the components (Buttons or Select Menu) of the Panel.
* Embed: Choose an embed to use for the Panel Message
* Linked: Choose Settings to be linked with the panel.

#### Components

<div align="left"><figure><img src="../../.gitbook/assets/grafik (3).png" alt=""><figcaption></figcaption></figure></div>

* View Component Type: Can either be "select" or "button"
* Component Type: Set the component type. It will choose the direct opposite.
* Selector Placeholder: This placeholder will be shown in the message. Example for "<mark style="color:green;">Create a Ticket</mark>":

<div align="left"><figure><img src="../../.gitbook/assets/Screenshot 2025-06-04 212050.png" alt=""><figcaption></figcaption></figure></div>

{% hint style="warning" %}
If the button "Manage" is disabled, check if you have any Settings. Use `/ticket settings create`!
{% endhint %}

* Manage: Manage the buttons of the panel.&#x20;

<div align="left"><figure><img src="../../.gitbook/assets/grafik (4).png" alt=""><figcaption></figcaption></figure></div>

Choose a setting model to start editing a button. You can customize the whole button.

#### Embeds

{% hint style="warning" %}
You need to create an embed for this to work. Read more: [embeds.md](embeds.md "mention")
{% endhint %}

<figure><img src="../../.gitbook/assets/grafik (5).png" alt=""><figcaption></figcaption></figure>

You can choose an embed there. After you chose an embed, you see this:



<div align="left"><figure><img src="../../.gitbook/assets/Screenshot 2025-06-04 213321.png" alt=""><figcaption></figcaption></figure></div>

* The embed will be shown there. For example, this embed just contains the title "test". Your result will be different.
  * To use the embed, click on "Use"
  * To close this menu, click on <mark style="color:purple;">Dismiss message</mark>

#### Linked Settings

{% hint style="warning" %}
You need existing Ticket Settings for this to work. Use `/ticket settings create`!
{% endhint %}

<figure><img src="../../.gitbook/assets/grafik (6).png" alt=""><figcaption></figcaption></figure>

You can select Linked Settings here. Those are used to link settings directly to a panel. Those panels will be shown as options after you click on Components > Manage and Select a setting model. If you have selected select as your component type, it will automatically be used within the select menu. If you choose the component type button, you have to customize the button first for the panel to be usable:[#components](ticket.md#components "mention")&#x20;

#### Sending the panel

To finally send the panel, use `/ticket panel send [panel]`.

<div align="left"><figure><img src="../../.gitbook/assets/grafik (7).png" alt=""><figcaption></figcaption></figure></div>

This message now contains the embed saved with [#embeds](ticket.md#embeds "mention") and the component configured with [#components](ticket.md#components "mention").

### Settings

### Transfers

### Commands

### Common Issues

### FAQ
