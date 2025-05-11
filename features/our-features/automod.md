---
description: Automod is a new feature added on October 26, 2024.
icon: lightbulb
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
---

# Automod

### Information

#### Nickname Automod

* This Automod uses the built-in Discord Automod for Usernames. Read more about the Discord Automod here: [https://support.discord.com/hc/en-us/articles/4421269296535-AutoMod-FAQ](https://support.discord.com/hc/en-us/articles/4421269296535-AutoMod-FAQ)

### Permissions

* <mark style="color:red;">Required</mark> permission for `/automod nicknames`: <mark style="color:red;">Manage Guild</mark> or <mark style="color:red;">Administrator</mark>

### Commands

`/automod nicknames add_allowed_role`` `<mark style="color:purple;">`[role]`</mark>

* Adds a role to the Allowlist. Users with this role are not monitored.
* Argument <mark style="color:purple;">\[role]</mark>
  * This role will be added into the filter.

`/automod nicknames addname`` `<mark style="color:purple;">`[name]`</mark><mark style="color:orange;">`[type]`</mark>

* Adds a provided <mark style="color:purple;">name</mark> to the filter.&#x20;
* Argument <mark style="color:purple;">\[name]</mark>
  * This name will be added to the filter.
* Argument <mark style="color:orange;">\[type]</mark>
  * Choose the type of disallowance:
    * Disallow completely
    * The name must not start with the provided <mark style="color:purple;">name</mark>
    * The name must not end with the provided <mark style="color:purple;">name</mark>
    * The user name must be exactly the <mark style="color:purple;">name</mark> specified

`/automod nicknames allowlist`

* Shows all roles which are on the Allowlist.

`/automod nicknames list`

* Shows all names in the filter.

`/automod nicknames logchannel`` `<mark style="color:purple;">`[channel]`</mark>

* Sets the logging channel to a specific channel. If the filter catches a result it will send information into the channel.
* Argument <mark style="color:purple;">\[channel]</mark>
  * This channel will be the channel the information will be sent in

`/automod nicknames remove_allowed_role`` `<mark style="color:purple;">`[role]`</mark>

* Removes a role from the Allowlist.
* Argument <mark style="color:purple;">\[role]</mark>
  * This role will be removed from the Allowlist.

`/automod nicknames removelogging`

* Removes the logging channel.

`/automod nicknames removename`` `<mark style="color:purple;">`[name]`</mark><mark style="color:orange;">`[type]`</mark>

* Removes a provided <mark style="color:purple;">name</mark> from the filter.&#x20;
* Argument <mark style="color:purple;">\[name]</mark>
  * This name will be removed from the filter.
* Argument <mark style="color:orange;">\[type]</mark>
  * Choose the type of disallowance:
    * Disallow completely
    * The name must not start with the provided <mark style="color:purple;">name</mark>
    * The name must not end with the provided <mark style="color:purple;">name</mark>
    * The user name must be exactly the <mark style="color:purple;">name</mark> specified

`/automod nicknames toggle`

* Enable or disable the filter. It will <mark style="color:red;">NOT</mark> delete any data.

