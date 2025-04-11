---
layout: default
---

Participating in the community for [Root](https://ledergames.com/products/root-a-game-of-woodland-might-and-right) led me to encountering some of the rough edges in the game's design, and/or its implementation on Tabletop Simulator.
These projects are my attempt to improve quality-of-life for the TTS playerbase. Many of these tools were directly integrated into the most popular TTS mod for the game by the mod creators.

## Lizard Wizard

The game's "Lizard Cult" faction revolves around a secondary discard pile that takes priority over the normal one. While this becomes mechanically interesting, it demands that all
players at the table constantly hand discarded cards across the table to the Lizard player rather than the comfortable central placement of the normal discard pile.
Moreover, the faction's mechanics rely on the the _number_ of each card suit in their pile, creating issues with visibility that require frequent deck-searches.

The [Lizard Wizard](https://steamcommunity.com/sharedfiles/filedetails/?id=2302408180) is a spawnable object that comfortably sits beside the normal discard pile in the centre of the table.
It also features a scripted counter to show the number of each discarded card suit, as well as a tracking token for the Lizard faction's related functionality.

![Lizard wizard](https://images.steamusercontent.com/ugc/1777200862706714441/5F8E2832548EF5A4DD1AD827F05E0749CF5959F9/?imw=5000&imh=5000&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false)

## Mole Monger

The [Mole Monger Minister Manager](https://steamcommunity.com/sharedfiles/filedetails/?id=2366650442) is a spawnable object for the "Underground Duchy" faction, which makes use of a
suite of nine "ministers" that can be gained and lost through gameplay. The original game handles these through a deck of cards, which can be onerous to manage in TTS.

This mod has clickable UI elements which toggle the status of each minister, as well as clickable "Crowns" to show how many ministers of each type you've already unlocked.

![Mole Monger](https://images.steamusercontent.com/ugc/1777201099846226954/50220014BEA990B1C32D24FD0B2D434B1A5286AF/?imw=5000&imh=5000&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false)

## Koffin Keeper

The [Koffin Keeper](https://steamcommunity.com/sharedfiles/filedetails/?id=2373868841) is a spawnable object designed for use with the "Exiles and Partisans" deck. In this deck, the card "Coffin Makers"
requires all players to store destroyed meeples atop the card until its owner's turn, when they are exchanged for points at a rate of 5:1.

Prior to this mod, the most common way of handling this interaction on TTS was to duplicate the card and enlarge it, placing it near the center of the table. 
Forgetting to duplicate the card first meant you could no longer return the card to the deck without odiously resizing it to match the others. The card art also tended to hide certain
meeples of similar colour.

The Koffin Keeper can be toggled between an open & closed state, and automatically counts the point value for the number of meeples contained within it.
The coffin model was sourced from [used "Desca" on steam](https://steamcommunity.com/sharedfiles/filedetails/?id=720881721&searchtext=coffin), and I modified it in blender to better accommodate meeples.

![Koffin Keeper](https://images.steamusercontent.com/ugc/1777201711984133992/E94E79522F01029269F7C075E8C2899F8D473A32/?imw=5000&imh=5000&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false)

## Mob Lobber

The [Mob Lobber Rolling mat](https://steamcommunity.com/sharedfiles/filedetails/?id=2676414604) is designed for use with the "Lord of the Hundreds" (AKA: Warlord) faction, which places
'mob' tokens that randomly spread across the map via a specialized dice.

In TTS, this specialized dice can be hard to read, is small by default, and waiting for physics behaviours is slow. This mod condenses that functionality into a one-click "Rolling mat",
which randomly selects suits alongside a jaunty rolling animation (and sound effects from _Mario Kart_.)

<iframe width="560" height="315" src="https://www.youtube.com/embed/YMjl7drN-IU?si=cjQbwVPeYlicKSdA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

[back](./)
