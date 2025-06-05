---
icon: ticket
---

# Panels

### General

<mark style="color:red;">Panels</mark>: Those are the <mark style="color:red;">visual representations</mark> / the ticket message. The Ticket Panel is used to give users the possibility to create a ticket. <mark style="color:blue;">Panels are usable globally</mark>.&#x20;

Example:&#x20;

<div align="left"><figure><img src="../../../.gitbook/assets/grafik (3).png" alt=""><figcaption></figcaption></figure></div>

### Manage Panel

Create a Panel using `/ticket panel create [name]`, edit an existing panel using `/ticket panel edit [panel]`

<div align="left"><figure><img src="../../../.gitbook/assets/grafik (2) (1).png" alt=""><figcaption></figcaption></figure></div>

### Name

Manage the short name of the Panel.

### Components

<div align="left"><figure><img src="../../../.gitbook/assets/grafik (3) (1).png" alt=""><figcaption></figcaption></figure></div>

* View Component Type: Can either be "select" or "button"
* Component Type: Set the component type. It will choose the direct opposite.
* Selector Placeholder: This placeholder will be shown in the message. Example for "Create a Ticket":

### Manage Button Components

<div align="left"><figure><img src="../../../.gitbook/assets/grafik (4) (1).png" alt=""><figcaption></figcaption></figure></div>

Choose a setting model to start editing a button. You can customize the whole button.

Buttons are attached to a setting model. Click on "Choose a setting model", after that you are able to manage the button.

### Embed

You can choose an embed there. After you chose an embed, you see this:

<figure><img src="../../../.gitbook/assets/grafik (6).png" alt=""><figcaption></figcaption></figure>

You can choose an embed there. After you chose an embed, you see this:

<div align="left"><figure><img src="../../../.gitbook/assets/Screenshot 2025-06-04 213321.png" alt=""><figcaption></figcaption></figure></div>

* The embed will be shown there. For example, this embed just contains the title "test". Your result will be different.
  * To use the embed, click on "Use"
  * To close this menu, click on <mark style="color:purple;">Dismiss message</mark>

### Linked Settings

{% hint style="warning" %}
You need existing Ticket Settings for this to work. Use `/ticket settings create`!
{% endhint %}

<figure><img src="../../../.gitbook/assets/grafik (6).png" alt=""><figcaption></figcaption></figure>

You can select Linked Settings here. Those are used to link settings directly to a panel. Those panels will be shown as options after you click on Components > Manage and Select a setting model. If you have selected select as your component type, it will automatically be used within the select menu. If you choose the component type button, you have to customize the button first for the panel to be usable:[#components](panels.md#components "mention")&#x20;

### Sending the panel

To finally send the panel, use `/ticket panel send [panel]`.

<div align="left"><figure><img src="../../../.gitbook/assets/grafik (7).png" alt=""><figcaption></figcaption></figure></div>

This message now contains the embed saved with [#embeds](panels.md#embeds "mention") and the component configured with [#components](panels.md#components "mention").
