---
description: >-
  Dat Bot supports some games: Fortnite, Clash of Clans, Brawl Stars and
  VALORANT. You can also play TicTacToe with this command.
icon: gamepad-modern
---

# Games

{% hint style="warning" %}
The command `/games valorant matchhistory` got an update on December 31st, 2024.

* New design, support for Regen Shield and Vyse and bug fixes.
{% endhint %}

<div><figure><img src="../../.gitbook/assets/Screenshot 2024-12-31 165116.png" alt=""><figcaption><p>Old design of Players &#x26; Queues screen</p></figcaption></figure> <figure><img src="../../.gitbook/assets/Screenshot 2024-12-31 154911.png" alt=""><figcaption><p>New design of Players &#x26; Queues screen</p></figcaption></figure></div>





### Possibilities

* Fortnite: View your statistics, get the latest news, take a look at the map or get information about a store item.
* VALORANT: View information about an agent, the current version, a map, skin, weapon, playercard, spray, gamemode or season. You can also log in with `/link valorant` to view your match history and competitive rank.



### Connections

* You can find out how to connect your account under [links-connections.md](links-connections.md "mention")

## Command

## Fortnite

* `/games fortnite map [type]`
  * Receive the current map as an image.
  * Argument \[type]:
    * Blank: Does not contain POI names.
    * POI's: Displays the names of the POIs.
* `/games fortnite news`
  * Get the latest Fortnite news.
* `/games fortnite shopitem [search_language] [item]`
  * See information about a cosmetic item.
  * Argument \[search\_language]
    * The item is searched for in this language.&#x20;
    * As of February 10th, 2024, German and English are supported.
  * Argument \[item]
    * Enter the name of the store item here.
    * This option supports autocomplete. You will also receive suggestions here.
* `/games fortnite stats [username]`
  * Get the statistics of a player. This player must have public match statistics activated.
  * Argument \[username]
    * The name of the player. For example: D\_Gamet.



## Tic Tac Toe

* `/games tictactoe [difficulty] <opponent>`
  * Play Tic Tac Toe against an opponent or the AI.
  * Argument \[difficulty]
    * When you play against the AI, you can choose your difficulty level: Easy, Medium, Hard and Unbeatable.
  * Argument \<opponent>
    * Choose an opponent to play Tic Tac Toe against.
    * If you do not select an opponent, you play against the AI.



## Valorant

* `/games valorant agent [agent]`
  * Get information about a specific agent.
  * Argument \[agent]
    * This is the name of the agent.&#x20;
    * This option supports autocomplete. Suggestions are made to you.
* `/games valorant map [map]`
  * Get information about a specific map.
  * Argument \[map]
    * This is the name of the map.
    * &#x20;This option supports autocomplete. Suggestions are made to you.
* `/games valorant matchhistory`
  * The matches in your match history are displayed here. You can select one and get information about this match.
* `/games valorant rank <riot_name>`
  * Get the all-time rank and the current rank of a player.
  * Argument \<riot\_name>
    * If you have linked your account, you do not have to enter this argument.
    * If you have not linked your account, you must provide this argument. For example: DGamet#1687.
* `/games valorant version`
  * See information about the current version of the game.
* `/games valorant season [season]`
  * Get information about a season.
  * Argument \[season]
    * Select a season. This option is an autocomplete option.
* `/games valorant gamemode [gamemode]`
  * Get information about a gamemode.
  * Argument \[gamemode]
    * Select a gamemode.
* `/games valorant playercard [playercard]`
  * Get information about a playercard.
  * Argument \[playercard]
    * Select a playercard. This option is an autocomplete option.
* `/games valorant spray [spray]`
  * Get information about a spray.
  * Argument \[spray]
    * Select a spray. This option is an autocomplete option.
* `/games valorant skin [skin]`
  * Get information about a skin.
  * Argument \[skin]
    * Select a skin. This option is an autocomplete option.
* `/games valorant weapon`
  * Get information about a weapon.
  * Argument \[weapon]
    * Select a weapon.
