---
icon: shield-check
---

# Security

### Commands

* `/security suspicious_accounts`
  * This command scans the server and searches for suspicious accounts.
* `/security joingate channel [channel]`
  * Security notifications are sent in this channel. These notifications relate to users who join the server.
  * Argument  \[channel]
    * Security notifications are sent in this channel.
* `/security joingate toggle`
  * Activate or deactivate the system. If the system is deactivated, the system notifications are not sent.
* `/security joingate minage [days]`
  * If accounts that join the server fall below this account age, a notification is sent.
  * Argument \[days]
    * This is the account age in days
